# odev2
# Kullanıcıdan iki sayı al
sayi1 = float(input("Birinci sayıyı girin: "))
sayi2 = float(input("İkinci sayıyı girin: "))

# İşlemler
print(f"Toplama: {sayi1} + {sayi2} = {sayi1 + sayi2}")
print(f"Çıkarma: {sayi1} - {sayi2} = {sayi1 - sayi2}")
print(f"Çarpma: {sayi1} * {sayi2} = {sayi1 * sayi2}")
print(f"Bölme: {sayi1} / {sayi2} = {sayi1 / sayi2}")
print(f"Mod Alma: {sayi1} % {sayi2} = {sayi1 % sayi2}")
print(f"Üs Alma: {sayi1} ** {sayi2} = {sayi1 ** sayi2}")

#Görev2
n = int(input("Bir sayı girin: "))
toplam = 0

for i in range(1, n + 1):
    toplam += i

print(f"1'den {n}'e kadar olan sayıların toplamı: {toplam}")

#Görev3
print("1 ile 100 arasındaki çift sayılar:")
for i in range(2, 101, 2):  
    print(i, end=" ")

#Görev4
metin = input("Bir metin girin: ")
ters_metin = ""

for harf in metin[::-1]:  
    ters_metin += harf

print(f"Girilen metnin tersi: {ters_metin}")
