🟦 Identitas & klasifikasi rumah
Kolom	Arti
Id	ID rumah
MSSubClass	Jenis bangunan (kode)
MSZoning	Zona peruntukan lahan

📌 MSZoning ada 1455 data → 4 rumah datanya kosong

🟦 Ukuran tanah & bentuk lahan
Kolom	Arti
LotFrontage	Lebar tanah bagian depan
LotArea	Luas tanah
Street	Jenis jalan
Alley	Gang/akses samping
LotShape	Bentuk tanah
LandContour	Kontur tanah
Utilities	Fasilitas utilitas

📌 Alley hanya 107 data → kebanyakan rumah tidak punya gang

🟦 Lingkungan & lokasi
Kolom	Arti
Neighborhood	Lingkungan
Condition1 / 2	Kondisi sekitar
LotConfig	Posisi lahan
LandSlope	Kemiringan lahan
🟦 Struktur bangunan
Kolom	Arti
BldgType	Tipe bangunan
HouseStyle	Gaya rumah
OverallQual	Kualitas bangunan
OverallCond	Kondisi bangunan
YearBuilt	Tahun dibangun
YearRemodAdd	Tahun renovasi
🟦 Atap & eksterior
Kolom	Arti
RoofStyle	Bentuk atap
RoofMatl	Material atap
Exterior1st / 2nd	Material dinding luar
MasVnrType	Jenis veneer
MasVnrArea	Luas veneer
🟦 Basement (ruang bawah tanah)
Kolom	Arti
BsmtQual	Kualitas basement
BsmtCond	Kondisi basement
BsmtExposure	Paparan basement
BsmtFinType1 / 2	Tipe finishing
BsmtFinSF1 / 2	Luas basement selesai
BsmtUnfSF	Basement belum selesai
TotalBsmtSF	Total luas basement

📌 Banyak missing → tidak semua rumah punya basement

🟦 Sistem rumah
Kolom	Arti
Heating	Sistem pemanas
HeatingQC	Kualitas pemanas
CentralAir	AC sentral
Electrical	Sistem listrik
🟦 Luas & ruangan
Kolom	Arti
1stFlrSF	Luas lantai 1
2ndFlrSF	Luas lantai 2
GrLivArea	Luas area tinggal
BedroomAbvGr	Jumlah kamar tidur
KitchenAbvGr	Jumlah dapur
TotRmsAbvGrd	Total ruangan
🟦 Kamar mandi
Kolom	Arti
FullBath	Kamar mandi penuh
HalfBath	Kamar mandi setengah
BsmtFullBath	Kamar mandi basement
BsmtHalfBath	Setengah kamar mandi basement
🟦 Garasi
Kolom	Arti
GarageType	Jenis garasi
GarageYrBlt	Tahun garasi
GarageFinish	Finishing garasi
GarageCars	Kapasitas mobil
GarageArea	Luas garasi
GarageQual	Kualitas garasi
GarageCond	Kondisi garasi
🟦 Area luar rumah
Kolom	Arti
WoodDeckSF	Teras kayu
OpenPorchSF	Teras terbuka
EnclosedPorch	Teras tertutup
ScreenPorch	Teras berjaring
3SsnPorch	Teras musiman
🟦 Fasilitas tambahan
Kolom	Arti
PoolArea	Luas kolam
PoolQC	Kualitas kolam
Fence	Jenis pagar
MiscFeature	Fitur tambahan
MiscVal	Nilai fitur tambahan

📌 PoolQC hanya 3 data → sangat jarang rumah punya kolam

🟦 Informasi penjualan
Kolom	Arti
MoSold	Bulan dijual
YrSold	Tahun dijual
SaleType	Jenis penjualan
SaleCondition	Kondisi penjualan