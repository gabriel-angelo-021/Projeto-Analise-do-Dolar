# 💵 Projeto — Análise da Cotação do Dólar

## 📊 Sobre o projeto

Este projeto tem como objetivo realizar uma análise exploratória da cotação do dólar ao longo de um determinado período, utilizando dados obtidos por meio da API do Banco Central do Brasil (BACEN).

A análise foi desenvolvida utilizando Python e bibliotecas voltadas para manipulação, tratamento, análise estatística e visualização de dados.

O projeto foi desenvolvido com foco em transformar dados brutos de cotação em informações que possam ser facilmente interpretadas por meio de estatísticas e visualizações.

Durante o desenvolvimento foram realizadas etapas de:

- coleta dos dados;
- armazenamento em arquivo CSV;
- exploração da base;
- tratamento dos dados;
- validação da qualidade dos dados;
- análise estatística;
- análise temporal;
- criação de visualizações;
- interpretação dos resultados;
- documentação do projeto.

---

# 🎯 Objetivo

O principal objetivo do projeto é analisar o comportamento da cotação do dólar durante o período disponível na base de dados.

A análise busca responder perguntas como:

- Qual foi o valor médio do dólar no período?
- Qual foi o menor valor registrado?
- Qual foi o maior valor registrado?
- Qual foi o valor central da distribuição?
- Qual foi a variação observada?
- Como a cotação se comportou ao longo dos dias?
- Como a cotação se comportou considerando a média mensal?
- Houve períodos com valores mais elevados ou mais baixos?
- Qual foi o nível de dispersão dos valores observados?

---

# 🏦 Fonte dos dados

Os dados utilizados neste projeto foram obtidos por meio da API do Banco Central do Brasil (BACEN).

A utilização de uma fonte oficial permite trabalhar com dados reais de mercado e aplicar técnicas de análise de dados sobre informações econômicas.

Os dados foram posteriormente armazenados em formato CSV para facilitar a manipulação e análise utilizando Python.

---

# 🗂️ Base de dados

A base utilizada possui:

| Característica | Informação |
|---|---:|
| Registros | 358 |
| Colunas | 11 |
| Valores nulos | 0 |
| Formato | CSV |
| Fonte | Banco Central do Brasil |
| Tema | Cotação do dólar |

A base foi analisada inicialmente para verificar sua estrutura e qualidade antes da realização das análises.

---

# 🔎 Qualidade dos dados

Antes de iniciar a análise, foi realizada uma etapa de exploração da base para verificar possíveis problemas.

Foram verificadas informações como:

- quantidade de registros;
- quantidade de colunas;
- tipos de dados;
- existência de valores ausentes;
- valores estatísticos;
- estrutura das informações;
- consistência dos dados.

Após a verificação, a base apresentou **358 registros e 11 colunas, sem valores nulos**.

Isso significa que não foram identificados valores ausentes nas colunas analisadas, reduzindo a necessidade de procedimentos de preenchimento ou exclusão de registros por ausência de dados.

---

# 🧹 Tratamento dos dados

O tratamento dos dados foi realizado utilizando Python e Pandas.

As principais etapas foram:

1. leitura do arquivo CSV;
2. carregamento dos dados em um DataFrame;
3. análise inicial da estrutura;
4. verificação dos tipos de dados;
5. identificação de valores nulos;
6. análise estatística inicial;
7. preparação das informações de data;
8. organização dos dados para análise temporal;
9. criação de informações agregadas;
10. preparação dos dados para visualização.

Essa etapa é importante porque os dados precisam estar organizados e consistentes antes da geração dos indicadores e gráficos.

---

# 🐍 Tecnologias utilizadas

## Python

Utilizado como linguagem principal para desenvolvimento da análise.

Foi utilizado para:

- carregar os dados;
- tratar a base;
- realizar cálculos;
- criar análises;
- gerar visualizações.

## Pandas

Utilizado principalmente para manipulação dos dados.

Entre as tarefas realizadas estão:

- leitura do CSV;
- criação do DataFrame;
- seleção de colunas;
- análise de registros;
- cálculo de estatísticas;
- agrupamento dos dados;
- preparação das informações para os gráficos.

## NumPy

Utilizado como apoio para operações numéricas e estatísticas.

## Matplotlib

