# Perubahan Muzik

Tulis versi terbaru di ATAS. Format tajuk: `## v2.0.0` (nombor sama seperti dalam version.properties).
Perubahan kecil ditulis dengan awalan [bina N].

## v2.11.0
- Ikon app baharu: fon kepala putih pada latar merah, termasuk ikon adaptif untuk Android 8 ke atas dan ikon bertema untuk Android 13 ke atas.
- Halaman Tetapan disusun semula dalam kumpulan kad yang kemas: Paparan, Lirik, Pemainan, Perpustakaan dan Data. Tetapan lirik dikumpulkan di satu tempat.
- Baris tetapan seragam: label di kiri, nilai di kanan, penerangan ringkas di bawah suis.

## v2.10.0
- Sumber lirik dengan masa gaya Apple Music: Apple Music (Paxsenix) dengan masa suku kata, dan BetterLyrics (TTML Apple Music) dengan masa perkataan. Kedua-duanya diletakkan di hadapan senarai.
- SimpMusic dibuang kerana ia hanya boleh dicari menggunakan ID video YouTube, jadi tidak sesuai untuk lagu dalam telefon.
- Butang baharu Uji semua sumber di Tetapan, Sumber lirik. Ia menguji setiap sumber dengan satu lagu terkenal dan menunjukkan Berfungsi atau Gagal. Butang Matikan sumber yang gagal mematikan sumber yang gagal.
- LRC.red dan Unison kini boleh membaca respons TTML selain LRC.
- Lirik TTML ditukar kepada masa perkataan secara automatik, termasuk menapis suara latar dan terjemahan.
- [bina 2] Dibetulkan: app memaparkan skrin kosong selepas kemas kini kerana senarai sumber lirik dimuatkan sebelum ia sedia. Kini dimuatkan pada masa yang betul.
- [bina 3] Tulisan lirik dikemaskan: ketebalan lalai dikurangkan kepada Sederhana. Tetapan baharu Ketebalan teks lirik (Nipis, Sederhana, Tebal).
- [bina 4] Tulisan lirik ditebalkan sedikit: ketebalan lalai kini Lebih tebal. Pilihan ketebalan kini Nipis, Sederhana, Tebal, Lebih tebal dan Paling tebal.

## v2.9.0
- Sumber lirik baharu: Musixmatch (carian, richsync dengan masa setiap perkataan, dan subtitle baris), LRC.red, SimpMusic dan Unison. Semua boleh disusun semula atau dimatikan di Tetapan, Sumber lirik.
- Lirik Musixmatch richsync menggunakan masa perkataan sebenar, jadi sapuan perkataan lebih tepat.
- Sumber baharu ditambah selepas sumber lama, jadi tidak mengganggu turutan sedia ada.
- Pencarian lirik membaca jawapan JSON secara fleksibel untuk LRC.red, SimpMusic dan Unison.
- [bina 2] Dibetulkan: sumber lirik yang dinyahtanda kini boleh dipilih semula (butang kini bulatan yang sentiasa boleh ditekan).

## v2.8.0
- Mini player baharu untuk notifikasi dan skrin kunci menggunakan sesi media Android: gambar album, tajuk, artis, bar kemajuan yang boleh diseret (Android 11 ke atas), dan butang menu, sebelumnya, main/jeda, seterusnya serta favorit.
- Rupa mengikut tema telefon (terang atau gelap) dan warna album secara automatik.
- Butang favorit dalam notifikasi disegerakkan dengan senarai Favorit dalam app.
- Butang fon kepala atau Bluetooth (main, jeda, seterusnya, sebelumnya) turut berfungsi melalui sesi media.
- Ikon butang notifikasi direka baharu dalam gaya pepejal (menu, sebelumnya, main, jeda, seterusnya, hati).

## v2.7.0
- Skrin player (tanpa lirik) kini berlatar warna album, sama seperti skrin lirik: latar kabur dengan teks dan butang putih.
- Bar status dan bar navigasi telefon mengikut warna album bila player dibuka dan kembali ke warna tema bila player ditutup.
- Warna diambil daripada bahagian atas dan bawah gambar album supaya sambungan dengan bar telefon licin.
- Jika gambar album dimatikan, warna dijana daripada nama lagu.

## v2.6.0
- Animasi lirik dibaharui ikut video rujukan: penyerlahan perkataan kini menyapu secara licin (bukan lompat), dengan tepi lembut.
- Tiga titik pemasaan muncul sebelum lirik bermula (intro) dan semasa bahagian instrumental. Titik menyala satu persatu mengikut masa dan mengecil sebelum baris seterusnya masuk.
- Skrol lirik berhenti pada titik semasa jeda, kemudian bergerak ke baris yang bermula.
- Animasi titik mengikut tetapan Kurangkan gerakan.

