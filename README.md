# Sistema de Cidade Inteligente

Sistema desenvolvido em **C** para simular o gerenciamento de uma cidade inteligente, permitindo representar regiões da cidade e registrar ocorrências urbanas.

## 📋 Sobre o projeto

O sistema tem como objetivo representar uma cidade por meio de uma **matriz 2D**, onde cada posição corresponde a uma região ou bairro.

Cada região pode armazenar diversos eventos urbanos, como:

* 🕳️ Buracos nas ruas
* 💡 Problemas na iluminação pública
* 🗑️ Acúmulo de lixo
* 🚗 Acidentes
* 🎉 Eventos urbanos
* 🚦 Problemas relacionados ao trânsito

Cada ocorrência possui informações como identificação, descrição, prioridade, status e localização.

## 🎯 Objetivo

Desenvolver uma solução que permita representar uma cidade e seus eventos em um programa de computador, facilitando o cadastro, localização, consulta e organização das ocorrências urbanas.

## 🧩 Estrutura do sistema

A cidade é representada por uma **matriz 2D**:

```text
cidade[linha][coluna]
```

Cada posição representa uma região da cidade.

A estrutura segue a ideia:

```text
CIDADE
  │
  └── Matriz 2D
        │
        ├── Região
        │     ├── Eventos
        │     └── Quantidade de eventos
        │
        └── Região
              ├── Eventos
              └── Quantidade de eventos
```

Cada evento possui uma localização específica, permitindo identificar exatamente onde o problema ocorreu.

## ⚙️ Funcionalidades

O sistema será organizado em quatro grupos principais:

### Criar e inicializar

* Inicializar a matriz da cidade
* Criar e configurar regiões
* Inicializar os eventos

### Cadastrar e modificar

* Cadastrar regiões
* Cadastrar novos eventos
* Alterar informações de eventos
* Atualizar status das ocorrências

### Buscar e consultar

* Localizar uma região
* Consultar eventos de uma região
* Buscar eventos por prioridade
* Buscar ocorrências específicas

### Analisar e organizar

* Identificar regiões com maior quantidade de ocorrências
* Encontrar problemas prioritários
* Ordenar eventos por prioridade
* Analisar as regiões mais críticas da cidade

## 🛠️ Conceitos utilizados

O projeto foi desenvolvido com foco nos seguintes conceitos:

* `struct`
* `typedef`
* Strings
* Vetores
* Matrizes 2D
* Funções
* Busca linear
* Métodos de ordenação
* Manipulação de registros
* Organização modular do código

## 📚 Conteúdos relacionados

O desenvolvimento do projeto envolve os conteúdos estudados na disciplina:

1. Strings
2. Matrizes
3. Funções
4. Métodos de Ordenação
5. Busca Linear

## 🚀 Objetivo acadêmico

Este projeto faz parte da atividade **Projeto 1 — Sistema de Cidade Inteligente**, tendo como finalidade aplicar conceitos de programação estruturada na modelagem e implementação de um problema do mundo real.

---

**Projeto acadêmico — Engenharia de Computação**
