# Hosting a ML-Model as Microservice

Fictional scenario: Customers provide reviews of your company’s products, which are used to give a product rating. Until now, assigning a rating has been manual: contractors read each review, decide whether it’s positive or negative, and assign a score. The boss has decided that this is too expensive and time consuming. The mission is to automate this process, dramatically increasing the speed of rating calculations, and decreasing the cost to the company. To meet the expectations a machine learning model needs to be trained in order to recognize and rank positive and negative reviews, and then exposed to an API so the website and partner sites can benefit from automatic ratings Finally, a small webpage using FaaS, containers, and microservices that can run your model for demonstration will be built.

## Project Outline:

- Use an existing ML service (Amazon Comprehend)
- Train an own ML model
- Deploy the model as a FaaS with AWS Lambda
- Create an application using flask and containerize the API
- Develop a simple HTML-Frontend and host it on AmazonS3

## Tech Stack:

- NLTK
- Flask
- Docker
- AWS (Comprehend, Lambda, S3)
