# Materi Belajar Digital Twin

Kurikulum, modul pelatihan, dan bahan riset yang diterbitkan **Pokja 3 IDTC** — terbuka untuk
dipakai ulang siapa pun dengan atribusi.

> **Repo ini baru dimulai.** Belum ada modul yang terbit. Cara kerja penyusunannya ada di
> [`pokja3-handbook`](https://github.com/idtc-id/pokja3-handbook).

## Jalur belajar

| Jalur | Sasaran | Modul tersedia |
|---|---|---|
| **A — Pengambil keputusan** | Pimpinan instansi, perencana, pejabat pengadaan | 0 |
| **B — Praktisi data & spasial** | Staf GIS, BIM, IT | 0 |
| **C — Pengembang & arsitek sistem** | Pengembang perangkat lunak, arsitek solusi | 0 |

Rincian jalur: [`pokja3-handbook/docs/03-program-pembelajaran.md`](https://github.com/idtc-id/pokja3-handbook/blob/main/docs/03-program-pembelajaran.md).

## Daftar modul

| Kode | Judul | Jalur | Tingkat | Versi | Status |
|---|---|---|---|---|---|
| — | *(belum ada)* | | | | |

## Status modul

| Status | Arti |
|---|---|
| **Rencana** | Sudah masuk kurikulum, materinya belum mulai disusun |
| **Draf** | Masih disusun |
| **Siap uji** | Bisa dipakai, belum pernah dibawakan |
| **Teruji** | Sudah dibawakan minimal satu kali dan direvisi dari umpan balik |
| **Ditinjau ulang** | Sedang diperbarui |
| **Arsip** | Tidak dipakai lagi; tetap bisa diakses |

## Struktur folder

```
kurikulum/     Silabus per jalur belajar dan peta kompetensi
modul/         Modul pelatihan, satu folder per modul
riset/         Daftar kebutuhan riset dan hasil kajian
template/      Template penulisan modul dan silabus
```

## Penomoran kode modul

```
DT-M-<jalur><nomor>
```

Contoh: `DT-M-B03` = modul ketiga pada jalur B.

## Menyumbang materi

1. Pastikan programnya sudah disetujui lewat issue di
   [`pokja3-handbook`](https://github.com/idtc-id/pokja3-handbook/issues).
2. Buat branch `modul/<kode>-<slug>`.
3. Salin [template modul](template/modul-pelatihan.md) ke `modul/<kode>-<slug>/README.md`.
4. Buka Pull Request berlabel `dokumentasi`.

Perbaikan kecil (typo, tautan rusak, contoh tambahan) boleh langsung lewat PR tanpa issue.

> **Jangan lupa situs.** Section *Materi Belajar* di [idtc-id.github.io](https://idtc-id.github.io/#materi)
> dibaca dari berkas `data/materi.json` pada repo
> [`idtc-id.github.io`](https://github.com/idtc-id/idtc-id.github.io). Saat sebuah modul terbit,
> perbarui `status` dan isi `tautan` modul tersebut di sana agar ikut tampil di situs.

## Aturan penting

- **Jangan mengunggah data pribadi peserta.** Nama, email, nomor kontak, dan daftar hadir
  disimpan Sekretariatan, bukan di repo ini.
- **Rekaman video** disimpan di kanal video IDTC — di sini cukup tautannya.
- **Dataset latihan** maksimal 50 MB. Dataset besar simpan di storage, catat tautannya.
- **Materi pihak ketiga** hanya boleh dimuat ulang bila lisensinya mengizinkan. Bila tidak,
  cukup tautkan sumbernya.

## Cara menyitir

```
Indonesia Digital Twin Community, Pokja 3. (TAHUN).
<Judul Modul>, versi <x.y>. Jakarta: IDTC.
Tersedia di: https://github.com/idtc-id/materi-belajar
```

## Lisensi

Materi: **CC BY 4.0**. Contoh kode dan notebook: **MIT**. Lihat [LICENSE.md](LICENSE.md).
