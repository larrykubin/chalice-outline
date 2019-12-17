# AWS Chalice

* "Serverless" Microframework - Python, Flask-like Routing
* Lambda + API Gateway - Billed per execution / resources used - https://aws.amazon.com/lambda/pricing/
* Provides command line tool
* Handles configuration of IAM
* Up and Running in 30 seconds

![Serverless App](https://d1.awsstatic.com/Test%20Images/Kate%20Test%20Images/Serverless_Web_App_LP_assets-12.da876b91b6451199d3582b6cc81dc17ff7e5791f.png)

## Project 1: Hello World

### Creating a New Project

* app.py
* requirements.txt
* deploying
* AWS Console - Lambda, API Gateway Diagram, IAM, Policies and Permissions
* running an application locally

#### Routes

* decorator syntax
* named placeholders
* deploying to different environments

#### Logging

* app.log.setLevel(logging.DEBUG) and app.log.debug()
* Cloudwatch

#### Request and Response

* POST Request
* current_request - json_body, query_params, headers, method

### Screencast Tutorials (Twitter App)

* Getting Started with Chalice Tutorial Part 1: https://www.youtube.com/watch?v=me-v7BCaZH0
* Getting Started with Chalice Tutorial Part 2: https://www.youtube.com/watch?v=mRuBtE057aM

## Project 2: Slack Bot

* Accepting other content types
* Verifying the request
* Including 3rd party libraries (requirements.txt)
* Adding local packages (config, utils)
* Cloudwatch Events (Cron, Rate)
* DynamoDB, IAM Role (Automatic vs. Manual)
* https://hub.docker.com/r/amazon/dynamodb-local/
* Billing

### Source Code

* https://github.com/larrykubin/stockbot

### Screencast Tutorials (Stockbot)

* Serverless Slack Bot Tutorial Part 1: https://www.youtube.com/watch?v=-Ag_k5p0sTs
* Serverless Slack Bot Tutorial Part 2: https://www.youtube.com/watch?v=G__hYyluwYM
* Serverless Slack Bot Tutorial Part 3: https://www.youtube.com/watch?v=m0HW-Bb70_c

## Project 3: Music Festival Posters

* What is it? createlineup.com - simple PHP webapp with daily usage
* Good amount of sharing on twitter, emails for theming / consulting
* Goal: port this to "serverless"
* React UI and CORS, unique font, style, poster
* Packaging chalicelib - font, image, blueprints, packages
* boto3 - client for s3, sqs, dynamodb
* Chalice Events - On SQS Message, On S3 Event
* Python Imaging Library and S3 (image upload)
* Cognito (show User Pool) and amazon-cognito-identity-js
* SDK Generation
* CodeCommit, CodePipeline

#### Additional Resources

* Ben Unity Repo + Leaderboard (needs Auth) - https://github.com/larrykubin/leaderboard
