# sns-sqs-fanout
SNS SQS Fan-out with filter policies

```
$ aws cloudformation create-stack --template-body file://template.yaml --stack-name sns-sqs-fanout-filter-example
```

An example message can have 2 attributes:
- color
- number

![Copy of SNS(3)](https://user-images.githubusercontent.com/14105387/90342335-b9833c80-e007-11ea-93f3-ecdf884e97e2.png)
