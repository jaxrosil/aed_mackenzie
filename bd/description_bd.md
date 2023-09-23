# Base de dados
O recorte da base de dados foi extraída do data lake da OpenAQ, disponível publicamente no BigQuery, por meio da seguinte query:
```sql
select * from bigquery-public-data.openaq.global_air_quality
where country = "BR" 
```
# Saiba mais
A base da OpenAQ foi construída por meio de parcerias governamentais a nível de pesquisa para conscientização pública e a regulamentação ambiental, visando ao entendimento e ao combate da poluição do ar e seus impactos negativos.
Leia mais [aqui](https://openaq.org/)

# Nova base
O grupo avaliou que a análise ficaria desfalcada se mantivéssemos apenas a base original, devido às linhas nulas. Por isso, propusemos o uso de uma nova base de dados de qualidade do ar, também disponibilizada pela OpenAQ, e produzida pela CESTESB, e disponível no link abaixo a seguir: [World Air Quality - OpenAQ — Opendatasoft](https://public.opendatasoft.com/explore/dataset/openaq/table/?disjunctive.city&disjunctive.location&disjunctive.measurements_parameter&sort=measurements_lastupdated)
