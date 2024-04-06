# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API with no auth and no CORS from the following list. It _should not_ be one that you've already seen or worked on in class.
   - [Public APIs](https://github.com/public-apis/public-apis)
1. Choose an API not covered in your readings, class, or other assignments. The API should be new to you.
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.
1. Take the time to read back the work, and edit what you've written so that your answers are clear and anyone reading it can easily understand what you've written.

## Instructions

Do your best to answer the questions with specific details. Writing about code clearly and thoroughly is a critical skill to practice.

- Which one did you choose? Provide the name and base URL.

> https://anapioficeandfire.com/api/

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is...provide data for the Books, Characters and Houses from the Book series  Ice and Fire which is the HBO Game of Thrones Series.

- What is the URL of the documentation?

> https://github.com/joakimskoog/AnApiOfIceAndFire/wiki

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://anapioficeandfire.com/api/

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
`{
    "books": "https://anapioficeandfire.com/api/books",
    "characters": "https://anapioficeandfire.com/api/characters",
    "houses": "https://anapioficeandfire.com/api/houses"
}
`

```

- What status code did you get back from your request? Why did you receive this status code?

> 200, This means the the request is sent sucessfully.

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json; charset=utf-8

> `Content-Length`: N/A, I do not see.

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes... The information on a Character Jon Snow from the series. Name, DOB, hoise, aliases and other information.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that ... A website to look up information the the Characters from the series. Also, you can maybe create a trivia game of out it. 

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was ... Short. It provided useful information such as Rate Limiting information and information on how to request the information we are looking for. 

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation ...It was new at first, but once you go through it and try out a few request, it all makes sense. 

- Did the quality of the documentation impact your decision to use it?

> Yes/No because...No, it was a simple API and everything worked right out of the gate. 

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up ...No, I stuck with this one because It is one of my Favorite shows. 

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle ... It is a way to request information (data) that is stored somewhere (Server) and how to do it (CRUD). A request should be answered with a response indicating if it was sucessful or not and the data we are looking for. 

- In your own words, describe what an API is.

> An API is ... Application Programming Interface. It is a set of data, usually on a specific topic, which we have access to and can ask for a subset of the data to display on our site as an example. 

- In your own words, describe the purpose of Postman.

> Postman is an application that ... It allows us to Send Create, Read, Update and Delete request to an API or Database to change the State of the system. When we build 
our own apps, we will have a Database where we can Create new users, Update and delete users. Postman allows us to test the endpoints before the frontend is developed.
