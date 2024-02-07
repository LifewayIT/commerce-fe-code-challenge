
---

This is Lifeway IT's code challenge given to full stack software engineering candidates! Interested in working with our team? Check out open positions [here](http://tech.lifeway.com/)

---

### Premise

The premise of this challenge is to create a "profile page" for various star wars characters in the Star Wars universe.

### Specification

Create a simple single page application that provides the following features:

  * A search bar that takes the characters name as input.
  * A profile containing the following sectional information for the searched character:
    * About Me (height, weight, hair color, date of birth, species information)
    * Films Appeared In
    * Starships Flown

Use [SWAPI](https://swapi.dev/) to obtain all the star wars data that you need.

Use whatever languages or tech you want -- we are looking for clean, testable code that demonstrates usage of common design patterns and best practices above all else. 

#### What we are looking for

We will be using the code challenge to evaluate the following:

* A decent understanding of React is demonstrated
* A decent understanding of Next.js is demonstrated
* A decent understanding of TypeScript is demonstrated
* A decent understanding of unit/integration testing is demonstrated
* A basic "gateway" api is created to consolidate and proxy calls to SWAPI

#### In addition...Data Modelling

While we make use of many REST API services at Lifeway, we also make use of GraphQL API services, and other technologies such as DynamoDB.

In particular we use [AppSync](https://aws.amazon.com/appsync/) as our GraphQL API Gateway in order to integrate backend services into our Next.js website.

In order to demonstrate skills in this area, we will also evaluate your skills in GraphQL and DynamoDB data modelling:

* Pick at least two Resource types from the [SWAPI documentation](https://swapi.dev/documentation) that have a relationship between them
    * For example [People](https://swapi.dev/documentation#people) and [Films](https://swapi.dev/documentation#films)
* Create a GraphQL schema that models how you would expose these Resources via GraphQL Queries and Mutations
* Create a DynamoDB data schema that shows how those models would be persisted in a way that would allow that data to be used to service the GraphQL schema
    * Consider access patterns and plan your Partition and Sort keys accordingly. As well as any required secondary indexes.
* If you're familiar with AppSync, bonus points would be given if you also provide designs for any resolvers required to integrate with DynamoDB and transform the data between GraphQL and DynamoDB data formats
* You don't need to implement these schema designs, but you will need to walk us through your designs and the reasons for them, as well as any trade-offs or alternative options you considered.
---

### Submissions

Please put your submission in a public github repository to share.

---


<div class="footer">
  <img src="https://commerce-notification-service-uat.s3.amazonaws.com/emails/Lifewaylogo__RGB_gray_flat.png" alt="Lifeway Christian Resources" width="150" style="padding: 1rem;">
</div>
