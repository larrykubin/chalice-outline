# AWS Chalice

* Serverless Microframework - Python
* Lambda + API Gateway - Billed per execution
* Handles configuration

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
* Including 3rd party libraries (requirements.txt)
* Adding local packages (config, utils)
* Cloudwatch Events (Cron, Rate)
* DynamoDB
* Billing

### Screencast Tutorials (Stockbot)

* Serverless Slack Bot Tutorial Part 1: https://www.youtube.com/watch?v=-Ag_k5p0sTs
* Serverless Slack Bot Tutorial Part 2: https://www.youtube.com/watch?v=G__hYyluwYM
* Serverless Slack Bot Tutorial Part 3: https://www.youtube.com/watch?v=m0HW-Bb70_c

## Project 3: Music Festival Posters

* What is this?
* React UI
* CORS
* Packaging chalicelib - font, image, blueprints, packages
** boto3
*** DynamoDB
*** S3
* Cognito
* SDK Generation
