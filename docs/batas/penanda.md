Rang bahasa penanda
-------------------

Semua kandungan bagi sumber ini harus menggunakan
CommonMark, iaitu Markdown yang mengikut peraturan lazim.

Jika terdapat ciri-ciri yang tidak disokong secara lalai,
maka gunakan bahasa penanda HTML. Ia boleh ditulis seiring
dengan Markdown, berdasarkan piawai CommonMark sendiri.

Dari sudut pandangan suatu bahasa penanda, terdapat dua
kumpulan ciri:

1. Piawai
2. Bukan piawai (atau Perluasan)

Kumpulan pertama merujuk pada ciri-ciri yang hadir dan
seragam. Kumpulan kedua pula merujuk pada ciri-ciri yang
tidak hadir atau yang diperluas. Kehadiran ciri-ciri
tersebut bergantung pada bahasa penanda.

Misalnya, senarai definisi adalah ciri bukan piawai. Berbeza
dengan senarai biasa yang menggunakan tanda sempang `-` pada
permulaan setiap baris, ciri ini ditulis seperti berikut:

    perkataan
    : diikuti titik noktah bertindih, satu jarak kosong,
    dan erti perkataan pada baris kedua dan seterusnya

Apabila senarai definisi berubah daripada format asal
menjadi HTML, perkataan dan erti perkataan dipapar dalam
bentuk senarai dan kod yang dijana adalah seperti berikut:

    <dl>
    <dt>perkataan</dt>
    <dd>diikuti titik noktah bertindih, satu jarak kosong,
    dan erti perkataan pada baris kedua dan seterusnya</dd>
    </dl>

Sebaliknya, jika senarai definisi tidak disokong oleh
bahasa penanda pilihan, maka semua baris terkumpul dalam
perenggan yang sama seperti berikut:

    <p>perkataan
    : diikuti titik noktah bertindih, satu jarak kosong,
    dan erti perkataan pada baris kedua dan seterusnya</p>

----

Untuk melihat paparan sebenar, senarai definisi yang sama
telah disalin semula tanpa jarak empat aksara kosong pada
permulaan setiap baris dan ditampal seperti berikut:

perkataan
: diikuti titik noktah bertindih, satu jarak kosong,
dan erti perkataan pada baris kedua dan seterusnya

Hasilnya adalah sama ada dalam bentuk senarai (ciri hadir)
atau perenggan (ciri tidak hadir atau terkecuali).

----

Bahasa penanda pilihan seperti CommonMark, memperincikan
yang piawai dan memberi hasil paparan yang seragam.
Walaupun kelihatan sederhana dan kurang lengkap, namun
ciri-ciri piawai sedia digunakan di mana jua.

Bahasa penanda lain seperti MultiMarkdown dan kramdown,
memperincikan yang piawai dan yang bukan piawai sekaligus
dan kelihatan lebih lengkap. Bagaimanapun, setiap satu
bahasa penanda itu dapat digunakan di dalam persekitaran
terhad atau dengan perisian tertentu sahaja.

Disediakan oleh kmubiin, bermula Mei 2026.
