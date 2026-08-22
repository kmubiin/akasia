Perihal senarai definisi
------------------------

Senarai definisi adalah ciri bukan piawai. Berbeza dengan
senarai biasa yang menggunakan tanda sempang `-` pada
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

Untuk melihat paparan sebenar, lihat senarai definisi
yang dipapar di luar bongkah kod seperti berikut:

perkataan
: diikuti titik noktah bertindih, satu jarak kosong,
dan erti perkataan pada baris kedua dan seterusnya

Hasilnya adalah sama ada dalam bentuk senarai (ciri hadir)
atau perenggan (ciri tidak hadir atau terkecuali).
