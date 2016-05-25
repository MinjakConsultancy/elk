# Parsing Oracle Database and Fusion Middleware log-files into Elasticsearch
The content of this repository helps to easily put some logfiles from oracle into elasticsearch.

I have used them inside a vbox environment:

1. vbox with ubuntu server edition

2. installed docker

3. pulled docker elk image 

4. start elk image

5. download logstash

6. start logstash with configuration-files.

# Logstash Configuration files
1. logstash_configuration 
  * logstash_oracle_database_log.conf 
   This file can be used to parse the Oracle Database alert-log files into elasticsearch
  * logstash_weblogic_log.conf 
   This file can be used to parse the Oracle Fusion Middleware log (domain, access and out) files into elasticsearch
   
   
