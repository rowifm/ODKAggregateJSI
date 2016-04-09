# FORMULIR SURAT KETERANGAN LULUS TA

Proyek ini merupakan salah satu gagasan untuk mengurangi peredaran kertas pada sebuah jurusan di kampus ternama yang berada di Surabaya. Formulir ini berguna ketika mahasiswa tahun akhir telah selesai melaksanakan Tugas Akhir, namun belum memiliki ijazah sebagai tanda bukti kelulusan.

Proyek ini menggunakan ODKAggregate sebagai platform pengumpul data, MySQL sebagai database, dan Microsoft Word untuk menggunakan fitur mail merge agar dapat langsung digunakan ketika membuat dokumen. Berkat ODKAggregate, data tidak hanya dapat disubmit melalui web, namun juga dapat menggunakan Android untuk mengisi form.

## Kontributor
Rowi Fajar Muhammad &
Ramadhan Erry Pranata

## Struktur File

| -- README.md

| -- LICENSE

| -- form

## Penggunaan
### Persyaratan
1. ODKAggregate telah terinstall diserver yang siap digunakan. Untuk panduan instalasi dapat mencari sumber lain
2. Memiliki file .xml yang siap diupload
3. Untuk menggunakan fitur mail merge, dibutuhkan ODBC Connector ke MySQL sebagai penyambung ke database
4. ODKAggregate.apk dibutuhkan untuk diinstalasi di Android sebagai client
5. Pastikan hak akses kedalam databse BUKAN root
6. Jangan terlalu sering main DoTA, kerjakan TA Anda. Hentikan sebelum terlambat

### Tata Cara
1. Upload file .xml yang ada di folder form kedalam ODKAggregate
2. Setelah itu, install aplikasi ODKAggregate.apk ke Android yang ada di folder application
3. Pada Android, pilih Get Blank Form, lalu pilihlah form yang sesuai
4. Setelah itu, pilih fill blank form dan isilah sesuai format yang ada
5. Send form and voila!
6. Untuk staf/karyawan yang mengurus,  cukup setting ODBC kepada database Anda, lalu setup mail merge kepada database ODKAggregate

### Version
0.1 