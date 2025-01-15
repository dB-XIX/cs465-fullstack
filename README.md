# CS-465 Full Stack Development with MEAN

## Architecture

### Frontend Development Comparison
In building the full stack application, I utilized two types of frontend development:
- **Express HTML**: Used for customer-facing pages, rendering content server-side. This approach is effective for displaying static content and ensuring quick initial page loads.
- **Angular**: Implemented for the administrative Single-Page Application (SPA). Angular handles client-side rendering, making it well-suited for dynamic content, such as admin dashboards. This approach minimizes server-client communication and enhances user interactivity.

### Backend and MongoDB
The backend uses MongoDB, a NoSQL database, due to its efficiency in storing and retrieving JSON-like documents. MongoDB's flexibility accommodates evolving data requirements, such as the varying data structures seen in trip records. This adaptability is critical for web applications that manage diverse datasets.

---

## Functionality

### JSON and Its Role in Full Stack Development
JSON (JavaScript Object Notation) differs from JavaScript in that it is a lightweight data format used for storing and exchanging data. While JavaScript is a full programming language, JSON acts as the bridge between the frontend and backend:
- Data is stored in MongoDB in JSON-like documents.
- The backend API retrieves this data and sends it to the Angular frontend, which renders it dynamically for users.

### Code Refactoring and UI Components
During the project, I refactored code to improve functionality and efficiency by creating reusable Angular components, including:
- **TripListingComponent**
- **TripCardComponent**

These components:
- Simplify updates by centralizing logic and UI design.
- Minimize redundancy, as they can be reused across multiple parts of the SPA.
- Enhance maintainability and scalability of the application.

---

## Testing

### API Testing and Security Challenges
Testing involved:
- **Postman**: Used to verify API endpoints for methods like GET and PUT, ensuring proper data retrieval and updates between Angular and the backend.
- **Security Testing**: Focused on verifying authorization headers and JWT-based authentication.

Challenges included:
- **CORS Errors**: Resolved by enabling CORS in the Express application and aligning data formats with Angular service requirements.
- **Endpoint Validation**: Ensured secure and accurate communication between the frontend and backend, mitigating potential vulnerabilities.

---

## Reflection

### Professional Growth
This course has significantly contributed to my professional development by strengthening my full stack development skills. Key areas of growth include:
- **Frontend Development**: Proficiency in Angular for client-side rendering and dynamic content management.
- **Backend Integration**: Experience with NoSQL databases like MongoDB and RESTful API design.
- **Security**: Understanding and implementing JWT authentication to secure web applications.
- **Reusable Components**: Mastery of creating modular, maintainable UI components for scalable application design.

These skills have made me a more marketable candidate, equipping me to handle complex full stack development tasks and adapt to industry demands.

