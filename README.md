# challenge-telecom-x


# 📊 Análise de Churn de Clientes

Este projeto tem como objetivo analisar o comportamento de clientes e identificar padrões relacionados à evasão (**churn**) em uma base de dados.  
A análise segue um fluxo de **ETL + EDA** estruturado em quatro etapas:

1. **Extração** – Leitura e carregamento dos dados brutos.  
2. **Transformação** – Limpeza, padronização e tratamento de colunas.  
3. **Carga e Análise (EDA)** – Cálculo de métricas descritivas, estatísticas e geração de visualizações.  
4. **Relatório Final – Insights** – Interpretação dos resultados e recomendações estratégicas.

---

# 📊 Métricas e Visualizações

A análise inclui:

Distribuição do churn – proporção de clientes que permanecem x saem

Métricas numéricas agrupadas por churn – média, mediana e desvio padrão de tenure, MonthlyCharges e TotalCharges

Distribuição de variáveis categóricas – como gênero, tipo de contrato e método de pagamento

Visualizações – gráficos de barras, pizza e histogramas para identificar padrões

# 💡 Principais Insights
Clientes que cancelam permanecem menos tempo na empresa (média ~18 meses vs. 38 meses).

Planos com mensalidade mais alta apresentam maior taxa de churn.

A evasão é mais comum nos primeiros anos de contrato, exigindo estratégias de retenção precoce.

# 🛠 Tecnologias Utilizadas
Python 3.9+

Pandas – Manipulação e análise de dados

Matplotlib / Seaborn – Visualização gráfica

Jupyter Notebook – Prototipagem e documentação do fluxo

