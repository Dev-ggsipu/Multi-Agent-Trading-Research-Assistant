# Multi-Agent Trading Research Assistant

## Overview

Multi-Agent Trading Research Assistant is an agentic AI workflow built using the OpenAI Agents SDK.

The system uses specialized AI agents that collaborate to perform stock research and generate structured trading assessments. Instead of relying on a single model response, the workflow divides responsibilities between dedicated agents to improve information gathering and decision making.

---

## Features

* Multi-agent architecture
* Stock research using web search
* Structured outputs with Pydantic models
* Automated trading analysis
* Sequential agent collaboration
* OpenAI Agents SDK integration

---

## Agent Workflow

### Research Agent

Responsible for:

* Gathering information about a company or stock
* Searching recent developments
* Producing a structured research report

### Trade Decision Agent

Responsible for:

* Analyzing the research output
* Evaluating opportunities and risks
* Generating a final trading assessment

---

## Workflow

1. User submits a stock query.
2. Research Agent collects relevant information.
3. Research Agent generates a structured report.
4. Trade Decision Agent analyzes the report.
5. Final trading recommendation is produced.

---

## Tech Stack

* Python
* OpenAI Agents SDK
* GPT-5
* Pydantic
* AsyncIO

---

## Screenshots

### Agent Workflow

![Workflow](screenshots/workflow.png)

### Example Output

![Output](screenshots/output_1.png)

### Additional Example

![Output](screenshots/output_2.png)

---

## Running Locally

Clone the repository:

```bash
git clone <repo-url>
cd multi-agent-trading-research-assistant
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Configure environment variables:

```bash
OPENAI_API_KEY=your_key_here
```

Run the notebook inside Jupyter or Google Colab.

---

## Future Improvements

* Multi-agent debate workflows
* Portfolio optimization agent
* Risk analysis agent
* Backtesting support
* Custom user-defined agent configurations

---

## Disclaimer

This project is intended for educational and research purposes only and does not constitute financial advice.
