# Sistema de Gestão de Atividades e Participantes: Instituto Além dos Olhos

**Resumo:**  
Plataforma multiplataforma para cadastro de participantes, controle de frequência, calendário de aulas/eventos e geração de relatórios simples, visando reduzir o trabalho manual em planilhas e facilitar a prestação de contas e comunicação interna.

**Problema:**  
A ONG registra presença e informações dos beneficiados manualmente em planilhas, o que demanda muito tempo e dificulta a geração de relatórios.

**Objetivo:**  
Criar um sistema simples e responsivo que permita:
- Cadastro de alunos e voluntários;
- Registro de frequência por atividade;
- Calendário de aulas/eventos;
- Relatórios automáticos de frequência e participação.

**Escopo (Etapa 1: planejamento):**
- Documento de requisitos (RF / RNF);
- Arquitetura do sistema (frontend/backend/banco);
- Modelo de dados (ER);
- Protótipos

**Relacionamento com ODS 11:**  
Contribui para cidades e comunidades mais inclusivas e resilientes ao fortalecer a gestão de ações comunitárias e otimizar recursos.

**Visão geral da arquitetura proposta:**
- Frontend Web: React (SPA) — admin/relatórios.
- Frontend Mobile: Flutter ou React Native — chamada rápida.
- Backend: Node.js + Express (REST API).
- Banco de Dados: PostgreSQL.
- Autenticação: JWT (roles: admin, professor).

**Tecnologias sugeridas:**  
React, Flutter (ou React Native), Node.js, Express, PostgreSQL, Figma, Swagger.

**Cronograma sugerido (Etapa 2 — implementação):**
- Configuração inicial e backend básico → Sprint 1
- Modelagem e APIs → Sprint 2
- Frontend Web → Sprint 3
- Mobile (chamada) → Sprint 4
- Testes, ajustes e entrega → Sprint 5

**Equipe e papéis:**  
- [Nilza] — Requisitos / Documentação  
- [Victor e Paulo Sérgio] — Modelagem de BD / APIs  
- [Antunis Jr] — Protótipos / UX  
- [Cláudio] — Integração / Cronograma

**Links:**  
- Protótipos (Figma): (colocar link)  

## Cronograma para Etapa 2 (Implementação)

| Etapa | Atividade | Período |
|-------|-----------|----------|
| 1 | Configuração inicial do ambiente (repositório, pastas, dependências) | Semana 1 |
| 2 | Implementar cadastro de participantes e voluntários | Semana 2 |
| 3 | Implementar cadastro de atividades | Semana 3 |
| 4 | Implementar registro de presenças | Semana 4 |
| 5 | Implementar relatórios | Semana 5 |
| 6 | Testes e ajustes finais | Semana 6 |
| 7 | Entrega final do sistema | Semana 7 |

