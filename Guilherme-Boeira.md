# Relatório de Desenvolvimento - Guilherme Boeira

**Papel no Projeto:** Scrum Master (SM) e Desenvolvedor

## Atividades Realizadas (Sprint 1)

### 1. Criação da API de registro e autenticação (Tarefa #10 do Backlog)
* **Descrição:** Desenvolvi a lógica de segurança e os endpoints de backend para o login do sistema (`POST /login` e `POST /register`). Apliquei criptografia nas senhas antes de salvar no banco e implementei a geração de tokens JWT para proteger as rotas restritas do abrigo.
* **Tecnologias utilizadas:** Autenticação Web (JWT) e Criptografia.

### 2. Desenvolvimento do formulário de registro de animais (Tarefa #02 do Backlog)
* **Descrição:** Criei a interface de usuário (Frontend) contendo o formulário visual para cadastrar novos animais. Realizei a integração desta tela com o backend criado pelo meu parceiro de equipe, garantindo que os dados digitados sejam enviados corretamente para o banco.
* **Tecnologias utilizadas:** HTML, CSS e JavaScript.

### 3. Criação da interface de listagem de animais (Tarefa #04 do Backlog)
* **Descrição:** Projetei e codifiquei a tela principal (Galeria de Adoção) onde os animais aparecem em formato de "cards". A página consome os dados do banco e renderiza dinamicamente a foto, o nome e o status de adoção de cada pet na tela.
* **Tecnologias utilizadas:** Frontend (Grid/Flexbox) e consumo de API.