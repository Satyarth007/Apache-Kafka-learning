# Apache-Kafka-learning

### Install Kafka version -> 3.9.1

### First Steps: 

1. Run the Kraft server:
     ```
         .\kafka-storage.bat random-uui -> Get UUID
         .\kafka-storage.bat format -t <Paste the UUID> -c C:\kafka\config\kraft\server.properties -> This will update you kraft server config files
         .\kafka-server-start.bat C:\kafka\config\kraft\server.properties -> This will start the kafka server in local at localhost:9092
     ```
     
3. Run the Topic Creation, Describe, etc cmds:
4. Run the producer:
5. Run the consumer:


