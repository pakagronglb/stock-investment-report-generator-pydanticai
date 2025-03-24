# Stock Investment Report Generator 💰

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![OpenAI](https://img.shields.io/badge/OpenAI-API-green.svg)](https://openai.com/)
[![Pydantic](https://img.shields.io/badge/Pydantic-2.0+-orange.svg)](https://pydantic-docs.helpmanual.io/)
[![PydanticAI](https://img.shields.io/badge/PydanticAI-Latest-red.svg)](https://github.com/ahirner/pydantic-ai)
[![Rich](https://img.shields.io/badge/Rich-Terminal-purple.svg)](https://github.com/Textualize/rich)

## Overview ⚙️

An intelligent, AI-powered tool for generating comprehensive stock investment reports. This application leverages OpenAI's models through PydanticAI to provide detailed analysis of stock performance, company fundamentals, and investment recommendations.

## Features ✨

- **Intelligent Input Validation**: Validates user inputs to ensure they contain only valid company ticker symbols
- **Comprehensive Market Analysis**: Analyzes company fundamentals, financial statements, and recent performance
- **Multi-Agent Workflow**: Uses specialized AI agents for different aspects of the analysis process
- **Financial Data Integration**: Retrieves real-time financial data from Yahoo Finance
- **Structured Report Generation**: Creates detailed markdown reports with consistent formatting

## Installation 📦

1. Clone this repository
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Create a `.env` file in the root directory with your OpenAI API key:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```

## Usage 📍

Run the main script:

```
python investment_research_workflow.py
```

Follow the prompts to enter company ticker symbols for analysis. The program will generate three reports in the `reports` directory:
- `stock_analyst_report.md`: Detailed financial and market analysis
- `research_analyst_report.md`: Research findings and industry context
- `investment_report.md`: Final consolidated investment recommendations

## Project Structure 🔧

- `investment_research_workflow.py`: Main application script
- `tools/yahoo_finance_tools.py`: Yahoo Finance API integration tools
- `reports/`: Directory for generated analysis reports
- `requirements.txt`: Project dependencies

## Technologies Used 💻

- **Python**: Core programming language
- **PydanticAI**: Framework for building AI agents with structured outputs
- **OpenAI API**: Powers the intelligent analysis capabilities
- **Rich**: Terminal formatting and user interface
- **Python-dotenv**: Environment variable management

## Credit 🙏🏻

This project is based on the tutorial by [Jie Jenn](https://www.youtube.com/watch?v=wF4dMDICilQ) on YouTube.

## License 📝

MIT - Licence
