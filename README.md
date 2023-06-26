# CS-465 Full Stack Development with MEAN

## Architecture
For this project, I utilized a combination of HTML, JavaScript, Express, and Angular for the frontend architecture. The customer-facing side of the application was built using HTML documents enhanced with JavaScript, which were served by Express. This followed the Model-View-Controller (MVC) pattern, where multiple pages were loaded individually as users requested them.

On the admin-facing side, I leveraged Angular, a TypeScript-based framework, to create a more interactive experience. Instead of loading separate pages, I designed the interface to dynamically load multiple components within a single HTML document. These components were preloaded, enabling seamless navigation for admins without the need to cache or load new pages. By having the necessary code already present on the client side, the application delivered a smooth and efficient user experience.

For the backend, I utilized MongoDB as the database solution. MongoDB is a highly compatible NoSQL database that integrates well with Node.js. It offers excellent scalability, and the fact that it stores data in BSON (Binary JSON) format makes the conversion to JSON straightforward and hassle-free.

Overall, the project utilized HTML and JavaScript in conjunction with Express and Angular for the frontend. The customer-facing side followed an MVC architecture with individual page loads, while the admin-facing side utilized Angular's component-based approach for seamless navigation. MongoDB served as the backend database, leveraging its scalability and convenient BSON-to-JSON conversion capabilities.

## Functionality
JSON is a data format, while JavaScript is a programming language. JSON provides a standardized way to represent structured data, making it easy to transmit information between the backend and frontend. It acts as a bridge, allowing data to be parsed and manipulated in JavaScript on the frontend side.

One example of code refactoring to enhance functionality and efficiency is the optimization of the trip card and trip list components. Initially, having two separate components to display the same information proved inefficient. However, by rendering each trip separately while still maintaining their cohesion, the overall functionality of the site improved. The reuse of UI components brings several benefits, including reducing the application's overall size, speeding up the development process, and minimizing the potential introduction of errors and vulnerabilities (as long as the component itself is secure).

## Testing
Before implementing security measures, there are multiple approaches to testing endpoints. The first method is accessing the API endpoint's localhost web address directly to verify if the page loads the data successfully or to observe any error messages if an error occurs. Another recommended approach is utilizing an application like Postman, which specializes in testing HTTP requests. Postman offers the advantage of incorporating security measures and inputs to test endpoints that may be protected against unauthorized access. This allows for comprehensive endpoint testing, even for authenticated scenarios.

There are several ways to test endpoints before implementing security measures. One approach is to directly access the API endpoint's localhost web address and observe if the data is successfully loaded or if any errors are encountered. Another effective method involves using dedicated tools like Postman, which can not only test HTTP requests but also handle security measures and inputs. This enables testing of endpoints that may be protected against unauthorized access, ensuring a comprehensive evaluation of the endpoints, even for scenarios involving authentication.

## Reflection
This course has been incredibly beneficial for my professional development. Balancing full-time work and my studies made it challenging at times, but with the last couple classes left will be worth all of it. The programming languages intrigued me, and whether I wanted to focus on either front-end or back-end development, this course has provided valuable insights. It has helped me narrow down my career direction and identify the additional skills necessary to remain competitive in the job market. The most significant skill I've acquired throughout this journey is gaining a deeper understanding of how various modules or components of code connect and collaborate to construct a final product.
