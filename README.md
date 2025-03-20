# Kullanıcıdan 5 sayı alıp bir listeye ekleme
sayilar = []
for i in range(5):
    sayi = int(input("Bir sayı girin: "))
    sayilar.append(sayi)

toplam = sum(sayilar)
ortalama = toplam / len(sayilar)
en_buyuk = max(sayilar)
en_kucuk = min(sayilar)

print(f"Toplam: {toplam}")
print(f"Ortalama: {ortalama}")
print(f"En büyük sayı: {en_buyuk}")
print(f"En küçük sayı: {en_kucuk}")


# Kullanıcıdan kelimeleri alıp bir listeye ekleme
kelimeler = []

while True:
    kelime = input("Bir kelime girin (çıkmak için 'q' tuşlayın): ")
    if kelime == 'q':
        break
    kelimeler.append(kelime)

kelimeler.reverse()

print("Ters sıralı kelimeler:", kelimeler)

# Kullanıcıdan sayıları alıp bir listeye ekleme
sayilar = []

while True:
    sayi = input("Bir sayı girin (çıkmak için 'q' tuşlayın): ")
    if sayi == 'q':
        break
    sayilar.append(int(sayi))

benzersiz_sayilar = list(set(sayilar))

print("Tekrar etmeyen sayılar:", benzersiz_sayilar)












