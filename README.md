# Validador de MEI com JUnit

Este projeto Java verifica se uma pessoa está apta a se registrar como Microempreendedor Individual (MEI) com base nas regras da legislação brasileira.

## 📁 Estrutura do Projeto

## 📌 Regras de Validação

A classe 'Person' possui o método 'isMEI()' que retorna 'true' ou 'false' com base nos seguintes critérios:

- Ter mais de 18 anos
- Não ser pensionista
- Não ser servidor público
- Não possuir outra empresa
- Ter faturamento anual inferior a R$ 130.000,00

## 🧪 Testes com JUnit

A classe 'PersonTest' realiza os seguintes testes:

- 'show_full_name': verifica se o nome completo está correto
- 'test_calculateYearlySalary': valida o cálculo do salário anual
- 'person_is_MEI': verifica se uma pessoa com dados válidos é MEI
- 'person_is_not_MEI': verifica se uma pessoa com dados inválidos não é MEI

## 🚀 Como Executar

1. Instale o Java e o Maven
2. Navegue até o diretório do projeto:
   '''bash
   '''cd 0x01/mei
