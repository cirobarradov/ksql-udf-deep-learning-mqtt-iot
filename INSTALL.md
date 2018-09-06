Requirements Installation Guide
=================
Requirements
------------
- Operative System: Ubuntu 16.04 

Tech Stack
------------
- Java 8
- Kafka
- Maven 
- kafkacat (optional - if you do not want to use MQTT Producers, and of course you can also use kafka-console-producer instead, but kafkacat is much more comfortable)
Java 8
------------
```
sudo apt-get update
sudo apt-get install default-jre
sudo apt-get install default-jdk
```

Maven
-----
```
sudo apt-get update
sudo apt-get install maven
```
Kafka
------------
```
wget -qO - https://packages.confluent.io/deb/5.0/archive.key | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://packages.confluent.io/deb/5.0 stable main"
sudo apt-get update && sudo apt-get install confluent-platform-oss-2.11
```
Kafkacat
------------
```
apt-get install kafkacat
```
