# Image-Classification-Web-Deployment
Modul 6 Machine Learning


# Flask:
Flask adalah kerangka kerja (framework) web mikro yang ditulis dalam bahasa pemrograman Python yang dirancang untuk 
menjadi ringan dan sederhana, dengan fokus pada kemudahan penggunaan dan fleksibilitas.

# EfficientNet:
EfficientNet adalah arsitektur klasifikasi gambar yang terkenal karena memanfaatkan strategi peningkatan skala, ketebalan, 
dan resolusi model secara seragam. Kelebihan utamanya terletak pada efisiensinya dalam mencapai akurasi tinggi dengan 
menggunakan jumlah parameter yang relatif lebih sedikit dibandingkan dengan model-model sebelumnya. Ini membuatnya sangat 
cocok untuk aplikasi dengan batasan sumber daya komputasional, seperti perangkat bergerak atau lingkungan perangkat terkait.

# MobileNet:
MobileNet, di sisi lain, dirancang khusus untuk aplikasi pada perangkat seluler dan perangkat terkait. Kelebihan utama MobileNet 
adalah arsitekturnya yang ringan dan dapat diimplementasikan dengan cepat pada perangkat dengan daya komputasi terbatas. Dengan
menggunakan operasi konvolusi depthwise separable, MobileNet dapat memberikan keseimbangan yang baik antara akurasi klasifikasi
dan kebutuhan komputasi yang rendah. Hal ini membuatnya sangat cocok untuk aplikasi real-time atau perangkat dengan keterbatasan 
daya baterai.

# Dataset
Dataset yang digunakan dapat diakses melalui link https://drive.google.com/file/d/1X9jFokn9AXMMVTmlBQ7XZpBsLKVFnp-d/view?usp=drive_link 

![download (2)](https://github.com/PelangiCita/Image-Classification-Web-Deployment/assets/72428654/c10cad5a-49dd-43a8-b421-b18656e60dff)

Dataset telah melalui proses pre-processing, seperti augmentasi sebelum dilakukan fit model.

# Web Deployment
Dalam tugas ini, web memanfaatkan Flask untuk menyajikan halaman web, menerima unggahan gambar, dan menggunakan model klasifikasi 
gambar untuk membuat prediksi. 

1. Tampilan halaman web untuk mengupload gambar.
   
![Screenshot (677)](https://github.com/PelangiCita/Image-Classification-Web-Deployment/assets/72428654/399bf375-615b-4c46-a2d1-54e63d9563a6)

   
2. Tampilan halaman web untuk menampilkan hasil klasifikasi citra.
   
![Screenshot (678)](https://github.com/PelangiCita/Image-Classification-Web-Deployment/assets/72428654/32457171-1e38-485a-96bb-ef8dfd1cc4e4)

