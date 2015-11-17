REST calls that stored my cluster config


praseed-MBP:cm_config praseed$ curl -u admin:admin 'http://injest-cluster-1.vpc.cloudera.com:7180/api/v/clusters/Cluster%201/services/hdfs/config?view=full' > hdfs_config.json
praseed-MBP:cm_config praseed$ curl -u admin:admin 'http://injest-cluster-1.vpc.cloudera.com:7180/api/v1/clusters/Cluster%201/services/zookeeper/config?view=full' > zookeeper_config.json
praseed-MBP:cm_config praseed$ curl -u admin:admin 'http://injest-cluster-1.vpc.cloudera.com:7180/api/v1/clusters/Cluster%201/services/flume/config?view=full' > flume_config.json
praseed-MBP:cm_config praseed$ curl -u admin:admin 'http://injest-cluster-1.vpc.cloudera.com:7180/api/v1/clusters/Cluster%201/services/kafka/config?view=full' > kafka_config.json
praseed-MBP:cm_config praseed$ curl -u admin:admin 'http://injest-cluster-1.vpc.cloudera.com:7180/api/v1/clusters/Cluster%201/services/hbase/config?view=full' > hbase_config.json
praseed-MBP:cm_config praseed$ curl -u admin:admin 'http://injest-cluster-1.vpc.cloudera.com:7180/api/v1/clusters/Cluster%201/services/yarn/config?view=full' > yarn_config.json
praseed-MBP:cm_config praseed$ curl -u admin:admin 'http://injest-cluster-1.vpc.cloudera.com:7180/api/v1/clusters/Cluster%201/services/spark_on_yarn/config?view=full' > spark_on_yarn_config.json
praseed-MBP:cm_config praseed$ curl -u admin:admin 'http://injest-cluster-1.vpc.cloudera.com:7180/api/v1/clusters/Cluster%201/services/hive/config?view=full' > hive_config.json
praseed-MBP:cm_config praseed$ curl -u admin:admin 'http://injest-cluster-1.vpc.cloudera.com:7180/api/v1/clusters/Cluster%201/services/impala/config?view=full' > impala_config.json
