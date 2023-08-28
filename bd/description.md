# Base de dados
O recorte da base de dados foi extraída do data lake da OpenAQ, disponível publicamente no BigQuery, por meio da seguinte query:
```
select * from bigquery-public-data.openaq.global_air_quality
where country = "BR" 
```
# Saiba mais
A base da OpenAQ foi construída por meio de parcerias governamentais a nível de pesquisa para conscientização pública e a regulamentação ambiental, visando ao entendimento e ao combate da poluição do ar e seus impactos negativos.
Leia mais em:
https://openaq.org/
