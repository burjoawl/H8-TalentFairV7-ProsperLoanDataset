<!-- Full Name & Batch -->
<br />
<div align="center">
  <a>
    <img src="https://coursereport-s3-production.global.ssl.fastly.net/uploads/school/logo/322/original/Logo_Hacktiv8.jpg" alt="Hacktiv8">
  </a>

  <h2 align="center">Judul baris 1</h2>

  <p align="center">
    <strong>Dibuat oleh:</strong>
    <br />
</a>
    <strong>Muhammad Farhan Salimuddin</strong>
    <br />
    <strong>Batch RMT 020</strong>
    <br />
    <a href="https://huggingface.co/spaces/burjoawl/H8-TalentFairV7-ProsperLoanDataset">Deployment Projek</a>
  </p>
</div>

<!-- Project Description -->
<div align="Center">
<b><h1>Tentang Projek</b></h1>
</div>
Projek ini membahas tentang prediksi nasabah yang akan membayar pinjaman atau tidak beserta besaran kerugian apabila nasabah tidak membayar pinjaman.
<br>
<div align="left">
  Data yang digunakan berasal dari <a href="https://www.kaggle.com/datasets/nurudeenabdulsalaam/prosper-loan-dataset"><img src="https://upload.wikimedia.org/wikipedia/commons/7/7c/Kaggle_logo.png?20140912155123" width="40"></a> dengan nama datasetnya <i>Prosper Loan Dataset</i>, data ini berasal dari perusahaan Prosper yang berada di <i>United States</i> atau Amerika.


<!-- Conclusion -->
<div align="Center">
<b><h1>Kesimpulan</b></h1>
</div>

Berdasarkan EDA dapat dilihat bahwa:
- Nasabah pada dataset ini banyak yang masih berjalan dalam peminjaman, dan banyak juga yang sudah lunas
- Status pekerjaan Full Time tidak mempengaruhi apakah nasabah akan melunasi pinjaman atau tidak
- Pekerjaan Other dan Professional sama sama memiliki urutan 2 terbesar dalam hal melunasi atau tidaknya pinjaman, pekerjaan other tidak ada penjabaran.

Berdasarkan pemodelan dapat dilihat bahwa:
* Sebanyak 6912 nasabah yang diprediksi layak dapat pinjaman dan aktualnya layak, dan sebanyak 2821 nasabah yang diprediksi tidak layak dapat pinjaman dan aktualnya tidak layak.
* Sebanyak 542 nasabah yang diprediksi layak tetapi aktualnya tidak layak.
* Sebanyak 695 nasabah yang diprediksi tidak layak tetapi aktualnya layak, ini merupakan kondisi yang harus diperhatikan.
* Model ini tergolong overfit karena nilai akurasi pada train dan test yang memiliki gap yang lumayan jauh
* Nasabah dengan cluster 0 merupakan nasabah yang bertanggung jawab, karena seberapa besar nilai hutangnya tetap dibayar lunas, sedangkan pada cluster 1 merupakan nasabah perlu diperhatikan, karena semakin tinggi nilai pinjamannya akan semakin besar uang perusahaan yang hilang, untuk cluster 2 sama saeperti cluster 1, tetapi pada cluster 2 semakin tinggi angka pinjamannnya, maka nilai yang hilang akan semakin lebih besar juga

<!-- Akhir Kata -->
<div align="Center">
<b><h1>Akhir Kata</b></h1>
</div>

Saya ingin mengucapkan terima kasih sebesar-besarnya kepada pihak Hacktiv8 khususnya para instruktur dan buddy atas ilmunya selama ini.