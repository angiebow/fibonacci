Cara menggunakan project ini.
1 pastikan sudah ada php dan composer terinstall
2 clone repo ini
```bash
git clone <URL_REPOSITORY> pbkk_24
```
3 install dependency
```bash
composer install
```
4 ganti / copy file .env.example menjadi .env
5 tambahkan database.sqlite pada folder /database
6 jalankan perintah php artisan migrate
7 jalankan perintah php artisan key:generate
8 jalankan perintah php artisan serve untuk memulai
