# Hi, I'm Marwan.
### Backend Software Engineer & Computer Science Educator

I specialize in bridging the gap between theoretical algorithmic complexity and highly scalable, database-driven backend architecture. 

## Current Status
* **Engineering:** Robust, ACID-compliant backend microservices, real-time distributed systems, and automated container orchestration.
* **Instructing:** Core computer science fundamentals, focusing on advanced data structures, execution-time optimization, and logical analysis.
* **Operating:** Native development within strictly controlled Linux environments, scaling to isolated, reproducible containerized deployments.

## Technical Arsenal

**Backend & Architecture**
`Python` `FastAPI` `WebSockets` `PostgreSQL` `Redis (Pub/Sub & Queues)` `SQLAlchemy (ORM)` `RESTful APIs` `JWT / OAuth2`

**Core Logic & Languages**
`C++` `Object-Oriented Programming` `Algorithm Design & Analysis` `Concurrency` 

**Infrastructure & Quality Assurance**
`Docker` `Docker Compose` `Linux (Arch / Ubuntu)` `Nginx` `Oracle Cloud (OCI)` `Alembic` `Git` `GitHub Actions (CI/CD)` `Pytest` `HTTPX`

---

## Current Architecture Focus

### [FastAPI Matchmaking Engine](https://github.com/marwan-esam/fastapi-matchmaking-engine)
A high-performance, asynchronous matchmaking backend designed to pair users based on Elo ratings and manage real-time game states.
* **Core Features:** Asynchronous Redis worker queues for matchmaking and automated Elo settlement, real-time game state management via WebSockets, stateless JWT authentication, and automated CI/CD testing. Deployed securely on an Oracle Cloud (OCI) Linux instance with an Nginx reverse proxy and Let's Encrypt SSL.
* **Stack:** Python, FastAPI, WebSockets, Redis, PostgreSQL, SQLAlchemy, Docker, Nginx, Pytest.

### [Real-Time Distributed Chat Engine](https://github.com/marwan-esam/real-time-chat)
A production-grade, asynchronous chat application utilizing a message broker pattern to allow for infinite horizontal scaling of WebSocket connections across isolated worker processes.
* **Core Features:** Raw TCP WebSocket connections for zero-latency communication, Redis Pub/Sub for cross-worker state synchronization, enterprise-grade stateful token revocation (Redis Blacklist), multi-container Docker bridge networking, and an automated cloud CI/CD testing pipeline.
* **Stack:** Python, FastAPI, WebSockets, Redis, PostgreSQL, SQLAlchemy, Docker, GitHub Actions, Pytest.

### [Financial Ledger API](https://github.com/marwan-esam/financial-ledger)
A containerized, ACID-compliant financial backend microservice designed to handle concurrent transactions and stateful data persistence. 
* **Core Features:** Automated container orchestration via Docker Compose, programmatic schema migrations via Alembic, strict PostgreSQL row-level locking and `CheckConstraints` for defense-in-depth data integrity, stateless OAuth2/JWT authentication, IDOR mitigation, and an automated Pytest QA pipeline.
* **Stack:** Python, FastAPI, PostgreSQL, SQLAlchemy, Alembic, Docker, Pytest.

---

## Let's Connect
If you want to discuss backend architecture, infrastructure orchestration, or algorithmic optimization, feel free to reach out.

* **Email:** marwanesam60@gmail.com
