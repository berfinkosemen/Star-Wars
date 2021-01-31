# Star-Wars

Star Wars

Fatma Değirmenci  -	170201008
Berfin Kösemen	  -	170201058

Bu README.md dosyası, Star Wars projesine aittir.
Bu paket, kaynak kodu ile aynı dizin içerisinde bulunacaktır.


1-PAKETİN İÇERİĞİ:
-------------------
Proje dosyaları.
README.md - Bu dosya.
-------------------


2-SİSTEM GEREKSİNİMLERİ:
-------------------
Allegro - A game programming library - https://liballeg.org/
-------------------


3-KURULUM:
-------------------
Paket içeriğini, yukarıda görebilirsiniz.

Bu kod, iki adet Windows kurulu makinede çalıştırıldı.

Bu iki durumda da, kod, herhangi bir hata vermeksizin, daha önceden
belirlenen kriterlere uygun çalıştı.

-------------------


4- PARAMETRELER
-------------------
Kodun çalışması için allegro kütüphanesi kurulmalı ve Harita.txt StarWars
klasöründe olmalı. 
------------------


5- PROGRAMIN KULLANIMI
-----------------------------
Star Wars Projesi, Harita.txt dosyası içindeki bilgileri okur ve okunan bilgilere
göre kötü karakterleri, iyi karakteri ve map'i oluşturur. Kullanıcının hareketine göre
iyi karakteri hareket ettirir ve en kısa yol bulma algoritması yardımı ile de
kötü karakterler kullanıcıya ilerler. 

Program ilk çalıştırıldığında allegro kütüphanesi etkinleştirilir ve Harita.txt okunur. 
Ardından arayüz açılır ve okunan bilgiler burada çizilir. Kullanıcının klavye ile(yön okları)
hareketi sonucu her kötü karakter için en kısa yol hesaplanır.

Hesaplanan bu en kötü yol yine allegro kütüphanesi yardımı ile ekrana çizilir. 

İyi karakter, kötü karaktere yakalanırsa karakterin türüne özel olarak can düşümü yapılır.
Ardından tüm karakterler başlangıç konumuna döner.

MasterYoda iyi karakterinin canı yarım yarım azalırken, LukeSkywalker iyi karakterinin
canı birer birer azalır.

Aynı zamanda DarthVader kötü karakteri duvarlardan geçebilir, KyloRen 2şer birim ilerler.
Stormtrooper bir birim ilerler ve duvarlardan geçemez, ek bir özelliği yoktur.

Kullanıcının canı kalmazsa oyunu kaybettiğinden display kapanır, canı bitmeden çıkış 
noktasına ulaşırsa da oyunu kazanır ve display kapanır. 

Böylece program sonlandırılmış olur.
