# FAQ Bot using IBM Watsonx.ai (Simulated Project)

This project simulates an AI-powered FAQ bot using prompt engineering and IBM Watsonx.ai Foundation Model logic.

Due to credit card restrictions, direct Watsonx API access was not used — but the prompts, flow, and design follow the IBM Watsonx.ai approach as per SmartBridge internship project requirements.

## 📌 Project Overview

An intelligent chatbot that responds to customer questions based on a set of company FAQs using generative AI.

## 🔧 Tools & Technologies

- IBM Watsonx.ai (Prompt Engineering)
- Python (optional for local logic)
- GitHub (project repo)
- Markdown (for documentation)

## 💬 Prompt Engineering

The following prompt simulates what would be passed to a Watsonx Foundation Model like `flan-t5-xl`:

```
You are a helpful assistant. Here is a list of FAQs:

Q: What are your business hours?  
A: Our business hours are Monday–Friday, 9 AM to 6 PM.

Q: How can I contact support?  
A: You can contact support via email at support@example.com.

Q: Where are you located?  
A: We are located in Hyderabad, India.

Now answer the following question:  
Q: How can I reach support?
```

**Expected Output:**
```
You can reach support via email at support@example.com.
```


## 📸 Screenshots

![Prompt and Response Output](faq-bot-watsonx/assets/screenshots/project-summary.png)

- Prompt input (simulated)
- Sample outputs
- Mock chatbot UI

(See assets/screenshots/ folder)

## 📁 Folder Structure

```
faq-bot-watsonx/
├── README.md
├── prompts.txt
├── notebook.ipynb
├── assets/
│   └── screenshots/
└── project-summary.pdf 
```


## 📧 Author

**Name:** M Kiran Kumar 

**Email:** mennikiran@gmail.com

**Internship:** Generative AI with IBM Cloud (SmartBridge)
