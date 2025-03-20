# Legal AI Agent

An AI-powered legal assistant for Costa Rican law.

## Project Structure

```
├── frontend/     # Next.js frontend application
├── backend/      # Node.js backend API
└── docs/         # Documentation
```

## Features

- Legal document analysis
- Case management
- AI-powered legal research
- Subscription management
- User authentication

## Getting Started

### Prerequisites

- Node.js >= 18
- PostgreSQL
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/ByronCC/LegalAIAgent.git
```

2. Install dependencies:
```bash
# Frontend
cd frontend
npm install

# Backend
cd ../backend
npm install
```

3. Set up environment variables:
```bash
# Frontend (.env.local)
NEXT_PUBLIC_API_URL=http://localhost:3005

# Backend (.env)
PORT=3005
DB_HOST=localhost
DB_PORT=5432
DB_NAME=legalai
DB_USER=postgres
DB_PASSWORD=your_password
JWT_SECRET=your_jwt_secret
```

4. Start the development servers:
```bash
# Backend
cd backend
npm run dev

# Frontend (new terminal)
cd frontend
npm run dev
```

## License

MIT