# Proyek Akhir: Klasifikasi Gambar

## Intruksi proyek

Proyek klasifikasi gambar ini digunakan untuk menyelesaikan kelas Dicoding Data Scientist tingkat menengah. dalam proyek ini kami dibebaskan untuk memilih topik atau kategori gambar yang ingin diklasifikasikan, serta platform atau dataset mana yang ingin dipakai sebagai sumber data.

## Dataset

Adapun dataset yang digunakan adalah data <a href="https://www.kaggle.com/datasets/yapwh1208/dogs-breed-dataset"> Breed Classification Dog</a>. Dalam dataset tersebut terdapat 5 ras anjing dengan total 1030 gambar.

## Cakupan Proyek

Untuk mengerjakan proyek tersebut, saya akan membuat klasifikasi gambar yang dilakukan menggunakan ***model pre-train dari MobileNetV2 kemudian ditambah model Sequential***. Setelah itu model yang sudah jadi disimpan ke dalam format SavedModel, TF-Lite dan TFJS .


## Hasil

Setelah model dibuat, didapatkan hasil akurasi sebesar 89% (dapat dilihat di file ""). Akan tetapi, ternyata akurasi training dan validation berbeda jauh sehingga menunjukkan model mengalami overfit.

## Conclusion

Berdasarkan model yang telah dibuat dapat disimpulkan bahwa:
- Model berhasil mendapatkan akurasi sebesar 89%
- Model mengalami overfit. hal ini dibuktikan dengan perbedaan akurasi training dan validation (selisih 10%)