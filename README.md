# WebAPIs: .NET Core(.Net6,.NET7)
Learning and revisiting some advanced and fundamental concepts of .NET Core Web APIs. Exploring new features of Web APIs with C# in .NET Core (.NET 6 and .NET 7 SDK versions).  


## Notes 


Keeping the references/notes for myself, or anyone who wants to revisit related concepts.


<details>
  <summary>HTTP</summary>
  <p>
    &emsp;&emsp;- <a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/Status" target="_blank">HTTP response status codes</a>
  </p>

  <p>
    &emsp;&emsp;- <a href="https://www.debugbear.com/blog/http3-quic-protocol-guide" target="_blank">A Comprehensive Guide To HTTP/3 and QUIC + HTTP/1.1 vs HTTP/2 vs HTTP/3</a>
  </p>

  <p>
    &emsp;&emsp;- <a href="https://datatracker.ietf.org/doc/html/rfc2616" target="_blank">HTTP/1.1 Original Specification</a>
  </p>
</details>


<details>
  <summary>REST</summary>

  <p>
    &emsp;&emsp;- REST is a design concept.
  </p>
  
  <p>
    &emsp;&emsp;- Rest builds on the foundation of HTTP, utilizing its methods, URIs, status codes, and other features to create a scalable and standardized architecture for building web APIs. The principles of REST are designed to align with the capabilities and characteristics of the HTTP protocol.
  </p>

    <details>
    <summary>More on: REST is built on top of HTTP</summary>
  
    &emsp;&emsp;&emsp;&emsp;**HTTP Methods (Verbs):**  
    &emsp;&emsp;&emsp;&emsp;REST relies on standard HTTP methods (verbs) for interactions with resources. The primary methods used in RESTful APIs are GET (retrieve), POST (create), PUT (update/replace), PATCH (partially update), and DELETE (delete).
  
    &emsp;&emsp;&emsp;&emsp;**Uniform Resource Identifier (URI):**  
    &emsp;&emsp;&emsp;&emsp;RESTful APIs use URIs to identify resources. URIs are the paths that clients use to access and manipulate resources. For example, /users might represent a collection of users, and /users/123 might represent a specific user with ID 123.
  
    &emsp;&emsp;&emsp;&emsp;**HTTP Status Codes:**  
    &emsp;&emsp;&emsp;&emsp;HTTP status codes are used to indicate the result of a client's request. RESTful APIs return status codes such as 200 (OK), 201 (Created), 404 (Not Found), and 500 (Internal Server Error) to convey the outcome of operations.
  
    &emsp;&emsp;&emsp;&emsp;**Statelessness:**  
    &emsp;&emsp;&emsp;&emsp;REST adheres to the statelessness constraint, meaning each request from a client to a server must contain all the information needed to understand and fulfill the request. The server does not store the client's state between requests.
  
    &emsp;&emsp;&emsp;&emsp;**Representation Formats:**  
    &emsp;&emsp;&emsp;&emsp;REST commonly uses standard data representation formats, such as JSON or XML, for exchanging information between clients and servers. These formats are specified in the HTTP headers (e.g., Content-Type).
  
    &emsp;&emsp;&emsp;&emsp;**HATEOAS (Hypermedia As The Engine Of Application State):**  
    &emsp;&emsp;&emsp;&emsp;HATEOAS is a constraint in REST that uses hypermedia links in the response to enable clients to discover and navigate to related resources. Links are embedded in the representation, guiding clients on what actions are possible.
  
    &emsp;&emsp;&emsp;&emsp;**Cacheability:**  
    &emsp;&emsp;&emsp;&emsp;HTTP provides mechanisms for caching, and RESTful APIs often leverage caching to improve performance. Cache-related headers, like Cache-Control, can be used to control caching behavior.
  
    &emsp;&emsp;&emsp;&emsp;**Content Negotiation:**  
    &emsp;&emsp;&emsp;&emsp;Content negotiation, facilitated by HTTP headers such as Accept and Content-Type, allows clients and servers to agree on the format of the representation data (e.g., JSON or XML).
  
  </details>

</details>


<details>
      <summary>Title</summary>
      <p>
           Content 1 Content 1 Content 1 Content 1 Content 1
      </p>
</details>

  
## Observations: Improvements/What's New in .NET 6


<details>
      <summary>HTTP/3 Support</summary>
      <p>
      &emsp;&emsp;- .NET 6 includes preview support for HTTP/3. HTTP/3 solves some existing functional and performance challenges by using a new underlying connection protocol called QUIC.QUIC establishes connections more quickly, and connections are independent of the IP address, allowing mobile clients to roam between Wi-fi and cellular networks. 
      </p>
</details>


<details>
  <summary>Minimal APIs</summary>
  <p>
    &emsp;&emsp;- ASP.NET 6 introduces Minimal APIs, offering a lightweight approach to building APIs with reduced boilerplate code. Unlike the traditional ASP.NET Core Web API template, if the <strong>Use controllers</strong> checkbox is unchecked during project creation, no controllers are generated. This feature caters to developers aiming to minimize unnecessary components.
  </p>
  
  <p>
    &emsp;&emsp;- Minimal APIs simplify the process of developing smaller, faster microservices. In scenarios where a microservices or serverless architecture demands small, focused APIs, minimal APIs eliminate unnecessary overhead. They are particularly suitable for APIs with a single, well-defined purpose, providing an efficient way to define such APIs.
  </p>

  <p>
    &emsp;&emsp;- Consider leveraging minimal APIs for quick prototyping, testing, or the creation of temporary APIs to validate ideas. Their lightweight nature makes them well-suited for scenarios where a rapid development cycle and minimal setup are essential.
  </p>
</details>


<details>
      <summary>Title</summary>
      <p>
           Content 1 Content 1 Content 1 Content 1 Content 1
      </p>
</details>


## TODOs


- [ ] Add Endpoint Specifications  
- [ ] Add screenshots/demo  
- [ ] Summarize key concepts developers should know before diving into web API development
- [ ] Future Improvements? 


## Credits


- [Christian Wenz: Advanced Web APIs with ASP.NET Core in .NET 6](https://www.linkedin.com/learning/advanced-web-apis-with-asp-dot-net-core-in-dot-net-6/filtering-items?contextUrn=urn%3Ali%3AlearningCollection%3A7127800062000201728)
- [Christian Wenz: Building Web APIs with ASP.NET Core in .NET](https://www.linkedin.com/learning/building-web-apis-with-asp-dot-net-core-in-dot-net/hello-world-api-style-19429584?contextUrn=urn%3Ali%3AlearningCollection%3A7127800062000201728)
- [Create web APIs with ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/web-api/?view=aspnetcore-7.0)https://learn.microsoft.com/en-us/aspnet/core/web-api/?view=aspnetcore-7.0)
- [APIs with ASP.NET Core](https://dotnet.microsoft.com/en-us/apps/aspnet/apis)
