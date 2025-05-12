# 🧹 Limpeza de Dados de Vendas no Varejo

Este projeto tem como objetivo realizar a limpeza e preparação de uma base de dados simulada de vendas no varejo, corrigindo inconsistências, valores ausentes e formatos inadequados.

📂 **Dados Utilizados**  
- Dataset original: `retail_sales_dirty.csv`  
- Fonte: Kaggle – Retail Store Sales (Dirty for Data Cleaning)  
- Registros: ~12.000  
- Colunas: Data da Venda, Produto, Categoria, Preço, Quantidade, Cliente, entre outras.

🎯 **Objetivos de Limpeza**  
- Correção de valores nulos  
- Conversão da coluna de data para datetime  
- Validação de cálculos derivados (ex: Total Spent)  
- Padronização estrutural para análises futuras

✔️ **Etapas Realizadas**  
- Remoção de registros com campos críticos ausentes (`Item`, `Price Per Unit`, `Quantity`)  
- Preenchimento lógico de campos booleanos (`Discount Applied`)  
- Conversão da coluna de data para formato datetime  
- Criação e validação da coluna `Total Spent Calculado`  
- Exportação final como `retail_sales_cleaned.csv`

🛠️ **Ferramentas Utilizadas**  
- Python  
- Pandas  
- VS Code + Jupyter Notebook (`.ipynb`)

📓 O processo completo está documentado no notebook: [data_cleaning_retail_sales.ipynb](./data_cleaning_retail_sales.ipynb)

🧼 Resultado final: [retail_sales_cleaned.csv](./retail_sales_cleaned.csv)

---

👤 **Autor**  
Matheus Nunes Cardoso  
📬 mtsnunescardoso@gmail.com
