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

> I chose HTTPS status dogs: https://http.dog/101.jpg 

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to produce an image when the user clicks the link

- What is the URL of the documentation?

> https://http.dog/101.jpg

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://http.dog/101.json

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
{
    "image": {
        "avif": "https://http.dog/101.avif",
        "jpg": "https://http.dog/101.jpg",
        "jxl": "https://http.dog/101.jxl",
        "webp": "https://http.dog/101.webp"
    },
    "status_code": 101,
    "title": "Switching Protocols",
    "url": "https://http.dog/101"
}

```

- What status code did you get back from your request? Why did you receive this status code?

> I have recieved status code 200 to inform me that my response is okay

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json;charset=UTF-8

> `Content-Length`: 269

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes is a json object that gives us the response from the server.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that would showcase images or an app could use the API for promotion.

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was helpful for generating images of an dog.

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation  n/a

- Did the quality of the documentation impact your decision to use it?

> Yes/No because... n/a

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up ... I stuck with the API I originally chose because I don't have a solid understanding of what documentation is with API's

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle is when you enter a URL inside of postman, so that you can get information back from the server. After the information has been recived postman will give a status code which you should expect to be 200. When you see that you know that you have succesfuly recieved the information.

- In your own words, describe what an API is.

> An API is a application programming interface which alllows other websites to use the data. APIs can be expensive, so it's best to find a reliable free source of APIs

- In your own words, describe the purpose of Postman.

> Postman is an application that rtakes in a URL, so thatyou can recieve information back. Usually expecting a json file.
