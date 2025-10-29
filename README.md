# 🩺 Medical Self-Help App using GPT (Multimodal)

A smart medical assistance application powered by **Multimodal AI** (Image + Text) to help users perform quick health assessments from symptoms and medical images.  
This tool is designed for **educational and preliminary guidance only** and should not replace professional medical diagnosis.

---

## 🚀 Features

✅ Upload medical images (skin issues, X-ray, etc.) for AI analysis  
✅ Chat with the model about symptoms and health concerns  
✅ AI-generated medical suggestions and care tips  
✅ Multimodal: Combines **visual + textual** medical understanding  
✅ Privacy-focused: Medical data stays on user device (depending on deployment)  
✅ Simple UI for real-world usage (Streamlit / FastAPI)

---

## 🧠 Technology Stack

| Component | Tech Used |
|----------|-----------|
| AI Model | GPT-Vision / GPT-5 (Multimodal) |
| Frontend UI | Streamlit |
| Backend Logic | Python |
| Dependency Management | requirements.txt |
| Environment | Conda / Venv |
| Version Control | Git + GitHub |

---

## 📂 Project Structure

Medical-Self-Help-App-using-GPT/
│
├── app.py # Main application
├── requirements.txt # Libraries required
├── assets/ # Sample medical images/icons
└── README.md


---

## ⚙️ Installation

### 1️⃣ Clone the repository

git clone https://github.com/Vimalkanth7/-Medical-Self-Help-App-using-GPT.git
cd Medical-Self-Help-App-using-GPT

### 2️⃣ Create a virtual environment
python -m venv medical_env
medical_env\Scripts\activate  # Windows

3️⃣ Install requirements
pip install -r requirements.txt

4️⃣ Add OpenAI API Key
Create a .env file:
OPENAI_API_KEY=your_api_key_here

▶️ Run Application
streamlit run app.py
