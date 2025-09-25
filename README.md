# GIRAV Project Portal - Mockup

## Quick Setup

### Prerequisites
- Node.js 16+
- MongoDB
- Git

### Installation
```bash
# Clone repository
git clone https://github.com/yourusername/girav-portal.git
cd girav-portal

# Backend setup
cd backend
npm install
cp .env.example .env
# Edit .env with your MongoDB URI

# Frontend setup
cd ../frontend
npm install

# Start development servers
# Terminal 1 - Backend
cd backend && npm run dev

# Terminal 2 - Frontend  
cd frontend && npm run dev
