# Pertemuan 10 - String dan Pengolahan Teks 
 
Nama: RIKI AGIL SAPUTRA


NIM: 2225250026


Kelas: 3A
 
## Tujuan 
Mengolah dan menormalisasi data teks dengan string Python. 
 
## Cara Menjalankan 
python3 tugas/normalisasi_data_mahasiswa.py 
 
## Algoritma 
proses normalisasi dilakukan dengan membersihkan spasi di awal dan akhir nama. Kemudian memisahkan nama menjadi beberapa kata dalam list dan menggabungkannya kembali nama menjadi satu dengan memberikan satu spasi di antara kata dalam nama dan membuat huruf awal setiap kata dalam nama menjadi kapital.
 
## Test Case 

| Input Nama | Input Kode | Hasil Diharapkan | Hasil Aktual | Status |
| :--- | :--- | :--- | :--- | :--- |
| aan hendrayana | pmat a 2026 | Aan Hendrayana \| PMAT-A-2026 \| AH | Aan Hendrayana \| PMAT-A-2026 \| AH | Sesuai |
| fATHIYYAH mUTHMAINNAH | kelas b | Fathiyyah Muthmainnah \| KELAS-B \| FM | Fathiyyah Muthmainnah \| KELAS-B \| FM | Sesuai |
| BUDI | pmtk 01 | Budi \| PMTK-01 \| B | Budi \| PMTK-01 \| B | Sesuai |
| siti nur aisyah | kelas c | Siti Nur Aisyah \| KELAS-C \| SNA | Siti Nur Aisyah \| KELAS-C \| SNA | Sesuai |

## Refleksi 
Jelaskan satu masalah teks yang ditemukan dan cara memperbaikinya.
satu masalah teks yang saya temui adalah saya menggabungkan 
.title() ke dalam bagian join sehingga menimbulkan error. Kemudian saya atasi dengan memisahkan .title() dari bagian join.