# Validação de Usuário e Senha com JUnit

Este projeto Java implementa uma classe  com métodos para validar nome de usuário e senha, seguindo regras específicas. Os testes são escritos com JUnit 5.

## 📂 Estrutura

- 'src/Person.java': Classe principal com métodos 'checkUser()' e 'checkPassword()'
- 'src/PersonTest.java': Classe de testes com métodos parametrizados usando JUnit 5

## ✅ Regras de Validação

### checkUser()
- Mínimo de 8 caracteres
- Apenas letras e números (sem caracteres especiais)

### checkPassword()
- Mínimo de 8 caracteres
- Pelo menos uma letra maiúscula
- Pelo menos um número
- Pelo menos um caractere especial

## 🧪 Testes

Os testes cobrem casos válidos e inválidos para nome de usuário e senha, usando '@ParameterizedTest' e '@ValueSource'.

## 🚀 Como executar

1. Compile o projeto:
   '''bash
   mvn compile
