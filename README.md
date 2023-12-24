# Image-Classification-Web-Deployment
Machine Learning


Pelangi Cita Indah - 202010370311430 - Machine Learning C


# Dataset
Dataset yang digunakan dapat diakses melalui link https://drive.google.com/file/d/1X9jFokn9AXMMVTmlBQ7XZpBsLKVFnp-d/view?usp=drive_link 

![download (2)](https://github.com/PelangiCita/Image-Classification-Web-Deployment/assets/72428654/c10cad5a-49dd-43a8-b421-b18656e60dff)

Dataset telah melalui proses pre-processing, seperti augmentasi sebelum dilakukan fit model.

# Flask:
Flask adalah kerangka kerja (framework) web mikro yang ditulis dalam bahasa pemrograman Python yang dirancang untuk 
menjadi ringan dan sederhana, dengan fokus pada kemudahan penggunaan dan fleksibilitas.

# ResNet:
ResNet, singkatan dari Residual Networks, adalah arsitektur jaringan saraf konvolusional (CNN) yang diperkenalkan pada 2015. 
Dengan memanfaatkan blok residu, ResNet dapat melibatkan model yang sangat dalam tanpa mengalami masalah kinerja. Pendekatan 
ini telah meningkatkan akurasi dalam tugas-tugas visi komputer seperti klasifikasi gambar dan deteksi objek.

# MobileNet:
MobileNet, di sisi lain, dirancang khusus untuk aplikasi pada perangkat seluler dan perangkat terkait. Kelebihan utama MobileNet 
adalah arsitekturnya yang ringan dan dapat diimplementasikan dengan cepat pada perangkat dengan daya komputasi terbatas. Dengan
menggunakan operasi konvolusi depthwise separable, MobileNet dapat memberikan keseimbangan yang baik antara akurasi klasifikasi
dan kebutuhan komputasi yang rendah. Hal ini membuatnya sangat cocok untuk aplikasi real-time atau perangkat dengan keterbatasan 
daya baterai.

# Web Deployment
Dalam tugas ini, web memanfaatkan Flask untuk menyajikan halaman web, menerima unggahan gambar, dan menggunakan model klasifikasi 
gambar untuk membuat prediksi. 

1. Tampilan halaman web untuk mengupload gambar.

   ![Screenshot (691)](https://github.com/PelangiCita/Image-Classification-Web-Deployment/assets/72428654/1b0dd5fa-dcd7-4f3e-a6c6-c2af9f03a814)
   
2. Tampilan halaman web untuk menampilkan hasil klasifikasi citra.
  
   Hasil klasifikasi menggunakan ResNet.
   
   ![Screenshot (690)](https://github.com/PelangiCita/Image-Classification-Web-Deployment/assets/72428654/697cf313-a5e8-42ad-bb53-522f893f0828)

   Hasil klasifikasi menggunakan MobileNet.

   ![Screenshot (689)](https://github.com/PelangiCita/Image-Classification-Web-Deployment/assets/72428654/49f07f84-12f6-4ba4-8c0b-4468c1edb456)
