# Plataforma de Mentoria para Estudantes

Este projeto é uma aplicação web desenvolvida em Spring Boot que visa conectar estudantes (mentorados) a profissionais experientes (mentores) para sessões de mentoria. A plataforma permite o cadastro de usuários, a criação de perfis e o gerenciamento de solicitações de mentoria.

## Tecnologias Utilizadas

Java 17: Versão da linguagem de programação.
Spring Boot 3.x: Framework principal para o desenvolvimento da aplicação.
Spring Data JPA: Para persistência de dados e abstração do acesso ao banco de dados.
H2 Database: Banco de dados em memória, selecionado pela simplicidade de configuração para o ambiente de desenvolvimento.
Thymeleaf: Motor de templates para a renderização das páginas web (UI).
Maven: Ferramenta de gerenciamento de dependências e build do projeto.
SpringDoc OpenAPI (Swagger): Para documentação automática e interativa da API REST.
Jakarta Bean Validation: Para validação dos dados de entrada.

## Como Executar

Siga os passos abaixo para clonar, configurar e executar a aplicação localmente.

### 1. Pré-requisitos

Certifique-se de que você tem o seguinte software instalado em sua máquina:
JDK 17 ou superior.
Apache Maven 3.8 ou superior.

### 2. Clonagem do Repositório

Clone este repositório para sua máquina local usando o seguinte comando:
```bash
git clone https://github.com/savinoo/mentoria-estudantes.git
```

### 3. Navegação para o Diretório

Acesse o diretório raiz do projeto:
```bash
cd mentoria-estudantes
```

### 4. Execução da Aplicação

Utilize o Maven para compilar e executar a aplicação Spring Boot:
```bash
mvn spring-boot:run
```


A aplicação iniciará e estará disponível em alguns instantes.

### 5. Acesso

Após a inicialização, você pode acessar os seguintes URLs no seu navegador:
Aplicação Web: http://localhost:8080
Documentação da API (Swagger UI): http://localhost:8080/swagger-ui.html
Console do Banco H2: http://localhost:8080/h2-console
JDBC URL: jdbc:h2:mem:testdb
User Name: sa
Password: password



---
