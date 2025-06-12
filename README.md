📦 CTE Recursiva para Análise de Valor de Estoque nos Últimos 12 Meses
Este projeto demonstra o uso de uma CTE Recursiva (Common Table Expression) no SQL Server para realizar a análise do valor do estoque ao final de cada um dos últimos 12 meses.

🧠 O que é uma CTE Recursiva?
Uma CTE Recursiva permite criar um conjunto de dados que se autoalimenta — ideal para gerar sequências, estruturas hierárquicas ou, neste caso, uma lista de períodos mensais.
Ela é composta por duas partes:

Anchor Member (ponto de partida)

Recursive Member (a repetição incremental)

🎯 Objetivo
Calcular o valor total do estoque ao último dia de cada um dos últimos 12 meses, usando:

A função EOMONTH para obter o último dia do mês

Uma CTE recursiva para gerar os períodos automaticamente

Junção com a tabela de estoque real

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gustavo-barbosa-868976236/) [![Email](https://img.shields.io/badge/Email-gustavobarbosa7744@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gustavobarbosa7744@gmail.com)
