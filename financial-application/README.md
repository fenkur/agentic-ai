# Agentic AI Financial Assistant

A multi-agent AI system that combines web search capabilities with financial data analysis to provide comprehensive stock market insights and recommendations.

## Overview

This project demonstrates the power of agentic AI by coordinating specialized agents to gather, analyze, and present financial information. The system uses the Phidata framework with Groq's LLaMA 3.3 model to orchestrate multiple AI agents that work together to answer complex financial queries.

## Features

- **Multi-Agent Architecture**: Coordinates specialized agents for different tasks
- **Web Search Integration**: Real-time web search capabilities using DuckDuckGo
- **Financial Data Analysis**: Access to stock prices, analyst recommendations, fundamentals, and company news
- **Intelligent Orchestration**: Automatically delegates tasks to the appropriate agent
- **Structured Output**: Presents data in formatted tables with source citations

## Architecture

The system consists of three main components:

### 1. Web Search Agent
- Searches the web for general information
- Always includes sources in responses
- Uses DuckDuckGo for web queries

### 2. Financial Agent
- Retrieves stock market data using YFinance
- Provides analyst recommendations
- Fetches company fundamentals and news
- Formats data in tables for easy reading

### 3. Multi-Agent Coordinator
- Orchestrates collaboration between specialized agents
- Delegates tasks based on query requirements
- Combines insights from multiple sources

## Example Output

![Agent Response Example](https://github.com/fenkur/agentic-ai/blob/main/financial-application/financial_application.png)

## Technologies Used

- **Phidata**: Agent framework for building multi-agent systems
- **Groq**: LLM inference provider (LLaMA 3.3 70B Versatile)
- **YFinance**: Financial data retrieval
- **DuckDuckGo**: Web search functionality
- **Python**: Core programming language

## Acknowledgments

- Built with [Phidata](https://www.phidata.com/)
- Powered by [Groq](https://groq.com/)
- Financial data from [Yahoo Finance](https://finance.yahoo.com/)

---

**Note**: This is a demonstration project for learning purposes. Always consult with financial professionals before making investment decisions.
