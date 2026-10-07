# 💼 FinHealth: Expert System Kesehatan Finansial UMKM

Aplikasi berbasis web (*Web Application*) dengan arsitektur Sistem Pakar (*Rule-Based Expert System*) yang dirancang khusus untuk mendiagnosa kesehatan finansial pelaku Usaha Mikro, Kecil, dan Menengah (UMKM) secara instan.

## 🎯 Deskripsi Proyek
Kebanyakan UMKM kesulitan memahami rasio akuntansi yang kompleks. *FinHealth* mentransformasikan data input sederhana (seperti aset, kewajiban, omzet, dan arus kas) ke dalam kalkulasi rasio likuiditas/profitabilitas. Mesin inferensi kemudian akan mengevaluasi angka tersebut dan mengeluarkan diagnosa serta rekomendasi operasional yang dapat langsung ditindaklanjuti.

## 🛠️ Tech Stack & Arsitektur
* **Backend Language:** Python 3
* **Framework:** Flask
* **Arsitektur Sistem:** RESTful API
* **Metode Pakar:** *Rule-Based Logic Tree* (Berdasarkan standar rasio keuangan akuntansi)
* **Format Data:** JSON

## ✨ Fitur Utama
1. **Financial Calculator API:** Menghitung *Current Ratio*, *Cash Flow Margin*, dan *Profit Margin* secara otomatis.
2. **Diagnostic Engine:** Mengevaluasi ambang batas (*threshold*) indikator untuk mendeteksi krisis likuiditas atau inefisiensi biaya.
3. **Actionable Recommendations:** Memberikan umpan balik yang ramah pengguna (contoh: "Fokus kurangi hutang jangka pendek" atau "Lakukan efisiensi biaya operasional bulanan").
