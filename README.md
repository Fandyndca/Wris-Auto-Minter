
WRIS Auto Minter

English and Bahasa Indonesia Tutorial



## English

Download mint.js from this repository, then open it with Notepad or another Text Editor.

Modify the following sections according to your Private Key and Address.
- YOUR_PRIVATE_KEY
- YOUR_ADDRESS
SKIP this part if you are using Android, as it will be explained below.
### Steps for Windows

1. Download and install NodeJS.
    https://nodejs.org/en/download/current
2. Download the mint.js file from this repository.
3. Create a new directory named "MINT," then move the mint.js file to that directory.
4. Open CMD in that new directory. 
```
cd C:\Users\User\Desktop\MINT
```
5. Run the command "npm init" and press ENTER until it's done.
6. Run the command "npm install web3" and wait until it's done.
7. Finally, run the command "node mint.js."
### Steps for Android

1. Download Termux from F-Droid.
   ```
   https://f-droid.org/id/packages/com.termux/
   ```
2. Open Termux and run the command "pkg update && pkg upgrade."
3. After it's done, install NodeJS, Wget and Nano
   ```
   pkg install nodejs
   pkg install wget
   pkg install nano
   ```
4. Run the command:
   ```
   wget -O mint.js https://github.com/AganFebro/ETCX-Auto-Minter/raw/main/mint.js
   ```
5. Run the command:
   ```
   npm install web3
   ```
7. Run the command:
   ```
   npm init
   ```
8. Open the mint.js file:
   ```
   nano mint.js
   ```
9. Modify YOUR_PRIVATE_KEY and YOUR_ADDRESS according to yours.
10. Once done, Save by pressing Ctrl + X, then Y, and finally Enter.
11. Finally, run the command:
    ```
    node mint.js
    ```
## Bahasa Indonesia

Download mint.js dari repositori ini lalu buka dengan Notepad atau Text Editor lainnya.
Ubah bagian dibawah sesuai dengan Private Key dan Address-mu.
- YOUR_PRIVATE_KEY
- YOUR_ADDRESS
SKIP Bagian ini jika pake Android karena akan dijelaskan di bawah.
### Langkah Langkah untuk Windows

1. Download dan instal NodeJS.
   ```
   https://nodejs.org/en/download/current
   ```
2. Download file mint.js dari repositori ini.
3. Buat direktori baru bernama "MINT", lalu pindahkan file mint.js ke direktori tersebut.
4. Buka CMD direktori baru tersebut
   ```
   cd C:\Users\User\Desktop\MINT
   ```
5. Jalankan perintah "npm init" tekan ENTER hingga selesai.
6. Jalankan perintah "npm install web3" tunggu hingga selesai.
7. Terakhir, jalankan perintah "node mint.js".
### Langkah Langkah untuk Android

1. Download Termux dari F-Droid.
   ```
   https://f-droid.org/id/packages/com.termux/
   ```
2. Buka Termux lalu jalankan perintah
   ```
   pkg update && pkg upgrade
   ```
3. Setelah selesai lalu instal NodeJS, Wget dan Nano
   ```
   pkg install nodejs
   pkg install wget
   pkg install nano
   ```
4. Jalankan perintah
   ```
   wget -O mint.js https://github.com/AganFebro/ETCX-Auto-Minter/raw/main/mint.js
   ```
5. Jalankan perintah
   ```
   npm install web3
   ```
6. Jalankan perintah
   ```
   npm init
   ```
7. Buka file mint.js
   ```
   nano mint.js
   ```
8.. Ubah YOUR_PRIVATE_KEY dan YOUR_ADDRESS sesuai dengan milikmu.
9.. Jika sudah maka Save dengan klik tombol Ctrl + X lalu Y dan terakhir Enter.
10. Terakhir, jalankan perintah
    ```
    node mint.js
    ```
