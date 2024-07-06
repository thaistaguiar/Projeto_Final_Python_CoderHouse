# Projeto Final - Pipeline ETL com BrasilAPI

## Descrição

<p>Este é um projeto desenvolvido no curso de Python da CoderHouse que implementa um pipeline ETL (Extração, Transformação e Carga) usando a BrasilAPI.<br>
O Objetivo deste projeto é extrair dados de bancos, corretoras e feriados nacionais, transformá-los de acordo com a necessidade e carregá-los num banco de dados para consulta. O projeto conta, ainda, com um sistema de notificação de falhas do processo de extração.</p>

## Fases do Projeto

+ Escolher uma API
+ Fazer a extração de pelo menos 3 tabelas
+ Realizar os tratamentos devidos das tabelas
+ Adicionar os dados tratados em um banco de dados para consulta
+ Validar as tabelas disponibilidades

## Processos

+ **Extração:** Os dados são extraídos de três fontes da BrasilAPI (`/banks`, `/feriados`, `/corretoras`)
+ **Transformação:** Os dados são transformados em dataframes pandas.
+ **Carga:** Os dados transformados são carregados em um banco de dados.
+ **Alertas:** Um sistema de alerta notifica falhas no processo de extração utilizando a biblioteca `plyer`.

## Hipóteses

+ Em qual estado constam mais corretoras com status cancelada?
+ Em qual região estão as corretoras com maior patrimônio líquido?
+ Analisar se existe uma relação entre as corretoras de status cancelados com o valor de seus respectivos patrimônios.
+ Existe relação entre a data de registro da corretora com a situação de seu status? 
