# Osananajimi ni Kage de Tsugou no Yoi Otoko Yobawari Sareta Ore wa, Koui wo Risetto Shite Futsuu ni Seishun o Okuritai

> Hari itu, Toudou Tsuyoshi nge-'reset' semua perasaan yang selama ini dia tujukan ke teman masa kecilnya, Hanazono Hana. Dengan canggung tapi tetap ngotot pengen ngerasain masa muda yang 'normal',

---

## Info

| | |
|---|---|
| Judul | Osananajimi ni Kage de Tsugou no Yoi Otoko Yobawari Sareta Ore wa, Koui wo Risetto Shite Futsuu ni Seishun o Okuritai |
| Judul Alternatif | 幼馴染に陰で都合の良い男呼ばわりされた俺は、好意をリセットして普通に青春を送りたい |
| Author | Nora Usagi |
| Artist | ReTake |
| Tipe | Manga (Hitam Putih) |
| Genre | Comedy · Romance · School Life · Slice of Life · Shounen · Drama |

## Link

- [Raw](https://www.manga-up.com/titles/1680)

---

## Struktur

```
Osananajimi/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)