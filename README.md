---

# Projeto Web Monólito em Java - Avaliação de Cursos EAD

Este projeto tem como objetivo o desenvolvimento de uma aplicação web monolítica em Java para **avaliação de cursos de graduação EAD (Educação a Distância)**. A plataforma permitirá que alunos avaliem suas instituições de ensino com base em critérios como qualidade do conteúdo, professores, apoio ao aluno, material didático e funcionamento do polo presencial.

## ✨ Funcionalidades

- Cadastro de usuários com validação por R.A. (Registro Acadêmico)
- Cadastro de universidades, cursos e polos EAD
- Avaliação de cursos com base nos seguintes critérios:
  - Qualidade do conteúdo
  - Qualidade dos professores
  - Apoio nos estudos
  - Material didático
  - Infraestrutura do polo
- Exibição de médias por curso, universidade e polo
- Filtro por instituição e área de formação
- Área administrativa para moderação de avaliações

## 🛠️ Tecnologias Utilizadas

- **Java 21**
- **Spring Boot** (caso esteja usando, ou especifique o framework MVC se for puro Java EE)
- **Hibernate OGM** com MongoDB
- **Thymeleaf** (caso esteja usando para renderizar o front-end)
- **Maven**
- **IntelliJ IDEA**
- **MongoDB**

## 📁 Estrutura do Projeto

```
src/
├── main/
│   ├── java/
│   │   └── br.com.seuprojeto/
│   │       ├── controller/
│   │       ├── model/
│   │       ├── repository/
│   │       └── service/
│   └── resources/
│       ├── templates/
│       ├── static/
│       └── application.properties
└── test/
```

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/nome-do-repositorio.git
   cd nome-do-repositorio
   ```

2. Configure o banco de dados MongoDB no arquivo `application.properties` ou `persistence.xml`.

3. Execute o projeto com seu IDE favorita ou via linha de comando:
   ```bash
   ./mvnw spring-boot:run
   ```

4. Acesse a aplicação em: `http://localhost:8080`

## 📌 Requisitos

- Java 21+
- Maven
- MongoDB em execução local ou remoto

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---
