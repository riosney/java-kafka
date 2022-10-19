# java-kafka

Subir o Kafka:
- C:\kafka_2.12-3.2.0\bin\windows
- Subir CMD: zookeeper-server-start.bat ../../config/zookeeper.properties
- Subir CMD: kafka-server-start.bat ../../config/server.properties

Criando tópicos:
- Ver topico criado: kafka-topics.bat --bootstrap-server localhost:9092 --describe
- Criar topico: kafka-topics.bat --bootstrap-server localhost:9092 --topic compras.do.cliente --create --partitions 1