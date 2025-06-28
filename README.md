# ✅ AppChecklist – Sistema de Checklists (Entrevista Técnica)

Este projeto foi desenvolvido como parte de uma entrevista técnica, com o objetivo de demonstrar conhecimentos em desenvolvimento back-end utilizando Java com Spring Boot.  
O sistema consiste em uma API de gerenciamento de **checklists**, com autenticação simples.

---

## 🚀 Tecnologias utilizadas

- Java 17
- Spring Boot
- Spring Data JPA
- Maven
- Banco de dados H2 (ou outro configurável)
- Eclipse (estrutura de projeto gerada no Eclipse)

---

## 📁 Estrutura do Projeto

src/
├── main/
│ ├── java/
│ │ └── br/com/acobrazil/app/checklist/
│ │ ├── check/ # Lógica do checklist (modelo, controller, service, repository)
│ │ ├── login/ # Autenticação básica
│ │ └── config/ # Configuração de CORS
│ └── resources/
│ └── application.properties


---

## ⚙️ Como rodar localmente

### ✅ Pré-requisitos

- Java 17+
- Maven 3+

### ▶️ Executando

```bash
# Clone o repositório
git clone https://github.com/seuusuario/appchecklist.git
cd appchecklist

# Compile o projeto
./mvnw clean install

# Rode a aplicação
./mvnw spring-boot:run

