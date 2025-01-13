# FastAPI Learning Roadmap
- :LiCalendar: **Duration:** 4 weeks ( 2 hours/day )
<span style="color:red">hello </span>
- :LiCheckSquare: **Goals:** Master FastAPI to build scalable, production-ready APIs

### Quick Navigation
- [[#<font color=7FFFD4> `ris:Flashlight` Week 1: FastAPI Basics</font>|Week 1: FastAPI Basics]]
- [[#<font color=D2691E>`ris Star` Week 2 Advanced Topics</font>| Week 2: Advanced Topics]]
- [[#<font color=6495ED>`ris Database2` Week 3 Database Intergration</font>| Week 3: Database Integration]]
- [[#<font color=BA55D3>`ris Global` Week 4 Production & Deployment</font>| Week 4: Production & Deployment]]

---
###  <font color=7FFFD4> `ris:Flashlight` Week 1: FastAPI Basics</font> 

[Week One](#<font color=7FFFD4> `ris:Flashlight` Week 1: FastAPI Basics</font>)

   `ris:Lightbulb` **Goal**: Learn foundation of FastAPI and build a simple APIs.

#### Day 1: Introduction to FastAPI
**:LiLink: Link:** [[day_1-introduction-to-fastapi]]

`ris:Search` **Key Topics**:
- What is FastAPI ?
- Install FastAPI & Uvicorn.
- Create your first FastAPI app.
- Explore swagger UI and ReDoc.

#### Day 2: Handling Requests
`ris:Search` **Key Topics**:
- HTTP methods: GET, POST, PUT, DELETE.
- path parameters.
- query parameters.

#### Day 3: Request & Response Models
`ris:Search` **Key Topics**:
- Pydantic for validation.
- Response models for structured data.

#### Day 4: Dependency Injection
`ris:Search` **Key Topics**:
- Reusable Dependencies in FastAPI

#### Day 5: Response Handling
`ris:Search` **Key Topics**:
- Custom HTTP responses and status codes.
- Returning JSON, text, or files.

#### Day 6: Error Handling
`ris:Search` **Key Topics**:
- Using `HTTPExeption` and custom handlers.

#### Day 7: Practice Day
`ris:TestTube` **Project**: 
- Build a **To-Do App** with CRUD operations.

---

### <font color=D2691E>`ris:Star` Week 2: Advanced Topics</font>
   `ris:Lightbulb` **Goal**: Add authentication, middleware, and advanced features.

#### Day 1: Organize Routes
`ris:Search` **Key Topics**:
- User routers.
- Tags, summaries, and documentations.

#### Day 2: Authentication
`ris:Search` **Key Topics**:
- Basic authentication.
- JWT-based authentication.

#### Day 3: Authorization
`ris:Search` **Key Topics**:
- Role-based access control.
- Protect routes using dependencies.

#### Day 4: Middleware
`ris:Search` **Key Topics**:
- Built-in and custom middleware.
- Login requests.

#### Day 5: Background Tasks
`ris:Search` **Key Topics**:
- Using `BackgroundTasks` for non-blocking operations.

#### Day 6: Custom Responses
`ris:Search` **Key Topics**:
- Streaming files with `StreamingResponse`.

#### Day 7: Practice Day
`ris:TestTube` **Project**: 
- Extend the **To-Do App** with authentication and file uploads.

---

## <font color=6495ED>`ris:Database2` Week 3: Database Intergration</font>
   `ris:Lightbulb` **Goal**: Connect and optimize database with FastAPI.

#### Day 1: SQLAlchemy Basics
`ris:Search` **Key Topics**:
- Setup database connections.
- Introduction to SQLAlchemy.

#### Day 2: CRUD with SQLAlchemy
`ris:Search` **Key Topics**:
- Define models and perform CRUD operations.

#### Day 3: Relationships in SQLAlchemy
`ris:Search` **Key Topics**:
- One-to-many and many-to-many relationships.

#### Day 4: Async Database Queries
`ris:Search` **Key Topics**:
- Asynchronous queries and `async/await` patterns.

#### Day 5: Alembic for Migrations
`ris:Search` **Key Topics**:
- Managing schema changes with *Alembic*.

#### Day 7: Practice Day
`ris:TestTube` **Project**: 
- Add a database with relationships to the **To-Do App**.

---

## <font color=BA55D3>`ris:Global` Week 4: Production & Deployment</font>
   `ris:Lightbulb` **Goal**: Prepare APIs for production and build a complete project.

#### Day 1: Configuration Management
`ris:Search` **Key Topics**:
- Use environments variables for secure settings.

#### Day 2: Testing
`ris:Search` **Key Topics**:
- Write unit and integration tests with *pytest*.
- Test endpoints using FastAPI's test clients.

#### Day 3: Asynchronous Tasks
`ris:Search` **Key Topics**:
- Integrate **Celery** for background tasks.

#### Day 4: Deployment
`ris:Search` **Key Topics**:
- Deploy FastAPI with Uvicorn and Gunicorn.
- Use Docker to containerize deployment.

#### Day 5: API Documentation
`ris:Search` **Key Topics**:
- Customize OpenAPI schema and documentation.

#### Day 6: Performance Optemization
`ris:Search` **Key Topics**:
- Add caching with **Redis**.
- Monitor Performance and logs.

#### Day 7: Final Project
`ris:TestTube` **Final Project**: 
- Build a complete **Employee Salary System** with authentication, database, and deployment.

#### Day 8: Wrap-Up
`ris:Search` **Key Topics**:
- Review concepts and best practice.
