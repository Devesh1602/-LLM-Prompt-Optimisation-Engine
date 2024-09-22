# LLM Prompt Optimization Engine
## Project Description
The LLM Prompt Optimization Engine is an AI-driven system designed to streamline and enhance the use of Language Models (LLMs) across various industries. By automating the generation, evaluation, and testing of prompts, this project significantly reduces the time and expertise required to craft effective prompts manually. The system consists of both frontend and backend components, facilitating the automatic generation of high-quality prompts, test cases for evaluation, and prompt ranking to ensure reliable LLM performance.

### Key Features:
1) Automatic Prompt Generation: Efficiently create optimized prompts, enabling businesses to utilize LLMs for high-quality, relevant content generation.
2) Evaluation Data Generation: Automatically generate diverse test cases to enhance the reliability and performance of LLM applications, saving time in the QA process.
3) Prompt Testing and Ranking: Evaluate and rank prompts to ensure effectiveness, improving chatbot and virtual assistant interactions, and increasing user satisfaction.

An AI-driven prompt generation and evaluation system, designed to optimize the use of Language Models (LLMs) for various industries. This project automates prompt creation, testing, and evaluation, reducing the manual effort required and improving LLM performance.
![LLM Model SS](https://github.com/Devesh1602/LLM-Prompt-Optimisation-Engine/blob/main/LLM%20Model%20SS.png)


### Project Overview
The LLM Prompt Optimization Engine streamlines the use of LLMs by automating the generation, evaluation, and ranking of prompts. It ensures that businesses can quickly create, test, and optimize prompts, reducing manual intervention while increasing efficiency. The project supports automatic evaluation data generation to ensure comprehensive testing and enhanced LLM reliability.

### Backend
The backend, powered by Flask, is responsible for managing API requests related to prompt generation, evaluation, and testing. It contains utility files for prompt processing and evaluation services.
tests/: Contains backend test files for evaluation data generation and prompt testing.
utils/: Includes utility files for handling tasks like text splitting, PDF parsing, and vector storage.
app.py: Flask application file to handle API requests.
config.py: Contains configuration settings.
requirements.txt: Python dependencies required for the backend. Install with pip install -r requirements.txt.

### Frontend
The front end is built with ReactJS and manages the user interface for prompt testing and interactions with the LLM system.
src/: Main source directory for the ReactJS application.
components/: Contains individual React components, including the chatbox component.
app.js, index.js, index.css: Core files for running the front end.
package.json: NPM dependencies for the front end.
