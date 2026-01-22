# 🚀 AI-Powered Data & Business Analyst Platform

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0--beta-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Python](https://img.shields.io/badge/python-3.11+-blue.svg)
![TypeScript](https://img.shields.io/badge/typescript-5.0+-blue.svg)
![FastAPI](https://img.shields.io/badge/FastAPI-0.104+-green.svg)
![Next.js](https://img.shields.io/badge/Next.js-14+-black.svg)

**Transform raw business documents into professional analytical insights with a single prompt**

[Live Demo](https://github.com/milansharma01/ai-business-analyst) • [Documentation](https://github.com/milansharma01/ai-business-analyst/wiki) • [Report Bug](https://github.com/milansharma01/ai-business-analyst/issues) • [Request Feature](https://github.com/milansharma01/ai-business-analyst/issues)

</div>

---

## 📋 Table of Contents

- [About The Project](#about-the-project)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [API Documentation](#api-documentation)
- [Development](#development)
- [Testing](#testing)
- [Deployment](#deployment)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

---

## 🎯 About The Project

The **AI-Powered Data & Business Analyst Platform** is an intelligent web application that automates the entire data analysis workflow. Built for product managers, business analysts, and decision-makers, it eliminates the need for technical expertise while delivering professional-grade insights.

### The Problem

Business professionals waste countless hours:
- ⏰ Manually processing and analyzing data
- 📊 Creating charts and visualizations
- 📝 Writing analytical reports
- 🔍 Identifying trends and patterns
- 💡 Formulating actionable recommendations

### The Solution

Upload your files, describe what you need in plain English, and receive:
- ✅ **Executive summaries** with key findings
- ✅ **Detailed analytical reports** with evidence-based insights
- ✅ **Interactive visualizations** and dashboards
- ✅ **Actionable recommendations** prioritized by impact
- ✅ **Professional exports** (PDF, Excel, PowerPoint)

### Built With

<div align="center">

[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)

</div>

---

## ✨ Key Features

### 🎯 Core Capabilities

#### **Smart File Processing**
- 📄 **Multi-format support**: PDF, Excel (.xlsx, .xls), Word (.docx), CSV, TSV
- 📤 **Batch upload**: Process up to 10 files simultaneously
- 🔍 **Intelligent extraction**: Automatically detects tables, charts, and text
- ✅ **Validation**: Built-in virus scanning and format verification

#### **Advanced Analytics**
- 📊 **Descriptive Analytics**: Summary statistics, distributions, data quality reports
- 🔎 **Diagnostic Analytics**: Root cause analysis, correlations, variance analysis
- 📈 **Predictive Insights**: Trend forecasting, pattern recognition, anomaly detection
- 💡 **Prescriptive Analytics**: Actionable recommendations, optimization suggestions

#### **AI-Powered Insights**
- 🤖 **GPT-4 Integration**: Leverages latest LLM technology
- 🧠 **Context-aware**: Understands business context and domain-specific terminology
- 📝 **Natural language**: Explains insights in plain English
- 🎯 **Industry-specific**: Adapts to finance, marketing, healthcare, and more

#### **Professional Visualizations**
- 📊 **20+ chart types**: Line, bar, scatter, heatmap, waterfall, and more
- 🎨 **Interactive dashboards**: Zoom, filter, and explore your data
- 📱 **Responsive design**: Perfect on desktop, tablet, and mobile
- 💾 **Export options**: Download as PNG, SVG, or embed in reports

#### **Comprehensive Reports**
- 📄 **Executive summaries**: 2-3 paragraph overviews for stakeholders
- 📋 **Detailed analysis**: Step-by-step findings with supporting evidence
- 📊 **Visual reports**: Charts and graphs integrated seamlessly
- 📦 **Multiple formats**: PDF, Word, PowerPoint, Excel

### 🚀 User Experience

- **One-Prompt Analysis**: Single text input for entire workflow
- **Real-time Progress**: Live updates via WebSocket
- **Template Library**: Pre-built prompts for common analyses
- **History & Favorites**: Save and reuse past analyses
- **Collaboration**: Share results with team members
- **Dark Mode**: Easy on the eyes for extended use

---

## 🛠️ Tech Stack

### Frontend

| Technology | Version | Purpose |
|------------|---------|---------|
| **Next.js** | 14+ | React framework with SSR |
| **React** | 18+ | UI component library |
| **TypeScript** | 5.0+ | Type-safe JavaScript |
| **TailwindCSS** | 3.4+ | Utility-first CSS |
| **shadcn/ui** | Latest | Component library |
| **Recharts** | 2.10+ | Data visualization |
| **D3.js** | 7.8+ | Advanced visualizations |
| **React Query** | 5.0+ | Data fetching & caching |
| **Zustand** | 4.4+ | State management |
| **Framer Motion** | 10.0+ | Animations |

### Backend

| Technology | Version | Purpose |
|------------|---------|---------|
| **Python** | 3.11+ | Core language |
| **FastAPI** | 0.104+ | Web framework |
| **Pandas** | 2.0+ | Data manipulation |
| **NumPy** | 1.24+ | Numerical computing |
| **scikit-learn** | 1.3+ | Machine learning |
| **LangChain** | 0.1+ | LLM orchestration |
| **OpenAI SDK** | 1.0+ | GPT-4 integration |
| **Anthropic SDK** | 0.8+ | Claude integration |
| **SQLAlchemy** | 2.0+ | ORM |
| **Celery** | 5.3+ | Task queue |

### Infrastructure

| Technology | Purpose |
|------------|---------|
| **PostgreSQL** | Primary database |
| **Redis** | Caching & sessions |
| **MinIO/S3** | File storage |
| **Docker** | Containerization |
| **Kubernetes** | Orchestration |
| **Nginx** | Reverse proxy |
| **GitHub Actions** | CI/CD |

### AI/ML Services

- **OpenAI GPT-4 Turbo**: Complex reasoning and insights
- **Anthropic Claude 3**: Long-context analysis
- **OpenAI Embeddings**: Semantic search
- **Pinecone/ChromaDB**: Vector database

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** 18+ and npm/yarn
- **Python** 3.11+
- **Docker** and Docker Compose
- **PostgreSQL** 15+ (or use Docker)
- **Redis** (or use Docker)

### Installation

#### 1. Clone the Repository

```bash
git clone https://github.com/milansharma01/ai-business-analyst.git
cd ai-business-analyst
```

#### 2. Set Up Backend

```bash
cd backend

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run database migrations
alembic upgrade head

# Start the backend server
uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```

#### 3. Set Up Frontend

```bash
cd frontend

# Install dependencies
npm install
# or
yarn install

# Start development server
npm run dev
# or
yarn dev
```

#### 4. Using Docker (Recommended)

```bash
# From project root
docker-compose up -d

# Access the application
# Frontend: http://localhost:3000
# Backend API: http://localhost:8000
# API Docs: http://localhost:8000/docs
```

### Environment Variables

#### Backend (.env)

Create a `.env` file in the `backend/` directory:

```env
# Application
APP_NAME=AI Business Analyst Platform
ENVIRONMENT=development
DEBUG=True
SECRET_KEY=your-super-secret-key-change-this-in-production
API_V1_PREFIX=/api/v1

# Database
DATABASE_URL=postgresql://user:password@localhost:5432/analysis_db
DATABASE_POOL_SIZE=20

# Redis
REDIS_URL=redis://localhost:6379/0

# File Storage
STORAGE_TYPE=s3  # or 'local' or 'minio'
AWS_ACCESS_KEY_ID=your-access-key
AWS_SECRET_ACCESS_KEY=your-secret-key
AWS_REGION=us-east-1
S3_BUCKET_NAME=analysis-platform-files

# AI Services
OPENAI_API_KEY=sk-your-openai-api-key
ANTHROPIC_API_KEY=sk-ant-your-anthropic-key
OPENAI_MODEL=gpt-4-turbo-preview
ANTHROPIC_MODEL=claude-3-opus-20240229

# Vector Database
PINECONE_API_KEY=your-pinecone-key
PINECONE_ENVIRONMENT=us-west1-gcp

# Celery
CELERY_BROKER_URL=redis://localhost:6379/1
CELERY_RESULT_BACKEND=redis://localhost:6379/2

# Security
JWT_SECRET_KEY=your-jwt-secret-key-change-this
JWT_ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=15
REFRESH_TOKEN_EXPIRE_DAYS=7

# CORS
CORS_ORIGINS=http://localhost:3000,https://yourdomain.com

# Email (Optional)
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_USER=your-email@gmail.com
SMTP_PASSWORD=your-app-password
```

#### Frontend (.env.local)

Create a `.env.local` file in the `frontend/` directory:

```env
# API Configuration
NEXT_PUBLIC_API_URL=http://localhost:8000
NEXT_PUBLIC_WS_URL=ws://localhost:8000

# Authentication
NEXT_PUBLIC_APP_URL=http://localhost:3000

# Feature Flags
NEXT_PUBLIC_ENABLE_ANALYTICS=true
NEXT_PUBLIC_ENABLE_COLLABORATION=false

# Analytics (Optional)
NEXT_PUBLIC_GA_ID=G-XXXXXXXXXX
```

---

## 📖 Usage

### Quick Start Guide

#### 1. **Create an Account**

Visit `http://localhost:3000` and sign up with your email.

#### 2. **Upload Your Files**

- Click **"New Analysis"** from the dashboard
- Drag and drop your files (or click to browse)
- Supported formats: PDF, Excel, Word, CSV
- Upload up to 10 files at once

#### 3. **Describe What You Need**

Enter a natural-language prompt:

```
Examples:
- "Analyze Q4 sales trends and identify top-performing products"
- "Compare revenue across regions and explain key drivers"
- "Find anomalies in customer churn data and recommend retention strategies"
- "Summarize customer feedback and identify common themes"
```

#### 4. **Get Your Results**

Within minutes, receive:
- **Executive Summary**: High-level findings
- **Detailed Insights**: Step-by-step analysis
- **Visualizations**: Interactive charts
- **Recommendations**: Prioritized action items

#### 5. **Export & Share**

- Download as PDF, Word, or PowerPoint
- Share link with teammates
- Export data to Excel
- Embed charts in presentations

### Example Use Cases

<details>
<summary><b>📊 Sales Analysis</b></summary>

**Prompt:**
```
Analyze our Q3 sales data. Identify top-performing products, regions with declining sales, 
and provide recommendations to improve revenue in underperforming areas.
```

**Files:** `sales_q3_2024.xlsx`

**Output:**
- Revenue breakdown by product and region
- YoY and MoM growth analysis
- Underperforming segment identification
- 5 actionable recommendations
- 8 interactive visualizations
</details>

<details>
<summary><b>📈 Marketing Campaign ROI</b></summary>

**Prompt:**
```
Compare the ROI of our Facebook, Google, and LinkedIn campaigns from the past 6 months. 
Which channels should we invest more in?
```

**Files:** `campaign_data.xlsx`, `conversion_metrics.csv`

**Output:**
- ROI calculations by channel
- Cost per acquisition analysis
- Conversion funnel breakdown
- Budget allocation recommendations
- Channel performance comparison charts
</details>

<details>
<summary><b>🔍 Customer Feedback Analysis</b></summary>

**Prompt:**
```
Analyze customer reviews and identify the top 5 complaint categories. 
Provide sentiment trends over time and suggest improvements.
```

**Files:** `customer_reviews.csv`, `support_tickets.xlsx`

**Output:**
- Sentiment analysis (positive/negative/neutral)
- Topic modeling (complaint categories)
- Trend analysis over time
- Word clouds and frequency charts
- Prioritized improvement suggestions
</details>

---

## 📁 Project Structure

```
ai-business-analyst/
├── backend/
│   ├── app/
│   │   ├── api/                    # API endpoints
│   │   │   └── v1/
│   │   │       ├── endpoints/      # Route handlers
│   │   │       └── router.py
│   │   ├── core/                   # Core functionality
│   │   │   ├── config.py          # Configuration
│   │   │   ├── security.py        # Auth & security
│   │   │   └── exceptions.py
│   │   ├── services/               # Business logic
│   │   │   ├── file_processor/    # File handling
│   │   │   ├── analysis_engine/   # Analytics
│   │   │   ├── ai_engine/         # LLM integration
│   │   │   ├── visualization/     # Chart generation
│   │   │   └── report_generator/  # Report creation
│   │   ├── models/                 # Database models
│   │   ├── schemas/                # Pydantic schemas
│   │   ├── db/                     # Database layer
│   │   └── main.py                 # App entry point
│   ├── tests/                      # Test suite
│   ├── alembic/                    # DB migrations
│   ├── requirements.txt
│   └── Dockerfile
│
├── frontend/
│   ├── src/
│   │   ├── app/                    # Next.js pages
│   │   │   ├── (auth)/            # Auth pages
│   │   │   ├── (dashboard)/       # Dashboard pages
│   │   │   └── page.tsx
│   │   ├── components/             # React components
│   │   │   ├── ui/                # UI components
│   │   │   ├── upload/            # Upload components
│   │   │   ├── analysis/          # Analysis components
│   │   │   ├── results/           # Results components
│   │   │   └── charts/            # Chart components
│   │   ├── lib/                    # Utilities
│   │   │   ├── api/               # API client
│   │   │   ├── hooks/             # Custom hooks
│   │   │   └── utils/             # Helper functions
│   │   ├── store/                  # State management
│   │   ├── types/                  # TypeScript types
│   │   └── styles/
│   ├── public/                     # Static assets
│   ├── package.json
│   └── Dockerfile
│
├── docker-compose.yml
├── .github/
│   └── workflows/                  # CI/CD pipelines
├── docs/                           # Documentation
├── scripts/                        # Utility scripts
├── LICENSE
└── README.md
```

---

## 📚 API Documentation

### Interactive API Docs

Once the backend is running, visit:
- **Swagger UI**: http://localhost:8000/docs
- **ReDoc**: http://localhost:8000/redoc

### Key Endpoints

#### Authentication

```http
POST /api/v1/auth/register
POST /api/v1/auth/login
POST /api/v1/auth/refresh
GET  /api/v1/auth/me
```

#### File Management

```http
POST   /api/v1/files/upload
GET    /api/v1/files/{file_id}
DELETE /api/v1/files/{file_id}
GET    /api/v1/files/
```

#### Analysis

```http
POST   /api/v1/analysis/start
GET    /api/v1/analysis/{id}
DELETE /api/v1/analysis/{id}
GET    /api/v1/analysis/
```

#### Results & Export

```http
GET  /api/v1/results/{analysis_id}
POST /api/v1/export/pdf
POST /api/v1/export/docx
POST /api/v1/export/pptx
```

### Example API Request

```bash
# Start a new analysis
curl -X POST "http://localhost:8000/api/v1/analysis/start" \
  -H "Authorization: Bearer YOUR_TOKEN" \
  -H "Content-Type: application/json" \
  -d '{
    "file_ids": ["file-123", "file-456"],
    "prompt": "Analyze sales trends and identify top products"
  }'
```

### Response Format

```json
{
  "analysis_id": "analysis-789",
  "status": "queued",
  "message": "Analysis started successfully",
  "estimated_time": 120
}
```

---

## 🔧 Development

### Running Tests

#### Backend Tests

```bash
cd backend

# Run all tests
pytest

# Run with coverage
pytest --cov=app --cov-report=html

# Run specific test file
pytest tests/test_analysis.py

# Run with verbose output
pytest -v
```

#### Frontend Tests

```bash
cd frontend

# Run unit tests
npm test

# Run with coverage
npm test -- --coverage

# Run E2E tests
npm run test:e2e
```

### Code Quality

```bash
# Backend
cd backend

# Format code
black app/
isort app/

# Type checking
mypy app/

# Linting
ruff check app/

# Frontend
cd frontend

# Format code
npm run format

# Linting
npm run lint

# Type checking
npm run type-check
```

### Database Migrations

```bash
cd backend

# Create a new migration
alembic revision --autogenerate -m "Add new table"

# Apply migrations
alembic upgrade head

# Rollback
alembic downgrade -1
```

### Starting Celery Workers

```bash
cd backend

# Start worker
celery -A app.tasks.celery_app worker --loglevel=info

# Start with concurrency
celery -A app.tasks.celery_app worker --loglevel=info --concurrency=4

# Start beat scheduler (for periodic tasks)
celery -A app.tasks.celery_app beat --loglevel=info
```

---

## 🚢 Deployment

### Docker Deployment

```bash
# Build images
docker-compose build

# Start services
docker-compose up -d

# View logs
docker-compose logs -f

# Stop services
docker-compose down
```

### Kubernetes Deployment

```bash
# Apply configurations
kubectl apply -f k8s/

# Check deployment status
kubectl get pods
kubectl get services

# View logs
kubectl logs -f deployment/backend

# Scale deployment
kubectl scale deployment backend --replicas=3
```

### Environment-Specific Builds

```bash
# Production build
docker build -t ai-business-analyst:prod -f Dockerfile.prod .

# Staging build
docker build -t ai-business-analyst:staging -f Dockerfile.staging .
```

### Health Checks

```bash
# Backend health
curl http://localhost:8000/health

# Frontend health
curl http://localhost:3000/api/health
```

---

## 🗺️ Roadmap

### Version 1.0 (Current - MVP)
- [x] File upload (PDF, Excel, Word, CSV)
- [x] Natural language prompts
- [x] Basic analytics (descriptive, diagnostic)
- [x] Chart generation (10+ types)
- [x] PDF/Excel export
- [x] User authentication
- [x] Real-time progress tracking

### Version 1.1 (Q2 2026)
- [ ] Advanced visualizations (network graphs, geo maps)
- [ ] Collaboration features (share, comments)
- [ ] Custom templates
- [ ] PowerPoint export
- [ ] Email report delivery
- [ ] Dark mode

### Version 1.2 (Q3 2026)
- [ ] Predictive analytics (forecasting)
- [ ] Custom metric builders
- [ ] Industry-specific templates
- [ ] API access for developers
- [ ] Scheduled analyses
- [ ] Mobile app (iOS/Android)

### Version 2.0 (Q4 2026)
- [ ] Fine-tuned custom models
- [ ] Enterprise SSO
- [ ] Advanced permissions & roles
- [ ] White-label options
- [ ] On-premise deployment
- [ ] Real-time collaboration

See the [open issues](https://github.com/milansharma01/ai-business-analyst/issues) for a full list of proposed features and known issues.

---

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

### How to Contribute

1. **Fork the Project**
2. **Create your Feature Branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your Changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the Branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Contribution Guidelines

- Follow the existing code style
- Write tests for new features
- Update documentation
- Keep commits atomic and descriptive
- Reference issues in PR descriptions


## 📧 Contact

**Project Creator & Maintainer**: Milan Sharma  
**LinkedIn**: [https://www.linkedin.com/in/milansharma01](https://www.linkedin.com/in/milansharma01)  
**GitHub**: [@milansharma01](https://github.com/milansharma01)  
**Email**: milan.sharma@example.com

**Project Repository**: [https://github.com/milansharma01/ai-business-analyst](https://github.com/milansharma01/ai-business-analyst)

**Live Demo**: [Coming Soon]

**Documentation**: [GitHub Wiki](https://github.com/milansharma01/ai-business-analyst/wiki)

---

## 🙏 Acknowledgments

### Core Technologies
- [Next.js](https://nextjs.org/) - React framework
- [FastAPI](https://fastapi.tiangolo.com/) - Python web framework
- [OpenAI](https://openai.com/) - GPT-4 API
- [Anthropic](https://www.anthropic.com/) - Claude API
- [Vercel](https://vercel.com/) - Frontend hosting
- [shadcn/ui](https://ui.shadcn.com/) - UI components

### Inspiration & Resources
- [LangChain Documentation](https://docs.langchain.com/)
- [Recharts Examples](https://recharts.org/)
- [FastAPI Best Practices](https://github.com/zhanymkanov/fastapi-best-practices)
- [Next.js Examples](https://github.com/vercel/next.js/tree/canary/examples)

### Special Thanks
- To all the open-source contributors who make projects like this possible
- The amazing developer communities on GitHub, Stack Overflow, and Reddit
- Early beta testers and users providing valuable feedback

### Contributors
Thanks to all the amazing people who have contributed to this project!

<a href="https://github.com/milansharma01/ai-business-analyst/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=milansharma01/ai-business-analyst" />
</a>

---

## 📊 Project Stats

![GitHub stars](https://img.shields.io/github/stars/milansharma01/ai-business-analyst?style=social)
![GitHub forks](https://img.shields.io/github/forks/milansharma01/ai-business-analyst?style=social)
![GitHub issues](https://img.shields.io/github/issues/milansharma01/ai-business-analyst)
![GitHub pull requests](https://img.shields.io/github/issues-pr/milansharma01/ai-business-analyst)
![GitHub last commit](https://img.shields.io/github/last-commit/milansharma01/ai-business-analyst)

---

## 💖 Support the Project

If you find this project helpful, please consider:

- ⭐ **Star the repository** to show your support
- 🐛 **Report bugs** and issues you encounter
- 💡 **Suggest new features** that would be valuable
- 📖 **Improve documentation** to help others
- 🔧 **Contribute code** to enhance the platform
- 📢 **Share** with colleagues who might benefit

**Connect with me on LinkedIn**: [Milan Sharma](https://www.linkedin.com/in/milansharma01)

---

<div align="center">

**Built with ❤️ by Milan Sharma**

*Transforming how businesses leverage data for decision-making*

[GitHub](https://github.com/milansharma01) • [LinkedIn](https://www.linkedin.com/in/milansharma01) • [Documentation](https://github.com/milansharma01/ai-business-analyst/wiki)

</div>
