# Booking System REST API

A robust, production-ready RESTful API for booking systems. Designed with scalability, maintainability, and developer experience in mind.

## Features

- User authentication and role-based access control
- Booking and cancellation workflows
- Search and filtering capabilities
- API documentation (OpenAPI/Swagger)
- Error handling and validation
- Unit and integration tests

## Getting Started



### Installation

```bash
git clone https://github.com/Saba-Burduli/Booking-System-RestAPI-Final-One.git
cd Booking-System-RestAPI-Final-One
dotnet install
```

### Environment Variables

Create a `.env` file in the root:

```
PORT=3000
DATABASE_URL=your_npsql_url
JWT_SECRET=your_jwt_secret
```

### Running the App

```bash
dotnet start
# or for development:
dotnet run dev
```

### Running Tests

```bash
dotnet test
```

## API Documentation

Interactive API docs are available at `/api-docs` when the server is running.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

