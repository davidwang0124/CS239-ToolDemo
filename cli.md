```
ssh -i ~/spark-demo.pem hadoop@ec2-54-202-209-50.us-west-2.compute.amazonaws.com
aws s3 cp s3://xgwang-spark-demo/ml-100k/u.item .
aws s3 cp s3://xgwang-spark-demo/ ./data

spark-submit SparkDemo.jar
```