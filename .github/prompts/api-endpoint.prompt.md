Create a **{endpoint_name}** API endpoint using **{framework}** (e.g. NestJS, Express, FastAPI, ASP.NET Core, etc.).

### Requirements:

**Functional Requirements:**
- Implement the full endpoint logic according to the described use case
- Follow RESTful principles (or GraphQL if specified)
- Use proper HTTP methods and status codes
- Return consistent response format across the application

**Technical Requirements:**
- Full input validation using the framework's preferred method (Zod, Pydantic, class-validator, DataAnnotations, etc.)
- Proper error handling with meaningful error messages
- Implement logging for important events and errors
- Add necessary authentication and authorization checks
- Use dependency injection where applicable
- Follow async/await patterns properly

**Code Quality:**
- Clean, readable, and well-structured code
- Comprehensive JSDoc / docstrings / XML comments
- Meaningful variable and function names
- Proper separation of concerns
- Follow the existing architecture and patterns in this project

**Security & Performance:**
- Protect against common vulnerabilities (injection, rate limiting, etc.)
- Consider pagination for list endpoints
- Add appropriate caching headers if needed
- Validate and sanitize all user inputs

**Additional Output:**
- Suggest relevant unit or integration test cases
- Include any necessary DTOs, request/response models, or schemas
- Add OpenAPI/Swagger annotations if applicable

---

**Example Usage:**
Endpoint: `POST /api/users`
Framework: NestJS + TypeScript
