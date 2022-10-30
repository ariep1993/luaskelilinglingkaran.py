# Menghitung luas dan keliling lingkarn menggunakan Python
Nama = saripudin

Nim  = 312210077 

Kelas= TI.22.B1

Flowchart luas dan keliling lingkaran

<img width="625" alt="flow" src="https://user-images.githubusercontent.com/115473865/198858069-df66d0b8-971f-4401-bdd2-c6563329243a.png">

  # import module math
import math

# Variable jariJari menampung nilai input yang dimasukan yaitu berupa string
jariJari = input('Masukan jari-jari lingkaran :')

"""

rumus luas & keliling lingkaran
_____________________________________

luas     = phi * r^2

keliling = 2 * phi * r

_____________________________________

"""

# convert string to integer
jariJari = int(jariJari)

# hitung luas lingkaran
luas = math.pi * (jariJari * jariJari)

# hitung luas keliling
keliling = 2 * math.pi * jariJari

# output luas & keliling lingkaran
# .2f => mengambil 2 angka setelah (,)
print("Berikut Luas lingkaran =  ", format(luas, '.2f'))
print("Berikut Keliling lingkaran = ", format(keliling, '.2f'))
