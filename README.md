# kafkapractice


Downloaded kafka
Go to the folder and open in terminal
run the zookeeper command in terminal in bin folder
open another terminal for bin folder and run the command to configure kafka broker

Then create kafka topic in terminal bin folder with below command :-
 ./kafka-topics.sh --create --topic myKafkaTest -zookeeper \
 localhost:2181 --replication-factor 1 --partitions 1

create java application by including spring dependencies
create javatest appplication main class
create producerconfiguration class with code - this will create a producer factory class which will help to configure the values which we want to send in the kafka broker.  this will also create a template class which woould be called in controller
create controller - the controller is created to create an enpoint which needs to be called. also the controller will call the template defined in configuration
run mvn spring command in terminal to build the project - this 
run the 
