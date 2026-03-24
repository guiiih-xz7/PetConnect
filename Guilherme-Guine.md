# Relatório de Desenvolvimento - Guilherme Guiné

**Papel no Projeto:** Product Owner (PO) e Desenvolvedor

## Atividades Realizadas (Sprint 1)

### 1. Modelagem do banco de dados para "Animais" (Tarefa #01 do Backlog)
* **Descrição:** Fui responsável por criar a estrutura inicial do banco de dados para armazenar os pets. Desenvolvi a tabela `animais` contendo os campos essenciais como `id`, `nome`, `especie`, `raca`, `idade`, `status_adocao` e `data_resgate`.
* **Tecnologias utilizadas:** Modelagem SQL.

### 2. Modelagem do banco de dados para "Usuários" (Tarefa #09 do Backlog)
* **Descrição:** Estruturei a tabela `usuarios` para gerenciar as contas do sistema. Criei os campos necessários para autenticação (`email`, `senha_hash`) e adicionei a coluna `nivel_acesso` para diferenciar os administradores do abrigo dos adotantes comuns.
* **Tecnologias utilizadas:** Modelagem SQL.

### 3. Funcionalidade de upload de fotos (Tarefa #03 do Backlog)
* **Descrição:** Implementei a lógica de backend para o recebimento de arquivos de imagem. O sistema valida a extensão do arquivo (aceitando apenas JPG ou PNG), trata o tamanho da imagem e salva a referência/caminho no banco de dados vinculada ao ID do animal.
* **Tecnologias utilizadas:** Lógica de Backend (APIs).