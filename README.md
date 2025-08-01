# 🧠 Gemini ChatBot (Image + Text Input)

This is a simple chatbot built using **Google's Gemini 1.5 Flash model** and **Streamlit**. 
It can process both **text input** and **image input**, providing intelligent responses based on the combination of both.

---

## 📦 Requirements

Install the required libraries using:

```bash
pip install streamlit python-dotenv google-generativeai pillow
```
# 🧪 How to Run

To run the chatbot locally:

```bash
streamlit run app.py
```
# 💡 How It Works
1. Load your API key securely with dotenv.

2. Use streamlit to build the UI with a text input and image uploader.

3. On submission, pass the text and image to the Gemini model.

4. Display the model's response below the form.
