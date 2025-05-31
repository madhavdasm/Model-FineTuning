
# 🧠 Mental Health Assistant Chatbot

A fine-tuned chatbot that answers frequently asked questions about mental health in a supportive, empathetic, and informative manner. This assistant is designed to aid users in understanding and addressing their mental well-being concerns through natural conversation.

---

## 📌 About the Project

This Mental Health Assistant was created as part of a fine-tuning project using the [Mental Health FAQ for Chatbot](https://www.kaggle.com/datasets/narendrageek/mental-health-faq-for-chatbot) dataset from Kaggle.

The model has been fine-tuned to handle a wide range of mental health-related queries and respond with care and accuracy. This project aims to support mental well-being and mental health awareness through AI.

---

## 📂 Dataset Used

- **Source**: [NarendraGeek on Kaggle](https://www.kaggle.com/datasets/narendrageek/mental-health-faq-for-chatbot)  
- **Description**: The dataset consists of  frequently asked questions related to mental health, along with accurate and human-friendly answers. Topics include depression, anxiety, therapy, medication, support systems, and more.

---

## ✨ Features

- Fine-tuned LLM specifically for mental health Q&A
- Empathetic and context-aware responses
- Can be embedded into websites, chat platforms, or support tools
- Lightweight and privacy-conscious

---

## 🚀 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/mental-health-assistant.git
cd mental-health-assistant
````

### 2. Create Virtual Environment (Optional)

```bash
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Load the Fine-Tuned Model

Ensure you have the fine-tuned model checkpoint saved locally or on Hugging Face. Update `app.py` or the serving script accordingly.

---

## 💬 Usage

### Run the Chatbot

```bash
python app.py
```

You’ll be able to chat with the assistant via command line or web (depending on implementation).

Example query:

> "Can people with mental illness recover?"

Response:

> "People experience mental illness differently and recovery can vary. Recovery is a process, and people can experience ups and downs. It’s important to be part of the recovery process with your healthcare team. It’s also important that you take responsibility for your recovery.The research shows that people with mental illness can recover. People who receive the care they need and have the support they need can recover. This recovery is possible for anyone, regardless of their age, gender, sexual orientation, ethnicity, socioeconomic status, religion, or background.A recovery plan is a tool to help you track your progress. It can help you stay on track and help you understand what’s expected of you. Your recovery plan should include goals for functioning, social relationships, and recovery. Your recovery plan should also include information about the symptoms you experience, and how they affect your life. You and your healthcare team should review your recovery plan regularly to make sure it’s still relevant and to make changes as you need.The recovery process takes time, and recovery does not happen overnight. There may be setbacks and challenges along the way. It may feel like recovery is slow or that you’re not making progress. This is common. Recovery takes time and patience.
It’s important to know that recovery is possible. It’s possible to recover from a mental illness."

---

## 🧠 Model Training Notes

* **Base Model**: (e.g., `gpt-3.5-turbo`, `LLaMA`, `FLAN-T5`, etc. — specify if applicable)
* **Fine-Tuned On**: QA pairs from the Kaggle dataset
* This notebook is intended to run on GPUs with enough memory for 4-bit quantized training.
* You can customize LoRA hyperparameters and dataset preprocessing as needed.
* Ensure your CSV file contains correctly formatted Instruction and Response columns.
---

## 🙏 Acknowledgments

* [NarendraGeek's Mental Health FAQ Dataset](https://www.kaggle.com/datasets/narendrageek/mental-health-faq-for-chatbot)
* OpenAI / Hugging Face for model support
* All those working toward accessible and empathetic mental health resources

---

## 💡 Future Plans

* Add multilingual support
* Integrate voice-based interaction
* Deploy on web/app with secure logging and anonymized feedback

---

*This assistant is not a replacement for professional help. Always consult a qualified mental health professional for personal issues.*

