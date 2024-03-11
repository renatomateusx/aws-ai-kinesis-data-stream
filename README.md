
# Project made to show how to upload a text file - trigger lambda functions for reading the content.
# Case Study

* 1 - We have an application which uploads text files to S3 Bucket.

* 2 - Whenever a file is uploaded to the S3 Bucket, it’s going to trigger a lambda function.

* 3 - The lambda function is a data producer, which reads the content from the S3 Bucket and then pushes the data to the Kinesis data stream.

* 4 - We have two consumers which consume the data from the stream.

* 5 - The consumers can do many things with the data.

* 6 - Suppose the consumer can read the data and send an email to the clients with the information or the data can be published into social media platforms or the data can be saved into the database.

* 7 - In this lab, we’ll log out the data and verify it.

![project_arch](https://github.com/renatomateusx/aws-ai-kinesis-data-stream/assets/4579323/0acf5413-c576-4b44-a8eb-cffb9d3f53db)

# Project Preview

https://github.com/renatomateusx/aws-ai-kinesis-data-stream/assets/4579323/1bf07ada-f4a6-4fd3-8ebd-726c2ea8938b

