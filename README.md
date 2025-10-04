
# Crypto Price Notifier Bot

Bot Telegram untuk memantau harga cryptocurrency secara real-time dan memberikan notifikasi cepat.  
Saat ini mendukung: Bitcoin (BTC) dalam USD, tapi bisa dikembangkan untuk crypto lain.

## **Fitur**
- `/start` → Memulai bot dan menampilkan info dasar.  
- `/price` → Mengecek harga crypto saat ini.  
- Mudah dikembangkan untuk multiple crypto dan notifikasi otomatis.  

## **Instalasi & Setup**
1. Clone repo:
```bash
git clone https://github.com/username/my-coding-projects.git
cd my-coding-projects/scripts/bot-telegram
````

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Dapatkan **Telegram Bot Token** dari [BotFather](https://t.me/BotFather).

4. Ganti konfigurasi di `main.py`:

```python
TOKEN = "YOUR_TELEGRAM_BOT_TOKEN"
CHAT_ID = "YOUR_CHAT_ID"  # Bisa chat pribadi untuk testing
CRYPTO = "bitcoin"
CURRENCY = "usd"
```

---

## **Cara Menjalankan**

```bash
python main.py
```

Di Telegram, kirim:

* `/start` → Memulai bot
* `/price` → Mengecek harga Bitcoin saat ini

---

## **Pengembangan Selanjutnya**

* Tambahkan crypto lain (ETH, DOGE, dll).
* Notifikasi otomatis saat harga naik/turun sesuai threshold.
* Inline keyboard untuk memilih crypto.
* Deploy ke server agar bot selalu online (VPS, Railway, Heroku, dsb).

---

## **Lisensi**

Apache2 License

