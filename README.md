Configuration introduction
==================

This is a configuration of Logstash plugin "logstash-input-jdbc" to fetch data from Mysql Database and migrating Mysql Database Data to Elasticsearch.So finnaly we could use kibana to visualize them.  

##Usage:  
    ```
    logstash -f mysql.conf  
    ```
      or on windows
    ```
    logstash.bat -f mysql.conf
    ```
    mysql.conf means exact this configuration.

#Here are steps:  
##1.Have your ElasticSearch installed:  
    *Windows/Linux Download:  
        >https://www.elastic.co/downloads/elasticsearch  
    *Windows run:  
        Just unzip .zip and enter the "bin" directory and run elasticsearch.bat under Terminal window  
##2.Have your Logstash installed:  
    -Windows/Linux Download:  
        https://www.elastic.co/cn/downloads/logstash  
    -How migrate mysql data to elastic,commands:  
        logstash.bat -f mysql.conf  

##3.Have your Kibana installed( on this case,it's optional,because in here we only want to migrating data to elastic )  
