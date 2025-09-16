# System Architecture

This project uses NestJS with ESModule support for modular, scalable server-side development.

## Modules

- AppModule: Main application module
- AppController: Handles HTTP requests
- AppService: Business logic provider

## Data Flow

- Requests are routed through controllers to services
- Responses are standardized and error handling is centralized

## Dependencies

- TypeScript, ESLint, Prettier, Husky, Commitlint, Semantic Release
