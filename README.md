# Docker Sample untuk Pemula

Dua app kecil, masing-masing punya `Dockerfile` dan `docker-compose.yml` sendiri.

| Folder       | Isi                     | URL                   |
|--------------|-------------------------|-----------------------|
| `web-static` | HTML + CSS (Nginx)      | http://ipvm:8080 |
| `web-flask`  | Python Flask            | http://ipvm:5000 |

## Cara menjalankan

```bash
cd web-static atau cd web-flask
docker compose up -d --build
```

Hentikan dengan `Ctrl+C`, lalu bersihkan:

```bash
docker compose down -v
```

## Perintah yang berguna

```bash
docker compose up -d      # jalan di background
docker compose ps         # lihat container yang aktif
docker compose logs       # lihat log
docker compose down       # stop & hapus container
```
