# cs465-fullstack

CS-465 Full Stack Development with MEAN

## Architecture

Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

Why did the backend use a NoSQL MongoDB database?

In building the full stack application, I used two types of front-end development: Express HTML for customer-facing pages and Angular for the administrative Single-Page Application (SPA). The Express HTML side renders pages server-side, which is effective for displaying static content. In contrast, Angular handles client-side rendering, making it well-suited for dynamic content, like admin dashboards, by minimizing server-client communication and improving user interactivity.

The backend uses MongoDB, a NoSQL database because it efficiently stores and retrieves JSON-like documents. MongoDB's flexibility is particularly useful for the evolving data requirements of a web application, such as the varying data structures seen with different trip records in the application.

## Functionality

How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.

JSON serves as a bridge between the front and back ends. Unlike JavaScript, which is a programming language, JSON is simply a format for representing data. It allowed data from MongoDB to be passed to Angular for rendering, making integration between the backend API and the Angular front end seamless.

I refactored the code during the project by creating reusable Angular components like TripListingComponent and TripCardComponent. These components improved the application's maintainability by simplifying updates and minimizing redundancy, as the same components could be reused in multiple parts of the SPA.

## Testing

Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.

Testing involved using Postman to verify API endpoints for the GET and PUT methods, ensuring data retrieval and updates worked correctly between Angular and the backend. This included testing authorization headers, especially after adding security features like JWT-based authentication. Challenges included CORS errors, which were resolved by enabling CORS in the Express application and adjusting the data format to match the Angular service's expectations.

## Reflection

How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

This course has strengthened my skills in full stack development, especially in using Angular for client-side rendering, integrating with NoSQL databases, and securing web applications with JWT authentication. Working through these technologies and learning to build reusable components has made me more adaptable as a developer, and these skills will be valuable as I move into the industry.
