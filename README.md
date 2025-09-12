# Data_Science
Olá! Bem-vindo ao meu portfólio de projetos de análise de dados.  Aqui eu demonstro minhas habilidades em Python, SQL, e ferramentas de BI para transformar dados em insights.

# 📊 Projeto de Análise de Vendas | E-commerce Olist

## 🔗 Link para o Projeto

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PLXn3dQD0mLLD22KxQnHfyDIQ_wSG5pG?usp=sharing)

## 🎯 Objetivo

Realizar uma análise exploratória de dados (EDA) sobre o dataset público da Olist, disponível no Kaggle, para extrair insights estratégicos sobre as operações de vendas entre 2016 e 2018. O projeto busca responder a três perguntas de negócio fundamentais:
1.  **Perfil Geográfico:** Qual a distribuição dos clientes pelo Brasil?
2.  **Análise Temporal:** Qual a evolução das vendas ao longo do tempo e quais os períodos de maior sazonalidade?
3.  **Perfil de Produtos:** Quais as categorias de produtos mais vendidas pela plataforma?

## 🛠️ Ferramentas e Técnicas

* **Linguagem:** Python
* **Bibliotecas:** Pandas (para limpeza, tratamento e manipulação dos dados), Matplotlib e Seaborn (para visualização de dados).
* **Ambiente:** Google Colaboratory (Notebooks Jupyter na nuvem).
* **Técnicas:** Limpeza de Dados, Tratamento de Valores Nulos, Conversão de Tipos de Dados, Feature Engineering, Análise Exploratória de Dados (EDA), Visualização de Dados.

## 📈 Principais Descobertas

* **Concentração no Sudeste:** A análise geográfica revelou que mais de 40% dos clientes estão concentrados no estado de São Paulo, evidenciando a importância da região Sudeste para o negócio.
* **Impacto da Black Friday:** Foi identificada uma clara tendência de crescimento nas vendas ao longo do período, com um pico significativo em novembro de 2017, confirmando a Black Friday como o evento comercial mais importante para a empresa.
* **Domínio de "Casa e Bem-Estar":** A categoria "cama_mesa_banho" lidera as vendas com grande margem, seguida por "beleza_saude" e "esporte_lazer", caracterizando a Olist como um marketplace com forte perfil em produtos para o lar e bem-estar pessoal.

# 📊 Projeto de Análise de Teste A/B

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1W9k9P92M1MZX1jUbFV0xcxPOHPFmiTOb?usp=sharing)

## 🎯 Contexto do Projeto
Análise de um teste A/B realizado por uma empresa de marketing digital. O objetivo é determinar se uma nova campanha de propaganda (PSA) gera uma taxa de conversão superior à campanha antiga (AD) e fornecer uma recomendação de negócio baseada em dados.

## 🛠️ Tecnologias Utilizadas
- Python
- Pandas (para manipulação de dados)
- Matplotlib e Seaborn (para visualização)
- SciPy (para o teste estatístico)
- Google Colab (como IDE)

## 📂 Fonte dos Dados
O dataset utilizado está disponível publicamente no Kaggle: [Marketing A/B Testing Dataset](https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing).

## 📊 Resultados e Conclusão
A análise visual e o teste de hipóteses (Qui-Quadrado) demonstraram que a campanha antiga possui uma performance superior.

<img width="850" height="630" alt="download" src="https://github.com/user-attachments/assets/91992964-810d-4715-aa8d-d1c445cadb55" />

* **Taxa de Conversão da Propaganda Antiga (AD):** 2.55%
* **Taxa de Conversão da Propaganda Nova (PSA):** 1.79%

O p-valor resultante do teste foi significativamente menor que o nível de significância de 5%, confirmando que esta diferença não é fruto do acaso.

### Recomendação Final
**A recomendação de negócio é não implementar a nova campanha de marketing (PSA).** A análise indica que a campanha antiga é mais eficaz e sua substituição resultaria em uma provável queda na taxa de conversão.

## 🚀 Como Executar o Projeto
Para visualizar e executar a análise completa, clique no botão "Open in Colab" no topo deste arquivo.

🚀 Projeto: Análise de Sentimentos de Reviews de Apps

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ftEpoLryasXDFMqeTiIdmy19mVpNHhRa?usp=sharing)

📖 Descrição
Este projeto realiza uma análise de sentimentos de ponta a ponta em um dataset público com mais de 35.000 reviews de aplicativos da Google Play Store. O objetivo é transformar milhares de comentários de texto não estruturado em insights visuais e acionáveis, culminando em um dashboard interativo que poderia ser usado por equipes de produto para entender a percepção do usuário.

🛠️ Ferramentas e Tecnologias
⚙️ Fluxo do Projeto
O projeto foi estruturado em um pipeline de dados claro e automatizado:

Coleta e Limpeza dos Dados: Carregamento dos datasets (apps.csv e user_reviews.csv), limpeza de dados corrompidos e nulos, e junção das duas fontes.

Pré-processamento de Texto (NLP): Aplicação de técnicas de Processamento de Linguagem Natural para padronizar os reviews, incluindo conversão para minúsculas, remoção de pontuação e de stopwords.

Análise Exploratória de Dados (AED): Análise de frequência de palavras (unigramas) e pares de palavras (bigramas) para identificar os temas mais discutidos pelos usuários, separando-os por sentimento (Positivo vs. Negativo).

Engenharia de Dados e Automação: Construção de um pipeline automatizado onde o script Python no Google Colab processa e agrega os dados de análise e os envia diretamente para uma Planilha Google através da API, servindo como uma fonte de dados "viva" para o dashboard.

Visualização de Dados: Desenvolvimento de um dashboard interativo no Looker Studio, com um layout estratégico para contar a história dos dados, desde uma visão geral até os insights mais detalhados.

💡 Principais Insights
A análise revelou padrões claros no feedback dos usuários:

Pontos Fortes (Reviews Positivos): Os elogios mais comuns estão diretamente relacionados à experiência de uso e ao propósito principal dos apps, com termos como "love game", "great app" e "easy use" se destacando.

Pontos Fracos (Reviews Negativos): As reclamações se concentram majoritariamente em problemas de monetização e performance. "Many ads" (muitos anúncios) foi o tema negativo mais recorrente, seguido de bugs e pedidos de correção ("please fix").

Temas Controversos: Palavras como "update" aparecem em ambos os contextos, e o gráfico de comparação de sentimentos mostra o balanço entre usuários que amaram e odiaram as novas atualizações.

🖥️ Dashboard Final
O resultado final é um dashboard limpo e interativo que resume todas as descobertas da análise.

✨ Ver Dashboard Interativo (Looker Studio) <- https://lookerstudio.google.com/reporting/3f697291-30a4-4d8f-839f-ff85caa99df9

<img width="1105" height="845" alt="Captura de tela de 2025-09-12 10-36-07" src="https://github.com/user-attachments/assets/663409d8-0226-42d6-8994-d3fe72f770a3" />






