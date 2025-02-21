# 📧 AI-Powered Email Generator

This is a **Templatized AI Email Generator** built using **Streamlit** and **LangChain**, powered by **Groq Llama-3.3-70B**. It allows users to generate professional and personalized emails based on the provided input parameters.

## 🚀 Features

- **Compose a new email** or **Reply to an email**.
- Customize **tone** (Formal, Professional, Friendly, etc.).
- Choose **email length** (Short, Medium, Long).
- Generate emails based on a **specific purpose**.
- Uses **LangChain + Groq Llama-3.3-70B** for high-quality AI-generated emails.
- **Streamlit-based UI** for easy interaction.

## 📌 Installation

1. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up API keys**:
   - Create a `.env` file in the project directory.
   - Add your **Groq API key** inside the `.env` file:
     ```
     GROQ_API_KEY=your_api_key_here
     ```

## 🏃‍♂️ Running the App

Once everything is set up, start the Streamlit app:

```bash
streamlit run app.py
```

## ![Template](https://github.com/user-attachments/assets/bf43a0f6-378f-48e3-a935-41cfa117fa03)
![Generated_email](https://github.com/user-attachments/assets/9b311e62-32f0-4a2c-b560-81f00bec3f7f)


## 📜 Usage

1. **Select Email Type**: Choose either _Compose New Email_ or _Reply To Email_.
2. **Fill in the fields**:
   - Sender & Receiver name (Optional)
   - Purpose of the email
   - Subject (if composing a new email)
   - Received email content (if replying)
3. **Select Email Tone & Length**.
4. **Click "Generate"**, and the AI will generate an email based on your inputs.

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **LangChain**
- **Groq Llama-3.3-70B**
- **dotenv** (for API key management)

## 📝 License

This project is licensed under the **MIT License**.

---
