# Basic Website Hosting 
AWS website hosting from an S3 bucket made available through CloudFront


MineSweeper site example:

Initial deployment example for mine sweeper:
> aws cloudformation deploy --template-file cloudformation\template.yaml --stack-name "mine-sweeper" --parameter-overrides BucketName="mine-sweeper-site-assets" ProjectName="Mine-Sweeper"

Update site assets exmple to min sweeper bucket:
> aws s3 cp Website s3://mine-sweeper-site-assets/ --recursive


Example
> aws cloudformation deploy --template-file cloudformation\template.yaml --stack-name "stack-name" --parameter-overrides BucketName="bucket-name" ProjectName="project-name-for-tagging"

