# Projeto Final - Pipeline ETL com BrasilAPI

## Descrição

<p>Este é um projeto desenvolvido no curso de Python da CoderHouse que implementa um pipeline ETL (Extração, Transformação e Carga) usando a BrasilAPI.<br>
Neste projeto, iremos analisar se existe uma relação entre o status da corretora com o valor de seus respectivos patrimônios ou com a data de seu registro. Iremos extrair dados da API escolhida, transformá-los de acordo com a necessidade e carregá-los num banco de dados para consulta. O projeto conta, ainda, com um sistema de notificação de falhas do processo de extração.</p>

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
