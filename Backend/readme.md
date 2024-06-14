# INSTALASI BACKEND EXPRESS SIGN

### CLONE REPOSITORY
Setelah folder backend berada di local direktory anda, silahkan cd backend.

### SET UP ENVIRONTMENT VARIABLES
Buat file .env, lalu buat variables yang akan dibutuhkan seperti ini :
#express server config
PORT=8080
HOST=localhost
HOST_URL=http://localhost:8080
#firebase database config
API_KEY=YOUR_API_KEY
AUTH_DOMAIN=YOUR_AUTH_DOMAIN
DATABASE_URL=YOUR_DB_URL
PROJECT_ID=YOUR_PROJECT_ID
STORAGE_BUCKET=YOUR_STORAGE_BUCKET_URL
MESSAGING_SENDER_ID=YOUR_MSG_SENDER_ID
APP_ID=YOUR_APP_ID

### SET UP FIREBASE
Buat project firebase lalu unduh serviceAccountKey.json dan letakkan di direktori backend

### SPLIT TERMINAL
Buat 2 terminal, lalu salah satu terminal tersebut jalankan perintah cd ML

### masukkan model ml kalian di direktori ML
Setelah model ml di masukkan, bukan app.py lalu ubah nama path model sesuai dengan keinginan kalian.

### jalankan flask server
jalankan perintah python app.py di terminal ML

### NPM INSTALL
Di terminal lain, jalankan NPM install

### KONFIGURASI URL ENDPOINT FLASK KE NODE.JS
Pada file signLanguange.js dan expression.js, di bagian call flask server ganti url nya (jika masih localhost, ganti dengan localhost 3000/nama endpoint di app flask)

### JALANKAN API SERVICES
Jalankan perintah npm run api-services

## Dokumentasi Endpoint
Untuk melihat dokumentasi dan cara tes api nya, silahkan cek [disini](https://documenter.getpostman.com/view/33504216/2sA3QtfBwL)