## v2.5.0
- Laras lirik: tekan label "Lirik oleh ..." atau menu tiga titik, kemudian Laras lirik. Boleh lewatkan atau awalkan lirik setiap 0.5 saat untuk setiap lagu (diingat).
- Paparan tempoh versi lirik berbanding lagu anda, untuk mengesan lirik versi lain.
- Butang Cuba sumber lirik lain jika lirik tidak sepadan.
- Padanan lirik lebih ketat: lirik dengan tempoh beza lebih 4 saat tidak diterima.
- Sokongan tag [offset:] dalam fail lirik.
- Tetapan baharu: Perkataan menyala satu persatu (boleh dimatikan supaya seluruh baris menyala serentak).
- [bina 2] Butang back dibetulkan: tutup menu/sheet dahulu, tunjuk semula kawalan bila lirik skrin penuh, tutup player, kembali ke skrin sebelumnya, dan tekan dua kali di Pustaka untuk keluar.
- [bina 3] Ketinggian dan kedudukan kawalan player (bar kemajuan, butang main, kelantangan, ikon bawah) diseragamkan antara mod lirik dan tanpa lirik.
- [bina 4] Gambar album di skrin player kekal saiz yang sama bila main atau jeda (tidak lagi mengecil semasa dijeda).

## v2.4.0
- Butang lirik di skrin sedang dimainkan dibetulkan: tidak lagi terpotong di bahagian bawah.
- Tetapan baharu: Latar lirik (album kabur atau hitam pekat).
- Tetapan baharu: Tunjuk gambar album, Tunjuk masa berbaki, Kurangkan gerakan.
- Tetapan baharu: Bilangan lagu dalam Paling kerap dimainkan (3, 6, 9 atau 12).
- Tetapan baharu: Hentikan muzik bila app disapu, Ulang lalai dan Rawak sebagai lalai.

## v2.3.0
- Tema baharu: Putih, Hitam atau Ikut sistem. Bar status dan bar navigasi turut berubah.
- Warna aksen boleh dipilih: Merah, Biru, Hijau, Oren atau Ungu.
- Saiz teks lirik: Kecil, Sederhana atau Besar.
- Pilihan tunjuk atau sorok label kualiti (format dan bitrate).
- Jeda muzik secara automatik bila fon kepala dicabut.
- Skrin kekal hidup semasa lirik dipaparkan (pilihan).
- Set semula bilangan main untuk senarai Paling kerap dimainkan.

## v2.2.0
- Menu baharu di Pustaka: Artis dan Album. Tekan artis atau album untuk lihat senarai lagunya.
- Lagu dalam album disusun mengikut nombor trek.

## v2.1.0
- Lirik bergerak ikut gaya Apple Music: baris aktif putih, perkataan menyala satu persatu, baris lain kabur mengikut jarak dan skrol sendiri mengikut lagu.
- Butang lirik di skrin sedang dimainkan. Latar belakang kabur ikut warna gambar album. Kawalan disorok selepas 5 saat dan muncul semula bila disentuh.
- Tekan baris lirik untuk lompat ke bahagian itu.
- Tetapan baharu: Sumber lirik (LRCLIB, NetEase Music, KuGou). Seret untuk susun turutan, tanda untuk hidup atau matikan, dan cache lirik supaya boleh dibaca tanpa internet.
- Menu tiga titik: tambah Lirik, Muat semula lirik dan Sumber lirik.
- Butang cast/output dibuang.
- [bina 2] Lirik tidak lagi kabur. Baris yang jauh hanya semakin malap.

## v2.0.0
- Skrin sedang dimainkan direka semula ikut gaya Apple Music: tajuk berfon serif, butang bintang (Favorit) dan butang tiga titik di sebelah tajuk.
- Label format dan kualiti di bawah bar kemajuan (contoh MP3 - 320 kbps, FLAC - Lossless).
- Slider kelantangan dan butang bawah: Info lagu, Peranti output dan Giliran seterusnya.
- Menu tiga titik: Favorit, Tambah ke playlist, Info lagu, Cari lagu artis, Rawak, Ulang, Kelajuan main, Pemasa tidur, Kongsi lagu dan Sorok lagu.
- Menu tekan lama: tambah Main seterusnya dan Tambah ke giliran.
- Ikon Favorit ditukar daripada hati kepada bintang.

## v1.3.0
- Tetapan baharu: Sorok lagu pendek (tiada, 15, 30, 60, 90, 120 saat atau tersuai). Nilai awal 30 saat.
- Tetapan baharu: Folder lagu, hidup atau matikan folder yang dipaparkan.
- Tetapan baharu: Urus lagu, sorok atau tunjuk lagu satu persatu dengan suis.
- Menu tekan lama: tambah pilihan Sorok lagu.
- [bina 2] Nota perubahan ini kini dipaparkan pada setiap Release di GitHub.

## v1.2.0
- Pustaka memaparkan lagu paling kerap dimainkan.
- Menu baharu: Favorit dan Playlist (buat, tambah lagu, buang lagu, padam playlist).
- Tekan lama pada lagu: Favorit, Tambah ke playlist, Info lagu.
- Butang hati pada skrin sedang dimainkan.

## v1.1.0
- Menu susun lagu: A-Z, Z-A, Terbaru-Lama, Lama-Terbaru.
- Gambar album dipaparkan dalam senarai, mini player dan skrin sedang dimainkan.

## v1.0.0
- Keluaran pertama: pemain muzik luar talian untuk lagu dalam telefon.
- Imbas lagu automatik, main di latar belakang dengan notifikasi.
- Pustaka, Lagu, Cari dan Tetapan, rekaan bergaya Apple Music.
