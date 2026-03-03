# Caverna-Programacao-Dinamica

Este projeto foi desenvolvido como Trabalho Pratico 2 da disciplina de Projeto e Analise de Algoritmos na Universidade Federal de Vicosa (UFV) - Campus Florestal. O programa simula a navegacao de um estudante em uma caverna com o objetivo de encontrar o caminho que maximiza seus Pontos de Vida (PV) ate a saida.

## 1. O que faz

O programa carrega a configuracao de uma caverna a partir de um arquivo texto e utiliza programacao dinamica para encontrar o caminho otimo do ponto inicial ate o ponto final, maximizando os pontos de vida acumulados durante o percurso.

Funcionalidades:
- Carregar caverna de arquivo texto
- Encontrar caminho que maximiza os PV
- Gerar arquivo de saida com o caminho percorrido
- Indicar quando nao ha solucao viavel

## 2. Tecnologias e Estruturas

- **Linguagem:** C
- **Compilador:** GCC
- **Algoritmo:** Programacao Dinamica + Busca em Largura (BFS)
- **Estruturas:** Matrizes, filas, alocacao dinamica
- **Entrada/Saida:** Leitura e gravacao de arquivos


## 3. Compilacao e Execucao

### Compilar:
```bash
make
```
### Executar:
```bash
./programa entrada.txt