# SourceCode-Pertemuan2
#Nama : Joshua R M Wanggai #UniversitasKristenDutaWacana 
#Grup C  
#https://faridanursyahidah.files.wordpress.com/2013/06/matematika-keuangan.pdf 
#***Harga  beras  tiap  kilogram  setelah  mendapatkan  subsidi  dari  pemerintah  adalah  Rp1.575,00.  
#Jika pemerintah memberikan subsidi sebesar 37%, tentukan subsidi yang ditentukan pemerintah dan harga beras sebelum subsidi!  
#subsidi = 37% / 100%-37% * 1575 #harga beras sebelum subsidi = harga beras setelah subsidi - subsidi  

#input : a = 37% ; b = 100% ; c = 1575 (harga setelah subsidi)  

#proses : 
#subsidi = s 
#harga beras sebelum subsidi = p  

#output : 
nilai s dan nilai p  

a = 37 
b = 100 
c = 1575.00 
s = a / (b - a) * c print('nilai s : Rp', s)  

p = c + s 
print('nilai p : Rp', p)
