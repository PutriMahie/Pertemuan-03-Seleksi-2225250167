# Pertemuan 03 Seleksi Python
Nama: Putri Ayu Anisa Mahie
NIM: 2225250167
Kelas: 3F
## Tujuan
Menulis program seleksi if, if-else, kondisi majemuk, dan nested if.
## Cara Menjalankan
python3 tugas/analisis_persamaan_kuadrat.py
## Algoritma Tugas
1. Pertama, program bakal minta user masukin tiga angka, yaitu nilai a, b, dan c dari persamaan kuadratnya.
2. Sebelum lanjut ke rumus, program cek dulu apakah a-nya nol atau enggak. Soalnya kalau a = 0, itu udah bukan persamaan kuadrat lagi, jadi langsung dikasih tau ke user kalau persamaannya nggak valid.
3. Kalau a-nya bukan nol, baru deh program ngitung nilai diskriminan (D) pakai rumus D = b² - 4ac. Nilai D ini yang bakal nentuin "nasib" akar-akarnya nanti.
4. Setelah dapet nilai D, program mulai ngecek kondisinya satu-satu pakai if-elif-else:
   - Kalau D lebih besar dari 0, berarti persamaannya punya dua akar real yang beda.
   - Kalau D sama dengan 0, berarti cuma ada satu akar real (akarnya kembar).
   - Kalau D lebih kecil dari 0, berarti nggak ada akar real sama sekali (akarnya imajiner).
5. Di dalam masing-masing kondisi itu, ada pengecekan tambahan (nested if) buat mastiin hasil yang ditampilkan makin detail dan akurat, misalnya buat ngitung nilai akarnya langsung.
6. Terakhir, program nampilin hasil analisisnya ke layar sesuai kondisi yang kejadian tadi.
## Hasil Pengujian
Catat input, keluaran yang diharapkan, keluaran aktual, dan status.
## Refleksi
Jelaskan satu kesalahan logika yang ditemukan dan cara memperbaikinya.