Utilizado para criação das visualizações utilizadas na análise.

## API do Banco Central do Brasil

Utilizada como fonte dos dados de cotação.

## Git e GitHub

Utilizados para versionamento, organização e publicação do projeto.

---

# 🔄 Fluxo do projeto

O fluxo de desenvolvimento pode ser representado da seguinte forma:

API do Banco Central

↓

Coleta dos dados

↓

Arquivo CSV

↓

Python

↓

Pandas

↓

Tratamento dos dados

↓

Análise exploratória

↓

Análise estatística

↓

Visualizações

↓

Interpretação dos resultados

↓

Documentação

↓

GitHub

---

# 📈 Análise estatística

Após o tratamento da base, foram calculadas algumas medidas estatísticas para compreender o comportamento da cotação.

## Média

A média da cotação de venda foi de aproximadamente:

**R$ 5,46**

A média representa o valor obtido ao somar os valores observados e dividir pela quantidade de registros.

Ela fornece uma visão geral do nível médio da cotação durante o período analisado.

---

## Mediana

A mediana da cotação foi aproximadamente:

**R$ 5,44**

A mediana representa o valor central dos dados quando eles são organizados em ordem crescente.

A comparação entre média e mediana é importante porque pode ajudar a identificar possíveis assimetrias na distribuição.

Neste projeto, a média e a mediana apresentam valores próximos, indicando que o valor central da distribuição está próximo da média observada.

---

## Menor valor

O menor valor registrado foi aproximadamente:

**R$ 4,8973**

Esse indicador representa o menor valor de cotação encontrado na base durante o período analisado.

---

## Maior valor

O maior valor registrado foi aproximadamente:

**R$ 6,2086**

Esse valor representa o maior nível de cotação encontrado na base durante o período analisado.

---

## Desvio-padrão

O desvio-padrão observado foi aproximadamente:

**R$ 0,28**

O desvio-padrão é uma medida de dispersão.

Ele ajuda a entender o quanto os valores se afastam da média.

Neste projeto, o valor de aproximadamente R$ 0,28 indica que existiu variação nos valores da cotação ao longo do período analisado.

---

# 📊 Resumo estatístico

| Métrica | Resultado |
|---|---:|
| Registros | 358 |
| Média | R$ 5,46 |
| Mediana | R$ 5,44 |
| Mínimo | R$ 4,8973 |
| Máximo | R$ 6,2086 |
| Desvio-padrão | R$ 0,28 |

---

# 📉 Visualizações

As visualizações foram utilizadas para facilitar a interpretação dos dados.

Em vez de analisar somente números em uma tabela, os gráficos permitem observar tendências, oscilações e diferenças entre períodos.

---

# 📈 1. Evolução diária da cotação

<p align="center">
  <img src="COLOQUE-AQUI-O-NOME-DO-GRAFICO-DIARIO.png" alt="Evolução diária da cotação do dólar" width="100%">
</p>

## O que esse gráfico representa?

Este gráfico apresenta a evolução da cotação do dólar ao longo dos dias disponíveis na base.

O eixo horizontal representa o período analisado.

O eixo vertical representa o valor da cotação em reais.

Cada ponto da linha representa uma observação da cotação.

---

## Para que esse gráfico serve?

O principal objetivo é identificar como a cotação se comportou ao longo do tempo.

Com ele é possível observar:

- períodos de alta;
- períodos de queda;
- oscilações;
- picos de cotação;
- menores níveis de cotação;
- mudanças no comportamento do dólar.

---

## Como interpretar?

Quando a linha apresenta movimento ascendente, significa que a cotação aumentou em relação às observações anteriores.

Quando a linha apresenta movimento descendente, significa que a cotação diminuiu.

Os pontos mais altos representam períodos em que o dólar apresentou valores maiores.

Os pontos mais baixos representam períodos em que a cotação apresentou valores menores.

---

## Por que utilizar uma linha?

Como estamos analisando uma variável ao longo do tempo, o gráfico de linha é adequado porque permite acompanhar a sequência das observações.

A principal informação desse gráfico não é apenas o valor de cada ponto, mas também o comportamento da cotação durante o período.

---

# 📊 2. Média mensal da cotação

<p align="center">
  <img src="COLOQUE-AQUI-O-NOME-DO-GRAFICO-MENSAL.png" alt="Média mensal da cotação do dólar" width="100%">
