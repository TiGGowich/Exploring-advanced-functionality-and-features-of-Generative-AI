# Visual Question Answering with Multimodal Generative AI: Evaluating ViLT, BLIP-2, and GIT

This repository presents a project completed for the **Generative AI and AI Applications** from my MSc Business Analytics program at Warwick Business School. The project explores the capabilities and trade-offs of **multimodal transformer models** for **Visual Question Answering (VQA)** tasks.

---

## 📂 Repository Contents

- [**`vqa_model_comparison_colab.ipynb`**](./vqa_model_comparison_colab.ipynb): Google Colab notebook with all code for model loading, evaluation, and result aggregation.

---

## 🎯 Project Objective

This project investigates the **functionality and comparative performance** of three advanced **vision-language transformer models**:

- **ViLT (Vision-and-Language Transformer)**
- **BLIP-2 (Bootstrapping Language-Image Pretraining)**
- **GIT (Generative Image-to-Text)**

These models were evaluated in their ability to interpret and respond to image-based questions across a spectrum of cognitive tasks, relevant to real-world applications in accessibility, autonomous systems, education, and content moderation.

---

## 🧠 Methodology

### 📷 Dataset Design

- A **custom benchmark** of 9 diverse images was created and categorized by **three levels of visual complexity**: easy, medium, and hard.
- Each image was paired with **five targeted questions**, covering:
  - Object Presence
  - Object Counting
  - Attribute Recognition
  - Scene Understanding
  - Commonsense Reasoning

### 🧪 Evaluation Process

- Each model's responses were assessed manually by two independent raters.
- Scoring was done on a **1–5 scale** across:
  - **Correctness**
  - **Relevance**
  - **Completeness**
- Scores were averaged and analyzed across models, task types, and complexity tiers.

---

## ✅ Results Summary

| Model   | Key Strengths                                               | Key Limitations                                         |
|---------|-------------------------------------------------------------|----------------------------------------------------------|
| **ViLT**   | Highest overall performance; strong across all complexity levels | N/A – performed consistently well                        |
| **BLIP-2** | Excellent at visual detail and object recognition         | Weaker at commonsense and reasoning-heavy questions       |
| **GIT**    | N/A                                                       | Underperformed across most tasks and reasoning scenarios  |

- **ViLT emerged as the top performer**, offering both high accuracy and consistency, benefiting from its tightly coupled transformer architecture.
- **BLIP-2** was highly effective in detail-oriented visual tasks but struggled in abstract and reasoning-based prompts.
- **GIT** lagged behind significantly and was less suited for tasks requiring multi-step interpretation.

Despite some initial exploration, **fine-tuning** was not adopted in final evaluations due to negligible gains and increased computational cost.

---

## 💡 Key Takeaways

- **Model architecture matters**: tightly integrated architectures like ViLT outperform more loosely coupled generative approaches in VQA.
- The project’s custom benchmark provides a **reproducible and scalable** framework for future VQA model evaluation.
- Insights gained are valuable for both **academic benchmarking** and **real-world AI deployment**, especially in scenarios requiring **interpretability and robustness**.

---

## 📎 How to Use This Repository

- Open the `.ipynb` notebook in Google Colab or Jupyter to reproduce the results or experiment with new models or prompts.

---

## 📬 Contact

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/benjamin-sachse-consultant/) or reach out for collaboration or discussion on multimodal AI applications.
