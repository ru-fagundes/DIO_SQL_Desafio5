# :octocat: Desafio V :octocat:


## 🎯 Objetivo
Personalizando o Banco de Dados com Índices e Procedures

## 📋 Descrição do Desafio

>- ### Parte 1 – Criando índices em Banco de Dados 
- O que será levado em consideração para criação dos índices? 
- Quais os dados mais acessados 
- Quais os dados mais relevantes no contexto 

  A criação do índice pode ser criada via ALTER TABLE ou CREATE Statement, como segue o exemplo: 
ALTER TABLE customer ADD UNIQUE index_email(email); 
CREATE INDEX index_ativo_hash ON exemplo(ativo) USING HASH; 

#### Perguntas:  
- Qual o departamento com maior número de pessoas? 
- Quais são os departamentos por cidade? 
- Relação de empregados por departamento 

>- ### Parte 2 - Utilização de procedures para manipulação de dados em Banco de Dados 
  Criar uma procedure que possua as instruções de inserção, remoção e atualização de dados no banco de dados. As instruções devem estar dentro de estruturas condicionais (como CASE ou IF).  
  Além das variáveis de recebimento das informações, a procedure deverá possuir uma variável de controle. Essa variável de controle irá determinar a ação a ser executada. Ex: opção 1 – select, 2 – update, 3 – delete. 
  

## ☑️ Tecnologias Necessárias:
>- MySQL Workbench


### 📝👩‍💻 Autor(a):
> Rubia Fagundes
