# tampil data
method get = http://127.0.0.1:8001/api/index

# show by id
method get = http://127.0.0.1:8001/api/index/1

# update data
method post = http://localhost:8001/api/pengguna/store?nama=sabaed&alamat=jsjjajaja&nomor_telepon=073883939&jenis_kendaraan=mobil

# hapus data
method delete = http://127.0.0.1:8001/api/pengguna/3