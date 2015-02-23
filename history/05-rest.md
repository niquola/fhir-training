## REST

> Architectural Styles and the Design of Network-based Software Architectures

Roy Thomas Fielding

http://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm

Representational state transfer - architectural style

Concept of resource - uri or url

REST vs RPC -

You work with representation.

6 constraints:

* Client-Server
* Stateless
* Cacheable
* Code On Demand
* Uniform Interface
* Hypermedia as the engine of application state

### Resource

Things vs actions
Nouns vs Verbs
Identified by URI
Separate from representation

### Representation

Format negotiation JSON, XML, csv

### Uniform Interface

* URIs
* VERBs:  GET, POST, PUT & DELETE (OPTION, PATCH)
* Response: [status codes](http://en.wikipedia.org/wiki/List_of_HTTP_status_codes), body

### Stateless

Each request has enough information to handle request
Session state is on client

### Client-Server

* Disconnected system
* Separation of concerns
* Uniform Interface between both

### Cacheable

* scalability
* implicitly, explicitly or negotiated

### Layered System

* client does not assume direct connect
* middleware (cache, security)

### Code on Demand

* respond with code for resource manipulation
* JS (java, flash)


### Hypermedia driven

http://roy.gbiv.com/untangled/2008/rest-apis-must-be-hypertext-driven
