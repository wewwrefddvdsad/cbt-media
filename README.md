# cbt-media — gambar soal CBT Sekolah

Repo ini **harus PUBLIK**. Gambar yang diunggah guru dari aplikasi CBT disimpan otomatis di folder
`img/<tahun>/<bulan>/` dan ditampilkan ke siswa lewat CDN jsDelivr
(`https://cdn.jsdelivr.net/gh/<akun>/cbt-media@<commit>/img/...`).

- Jangan menghapus atau memindahkan file di `img/`: soal yang memakainya akan kehilangan gambar.
- Jangan menaruh kunci jawaban atau data siswa di repo ini, karena semua orang bisa melihatnya.
- Token GitHub untuk aplikasi perlu izin **Contents: Read and write** pada repo ini.
