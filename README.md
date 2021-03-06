API-Craft Detroit 2014 - Hypermedia Panel
=======================================

This is a working repository for the hypermedia panel at [APICraft Detroit 2014](http://api-craft.org/).

**Format:**

* 2 hour panel
  * 10 minute press by each panelist
  * 1 hour of conversation

**When:** 1pm-3pm, Monday, July 28th 2014
**Where:** Grand Circus http://grandcircus.co/ downtown Detroit

Panel will be followed by a hands-on hypermedia hackathon that will run from 3:30pm to 7pm.

**Panelists:**

* Mike Amundsen ([@mamund](https://twitter.com/mamund))
* Mike Kelly ([@mikekelly85](https://twitter.com/mikekelly85))
* Steve Klabnik ([@steveklabnik](https://twitter.com/steveklabnik))
* Kevin Swiber ([@kevinswiber](https://twitter.com/kevinswiber))
* Jørn Wildt ([@JornWildt](https://twitter.com/JornWildt))
* Markus Lanthaler ([@MarkusLanthaler](https://twitter.com/MarkusLanthaler))

**Panelists:** Kin Lane ([@kinlane](https://twitter.com/kinlane))

**Title:** State of Hypermedia Today

* What is the state of hypermedia?
* How did we get here?
* Where are we going?
* Where should we be going?
* What can we do during hackathon?
* What are two things everyone should leave API-Craft thinking about?
  * adding hypermedia to an API is a way to improve the API's usability ([@mamund](https://twitter.com/mamund))
  * the more hypermedia information in a response, the more stateless that response can be ([@mamund](https://twitter.com/mamund))
  * Hypermedia allows us to go beyond CRUD-influenced API design, enabling a task-based message design consisting of current resource state and available transitions.  This provides a richer interaction model between client and server.  ([@kevinswiber](https://twitter.com/kevinswiber))
  * The best way to improve the state of the art is to see hypermedia applied to more use cases and have feedback shared publicly with the community. ([@kevinswiber](https://twitter.com/kevinswiber))
  * What are the metrics of success for your API? How do hypermedia designs contribute to or detract from those metrics? ([@mikekelly85](https://twitter.com/mikekelly85))
  * Is adding links to a response enough? ([@MarkusLanthaler](https://twitter.com/MarkusLanthaler))
  * What are the benefits of adding HTTP method and payload encoding information to links - aka forms/actions for APIs? What are the problems? Is it worth it?  ([@JornWildt](https://twitter.com/JornWildt))
  * Are more complicated media types, that require more than an HTTP library and a JSON parser to deal with, moving away from the "simplicity" that has been driving web API adoption over SOAP?  ([@mikekelly85](https://twitter.com/mikekelly85))
  * Does adding hypermedia really help if the data itself can't be understood without out-of-band knowledge? ([@MarkusLanthaler](https://twitter.com/MarkusLanthaler))
  * What are the pros and cons of moving hypermedia controls to a separate, machine-readable document (API descriptions) compared to embedding them directly in resource representations? ([@MarkusLanthaler](https://twitter.com/MarkusLanthaler))
  * How would an ideal hypermedia client library look like? ([@MarkusLanthaler](https://twitter.com/MarkusLanthaler))
  * People often have a knee jerk reaction to dismiss hypermedia APIs as a complex approach to API design. What is your three sentence pitch to convince these people that it is not overkill, and in fact can be a simpler approach over time? ([@MattMcLartyBC](https://twitter.com/MattMcLartyBC))

**Formats:**

* Collection+JSON - http://amundsen.com/media-types/collection/format/
* UBER - https://rawgit.com/mamund/media-types/master/uber-hypermedia.html
* ALPS - http://alps.io/
* HAL - http://stateless.co/hal_specification.html
* Siren - https://github.com/kevinswiber/siren
* Hydra - http://www.markus-lanthaler.com/hydra/
* JSON-LD - http://json-ld.org/
* json:api - http://jsonapi.org/
* Mason - https://github.com/JornWildt/Mason
