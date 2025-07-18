# 使用方法

```shell
spark-sql \
  --name demo \
  --jars hdfs:/apps/datahub/datahub-spark-lineage-0.12.1.jar \
  --driver-class-path /cluster/datahub/datalake-datahub-client-1.0.0.jar:/cluster/datahub/datalake-datahub-spark-lineage-1.0.0.jar
```