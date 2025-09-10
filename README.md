# Data_Science
Olá! Bem-vindo ao meu portfólio de projetos de análise de dados.  Aqui eu demonstro minhas habilidades em Python, SQL, e ferramentas de BI para transformar dados em insights.

# Projeto de Análise de Vendas | E-commerce Olist

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

## 🔗 Link para o Projeto

* **[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PLXn3dQD0mLLD22KxQnHfyDIQ_wSG5pG?usp=sharing).**

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
