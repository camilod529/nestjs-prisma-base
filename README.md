# NestJS Prisma Base

A base template for building scalable and efficient back-end applications using [NestJS](https://nestjs.com) and [Prisma](https://www.prisma.io).

## Dependencies Versions 🚀

- 🌀 **@nestjs:** 11.0.1  
- 🔮 **prisma:** 6.4.1  

## Prerequisites

- [Node.js](https://nodejs.org) (v14 or higher)
- [pnpm](https://pnpm.io) (you can use npm or yarn as alternatives)
- A compatible database (PostgreSQL, MySQL, SQLite, etc.)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/camilod529/nestjs-prisma-base.git
   cd nestjs-prisma-base
   ```

2. **Install the dependencies:**

   ```bash
   pnpm install
   ```

3. **Configure the environment variables:**

   Copy the `.env.template` file to `.env` and edit the values according to your environment configuration:

   ```bash
   cp .env.template .env
   ```

## Usage

### Run in development mode

```bash
pnpm run start:dev
```

### Run in production mode

```bash
pnpm run start:prod
```

### Compile the project

```bash
pnpm run build
```

## Integration with Prisma

This project uses Prisma to manage the database. Make sure your database is configured and follow these steps:

1. **Generate the Prisma client:**

   ```bash
   pnpm prisma generate
   ```

2. **Run the database migrations:**

   ```bash
   pnpm prisma migrate dev
   ```

3. **Open Prisma Studio (optional):**

   To graphically view and manage your database data:

   ```bash
   pnpm prisma studio
   ```

## Deployment

When you're ready to deploy the application in production, make sure to:

- Properly configure the environment variables, especially the database connection.
- Follow the [NestJS deployment guides](https://docs.nestjs.com) to optimize performance and security.
- (Optional) Use platforms like [Mau](https://mau.nestjs.com) for simple AWS deployment.

## Contributing

Contributions are welcome! If you wish to improve this project:

1. Open an issue to discuss potential changes or improvements.
2. Submit a pull request with your proposals.

Please ensure you follow best practices and keep the code clean and well-documented.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

- **Author:** [Camilo Duran](https://github.com/camilod529)
- **Repository:** [NestJS Prisma Base on GitHub](https://github.com/camilod529/nestjs-prisma-base)