# Relatório de Avaliação de Usabilidade

**Projeto:** Agendamento-Fullstack  
**Responsável:** Tiago Martins
**Data:** 07/10/2026  
**Branch:** `relatorio-usabilidade`  

---

## 1. Objetivos da Avaliação
Encontrar erros na usabilidade e acessibilidade do sistema.

---

## 2. Escopo e Metodologia
- **Público-alvo / Personas:** Usuários finais, administradores, etc.
- **Ambiente testado:** Navegador Chrome.
- **Método utilizado:** Avaliação heurística / Utilização do AMAWeb para teste de acessibilidade
---

## 3. Principais Achados e Problemas Identificados

| ID | Tela / Componente | Descrição do Problema | Gravidade |
| :--- | :--- | :--- | :--- |
| **DEV.Horários** | Relógio no canto inferior esquerdo | Horário incorreto. Está usando fuso UTC ao invés de UTC-3 | Baixa |
| **Phone Mode** | Menu de Navegação | Menu lateral incompleto e pouco intuitivo no modo celular. | Média |
| **Portal Arthur Saboya** | Preview de e-mails | Erro ao enviar e-mail de teste. | Alta |
| **Portal Arthur Saboya** | Pré-Projeto | Erro ao finalizar abertura de requisição em Pré-Projeto. | Alta |
| **Pré-Projeto** | Pré-Projeto | Erro failed to fetch em qualquer funcionalidade relativa à Pré-Projeto. | Alta |
| **Agendamentos SMUL** | Menu Lateral | Menu lateral do Gerenciador de Agendamentos pouco intuitivo quando minimizado. | Média |
| **Portal Arthur Saboya** | Processos em Trâmite | Campo "Qual é a sua dúvida?" possui limite mínimo de caracteres para ativar botão "Continuar" mas número mínimo de caracteres não é especificado. | Média |
| **Portal Arthur Saboya** | Processos em Trâmite | Campo "Selecione a ocorrência relacionada à sua dúvida", relacionado ao tipo de agendamento "Atendimento técnico sobre comunique-se" só aparece após clicar em "Continuar" com mensagem de erro e acima do tipo de agendamento. | Alta |
| **Portal Arthur Saboya** | Horário | Campo "Horário de preferência (9h às 16h)" permite inserção de horários fora da faixa disponível e só avisa que o horário está indisponível no botão "Enviar solicitação" e não em "Continuar", na tela anterior. | Média |
| **Agendamentos SMUL** | Menu Lateral | Campos "Página Inicial" e "Agendamentos" possuem mesmo link de destino. | Alta |
| **Agendamentos SMUL** | Usuários | "Erro ao buscar usuário LDAP_BASE_DN não configurado no ambiente" ao tentar criar novo usuário. | Alta |
| **Portal Arthur Saboya** | Processos em Trâmite | O sistema permite agendar atendimento em dias como feriados e/ou pontos facultativos. | Média |
| **Agendamentos SMUL** | Acessibilidade | Tema escuro está escurecendo apenas o menu lateral e alguns poucos pontos de outras telas. | Alta |
| **Agendamentos SMUL** | Acessibilidade | Tema escuro está escurecendo apenas o menu lateral e alguns poucos pontos de outras telas. | Alta |
| **Agendamentos SMUL** | Agendamentos | Ao clicar em Agendamentos, a tela já abre filtrada com a data atual, levando a primeiro momento, não ter ou ter poucos processoa abertos. | Alta |
---

