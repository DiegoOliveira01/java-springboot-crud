# Sistema de Gerenciamento de Usuários – API REST Spring Boot👤

O **Gerenciamento de Usuário** é uma **API REST CRUD** desenvolvida em **Java** com foco na manipulação de **dados de usuários** dentro de um sistema backend.  
O projeto centraliza as operações de **criação**, **leitura**, **atualização** e **exclusão** de usuários, oferecendo uma estrutura organizada e fácil de entender.

O projeto foi desenvolvido com foco em organização de código, separação de responsabilidades e facilidade de manutenção.

---

## 🚀 Funcionalidades

- Cadastro de novos usuários  
- Listagem de usuários existentes  
- Atualização de dados de usuários  
- Remoção de usuários  
- Padrão REST com endpoints HTTP  
- Estrutura organizada em camadas (Controller, Service, Repository)

---

## 🛠️ Tecnologias Utilizadas

- **Java**  
- **Spring Boot** (Framework web RESTful)  
- **Spring Data JPA** (Persistência de dados)  
- **Maven** (Gerenciamento de dependências)  
- **Banco de dados configurável** (via `application.properties`)

## 📂 Estrutura do Projeto
```markdown
src
├── main
│   ├── java
│   │   └── com
│   │       └── diego
│   │           └── gerenciamento_usuario
│   │               ├── GerenciamentoUsuarioApplication.java
│   │               │
│   │               ├── business
│   │               │   └── UsuarioService.java
│   │               │
│   │               ├── controller
│   │               │   └── UsuarioController.java
│   │               │
│   │               └── infrastructure
│   │                   ├── entitys
│   │                   │   └── Usuario.java
│   │                   │
│   │                   └── repository
│   │                       └── UsuarioRepository.java
│   │
│   └── resources
│       ├── application.properties
│       ├── static
│       └── templates
```

<p align="center">
  <img src="src/main/resources/com/physicalmed/physicalmedmanagement/screenshots/admin-dashboard.png" width="400" />
</p>
