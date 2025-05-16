
# 🧠 Multi-Agent Market Research System: AI/ML Jobs in MENA

## 📌 Overview

This project presents a **Multi-Agent Market Research System** designed to autonomously gather and analyze market intelligence on **AI/ML job trends in the MENA region (Middle East and North Africa)**. Powered by [CrewAI](https://crewai.com/) or a similar agent-based framework, the system automates job data collection, analysis, and report generation, offering actionable insights for job seekers, employers, and researchers.

## 🎯 Objective

Design and deploy a **collaborative multi-agent system** to:

- Search web platforms for live job postings in the AI/ML sector.
- Extract and analyze job title frequency, required skills, locations, and demand metrics.
- Generate a comprehensive report summarizing AI/ML job market trends in MENA.

## 🛠️ Key Features

- 🌐 **Web scraping** from job platforms such as LinkedIn, Bayt, Wuzzuf, and Glassdoor.
- 📊 **Trend analysis** on job titles, skill requirements, and geographical distribution.
- 📌 **Ranking of top AI/ML roles** based on frequency, location spread, and (if available) salary data.
- 📝 **Automated report generation** in Markdown or PDF format.
- 📉 Optional CLI or dashboard interface for previewing job trends.

## 🧩 System Architecture

The system is composed of the following specialized agents:

### 1. Web Search Agent
- Collects raw job posting data from selected online platforms.

### 2. Data Extraction Agent
- Parses postings to extract structured data: job title, company, skills, location.

### 3. Trend Analysis Agent
- Analyzes extracted data to identify in-demand roles and trending skills.

### 4. Report Writer Agent
- Compiles a final report including:
  - ✅ Top 10 AI/ML roles
  - 🧠 Key skill requirements
  - 🌍 Country-wise job distribution
  - 📈 Observed hiring trends or shifts

## 📂 Deliverables

- ✅ **Codebase** for the full multi-agent system.
- 📄 **Report**: `Top AI/ML Jobs in MENA – May 2025`.
- 🖥️ *(Optional)*: Dashboard or CLI for pre-report insights.

## 🚀 Getting Started

### Prerequisites

- Python 3.9+
- CrewAI or similar multi-agent framework
- Selenium or BeautifulSoup (for scraping)
- Pandas, Matplotlib/Seaborn (for analysis and visualization)

### Installation

```bash
git clone https://github.com/your-repo/ai-ml-job-market-mena.git
cd ai-ml-job-market-mena
pip install -r requirements.txt
```

### Running the System

```bash
python main.py
```

Optional: Use CLI flags or config files to specify platforms, date ranges, etc.

## 📊 Sample Output

The final report includes:

- 🔟 **Top 10 AI/ML Job Roles**
- 🛠️ **Key Skills Required**
- 🌐 **Location Distribution (Country-wise)**
- 🔄 **Trends & Shifts Over Time**

## 🧪 Testing

Unit and integration tests are included. Run with:

```bash
pytest
```

## 👨‍💻 Contributing

We welcome contributions! Please fork the repository and submit a pull request with clear descriptions of changes.

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
