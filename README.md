# 🧾 Cadastro com Abas em ADVPL (Protheus)

Projeto desenvolvido em ADVPL utilizando componentes visuais do Protheus para praticar criação de interfaces gráicas com `TDialog`, `TFolder`, `TGet`, `TComboBox`, `TRadMenu` e manipulação de dados via `JsonObject`.

---

## 📌 Sobre o projeto

O projeto consiste em uma tela de cadastro dividida em abas, permitindo separar informações pessoais e endereço de forma organizada.

Os dados preenchidos pelo usuário são capturados e exibidos através de uma função reutilizável (`ExibiDados`) utilizando `JsonObject`.

Este projeto foi desenvolvido com foco em estudos de interfaces gráficas no Protheus e reutilização de funções em ADVPL.

---

## 🚀 Funcionalidades

### 📂 Estrutura com abas (`TFolder`)

* Aba **Dados Pessoais**
* Aba **Endereço**

### 👤 Cadastro de Dados Pessoais

* Nome
* Nome reduzido
* Data de nascimento
* DDD
* Celular
* Sexo (`TRadMenu`)
* CPF

### 🏠 Cadastro de Endereço

* Endereço
* Bairro
* Tipo de imóvel (`TComboBox`)
* CEP
* Estado (`TComboBox`)
* Cidade

### 📋 Exibição dos dados

* Botão para visualizar os dados preenchidos em cada aba
* Utilização de `JsonObject`
* Função reutilizável para exibição (`Static Function ExibiDados`)

---

## 🧠 Conceitos aplicados

* Criação de telas com `TDialog`
* Utilização de abas com `TFolder`
* Componentes gráficos:

  * `TSay`
  * `TGet`
  * `TButton`
  * `TRadMenu`
  * `TComboBox`
* Máscaras de campos (`CPF`, `CEP`, `Telefone`)
* Manipulação de arrays
* `JsonObject`
* Funções estáticas reutilizáveis
* Captura de dados via `bSetGet`
* Organização visual de formulários

---

## ▶️ Como executar

Compile o fonte no ambiente Protheus e execute a função:

```advpl
U_ZCADASTRO()
```

---


## 👨‍💻 Autor

Diego Santana
🔗 [LinkedIn - Diego Santana](https://www.linkedin.com/in/die-santana/?utm_source=chatgpt.com)

---

## 💬 Feedbacks

Sugestões e melhorias são muito bem-vindas! 🚀
