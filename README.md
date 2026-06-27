# Hi, I'm Marwan.
### Backend Software Engineer & Computer Science Teaching Assistant

I am a backend engineer with a strong foundation in computer science, focused on translating theoretical algorithms into reliable, database-driven applications. I enjoy building robust systems, managing cloud infrastructure, and helping students grasp core programming logic.

## Current Status
* **Engineering:** Building ACID-compliant backend microservices, real-time distributed systems, and containerized deployments.
* **Instructing:** Guiding students through core computer science fundamentals, data structures, and logical analysis.
* **Operating:** Developing within Linux environments and deploying scalable infrastructure via Docker and Oracle Cloud.

## Technical Arsenal

**Backend & Architecture**
`Python` `FastAPI` `WebSockets` `PostgreSQL` `Redis (Pub/Sub & Queues)` `SQLAlchemy (ORM)` `RESTful APIs` `JWT / OAuth2`

**Core Logic & Languages**
`C++` `Object-Oriented Programming` `Algorithm Design & Analysis` `Concurrency`

**Infrastructure & Quality Assurance**
`Docker` `Docker Compose` `Linux (Arch / Ubuntu)` `Nginx` `Oracle Cloud (OCI)` `Alembic` `Git` `GitHub Actions (CI/CD)` `Pytest` `HTTPX`

---

## Current Architecture Focus

### [Real-Time CRDT Document API](https://github.com/marwan-esam/crdt-collaborative-document-editor)
A high-performance, real-time collaborative document editor backend utilizing fractional indexing Conflict-free Replicated Data Types (CRDTs) to ensure deterministic state across distributed clients.
* **Core Features:** Base-100 fractional indexing operations for character-level transformations, strict 3-second Reaper Handshake authentication protocols via WebSockets, Redis distributed locks for cache state synchronization, and a fully containerized architecture deployed on a secure Oracle Cloud instance.
* **Stack:** Python, FastAPI, WebSockets, PostgreSQL, Redis, Docker Compose, Pytest, Uvicorn/Gunicorn.

### [FastAPI Matchmaking Engine](https://github.com/marwan-esam/fastapi-matchmaking-engine)
An asynchronous matchmaking backend designed to pair users based on Elo ratings and manage real-time game states.
* **Core Features:** Asynchronous Redis worker queues for matchmaking and automated Elo settlement, real-time game state management via WebSockets, stateless JWT authentication, and automated CI/CD testing.[cite: 4] Deployed securely on an Oracle Cloud (OCI) Linux instance with an Nginx reverse proxy and Let's Encrypt SSL.
* **Stack:** Python, FastAPI, WebSockets, Redis, PostgreSQL, SQLAlchemy, Docker, Nginx, Pytest.

### [Real-Time Distributed Chat Engine](https://github.com/marwan-esam/real-time-chat)
A production-grade, asynchronous chat application utilizing a message broker pattern to allow for horizontal scaling of WebSocket connections across isolated worker processes.
* **Core Features:** Raw TCP WebSocket connections for real-time communication, Redis Pub/Sub for cross-worker state synchronization, stateful token revocation (Redis Blacklist), multi-container Docker bridge networking, and an automated cloud CI/CD testing pipeline.
* **Stack:** Python, FastAPI, WebSockets, Redis, PostgreSQL, SQLAlchemy, Docker, GitHub Actions, Pytest.

---

## Let's Connect

I am always looking to learn, build, and tackle new challenges in backend development and infrastructure. If you'd like to discuss code, architecture, or potential opportunities, feel free to reach out.

* **Email:** marwanesam60@gmail.com
