```bash
spark-submit --master yarn --deploy-mode client --class com.fire.SparkApp s3://fire-sample-data/change-health/jar/fire-xml-parse-1.0-jar-with-dependencies.jar --pipelineName TestCustomXMLParser --inputXmlLocation s3://fire-sample-data/change-health/input/version=1-2/year=2022/month=03/day=30/hour=04/New270x12_test.xml --rowTag TS_270 --outputFormat parquet --outputLocation s3://fire-sample-data/change-health/output/test/
```
