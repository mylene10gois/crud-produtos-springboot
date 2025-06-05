Este projeto é uma aplicação full stack com **Java (Spring Boot)** no backend e **Angular** no frontend, que permite realizar operações de cadastro, listagem, edição e exclusão de produtos.

#Tecnologias Utilizadas

- Backend:
  - Java 17
  - Spring Boot 3
  - Spring Data JPA
  - H2 Database (em memória)
- Frontend:
  - Angular 17+
  - TypeScript
  - Bootstrap (opcional)

---

#Como Executar

#Backend (Spring Boot)

1. **Pré-requisitos:**
   - Java 17+ instalado
   - Maven instalado

2. **Clonar o repositório e entrar na pasta do backend:**

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd crud-produtos-springboot
```

3. **Rodar a aplicação:**

```bash
./mvnw spring-boot:run   # Linux/macOS
mvnw.cmd spring-boot:run # Windows
```

4. **Acesso:**
   - API REST: `http://localhost:8080/produtos`
   - Console do banco de dados H2: `http://localhost:8080/h2-console`
     - JDBC URL: `jdbc:h2:mem:produtosdb`
     - Usuário: `sa`
     - Senha: *(em branco)*

---

#Frontend (Angular)

1. **Pré-requisitos:**
   - Node.js + npm instalados
   - Angular CLI instalado (`npm install -g @angular/cli`)

2. **Instalar dependências:**

```bash
cd frontend-angular-produtos
npm install
```

3. **Executar a aplicação:**

```bash
ng serve
```

4. **Acessar no navegador:**
   - `http://localhost:4200`

---

#Funcionalidades

- Cadastrar novo produto
- Listar produtos em tabela
- Editar produto
- Excluir produto
- Paginação (via backend com `Pageable`)

---

#Estrutura dos Diretórios

```
crud-produtos-springboot/
└── Backend Spring Boot

frontend-angular-produtos/
└── Frontend Angular
```

