# 📊 Submission Pertama : Menyelesaikan Permasalahan Human Resources 📊

## Business Understanding

Jaya Jaya Maju merupakan salah satu perusahaan multinasional yang telah berdiri sejak tahun 2000. Ia memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri. 

### Permasalahan Bisnis

Walaupun telah menjadi menjadi perusahaan yang cukup besar, Jaya Jaya Maju masih cukup kesulitan dalam mengelola karyawan. Hal ini berimbas tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10%.

Untuk mencegah hal ini semakin parah, manajer departemen HR ingin meminta bantuan Anda mengidentifikasi berbagai faktor yang mempengaruhi tingginya attrition rate tersebut. Selain itu, ia juga meminta Anda untuk membuat business dashboard untuk membantunya memonitori berbagai faktor tersebut.

### Cakupan Proyek

- Memahami permasalahan bisnis
- Pengecekan Data
- Data Cleaning
- Pembuatan Prediction Model
- Pembuatan Dashboard
- Pembuatan Video tentang dashboard yang telah dibuat dan akan di submit 

### Persiapan

Sumber data: https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee

Setup environment:

```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import classification_report, confusion_matrix, accuracy_score
import plotly.express as px
import joblib
```

## Business Dashboard

Saya telah membuat business dashboard yang bisa memberikan informasi tentang attrition maupun general information tentang karyawan yang perusahaan 'Jaya Jaya Maju' miliki. Menggunakan faktor-faktor seperti umur, role pekerjaan dan juga gaji bulanan sebagai visualisasi pembanding terhadap attrition kita bisa mendapatkan informasi atau insight-insight penting dari dashboard ini. Dashboard dapat diakses melalui file yang telah saya lampirkan diatas.

## Conclusion

Faktor-faktor seperti umur, gaji dan juga posisi pekerjaan menjadi pengaruh yang cukup signifikan terhadap attrition rate di perusahaan 'Jaya Jaya Maju'. Research dan Survey lebih lanjut terhadap hal ini diperlukan untuk bisa menentukan dan memilah faktor-faktor penentu utama terhadap attrition di perusahaan 'Jaya Jaya Maju'

### Rekomendasi Action Items (Optional)

Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.

- Perbaikan standar gaji atau pemberian benefit lebih terhadap karyawan dengan gaji yang lebih rendah : Karyawan dengan gaji '1000 - 3000' memiliki tingkat attrition yang sangat tinggi dibandingkan dengan grup gaji lain-nya. Hal ini bisa digunakan sebagai perbaikan terhadap standarisasi perusahaan dengan cara meningkatkan gaji karyawan dengan rate gaji '1000 - 3000' ataupun pemberian benefit yang juga bisa membuat mereka lebih puas dan betah terhadap perusahaan mereka.
- Research dan Survey lebih lanjut terhadap gaji : Selain saran saya diatas, terdapat anomali terhadap grup gaji '8000 atau lebih' karena mereka memiliki tingkat attrition yang lebih tinggi jika dibandingkan dengan grup '5000 - 8000'. Berdasarkan hal tersebut, jika anomali ini tidak segera diselesaikan maka bisa menjadi kerugian berlanjut terhadap perusahaan karena telah mengeluarkan budget yang lebih banyak tapi ternyata tidak bisa menurunkan tingkat attrition karyawan.
- Research dan Survey lebih lanjut terhadap work environment dll pada Job Role tertentu : Terdapat 3 Job Role dengan tingkat attrition yang sangat tinggi jika dibandingkan dengan Job Role lain-nya. Hal ini sangat berpengaruh terhadap tingkat attrition perusahaan.
