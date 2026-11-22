# stashly-web

Situs Stashly: halaman utama, Kebijakan Privasi, dan Ketentuan Layanan. HTML dan CSS statis, tanpa proses build.

Semua tautan di dalamnya relatif, jadi situs ini jalan di alamat mana pun, termasuk `https://fauzi.is-a.dev/stashly/`.

## Menayangkan di GitHub Pages

Agar alamatnya `fauzi.is-a.dev/stashly`, nama repositorinya harus `stashly` dan berada di akun yang sama dengan situs `fauzi.is-a.dev`.

1. Buat repositori bernama `stashly`, lalu unggah isi folder ini ke cabang `main`.
2. Di Settings, Pages: Source "Deploy from a branch", Branch `main`, folder `/ (root)`.
3. Tunggu sampai terbit, lalu buka `https://fauzi.is-a.dev/stashly/`.

Berkas `.nojekyll` membuat GitHub Pages menayangkan berkas apa adanya.

## Melihat di komputer

    python3 -m http.server 8000

lalu buka `http://localhost:8000/`.
