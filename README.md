# İlk Adım

```bash
cp env.example .env
```

Bu kısımdan "phpmyadmin" ayarlarını yönet.

## İkinci Adım

```bash
docker-compose up
```
Docker ayağa kalktıktan sonra,
```
wp-app - wp-data
```
Wordpress'i yöneteceğiniz, configure edeceğiniz kısım.


## First Start

```bash
docker-compose start
```
Komutu ile Localhost default adresinden çıktıyı görebilirsiniz.
```bash
docker-compose stop
```
Komutu ile container'ları durdurabilirsiniz.

## Database Dumps
```bash
./export.sh
```
Komutu ile Database Dump oluşturabilirsiniz.

## Database

`http://127.0.0.1:8080` ile phpmyadmin kısmına giriş yapabilirsiniz.
Default kullanıcı adı `root`
Şifreyi değiştirmek için `.env` klasörünü kullanınız.

### Author: Can Çetin

