**Program Pengolah Data Nilai Akhir Mahasiswa**

**Deskripsi Program**

Program ini adalah program yang dibuat mengguanakan Dictionary untuk mengolah data nilai akhir mahasiswa. Program ini dibuat untuk mengelola data mahasiswa termasuk menampilkan, menambah, mengubah, menghapus, dan mencari data nilai mereka. Program ini dibuat dengan menggunakan NIM sebagai Key dan data mahasiswa (Nama, Nilai Tugas, Nilai UTS, Nilai UAS) sebagai Value. Program ini menggunakan perhitungan nilai akhir dengan bobot sebesar Nilai Tugas 30% lalu Nilai UTS 35% dan Nilai UAS 35%

**Fungsi Program**

1. Menghitung Nilai

Program ini menghitung Nilai Akhir berdasarkan formula yang ada.

![image](https://github.com/user-attachments/assets/70b3c75f-de55-4f49-b4d5-05050a4b78c8)

2. Menampilkan Data

Program ini menampilkan data mahasiswa dalam bentuk tabel. Apabila data di dalam program kosong maka tampilan tabel tersebut juga kosong.

![1](https://github.com/user-attachments/assets/25c4cc0c-23f6-42ae-9a82-474f4e419b27)

![image](https://github.com/user-attachments/assets/174262ec-a809-4437-817b-51c952fd67a9)


3. Menambahkan Data

Program ini akan meminta untuk memasukan data mahasiswa (Nama, Nilai Tugas, Nilai UTS, Nilai UAS) untuk selanjutnya akan dihitung menjadi data nilai akhir. Apabila program ini berhasil maka program akan menampilkan "Data berhasil ditambahkan!" dan program akan kembali ke menu awal.

![image](https://github.com/user-attachments/assets/f7729c6f-f95d-4b43-9a42-9a7b84755fb3)

4. Mengubah Data

Program ini akan meminta untuk memasukan NIM mahasiswa sebagai Key. Selanjutnya program akan meminta untuk memasukan data (Nama, Nilai Tugas, Nilai UTS, Nilai UAS) untuk kemudian akan diganti menjadi data yang baru. Apabila program ini berhasil maka program akan menampilkan "Data berhasil diubah!", namun apabila NIM yang dimasukan salah maka tambilan program "Data tidak ditemukan!".

![image](https://github.com/user-attachments/assets/0624f9a1-1817-4829-913a-193e7f99d9c2)

5. Menghapus Data

Program ini akan meminta untuk memasukan NIM mahasiswa sebagai Key. Selanjutnya apabila program ini berhasil maka program akan menampilkan "Data berhasil dihapus!", namun apabila NIM yang dimasukan salah maka tambilan program "Data tidak ditemukan!".

![image](https://github.com/user-attachments/assets/977b4ae6-3423-4440-a08a-8936d9284289)

6. Mencari Data

Program ini akan meminta untuk memasukan NIM mahasiswa sebagai Key. Selanjutnya apabila program ini berhasil maka program akan menampilkan data yang dicari, namun apabila NIM yang dimasukan salah maka tampilan program "Data tidak ditemukan!".

![image](https://github.com/user-attachments/assets/34ddd148-b092-4f24-85fe-9429113e7d85)

**Alur Penggunaan Program**

![12](https://github.com/user-attachments/assets/eda949ce-2218-42df-a8d5-ff2a323d162b)

 1. Menjalankan Program

    * Program akan menampilkan menu ketika dijalankan.

    * Ketika menu yang dipilih salah maka akan menampilkan "Pilihan tidak valid! Silakan coba lagi."

2. Memilih Menu

    * Ketik huruf sesuai pilihan menu:

      L: Melihat daftar nilai mahasiswa.

      T: Menambahkan data mahasiswa baru.

      U: Mengubah data mahasiswa berdasarkan NIM.

      H: Menghapus data mahasiswa berdasarkan NIM.

      C: Mencari data mahasiswa berdasarkan NIM.

      K: Keluar dari program.

3. Menambahkan Data

    * Pilih menu T (Tambah).

    * Masukkan informasi berikut:

      NIM: Nomor Induk Mahasiswa.

      Nama: Nama mahasiswa.

      Nilai Tugas, UTS, UAS: Nilai numerik.

    * Program akan otomatis menghitung nilai akhir dan menyimpan data.

4. Melihat Data

    * Pilih menu L (Lihat).

    * Data akan ditampilkan dalam tabel, termasuk NIM, nama, nilai tugas, UTS, UAS, dan nilai akhir.

5. Mengubah Data

    * Pilih menu U (Ubah).

    * Masukkan NIM mahasiswa yang ingin diubah.

    * Jika ditemukan, masukkan data baru (nama, nilai tugas, UTS, UAS).

    * Data akan diperbarui.

6. Menghapus Data

    * Pilih menu H (Hapus).

    * Masukkan NIM mahasiswa yang ingin dihapus.

    * Jika ditemukan, data akan dihapus dari daftar.

7. Mencari Data

    * Pilih menu C (Cari).

    * Masukkan NIM mahasiswa yang dicari.

    * Jika ditemukan, data akan ditampilkan.

8. Keluar dari Program

    * Pilih menu K (Keluar).

    * Program akan berhenti dengan pesan terima kasih.

Kesimpulan

Program ini sangat cocok untuk mengelola data sederhana, seperti nilai akhir semester, dengan fitur CRUD (Create, Read, Update, Delete). Dengan mengikuti alur di atas, pengguna dapat dengan mudah mengelola data mahasiswa.


