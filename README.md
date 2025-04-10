## Notebooks criados no Databricks

- Camada Bronze Link: https://github.com/hannemanbr/PUC-RIO-MVP/blob/main/Thomas-Notebook-PUC-RIO%20-%20Camada%20Bronze.ipynb
- Camada Silver Link: https://github.com/hannemanbr/PUC-RIO-MVP/blob/main/Thomas-Notebook-PUC-RIO%20-%20Camada%20Silver.ipynb
- Camada Gold Link: https://github.com/hannemanbr/PUC-RIO-MVP/blob/main/Thomas-Notebook-PUC-RIO%20-%20Camada%20Gold.ipynb
- Relatórios Link: https://github.com/hannemanbr/PUC-RIO-MVP/blob/main/Thomas-Notebook-PUC-RIO%20-%20Relatorios.ipynb

## Documento completo com os dicionários de dados e todos os detalhes do processo
Acesse: https://github.com/hannemanbr/PUC-RIO-MVP/blob/main/MVP%20Engenharia%20de%20Dados%202025.pdf

        
## Coleta
O IMDb é uma Base de Dados de Filmes na Internet, contendo informações de séries, documentários, videogames e outras mídias. Todos os dados utilizados neste trabalho foram coletados nos dados públicos disponibilizados pelo IMDb (Internet Movie Database) no link https://datasets.imdbws.com/ 
Utilizando a base de acesso publico no endereço https://datasets.imdbws.com/ que disponibiliza os arquivos no formato TSV compactado no padrão GZIP:

Todos os arquivos estão compactados (formato Gnu Zip):
- title.principals.tsv.gz
- title.basics.tsv.gz
- name.basics.tsv.gz
- title.akas.tsv.gz
- title.crew.tsv.gz
- title.episode.tsv
- title.ratings.tsv.gz

## Objetivo
Nesse MVP optei por analisar os dados públicos disponibilizados pelo IMDb (Internet Movie Database) no link https://datasets.imdbws.com/ por se tratar de um conteúdo que familiaridade. 
Através da análise dos arquivos e da documentação disponibilizada no link https://developer.imdb.com/non-commercial-datasets/, procuro responder às seguintes perguntas:

- Quantidade de títulos lançados no Brasil por categoria e década (80, 90, etc.)?
- Qual categoria teve mais lançamentos no Brasil por década?
- Todos os títulos que possuem nome exclusivo no Brasil (Com nome diferente do nome original ou comercial).
- Qual a porcentagem de pessoas que atuaram como Ator ou Atriz em Títulos do tipo Filmes, Curtas ou Vídeo, lançados no Brasil?
- Porcentagem de atores do sexo feminino e masculino que atuaram nos títulos do tipo Filme em cada década existente na base.
- Filmes lançados no Brasil, onde o Diretor(a) atuou como Ator/Atriz.
- Ranking dos diretores com títulos lançados no Brasil.

- 


