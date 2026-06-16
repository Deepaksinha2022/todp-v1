# TODP Architecture

## Architecture Style

Modular Monolith

## Frontend

React

Responsibilities:
- Search UI
- Institution UI
- Service UI
- Admin UI

## Backend

FastAPI

Responsibilities:
- Search API
- Ranking Engine
- Discovery Hierarchy
- Institution Management

## Database

PostgreSQL

Responsibilities:
- Store institutions
- Store services
- Store locations
- Store rankings

## Vector Search

pgvector

Purpose:
- Semantic search
- Similarity matching

## Cache

Redis

Purpose:
- Search caching
- Performance optimization

## Deployment

Single Server (V1)

## Rules

- No microservices
- No Kubernetes
- No event bus
- No unnecessary complexity
- Prefer maintainability