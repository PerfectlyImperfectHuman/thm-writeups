# Room: Client Server Basics

**Module:** Module 4 — Computer Fundamentals
**Date completed:** June 28, 2026

## What this room covers

In this room we learn the basics of a Client Server Model using a Pizza delivery example and we learn about clients, servers, dns, protocols etc

## Key concepts learned

- Client — is a user or machine that is requesting some sort of service from a server e.g In the Pizza delivery example the client is Alice because she is requesting to get a pizza so she can eat it
- Server — is a type of computer that runs 24/7 and is used to provide services to users, it responds to a request and provides the user the service they are looking for e.g In the pizza delivery example the server would be the pizza restaurant since they hear the request of Alice (client) and responds with the pizza (service)
- Domain Name System (DNS) — is a type of system that resolves a domain name (such as youtube.com) to an IP Address so that the user doesn't have to remember a bunch of numbers for each site they visit
- Protocol — are a set of rules that must followed when a client requests a server for a service e.g In the pizza delivery example the protocols include speaking the same language or a language that both parties understand and ordering a service (pizza) that the server can provide
- Port — is used to identify a specific service running on a server e.g In the pizza delivery example the restaurant has different doors for different kind of services like one for takeaways and one for dinning-in so the user needs to use a specific port (door) to access a specific service

- HTTP Commands — GET, POST, PUT, DELETE, PATCH, HEAD, OPTIONS, CONNECT, TRACE
- GET Request — is used to retrieve information from a webpage. Whenever you go to a webpage ( for example: tryhackme.com ) you need to send a GET Request to the webpage servers to access the data on the page (like the html, css, js files ) but you don't have to do it manually because whenever you search for a webpage the browsers sends a GET request to the server automatically and it responds with the data back which appears on the webpage

## Tools/commands used

- GET /index.html — is a HTTP request sent to a server to retrieve data about the webpage (it is done automatically by the browser ) but it contains some important information and can be viewed by going to the Network tab on the developer tools in the browser and checking the requests being sent

## Something that confused me at first

I had to spend a few minutes on the Pizza Delivery Example to properly understand the basics of the Client Server Model and secondly the GET Request confused me a lot and even now I know that i haven't grasped it properly and I don't know what most of the data it provides stands for ( for example the content length etc like what are they used for ) but i think that right now I don't really need to go too deep into it so the next time it appears I will make sure to understand it properly

## How this connects to real-world security

This connects with the real-world security because in this room we learn how the clients and servers interact with one another using browsers and protocols and how data is exchanged between them

This means that if someone is able to bypass the protocols somehow he can get access to data that may contain important information about the website or the clients hence the browsers protocols need to be as secure as they can be ( and also encrypted ) and I think that bypassing the protocols and redirecting or intercepting HTTP Requests is how you gain information about a websitse or a user and then you can use that information however you want

## Next steps / what I want to explore more

I want to learn more about the fundamentals of computers and how they work and hence i am moving to the next room
