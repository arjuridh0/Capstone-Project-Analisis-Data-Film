# 📊** Capstone Project – Data Analysis with AI Support**
## 📌 Project Overview

Proyek ini bertujuan untuk menganalisis dataset publik menggunakan kombinasi metode analisis data tradisional dan dukungan AI.
Hasil akhir mencakup:

- Analytical Result

- Insight & Findings

- Recommendations

## 📂 Dataset

Dataset yang digunakan tersedia dalam format .zip (misalnya archive.zip) dan dapat diunduh dari folder data

Dataset dimasukkan ke Google Colab dengan perintah:

**import pandas as pd
df = pd.read_csv('/content/sample_data/archive.zip')**

## ⚙️ Setup & Requirements

Clone repository dan install dependencies:

git clone https://github.com/username/capstone-project-analisis-data.git
cd capstone-project-analisis-data
pip install -r requirements.txt


**Library yang digunakan:**

- pandas → manipulasi data

- numpy → operasi numerik

- matplotlib & seaborn → visualisasi data

- langchain-community → integrasi dengan model AI

- replicate → akses model AI eksternal

## **🔑 API Token Setup**

Untuk menghubungkan dengan model AI, buat file token di Colab:

import os
os.environ["api_token2"] = "YOUR_API_KEY"

## **📈 Analysis Process**

- Data loading dan preprocessing

- Eksplorasi dan visualisasi data

- Klasifikasi menggunakan model AI

- Summarization & insight generation

- (Opsional) Interactive chat dengan AI untuk diskusi hasil

## ✅** Conclusion & Recommendations**

Program ini merupakan program yang sudah powerfull untuk menganalisis sebuah data, dengan adanya proses cleaning data, classification data, summarization data, serta fitur interactive chat dengan AI secara real-time untuk menanyakan informasi terkait hasil dari data yang sudah proses.

Program ini bisa dikembangkan lagi agar lebih interaktif dan user friendly serta bisa dikembangkan agar lebig fleksibel untuk menangani data lain selain data film

## 🤖** AI Support Explanation**

AI digunakan untuk mendukung analisis melalui fitur:

Classification → membantu identifikasi pola data

Summarization → merangkum insight penting

Interactive Chat → berdiskusi langsung dengan AI untuk eksplorasi lebih lanjut

## **📑 Output**

Hasil akhir dapat dilihat pada file berikut:

outputs/final_project_results.xlsx → gabungan hasil classification, summarization, dan chat history.

outputs/film_analysis_results.csv → hasil classification dan summarization data

outputs/chat_history.txt → log percakapan AI (opsional).

## **👤 Author**

**Nama: Muhammad Arju Ridho Maulana**

Batch: Hacktiv8 - Capstone Project

- LINK SOURCE CODE (in Colab):

https://colab.research.google.com/drive/1owOmWIFVFckEyOiFi_GyjdlDbWI_-Kn_?usp=sharing

