# task-manager-java
Task Manager API. Implementada em Java com o framework Spring Boot para gerenciar a criação e exclusão de tarefas.
## 🛠️ Tecnologias Utilizadas

* **Java:** Versão [INFORME A VERSÃO DO SEU JDK: Exemplo: 17, 21, etc.]
* **Spring Boot:** Versão [INFORME A VERSÃO DO SEU SPRING BOOT: Exemplo: 3.2.5]
* **Maven** ou **Gradle**
* **Banco de Dados:** [INFORME QUAL BANCO DE DADOS VOCÊ USOU: Exemplo: H2 Database, PostgreSQL, etc.]

## ⚙️ Como Executar o Projeto Localmente

### Pré-requisitos
Certifique-se de ter o seguinte instalado em sua máquina:
* JDK (Java Development Kit) [Versão 21]
* Maven ou Gradle
* Git

### Passos de Execução
1.  **Clone o repositório:**
    ```bash
    git clone 
    cd 
    ```

2.  **Execute a Aplicação:**
    * **Com Maven:**
        ```bash
        mvn spring-boot:run
        ```
    * **Com sua IDE (IntelliJ, VS Code, etc.):**
        Abra o projeto e execute a classe `Application.java`.

A aplicação estará disponível em `http://localhost:8080/task`.

## 📌 Endpoints da API

Você pode testar a API usando ferramentas como **HTTPie**  ou Postman.

| Método | Endpoint | Descrição | Exemplo de Uso (HTTPie) |
| :--- | :--- | :--- | :--- |
| **GET** | `/task` | Retorna todas as tarefas. | `http localhost:8080/task` |
| **POST** | `/task` | Cria uma nova tarefa. | `http POST localhost:8080/task titulo="Estudar Spring"` |
| **DELETE** | `/task/{id}` | Remove uma tarefa pelo ID. | `http DELETE localhost:8080/task/1` |

## ✍️ Autor

* **Si Lima** - 
