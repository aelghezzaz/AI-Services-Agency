# AI Services Agency 👨‍💼

AI Services Agency is an AI-driven application simulating a full-service digital agency. It utilizes multiple AI agents to analyze and plan software projects. Each agent represents a distinct role in the project lifecycle, from strategic planning to technical implementation.

## Features

### Five Specialized AI Agents

- **CEO Agent**: Strategic leader and final decision maker
  - Analyzes startup ideas with structured evaluation.
  - Makes decisions across product, technical, marketing, and financial domains.
  - Tools: `AnalyzeStartupTool`, `MakeStrategicDecision`.

- **CTO Agent**: Technical architecture and feasibility expert
  - Evaluates technical requirements and feasibility.
  - Provides architecture decisions.
  - Tools: `QueryTechnicalRequirements`, `EvaluateTechnicalFeasibility`.

- **Product Manager Agent**: Product strategy expert
  - Defines product strategy and roadmap.
  - Coordinates between technical and marketing teams.
  - Focuses on product-market fit.

- **Developer Agent**: Technical implementation expert
  - Provides detailed technical implementation guidance.
  - Suggests the optimal tech stack, cloud solutions, and estimates costs and timelines.

- **Client Success Agent**: Marketing strategy expert
  - Develops go-to-market strategies.
  - Plans customer acquisition approaches.
  - Coordinates with the product team.

### Custom Tools

- **Analysis Tools**: 
  - `AnalyzeProjectRequirements` for market evaluation and startup idea analysis.
  
- **Technical Tools**: 
  - `CreateTechnicalSpecification` for technical assessments.

### Asynchronous Communication

- Enables parallel processing of analysis tasks from different agents.
- Efficient collaboration in real-time with non-blocking operations for better performance.

### Agent Communication Flows

- **CEO ↔️ All Agents** (Strategic Oversight)
- **CTO ↔️ Developer** (Technical Implementation)
- **Product Manager ↔️ Marketing Manager** (Go-to-Market Strategy)
- **Product Manager ↔️ Developer** (Feature Implementation)

## How to Run

To set up and run the application, follow these steps:

### 1. Get Your OpenAI API Key

First, you need an OpenAI API key. Obtain it [here](https://platform.openai.com/api-keys).

### 2. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/aelghezzaz/AI-Services-Agency.git

 3. Install Dependencies
Install the required dependencies using pip:
pip install -r requirements.txt

4. Run the Streamlit App
Run the application using Streamlit:
streamlit run ai_services_agency/agency.py


