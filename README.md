# AI Backend Validator (Spring Boot + AI)

A backend microservice that validates and enriches incoming API requests using AI-driven workflows.

## Features
- REST API built with Spring Boot
- AI-assisted validation (LLM-ready design)
- JSON request validation and enrichment
- Clean microservices architecture

## Tech Stack
- Java 17
- Spring Boot
- REST APIs
- AI/LLM integration ready (OpenAI / Claude)

## API Example

### Endpoint
POST /api/validate

### Request
```json
{
  "name": "sushma",
  "email": "sushmab.com"
}

### Response
```json
{
  "valid": false,
  "issues": ["Invalid email format"],
  "suggestions": ["sushma@example.com"]
}
