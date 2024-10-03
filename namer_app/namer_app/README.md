# Pemrograman Mobile - Pertemuan 5

<table>
    <thead>
        <th style="text-align: center;" colspan="2">Pertemuan 5</th>
    </thead>
    <tbody>
        <tr>
            <td>Nama</td>
            <td>Sandra Devia Arge</td>
        </tr>
        <tr>
            <td>Nim</td>
            <td>2241720222</td>
        </tr>
    </tbody>
</table>

# Codelabs: Your first Flutter app

**Langkah 1: Create a project**

Membuat project baru dengan nama `namer_app`.

Menambahkan library pada file `pubspec.yaml`.

![alt](../../docs/pertemuan_05_16.png)

Menambahkan linter pada file `analysis_options.yaml`.

![alt](../namer_app/img/image1.png)

Merubah isi kode pada file `main.dart`.

![alt](../namer_app/img/image2.png)

**Langkah 2: Add a button**

Menjalanakan aplikasi pada device.

![alt](../namer_app/img/image3.png)

Mengubah Widget Text, menyimpan dan otomatis melakukan hot reload.

![alt](../../docs/pertemuan_05_20.png)

Selanjutnya, tambahkan tombol di bagian bawah Kolom, tepat di bawah contoh Teks kedua.

![alt](../../docs/pertemuan_05_21.png)

Ketika tombol ditekan, maka akan muncul di Debug Console.

![alt](../../docs/pertemuan_05_22.png)

Menambahkan fungsi `getNext()` pada file `main.dart`, Lalu menambahkan fungsi tersebut pada Button.

![alt](../../docs/pertemuan_05_23.png)

Ketika tombol ditekan, maka text akan berubah.

![alt](../../docs/pertemuan_05_24.gif)

**Langkah 3: Make the app prettier**

Melakukan sedikit perubahan kode pada file `main.dart`.

![alt](../../docs/pertemuan_05_25.png)

Melakukan Extract Widget pada Text Widget.

![alt](../../docs/pertemuan_05_26.png)

Wrap Widget Text di `BigCard` dengan Widget Padding.

![alt](../../docs/pertemuan_05_27.png)

Wrap Widget Padding dengan Widget Card.

![alt](../../docs/pertemuan_05_28.png)

Merubah warna background pada Card.

![alt](../../docs/pertemuan_05_29.png)

Menambahkan style ke Text Widget.

![alt](../../docs/pertemuan_05_30.png)

Menambahkan semanctic label pada Text untuk Screen Reader seperti Talkback.

![alt](../../docs/pertemuan_05_31.png)

Membuat isi di Column menjadi ke tengah secara vertikal.

![alt](../../docs/pertemuan_05_32.png)

Wrap Column dengan Widget Center.

![alt](../../docs/pertemuan_05_33.png)

Hapus Widget Text yang tidak digunakan, dan menambahkan Widget SizedBox untuk meberikan gap antara BigCard dengan Button.

![alt](../../docs/pertemuan_05_34.png)

**Langkah 4: Add functionality**

Menambahkan bussiness logic pada aplikasi.

![alt](../../docs/pertemuan_05_35.png)

Menambahkan button Like dengan icon.

![alt](../../docs/pertemuan_05_36.png)

Ketika tombol Like ditekan, maka akan berubah.

![alt](../../docs/pertemuan_05_37.gif)

**Langkah 5: Add navigation rail**

Replace semua kode pada file `main.dart`.

![alt](../../docs/pertemuan_05_38.png)

Merubah MyHomePage menjadi StatefulWidget.

![alt](../../docs/pertemuan_05_39.png)

Menambahkan property `selectedIndex`.

![alt](../../docs/pertemuan_05_40.png)

Jika tombol navigasi ditekan, maka akan berubah.

![alt](../../docs/pertemuan_05_41.gif)

Membuat properti untuk navigasi ke halaman lain.

![alt](../../docs/pertemuan_05_42.png)

Jika navigasi ditekan, maka akan berpindah ke halaman lain.

![alt](../../docs/pertemuan_05_43.gif)

Membuat halaman menjadi responsive dengan LayoutBuilder.

![alt](../../docs/pertemuan_05_44.png)

Sekarang jika layar diubah ukurannya atau melakukan rotate, maka akan berubah.

![alt](../../docs/pertemuan_05_45.gif)

**Langkah 6: Add a new page**

Membuat page baru dengan nama `FavoritePage`, untuk menampilkan list favorite.

![alt](../../docs/pertemuan_05_46.png)

Jika melakukan like pada halaman utama, maka akan muncul di halaman Favorite sebagai list.

![alt](../../docs/pertemuan_05_47.gif)