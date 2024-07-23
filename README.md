## Features

- **User-Friendly Interface**: Built with Streamlit, providing an intuitive and interactive interface for doctors.
- **AI-Powered Diagnosis**: Utilizes a Medical Diagnostician agent to analyze symptoms and medical history to offer a preliminary diagnosis.
- **Treatment Recommendations**: Includes a Treatment Advisor agent that generates detailed treatment plans tailored to individual patient needs.
- **Document Generation**: Automatically creates downloadable DOCX documents containing diagnosis and treatment recommendations.

## Technologies Used

- **Streamlit**: For building the web application interface.
- **LangChain**: To integrate OpenAI's GPT-3.5-turbo-16k model.
- **CrewAI**: For creating and managing AI agents and tasks.
- **OpenAI GPT-3.5-turbo-16k**: The primary language model for generating diagnoses and treatment plans.
- **SerperDevTool & ScrapeWebsiteTool**: Tools for searching and scraping medical information.
- **Python-docx**: For generating DOCX documents with diagnosis and treatment details.
