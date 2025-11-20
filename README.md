## Travel Booking API

Backend service for searching flights, managing user profiles, and booking or canceling trips. Built with Express.js, MongoDB, and Mongoose, and ready for deployment on Vercel.

### Features
- RESTful routes for flights, users, and bookings (10 endpoints total)
- MongoDB persistence with Mongoose models
- JWT-based authentication with password hashing
- Swagger UI documentation exposed at /api-docs
- Production-ready configuration for Vercel serverless deployment

### API Overview
| Method | Route | Description |
| --- | --- | --- |
| GET | `/api/v1/flights` | Search flights by city/date/passengers |
| GET | `/api/v1/flights/:flightId` | Fetch a specific flight |
| POST | `/api/v1/users` | Register user and receive JWT |
| GET | `/api/v1/users/:userId` | Authenticated user views their bookings |
| PUT | `/api/v1/users/:userId` | Update user profile |
| DELETE | `/api/v1/users/:userId` | Delete user account |
| POST | `/api/v1/bookings` | Create booking with seat check |
| GET | `/api/v1/bookings/:bookingId` | View booking details |
| PUT | `/api/v1/bookings/:bookingId` | Modify existing booking |
| DELETE | `/api/v1/bookings/:bookingId` | Cancel a booking |
| POST | `/api/v1/auth/login` | (Bonus) Login to obtain JWT |





