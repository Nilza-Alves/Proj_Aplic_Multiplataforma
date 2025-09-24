# Especificação de APIs - Instituto Além dos Olhos

## Endpoints Planejados

### 1. Participantes
- **POST /participantes** → Cadastrar novo participante  
  - Entrada: nome, idade, contato  
  - Saída: confirmação do cadastro  

- **GET /participantes** → Listar todos os participantes  
  - Saída: lista com id, nome, idade, contato  

### 2. Voluntários
- **POST /voluntarios** → Cadastrar novo voluntário  
  - Entrada: nome, função, contato  
  - Saída: confirmação  

- **GET /voluntarios** → Listar voluntários  

### 3. Atividades
- **POST /atividades** → Criar nova atividade  
  - Entrada: nome, data, local, descrição  
  - Saída: confirmação  

- **GET /atividades** → Listar atividades  

### 4. Presenças
- **POST /presencas** → Registrar presença de participante em uma atividade  
  - Entrada: id_participante, id_atividade, status (presente/ausente)  
  - Saída: confirmação  

- **GET /presencas/{id_atividade}** → Listar presenças de uma atividade  
  - Saída: lista de participantes e status de presença  

## Autenticação
- Administrador: pode cadastrar e consultar tudo.  
- Voluntário: pode registrar presenças e consultar atividades.  
