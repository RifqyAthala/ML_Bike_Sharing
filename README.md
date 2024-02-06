# **Machine Learning for Budget Optimization: Predicting Total Bike Rentals to Enhance Cost Savings**

### **CONTEXT**
Capital Bike Sharing adalah sistem penyewaan sepeda yang ada di Washington DC , Amerika Serikat. Seluruh proses penyewaan sepeda mulai dari keanggotaan, penyewaan, dan pengembalian kembali, sudah menjadi otomatis. Melalui sistem ini, pengguna
dapat dengan mudah menyewa sepeda dari posisi tertentu stasiun Bike Sharing dan kembali lagi pada posisi atau Stasiun lain dari Capital Bike Sharing. 

### **PROBLEM**
Tantangan utama yang dihadapi oleh Capital Bike Sharing adalah melakukan ekspansi stasiun penyewaan sepeda ke kota-kota lain di luar Washington DC. Untuk melakukan ekspansi ini dengan efektif, **Capital Bike Sharing perlu memprediksi potensi jumlah penyewa sepeda di kota-kota baru yang dituju**. Prediksi ini akan membantu dalam:

- Penghematan Anggaran: Dengan memahami jumlah penyewa sepeda yang diharapkan di kota baru, Capital Bike Sharing dapat mengalokasikan anggaran yang sesuai untuk persiapan operasional pengadaan sepeda dan penentuan lokasi stasiun penyewaan yang optimal
### **GOALS**
**Membuat Model Machine Learning yang dapat memprediksi total penyewa sepeda untuk Penghematan Anggaran**

### **Matrics Evaluation**

Untuk mengukur kualitas suatu model dan melakukan evaluasi dalam konteks Machine Learning, kita memerlukan metrik evaluasi. Dalam model Machine Learning yang akan dikembangkan, kita akan menggunakan 3 matrcis evaluasi yaitu :

1. **RMSE (Root Mean Squared Error)**:
   - "RMSE (Root Mean Squared Error) adalah metrik yang mengukur sejauh mana model machine learning dapat memprediksi jumlah pengguna yang menyewa sepeda dengan akurat. Ini dihitung sebagai akar kuadrat dari rata-rata dari selisih antara nilai prediksi dan nilai sebenarnya. Semakin kecil RMSE, semakin baik model tersebut, karena menunjukkan bahwa kesalahan prediksi lebih mendekati nol."

2. **MAPE (Mean Absolute Percentage Error)**:
   - "MAPE (Mean Absolute Percentage Error) adalah metrik yang mengukur sejauh mana kesalahan prediksi model dalam bentuk persentase relatif terhadap jumlah sepeda yang sebenarnya disewa. Ini dihitung sebagai nilai absolut dari selisih persentase antara nilai prediksi dan nilai sebenarnya. MAPE digunakan dalam dunia bisnis karena lebih mudah diinterpretasi oleh pemangku kepentingan, karena memberikan gambaran langsung tentang persentase kesalahan dalam prediksi."

3. **R-squared (Koefisien Determinasi)**:
   - "R-squared (Koefisien Determinasi) adalah metrik yang mengukur sejauh mana variasi dalam data yang dapat dijelaskan oleh model. Nilai R-squared berkisar antara 0 hingga 1, di mana nilai 1 menunjukkan bahwa model dapat menjelaskan seluruh variasi dalam data. Dalam dunia bisnis, R-squared digunakan untuk menilai sejauh mana model cocok dengan data historis, dan semakin tinggi nilainya, semakin baik model tersebut dalam menjelaskan variasi dalam jumlah sepeda yang disewakan."

- Dalam konteks utama, kita akan menggunakan MAPE sebagai metrik evaluasi utama karena kemudahan interpretasinya. Namun, kita juga akan melibatkan RMSE dan R-squared untuk memberikan informasi tambahan tentang kualitas model kepada pemangku kepentingan.
