Step-1 : Start the Zookeeper using the below command in cmd

$	C:\kafka_2.12-2.8.1\bin\windows\zookeeper-server-start.bat C:\kafka_2.12-2.8.1\config\zookeeper.properties

Step-2 : Start the Kafka Server using the below command in cmd

$	C:\kafka_2.12-2.8.1\bin\windows\kafka-server-start.bat C:\kafka_2.12-2.8.1\config\server.properties

Step-3 : Execute the below command in cmd for creating Kafka Message

$	C:\kafka_2.12-2.8.1\bin\windows\kafka-topics.bat -zookeeper localhost:2181 -topic kafkaMessage --create --partitions 3 --replication-factor 1


Step-4 : Start the Application in STS

Step-5 : Check whether the actuator is working or not using the below link in Web-browser.

localhost:8090/actuator


Step-6 : Go to Prometheus folder and open cmd for that path...and then execute this command

$	prometheus


Step-7 : Check whether the prometheus is working or not using the below link in Web-browser

http://localhost:9090


Step-8 : Go to Grafana Bin folder and open cmd for this path.....and then execute this command

$	grafana-server

and then check whether grafana is working or not in browser :                               

http://localhost:3000


Step-9 : Go to Elasticsearch  Bin folder and open cmd for this path....and thenn execute this command

$	elasticsearch

and then check whether elasticsearch is working or not in browser :                               

http://localhost:9200


Step-10 : Go to Logstash Bin folder and open cmd for this path....and thenn execute this command

$	logstash -f logstash.conf


Step-11 : Check whether the Logstash is working or not using the below link in Web-browser

http://localhost:9200/_cat/indices


Step-12 : Go to Kibana Bin folder and open cmd for this path....and thenn execute this command

$	kibana

Step-13 : Check whether the Kibana is working or not using the below link in Web-browser

http://localhost:5601



Step -14 : Navigate to Swagger UI using below link for API Documentation of backend application.

http://localhost:8090/swagger-ui.html#!/tweet-app-controller/getAllTweetsUsingGET
