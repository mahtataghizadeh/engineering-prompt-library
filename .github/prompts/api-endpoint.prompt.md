Create a **{endpoint_name}** API endpoint using **{framework}** (NestJS, Express, FastAPI, ASP.NET Core, etc.).

### Requirements:

**Functional:**
- Implement complete business logic for this endpoint
- Follow RESTful best practices (or GraphQL if specified)
- Use correct HTTP method and return appropriate status codes
- Return consistent response structure used across the project

**Technical:**
- Full input validation (Zod / Pydantic / class-validator / etc.)
- Comprehensive error handling with user-friendly messages
- Proper logging (success, errors, important events)
- Authentication and authorization checks
- Use dependency injection correctly
- Async/await best practices

**Code Quality:**
- Clean, readable, well-structured code
- Follow existing project architecture and naming conventions
- Comprehensive documentation (JSDoc / docstrings)
- Proper separation of concerns (controllers, services, repositories)

**Security & Performance:**
- Protect against common web vulnerabilities
- Input sanitization
- Consider pagination, filtering, and sorting for list endpoints
- Add rate limiting considerations if applicable

**Additional:**
- Include request/response DTOs or models
- Add OpenAPI/Swagger annotations if used in the project
- Suggest relevant unit/integration test cases
