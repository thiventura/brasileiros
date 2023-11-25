# Brasileiros

Script para criação de uma banco de dados contendo todos os brasileiros seguindo estatísticas do IBGE. Para cada brasileiro há os atributos de gênero, raça, idade, escolaridade, renda e Estado de moradia.

O script insere +200 milhões de registros, totalizando quase 40GB em uma base do SQLite. Os atributos são inseridos em tabelas separadas e depois mesclados. Cada inserção de atributo pode levar 1 hora dependendo do computador.

## Melhorias
- Ainda não estou satisfeito com as estimativas de renda. Caso alguém queira contribuir com mudança de código, será muito bem vindo.
- Uma boa evolução seria a adição de municípios.

## Aplicação
Eu criei uma aplicação para acessar os dados. Ela está disponível neste link: https://lookerstudio.google.com/s/qQjhmiWg1AE 

Infelizmente não consegui colocar no ar todos os Estados do Brasil (falta um servidor melhor para carregar +200 milhões de registros...), mas pelo menos os dados de Mato Grosso estão disponíveis. 
