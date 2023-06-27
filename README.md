# AWS-Mine-Sweeper
AWS website hosting demo 


Cloudformation:

Initial deployment:
> aws cloudformation deploy --template-file .\Initial_Setup_Template.json --stack-name "mine-sweeper"

Update site assets:
> aws cloudformation package --template .\Update_Site_Template.json --s3-bucket mine-sweeper-site-assets