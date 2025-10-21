# otomasi-jaringan-program-DNS-Change-Notifier-
Program Python sederhana untuk memantau perubahan DNS server pada sistem Linux dengan membaca file /etc/resolv.conf. Program ini secara berkala mengecek konfigurasi DNS dan memberikan peringatan jika terjadi perubahan, membantu kamu mengetahui perubahan pengaturan jaringan yang mungkin tidak diinginkan atau tidak diketahui.
# DNS Change Notifier

Program sederhana untuk memantau perubahan DNS server pada sistem Linux dengan membaca file `/etc/resolv.conf`.

Jika DNS server berubah, program akan menampilkan peringatan di terminal.

## Fitur

- Memantau perubahan DNS server secara berkala (default setiap 30 detik)
- Menyimpan baseline DNS terakhir yang digunakan
- Memberi tahu jika DNS server berubah dibanding baseline

## Cara Menggunakan

1. Clone repository ini atau download file `dns_change_notifier.py`

2. Jalankan program dengan Python 3:

```bash
python3 dns_change_notifier.py
