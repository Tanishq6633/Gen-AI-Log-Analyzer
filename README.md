GenAI Log Analyzer: AI-Powered Incident Debugging Tool
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
Overview
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

GenAI Log Analyzer leverages Generative AI to accelerate production incident resolution by analyzing raw log files, identifying root causes, and recommending remediation strategies. It is designed to integrate seamlessly into IT support workflows, enhancing operational efficiency, accuracy, and system resilience.

Business Problem
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

Incident management in IT operations is often time-consuming and error-prone, resulting in:

High operational costs

Slow mean time to resolve (MTTR)

Increased downtime and reduced service reliability

Solution
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

GenAI Log Analyzer addresses these challenges by:

Automating log analytics using Generative AI and NLP to interpret complex logs

Integrating with ITSM platforms like ServiceNow to augment existing workflows

Providing actionable insights and recommendations for rapid incident resolution

Key Features & Impact
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

Rapid Root Cause Analysis: AI-driven interpretation of raw log files

Seamless Integration: Supports popular IT operations platforms

Operational Efficiency: Reduces incident resolution costs by ~95% and troubleshooting time by ~90%

Scalable & Extensible: Built on AWS Bedrock and SageMaker for cloud-scale operations

User-Friendly Interface: Streamlit-based UI for interactive log exploration

Technology Stack
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

Cloud: AWS Bedrock, AWS SageMaker, AWS Cloud9

Programming: Python 3+

Libraries: boto3, LangChain, Streamlit

Installation & Execution

Clone the repository:

git clone https://github.com/Tanishq6633/Gen-AI-Log-Analyzer


Navigate to project directory:
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------


cd GenAI_LogAnalyzer


Create and activate virtual environment:

python -m venv venv
source venv/bin/activate


Install dependencies:
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

pip install -r requirements.txt


Configure AWS prerequisites (one-time setup):

python OneTimeExecution.py


Launch the Streamlit interface:

streamlit run streamlitUI.py

Outcome
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

This tool demonstrates best-in-class AI integration for IT operations, enabling organizations to:

Automate log analysis and root cause detection

Reduce operational costs and MTTR significantly

Improve system reliability and incident management workflows
