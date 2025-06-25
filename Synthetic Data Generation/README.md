# IBM watsonx.ai - Synthetic Data Hands-On Lab


This repository provides a **complete hands-on lab** for exploring synthetic data generation with [IBM watsonx.ai](https://www.ibm.com/products/watsonx-ai). It is intended for technical sellers, data scientists, or developers looking to prototype AI/ML workflows using realistic but privacy-safe data.

> 📂 All required materials – including the lab guide, sample data, and this README – are available in this GitHub repository.

---

## 🎯 Why Synthetic Data?

Modern AI systems need large volumes of **high-quality and privacy-compliant data** to function effectively. But in real-life:
- Real data is **costly**, **time-consuming**, and **legally sensitive** to obtain.
- GDPR and similar privacy laws impose **strict limitations** on usage.
- Accessing production data often takes **4–6 weeks or more**, especially in regulated industries.

> According to *Forbes* and *Gartner*, by 2024 over **60% of data used in AI/ML** will be synthetically generated.

---

## 💡 Solution: IBM watsonx.ai

With watsonx.ai you can:

✅ **Define a synthetic schema from scratch**,  
✅ **Mimic real-world datasets** (e.g., `titanic.csv`) to generate larger versions,  
✅ **Evaluate** the realism and privacy of your synthetic data with metrics such as:
- **Fidelity Score**
- **Proximity**
- **Data Distinguishability**
- **Leakage Score**

---

## 📁 Repository Structure

```plaintext
Synthetic Data Generation/
├── IBM_watsonx.ai_Synthetic_Data_Lab_Guide.pdf     # Step-by-step hands-on instructions       
├── Synthetic_Data_README.md                        # This README file
└── titanic.CSV                                     # Sample dataset for mimic mode

```

Welcome to the **IBM watsonx.ai Synthetic Data Lab**! This hands-on lab introduces technical users to the synthetic data generation capabilities of [watsonx.ai](https://www.ibm.com/products/watsonx-ai). You'll learn how to create realistic, privacy-compliant datasets either from scratch or by mimicking existing data schemas, enabling safe experimentation, model training, and product demos.

---

## 🧠 About watsonx.ai

`watsonx.ai` is part of the IBM watsonx platform, which also includes:

- **watsonx.data** – a fit-for-purpose data store
- **watsonx.governance** – a toolkit for responsible AI

In this lab, you'll use the **watsonx.ai studio** to generate synthetic tabular data for various AI use cases.

---

## 📘 Lab Objectives

This lab teaches you how to:

1. **Create synthetic data from a custom schema**
2. **Generate synthetic data by mimicking a real dataset**
3. **Validate and visualize synthetic data**
4. **Evaluate quality with statistical metrics** (e.g. fidelity, leakage, proximity)

---

## 🛠️ Prerequisites

- IBM Cloud account with access to watsonx.ai or IBM TechZone environment
- (Optional) Sample CSV file (`titanic.csv`) for data mimic use case

> For access issues, IBMers can post in `#data-ai-demo-feedback` Slack, and partners can contact support via [Partner Plus](https://www.ibm.com/partnerplus/support).

---

## 🚀 Getting Started

1. Create a **Sandbox Project** in watsonx.ai
2. Navigate to **Assets > New Asset > Generate synthetic tabular data**
3. Choose between:
   - **Custom Schema** – define data columns, types, and distributions
   - **Mimic Existing Data** – upload a real dataset to base synthetic generation on

---

## ✍️ Lab Sections

### 1. Generate Synthetic Data from Custom Schema

You will define columns like `Last_Name`, `Age`, and `Salary`, and configure:
- Distribution types (e.g., `categorical`, `normal`)
- Probability values
- Correlation between columns (e.g., Age ↔ Salary)

Output: `Name_Age_Salary.xlsx`

### 2. Generate Synthetic Data by Mimicking Existing Dataset

Upload a seed file (e.g., `titanic.csv`) and watsonx.ai will:
- Learn distributions and relationships
- Produce a larger dataset (e.g., 1,000+ rows)

Output: `mimic-output.csv`

You can also enable **evaluation metrics** like:
- **Fidelity Score**
- **Data Distinguishability**
- **Leakage Score**
- **Proximity Score**

---

## 📊 Visualization & Evaluation

- Visualize data using built-in charts (e.g., Age vs. Salary)
- Profile the data to compare original vs. synthetic distributions
- Tweak correlations (e.g., set Age-Salary correlation to `0.8` for realism)

---

## 📎 Outputs

You will produce assets like:

- ✅ Custom schema synthetic file: `Name_Age_Salary.xlsx`
- ✅ Mimicked dataset: `mimic-output.csv`
- ✅ Evaluated dataset: `mimic-output-eval.csv`
- ✅ Project assets: synthetic data flows and visualizations

---

## 👥 Contacts
- Stefan Vogel – [stefan.vogel@ch.ibm.com](mailto:stefan.vogel@ch.ibm.com)
- Naim Zierau – [Naim.Zierau@ibm.com](mailto:Naim.Zierau@ibm.com)
- Husniye Sekeroglu – [Huesniye.Sekeroglu@ibm.com](mailto:Huesniye.Sekeroglu@ibm.com)  