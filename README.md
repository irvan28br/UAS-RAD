# UAS-RAD
web api using python
Ini adalah contoh aplikasi Python yang mendemonstrasikan penggunaan yang sangat sederhana dari REST API dari aplikasi Web.
Hambatan awal terbesar bagi pengembang biasanya membuat autentikasi OAuth berfungsi dengan baik, sehingga sebagian besar contoh ini didedikasikan untuk itu.
Anda memerlukan kunci dan rahasia partner OAuth agar aplikasi sampel berhasil dijalankan.
Contoh ini menggunakan kerangka kerja Web Python kecil, web.py untuk menjalankan aplikasi Web guna mendemonstrasikan pengalihan OAuth lengkap, otentikasi, aliran pengalihan.
Ada empat file sumber:
1. api.py - Fungsi utilitas untuk masuk ke REST API dan membuat panggilan ke sana
2. oauth.py - Fungsi utilitas untuk membuat panggilan otentikasi OAuth
3. web_utils.py - Beberapa fungsi utilitas Web umum
4. api_example.py - Kode aplikasi contoh utama. Memutar dan mengonfigurasi aplikasi Web, dan menerapkan penangan permintaan untuk panggilan OAuth dan API sampel.

