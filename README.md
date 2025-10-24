
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
├── CEP_Prova1.pdf
├── manufacturing.csv
├── manufacturing-data-for-polynomial-regression-metadata.json
└── README.md

````
## Descrição dos Arquivos

### 1. `projeto_CEP.pdf` (O Relatório de Resposta)

Este arquivo é o relatório final submetido pelo aluno George Magalhães[cite: 2]. Ele contém:

 Definição do Problema: Descreve o problema analisado, hipóteses e o dataset[cite: 3, 11, 23].
 Respostas às Questões Teóricas: Contém as respostas para as quatro questões teóricas propostas no enunciado[cite: 38, 39, 49, 54, 62].
 Detalhamento da Análise Prática:
     Nota Importante: A análise prática neste relatório não corresponde ao caso farmacêutico descrito em `CEP_Prova1.pdf`.
     A análise foi realizada sobre um conjunto de dados de manufatura diferente, contendo 3957 observações com variáveis como "Temperatura" e "Pressão"[cite: 8, 24, 25, 27].
     O foco da análise foi a "Métrica de Transformação de Material", cuja hipótese era de que não estava sob controle[cite: 15, 17, 32].
     O relatório inclui as cartas X-barra e R para esta métrica (Figura 1) [cite: 122], com a conclusão "Not In Control"[cite: 83].

### 2. `analise_cep.py` (Script Python)

 (Arquivo hipotético baseado nos entregáveis da prova)
 Este script conteria o código Python usado para realizar os cálculos estatísticos (médias, amplitudes, limites de controle) e gerar os gráficos, conforme solicitado na "Trilha de Passos" do enunciado[cite: 353].

### 3. `xr_grafico.png` (Gráficos)

