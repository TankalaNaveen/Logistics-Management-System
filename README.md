End-to-end logistics platform for managing Orders, Cargoes, Carriers, and Addresses with clean domain models.

RESTful CRUD built with Spring Boot + Hibernate (JPA) + JDBC, exposing predictable endpoints for each entity.

Role-Based Access Control (RBAC): Admin/User roles gating car management, order tracking, and cargo operations.

Optimized PostgreSQL schema with FK constraints, indexes, and cascade rules for strong data integrity.

JSP views + role-specific dashboards for a simple, task-focused UI (create, update, search, filter).

Service + Repository layers for testable, modular architecture; DTOs and mappers to keep controllers lean.

Validation & error handling using Bean Validation (JSR-380) and global exception handling for consistent API responses.

Environment-driven config (application.yml) and profiles for dev/prod; database migrations ready (Flyway/Liquibase friendly).

Container-ready: runs with PostgreSQL locally; easy to dockerize for reproducible setups.

Quality gates: logging, input validation, and pagination on list endpoints for performance at scale.
