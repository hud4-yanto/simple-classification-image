# Proyek Akhir: Klasifikasi Gambar

## Pendahuluan

Proyek klasifikasi gambar ini digunakan untuk menyelesaikan kelas Dicoding Data Scientist tingkat menengah. dalam proyek ini kami dibebaskan untuk memilih topik atau kategori gambar yang ingin diklasifikasikan, serta platform atau dataset mana yang ingin dipakai sebagai sumber data.

## Dataset

Adapun dataset yang digunakan adalah data <a href="https://www.kaggle.com/datasets/yapwh1208/dogs-breed-dataset"> Breed Classification Dog</a>. Dalam dataset tersebut terdapat 5 ras anjing dengan total 1030 gambar.

## Cakupan Proyek

Untuk mengerjakan proyek tersebut, saya akan membuat klasifikasi gambar yang dilakukan menggunakan ***model pre-train dari MobileNetV2 kemudian ditambah model Sequential***. Setelah itu model yang sudah jadi disimpan ke dalam format SavedModel, TF-Lite dan TFJS .


## Hasil

Setelah model dibuat, didapatkan hasil akurasi sebesar 92%. 
<br>![alt text](https://github.com/hud4-yanto/simple-classification-image/blob/main/Hasil%20akurasi.png?raw=true) </br>
Adapun grafik akurasi dan loss yang dihasilkan sebagaimana berikut
<br>![alt text](https://github.com/hud4-yanto/simple-classification-image/blob/main/Grafik%20Akurasi.png?raw=true)</br>


## Catatan

Jika anda ingin menjalankan proyek ini, maka berikut caranya 

Setup environment:

Buka terminal atau PowerShell. Kemudian buat sebuah folder baru bernama proyek_image_classification dengan menjalankan perintah berikut.
```
mkdir proyek_image_classification

```
Kemudian pindah ke folder terbaru tersebut menggunakan perintah berikut.
```
cd proyek_image_classification

```
Kita buat sebuah virtual environment dengan menjalankan perintah berikut.
```
pipenv install

```
Aktifkan virtual environment dengan menjalankan perintah berikut.
```
pipenv shell

```
Instal semua library yang dibutuhkan menggunakan perintah berikut.
```
pip install -r requirements.txt 

```
Buka jupyter-notebook dengan menjalankan perintah berikut.
```
jupyter-notebook .

```
