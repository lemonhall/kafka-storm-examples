[Env]
export MAVEN_OPTS=-Dfile.encoding=UTF-8
export LC_ALL=UTF-8


[run local]
mvn compile exec:java -Dstorm.topology=kafka.storm.examples.kafkaTopology