# Adversarial AI Research & Security Audits 🐳

<img width="580" height="320" alt="image" src="https://github.com/user-attachments/assets/45e975a6-c64f-44c2-be47-6375c7c02914" />

## 🎯 Overview
This repository serves as a technical knowledge base and security audit log for my research into **Adversarial AI** and **LLM Security**. Following the **Google Secure AI Framework (SAIF)** and **HackTheBox (HTB) AI Red Teaming** pathways, I focus on analyzing the security posture of machine learning models and their integration points.

Rather than just building models, I treat AI infrastructure as a new attack surface. This repository documents my ability to perform **Security Code Reviews** on model training scripts and deployment pipelines to identify vulnerabilities before they reach production.

---

## 🔍 Core Research Areas
Based on my work with HTB Sherlocks and adversarial research, this repository covers:

* **Prompt Injection Analysis:** Auditing LLM wrappers to identify bypasses in system prompts and guardrails.
* **Data Poisoning & Integrity:** Analyzing training scripts for vulnerabilities that allow adversarial perturbations to be injected into the latent space.
* **Model Inversion & Extraction:** Investigating the risks of sensitive data leakage through model responses.
* **Adversarial Robustness:** Testing how minor input manipulations can lead to catastrophic misclassification in computer vision and NLP models.

---

## 🛠️ Methodology: The Audit Approach
In this repository, you will find "Annotated Security Reviews" of AI-related code. My process involves:

1.  **Vulnerability Identification:** Reading through model training and inference scripts to find weak logic or lack of input sanitization.
2.  **Mapping to SAIF:** Aligning findings with the Google Secure AI Framework to ensure robust, enterprise-grade defenses.
3.  **Adversarial Simulation:** Understanding the "Red Team" scripts used to exploit these models and documenting the resulting telemetry.

---

## 📁 Repository Structure (In Progress as of now)
* `/Prompt-Injection`: Analysis of vulnerable LLM integration points.
* `/Adversarial-ML`: Security audits of Python-based training scripts (HTB Sherlock research).
* `/SAIF-Implementation`: Documentation on applying Google's Secure AI Framework to real-world pipelines.

---

## 📈 Goals
* **Bridge the Gap:** Moving traditional SOC/Blue Team logic into the realm of Artificial Intelligence.
* **Documentation-as-Code:** Keeping a live record of emerging AI threats and mitigation strategies.

> **Note:** The code snippets provided here are for educational and security research purposes, derived from professional labs such as HackTheBox.
