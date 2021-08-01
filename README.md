# auto-run-app-on-startup-raspbarry
Cara membuat auto run app pada raspberry pi 3 raspbian buster
menjalankan aplikasi bawaan/program pada raspbian ini secara otomatis ketika Raspberry pertama kali dinyalakan/booting/startup.

rc.local adalah file yang dikelola sistem yang dijalankan setelah semua layanan sistem dimulai, yaitu, setelah beralih ke run level multi-pengguna.  Ini adalah metode termudah untuk membuat program berjalan saat boot pada sistem Linux.  Tapi ada peringatan: Anda hanya dapat menggunakan metode ini untuk program tanpa elemen GUI (antarmuka pengguna grafis) karena rc.local dijalankan sebelum sistem windowing Raspberry Pi dimulai.
