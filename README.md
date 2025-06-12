# 📊 Grupo Varejo Brasil – Análise de Vendas

Projeto de análise de dados desenvolvido como parte do curso de Power BI da EBAC. O objetivo é explorar e visualizar informações de vendas do Grupo Varejo Brasil, com foco em produtos, categorias, comportamento de compra e perfil dos clientes.

## 🔍 Objetivo

Realizar uma análise de vendas por produto e departamento, identificar padrões de compra e gerar insights úteis para tomada de decisão em um contexto de varejo nacional.

---

## 🧾 Sobre os dados

Os dados foram fornecidos no curso e simulam transações reais de uma grande empresa de varejo. As informações estão divididas em múltiplas tabelas, relacionadas por meio do número do pedido (`NroPedido`).

### Exemplos de colunas:

- **Departamentos**:
  - `CodDepto`: Código do departamento
  - `DescDepto`: Descrição (ex: Celulares, Eletrodomésticos, Games)

- **Pedidos**:
  - `NroPedido`: Número único de cada pedido
  - `DataPedido`: Data da compra
  - `FormaDePagamento`: Ex: Crédito, Débito
  - `CondicaoPagamento`: Ex: Parcelado

- **Itens do Pedido**:
  - `CodProduto`: Código do produto
  - `Quantidade`: Número de itens vendidos
  - `ValorUnitario`: Preço unitário do produto
  - `ValorDescontoItem`: Desconto aplicado

- **Clientes** (informações anonimizadas):
  - `Variavel`: Sexo ou faixa etária
  - `Valor`: Ex: “25-34”, “M”

---

## 🛠️ Ferramentas utilizadas

- **Power BI Desktop** – Para modelagem dos dados, criação de medidas DAX e dashboards interativos
- **Power BI Service** – Para publicação e compartilhamento dos relatórios
- **Excel** – Para visualização e inspeção inicial dos dados

---

## 📈 Resultados

O relatório foi dividido em páginas temáticas, com os seguintes destaques:

- **Vendas por Mês**: evolução das vendas ao longo do tempo  
- **Ranking por Departamento**: desempenho por categoria de produto  
- **Ranking por Região**: vendas segmentadas geograficamente  
- **Análise de Departamentos (Top 3)**: foco nos três departamentos com maior faturamento  
- **Meta de Vendas**: comparação entre vendas realizadas e metas estabelecidas  
- **Variação Mensal de Vendas**: análise das oscilações mensais no volume de vendas  
- **Relatório Gerencial**: visão consolidada com indicadores e um gráfico de dispersão para análise comparativa entre departamentos

---

## 📄 Visualização do Projeto

🖥️ Acesse o dashboard interativo publicado no Power BI Online:  
👉 [Clique aqui para visualizar o relatório](https://app.powerbi.com/view?r=eyJrIjoiYWI0ZDZhZGMtMTQ1OC00N2UwLTgwNTgtZjg2MzkzY2NmZjYxIiwidCI6ImU4Y2YyNjM5LTFmOTgtNGJiNC1iZDg5LWFiZDE0OTI4OTM3ZiJ9)

📎 Ou, se preferir, veja a versão em PDF:  
[Relatório em PDF](./GRUPO VAREJO BRASIL.pdf)

---

## 💡 Aprendizados

Este projeto reforçou habilidades em:

- Limpeza e modelagem de dados no Power BI
- Criação de relacionamentos entre tabelas
- Criação de medidas DAX para KPIs de vendas
- Visualização de dados com foco em insights de negócio
- Publicação e documentação de projetos no GitHub

---

## 📬 Contato

Caso tenha interesse em conversar sobre o projeto ou colaborar:

**[Luiz Felipe]**  
[LinkedIn](https://www.linkedin.com/in/luiz-felipe-gomes-de-carvalho-dataanalytics/) • [GitHub](https://github.com/luizzfelipeh)  

---

> Projeto desenvolvido como parte do curso de formação de Analista de Dados da [EBAC](https://ebaconline.com.br).
