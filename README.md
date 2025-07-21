# Análise de Notas de Alunos

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/carolcerceau/projeto/blob/main/Projeto.ipynb)

Este projeto é um notebook Jupyter (Google Colab) que realiza uma análise exploratória básica de um conjunto de dados de notas de alunos.

---

## Visão Geral

O objetivo principal deste notebook é demonstrar como carregar dados de um arquivo CSV usando a biblioteca `pandas` no Python e realizar algumas operações iniciais de inspeção do dataset, como verificar suas dimensões, colunas, obter um resumo estatístico e adicionar colunas.

---

## Estrutura do Projeto

* `Projeto.ipynb`: O notebook principal do Google Colab contendo o código Python para análise.
* `Notas.csv`: O arquivo CSV contendo os dados das notas dos alunos.

---

## Dados

O arquivo `Notas.csv` é um arquivo de valores separados por ponto e vírgula (`;`) e contém as seguintes colunas:

* **Aluno**: Nome do aluno.
* **D1**: Nota da primeira disciplina/avaliação.
* **D2**: Nota da segunda disciplina/avaliação.
* **D3**: Nota da terceira disciplina/avaliação.

Exemplo do conteúdo do arquivo `Notas.csv`:

```csv
Aluno;D1;D2;D3
Maria;13;20.0;14.0
João;16;17.0;20.0
José;20;16.0;19.0
Alexandre;18;16.0;
Paulo;19;9.0;7.0
Carlos;9;10.0;11.0
Pedro;11;;18.0
Joana;19;20.0;3.0
Carla;17;;17.0
Joana;19;20.0;3.0
```
---

## Como Usar

Para executar este notebook:

- Clique no badge **"Open In Colab"** acima ou acesse o link direto: [https://colab.research.google.com/github/carolcerceau/projeto/blob/main/Projeto.ipynb](https://colab.research.google.com/github/carolcerceau/projeto/blob/main/Projeto.ipynb)
- Faça o upload do arquivo **Notas.csv** para o ambiente do Google Colab, na mesma pasta do notebook.
- Execute as células do notebook sequencialmente.

---

## Análise Realizada

O notebook executa as seguintes etapas:

1. **Leitura do CSV**  
   Carrega o arquivo `Notas.csv` em um DataFrame do pandas.

2. **Verificação de Dimensões**  
   Exibe o número de linhas e colunas do DataFrame (`notas.shape`).

3. **Visualização de Colunas**  
   Lista os nomes das colunas presentes no DataFrame (`notas.columns`).

4. **Resumo Estatístico**  
   Gera um resumo estatístico das colunas numéricas, incluindo contagem, média, desvio padrão, valores mínimo e máximo, e quartis (`notas.describe()`).

5. **Criar novas colunas**  
   Cria novas colunas no DataFrame.

