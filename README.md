Full Stack Travlr Project Reflection
Architecture
This full stack application uses both a traditional Express-rendered frontend and an Angular single-page application (SPA). The customer-facing website uses Express, Handlebars templates, and JavaScript to render dynamic trip data from the server. In contrast, the admin interface is built as an Angular SPA, allowing dynamic updates without full page reloads and providing a more interactive experience for managing trips.
MongoDB was used as the backend database because its document-based structure works naturally with JSON data. Since the application transfers data in JSON format between frontend and backend, MongoDB integrates efficiently with Node.js and Express through Mongoose and supports flexible schema design.

Functionality
JSON differs from JavaScript in that it is strictly a data format, not a programming language. In this project, JSON connects the frontend and backend by serving as the data format for API responses. Trip data stored in MongoDB is retrieved by Express, sent as JSON, and rendered either through Handlebars templates or consumed by Angular services.
During development, I refactored code to improve structure and efficiency. For example, API logic was centralized in controllers, and Angular services were used to manage HTTP requests. Reusable UI components reduced redundancy and improved maintainability, making the application easier to scale.

Testing
Testing involved verifying RESTful API endpoints using GET, POST, and PUT requests to ensure correct database interaction. After implementing JWT-based authentication, I also tested secured endpoints to confirm that unauthorized users were blocked and authenticated users could access protected routes. This reinforced my understanding of endpoints, middleware, and layered application security.

Reflection
This course strengthened my understanding of full stack architecture and the MEAN stack. I developed practical skills in building RESTful APIs, integrating MongoDB databases, creating dynamic frontends, and implementing secure authentication using JWTs. Completing a fully functional, secure web application has given me a strong portfolio project and improved my confidence as a developer.

