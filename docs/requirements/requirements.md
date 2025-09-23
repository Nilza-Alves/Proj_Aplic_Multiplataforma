# Requisitos do Sistema - Instituto Além dos Olhos

## Requisitos Funcionais (RF)
- RF01: Permitir cadastro de participantes (nome, idade, contato, etc.).
- RF02: Permitir cadastro de atividades/eventos (nome, data, local).
- RF03: Registrar presença dos participantes em atividades/eventos.
- RF04: Gerar relatórios simples de frequência e participação.
- RF05: Permitir que voluntários registrem informações de forma rápida.

## Requisitos Não-Funcionais (RNF)
- RNF01: O sistema deve ser multiplataforma (web e mobile).
- RNF02: A interface deve ser simples e acessível para diferentes perfis de usuários.
- RNF03: Os dados devem ser armazenados de forma segura.


## Regras de Negócio
- Cada participante só pode ser registrado em uma atividade uma vez por data.
- Voluntários só podem marcar presença em atividades nas quais estão cadastrados.
- Os relatórios devem ser exportáveis em formato PDF ou Excel.

## Perfis de Usuário
- **Administrador**: cadastra atividades, participantes e gera relatórios.
- **Voluntário**: registra presenças e consulta atividades.
- **Beneficiário**: participa das atividades (não acessa diretamente o sistema).

## Histórias de Usuário
- Como **administrador**, quero cadastrar atividades para organizar o calendário.  
- Como **voluntário**, quero marcar a presença dos participantes de forma rápida.  

