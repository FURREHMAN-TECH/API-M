# Azure API Management Service

## Overview
This repository documents my learning and experience with Azure API Management (API-M).

## Adding the OpenAPI API

- I began by creating an API Management service within my designated lab Resource Group.

![image](https://github.com/user-attachments/assets/2335edb2-9f7b-405a-9db6-7995a67584a3)

- After the API Management service was successfully created, I configured the OpenAPI API by providing the OpenAPI link: [Click Here](https://petstore3.swagger.io/api/v3/openapi.json).

![image](https://github.com/user-attachments/assets/c3e8db1c-c8ca-4e1f-9bba-d86e303c11ae)

- Within the API Management interface, I selected the "GET Get user by user name" operation and navigated to the "Test" tab. I modified the value to "user1" and received the following HTTP response:

![image](https://github.com/user-attachments/assets/12a77eb5-698b-477c-bbc3-e8593870c17d)

- I implemented a series of policies to enhance the security and functionality of the API, including:

  - Blocking a specific range of IP addresses.
  - Enforcing API Key authentication.
  - Implementing cache lookups to improve response times.
  - Applying rate limiting to control traffic and prevent abuse.

![image](https://github.com/user-attachments/assets/42b44f9b-1e1f-43cb-a0b1-23c01c16c1f2)
