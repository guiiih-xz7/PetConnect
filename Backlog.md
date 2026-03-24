# 📋 Backlog do Produto - PetConnect

**Responsável (Product Owner):** Guilherme Guiné

Este documento contém a lista de todas as funcionalidades, requisitos e tarefas técnicas necessárias para o desenvolvimento do sistema PetConnect. As tarefas estão organizadas por módulos e priorizadas para as futuras Sprints.

## 🐾 Módulo 1: Gestão de Animais (Prioridade Alta)
1. Modelação da base de dados para a entidade "Animais".
2. Desenvolvimento do formulário de registo de novos animais (Nome, espécie, raça, idade).
3. Implementação da funcionalidade de upload de fotografias do animal.
4. Criação da interface de listagem de animais no sistema.
5. Desenvolvimento de filtros de pesquisa (por porte, idade e temperamento).
6. Registo de histórico médico e controlo de vacinação.
7. Implementação da alteração de estado do animal (Ex: Disponível, Em tratamento, Adotado).
8. Exportação da ficha completa do animal para formato PDF.

## 👤 Módulo 2: Gestão de Utilizadores e Autenticação (Prioridade Alta)
9. Modelação da base de dados para "Utilizadores" e "Adotantes".
10. Criação da API de registo e autenticação (Login com JWT).
11. Implementação de níveis de acesso (Administrador do abrigo vs. Voluntário).
12. Desenvolvimento da página de perfil do utilizador (edição de dados).
13. Mecanismo de recuperação de palavra-passe.

## 🏡 Módulo 3: Processo de Adoção (Prioridade Média-Alta)
14. Criação do formulário público de interesse em adoção.
15. Desenvolvimento do painel de triagem de adotantes para os administradores.
16. Sistema de aprovação ou rejeição de candidaturas de adoção.
17. Funcionalidade para agendamento de visitas presenciais ao abrigo.
18. Registo do histórico de adoções bem-sucedidas.
19. Envio de e-mail automático após a aprovação da adoção.

## 📦 Módulo 4: Controlo de Recursos e Stock (Prioridade Média)
20. Criação do módulo de registo de entrada e saída de ração.
21. Registo de doações financeiras e de materiais recebidos.
22. Cadastro de fornecedores e parceiros veterinários.
23. Sistema de alertas automáticos para stock baixo de alimentos.
24. Geração de relatórios de despesas mensais por animal.

## ⚙️ Módulo 5: Interface, UX e Infraestrutura (Prioridade Média-Baixa)
25. Desenvolvimento do Dashboard principal com estatísticas (total de animais, adoções no mês).
26. Criação de uma página de Perguntas Frequentes (FAQ) sobre o processo de adoção.
27. Integração com API de mapas (Google Maps) para mostrar a localização do abrigo.
28. Adaptação de todos os ecrãs para dispositivos móveis (Design Responsivo).
29. Implementação de testes unitários nas rotas principais de registo e adoção.
30. Configuração do deploy (publicação) da aplicação e rotina de cópia de segurança (backup) da base de dados.
