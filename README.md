# AWS-Mine-Sweeper
AWS website hosting demo 


Cloudformation:

Initial deployment:
> aws cloudformation deploy --template-file .\template.json --stack-name "mine-sweeper"

Update site assets:
> aws s3 cp Website s3://mine-sweeper-site-assets/ --recursive