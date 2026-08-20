#  Formula1 PowerBI

Projeto acadêmico de **Business Intelligence** desenvolvido em **Microsoft Power BI**, com foco na análise de dados históricos da Fórmula 1.

O projeto está sendo desenvolvido de forma incremental, com novas análises sendo adicionadas a cada entrega acadêmica.

##  Objetivo do Projeto

Transformar dados históricos da Fórmula 1 em informações visuais e indicadores que permitam analisar o desempenho de pilotos, equipes, classificações e corridas ao longo das temporadas.

##  Tecnologias Utilizadas

* Microsoft Power BI
* Power Query
* DAX
* CSV
* GitHub

##  C1 — Campeonato de Pilotos

A primeira entrega do projeto tem como foco a **análise de desempenho dos pilotos de Fórmula 1**.

### Principais indicadores

* Posição atual
* Pontos
* Corridas disputadas
* Corridas completas
* Número de vitórias
* Percentual de vitórias
* Pole Positions
* Percentual de Pole Positions
* Abandonos
* Percentual de abandonos
* Desempenho Top 5
* Desempenho Top 10

### Filtros disponíveis

* Temporada
* Piloto
* Round

Os indicadores e gráficos são atualizados dinamicamente conforme os filtros selecionados.

##  Estrutura do Projeto

```text
Formula1_PowerBI
│
├── Dados
│   ├── circuits.csv
│   ├── constructor_standings.csv
│   ├── constructors.csv
│   ├── driver_standings.csv
│   ├── drivers.csv
│   ├── pitstops.csv
│   ├── qualifying_results.csv
│   ├── results.csv
│   ├── results_history.csv
│   └── results_qualy.csv
│
├── Imagens_Pilotos
│
├── Power BI
│   └── Formula1_PowerBI_C1.pbix
│
└── Documentação
```

##  Tratamento dos Dados

Os arquivos utilizados como fonte são carregados no Power BI por meio do **Power Query**.

Foi criado um parâmetro chamado `CaminhoBaseF1` para centralizar o diretório dos arquivos utilizados pelo projeto, facilitando a manutenção e atualização das fontes de dados.

O modelo também utiliza medidas desenvolvidas em **DAX** para realizar os cálculos e alimentar os indicadores e visualizações do dashboard.

##  Fonte dos Dados

Os dados utilizados neste projeto são provenientes da **Ergast F1 API**,
base pública de dados históricos da Fórmula 1, atualmente continuada
pela **Jolpica F1 API**.

Os dados foram disponibilizados em arquivos CSV e posteriormente
tratados e modelados no Power BI por meio do Power Query.

> Fonte de referência: **Ergast F1 API / Jolpica F1 API**

##  Evolução do Projeto

* [x] C1 — Análise do Campeonato de Pilotos
* [ ] C2 — Próxima análise
* [ ] C3 — Próxima análise
* [ ] Prova — Análise final

## 👨‍💻 Autor

**Lucas Felipe de Jesus Correa**

Projeto desenvolvido para fins acadêmicos.
