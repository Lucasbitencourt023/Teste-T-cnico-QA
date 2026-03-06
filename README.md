# Teste Técnico QA – Simulação de Crédito

## 📌 Objetivo

Este repositório apresenta a execução de um **teste técnico de Quality Assurance (QA)** baseado na jornada de **simulação de crédito** em um ambiente bancário.

O objetivo do teste foi:

* Realizar **testes funcionais** em uma jornada de simulação de crédito (imobiliário ou automotivo).
* Identificar possíveis **bugs ou inconsistências** durante a navegação.
* Desenvolver e documentar **casos de teste** da jornada analisada.
* Evidenciar os testes realizados.
* Modelar o **processo de simulação de crédito utilizando BPMN**.

Mesmo nos cenários em que não foram encontrados erros, todos os testes foram devidamente **executados e evidenciados**.

---

# 🧪 Etapa 1 – Execução dos Testes

Nesta etapa foram realizados **testes manuais** na jornada de simulação de crédito, avaliando os principais campos e validações do fluxo de cadastro.

## 🔎 Escopo testado

A jornada analisada inclui as seguintes etapas:

1. Preenchimento do nome do usuário
2. Validação de CPF
3. Preenchimento da data de nascimento
4. Validação de e-mail
5. Preenchimento do telefone
6. Informar renda mensal
7. Validação de token (SMS ou autenticação)
8. Processamento da simulação de crédito
9. Exibição do resultado da simulação

---

## 📋 Casos de Teste

Foram criados cenários de teste para validar:

* Fluxos **positivos**
* Fluxos **negativos**
* **Campos obrigatórios**
* **Validação de dados inválidos**
* **Regras de negócio**

Exemplos de validações realizadas:

* Campo nome vazio
* CPF inválido
* Idade mínima permitida
* Formato de e-mail inválido
* Campo renda mensal vazio
* Token de autenticação inválido

Os casos de teste completos podem ser encontrados no arquivo:

```
/caderno-de-testes/Caderno de teste.xlsx
```

---

## 🐞 Bugs Identificados

Durante a execução dos testes foram avaliadas possíveis inconsistências como:

* Instabilidade do sistema. 
* Problemas de navegação entre etapas

Caso nenhum bug seja identificado, todos os testes executados foram **evidenciados como sucesso**, demonstrando que a aplicação se comportou conforme esperado.

---

## 📸 Evidências de Teste

As evidências dos testes executados incluem:

* Prints da execução da jornada
* Resultados obtidos nos cenários de teste
* Registro de mensagens de erro (quando aplicável)

---



### Possíveis melhorias

* Validação de dados em tempo real nos campos do formulário
* Mensagens de erro mais claras para o usuário
* Automatização da validação de CPF
* Redução de etapas no fluxo de preenchimento
* Melhor tratamento de erros na validação do token

---

# 🛠️ Ferramentas Utilizadas

* Modelagem de processos: Bizagi Modeler
* Documentação de testes: Microsoft Excel
* Controle de versão: Git / GitHub

---

# 📊 Tipos de Teste Aplicados

Durante a execução do teste técnico foram aplicados:

* Testes funcionais
* Testes de validação de campos
* Testes de fluxo de navegação
* Testes negativos
* Testes de regras de negócio

---

# 👨‍💻 Autor

Lucas Bitencourt
Analista de Testes / QA

