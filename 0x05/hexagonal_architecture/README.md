# Sistema de Usuários com Arquitetura Hexagonal

Este projeto demonstra a aplicação da Arquitetura Hexagonal em Java, separando claramente as regras de negócio da infraestrutura.

## 🧩 Componentes

- 'domain': contém a entidade 'User'
- 'application': serviço 'UserService' com regras de negócio
- 'ports': interface 'UserRepository' para persistência
- 'adapters': implementação 'InMemoryUserRepository' e interface CLI 'UserConsoleApp'

## 🚀 Funcionalidades

- Criar usuários
- Buscar usuários por ID
- Listar todos os usuários

## 🛠 Execução

A interface de console permite testar o sistema diretamente pelo terminal. Basta compilar e executar a classe 'UserConsoleApp'.

