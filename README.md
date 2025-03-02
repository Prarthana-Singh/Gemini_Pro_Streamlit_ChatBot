# Gemini Pro Streamlit ChatBot

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)  ![Google AI](https://img.shields.io/badge/Google%20Gemini-4285F4?logo=google&logoColor=white)  ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)  

## 🌟 Overview  
This is an interactive **AI Chatbot** built using **Streamlit** and powered by **Google's Gemini Pro API**. It allows users to have conversations with an AI model and generate responses in real time.  

---
## ➡️ Live Demo
🖇️ **[Click here to try the chatbot](https://huggingface.co/spaces/1Prarthana/Gemini_Pro_Streamlit_ChatBot)**


## 🚀 Features  
✔️ Chat with **Google Gemini Pro**  
✔️ **Voice Support** using `pyttsx3` (Optional)  
✔️ **Fast & Interactive UI** using Streamlit  
✔️ Secure API Key Handling using **`.env` file**  

## 🛠 Tech Stack  
- **Python 3.10+**  
- **Streamlit** (for UI)  
- **Google Generative AI** (`google-generativeai`)  
- **Pyttsx3** (for text-to-speech)  
- **dotenv** (for API security)  

---
## ⚙ Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- pip (Python package manager)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Gemini_Pro_Streamlit_ChatBot.git
   cd Gemini_Pro_Streamlit_ChatBot
   ```
2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Add your Gemini Pro API key in a `.env` file:
   ```
   GEMINI_API_KEY=your_api_key_here
   ```

---
## Usage

Run the chatbot using the command:
```bash
streamlit run app.py
```

This will open a browser window with the chatbot interface.

---
## 🚀 Deployment

### Deploy on Streamlit Cloud

1. Push your project to a GitHub repository.
2. Go to [Streamlit Cloud](https://share.streamlit.io/), sign in, and create a new app.
3. Select your repository and branch, then specify `app.py` as the main file.
4. Click **Deploy**.

### Deploy on Hugging Face Spaces

1. Create an account on [Hugging Face](https://huggingface.co/).
2. Go to [Hugging Face Spaces](https://huggingface.co/spaces) and click **Create new Space**.
3. Choose **Streamlit** as the **SDK** and set a repository name.
4. Push your project to Hugging Face:
   ```bash
   git add .
   git commit -m "Deploy chatbot to Hugging Face Spaces"
   git push origin main
   ```
5. Your chatbot will be automatically deployed and accessible via a public link.

### Deploy on Heroku (Alternative)

1. Install Heroku CLI and log in:
   ```bash
   heroku login
   ```
2. Create a Heroku app:
   ```bash
   heroku create gemini-chatbot
   ```
3. Deploy the app:
   ```bash
   git add .
   git commit -m "Deploy chatbot"
   git push heroku main
   ```

---

### 📸 Demo Screenshot
![Screenshot 2025-03-02 231326](https://github.com/user-attachments/assets/3537f063-84ce-4a87-b745-edb3256d84b2)
![Screenshot 2025-03-02 231601](https://github.com/user-attachments/assets/c96b9ceb-b4da-492d-817b-1c0e72b5de26)
![Screenshot 2025-03-02 231655](https://github.com/user-attachments/assets/6dca6d18-f55e-4ed9-9758-ceb0942aba03)
![Screenshot 2025-03-02 231712](https://github.com/user-attachments/assets/fbe9c105-a040-4f09-a1c3-618e2ab7b2be)

---
### 🔥 How It Works
1. The user inputs a query.
2. The chatbot sends the query to Google Gemini Pro.
3. The AI generates a response and displays it in the UI.
4. (Optional) The response is read out loud using pyttsx3.

---

### 🛡 Security Best Practices
🔹 Never expose your API key in public repositories.
🔹 Use environment variables or Secrets when deploying to Hugging Face Spaces or Render.

---
## Contributing

Feel free to fork the repository and submit pull requests for improvements.

---
## License

This project is licensed under the MIT License.


## 🚀 **Connect With Me**  
📂 **GitHub**: ([GitHub_Link](https://github.com/Prarthana-Singh))  
💼 **LinkedIn**: ([LinkedIn_Link](https://www.linkedin.com/in/prarthanasingh))  
📺 **YouTube**: ([YouTube_Link](https://youtube.com/@deepcodeai3530?si=dwcglf0h-ONx-wGd))  

🔔 **Star this repo** ⭐ to stay updated!  

