# Projeto: Validador de Email com JUnit

Este projeto Java tem como objetivo validar endereços de email com base em critérios simples e realizar testes automatizados utilizando JUnit.

## 📁 Estrutura do Projeto

## 📌 Regras de Validação

A classe 'Pessoa' possui o método estático 'emailValid(String email)' que retorna 'true' ou 'false' com base nos seguintes critérios:

- O email deve conter o caractere '@'
- O email deve ter no máximo 50 caracteres
- O email não pode ser 

## 🧪 Testes com JUnit

A classe 'TesteEmail' realiza três testes:

- 'testar_email_com_arroba': verifica se '"email_teste@dominio.com.br"' é válido
- 'testar_email_sem_arroba': verifica se '"email_testedominio.com.br"' é inválido
- 'testar_email_mais_50_caracteres': verifica se emails com mais de 50 caracteres são inválidos

## 🚀 Como Executar

1. Certifique-se de ter o Java e o Maven instalados.
2. Navegue até o diretório do projeto:
   '''bash
   cd 0x01/email
