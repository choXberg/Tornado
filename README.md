Here’s the description formatted in Markdown:

```markdown
## Tornado CMS

**Description:**
Tornado is a powerful, flexible, and highly extendable open-source CMS built on .NET 8. It is optimized for high performance and offers a modular architecture for developers, while providing a simple and intuitive user experience for content authors. Tornado is fully aligned with Domain-Driven Design (DDD), employs Test-Driven Development (TDD), and follows Onion Architecture to ensure clear separation of concerns and maintainability. Clean Code and best practices are central principles in the development of Tornado to create a robust and sustainable system.

### Tech Stack:

#### Backend:
- **.NET 8:** A modern, high-performance runtime for building the backend logic and APIs.
- **C# (with DDD and TDD):** Implementation of domain-specific models and logic, using Test-Driven Development (TDD) to ensure high-quality code and minimize bugs.
- **Entity Framework Core:** ORM (Object-Relational Mapper) for flexible database access across relational databases (Postgres, MSSQL, SQLite) and potentially document-based databases (MongoDB).
- **Onion Architecture:** The backend architecture follows Onion Architecture, which ensures a clear separation of the core domain logic (Core) from infrastructure (databases, APIs, etc.). This makes it easier to extend and swap out components.
- **Domain-Driven Design (DDD):** Tornado is built with well-defined domain models and aggregates to structure business logic and better align the software with real-world needs.
- **Clean Code Principles:** Code is written following Clean Code principles to ensure readability, maintainability, and simplicity. Continuous refactoring and adherence to best practices are key.

#### Frontend:
- **Headless CMS:** Tornado provides a headless architecture, where the backend is decoupled from the frontend. Content is served via a **REST API** or **GraphQL**.
- **Pluggable Frontend:** Developers can use any frontend framework, such as **React**, **Next.js**, **Blazor**, or other JavaScript frameworks, to build the user interface.
- **Theming and Templates:** Tornado supports a flexible theming system, allowing for dynamic loading and swapping of templates and designs.

#### Persistence:
- **Database Flexibility:** Tornado supports multiple database options, including:
  - **PostgreSQL**
  - **Microsoft SQL Server**
  - **SQLite**
  - **MongoDB** (for document-based persistence)
  This flexibility allows users to choose the database that best fits their needs.

#### Extensibility:
- **Modular and Plugin-based:** Tornado is built from the ground up to be modular, supporting plugins and extensions. Developers can easily add new modules to extend functionality, such as SEO, e-commerce, or analytics.
- **Event-Driven System:** An event-driven architecture allows developers to hook into important events (such as content publishing) to customize or extend functionality.

#### CI/CD and Development:
- **GitHub for Version Control and Collaboration:** The project is hosted on GitHub to attract a broad developer community.
- **GitHub Actions for CI/CD:** Automated testing and builds ensure continuous integration and delivery.
- **Testing:** To ensure high code quality, Tornado is developed with unit tests (xUnit) and integration tests.

#### Security and Scalability:
- **Role-Based Access Control (RBAC):** Flexible, secure role-based access to define different permissions for authors, administrators, and developers.
- **Caching:** Integration with caching technologies such as **Redis** or **MemoryCache** to maximize performance and handle traffic spikes efficiently.

---

### Summary:
Tornado combines cutting-edge technologies and principles to offer developers a powerful, flexible, and scalable CMS. It is built with extensibility and user-friendliness in mind, with a strong focus on performance and code quality through Test-Driven Development (TDD), Domain-Driven Design (DDD), and the application of Onion Architecture.
```

You can now copy and paste this into any Markdown editor or GitHub repository!