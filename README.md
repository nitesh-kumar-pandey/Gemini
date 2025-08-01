# 🧠 Gemini ChatBot (Image + Text Input)

This is a simple yet powerful chatbot application built using **Google's Gemini 1.5 Flash model** integrated with **Streamlit** for the user interface.<br> It is designed to handle both **natural language text input** and **image input**, allowing users to interact in a more dynamic and visual way.<br> By combining these two input types, the chatbot can generate rich, intelligent, and context-aware responses, making it suitable for a wide range of use cases such as object recognition, creative storytelling, and informative Q&A.

---

## 📦 Requirements

Install the required libraries using:

```bash
pip install streamlit python-dotenv google-generativeai pillow
```


## 🚀 How to Run
To run the chatbot locally:

```bash
streamlit run app.py
```


## 🧠 How It Works
1. Load your API key securely with dotenv.
2. Use streamlit to build the UI with a text input and image uploader.
3. On submission, pass the text and image to the Gemini model.
4. Display the model's response below the form.

## 🎯 Example Use Cases

### Text + Image  
•&emsp;**Prompt**: "Describe what's happening in this image."  
•&emsp;**Image**: Upload a photo of a person cooking.  
•&emsp;**Response**: The chatbot will describe the scene, like "A person is cooking vegetables in a modern kitchen."

### Text Only  
•&emsp;**Prompt**: "Tell me a bedtime story about a robot and a cat."  
•&emsp;**Image**: Leave blank.  
•&emsp;**Response**: A short, creative bedtime story is generated.

### Image Only  
•&emsp;**Prompt**: Leave blank.  
•&emsp;**Image**: Upload an image of a flower.  
•&emsp;**Response**: The chatbot may respond with something like "This appears to be a sunflower, commonly found in summer gardens."


## 📝 Notes
•&emsp;The chatbot uses the gemini-1.5-flash model, which is optimized for both performance and cost.<br>
•&emsp;Works best when both image and prompt are provided.<br>
•&emsp;Make sure your image is under the supported formats: .jpg, .jpeg, .png.<br>
