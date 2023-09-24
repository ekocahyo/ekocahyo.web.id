+++
title = "My First Post"
date = 2023-09-24T13:25:40Z
author = "ekocahyo"
keywords = ["hugo", "eko cahyo"]
cover = "Hari pertamaku menggunakan Hugo"
summary = "Hari pertamaku menggunakan Hugo"
+++

## Hello World!

Mungkin kata tersebut yang cocok untuk aku ucapkan pertamakali, seperti yang lainnya ketika berhasil menjalankan sesuatu. Ini pertama kalinya aku mencoba membuat blog dengan menggunakan generator web static dengan bahasa Go (Go lang). Awalnya aku coba menggunakan generator web static miliknya jekyll masih cukup rumit menurutku (untuk orang yang bukan programmer).

## Intro Hugo
Pertama kali aku coba Hugo, aku langsung dibikin jatuh hati. Salah satu yang bikin aku menyukainya adalah, ketika running servernya, dan aku ada edit content, tanpa perlu refresh browser, content sudah berubah sendiri. So easy, so clean, so fast. Jadi buat yang belum tahu tentang Hugo, coba aku share pandangan aku tentang hugo.

Menurut bang [Wiki](https://en.wikipedia.org/wiki/Hugo_(software)), Hugo adalah suatu generator web static yang di kembangkan dengan menggunakan bahasa Go. Hugo ini ternyata dibuat sama bang [Steve Francia](https://spf13.com/) pada tahun 2013. Silahkan yang mau ikutan mengucapkan terima kasih terhadap beliau. Hugo ini memiliki lisensi opensource. Jadi sama bang Steve dishare itu code-nya. Sehingga tidak perlu bayar buat ngembangin atau pun cuma pakai. Buat yang ingin langsung mempelajari nya bisa mulai dari [sini](https://gohugo.io/getting-started/quick-start/) ya.

## Hosting to Github

Di hari yang sama juga, aku baru tahu kalau github bisa dijadiin hosting blog. Ya meskipun hanya mendukung static web saja, itu lebih dari cukup menurutku (kan memang ini temanya static web). Jadi Hugo ini memiliki folder khusus hasil generate file static web nya. Nama foldernya `public`. Oh iya, hampir lupa. Hugo ini menggunakan bahasa Markdown(format file .md) bukan bahasa Go untuk format penulisan content-nya. Jadi kita tulis dalam file dengan format `.md`, lalu digenerate sama Hugo hasilnya keluar di folder `public` dalam bentuk `.html`.

Kita lanjutin pembahasan ke hosting di github. Jadi yang akan kita taruh di github nantinya hanya folder public yang sudah di generate sama Hugo nya. Jadi pertama kalian harus punya akun github dulu pastinya. berikutnya bikin repository dengan format <em>username</em>.github.io. Kalian ganti usernamenya sesuai username kalian ya. Lalu folder public tadi kalian taruh deh ke repository tadi. Dan selamat, blog kalian sudah jadi.

## Summary
Open Source tidak lah buruk. Justru opensource bisa membuat wawasan kita menjadi lebih luas lagi. Intinya tetap membaca, tetap belajar, dan ketika sudah mahir, jangan lupa ikutan berkontribusi. Berbagi itu indah. Contoh nya dengan adanya hugo dan github, kita bisa ikutan merasakan mudah nya membuat blog yang gratis. Sudah ringan, gratis, simple (idaman banget).