# Jogo de Sudoku em C

## Trabalho Final — Disciplina de Algoritmos

**Curso:** Ciência da Computação  
**Instituição:** Universidade Federal de São João del-Rei (UFSJ)

---

## Descrição do Projeto

Este projeto consiste no desenvolvimento de um **jogo de Sudoku em linguagem C**, implementado como trabalho final da disciplina de **Algoritmos**. O objetivo principal é aplicar conceitos fundamentais da disciplina, como **estruturas de dados**, **funções**, **controle de fluxo**, **manipulação de matrizes**, **arquivos**.

O jogo permite ao usuário interagir via terminal, escolher níveis de dificuldade, jogar partidas completas de Sudoku, remover números, verificar desempenho por tempo e manter um **ranking persistente** em arquivo.

---

## Objetivos do Trabalho

* Aplicar o algoritmo de **backtracking** para resolução de Sudoku
* Trabalhar com **matrizes bidimensionais (9x9)**
* Utilizar **funções modulares** para organização do código
* Manipular **arquivos** para salvar ranking e dados do jogador
* Desenvolver uma aplicação interativa em **C estruturado**

---

## Funcionalidades Implementadas

* Geração automática de um Sudoku válido
* Resolução de Sudoku utilizando **backtracking**
* Exibição do tabuleiro formatado no terminal
* Três níveis de dificuldade:

  * Fácil
  * Médio
  * Difícil
* Inserção manual de números pelo jogador
* Remoção de números durante o jogo
* Contabilização do tempo de jogo
* Sistema de **ranking** salvo em arquivo (`records.txt`)
* Menu interativo com múltiplas opções

---

## Algoritmos Utilizados

### ✔ Backtracking

O algoritmo de backtracking é utilizado para:

* Resolver automaticamente o Sudoku
* Garantir que o tabuleiro gerado seja válido

A função `resolverSudoku()` tenta preencher recursivamente as posições vazias, retrocedendo quando encontra conflitos.

### ✔Verificação de Jogadas

A função `podeColocar()` garante que um número:

* Não se repita na linha
* Não se repita na coluna
* Não se repita no subgrid 3x3

---

## 🛠️ Tecnologias e Ferramentas

* **Linguagem:** C
* **Compilador:** GCC (MinGW)
* **Paradigma:** Programação estruturada
* **Entrada/Saída:** Terminal
* **Arquivos:** Leitura e escrita em arquivos `.txt`

---

## ▶️ Como Compilar e Executar

### Compilação

```bash
gcc main.c -o sudoku
```

### Execução

```bash
./sudoku
```

No Windows (MinGW):

```bash
sudoku.exe
```

---

## 📂 Arquivos Gerados

* `records.txt` → armazena o ranking dos jogadores
* `nome.txt` → armazena o nick do jogador atual

---

## 👨‍💻 Autores

* **André Almeida**
* **Maria Eduarda Antunes**
* **Bruno Rabelo**

---

## 📚 Considerações Finais

Durante o desenvolvimento deste projeto, foi necessário ir além do conteúdo apresentado em sala de aula. Embora o **algoritmo de backtracking não tenha sido abordado diretamente na disciplina de Algoritmos**, os integrantes do grupo realizaram **pesquisas adicionais por conta própria** para compreender e aplicar essa técnica na resolução do Sudoku.

Essa iniciativa contribuiu significativamente para o aprofundamento do aprendizado, estimulando a autonomia na busca por soluções, a capacidade de estudar algoritmos novos de forma independente e a aplicação prática de conceitos avançados de lógica e recursão.

O trabalho possibilitou a consolidação dos conceitos estudados na disciplina, além de desenvolver habilidades em **lógica**, **organização de código**, **resolução de problemas** e **programação em C**. O projeto pode ser expandido futuramente com validação completa do Sudoku, interface gráfica ou salvamento de partidas.

---

> Projeto desenvolvido com fins acadêmicos como parte da avaliação final da disciplina de Algoritmos — UFSJ.
