#Safe Management
==============
## Atores
 - Executor

## Problema
Hoje existe-se um cenário onde tem-se várias demandas planejadas e/ou demandas com dias marcados. Mas em todos os momentos, entra-se novas mini-demandas que não são planejadas quebrando o planejamento atual e deixando todos os envolvidos não confortáveis.
 
 - Demandas padrões entram diretamente após todas as demandas.
 - Demandas entrando-se a todos os momentos e pode-se ter demandas com dias marcados.
 - Caso entre alguma demanda no meio de outras, é necessário arrastar as demandas (tirando as agendadas).
 - Caso conflite com demanda agendada, validar se a prioridade é maior.
 - Necessidade de criar-se um histórico por executor
 - Necessidade de criar um histórico por gerente

### Demanda
 - Toda demanda deve ter um nome 
 - A demanda pode ter um dono e um executor
 - A demanda pode ter horário de início e horário de fim.
 - A demanda pode ter quantidade de horas necessárias para sua realização
 - A demanda pode ter tags
 
### Tag
 - Pode ser criado qualquer tipo de tags
 
 Exemplos:
 - Pode existir uma tag de "horário de trabalho extendido ativo"
 
### Prioridades
 - Pode-se adicionar quantas prioridades forem necessárias
 - Toda prioridade deve ter um nome, uma descrição e uma cor
 - Enquadrar-se em um grau de prioridade
 
 Exemplos:
 - Prioridade 0 - Problemas com sistemas de vendas
 - Demanda Agendada
 - Prioridade 1 - Demanda em progresso
 
### Demanda Planejada
 - Adicionar demanda planejada. Horário de início e fim.
 - Marcar a demanda de uma forma diferente caso seja agendada.
 - Demanda com dia agendado: Não pode-se modificar o dia dessa demanda.
 
### Horário de Trabalho
 - O executor pode ter um horário de trabalho
 - Um executor pode ter um horário de trabalho flexível durante a semana
 - Um executor pode ter um horário de extensão padrão
 
### Histórico
 - Mostrar em uma linha do tempo as demandas, quantidade de tempo planejado, executado e a prioridade dessa demanda.

## Objetivo
 
## Histórias
 
###