# URL Shortener — Full Stack App

A full stack URL shortener built with Spring Boot and React, featuring JWT authentication, analytics, and cloud deployment.

## Tech Stack

**Backend:** Java, Spring Boot, Spring Security, JWT, JPA/Hibernate, MySQL  
**Frontend:** React, Tailwind CSS, Context API  
**DevOps:** Docker, Cloud MySQL, VPS Deployment

## Features

- User signup & login with JWT authentication
- Shorten any URL with a custom alias
- Per-URL analytics (click tracking)
- Dashboard to manage all shortened URLs
- Subdomain and redirect management
- Protected routes on the frontend
- Fully Dockerized and deployed to production

## Getting Started

### Backend
\```bash
cd backend
./mvnw spring-boot:run
\```

### Frontend
\```bash
cd frontend
npm install
npm run dev
\```

### Environment Variables
Create `application.properties` in the backend with:
\```
spring.datasource.url=YOUR_DB_URL
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD
jwt.secret=YOUR_JWT_SECRET
\```

## Live Demo
[Link here]

## License
MIT
