# pokedash

Os Primeiros 151.

Dash desenvolvido por entusiastas de dados da Artplan, para desenvolvimento e aprendizado de programação voltado para dados. O Dash consistirá de informções dos status de todos os 151 pokemón da primeira geração do aclamado jogo de gameboy.

Utilizaremos as seguintes ferramentas:

Pokeapi
https://pokeapi.co/

Site que reúne as informações dos dados e status de todos os jogos pokemon. O site disponibiliza uma interface RESTful API para podermos conectar e buscar as informaçÕes que queremos.

Servidor (VM) na Google Cloud Platform
Um servidor Ubuntu criado dentro da plataforma do Google para centralizar e operacionalizar o backend do projeto.

MySQL
Serviço de banco de dados que servirá de repositório das tabelas que iremos transformar e carregar para o dataviz. O MySQL funcionará como um data warehouse do nosso projeto.


Airflow
Ferramenta de orquestralização do fluxo de trabalho, de ponta a ponta, executando os scripts de forma automatizada.

Power BI
Ferramenta de DataViz para montarmos o dash interativo.