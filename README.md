Amazon Kinesis Source and Sink for Apache Flume

Build:

1) git clone
2) cd flume-kinesis
3) mvn clean package
4) cp target/*.jar FLUME_HOME_DIR/lib
5) delete FLUME_HOME_DIR/lib/httpcore httpclient jar
6) refer to one of the configuration samples in flume-kinesis/conf on how to configure Amazon Kinesis Sink and Source