</p>

## O que esse gráfico representa?

Este gráfico apresenta a média da cotação do dólar agrupada por mês.

Em vez de analisar cada observação individualmente, os dados são agrupados para obter uma visão geral do comportamento mensal.

---

## Para que esse gráfico serve?

A média mensal ajuda a reduzir o impacto das oscilações diárias e facilita a comparação entre os meses.

Por meio dessa visualização podemos identificar:

- meses com maior cotação média;
- meses com menor cotação média;
- períodos de aumento;
- períodos de redução;
- mudanças no nível médio da cotação.

---

## Como interpretar?

Valores maiores no gráfico representam meses em que o dólar apresentou uma cotação média mais elevada.

Valores menores representam meses em que a cotação média foi menor.

Essa abordagem permite comparar períodos de forma mais simples do que analisar centenas de registros individualmente.

---

# 💱 3. Comparação entre cotações

<p align="center">
  <img src="COLOQUE-AQUI-O-NOME-DO-GRAFICO-COMPARACAO.png" alt="Comparação das cotações do dólar" width="100%">
</p>

## O que esse gráfico representa?

Este gráfico compara as diferentes informações de cotação disponíveis na base.

A comparação permite analisar o comportamento das cotações ao longo do período.

---

## Para que esse gráfico serve?

A visualização permite observar:

- diferenças entre os valores;
- comportamento das séries;
- momentos de maior variação;
- aproximação ou afastamento entre as cotações.

---

## Como interpretar?

Quando as linhas permanecem próximas, significa que os valores analisados apresentam comportamento semelhante naquele período.

Quando ocorre maior distância entre as linhas, existe uma diferença maior entre as cotações representadas.

---

# 📌 Principais indicadores encontrados

A análise permitiu identificar alguns indicadores importantes:

- média da cotação de venda: **R$ 5,46**;
- mediana: **R$ 5,44**;
- menor valor: **R$ 4,8973**;
- maior valor: **R$ 6,2086**;
- desvio-padrão: **R$ 0,28**;
- quantidade de registros: **358**;
- quantidade de colunas: **11**;
- valores nulos identificados: **0**.

Esses indicadores permitem compreender o nível médio, a dispersão e a amplitude dos valores observados.

---

# 🧠 Insights da análise

A análise dos dados permite observar que a cotação apresentou variações ao longo do período estudado.

A diferença entre o menor valor registrado, de aproximadamente R$ 4,8973, e o maior valor, de aproximadamente R$ 6,2086, demonstra que houve uma amplitude considerável entre os valores observados.

A média de R$ 5,46 e a mediana de R$ 5,44 apresentam valores próximos.

Além disso, o desvio-padrão de aproximadamente R$ 0,28 demonstra a existência de dispersão dos valores em relação à média.

As visualizações temporais complementam a análise estatística ao permitir observar quando essas alterações ocorreram.

---

# ⚠️ Limitações da análise

É importante destacar que este projeto possui algumas limitações.

A análise descreve exclusivamente os dados presentes na base utilizada.

Os resultados não têm como objetivo prever o comportamento futuro do dólar.

Além disso, a cotação do dólar pode ser influenciada por diversos fatores econômicos, políticos e de mercado que não fazem parte desta análise.

Portanto, os resultados devem ser interpretados como uma análise histórica do período disponível na base.

---

# 📚 O que foi desenvolvido neste projeto

Durante o desenvolvimento foram praticados conhecimentos de:

- Python;
- Pandas;
- NumPy;
- Matplotlib;
- manipulação de dados;
- análise exploratória de dados;
- estatística descritiva;
- análise temporal;
- agrupamento de dados;
- criação de visualizações;
- interpretação de gráficos;
- tratamento de dados;
- consumo de API;
- organização de projeto;
- Git;
- GitHub.

---

# 📁 Estrutura do projeto

```text
Projeto-Cotacao-Dolar/
│
├── Rota_Do_Heroi/
│   └── Cotacao_do_Dolar_por_período.csv
│
├── notebooks/
│   └── análise_cotacao_dolar.ipynb
│
├── graficos/
│   ├── grafico_diario.png
│   ├── grafico_mensal.png
│   └── grafico_comparacao.png
│
└── README.md