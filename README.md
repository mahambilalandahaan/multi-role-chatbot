# 🤖 Multi-Role Chatbot (Gradio + OpenRouter)

A conversational AI chatbot that can act as a **teacher**, **friend**, **advisor**, or **mentor** — styled in different tones like **formal**, **friendly**, or **poetic**.

---

## 🚀 How to Deploy

1. Create a new **Hugging Face Space**
   - Choose **Gradio** as SDK.
2. Upload these three files:
   - `app.py`
   - `requirements.txt`
   - `README.md`
3. Go to **Settings → Repository secrets**
   - Add a secret:
     - **Name:** `OPENROUTER_API_KEY`
     - **Value:** your API key from [https://openrouter.ai](https://openrouter.ai)
4. Click **Restart Space**

Your chatbot will appear live at  
👉 `https://huggingface.co/spaces/<your-username>/<space-name>`

---

## ✨ Features
- Role selection (Teacher / Friend / Advisor / Mentor)
- Style control (Formal / Friendly / Poetic / Sarcastic)
- Adjustable reply length (Short / Detailed)
- Simple Gradio interface — press **Enter** to chat!
