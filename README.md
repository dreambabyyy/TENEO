# Teneo Community Node BOT
Teneo Community Node BOT

Download Extension Here : [Teneo Community Node](https://chromewebstore.google.com/detail/teneo-community-node/emcclcoaglgcpoognfiggmhnhgabppkm) | Use Code : F5mxY

## Fitur

  - Auto Get Account Information
  - Auto Run With Auto Proxy if u Choose 1 [Use [Monosans Proxy](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt)]
  - Auto Run With Manual Proxy if u Choose 2 [Paste Ur personal proxy in manual_proxy.txt]
  - Auto Run Without Proxy if u Choose 3
  - Auto Connect Node and Send Ping
  - Auto Receive Message Every 15 Minutes
  - Multi Accounts With Threads

## Prasyarat

Pastikan Anda telah menginstal Python3.9 dan PIP.

## Instalasi

1. **Kloning repositori:**
   ```bash
      https://github.com/dreambabyyy/TENEO.git
   ```
   ```bash
   cd TENEO
   ```

2. **Instal Requirements:**
   ```bash
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```

## Konfigurasi

- **accounts.json:** Anda akan menemukan file `accounts.json` di dalam direktori proyek. Pastikan `accounts.json` berisi data yang sesuai dengan format yang diharapkan oleh skrip. Berikut adalah contoh format file:

  ```bash
    [
        {
            "Email": "your_email_address 1",
            "Password": "your_password 1"
        },
        {
            "Email": "your_email_address 2",
            "Password": "your_password 2"
        }
    ]
  ```
- **manual_proxy.txt:** Anda akan menemukan file `manual_proxy.txt` di dalam direktori proyek. Pastikan `manual_proxy.txt` berisi data yang sesuai dengan format yang diharapkan oleh skrip. Berikut adalah contoh format file:
  ```bash
    ip:port #http or socks5 - change schemes in line 100
    http://ip:port
    socks4://ip:port
    socks5://ip:port
    http://ip:port@user:pass #idk its work or not, cuase i don't have authentic proxy
    socks4://ip:port@user:pass #idk its work or not, cuase i don't have authentic proxy
    socks5://ip:port@user:pass #idk its work or not, cuase i don't have authentic proxy
  ```

## Jalankan

```bash
python bot.py #or python3 bot.py
```

## My Channel Tele Super BianzZz

  https://t.me/superbianz
