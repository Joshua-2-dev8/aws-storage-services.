# aws-storage-services.
## AWS CLI COMMAND TO MANAGE S3 BUCKET AND OBJECTS

C:\Users\Ojarotade>aws s3 mb s3://myaccurate-bucket
make_bucket: myaccurate-bucket

C:\Users\Ojarotade> cd C:\Users\Ojarotade\Documents\HTML_TUTORIAL

C:\Users\Ojarotade\Documents\HTML_TUTORIAL>aws s3 cp s3://myaccurate-bucket HTML_TUTORIAL

C:\Users\Ojarotade\Documents\HTML_TUTORIAL>aws s3 sync .  s3://myaccurate-bucket
upload: .\index.html.html to s3://myaccurate-bucket/index.html.html
upload: .\learnMore.html to s3://myaccurate-bucket/learnMore.html

C:\Users\Ojarotade\Documents\HTML_TUTORIAL>
