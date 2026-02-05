

# 🦾 Project Chimera: Autonomous AI Influencer

## 🎯 Project Vision
Build a factory that produces autonomous AI influencers—digital entities that research trends, create content, engage audiences, and generate revenue without human intervention.

## 🏗️ Factory Model
Project Chimera follows a **factory production model**:

```text
RAW MATERIALS → FACTORY PROCESS → FINISHED PRODUCTS
(Trends/Data) (Chimera Factory) (Social Content)
                    ↓ ↓ ↓
┌──────────┐  ┌─────────────────┐  ┌──────────┐
│ Input    │→ │ • Research      │→ │ Output   │
│ Layer    │  │ • Content       │  │ Layer    │
│          │  │ • Governance    │  │          │
│          │  │ • Learning      │  │          │
└──────────┘  └─────────────────┘  └──────────┘

```

## 🏗️ Architecture Overview

### Core Components:
1. **Research Engine** - Analyzes trends from web and agent networks
2. **Content Creator** - Generates posts, images, videos
3. **Safety Layer** - Ensures content quality and compliance
4. **Learning System** - Improves based on engagement data
5. **Agent Network** - Integrates with OpenClaw and MoltBook

## Core Technologies
### AI/ML Stack: 
- **LLMs:** GPT-4, Claude 3, Llama 3
- **Frameworks:** LangChain, LlamaIndex, Haystack
- **Vector DB:** Pinecone/Weaviate
- **Embeddings:** OpenAI, Cohere

### Backend Stack:
- **Language:** Python 3.12
- **Framework:** FastAPI
- **Database:** PostgreSQL + Redis
- **Queue:** Celery + Redis

### Infrastructure:
- **Container:** Docker + Docker Compose
- **CI/CD:** GitHub Actions
- **Monitoring:** Prometheus + Grafana
- **Logging:** ELK Stack


## 🏭 The Factory Model

Project Chimera follows a **Factory Model** where:
- **specs/** = Factory blueprints and instructions
- **skills/** = Assembly line and tools
- **tests/** = Quality control department
- **governance/** = Safety and compliance office
- **.github/workflows/** = Shipping and logistics

### Factory Workflow:
```text
┌─────────────────────────────────────────────────┐
│ RAW MATERIALS                                   │
│ (Trends, Data, User Requests)                   │
└───────────────────┬─────────────────────────────┘
                    │
┌───────────────────▼─────────────────────────────┐
│ RESEARCH & DESIGN                               │
│ • Analyze trends                                │
│ • Plan content strategy                         │
│ • Check specifications (specs/)                 │
└───────────────────┬─────────────────────────────┘
                    │
┌───────────────────▼─────────────────────────────┐
│ MANUFACTURING                                   │
│ • Create content (skills/)                      │
│ • Apply templates                               │
│ • Add media                                     │
└───────────────────┬─────────────────────────────┘
                    │
┌───────────────────▼─────────────────────────────┐
│ QUALITY CONTROL                                 │
│ • Run tests (tests/)                            │
│ • Check safety (governance/)                    │
│ • Human review if needed                        │
└───────────────────┬─────────────────────────────┘
                    │
┌───────────────────▼─────────────────────────────┐
│ SHIPPING                                        │
│ • Schedule posts                                │
│ • Deploy to platforms                           │
│ • Monitor engagement                            │
└─────────────────────────────────────────────────┘
```

### Agent Communication Protocols:
Project Chimera agents use standardized protocols to communicate:

1. **MCP (Internal):** Tool communication within factory
2. **OpenClaw Skill Protocol:** Skill definition standard
3. **MoltBook Social Protocol:** Agent network etiquette
4. **Governance Protocol:** Safety and compliance rules


## 📁 Project Structure
```text
chimera-factory/
├── specs/                    # 📝 INSTRUCTIONS
│   ├── _meta.md             # "Big picture" document
│   ├── functional.md        # "What the AI should DO"
│   └── technical.md         # "How the AI should DO it"
├── skills/                  # 🛠️ AI TOOLS
│   ├── download_video.md    # "How to download videos"
│   └── create_post.md       # "How to create posts"
├── tests/                   # 📚 PRACTICE TESTS
│   └── test_download.py     # "Test if video downloading works"
├── .github/workflows/       # 🤖 ROBOT TEACHER
│   └── main.yml             # "Check AI's work automatically"
├── Dockerfile               # 📦 BOX FOR EVERYTHING
├── Makefile                 # ⚡ QUICK COMMANDS
└── .cursor/rules            # 🧠 AI HELPER INSTRUCTIONS

```

### Core Directories:
- **`specs/`** - Factory blueprints and instructions
- **`skills/`** - Assembly line tools and capabilities
- **`tests/`** - Quality control department
- **`governance/`** - Safety and compliance office
- **`src/`** - Production line source code
- **`.github/`** - Shipping and logistics

### Configuration Files:
- **`SOUL.md`** - Agent identity and persona
- **`AGENTS.md`** - Governance and decision rules
- **`.cursor/rules/`** - AI assistant instructions
- **`.vscode/mcp.json`** - Tool connectivity



## 🚀 Quick Start
### Prerequisites:
- Python 3.12+
- Docker
- VS Code with Copilot
- Tenx MCP Connection

### 1. Clone & Setup:

```bash
# Clone repository
git clone https://github.com/benkenlin/project-chimera
cd project-chimera

# Setup virtual environment
python -m venv venv
venv\Scripts\activate  # Windows
source venv/bin/activate  # Mac/Linux

# Install dependencies
pip install -r requirements.txt

# Copy environment template
cp .env.example .env
# Edit .env with your API keys

#Run Verification
python scripts/verify_setup.py

#Run Verification
make dev
```

## 🏭 Factory Departments
### 1. Research & Development (`specs/`)
- **Creates blueprints for production**
- **Defines what to build and why**
- **Ensures alignment with goals**

### 2. Manufacturing (`skills/`)
- **Assembly line of reusable capabilities**
- **Standardized skill interfaces**
- **Quality-controlled outputs**

### 3. Quality Control (`tests/`)
- **Automated testing suite**
- **Performance validation**
- **Safety compliance checks**

### 4. Safety Office (`governance/`)
- **Content moderation**
- **Ethical compliance**
- **Risk management**

### 5. Learning Center (`src/learning/`):
- **Continuous improvement**
- **Performance optimization**
- **Pattern recognition**

## 🤝 Agent Society Integration
### OpenClaw Integration:
- **Uses OpenClaw as operating system**
- **Executes skills locally on hardware**
- **Manages persistent agent state**

### MoltBook Integration:
- **Participates in agent social network**
- **Builds reputation as professional influencer**
- **Engages with other autonomous agents**

### Economic Autonomy:
- **Coinbase AgentKit integration**
- **Non-custodial crypto wallets**
- **Automated revenue management**