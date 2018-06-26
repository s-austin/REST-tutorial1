### Source: https://restfulapi.net/
##### Quoted excerpts from the above page follow

REST is acronym for REpresentational State Transfer. It is architectural style for distributed hypermedia systems and was first presented by Roy Fielding in 2000 in his famous dissertation.'''

#### Guiding Principles of REST

##### Client–server – By separating the user interface concerns from the data storage concerns, we improve the portability of the user interface across multiple platforms and improve scalability by simplifying the server components.

#### LESSON LEARNED: Separation of concerns, user interface versus data storage

##### Stateless – Each request from client to server must contain all of the information necessary to understand the request, and cannot take advantage of any stored context on the server. Session state is therefore kept entirely on the client.

#### LESSON LEARNED1: Cannot take advantage of any stored context on the server. 
#### LESSON LEARNED2: Session state kept entirely on the client. 

##### Cacheable – Cache constraints require that the data within a response to a request be implicitly or explicitly labeled as cacheable or non-cacheable. If a response is cacheable, then a client cache is given the right to reuse that response data for later, equivalent requests.

#### LESSON LEARNED: Must explicity be labeled as cacheable or non-cacheable.

##### Uniform interface – By applying the software engineering principle of generality to the component interface, the overall system architecture is simplified and the visibility of interactions is improved. In order to obtain a uniform interface, multiple architectural constraints are needed to guide the behavior of components. REST is defined by four interface constraints: identification of resources; manipulation of resources through representations; self-descriptive messages; and, hypermedia as the engine of application state.

#### LESSON LEARNED: REST is defined by four interface constraints:
##### A: identification of resources
##### B:  manipulation of resources through representations
##### C: self-descriptive messages
##### D: hypermedia as the engine of application state
