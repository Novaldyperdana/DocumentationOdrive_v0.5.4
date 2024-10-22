# DocumentationOdrive_v0.5.4

## **DOWNLOADING AND INSTALLING ODRIVETOOL**
1. Install python3

    `sudo apt install python3 python3-pip`

2. Install Odrivetool melalui terminal

   `sudo pip3 install --upgrade odrive`

## **Firmware**
Ini adalah langkah jika odrive belum ada firmwarenya (masih baru), jika sudah ada firmwarenya maka lewati langkah ini. Flashing Firmware menggunakan Stlink-v2
1. Firmware yang kita pakai menggunakan firmware versi 0.5.4 maka download dulu file .elf pada [Link Berikut](https://docs.odriverobotics.com/releases/firmware) lalu pilih versi "ODrive v3.5-24V"
2. Sambungkan pin stlink 3,3v, gnd, swdio,swclk sesuai dengan yang ada di board
3. Buka STMCubeProgrammer lalu connect ke perangkat
4. pada “Memory & File edition”, terdapat tabs “Device memory” and “Open file”. klik “Open file” dan pilih file .elf tadi yang sudah didownload, lalu klik "Download"
5. Disconnect dan odrive sudah selesai di flash
