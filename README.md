# ERD-SiPPBENTOR
Pada tugas ini, akan dibuat Entity Relationship Diagram (ERD) dari SiPPBENTOR 
(Sistem  Pelayanan  dan  Perawatan  Bengkel  Motor)  dan  juga  menjelaskan  kardinalitas 
antar  entitas  dan  atribut  didalamnya.  Bengkel  motor  Annas  merupakan  bengkel  motor 
yang sedang berkembang  dikawasan Surabaya timur. Untuk otomasi dan memudahkan 
pelayanan  dan  pendataan  terkait  perawatan  motor  pelanggan,  maka  akan  dibuat  suatu 
system  informasi  sederhana.    Bengkel  tersebut  melayani  perawatan  dan  service  motor 
dari berbagai pabrikan, seperti  Honda, Yamaha, Suzuki dan lain-lain. Bengkel tersebut 
memilik seorang Front Office, bagian barang, kasir serta beberapa montir. Bagian barang 
akan melayani apabila ada pelanggan yang hanya membeli spare part Proses pelayanan 
selama ini masih manual, pelanggan yang datang akan dilayani oleh FO,  dan ditanyakan 
keperluannya apa, sekedar membeli sparepart/service kendaraan. Jika melakukan 
pembelian,  maka  FO  menyuruh  ke  bagian  barang  untuk  mengambilkan  barang  yang 
dibeli  dan  pelanggan  membayar  di  kasir.  Kasir  menginputkan  barang  yang  dibeli  ke 
system dan menginformasikan total yang harus dibayar oleh pelanggan. Jika pelanggan 
akan  melakukan  perawatan  kendaraanya,  FO  akan  memberikan  beberapa  pertanyaan, 
missal kendaraan pernah dibawa ke bengkel ini apat tidak, jika pernah dulu  melakukan 
perawatan apa, dll, sekarang keluhannya apa. Setelah didata keluhannya, FO 
memerintahkan  montir  untuk  mengerjakannya. 
Jika  tidak  ada  antrian,  kendaraan  akan 
segera ditangani oleh montir. Tapi jika ada antrian harus menunggu.  Jika ada sparepart 
yang harus diganti, maka montir akan minta persetujuan ke pelanggan, apabila pelanggan 
setuju, montir akan minta barang ke bagian barang. Bagian barang akan mencatat nama 
montirnya  serta  sparepart  apa  yang  diminta.  Setelah  selesai,  montir  akan  melaporkan 
pekerjaannya di bagian kasir, selanjutnya kasir akan menulis jenis perbaikan, spare part 
yang diganti berserta harganya, ongkos perbaikan dan total ongkos yang harus dibayarkan 
oleh pelanggan. 
Sistem yang akan dikembangkan harus bisa menangani hal2 seperti berikut : 
a) Menangani manajemen data-data master, pelanggan, kendaraan, dll (CRUD). 
b) Menangani transaksi pembelian sparepart. 
c) Menangani transaksi service dan penggantian spare part. 
Spare part apa yang diganti berserta harganya. 
Perawatan apa yang dilakukan. 
Total biaya yang harus dibayarkan. 
d) Menangani historis tracking perawatan kendaraan. 
Misal dengan memasukan nomor polisi, maka historis perawatan akan muncul 
dilayar. 
e) Melakukan searching untuk melihat ketersediaan sparepart.
