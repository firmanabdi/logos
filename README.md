# logos
Sistematis Dalam Bahasa Yang Logis

print("=======DATE & TIME=======")
print("Silahkan masukan tanggal, \nbulan dan tahun lahir anda \n")
tanggal = int(input("Tanggal \t:"))
bulan = int(input("Bulan \t\t:"))
tahun = int(input("Tahun \t\t:"))

tanggal_lahir = dt.date(tahun, bulan, tanggal)
print(f"Tanggal lahir anda adalah : {tanggal_lahir}")

hari_ini = dt.date.today()
print(f"hari ini tanggal: {hari_ini}")
umur_hari = hari_ini - tanggal_lahir
umur_tahun = umur_hari.days // 365
umur_bulan_sisa = (umur_hari.days % 365) // 30


print(f"Hari nya adalah : {tanggal_lahir:%A}")
print(f"umur anda adalah: {umur_tahun} tahun, {umur_bulan_sisa} bulan")


print("=======\nPROGRAM KONVERSI TEMPERATUR\n======")
celcius = float(input('Masukan suhu dalam celcius : '))
print("Suhu adalah",celcius, "Celcius")

# reamur

reamur = (4/5) * celcius
print("suhu dalam reamur adalah ",reamur, "reamur")

# fahrenheit

fahrenheit = ((9/5) * celcius) + 32
print("suhu dalam farenheit adalah ",fahrenheit, "fahrenheit")

# kelvin

kelvin = celcius + 273
print("suhu dalam kelvin adalah ",kelvin, "kelvin")


print("=======table distribusi frekuensi=======")
# bagian pada table distribusi frekuensi:
# 1. kelas interval = kelompok nilai data yang di tulis dalam bentuk interval

# 2. batas kelas = (a)batas atas & (b)batas bawah

# 3. tepi kelas =  (a)batas atas + 0,5 & (b)batas bawah - 0,5

# 4. panjang kelas = (a)batas atas - (b)batas bawah + 1

# 5. titik tengah kelas = x1= 1/2 * ((a)batas atas + (b)batas bawah))


print("=======tentukan jangkauan kelas((a) data terbesar - (b) data terkecil=======")
x = 95
_y = 42
hasil = x - _y
print(x, "-", _y, "=", hasil)

# tentukan banyak kelas interval

x = 1  
y = 3.3
z = 1.6 # log n(40)
hasil = (x + y) * z
print("(", x, "+", y, ") *", z, "=", hasil)

# tentukan panjang kelas

x = 53  # jangkauan kelas
_y = 6  # banyak kelas
hasil = x / _y
print(x, "/", _y, "=", hasil)


print("=======table distribusi frekuensi=======")
# bagian pada table distribusi frekuensi:
# 1. kelas interval = kelompok nilai data yang di tulis dalam bentuk interval

# 2. batas kelas = (a)batas atas & (b)batas bawah

# 3. tepi kelas =  (a)batas atas + 0,5 & (b)batas bawah - 0,5

# 4. panjang kelas = (a)batas atas - (b)batas bawah + 1

# 5. titik tengah kelas = x1= 1/2 * ((a)batas atas + (b)batas bawah))


print("=======tentukan jangkauan kelas (a)batas atas - (b)batas bawah=======")
x = 95
_y = 42
hasil = x - _y
print(x, "-", _y, "=", hasil)

# tentukan banyak kelas interval

x = 1  
y = 3.3
z = 1.6 # log n(40)
hasil = (x + y) * z
print("(", x, "+", y, ") *", z, "=", hasil)

# tentukan panjang kelas

x = 53  # jangkauan kelas
_y = 6  # banyak kelas
hasil = x / _y
print(x, "/", _y, "=", hasil)

print("=======Bilangan Bulat=======")
# 2x -8 < 4x + 2
# 2x -4x < 8 + 2
x = -4
_y = 2
hasil = x / _y
print(x,'/',_y,'=',hasil)

x = 8
_y = 2
hasil = x + _y
print(x,'+',_y,'=',hasil)

# -2x < 10
# ubah ruas 2x > -10
# x > -10/2
x = -10
_y = 2
hasil = x / _y
print(x,'/',_y,'=',hasil)
# hp = x > -5 (-5,unlimited)


print("=======Bilangan Rational=======")
# 9 >= 2x -5 >= 3
# 9 + 5 >= 2x -5 + 5 >= 3 + 5 "ditabahkan 5 di setiap bilangan aslinya"
# (14/2) >= (8/2)
# 7 >= 4
# hasil = True

x = 9
_y = 5
hasil = x + _y
print(x,'+',_y,'=',hasil)

x = -5
_y = 5
hasil = x + _y
print(x,'+',_y,'=',hasil)

x = 3
_y = 5
hasil = x + _y
print(x,'+',_y,'=',hasil)

hasil_a = 14
x1 = 2
hasil = hasil_a / 2
print(hasil_a,'/',x1,'=',hasil)


hasil_b = 8
hasil = hasil_b / 2
x2 = 2
print(hasil_b,'/',x2,'=',hasil)

hasil_a = 7
hasil_b = 4
hasil = 7 >= 4
print(hasil_a,'>=',hasil_b,'=',hasil)
