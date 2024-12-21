# Tutorial Node Miner InitVerse

Panduan ini memberikan instruksi untuk mengunduh, mengatur, dan menjalankan miner InitVerse.  

## Prasyarat  
- Sistem berbasis Linux.  
- Alamat wallet yang valid untuk penambangan.  
- `screen` terinstal di sistem Anda.  
- Spec Vps Ram 8Gb up
---

## Langkah-langkah Bergabung dengan Tugas dan Mulai Menambang  

### 1. Task Testnet
- Kunjungi tautan berikut:  
  [Join Testnet ](https://candy.inichain.com?invite=H35L1J2YTY4KC0I9GTKI461BM)  
- Ikuti instruksi untuk:  
  - Menghubungkan wallet baru atau wallet testnet.  
  - Menghubungkan akun Twitter dan Discord Anda.  
  - Menyelesaikan login harian, swap, dan semua tugas lainnya yang tercantum.  

---
## INSTALASI MANUAL

### 2. Unduh File Miner IniChain  
Gunakan perintah `wget` untuk mengunduh file executable miner:  
```bash  
wget https://github.com/Project-InitVerse/ini-miner/releases/download/v1.0.0/iniminer-linux-x64  
```
## 3. Berikan Izin Eksekusi
Berikan izin eksekusi pada file tersebut:
```bash
chmod +x iniminer-linux-x64  
```

## 4. Buat Sesi Screen Baru
Jalankan miner dalam sesi screen yang terpisah agar tetap aktif di latar belakang
```bash
screen -S airdropnode_inichain
```

## 5. Jalankan Miner InitVerse
Jalankan perintah berikut di dalam sesi screen untuk memulai penambangan:
```bash
./iniminer-linux-x64 --pool stratum+tcp://<YOUR_WALLET_ADDRESS>.Worker001@pool-core-testnet.inichain.com:32672  
```
Gantilah <YOUR_WALLET_ADDRESS> dengan alamat wallet Anda.

Untuk keluar dari sesi screen tanpa menghentikan miner:
CTRL+A+D

## AUTO INSTALL ONE CLICK
```bash
LOADING
```

## Periksa Aktivitas Miner Anda Kunjungi dasbor pool penambangan:

https://genesis-testnet.yatespool.com/

Tempelkan alamat wallet Anda untuk memantau aktivitas dan penghasilan Anda.

## Periksa Hadiah Penambangan Anda
Hadiah akan dikirim secara otomatis ke wallet Anda.
Anda dapat memverifikasinya menggunakan explorer:

https://genesis-testnet.iniscan.com/

## Support Airdrop Node

For more updates and discussions, join the [Telegram Airdrop Node](https://t.me/airdrop_node).

[Traktir Kopi ](https://trakteer.id/AirdropNode/tip).

## DONE


