# 🚗 Parking System CLI

Sistema de gerenciamento de estacionamento desenvolvido em C para controle de entrada e saída de veículos via terminal.

## 📌 Sobre o Projeto

O Parking System CLI é um sistema simples de estacionamento que permite:

- Registrar entrada de veículos
- Registrar saída com cálculo automático de valor
- Listar veículos estacionados
- Mostrar quantidade de vagas disponíveis

O projeto foi desenvolvido com foco em lógica de programação, uso de estruturas (`struct`), vetores e organização em funções.

---

## 🛠 Tecnologias Utilizadas

- Linguagem C
- Estrutura de dados com `struct`
- Manipulação de vetores
- Funções
- Menu interativo com `do while`

---

## ⚙️ Funcionalidades

### 🚗 Registrar Entrada
- Verifica se a placa já está cadastrada
- Valida horário (0 a 23)
- Aloca automaticamente na primeira vaga disponível

### 🚙 Registrar Saída
- Busca veículo pela placa
- Calcula tempo estacionado
- Trata casos de virada de meia-noite
- Calcula valor (R$ 5,00 por hora)
- Libera vaga automaticamente

### 📋 Listagem
- Mostra todos os veículos estacionados

### 📊 Controle de Vagas
- Exibe quantidade de vagas livres

---

## 💰 Regra de Cobrança

- R$ 5,00 por hora
- Tempo mínimo: 1 hora
- Sistema considera virada de dia (24h)

---

## 🚀 Como Executar

1. Compile o programa:

```bash
gcc main.c -o parking
