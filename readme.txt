CS 6350 ASSIGNMENT 2

Names of students in your group:

SRIPRASATH GUJULUVA PARTHASARATHY(sxg180154)

SHARIQ ALI(sxa190016)


NOTE: Please use Spark 2.4.5, Scala 2.11, DBR 6.5 and com.johnsnowlabs.nlp:spark-nlp_2.11:2.5.2


Question 1:

Config your cluster as follows:

1. Go to Aadvanced Options -> Spark tab and the following:
spark.kryoserializer.buffer.max 1000M
spark.serializer org.apache.spark.serializer.KryoSerializer

In Libraries tab inside your cluster you need to follow these steps:
Insatll New -> PyPI -> spark-nlp -> Install
Install New -> Maven -> Coordinates -> com.johnsnowlabs.nlp:spark-nlp_2.11:2.5.2 -> Install

The input file is DonQuixote.txt downloaded from the Gutenberg project website.

Databricks url for Question 1:
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/32072069969770/179355301904644/478845738118579/latest.html





Question 2:

The input files are plot_summaries.txt, movie_metadata-ab497.tsv, search.txt

Databricks url for Question 2:
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/32072069969770/1691937854368529/478845738118579/latest.html