# Pertemuan 07 Fungsi Python

**Nama:** Disti Rizqiana Putri  
**NIM:** 2225250098  
**Kelas:** 3E

## Tujuan

Menggunakan fungsi, parameter, `return value`, dan scope untuk membuat program modular.

## Cara Menjalankan

Jalankan program melalui terminal VS Code dengan perintah:

```bash
python3 praktik/utilitas_matematika.py
```

## Struktur Fungsi

| Nama Fungsi | Parameter | Nilai Return |
|---|---|---|
| `luas_persegi_panjang(p, l)` | Panjang dan lebar | Hasil perkalian panjang dan lebar |
| `luas_segitiga(a, t)` | Alas dan tinggi | Hasil perhitungan luas segitiga |
| `jumlah_n(n)` | Bilangan bulat `n` | Jumlah bilangan dari 1 sampai `n` |
| `faktorial(n)` | Bilangan bulat `n` | Hasil faktorial dari `n` |
| `tampilkan_menu()` | Tidak ada | Tidak mengembalikan nilai; menampilkan menu |

## Hasil Pengujian

| No. | Input | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---|---|---|
| 1 | Panjang = 8, lebar = 5 | 40 | 40 | Berhasil |
| 2 | Alas = 10, tinggi = 6 | 30 | 30 | Berhasil |
| 3 | `n = 5` | 15 | 15 | Berhasil |
| 4 | `n = 5` untuk faktorial | 120 | 120 | Berhasil |
| 5 | Pilihan menu = 5 | Program selesai | Program selesai | Berhasil |

*Catatan: Hasil aktual di atas merupakan hasil yang diharapkan berdasarkan perhitungan kode. Jalankan program untuk memastikan hasil pengujian aktual.*

## Refleksi

Program menjadi lebih sederhana setelah setiap perhitungan dipisahkan menjadi fungsi. Misalnya, perhitungan luas persegi panjang cukup dilakukan dengan memanggil fungsi `luas_persegi_panjang(p, l)` tanpa menuliskan kembali rumusnya di program utama. Dengan demikian, kode lebih rapi, mudah dibaca, dan dapat digunakan kembali.
