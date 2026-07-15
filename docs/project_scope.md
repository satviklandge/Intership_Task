# MetricMind: Agentic Semantic BI Engine

## Project Scope Document

### 1. Project Overview

MetricMind is an AI-powered Conversational Business Intelligence system designed to provide accurate, consistent, and governed business insights through natural language questions.

The system allows business users to ask analytical questions in simple English, such as:

"Why did European margins drop last quarter?"

Instead of allowing the AI model to directly generate uncontrolled SQL queries on raw database tables, MetricMind uses a Semantic Layer containing predefined business metrics and dimensions.

The AI agent interprets the user's question, identifies the required business metrics and filters, communicates with the Semantic Layer, retrieves structured analytical data, and generates a clear business explanation with suitable visualizations.


### 2. Problem Statement

Traditional Text-to-SQL systems allow Large Language Models to generate SQL queries directly against databases.

This approach may result in:

- Incorrect table joins
- SQL hallucinations
- Inconsistent metric calculations
- Incorrect business logic
- Different results for the same analytical question
- Expensive and uncontrolled database queries

For example, different departments may calculate "Margin" differently, resulting in inconsistent reports.

MetricMind solves this problem by introducing a governed Semantic Layer where official business metrics are centrally defined.


### 3. Project Aim

The aim of MetricMind is to develop an AI-powered Conversational BI system that enables users to query business data using natural language while maintaining metric consistency, data governance, and analytical accuracy.

The system aims to transform complex business data into trusted and understandable insights.


### 4. Project Objectives

The main objectives of the project are:

1. Build a structured business analytics database.

2. Design a data model for sales and financial analytics.

3. Define official business metrics such as Revenue, Total Cost, Profit, and Margin.

4. Implement a Semantic Layer to manage business metrics and dimensions.

5. Develop an AI agent capable of understanding natural language business questions.

6. Convert user questions into controlled Semantic API requests.

7. Prevent the AI from directly accessing raw database tables.

8. Perform multi-step analytical reasoning to identify the root causes of business problems.

9. Generate clear business explanations based on structured analytical data.

10. Dynamically display suitable charts based on the analytical result.

11. Maintain transparency by displaying metric definitions and Semantic API requests.

12. Ensure consistent results for repeated business questions.


### 5. Proposed System Workflow

The MetricMind system follows the workflow below:

User Question
        ↓
Conversational BI Interface
        ↓
AI Agent / LLM
        ↓
Question and Intent Analysis
        ↓
Metric and Filter Identification
        ↓
Semantic Layer
        ↓
Business Analytics Database
        ↓
Structured JSON Response
        ↓
AI Analytical Reasoning
        ↓
Business Explanation and Visualization


### 6. Project Domain

Domain: Enterprise Analytics and Agentic AI

Business Use Case: Sales and Financial Analytics


### 7. Project Scope

The project will focus on the following analytical areas:

- Revenue Analysis
- Cost Analysis
- Profit Analysis
- Margin Analysis
- Regional Sales Analysis
- Product Performance Analysis
- Quarterly Performance Analysis
- Cost Breakdown Analysis
- Business Trend Analysis
- Root Cause Analysis


### 8. Core Business Metrics

The following governed business metrics will be implemented:

#### Total Revenue

Total Revenue represents the total income generated from sales.

Calculation:

Total Revenue = SUM(Revenue)


#### Total Cost

Total Cost represents the combined business expenses.

Calculation:

Total Cost = Material Cost + Shipping Cost + Operational Cost


#### Profit

Profit represents the financial gain after deducting total costs from revenue.

Calculation:

Profit = Total Revenue - Total Cost


#### Margin Percentage

Margin Percentage represents the percentage of revenue retained as profit.

Calculation:

Margin Percentage = (Profit / Total Revenue) × 100


### 9. Business Dimensions

The system will support the following analytical dimensions:

- Date
- Month
- Quarter
- Year
- Region
- Country
- Product
- Product Category
- Customer Type


### 10. Key System Features

#### Conversational Business Intelligence

Users can ask business questions using natural language.


#### Governed Semantic Metrics

All business metrics are centrally defined to ensure consistent calculations.


#### AI Agent Orchestration

The AI agent interprets user questions and interacts with the Semantic Layer.


#### Multi-Step Root Cause Analysis

The system can perform additional analytical queries to identify the reason behind changes in business performance.


#### Dynamic Data Visualization

The system automatically selects an appropriate chart based on the analytical data.


#### Query Transparency

Users can view the metrics, filters, and Semantic API requests used to generate an answer.


#### Query Governance

The system restricts unsupported metrics and uncontrolled analytical queries.


### 11. Technology Stack

Programming Language:
- Python

Data Processing:
- Pandas
- NumPy

Database:
- PostgreSQL

Semantic Layer:
- Cube

AI and Agent Orchestration:
- LangChain
- Large Language Model (LLM)

User Interface:
- Streamlit

Data Visualization:
- Plotly

Version Control:
- Git
- GitHub


### 12. Project Duration

Total Project Duration: 4 Weeks

Working Days Per Week: 5 Days

Total Working Days: 20 Days


### 13. Expected Final Output

The final output of MetricMind will be a working AI-powered Conversational Business Intelligence application.

The application will allow a user to ask questions such as:

- What is the total revenue?
- Show revenue by region.
- Compare Q2 and Q3 margins.
- Show European sales.
- Which region generated the highest profit?
- Why did European margins drop in Q3?

The system will return:

- Accurate business metrics
- AI-generated analytical explanations
- Structured analytical results
- Interactive charts
- Metric information
- Semantic API request transparency


### 14. Project Success Criteria

The project will be considered successful if:

- Business metrics return consistent results.
- The AI does not directly query raw database tables.
- Natural language questions are correctly interpreted.
- Semantic API requests are generated correctly.
- The system identifies business trends and root causes.
- Charts are dynamically generated based on analytical results.
- Unsupported business questions are handled safely.
- The complete system works through a conversational user interface.


### 15. Conclusion

MetricMind aims to bridge the gap between Generative AI and governed enterprise analytics.

The project replaces uncontrolled Text-to-SQL analytics with a Semantic Layer-driven architecture where business metrics are clearly defined and consistently calculated.

By combining data analytics, semantic modeling, AI orchestration, multi-step reasoning, and interactive visualization, MetricMind provides a trusted and intelligent Conversational BI experience.