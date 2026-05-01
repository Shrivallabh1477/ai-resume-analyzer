# AI Resume Analyzer

LLM-powered resume analysis and job matching system.

## Features
- Resume parsing with NLP
- Job description analysis
- Multi-dimensional matching
- AI-powered suggestions
- Skill gap analysis

## Quick Start

### Prerequisites
- Python 3.9+
- Node.js 16+
- Docker & Docker Compose
- PostgreSQL 12+

### Installation

1. Clone repository
```bash
git clone https://github.com/yourusername/ai-resume-analyzer.git
cd ai-resume-analyzer
```

2. Create .env file
```bash
cp backend/.env.example backend/.env
# Edit .env and add your API keys
```

3. Start with Docker
```bash
docker-compose up -d
```

4. Access application
- Frontend: http://localhost:3000
- Backend API: http://localhost:8000/api/docs
- Database: localhost:5432

## Documentation

- [Installation Guide](docs/INSTALLATION.md)
- [API Documentation](docs/API_ENDPOINTS.md)
- [Architecture](docs/ARCHITECTURE.md)
- [Deployment Guide](docs/DEPLOYMENT.md)

## Tech Stack

- **Backend**: FastAPI, SQLAlchemy, PostgreSQL
- **Frontend**: React, TypeScript, Tailwind CSS
- **LLM**: OpenAI, Anthropic Claude
- **Vector DB**: Pinecone
- **Deployment**: Docker, Kubernetes, AWS

## Contributing

Please read [CONTRIBUTING.md](.github/CONTRIBUTING.md) for details.

## License

MIT License - see LICENSE file for details

## Author

Your Name

## Support

For issues and questions, please use GitHub Issues.
