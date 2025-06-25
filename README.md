# 🧠 ASR Model Evaluation Metrics Parser

This project provides a structured parser for extracting and summarizing **Automatic Speech Recognition (ASR)** model evaluation results from text logs. It is designed to handle outputs from multiple models and generate a comparative metrics table including **WER**, **CER**, and edit rates.

---

## 🎯 Purpose

To automate and organize evaluation metrics from ASR models like:
- `whisper-small` variants
- `wav2vec2-xls-r-300m`
- `mms-1b-all`

Used across different training durations and datasets.

---

## 📊 Metrics Captured

- **Word Error Rate (WER)**
- **Character Error Rate (CER)**
- **Substitution / Insertion / Deletion Counts and Rates**
- **Total Words Recognized**

---

## 🧰 Dependencies

Install required packages using:

```bash
pip install pandas
