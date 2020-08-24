# Arvores&Palavras

## Introdução

Uma tarefa comum no processamento de linguagem natural é a análise, o processo de determinar a estrutura de uma frase. Isso é útil por vários motivos: conhecer a estrutura de uma frase pode ajudar um computador a entender melhor o significado da frase e também pode ajudar o computador a extrair informações de uma frase. Em particular, costuma ser útil extrair sintagmas nominais de uma frase para entender do que se trata a frase. Neste problema, usaremos o formalismo de gramática livre de contexto para analisar sentenças em inglês e determinar sua estrutura.

## Como usar 

### pip install -r requirements

e 

### python parser.py /sentences/1.txt

onde 1.txt é um arquivo txt contendo a frase a ser analizada

### python parser.py

para informar a frase no terminal

## Observação 

Pode dar algum erro com o nltk. Caso aconteça abra o python no terminal

### python

e digite

### nltk.download('punkt')
### exit()

## Projeto original

Projeto 6 do Curso: [CS50’s Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/2020/weeks/6/)