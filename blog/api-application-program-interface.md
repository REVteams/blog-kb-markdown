---
title: API - Application Program Interface
author: Damian Thompson
meta: An application programming interface (API) is a software intermediary tool that mediates communication between software components and resources.
---

# API - Application Program Interface

Application Program Interface (API)

In computing and application building, programming forms the basis of every operation. Nowadays, applications are considered a staple of everyday life — but in order for them to work, programmers need to write and insert long lines of code.

Writing code from scratch takes a lot of time, though. Making some of the many applications out there work with each other can also be a challenging task but a crucial one nonetheless. To facilitate these processes, an application program interface is used.

## Definition

The term application programming interface, or API, is used to designate a set of rules that define interactions between software components and resources, as well as the computing interface that makes these interactions possible itself.

APIs are meant to be used by computers and applications in much the same way user interface (UI) is meant for any human end-user.

To avoid having to go through the process of typing each individual line of code, app developers also benefit from APIs when working with software components regularly. Even when they do write some of the necessary code, they can make use of several quality applications that have their own APIs, enabling them to better organize their code and reuse components.

## How Do APIs Work

The main task of APIs is linked to one of the cornerstone concepts of computer science — [abstraction](https://www.bbc.co.uk/bitesize/guides/zttrcdm/revision/1). By using abstraction, all the technical processes that happen in the background of computer functioning are hidden — that is, **abstracted** — from end-users, so that they can focus only on the tasks they need for their work.

To demonstrate abstraction with an example, think about a person learning how to ride a bike. Bikes are made of many parts. In order for them to move, a somewhat complex set of their parts needs to interact with each other: the pedals, attached by several cranks, need to be physically pushed with a certain amount of force, and they then interact with the bike chain, which is connected through cogs to at least one of the bike wheels. The wheels then move under the pressure of this force.

But, of course, anyone who wants to learn how to ride a bike doesn’t need to know any of these details: they should simply grab the handlebars, learn how to maintain balance, and push the pedals.

APIs work in a similar way when it comes to building applications. For example, a developer can use an API designed for file input and output to copy files, without necessarily having a grasp of what file systems processes happen in the background to make the copying possible.

APIs intermediate between an app and the web server by processing data transfer. The procedure works in the following way:

* Client apps make an API call — also known as a request — for information from the web server.
* The API’s [URI](https://www.hypr.com/uniform-resource-identifier-uri/) then processes the request that uses a request verb, headers, and sometimes a request body as well.
* When the API gets a valid request, it calls the external program or web server.
* The server then answers this call by providing the information that the API asked for.
* Finally, the API resends this information to the app that requested it in the first place.

This entire web service data transfer process goes through APIs.

## Security Aspects of APIs

As an intermediary that abstracts the processes that happen when two systems connect, APIs are what makes this connection secure. In this way, APIs technically separate the application from the service it requests information from, protecting them both from each other in case a security risk exists on either end. Neither of the ends is fully exposed to the other — both use small data packs that include only the necessary information to communicate with each other.

Requests made through APIs commonly use authorization credentials that make the server less vulnerable to attacks. The API gateway may also restrict access at either end, effectively reducing security risks. [Cookies](http://www.bbc.co.uk/webwise/guides/about-cookies), [HTTP headers](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers), and query string parameters also help the interaction by acting as supplementary layers that protect data.

## API Examples

A good example of the API’s security aspects is how they’re useful, for instance, when doing online payments. End-users can pay for products using only their credit card info, processed by the API of an online payment platform. For this purpose, the API creates a special token for the payment used during the request to the server that the payment app sends. This eliminates the need for the service to access the payer’s bank account where the money they use for the payment resides.

With that in mind, virtually every online transaction is a good example of API usage. When customers buy a product online, they pay for it with their cards, and then the product gets delivered to them in one way or another. The entire process of the payment application communicating with the website of the product’s supplier to process the payment to the supplier’s account and schedule the delivery is abstracted from the customer through the API; a set of background functions, if you will.

Other common uses for APIs may include such everyday processes as:

* Allowing end-users to log into third-party websites simply by using one of their social media accounts (Facebook, Gmail, etc.) they’re already logged into;
* Enabling map-applications (a notable example being [Google Maps](https://www.google.com/maps)) to perform most of their regular functions, such as displaying site maps, giving users directions, and so on;
* And more.

Though the concept of API has existed for quite some time, APIs have become virtually omnipresent in the past ten years. A huge number of the most prominent web apps of today owe their existence and continuous work to APIs.

## The Importance of APIs

With the most recent developments in API technology, APIs have become very valuable for software-reliant businesses. Some of their most recently developed traits include adherence to HTTP and REST standards, adaptation for use by niche groups (such as smart app developers, for example), increased security and performance, solid documentation for versioning, and more.

All of this makes APIs extremely significant to the income of businesses that use them in their apps. Some of the most prominent companies that monetize heavily on their APIs include giants such as Amazon, Google, Salesforce, and more. The sum of these companies, as a marketplace for APIs, makes up what is known as the **API economy.**

## Summary

An application programming interface (API) is a term used in computing science to describe a software intermediary tool that mediates communication between software components and resources. APIs make software development easier through a process known as abstraction, which hides background processes and focuses only on those that end-users need when interacting with applications.

APIs allow apps to exchange information easily and securely. They have become increasingly important in recent years, to the point that much of today’s most common software solutions would not be possible without them. This is why companies that rely on apps, as well as app developers, constantly make use of APIs in their work.