# 🥟 Baozi Store API - Sistema de Controlo e Pedidos

Repositório desenvolvido no âmbito de um projeto académico (Uninter), com o objetivo de construir uma API REST robusta em Java utilizando **Spring Boot** para gerir o controlo de clientes, produtos (pão chinês / Baozi) e transações de pedidos.

---

## 🚀 Tecnologias Utilizadas
* **Java 17+**
* **Spring Boot 3.x** (Spring Web, Spring Data JPA)
* **Base de Dados H2** (Em memória para testes rápidos e persistência local)
* **Maven** (Gestão de dependências)
* **Postman** (Testes de integração e validação de endpoints)

---

## 📋 Funcionalidades da API
O sistema implementa o fluxo completo de operações (CRUD) para os seguintes módulos:
1. **Clientes (`/clientes`):** Registo e consulta de clientes da loja (ex: *Guilherme Henrique de Almeida - RU: 5539852*).
2. **Produtos (`/produtos`):** Gestão do catálogo de produtos comercializados, como o *Baozi Tradicional*.
3. **Pedidos (`/pedidos`):** Associação de clientes, produtos e quantidades para o registo de transações comerciais.

---

## 🛠️ Endpoints Principais

| Método | Endpoint | Descrição |
| :--- | :--- | :--- |
| **POST** | `/clientes` | Cadastra um novo cliente |
| **GET** | `/clientes` | Lista todos os clientes registados |
| **POST** | `/produtos` | Adiciona um produto ao catálogo |
| **GET** | `/produtos` | Lista os produtos disponíveis |
| **POST** | `/pedidos` | Regista um novo pedido associando cliente e produto |
| **GET** | `/pedidos` | Lista o histórico de pedidos |

---

## ⚙️ Como Executar o Projeto Localmente

1. Certifique-se de ter o **Java** e o **Maven** instalados no seu computador.
2. Clone este repositório ou abra o projeto na sua IDE de preferência (como o **Eclipse** ou IntelliJ).
3. Execute a classe principal do Spring Boot (`BaoziStoreApplication.java`).
4. O servidor será iniciado na porta padrão `8080`.
5. Utilize ferramentas como o **Postman** para interagir com os endpoints descritos acima.

---

## ✒️ Autor
* **Guilherme Henrique de Almeida**  
* **RU:** 5539852
