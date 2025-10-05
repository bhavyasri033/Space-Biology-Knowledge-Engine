#  Space Biology Knowledge Engine

> **An AI-powered research platform for NASA's space biology research with comprehensive analytics, cross-domain synergy analysis, and mission readiness assessment.**

## 📋 Project Overview

The Space Biology Knowledge Engine is a comprehensive full-stack platform designed to accelerate NASA's space biology research through AI-powered insights and role-based dashboards. The platform serves three distinct user roles: **Scientists**, **Managers**, and **Mission Planners**, each with specialized interfaces and capabilities tailored to their specific needs.

<img width="1919" height="1004" alt="image" src="https://github.com/user-attachments/assets/c338bfe8-d00b-4a4d-94ba-d37e29967d3d" />

## 🔄 Website Workflow

The platform operates on a three-tier architecture:

1. **Frontend Layer**: Next.js 15.5 with React 19.1 provides an immersive mission control interface
2. **Backend Layer**: FastAPI server handles AI services, data processing, and API endpoints
3. **Data Layer**: Processes NASA Task Book datasets and PubMed papers with vector embeddings

**Core Workflow**: Users select their role → Access specialized dashboard → Interact with AI-powered tools → Generate insights and reports → Make data-driven decisions.

### 📺 Watch the Complete Flow
You can watch the entire flow of the website and see all features in action here: [**YouTube Demo Video**](https://youtu.be/OUCHEOKKYC4?si=0Ay2VDMlxtutHYRg)


## 👥 Role-Based Features

### 🔬 Scientist Dashboard
- **Research Papers Browser**: Advanced search, filtering, and categorization of 10,000+ research papers
- **AI-Powered Summaries**: Technical analysis with methodology insights and citation metrics
- **Knowledge Graph**: Interactive visualization of research networks and collaboration opportunities
- **Gap Analysis**: Identify research opportunities and unexplored areas
- **Methodology Comparison**: Compare research approaches and their effectiveness
- <img width="1919" height="1003" alt="image" src="https://github.com/user-attachments/assets/5caff1b7-15fd-4816-91f9-22154ba83f2e" />




### 💼 Manager Dashboard
- **Investment Analytics**: ROI tracking, funding analysis, and budget optimization
- **Duplicate Detection**: Identify overlapping research projects to reduce costs
- **Resource Optimization**: Cost-saving recommendations and efficiency metrics
- **Team Performance**: Research team analytics and productivity tracking
- **Strategic Insights**: Business intelligence for research investment decisions
- <img width="1919" height="1009" alt="image" src="https://github.com/user-attachments/assets/857285eb-37a1-4f2a-8cbd-c76df3037007" />




### 🚀 Mission Planner Interface
- **Mission Feasibility Analysis**: Comprehensive risk assessment with 0-100 scoring
- **Resource Requirements**: Calculate food, water, and oxygen needs for space missions
- **Crew Health Planning**: Exercise protocols and medical support requirements
- **Real-time Data Integration**: Live ISS crew data and radiation monitoring
- **AI Recommendations**: Mission optimization suggestions based on biological constraints
- <img width="1899" height="1006" alt="image" src="https://github.com/user-attachments/assets/4a8e3c82-58e7-4153-9353-5278796dcb75" />


## 🛠️ Tech Stack

### Frontend
- **Next.js 15.5** with App Router
- **React 19.1** with TypeScript
- **Tailwind CSS 4** for styling
- **Radix UI** for accessible components
- **Framer Motion** for animations
- **Zustand** for state management
- **TanStack Query** for API management
- **Recharts** for data visualization

### Backend
- **FastAPI** with Python 3.8+
- **Pandas & NumPy** for data processing
- **Scikit-learn** for ML algorithms
- **Sentence Transformers** for text embeddings
- **FAISS** for vector similarity search
- **NetworkX** for graph analysis

### Data & AI
- **NASA Task Book** dataset (CSV)
- **PubMed Papers** (JSONL format)
- **TF-IDF Vectorization** for text similarity
- **Cross-Domain Synergy Analysis**
- **Hypothesis Generation Engine**

## 🚀 Local Setup Instructions

### Prerequisites
- Python 3.8+ with pip
- Node.js 18+ with pnpm
- Git

### Backend Setup
```bash
cd nasa_project/cursor-back

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Start FastAPI server
python main.py
```

### Frontend Setup
```bash
cd nasa_project/cursor-front

# Install dependencies
pnpm install

# Start development server
pnpm run dev
```

### Access URLs
- **Frontend**: http://localhost:3000
- **Backend API**: http://localhost:8000
- **API Docs**: http://localhost:8000/docs

## 🎯 Key Features

- **Mission Readiness Index**: 5-category assessment (Biological, Technical, Resource, Safety, Research)
- **Cross-Domain Synergy**: TF-IDF analysis to identify collaboration opportunities
- **AI-Powered Insights**: Automated hypothesis generation and paper summarization
- **Real-time Analytics**: Live data integration from ISS and space monitoring systems
- **Role-Based Access**: Specialized interfaces for different user types

## 📊 Performance Metrics

- **10,000+** research papers processed
- **Sub-second** search response times
- **Real-time** mission feasibility scoring
- **Automated** duplicate detection with 95%+ accuracy
- **Cross-domain** synergy analysis across multiple research areas

## 🔧 Configuration

Set environment variables for API keys and database connections. The platform uses configurable category rules for research classification and supports custom similarity thresholds for synergy analysis.

## 📄 License

MIT License - see LICENSE file for details.

---

**Built for the future of space biology research** 🚀
