# IBM watsonx.ai - Prompt Engineering and Tuning Lab

This hands-on lab is designed for IBM technical sellers and solution engineers.  
You will explore the Prompt Lab, experiment with different prompting techniques, and create a prompt tuning job to customize model behavior for a specific domain.

---

## 🎯 Objectives

- Use watsonx.ai’s Prompt Lab to try zero-shot and few-shot prompting
- Compare responses across different foundation models
- Create and run a prompt tuning job using labeled data
- Deploy and test the tuned model

---

## 🧪 Lab Flow

> ⚠️ **Note:** If you already have an existing IBM Cloud account, you can skip the first four steps in the PDF and proceed directly to Chapter 5.

### 1. Launch Prompt Lab

- Go to the **Prompt Lab** in watsonx.ai
- Start testing prompts with different models like:
  - `flan-t5-xl`
  - `mpt-7b-instruct2`
  - `starcoderbase`

### 2. Zero-shot and Few-shot Prompting

- Try **zero-shot prompts** with no examples
- Use **few-shot prompts** with manually added input-output pairs
- Analyze and compare results directly in the UI

### 3. Start Prompt Tuning

- Click on **Tuning** in the Prompt Lab
- Create a new tuning job
- Upload the provided `.jsonl` training file
  - It contains labeled prompt-response pairs
- Select a model (e.g., `flan-t5-xl`)
- Set tuning parameters:
  - Learning rate
  - Epochs
  - Batch size

### 4. Monitor Job

- Once submitted, track training progress
- View logs and status in the Tuning tab

### 5. Deploy and Test Tuned Model

- After training completes, deploy the tuned model
- Use Prompt Lab to compare the tuned model with the base model using the same prompts

---


## 📝 Notes

- Prompt Tuning works with smaller labeled datasets
- Use the Prompt Lab to compare outputs qualitatively (no metrics are used in this lab)
- You do not need to write code — all actions are done via the watsonx.ai interface

---

## 📞 Contact

- Stefan Vogel – [stefan.vogel@ch.ibm.com](mailto:stefan.vogel@ch.ibm.com)
- Naim Zierau – [Naim.Zierau@ibm.com](mailto:Naim.Zierau@ibm.com)
- Husniye Sekeroglu – [Huesniye.Sekeroglu@ibm.com](mailto:Huesniye.Sekeroglu@ibm.com)  
