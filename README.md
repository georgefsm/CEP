
# Prova de Controle Estatístico de Processo (CEP) - UnB

Este repositório contém os arquivos referentes à Prova 1 da disciplina de Controle Estatístico de Processos (CEP), do curso de Engenharia de Produção da Universidade de Brasília (UnB).

O objetivo da avaliação era demonstrar a compreensão teórica e a capacidade de implementação prática de Cartas de Controle de Shewhart (X-barra e R) utilizando Python.

## Contexto da Avaliação

* [cite_start]**Disciplina:** Controle Estatístico de Processos [cite: 130]
* [cite_start]**Instituição:** Universidade de Brasília (UnB) - Departamento de Engenharia de Produção [cite: 126, 127]
* [cite_start]**Professor:** Dr. André Luiz Marques Serrano [cite: 129]
* [cite_start]**Tema:** Cartas de Controle de Shewhart [cite: 135]
* [cite_start]**Ferramentas:** Python, com as bibliotecas `pandas`, `numpy` e `matplotlib` [cite: 155]

## Estrutura do Repositório

```

.
├── CEP\_Prova1.pdf
├── projeto\_CEP.pdf
├── analise\_cep.py
├── xr\_grafico.png
└── README.md

````

## Descrição dos Arquivos

### 1. `CEP_Prova1.pdf` (O Enunciado da Prova)

Este arquivo contém o enunciado oficial da prova. Ele é dividido em:

* [cite_start]**Checklist de Definição do Problema:** Questões para guiar a análise preliminar[cite: 160, 161].
* [cite_start]**Caso Prático:** Um estudo de caso da indústria farmacêutica focado no monitoramento do peso (massa) de comprimidos de 500 mg[cite: 182, 183, 184]. [cite_start]O objetivo era usar 25 amostras de 5 comprimidos cada para construir cartas X-barra e R e verificar se o processo estava sob controle estatístico[cite: 187, 188, 196].
* [cite_start]**Trilha de Passos:** Um guia de 10 passos para a implementação do código em Python, desde a importação de bibliotecas até a análise dos resultados[cite: 210, 211, 212].
* [cite_start]**Questões Teóricas:** Quatro questões conceituais sobre CEP[cite: 291, 294, 297, 300, 306].
* [cite_start]**Entregáveis:** A prova exigia a entrega de um arquivo `.py`, os gráficos em `.png` e um relatório em `.pdf`[cite: 351, 353, 354, 355].

### 2. `projeto_CEP.pdf` (O Relatório de Resposta)

[cite_start]Este arquivo é o relatório final submetido pelo aluno George Magalhães[cite: 2]. Ele contém:

* [cite_start]**Definição do Problema:** Descreve o problema analisado, hipóteses e o dataset[cite: 3, 11, 23].
* [cite_start]**Respostas às Questões Teóricas:** Contém as respostas para as quatro questões teóricas propostas no enunciado[cite: 38, 39, 49, 54, 62].
* **Detalhamento da Análise Prática:**
    * **Nota Importante:** A análise prática neste relatório **não** corresponde ao caso farmacêutico descrito em `CEP_Prova1.pdf`.
    * [cite_start]A análise foi realizada sobre um conjunto de dados de manufatura diferente, contendo 3957 observações com variáveis como "Temperatura" e "Pressão"[cite: 8, 24, 25, 27].
    * [cite_start]O foco da análise foi a "Métrica de Transformação de Material", cuja hipótese era de que não estava sob controle[cite: 15, 17, 32].
    * [cite_start]O relatório inclui as cartas X-barra e R para esta métrica (Figura 1) [cite: 122][cite_start], com a conclusão "Not In Control"[cite: 83].

### 3. `analise_cep.py` (Script Python)

* *(Arquivo hipotético baseado nos entregáveis da prova)*
* [cite_start]Este script conteria o código Python usado para realizar os cálculos estatísticos (médias, amplitudes, limites de controle) e gerar os gráficos, conforme solicitado na "Trilha de Passos" do enunciado[cite: 353].

### 4. `xr_grafico.png` (Gráficos)

* *(Arquivo hipotético baseado nos entregáveis da prova)*
* [cite_start]Imagem contendo as Cartas de Controle X-barra e R geradas pelo script Python[cite: 354]. [cite_start]O gráfico contido em `projeto_CEP.pdf` é um exemplo[cite: 122].

## Como Executar

[cite_start]Para executar a análise (o arquivo `analise_cep.py`), você precisará das bibliotecas Python especificadas no enunciado da prova[cite: 215, 216, 217, 218].

1.  **Crie um ambiente virtual (recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```

2.  **Instale as dependências:**
    ```bash
    pip install pandas numpy matplotlib
    ```

3.  **Execute o script:**
    ```bash
    python analise_cep.py
    ```
````
