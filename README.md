# SparkJavaJson

Change the spark.driver.extraClassPath property inside the sparkjob.conf file before you execute the following command.

./bin/spark-submit --class org.sparketl.etljobs.SparkEtl --properties-file sparkjob.conf /sparketl/target/sparketl-0.0.1-SNAPSHOT.jar {spark master url} { use city_list.json present in this project} {output file (for Pair RDD) {output file for single RDD}} {Country ex:US}


For Spark begginers go to 

https://github.com/vijithreddy/SparkMavenJava 
