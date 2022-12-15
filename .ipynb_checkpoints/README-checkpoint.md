https://spark.apache.org/downloads.html

download and unar it 

cp conf/spark-env.sh.template conf/spark-env.sh

edit this spark-env.sh  add lines :

SPARK_MASTER_HOST=127.0.0.1
SPARK_MASTER_PORT=25130


then go to the sbin
./start-master.sh
./start-worker.sh # spark://127.0.0.1:25130 ? 