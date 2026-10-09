# Hi, I'm Bereket 👋

**EECS undergraduate at [GIST](https://www.gist.ac.kr/en/) · Undergraduate Research Intern at the GIST Data Science Lab (advisor: Prof. Sundong Kim)**

I research **test-time adaptation** and **self-correcting reasoning** in AI models, using the [ARC-AGI](https://arcprize.org/) benchmark as my testbed. I also build and ship full-stack AI products.

🔍 Looking for an **AI/ML internship** for winter 2026–27.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
<br>
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## 🔬 Research

- **[Test-time training for Tiny Recursive Models on ARC-AGI-2](https://github.com/Berekety1/trm-test-time-training)** · [📄 poster](https://github.com/Berekety1/trm-test-time-training/blob/main/docs/poster.pdf)<br>
  I trained a TRM checkpoint with the ARC-AGI-2 evaluation tasks held out, then compared full fine-tuning and LoRA for adapting it to tasks it had never seen. LoRA underfits, with a loss about 70× higher. Full fine-tuning reaches **4.07% pass@2** on the 120 held-out tasks; the original TRM scores 7.80%, but it saw these tasks during pre-training. Presented at the 10th GIST AX-Challenge (2026).

- **Iterative self-correction in language models** (undergraduate thesis, in progress)<br>
  A confidence ("doubt") head that predicts whether an LLM's answer is correct and decides when to revise it, with revision strength scaled to the model's uncertainty.

## 🛠️ Projects

| Project | What it is | Highlights |
|---|---|---|
| [**Composed image retrieval**](https://github.com/Berekety1/CLIP_FINE_TUNED_ON_FASHION_IQ) | Find a garment from a photo plus a text edit ("make it sleeveless") | LoRA-tuned CLIP, cross-attention fusion, FAISS · **Recall@10 25.8%** |
| [**Tic-tac-toe RL**](https://github.com/Berekety1/tic-tac-toe-rl) | Value iteration vs. self-play Q-learning | Q-learning matches the optimal policy in **all 4,520 positions** |
| [**HabeshaSphere**](https://habeshasphere.com) | Everyday web tools for Ethiopian users | Exchange rates, tax calculator, Ethiopian calendar · **~100–200 monthly users** |
| [**GPA Calculator**](https://github.com/Berekety1/GPA-Calculator-V2) | Semester and cumulative GPA web app | React · [**live demo**](https://berekety1.github.io/GPA-Calculator-V2/) |
| [**Password Manager**](https://github.com/Berekety1/Password-Manager) | Encrypted command-line password vault | scrypt key derivation, authenticated encryption, tests |
| [**Amharic TTS**](https://github.com/Berekety1/Amharic_AI) | Amharic text-to-speech web app | React frontend for an n8n speech pipeline |

## 📫 Contact

[bereketyimolal8991@gmail.com](mailto:bereketyimolal8991@gmail.com) · [habeshasphere.com](https://habeshasphere.com) · Gwangju, South Korea

Languages: Amharic (native) · English (fluent) · Korean (elementary)
