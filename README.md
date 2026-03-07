# 🏠 Smart Home Usage Monitor

## Overview
Backend system to track smart appliance usage. Supports multi-user, energy tracking, cost calculation, and intelligent recommendations.

## Core Features
- Multi-user support
- Appliance ownership
- Usage logging and calculations
- DTO layer for clean API
- RESTful API

## Entities & DTOs
- User → UserDTO
- Appliance → ApplianceDTO
- UsageLog → UsageLogDTO
- Recommendation → RecommendationDTO

## Development Steps
1. Create entities
2. Create DTOs
3. Create mappers (Entities ↔ DTOs)
4. Create repositories
5. Implement service layer
6. Implement controllers using DTOs
7. Test APIs with Postman
8. Add frontend integration (Vue.js)

## REST API Examples
- `POST /users` → create user
- `GET /users/{id}` → returns UserDTO
- `POST /users/{id}/appliances` → create appliance
- `GET /users/{id}/appliances` → returns ApplianceDTO list
- `POST /appliances/{id}/usage` → log usage
- `GET /appliances/{id}/recommendation` → returns RecommendationDTO

## Technologies
- Java, Spring Boot, Spring Data JPA
- Hibernate, REST APIs
- Vue.js (frontend)

## Author
Anastasios Kabundi








