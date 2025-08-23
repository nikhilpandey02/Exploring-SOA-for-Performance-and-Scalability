# Understanding Service Oriented Architecture (SOA)

## Abstract

Service Oriented Architecture (SOA) is a way to build software by putting together small, separate pieces called services. These services do specific jobs and can talk to each other over a network.
SOA helps companies reuse software parts they already have and easily change their systems when needed. The services don’t depend on each other too much, so one can work without messing up the others.
It works like this: services are listed in a directory, then other programs find them, connect to them, and use what they do.
So basically, SOA is about building flexible software from small, reusable parts that can work together smoothly.

## Introduction

Service Oriented Architecture, or SOA, is a way to design and build software applications by using small, reusable components called services.
These services work over a network, like the internet, and allow different parts of software to communicate and work together.

## What is a Service?

* A service is like a small worker in software that does one specific job.
* Over time, software has gotten more complicated. Instead of one big program,developers now build lots of smaller services that work together. This way ofbuilding software is called Service-Oriented Architecture,
  or SOA, and it focuses on connecting these small services to get bigger work done.

## When to use SOAP Services?

SOAP services are suitable for certain situations:

* When you need asynchronous processing (doing things separately without waiting).
* When your application needs guaranteed reliability and security.
* When both sides (service provider and user) must agree on strict message formats.
* When you need stateful operations - where the service remembers information between requests.

## Strategic Benefits of SOA

SOA helps businesses in many ways:

* Improves agility so you can quickly adapt to new business needs.
* Enables faster software development by reusing services.
* Helps manage changes efficiently.
* Supports development focused on business domains.
* Allows reuse of existing IT systems and investments.

## Operational and Maintenance Benefits

SOA improves how IT systems work daily:

* Makes it easier to diagnose and fix problems.
* Allows updates and replacements without disrupting everything.
* Reduces maintenance cost and complexity.

## How SOA Works - Find, Bind, Execute

* Services are registered in a public directory.
* Applications find the services they need.
* They connect (bind) to these services using contracts.
* Then they execute tasks using the services.

## Realizing SOA with Web Services

Web services help SOA by providing common standards and protocols (like XML, WSDL, SOAP).
Java platforms provide tools to build and expose these services, allowing different systems to work together even if built with different technologies.

## Conclusion

SOA is a powerful way to build flexible and scalable software by breaking down complex functions into reusable services.
It helps businesses save costs, be more agile, and maintain their IT systems more effectively.

## References

* [Service-oriented Architecture: Describing Benefits from an Industrial Perspective](https://www.scitepress.org/papers/2017/63836/63836.pdf)
* [Service-Oriented Architecture and Web Services - Oracle](https://www.oracle.com/technical-resources/articles/javase/soa.html)
* [A Survey Paper on Service Oriented Architecture Approach and Principles](https://opus.govst.edu/cgi/viewcontent.cgi?article=1159&context=capstones)
