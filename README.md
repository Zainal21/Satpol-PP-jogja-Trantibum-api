### List Data SATPOL PP JOGJA

### Data Trantibum

- kode
- kdsatgas
- jenis_perda
- jenis_pelanggaran
- jumlah_pelanggaran
- instansi terkait
- lokasi_x
- lokasi_y
- jum_penertiban
- tindak_lanjut
- tindak_lanjut_ket
- pengadilan_denda
- pengadilan_yanglain
- kd_user
- tgl_input
- kategori
- jenis
- bidang
- ket_lain
- lamp_gambar

### DETAIL Trantibum

```json
{
    "message": "success",
    "code":200,
    "data": [{
        "kode": "2923",
        "kdsatgas": "002",
        "namasatgas": "KOTA YOGYAKARTA",
        "pusat": "0",
        "tgltribum": "2022-02-10",
        "jenis": "73",
        "perda": "[\"77 Th 2020 Tentang Penerapan Disiplin dan Penegakan Hukum Protokol Kesehatan sebagai Upaya Pencegahan dan Pengendalian Covid-19\"]",
        "lokasi": "Pasar Serangan",
        "lokasi_x": "",
        "lokasi_y": "",
        "jum_penertiban": null,
        "tindak_lanjut": "LAINNYA",
        "tindak_lanjut_ket": null,
        "pengadilan_denda": null,
        "pengadilan_yanglain": null,
        "keterangan": "Mendapati pedagang yang tidak melaksanakan protokol kesehatan",
        "ket_lain": "",
        "kduser": "14",
        "tgl_input": "2022-02-10",
        "kduser1": "14",
        "tgl_input1": "2022-02-10",
        "kategori_peraturan": "[\"5\"]",
        "kdkategory": "0",
        "publish": "0",
        "id_bidang": "1",
        "bidang": "Trantibum",
        "namakategory": null
    }]
}
```


### Data Penegakan

- kode
- tgl_perda
- nama_satgas
- jenis_perda
- jenis_pelanggaran
- jumlah_pelanggaran
- instansi_terkait
- lokasi
- lokasi_x
- lokasi_y
- keterangan
- pelanggaran
- bidang
- jenis_kegiatan
- lamp_gambar


### DETAIL PENEGAKAN

```json
{
    "data": [{
        "kode": "2934",
        "kdsatgas": "002",
        "lokasi": "Jl. Hos Cokroaminoto",
        "lokasi_x": "",
        "lokasi_y": "",
        "namasatgas": "KOTA YOGYAKARTA",
        "tglperda": "2022-02-02",
        "kategori_peraturan": "[\"1\"]",
        "jenis_perda": "",
        "jenis_pelanggaran": "Memasang reklame tidak memiliki ijin",
        "jumlah_pelanggaran": "1",
        "instansi_terkait": "DINAS PERIJINAN",
        "keterangan": "Sanksi : Denda",
        "tglinput": "2022-02-10",
        "pelanggar": [{
            "nik": "",
            "nama": "Catur Wicaksono",
            "alamat": "a"
        }],
        "publish": "0",
        "kduser": "13",
        "id_bidang": "3",
        "id_jenis_kegiatan": "1",
        "nama_bidang": "Penegakan Perda",
        "jenis_kegiatan": "Yustisi"
    }],
    "message": "success",
    "status": 200
}
```