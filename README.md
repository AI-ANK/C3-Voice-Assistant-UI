# C3 Voice Assistant: Accessible LLM Apps for Everyone

Welcome to C3 Voice Assistant, a project that brings the power of Large Language Models (LLM) and Retrieval-Augmented Generation (RAG) within reach of everyone, particularly emphasizing accessibility. My goal is to democratize access to advanced AI technologies, ensuring inclusivity for users who may face challenges with traditional text-based interfaces.


## Demo Features
- **Voice Activation**: Just say "C3" to activate the assistant.
- **General Queries**: Ask any question as you would with a standard LLM.
- **Document-Based Responses (RAG)**: Get answers related to specific documents. Current deployment supports queries about Nvidia's FYE 2023 10K report. You can choose to have multiple documents loaded as required.
- **Accessibility Focused**: The design philosophy prioritizes accessibility, catering to a diverse user base with different needs and preferences.
- **Vercel Deployment**: Check out the production version on Vercel.

## Tools and Technologies
- **Frontend**: Custom-built React.js application.
- **LLM Backend**: Python Flask, leveraging LlamaIndex's 'Create Llama' feature.
- **Hosting**: API server on Render.com and frontend on Vercel.

## API Server Details
- The C3 Voice Assistant's backend is a separate, deployable Python Flask application, which interfaces with LLMs to process and respond to user queries. It is deployed using the wonderful and easy to use [create-llama](https://www.npmjs.com/package/create-llama?activeTab=readme) feature by Llamaindex.
- My [API Server](https://github.com/AI-ANK/c3-python-nostream) repo

## Setup and Usage

### Deploying the Frontend to Vercel
1. **Fork or Clone the Repository**:
   Fork or clone the C3 Voice Assistant frontend repository from GitHub.

2. **Set Up Vercel**:
   Create or log in to your [Vercel account](https://vercel.com/).

3. **Deploy to Vercel**:
   - Go to your Vercel dashboard.
   - Click on "New Project" and select the repository.
   - During setup, add the API server URL in the environment variables as specified in `App.js`.

4. **Launch Your Application**:
   Click on "Deploy" to launch your application.

### Setting Up the API Server
Follow the instructions on [Create Llama's npm page](https://www.npmjs.com/package/create-llama?activeTab=readme) to set up and deploy the API server.

Remember to modify the API server URL in `App.js` to point to your deployed backend.


## Feedback and Contributions
Your insights and contributions are welcome. Feel free to raise issues or submit pull requests for enhancements.

## Acknowledgements
Developed by Harshad Suryawanshi. If you find this project helpful, consider giving it a ⭐ on GitHub!

[View the Live Demo]()
