# Autonomous Fleet Orchestrator

A robust fleet management API for orchestrating autonomous robots and vehicles. This project explores scalable backend patterns for real-time command, control, and monitoring of distributed autonomous systems. It serves as a practical implementation for managing operational intelligence.

## Key Features
*   RESTful API for vehicle registration, status updates, and task dispatch.
*   Real-time communication layer for live telemetry and command streaming.
*   Persistent job queue for managing asynchronous, long-running fleet operations.
*   Structured logging and health monitoring endpoints.

## Tech Stack
FastAPI, PostgreSQL, Redis, SQLAlchemy, Pydantic, Python 3.11+

## Getting Started
1.  Clone the repository: `git clone https://github.com/zoreanuj/autonomous-fleet-orchestrator.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Configure environment variables in `.env`.
4.  Run the application: `uvicorn app.main:app --reload`