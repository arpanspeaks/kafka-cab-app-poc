KAFKA COMMANDS
==============

.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties

.\bin\windows\kafka-server-start.bat .\config\server.properties

.\bin\windows\kafka-topics.bat --create --topic quickstart-events --bootstrap-server localhost:9092

.\bin\windows\kafka-console-consumer.bat --topic quickstart-events --from-beginning --bootstrap-server localhost:9092

.\bin\windows\kafka-console-producer.bat --topic quickstart-events --bootstrap-server localhost:9092

.\bin\windows\kafka-topics.bat --list --bootstrap-server localhost:9092