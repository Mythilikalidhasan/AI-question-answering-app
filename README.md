# AI Question Answering App

A Streamlit web app that takes a user's question and returns an AI-generated answer using an open-source LLM through the Hugging Face Inference API.

## What I Did

- Built a simple web interface using Streamlit where users can type in a question
- Connected the app to Hugging Face's Inference API to generate answers using an LLM
- Displayed the AI-generated response back to the user on the same page

## Technologies Used

- Python
- Streamlit
- Hugging Face Hub (InferenceClient)
- Model: openai/gpt-oss-120b

## Workflow

1. User enters a question in the text area
2. On clicking "Ask AI", the question is sent to the Hugging Face Inference API
3. The API returns a response from the LLM
4. The response is displayed on the page under "AI Response"

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/14d41bf5-b9d8-4916-abb1-43065dcebcb4" />

## Future Enhancements

- Add chat history so previous questions and answers are saved during the session
- Allow users to choose between different LLM models
- Add response streaming for a faster, real-time typing effect
- Improve UI with better styling and layout
- Add error handling for API failures or invalid inputs

## Screenshot

<img width="1917" height="802" alt="image" src="https://github.com/user-attachments/assets/e5c1a354-312d-44c2-a560-2725a4572f3e" />


## Author

Mythili K
[GitHub](https://github.com/Mythilikalidhasan) | [LinkedIn](https://www.linkedin.com/in/mythili-k-392843378)
