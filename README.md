# Análise de Exportações do Brasil para a França

## Objetivo

Este repositório tem como objetivo analisar as exportações do Brasil para a França a partir de um arquivo chamado `exportacao_full.csv`, que contém dados de exportação do Brasil para diversos países.

## Etapas

### 1. Filtragem dos Dados

A primeira etapa do projeto é filtrar os dados do arquivo `exportacao_full.csv` e salvar em um novo dataframe `exportacoes_franca.csv` todas as informações relativas às exportações para a França, a partir de 2016.

### 2. Questões a Serem Respondidas

Após a filtragem dos dados, as seguintes perguntas serão respondidas:

1. **Quantas linhas têm a tabela? Existe algum valor vazio que deveria ser tratado?**
2. **Como foi a evolução das exportações para a França ao longo dos anos?**
3. **Quais os produtos mais exportados ao longo de todo o período?**
4. **Em 2020, qual cidade mais exportou para a França?**
5. **Quais os produtos mais exportados (em US$) que as 2 maiores cidades (em exportação em 2020) exportaram?**

## Estrutura do Repositório

- `exportacao_full.csv`: Arquivo original com os dados de exportação do Brasil para diversos países.
- `exportacoes_franca.csv`: Arquivo filtrado com dados de exportação do Brasil para a França a partir de 2016.
- `filtrar_dados.ipynb`: Script para filtrar os dados do arquivo original.
- `index.ipynb`: Script contendo as análises para responder às perguntas, assim com os gráficos gerados.
- `README.md`: Este arquivo.

## Downloads

- O arquivo `exportacao_full.csv` foi originalmente baixado do site 'kaggle' => 'https://www.kaggle.com/datasets/hugovallejo/brazil-exports' , o mesmo não foi adicionado ao github pelo limite de upload (100 MB)

## Próximas etapas:

- Implementar alguns gráficos com matplotlib;
- Colocar o dataset em uma pasta assets;
- Colocar mais análises após cada seção/pergunta/
- Ver sobre series temporais - associar análise do tempo
- Fazer análise da importação de cada estado?
- Tentar analisar os gráficos, e justificar valores por conta de acontecimentos no ano? Por exemplo: Pandemia;
- Ver subplots;
- Tentar descrever outliers (usando bloxplot) e o que torna cada um deles outliers;
