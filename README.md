# Image-Classification-Web-Deployment
Machine Learning


Pelangi Cita Indah - 202010370311430 - Machine Learning C


# Dataset
Dataset yang digunakan dapat diakses melalui link https://drive.google.com/file/d/1X9jFokn9AXMMVTmlBQ7XZpBsLKVFnp-d/view?usp=drive_link 

![download (2)](https://github.com/PelangiCita/Image-Classification-Web-Deployment/assets/72428654/c10cad5a-49dd-43a8-b421-b18656e60dff)

Dataset telah melalui proses pre-processing, seperti augmentasi sebelum dilakukan fit model. 

# Flask:
Flask adalah kerangka kerja (framework) web mikro yang ditulis dalam bahasa pemrograman Python yang dirancang untuk 
menjadi ringan dan sederhana, dengan fokus pada kemudahan penggunaan dan fleksibilitas. Untuk menjalankan Flask, dapat 
menggunakan perintah FLask run.

# ResNet:
ResNet, singkatan dari Residual Networks, adalah arsitektur jaringan saraf konvolusional (CNN) yang diperkenalkan pada 2015. 
Dengan memanfaatkan blok residu, ResNet dapat melibatkan model yang sangat dalam tanpa mengalami masalah kinerja. Pendekatan 
ini telah meningkatkan akurasi dalam tugas-tugas visi komputer seperti klasifikasi gambar dan deteksi objek.

![download (2)](https://github.com/PelangiCita/Image-Classification-Web-Deployment/assets/72428654/6e9f6aa1-d180-448e-a6cc-9ce3b7106750)


# MobileNet:
MobileNet, di sisi lain, dirancang khusus untuk aplikasi pada perangkat seluler dan perangkat terkait. Kelebihan utama MobileNet 
adalah arsitekturnya yang ringan dan dapat diimplementasikan dengan cepat pada perangkat dengan daya komputasi terbatas. Dengan
menggunakan operasi konvolusi depthwise separable, MobileNet dapat memberikan keseimbangan yang baik antara akurasi klasifikasi
dan kebutuhan komputasi yang rendah. Hal ini membuatnya sangat cocok untuk aplikasi real-time atau perangkat dengan keterbatasan 
daya baterai.

![download](https://github.com/PelangiCita/Image-Classification-Web-Deployment/assets/72428654/99a99500-6376-43e4-b826-5b0630310d1a)


# Hasil Prediksi
Berikut hasil yang didapatkan setelah dilakukan prediksi.

![download (1)](https://github.com/PelangiCita/Image-Classification-Web-Deployment/assets/72428654/6f00620a-0e5b-4338-8eee-a4f89686701c)


# Web Deployment
Dalam tugas ini, web memanfaatkan Flask untuk menyajikan halaman web, menerima unggahan gambar, dan menggunakan model klasifikasi 
gambar untuk membuat prediksi. 

1. Tampilan halaman web untuk mengupload gambar.

   ![Screenshot (699)](https://github.com/PelangiCita/Image-Classification-Web-Deployment/assets/72428654/b2220512-42c6-4c5f-8568-5064c206dc19)

   
3. Tampilan halaman web untuk menampilkan hasil klasifikasi citra.
  
   Hasil klasifikasi menggunakan ResNet.

   ![Screenshot (700)](https://github.com/PelangiCita/Image-Classification-Web-Deployment/assets/72428654/d0c27896-d5b4-4226-97a3-8977c2959f85)


   Hasil klasifikasi menggunakan MobileNet.

   ![Screenshot (701)](https://github.com/PelangiCita/Image-Classification-Web-Deployment/assets/72428654/559d2229-790b-48bf-a775-c68caffe30d2)

