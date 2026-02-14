tinggi = float(input("Masukkan tinggi badan (meter): "))
bmi = float(input("Masukkan nilai BMI yang diinginkan: "))
berat = bmi * (tinggi ** 2)
print("Berat badan yang diperlukan adalah", berat, "kg")


x = int(input("Masukkan nilai x: "))
hasil = (2 * (x ** 3)) + (2 * x) + (15 / x)
print("Nilai f(x) adalah:", hasil)


gaji_per_jam = int(input("Masukkan gaji per jam: "))
jam_per_minggu = int(input("Masukkan jumlah jam kerja per minggu: "))
pendapatan_kotor = gaji_per_jam * jam_per_minggu * 5
pajak = 0.14 * pendapatan_kotor
pendapatan_bersih = pendapatan_kotor - pajak
baju_aksesoris = 0.10 * pendapatan_bersih
alat_tulis = 0.01 * pendapatan_bersih
sisa_uang = pendapatan_bersih - baju_aksesoris - alat_tulis
sedekah = 0.25 * sisa_uang

anak_yatim = 0.30 * sedekah
dhuafa = 0.70 * sedekah
print("Pendapatan kotor:", pendapatan_kotor)
print("Pendapatan bersih:", pendapatan_bersih)
print("Uang untuk pakaian & aksesoris:", baju_aksesoris)
print("Uang untuk alat tulis:", alat_tulis)
print("Total sedekah:", sedekah)
print("Untuk anak yatim:", anak_yatim)
print("Untuk kaum dhuafa:", dhuafa)
