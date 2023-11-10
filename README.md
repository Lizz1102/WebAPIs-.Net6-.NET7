# WebAPIs: .NET Core(.Net6,.NET7)
Learning and revisiting some advanced and fundamental concepts of .NET Core Web APIs. Exploring new features of Web APIs with C# in .NET Core (.NET 6 and .NET 7 SDK versions).  


## Notes 


Keeping the references/notes for myself, or anyone who wants to revisit related concepts.


<details>
     <summary>**REST**</summary>
     <p>
       - REST is a design concept. 
       - Rest builds on the foundation of HTTP, utilizing its methods, URIs, status codes, and other features to create a scalable and standardized architecture for building web APIs. The principles of REST are designed to align with the capabilities and characteristics of the HTTP protocol.
     </p>
</details>


- [HTTP response status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
- [A Comprehensive Guide To HTTP/3 And QUIC + HTTP/1.1 vs HTTP/2 vs HTTP/3](https://www.debugbear.com/blog/http3-quic-protocol-guide)
- [HTTP/1.1 Original Specification](https://datatracker.ietf.org/doc/html/rfc2616)

  
## Observations: Improvements/What's New in .NET 6


**HTTP/3 Support**


.NET 6 includes preview support for HTTP/3. HTTP/3 solves some existing functional and performance challenges by using a new underlying connection protocol called QUIC. QUIC establishes connections more quickly, and connections are independent of the IP address, allowing mobile clients to roam between Wi-fi and cellular networks.


**Minimal APIs**: ASP.NET 6 introduces Minimal APIs, a lightweight approach to building APIs with less boilerplate code. 


If we uncheck **Use controllers** checkbox while creating a new project using **ASP.NET Core Web API** template, then the template doesn't create any Controllers. 


Minimal APIs make it easy to quickly write smaller, faster microservices. For microservices or serverless architectures where we might have small, focused APIs, minimal APIs provide a lightweight way to define these APIs without unnecessary overhead. When you have APIs with a single, focused purpose (e.g., exposing a specific functionality or data), minimal APIs can be a good fit. Use minimal APIs for quick prototyping, testing, or building temporary APIs to validate ideas.







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
