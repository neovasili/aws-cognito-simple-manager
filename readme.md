# AWS cognito simple manager

Simple html and javascript cognito users manager.

## Features

It allows you **register** new users with verification code confirmation process, **sign-in** users, and **sign-out**.

Use default cognito configuration for user pool creation process.

When creating user pool client, remember to **DISABLE the Generate client secret** checkbox.

## Use

Simply set environment variables in main.js file with your environment values:
*  AWS_REGION --> such as "eu-west-1"
*  COGNITO_USER_POOL_ID --> something similar to "eu-west-1_xxxxxxxxx"
*  CLIENT_ID --> such a thing like a string with characters and numbers "xxxxxx44444"

Open the index.html file.

Enjoy ;)