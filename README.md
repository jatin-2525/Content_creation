# Content Creation
A modern full-stack **Content Creation platform** built with Next.js and TypeScript. The project provides a foundation for building a centralized content-management and creator workflow application with database integration, authentication support, data visualization, and content aggregation.

## Features
* Modern responsive web application
* Content management foundation
* PostgreSQL database integration
* Type-safe database operations with Drizzle ORM
* Authentication and secure password handling
* Session/JWT-based authentication support
* Data visualization with Recharts
* RSS/content feed parsing
* Responsive UI with Tailwind CSS
* Production-ready Next.js architecture

## Tech Stack
### Frontend
* **Next.js 16**
* **React 19**
* **TypeScript**
* **Tailwind CSS**
* **Recharts**

### Backend & Database
* **Next.js**
* **PostgreSQL**
* **Drizzle ORM**
* **Drizzle Kit**
* **Node.js**

### Authentication & Security
* **bcryptjs** — Password hashing
* **jose** — JWT and secure token handling
* **dotenv** — Environment configuration

### Content & Data
* **RSS Parser** — RSS/feed processing
* **Recharts** — Data visualization

## Getting Started
### Prerequisites
Make sure you have installed:
* Node.js
* npm
* PostgreSQL

### Installation
Clone the repository:
```bash
git clone https://github.com/jatin-2525/Content_creation.git
```

Navigate to the project:
```bash
cd Content_creation
```

Install dependencies:
```bash
npm install
```

## Environment Variables
Create a `.env.local` file in the project root and configure the required environment variables.
Example:
```env
DATABASE_URL=your_postgresql_connection_string
```

Add any additional environment variables required by your local implementation.
> Never commit `.env.local` or private credentials to GitHub.

## Database Setup
The project uses **PostgreSQL** with **Drizzle ORM**.
After configuring your database connection, use the project's Drizzle configuration and migration workflow to create and update the database schema.

## Run the Development Server
Start the development server:
```bash
npm run dev
```

Open the application at:
```text
http://localhost:3000
```

## Available Scripts
### Development
```bash
npm run dev
```

### Production Build
```bash
npm run build
```

### Production Server
```bash
npm start
```

### Lint
```bash
npm run lint
```

### Type Checking
```bash
npm run typecheck
```

## Project Architecture
The application follows a modern Next.js full-stack architecture:
```text
Content_creation/
├── app/
├── components/
├── lib/
├── public/
├── drizzle.config.json
├── next.config.ts
├── postcss.config.mjs
├── package.json
├── tsconfig.json
└── README.md
```

## Development Goals
The project is designed as a foundation for developing a centralized content-creation workflow.
Potential capabilities include:
* Content organization
* Content feed aggregation
* Creator dashboards
* Analytics and visualization
* Database-backed content management
* Secure user authentication
* Automated content workflows

## Future Improvements
* [ ] Add complete content management workflows
* [ ] Add creator dashboard
* [ ] Add content scheduling
* [ ] Add analytics dashboard
* [ ] Add social-media integrations
* [ ] Add AI-assisted content generation
* [ ] Add content recommendations
* [ ] Add advanced search and filtering
* [ ] Add user profiles and role-based access
* [ ] Add automated testing
* [ ] Deploy the application

## Learning Objectives
This project provides practical experience with:
* Full-stack Next.js development
* React and TypeScript
* PostgreSQL database design
* Drizzle ORM
* Authentication and authorization concepts
* Secure password handling
* REST/API-oriented application development
* Data visualization
* RSS feed processing
* Tailwind CSS
* Production application architecture

## Author
**Jatin Kumar Singhal**
GitHub: [jatin-2525](https://github.com/jatin-2525)

## License
This project is intended for educational and personal use.
