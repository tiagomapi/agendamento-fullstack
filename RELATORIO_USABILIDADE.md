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
| **Preview de e-mails** | Preview de e-mails | Erro ao enviar e-mail de teste. | Alta |
| **Portal Arthur Saboya** | Pré-Projeto | Erro ao finalizar abertura de requisição em Pré-Projeto. | Alta |
| **Pré-Projeto** | Pré-Projeto | Erro failed to fetch em qualquer funcionalidade relativa à Pré-Projeto. | Alta |
| **Menu Lateral** | Menu Lateral | Menu lateral do Gerenciador de Agendamentos pouco intuitivo quando minimizado. | Média |

---

