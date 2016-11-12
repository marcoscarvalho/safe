#Safe Management
==============
## Atores
 - Desenvolvedor
 - Coordenador 
 - Gerente

## Problema
Hoje existe-se um cenário onde tem-se várias demandas planejadas e/ou demandas com dias marcados. Mas em todos os momentos, entram-se novas mini-demandas que não são planejadas quebrando o planejamento atual e deixando todos os envolvidos não confortáveis.

## Objetivo
 
## Histórias
 
###
 
## Necessidades
 - Necessidade de criar um histórico por executor
 - Necessidade de criar um histórico por coordenador
 - Necessidade de criar um histórico por gerente

## Regras
 - Uma demanda sem planejamento deve entrar após todas as demais demandas.
 - Se uma demanda entrar com dia marcado, deve arrastar todas as demais planejadas que serão afetadas, indicando nessas demandas que houve arrasto.
 - Caso conflite com demanda agendada, validar qual a prioridade é maior e informar o usuário.

### Demanda
 - Uma nova demanda deve ter um título.
 - Uma demanda pode ter descrição, data de início, data de fim, duração planejada, checklist, prioridade, criador, executor e tags.
 
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