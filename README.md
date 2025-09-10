# Data_Science
Olá! Bem-vindo ao meu portfólio de projetos de análise de dados.  Aqui eu demonstro minhas habilidades em Python, SQL, e ferramentas de BI para transformar dados em insights.

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
