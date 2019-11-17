#Aracın Kmde kaç Kuruş Yaktığını Hesaplayan Program 
print("Aracımın Km. de Ne Kadar Yaktığını Bulunuz")
alınan_yakıt = float(input("Kaç Paralık Yakıt Aldınız(TL): "))
gidilen_yol = float(input("Ne Kadar Yol Katettiniz(KM): "))
kaç_kuruş = float(alınan_yakıt / gidilen_yol)
print("Hesaplanıyor...\n")
print("Alınan Yakıt(TL): {}\nGidilen Yol(KM): {}\nFiyat/KM: {}\n".format(alınan_yakıt,gidilen_yol,kaç_kuruş))
print("Hesaplama Sona Erdi.")
