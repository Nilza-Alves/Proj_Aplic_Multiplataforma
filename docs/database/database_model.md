# Modelo de Dados>>> Instituto Além dos Olhos

## Entidades 
- **Participante**  
  - id  
  - nome  
  - idade  
  - contato  

- **Voluntário**  
  - id  
  - nome  
  - função  
  - contato  

- **Atividade**  
  - id  
  - nome  
  - data  
  - local  
  - descrição  

- **Presença**  
  - id  
  - id_participante  
  - id_atividade  
  - status (presente/ausente)  

## Relacionamentos
- Um **participante** pode estar em várias atividades (N:N).  
- Um **voluntário** pode coordenar várias atividades (1:N).  
- Uma **atividade** pode ter muitos participantes.  
- A tabela **presença** conecta participante + atividade.  

## Diagrama ER 

Participante (1) ---- (N) Presença (N) ---- (1) Atividade
Voluntário (1) ---- (N) Atividade


## Dicionário de Dados
- **Participante**: dados dos beneficiados.  
- **Voluntário**: dados de quem aplica as atividades.  
- **Atividade**: eventos da ONG.  
- **Presença**: registro da frequência dos participantes.  


