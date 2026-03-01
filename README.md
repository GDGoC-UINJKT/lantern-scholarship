## Lantern Scholarship

Malam itu, panitia beasiswa **Lantern Scholarship** bersiap mengumumkan penerima. Semua data kandidat sudah terkunci rapi di portal internal. Namun tepat **11 menit** sebelum pengumuman, portal tiba-tiba masuk mode *maintenance* singkat—lalu kembali normal seperti tidak terjadi apa-apa.

Keesokan paginya, muncul masalah aneh: beberapa mahasiswa melapor menerima email *“Selamat, Anda diterima!”* padahal mereka tidak pernah mendaftar. Sebaliknya, kandidat yang seharusnya lolos justru tidak muncul namanya di pengumuman.

Tim ops melakukan audit cepat dan menemukan pola akses yang tidak wajar: ada request berulang, rapi, dan **mengubah angka di URL**—seolah-olah seseorang sedang “membuka lemari arsip” berdasarkan nomor rak.

Lebih mencurigakan lagi, beberapa catatan internal tampaknya **disembunyikan dari mesin pencari** agar tidak terlihat publik. Panitia yakin: jika kamu bisa menemukan catatan tersebut, kamu akan paham celah apa yang dimanfaatkan.

Kamu diminta membantu sebagai investigator eksternal untuk memverifikasi kebocoran dan menemukan bukti paling kuat: **Recipient Ledger** — data penerima beasiswa yang seharusnya hanya bisa diakses admin.

Di dalam ledger itulah terdapat **kunci** yang dicari.

Ini adalah link portal: [Lantern Scholarship](lantern-scholarship.netlify.app)

---

### Objektif
Temukan **flag** dengan format: `GDGOC{...}`

---

### Rules!
- Ini simulasi untuk edukasi & kompetisi.
- Tidak perlu brute force / spam request.
- Browser + DevTools (Network tab) sudah cukup.
- Fokus hanya pada target yang disediakan.
