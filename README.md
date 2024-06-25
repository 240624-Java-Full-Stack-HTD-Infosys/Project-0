# Project 0 - CRUD Banking API
For our first project we are building a simple banking app where users can deposit and withdraw money from one or more bank accounts. At first we will be building this as a console application until we cover Javalin, then we will build out an API to access the functionality.  
  
This project will use a PostGres SQL database hosted in AWS for persistence. We will build DAOs (Data Access Objects) which can interact with the database via JDBC (Java Database Conection). We will build a 3-tier server with data, service, and presentation layers. In the early days of the project we can interact with it via manual testing, JUnit testing, or a console UI, but by week 3 we will be adding an API so that we can interact with our server using [Postman](https://www.postman.com/downloads/).

## Dates
 - Code Freeze: EOB 7/10/24
 - Due Date: 7/12/24
 - Presentations: 7/12/24 - 10:30 AM ET

## Presentations
The project is due on Friday 7/12/24 at 10:00 AM ET. We will each be presenting our project and giving a quick demo. The presentation should only be 5-10 minutes per person, take some time to discuss the project, how it turned out, challenges you faced, your favorite or least favorite parts, etc. I would advise against stepping through the code during the presentation. 

Before the due date there is a suggested code freeze date at the end of the day on Wednessday 7/10/24. This means you should stop making major changes to the project, and instead focus on bug fixing, polish, and presentation. You should aim to have your project basically complete by that time.

## Functional Requirements
 - Users should be able to register and login
 - Users should be able to preform CRUD operations on their resources via HTTP API
 - 

## Non-functional Requirements
 - User input should be validated for negative balances, out-of-bounds, types, special characters, ranges, etc.
 - 
