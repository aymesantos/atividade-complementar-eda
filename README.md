```markdown
# Atividade Complementar — Filas de Prioridade e Árvores de Huffman

**Disciplina:** INF 610 - Estruturas de Dados e Algoritmos

## Descrição

Implementação completa do algoritmo de Huffman Coding utilizando um Min-Heap
construído do zero, sem o uso de bibliotecas externas. O trabalho inclui
codificação, decodificação e análise de complexidade computacional teórica
e empírica.

## Atividades

### a) Min-Heap como Fila de Prioridade
Implementação completa de um Min-Heap com as operações `heapify`, `push`, `pop`
e `peek`, utilizado como fila de prioridade no algoritmo de Huffman. Os
resultados são comparados com o corpus de testes sintéticos e com os arquivos
do Calgary Corpus, avaliando custo computacional e métricas de compressão.

### b) Decodificação
Implementação da decodificação do algoritmo de Huffman, lendo os bits do
arquivo `.huf` e percorrendo a árvore para recuperar o texto original.
A correção é verificada comparando o arquivo decodificado com o original
em todos os arquivos de teste.

### c) Análise de Complexidade
Análise formal e completa da complexidade computacional das principais
operações, incluindo pseudo-códigos, somatórias, equações de recorrência
e provas formais. Os resultados teóricos são comparados com os dados
empíricos coletados nos dois corpora.

## Estrutura

```
.
├── AC_Huffman_Final.ipynb   # notebook principal com código e relatório
└── README.md
```

## Como executar

Abra o notebook no [Google Colab](https://colab.research.google.com/) e
execute as células em ordem. Para os testes com o Calgary Corpus, faça o
upload dos arquivos na pasta de trabalho ou monte o Google Drive.

## Referências

- Salomon, D. *Data Compression: The Complete Reference*, Seção 2.8
- [Calgary Corpus](https://www.data-compression.info/Corpora/CalgaryCorpus/)
- [Código base fornecido pelo professor](https://colab.research.google.com/drive/1BlBG9dZeCW-2dGZQ4Otf3xSO438tdxxE?usp=sharing)
```