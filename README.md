
# Prova de Controle Estatístico de Processo (CEP) - UnB

Este repositório contém os arquivos referentes à Prova 1 da disciplina de Controle Estatístico de Processos (CEP), do curso de Engenharia de Produção da Universidade de Brasília (UnB).

O objetivo da avaliação era demonstrar a compreensão teórica e a capacidade de implementação prática de Cartas de Controle de Shewhart (X-barra e R) utilizando Python.

## Contexto da Avaliação

* **Disciplina:** Controle Estatístico de Processos
* **Instituição:** Universidade de Brasília (UnB) - Departamento de Engenharia de Produção
* **Professor:** Dr. André Luiz Marques Serrano
* **Tema:** Cartas de Controle de Shewhart
* **Ferramentas:** Python, com as bibliotecas `pandas`, `numpy`, `matplotlib`, `json` e  `pyshewhart`

## Estrutura do Repositório

```

.
├── CEP - Prova 1.ipynb
├── manufacturing.csv
├── manufacturing-data-for-polynomial-regression-metadata.json
└── README.md

````
## Descrição dos Arquivos

### 1. `projeto_CEP.pdf` (O Relatório de Resposta)

Este arquivo é o relatório final submetido pelo aluno George Magalhães. Ele contém:

 Definição do Problema: Descreve o problema analisado, hipóteses e o dataset.
 Respostas às Questões Teóricas: Contém as respostas para as quatro questões teóricas propostas no enunciado.
 Detalhamento da Análise Prática:
     A análise foi realizada sobre um conjunto de dados de manufatura diferente, contendo 3957 observações com variáveis como "Temperatura" e "Pressão".
     O foco da análise foi a "Métrica de Transformação de Material", cuja hipótese era de que não estava sob controle.
     O relatório inclui as cartas X-barra e R para esta métrica (Figura 1), com a conclusão "Not In Control".
