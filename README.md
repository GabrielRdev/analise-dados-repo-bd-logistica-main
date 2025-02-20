# Análise de Entrega de Produtos no Google Colab

Este projeto utiliza o Google Colab para analisar os dados de entregas de produtos de uma empresa de Logística.

## Contexto

Determinada empresa está com alguns problemas com seus motoristas, os produtos e suas entregas. Além disso, esta empresa não possui informações relevantes que possam ajuda-la a resolver este problema.
Com isso, este projeto é responsável por auxiliar esta empresa de Logística a mapear o que tem dado errado com seu negócio.
A base de dados está em arquivo CSV com informações relevantes e com isso será possível verificar insights valiosos para o Gestor conseguir tomar decisões acertivas baseado em análise dos dados.

- Carregamento da base de dados do arquivo CSV para o Google Colab
  ![](./img/carga-base-dados.png)

- Tratamento dos dados
  ![](./img/tratamento-dados.png)

- Depois de carregar e tratar os dados, é possível gerar métricas para a empresa

  ![](./img/total-faturamento.png)

![](./img/qtd-motoristas.png)

![](./img/qnt-devolucao-por-mot.png)

![](./img/motivos-dev.png)

![](./img/motivos-dev-por-motorista.png)

![](./img/qnt-produtos-status.png)

![](./img/mot-atrasados-entrega.png)

Com isso, o objetivo deste projeto é verificar insights para auxiliar o Gestor da empresa a tomar uma decisão acertiva,
baseada na análise e visualização dos dados.

## Descrição

O projeto está dividido em:

- Analisar e transformar os dados com código Python e suas bibliotecas; e
- Visualizações dos dados em formato de tabela e gráfico.

## Tecnologias

- Google Colab
- Python
- Pandas
- Matplotlib
- Seaborn

## Como Rodar o Projeto no Google Colab

1. **Abrir o Notebook no Google Colab**: Clique no link abaixo para abrir o notebook diretamente no Google Colab:
   [Abrir no Google Colab] (https://colab.research.google.com/drive/1Q5VppeAhTqz1sqq732usRLHuRdTlovV2

2. **Executar as Células**: Clique em "Runtime" > "Run all" para rodar o código do notebook. Você pode rodar as células uma por uma clicando em cada célula e pressionando Shift + Enter.

3. **Verifique os Resultados**: O notebook irá gerar gráficos e modelos preditivos, exibidos diretamente no Colab.

## Contribuindo

Contribuições são bem-vindas!
Sinta-se à vontade para contribuir com melhorias, correções ou novas funcionalidades.Para isso, por favor:

- Faça um fork do repositório
- Crie uma branch para a sua modificação (git checkout -b nova-funcionalidade)
- Commit suas alterações (git commit -am 'Adicionando nova funcionalidade')
- Envie para o repositório original (git push origin nova-funcionalidade)
- Abra um pull request
