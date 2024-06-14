# INSTALASI BACKEND EXPRESS SIGN

### 1. CLONE REPOSITORY
Setelah folder backend berada di local direktory anda, silahkan cd backend.

### 2. SET UP ENVIRONTMENT VARIABLES
<p>Buat file .env, lalu buat variables yang akan dibutuhkan seperti ini :</p>
<p>#express server config</p>
<p>PORT=8080</p>
<p>HOST=localhost</p>
<p>HOST_URL=http://localhost:8080</p>
<p>#firebase database config</p>
<p>API_KEY=YOUR_API_KEY</p>
<p>AUTH_DOMAIN=YOUR_AUTH_DOMAIN</p>
<p>DATABASE_URL=YOUR_DB_URL</p>
<p>PROJECT_ID=YOUR_PROJECT_ID</p>
<p>STORAGE_BUCKET=YOUR_STORAGE_BUCKET_URL</p>
<p>MESSAGING_SENDER_ID=YOUR_MSG_SENDER_ID</p>
<p>APP_ID=YOUR_APP_ID</p>

### 3. SET UP FIREBASE
Buat project firebase lalu unduh serviceAccountKey.json dan letakkan di direktori backend

### 4. SPLIT TERMINAL
Buat 2 terminal, lalu salah satu terminal tersebut jalankan perintah cd ML

### 5. MASUKKAN MODEL ML KE DIREKTORI ML
Setelah model ml di masukkan, bukan app.py lalu ubah nama path model sesuai dengan keinginan kalian.

### 6. JALANKAN FLASK SERVER
jalankan perintah python app.py di terminal ML

### 7. NPM INSTALL
Di terminal lain, jalankan NPM install

### 8. KONFIGURASI URL ENDPOINT FLASK KE NODE.JS
Pada file signLanguange.js dan expression.js, di bagian call flask server ganti url nya (jika masih localhost, ganti dengan localhost 3000/nama endpoint di app flask)

### 9. JALANKAN API SERVICES
Jalankan perintah npm run api-services

## 10. Dokumentasi Endpoint
Untuk melihat dokumentasi dan cara tes api nya, silahkan cek [disini](https://documenter.getpostman.com/view/33504216/2sA3QtfBwL)
