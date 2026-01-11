
# Laporan Praktikum Minggu [X]
Topik: [Tuliskan judul topik, misalnya "Arsitektur Sistem Operasi dan Kernel"]

---

## Identitas
- **Nama**  : Naufal Adib Bissibyan
- **NIM**   : 250202958
- **Kelas** : 1 IKR A

---

## Tujuan
Tuliskan tujuan praktikum minggu ini.  
Setelah menyelesaikan tugas ini, mahasiswa mampu:

1.Membuat program simulasi algoritma penjadwalan FCFS dan/atau SJF.
2.Menjalankan program dengan dataset uji yang diberikan atau dibuat sendiri.
3.Menyajikan output simulasi dalam bentuk tabel atau grafik.
4.Menjelaskan hasil simulasi secara tertulis.
5.Mengunggah kode dan laporan ke Git repository dengan rapi dan tepat waktu.

---

## Dasar Teori
1.Sistem Operasi dan Manajemen Proses Sistem operasi berfungsi mengelola sumber daya komputer, salah satunya adalah manajemen proses. Manajemen proses bertugas mengatur eksekusi beberapa proses agar dapat berjalan secara efisien dengan memanfaatkan CPU secara optimal.

2.Konsep Penjadwalan CPU Penjadwalan CPU adalah mekanisme penentuan urutan proses yang akan dieksekusi oleh CPU. Karena CPU hanya dapat memproses satu proses pada satu waktu, penjadwalan diperlukan untuk mengatur giliran eksekusi proses.

3.Algoritma Penjadwalan CPU Algoritma penjadwalan CPU merupakan aturan yang digunakan untuk memilih proses yang akan dijalankan, seperti First Come First Served (FCFS), Shortest Job First (SJF), Priority Scheduling, dan Round Robin (RR). Setiap algoritma memiliki karakteristik serta kelebihan dan kekurangan masing-masing.

4.Parameter Kinerja Penjadwalan Kinerja algoritma penjadwalan dievaluasi menggunakan parameter seperti waiting time, turnaround time, response time, dan CPU utilization. Parameter ini digunakan untuk menilai efisiensi dan keadilan suatu algoritma penjadwalan.

5.Simulasi Algoritma Penjadwalan CPU Simulasi algoritma penjadwalan CPU digunakan untuk memodelkan dan menganalisis cara kerja algoritma dalam kondisi tertentu. Melalui simulasi, performa berbagai algoritma dapat dibandingkan dan dipahami tanpa harus diterapkan langsung pada sistem operasi nyata.

---

## Langkah Praktikum
1.Menyiapkan Dataset Buat dataset proses minimal berisi data yang telah disajikan.
2.Implementasi Algoritma Program harus: Menghitung waiting time dan turnaround time. Mendukung minimal 1 algoritma (FCFS atau SJF non-preemptive). Menampilkan hasil dalam tabel.
3.Eksekusi & Validasi : Jalankan program menggunakan dataset uji. Pastikan hasil sesuai dengan perhitungan manual minggu sebelumnya.Simpan Hasil Screenshot.
4.Analisis : Jelaskan alur program. Bandingkan hasil simulasi dengan perhitungan manual. Jelaskan kelebihan dan keterbatasan simulasi.
5.Commit & Push git add . git commit -m "Minggu 9 - Simulasi Scheduling CPU" git push origin main
---

## Kode / Perintah
Tuliskan potongan kode atau perintah utama:
```bash
praktikum/week9-sim-scheduling/
├─ code/
│  ├─ scheduling_simulation.*
│  └─ dataset.csv
├─ screenshots/
│  └─ hasil_simulasi.png
└─ laporan.md
```

---

## Hasil Eksekusi

![rykii phyton](https://github.com/user-attachments/assets/718f9a7b-a1e3-4596-a1e8-216d3e3490bb)


---

## Analisis
Hasil simulasi sesuai dengan perhitungan manual yang telah dilakukan pada praktikum minggu sebelumnya. Algoritma FCFS memiliki kelebihan yaitu mudah diimplementasikan dan adil berdasarkan urutan kedatangan. Namun, algoritma ini memiliki kelemahan berupa kemungkinan terjadinya convoy effect, di mana proses dengan burst time panjang dapat memperlambat proses lain.


---

## Kesimpulan
Simulasi FCFS berhasil diimplementasikan dengan baik dan memberikan hasil yang konsisten dengan teori. Praktikum ini membantu memahami hubungan antara konsep penjadwalan CPU dan implementasi komputasionalnya.



---

## Quiz
1.Mengapa simulasi diperlukan untuk menguji algoritma scheduling? Jawaban: Simulasi diperlukan untuk mengotomatisasi perhitungan penjadwalan CPU sehingga hasil lebih cepat, konsisten, dan minim kesalahan dibandingkan perhitungan manual.
2.Apa perbedaan hasil simulasi dengan perhitungan manual jika dataset besar? Jawaban: Secara teori hasilnya sama, namun pada dataset besar simulasi jauh lebih efisien dan akurat, sedangkan perhitungan manual tidak praktis dan rawan kesalahan.
3.Algoritma mana yang lebih mudah diimplementasikan? Jelaskan. Jawaban: Algoritma FCFS lebih mudah diimplementasikan karena hanya mengurutkan proses berdasarkan waktu kedatangan tanpa logika tambahan seperti pemilihan proses terpendek.
---


## Refleksi Diri
Tuliskan secara singkat:
- Apa bagian yang paling menantang minggu ini?  
- Bagaimana cara Anda mengatasinya?  

---

**Credit:**  
_Template laporan praktikum Sistem Operasi (SO-202501) – Universitas Putra Bangsa_
