# Aplikasi Sistem Informasi Perpustakaan #

Anggota Kelompok :
-------
1. AHMAD AYURVEDA ORYZA ASMORO WASIS (50418324)
2. ARI ROYANI BIYA (51418045)
3. MAULANA MUHAMMAD YUSUF FRASHA (54418032)
4. MUHAMMAD RUSYDI (54418950)


Fitur :
-------
1. Autentikasi (Login Admin)
2. Upload Foto
3. CRUD

Tabel database **`db_perpus`** :
----------------
1. Master : <br />
  **buku** <br />
<table>
  <tr>
    <th>field</th>
    <th>type</th>
  </tr>
  <tr>
    <td>buku_id</td>
    <td>`int`</td>
  </tr>
  <tr>
    <td>judul</td>
    <td>`varchar`</td>
  </tr>
  <tr>
    <td>kategori</td>
    <td>`int`</td>
  </tr>
  <tr>
    <td>deskripsi</td>
    <td>`text`</td>
  </tr>
  <tr>
    <td>jumlah</td>
    <td>`int`</td>
  </tr>
  <tr>
    <td>cover</td>
    <td>`varchar`</td>
  </tr>
</table>
**kategori** <br />
<table>
  <tr>
    <th>field</th>
    <th>type</th>
  </tr>
  <tr>
    <td>kategori_id</td>
    <td>`int`</td>
  </tr>
  <tr>
    <td>kategori</td>
    <td>`varchar`</td>
  </tr>
</table>
**anggota** <br />
<table>
  <tr>
    <th>field</th>
    <th>type</th>
  </tr>
  <tr>
    <td>anggota_id</td>
    <td>`int`</td>
  </tr>
  <tr>
    <td>nama</td>
    <td>`varchar`</td>
  </tr>
  <tr>
    <td>alamat</td>
    <td>`text`</td>
  </tr>
  <tr>
    <td>jk</td>
    <td>`enum(L,P)`</td>
  </tr>
  <tr>
    <td>telp</td>
    <td>`varchar`</td>
  </tr>
</table>
**petugas** <br />
<table>
  <tr>
    <th>field</th>
    <th>type</th>
  </tr>
  <tr>
    <td>petugas_id</td>
    <td>`int`</td>
  </tr>
  <tr>
    <td>nama</td>
    <td>`varchar`</td>
  </tr>
  <tr>
    <td>username</td>
    <td>`varchar`</td>
  </tr>
  <tr>
    <td>password</td>
    <td>`varchar`</td>
  </tr>
</table>
2. Transaksi : <br />
**pinjam** <br />
<table>
  <tr>
    <th>field</th>
    <th>type</th>
  </tr>
  <tr>
    <td>pinjam_id</td>
    <td>`int`</td>
  </tr>
  <tr>
    <td>buku_id</td>
    <td>`int`</td>
  </tr>
  <tr>
    <td>anggota_id</td>
    <td>`int`</td>
  </tr>
  <tr>
    <td>tgl_pinjam</td>
    <td>`date`</td>
  </tr>
  <tr>
    <td>tgl_jatuh_tempo</td>
    <td>`date`</td>
  </tr>
</table>
**kembali** <br />
<table>
  <tr>
    <th>field</th>
    <th>type</th>
  </tr>
  <tr>
    <td>kembali_id</td>
    <td>`int`</td>
  </tr>
  <tr>
    <td>pinjam_id</td>
    <td>`int`</td>
  </tr>
  <tr>
    <td>tgl_kembali</td>
    <td>`date`</td>
  </tr>
  <tr>
    <td>denda</td>
    <td>`double`</td>
  </tr>
</table>

### SCREENSHOT APLIKASI ###

--------------
