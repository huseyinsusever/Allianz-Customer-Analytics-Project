# Allianz-Customer-Analytics-Project
This project demonstrates an end-to-end data pipeline from a **MySQL** database to a **PyTorch** deep learning model.

## Features
- **Database:** Relational schema design with MySQL.
- **Deep Learning:** Artificial Neural Network (ANN) implemented using PyTorch.
- **Hardware Acceleration:** Leveraging **NVIDIA CUDA** for faster training.
- **Hybrid Environment:** Compatible with both local Jupyter and Google Colab.

## How to Run
1. Run `database_setup.sql` in your MySQL environment.
2. Open `Allianz_Analysis.ipynb` and update your database credentials.
3. Observe the training loss visualization.
database_setup.sql: Veritabanı ve tablo kurulum kodları.
● Allianz_Analiz_Local.ipynb: Yerel bilgisayardaki SQL bağlantılı analiz dosyası yani jupyter
● Allianz_Analiz_Colab.ipynb: Google Colab üzerinden GPU hızlandırmalı eğitim dosyası.
● Proje_Ozeti.pdf: Projenin teknik raporu ve görsel sonuçları
