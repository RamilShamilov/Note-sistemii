# Note-sistemii
print("NOT SISTEMI")
ad = input("adinizi giriniz:")
soyad = input("Soyadinizi giriniz:")
universte_ismi = input("Universite isminizi giriniz:")
sinif_NO = input("Sinif numaranizi giriniz:")
note = int(input("Notunuzu giriniz:"))
bilgiler = [ad, soyad, universte_ismi, sinif_NO, note]

if note >= 90:
    print("AA aldiniz")

elif note >= 80: 
    print("BB aldiniz")
elif note >= 70:
    print("CC aldiniz")
elif note < 70:
    print("Sinifda kaldiniz")

print("Adiniz:{}\nSoyadiniz:{}\nUniversite adiniz:{}\nSinif numaraniz:{}".format(bilgiler[0], bilgiler[1], bilgiler[2], bilgiler[3]))
    
print("Basharilar")
