# dbmanager
This repository contains the lambda functions and Alexa skills needed to build the Alexa Amazon RDS Manager

This skill is intended to take advantage of and combine DB automation and Alexa tools. The initial intent was to demonstrate the capabilities of the AWS RDS Aurora database product to customers via Alexa, capabilities such as a failover in under 60 seconds and adding a Read Replica in seconds. Basic intents of the script, allows a user to list his instance, check the status of his cluster and modify it to add an additional Read Replica.


# Prerequisites

In order to develop this skill, you will need to have the knowledge on how to build Alexa skills, Lambda functions, and basic knowledge around IAM roles.

You would need to set up the following:
- Have an AWS account with the access to the AWS Management Console.
- Have access to Alexa Developer Account: https://developer.amazon.com/alexa
- Create IAM roles to access RDS from Lambda to create a secure role: https://docs.aws.amazon.com/lambda/latest/dg/access-control-identity-based.html
- Configure Endpoint and Alexa Skill Trigger: https://developer.amazon.com/docs/custom-skills/host-a-custom-skill-as-an-aws-lambda-function.html#add-ask-trigger
