```markdown
# Projeto Web Monólito em Java - Avaliação de Cursos EAD

Este projeto tem como objetivo desenvolver uma aplicação web monolítica, utilizando Java, para permitir a avaliação de cursos de graduação a distância (EAD). A plataforma visa fornecer um espaço onde os alunos possam compartilhar suas experiências e avaliar a qualidade dos cursos oferecidos por diferentes instituições de ensino superior.

## 🧩 Funcionalidades

- Cadastro de cursos e instituições de ensino
- Avaliação de cursos por alunos (com critérios como: qualidade do conteúdo, professores, apoio ao aluno, estrutura do polo e material didático)
- Registro obrigatório de nome, R.A., universidade e curso para garantir veracidade das avaliações
- Cálculo de médias por critério e geral para cada curso
- Listagem e ranking dos cursos melhor avaliados

## 🛠️ Tecnologias Utilizadas

- **Java 21**
- **Spring Boot** (opcional, dependendo da implementação)
- **Hibernate OGM com MongoDB**
- **HTML/CSS/JavaScript** para a interface
- **Maven** para gerenciamento de dependências
- **IntelliJ IDEA** como ambiente de desenvolvimento

## 📁 Estrutura do Projeto

```
Mod39/
└── curso-ranking/
    ├── src/
    ├── README.md
    ├── pom.xml
    └── ...
```

## 🚀 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/dionatandiego11/tarefas-ebac-Dionatan.git
cd tarefas-ebac-Dionatan/Mod39/curso-ranking
```

2. Compile e execute com o Maven:

```bash
mvn clean install
mvn spring-boot:run
```

3. Acesse a aplicação no navegador:

```
http://localhost:8080
```

## 📌 Observações

Este projeto é um protótipo acadêmico com fins educacionais. Todas as informações inseridas devem ser verificadas antes de uso em produção.

---
**Autor:** Dionatan Diego  
```
