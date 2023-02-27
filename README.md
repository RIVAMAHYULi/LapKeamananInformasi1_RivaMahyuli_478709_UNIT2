# LapKeamananInformasi1_RivaMahyuli_478709_UNIT2
Pembahasan/analisis
Pada pratikum ini kita  melakukan 2 buah unit secara langsung yaitu   eksplorasi nmap yang bertujuan untuk mengetahui tools dan perintah yang digunakan di nmap dan  Pemantauan Trafik HTTP dan HTTPS dengan menggunakan Wireshark. Dimana wireshark merupakan salah satu tool yang terdapat di nmap.

Pada unit 2 kita bisa mendapatkan informasi apa aitu nmap, fungsinya, port yang terbuka dan software yang digunakan, layanan yang digunakan oleh system, ip address ,subnet mask, dan jumlah host yang aktif dengan menggunakan argument atau syntax-syntax yang ada.dimana ini bisa digunakan untuk audit keamanan, namun banyak administrator sistem dan jaringan menganggapnya berguna untuk tugas rutin seperti inventori jaringan, mengelola jadwal upgrade layanan, dan melakukan monitoring uptime host atau layanan.
Output Nmap adalah sebuah daftar target yang diperiksa, dengan informasi berisi daftar angka port dan protokol, nama layanan, dan status. Statusnya adalah terbuka (open), difilter (filtered), tertutup (closed), atau tidak difilter (unfiltered)

Sedangkan  pada unit 3 kita menggunakan wireshark yang merupakan aplikasi yang menangkap paket dari koneksi jaringan. Paket data yang didapatkan dari wireshark bisa diklasifikasikan berdasarkan warnanya contoh nya pada gambar1 terdapat dua buah warna yaitu biru muda dan hijau muda dimana biru muda merupakan packet type UDP. Sedangkan  hijau muda merupakan packet type lalu lintas HTTP. Sedangkan pada gambar 2 kita menemukan adanya paket yang berwarna hitam yang merupakan packet type packet dengan kesalahan 

JAWABAN DARI PERTANYAAN DI MODUL
1. Apa itu Nmap? Nmap(network mapper) is a open source tool for network exploration and security auditing.
Apa fungsi dari Nmap? Nmap uses raw IP packets in novel ways to determine what host are available on the network, what service those host are offering, what operating system they are running, what type of packet filters/firewalls are in use and dozens of others characteristic.

2. Port dan layanan apa yang terbuka serta software yang digunakan ? 21/tcp open ftp software vsftpd, 22/tcp open ssh software ssh 8.2 , 23/tcp open telnet software linux.

3.Berapa alamat ip dan subnet mask dari pc host? 10.0.2.15/24 dan 10.0.2.255

4. Berapa jumlah host yang terdeteksi? 1 host up

5.Alamat IP server adalah 45.33.32.156 dan sistem operasi yang digunakan oleh server adalah linux

