# Desafio Processo Seletivo - Dados

Estamos muito felizes que tenha chegado nessa fase!  
Essa etapa do processo tem como objetivo avaliar as habilidades técnicas do candidato.

## Desafio

O desafio consiste em extrair algumas métricas dos dados do ENEM disponibilizados anualmente pelo INEP.

Neste desafio usaremos os [microdados de Enem]([https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem)) de 2019.
Link direto para download dos dados: [https://download.inep.gov.br/microdados/microdados_enem_2019.zip](https://download.inep.gov.br/microdados/microdados_enem_2019.zip)

O entregável deve ser um repositório git com o código necessário para resolver as etapas abaixo.  Arquivos auxiliares como `Dockerfile`,`docker-compose.yml`ou outros também devem ser incluídos caso sejam utilizados.

 1. Os dados devem ser carregados em um banco de dados relacional. Preferencialmente deve ser utilizado PostgreSQL ou MySQL. SQLite também pode ser escolhido como alternativa mais simples.
 2. Calcular a média das notas por estado dos alunos não "treineiros".
 3. Calcular o percentual de acerto de cada habilidade das questões de "Ciências da Natureza", limitando aos 5 estados com maior quantidade de inscritos.

Os itens 2 e 3 devem ser feitos em SQL.  
O item 1 pode ser resolvido com qualquer linguagem ou ferramenta.  
Caso o volume de dados seja um problema, o candidato pode limitar os microdados nas 50.000 primeiras linhas do arquivo.  
Além do dicionário, os arquivos `INPUTS/INPUT_SPSS_MICRODADOS_ENEM_2019.sps` e `INPUTS/INPUT_SPSS_ITENS_PROVA_2019.sps` contêm uma breve descrição das colunas dos microdados.  

## Critérios de Avaliação
-  Organização e legibilidade do código.
-  Boas praticas de engenharia de software.
-  Conhecimentos de SQL.

Caso haja alguma dúvida estamos à disposição por email.  
Boa sorte!
