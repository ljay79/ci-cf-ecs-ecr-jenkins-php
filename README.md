# ECS Solutions Templates

## Based on ...
[Create and Connect to an AWS CodeCommit Repository](https://stelligent.com/2016/05/02/create-and-connect-to-an-aws-codecommit-repository/)

[Automating ECS: Provisioning in CloudFormation (Part 1)](https://stelligent.com/2016/05/26/automating-ecs-provisioning-in-cloudformation-part-1/)

[Automating ECS: Orchestrating in CodePipeline and CloudFormation (Part 2)](https://stelligent.com/2016/06/10/automate-amazon-ec2-container-service-provisioning-and-orchestration-using-cloudformation-and-aws-codepipeline/)

(https://github.com/stelligent/cloudformation_templates/tree/master/labs/ecs)


Updated to fit 2018!

Tried to simplify the storage of all required artifacts and scripts to minimum of locations.
During the tutorial there is mentioned a file `configure-ecs.sh` which i add to the sample-app repo. As i struggled to figure our where to find and where to put it.
That same file also now has updated logic.

The entire sample project is now capable to be deployed to most AWS regions dynamically except for the hard coded setting in [.env](https://github.com/ljay79/ci-cf-ecs-ecr-jenkins-php/blob/master/.env).

# Referencing:
- [PHP Simple Demo App](https://github.com/ljay79/ecs-demo-php-simple-app)
-* based on [Amazon ECS PHP Simple Demo App](https://github.com/awslabs/ecs-demo-php-simple-app)
- https://s3.eu-central-1.amazonaws.com/ljay79/github/ci-cf-ecs-ecr-jenkins-php/ecs-pipeline.json ; pls use your own S3 bucket to store your custom CloudFormation template.
- CloudFormation template references to this GutHub repository by default
