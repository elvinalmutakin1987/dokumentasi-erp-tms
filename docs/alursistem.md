# Alur Sistem

Sistem yang dibangun ini dirancang berdasarkan alur dan prosedur yang berlaku dalam proses bisnis di PT. Tunas Mitra Sejati, dengan tujuan untuk meningkatkan efisiensi dan efektivitas operasional perusahaan. Sistem ini mencakup berbagai fungsi yang mendukung kelancaran berbagai aktivitas perusahaan, yang masing-masing dikelola oleh modul-modul tertentu.

Terdapat 5 modul utama dalam sistem ini, yang masing-masing memiliki peran penting dalam menangani dan mengelola berbagai proses bisnis yang ada. Modul-modul ini dirancang untuk saling terintegrasi, sehingga dapat mendukung proses bisnis secara menyeluruh, mulai dari tahap perencanaan, pelaksanaan, hingga evaluasi, dengan memanfaatkan teknologi untuk mempermudah pekerjaan dan memastikan hasil yang optimal.

## 1. Equipment

### 1.1 Daily Report

![](/assets/images/flowchart-dailyreport.png)

Proses dimulai dengan pengiriman laporan yang dilakukan oleh pengirim melalui WhatsApp (WA). Laporan ini mencakup berbagai informasi yang perlu direkap.

- Setelah laporan diterima via WA, langkah selanjutnya adalah merekap data yang ada dalam laporan tersebut.
- Salah satu komponen laporan yang direkap adalah informasi mengenai **kilometer** yang telah ditempuh.
- Laporan juga mencatat penggunaan **bahan bakar** atau fuel.
- Informasi mengenai **waktu kerusakan (break down)** juga harus direkap.
- Data mengenai **total beban (load)** yang dibawa juga dihitung dan dicatat dalam laporan.

Setelah semua laporan tersebut direkap, data akan dikelompokkan dan bisa digunakan untuk analisis lebih lanjut atau pelaporan.

### 1.2 Repair & Maintenance

![](/assets/images/flowchart-repair.png)

Proses dimulai dengan pengiriman laporan yang berisi informasi yang perlu ditindaklanjuti, biasanya terkait dengan **kerusakan** atau kebutuhan **perbaikan**.

- Langkah pertama adalah menindaklanjuti laporan tersebut untuk menentukan apakah perbaikan diperlukan dan apakah spare part perlu dibeli.
- Jika spare part perlu dibeli, proses dilanjutkan untuk membeli spare part. Jika tidak, perbaikan langsung dilakukan.
- Permintaan pembelian spare part akan dibuat via WA dan diproses lebih lanjut untuk pengadaan spare part.
- Setelah barang diterima, perbaikan dapat dilakukan dan laporan perbaikan dikirimkan via WA untuk memberikan pembaruan.
- Dokumen penerimaan barang akan dilampirkan untuk memastikan bahwa barang yang diterima tercatat dengan baik.

Saat ini, **dokumen penerimaan barang** akan dibuatkan untuk memastikan setiap penerimaan tercatat dengan baik.

## 2. Procurement

![](/assets/images/flowchart-po.png)

Proses dimulai dengan pembuatan **permintaan barang** oleh departemen yang membutuhkan barang.

- Setelah permintaan dibuat, langkah selanjutnya adalah meminta **penawaran vendor** untuk barang yang dibutuhkan.
- Setelah penawaran diterima, langkah berikutnya adalah membuat **Purchase Order (PO)** yang merupakan dokumen resmi untuk memesan barang.
- Setelah PO disetujui, vendor akan mengirimkan barang sesuai dengan pesanan.
- Di akhir proses, **Purchase Order** diterbitkan sebagai bukti transaksi yang sah dan dasar pengiriman barang.

## 3. Survey

![](/assets/images/flowchart-survey.png)

Proses dimulai dengan penerbitan **sertifikat survey** sebagai dokumen resmi yang menyatakan pekerjaan telah selesai sesuai dengan ketentuan.

- Setelah sertifikat diterbitkan, dilakukan **rekonsiliasi volume** untuk memastikan bahwa volume pekerjaan yang tercatat sesuai dengan hasil survey.
- Jika ada kesepakatan, maka dilanjutkan dengan membuat **progress claim** untuk mengajukan pembayaran berdasarkan kemajuan pekerjaan.
- **Invoice** akan diproses berdasarkan klaim yang diajukan dan sertifikat survey yang telah disetujui.

## 4. Finance

![](/assets/images/flowchart-penerbitan-cic.png)

Proses dimulai dengan merekap **waktu down time** untuk mengetahui estimasi biaya yang akan dihitung.

- Setelah waktu down time direkap, **proforma invoice** dikirimkan kepada **KPC** (klien) untuk menampilkan estimasi biaya.
- Setelah itu, dilakukan pengecekan dan perbaikan data pada proforma invoice jika diperlukan.
- Jika data sudah benar, **request CIC** (Cost Invoice Confirmation) dikirim untuk verifikasi biaya.
- Setelah konfirmasi diterima, **invoice resmi** diproses untuk pembayaran.

## 5. Safety

![](/assets/images/flowchart-safety.png)

Proses dimulai dengan pembaruan tanggal **kadaluarsa** unit.

- Setelah tanggal kadaluarsa diperbarui, langkah selanjutnya adalah mempersiapkan **dokumen perpanjangan** unit.
- Sistem akan mengirimkan **notifikasi WA** kepada pihak terkait mengenai unit yang telah expired.
- Jika tidak ada notifikasi, maka sistem akan dibuat untuk mengirimkan pemberitahuan yang diperlukan untuk memperpanjang unit.
