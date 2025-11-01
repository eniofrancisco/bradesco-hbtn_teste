# Validador de Usuário e Senha

Este projeto Java implementa uma classe  com métodos para validar nome de usuário e senha, com testes automatizados usando JUnit 5.

## 📁 Estrutura

- 'src/main/java/Person.java': Classe principal com métodos 'checkUser()' e 'checkPassword()'
- 'src/test/java/PersonTest.java': Classe de testes com JUnit 5

## ✅ Regras

### checkUser()
- Mínimo de 8 caracteres
- Apenas letras e números

### checkPassword()
- Mínimo de 8 caracteres
- Pelo menos uma letra maiúscula
- Pelo menos um número
- Pelo menos um caractere especial

## 🧪 Testes

Os testes cobrem casos válidos e inválidos para nome de usuário e senha, usando '@ParameterizedTest'.

## 🚀 Como executar

'''bash
mvn test
