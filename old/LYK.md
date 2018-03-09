#1-Başlangıç:

##Cent Os Note: 
Oluşturduğumuz Cent Os un klonunu Kopyalamak için sağ tık,Mac adresini işaretle,Bağlantılı seç(Çökme durumunda kurtarma imkanı olsun diye)

Root alanı(/) oluştururken 1/4 yeter. Ssdler için swap uygun değil(harddiski çabuk yıpratır ).Swap için ram in iki katı önerilir.(Zorlandığın da ram yerine kullanılır.)Geri kalan

Alan Home a atılır.(Resim Müzik dosyaları Falan) 
root@local
//Control-R Klonu siler.//
//Ekranı Temizlemek için control-l veya clear yazmalıyız//
**Yaptığımız Programı Arkadaşa atmak istersek parolayı değiştirmek gerekir.

##Bazı Semboller:

~  Şuan nerde olduğumuzu gösterir.

@localhost=Bilgisayarın adı oluyor(Buğranın Bilgisayarı Falan)

root olduğunu # sembolden anlarız.

##Komutlar:
echo= ekranda ne yazarsak onu gösterir.
echo $SHELL= Hangi shell de olduğumuzu gösterir. örneğin /bin/bash
touch= Dosya oluşturur.
ls= dosyaları gösterir.(Klasörün içinde ne var ne yok gösterir.)
ls-l=Daha ayrıntılı gösterir. Alt Alta
pwd=nerde olduğumuzu söyler.
uzun\dosya.. \=Dosya arasında boşluk bırakır(\)
ls /=/ klasöründe hangş dosyalar olduğunu gösterir(/ yerine başka klasörlerde yazabiliriz.)
uptime= Sistemin ne kadar açık olduğunu gösterir.
date= Tarih saati gösterir
. ile başlayan dosya ismi yazarsan gizli dosya olur.
ls -la =tüm dosyaları gösterir.
cd=Change Directory Bulunduğun klasörü değiştirir.
rm= dosya siler örnek: rm oyunlar
rm -f= sormadan siler.
mkdir=dizin oluşturma.
rmdir=içi boş bi dizini siler örnek: rmdir dizin/
mkdi sonra tab a bas sana mkdi ile başlayan komutları gösterir.
man pwd= pwd nin ne işe yaradığını gösterir
rm -r= boş olmayan dizini de siler.
rm -rf=sil ama adım adım sorma.
rm -rf --no-preserve-root / = rootu silicem bana karışma
Komutla çıkış--> logout
cd ~ --> bizi evimize götürür.
cd - --> bir önceki yere götürür.
../isteğin yeri yaz tabi iki geri gitçeksen ikitane yaz.
cp= kopyalamayı sağlar
cp -R lyk/lyka--> lyk yı lyka olarak kopyalar.
file komutu dizin mi dosya mı olduğunu söyler.
mv--> taşımayı sağlıyor.
mv lyk1/musıcc lyk2/musıcs --> lyk1 deki dosyayı lyk2 ye istediğimiz isimle taşımış oluyoruz.
ctrl+d ile yazma bölümünden çıkabiliriz.
cat > deneme diyip yazabilirsin sonra ctrl d ile çıkarsın ve cat >> deneme ile eklemeye devam edebilirsin.
cat >> roman <<zncr --> zncr ile çıkmayı sağlar.
mkdir -p kefir/kebap--> kefir dizini içine kebap klasörü oluşturur.
mkdır -p kefır/kebab{} sırayla oluşturmamızı sağlar. sayılar için {1..100} yapabiliriz.
dd if =/dev/random of=/dev/sda bs=512 count 1 formatı sağlıyor.
ls kebap1*/ --> 1le başlayanları gösterir.
cat>lyk1 ---> lyk1 dosyası oluşturur ve içine yazmayı sağlar.
history--> önceki komutları gösterir.
history yazdıktan sonra control +r yaparsak istediğimiz komuta ulaşırız.
history -c --> geçmişi siler.
**less,more,script komutlarını gördük (script yaptığımız işlemleri kaydetmeye yarar. script kayitlar4 ,,,,, ctrl+d)
0-->giriş
1-->çıktı
2--> hata


control c komutu siler ve yeni sekme açar.
 
**password ile cypher farklı şeyler= cypher belirli kurallarla konuşma yazma , pasaport ise bizim koyduğumuz şeyler.
alt+f2,alt+f3=terminalleri değiştiriyor.
**screen komutuyla terminal açabilirsin
shift+page up,page down=yukarı aşağı gitmesini sağlar.
Control+d=çıkış yapar.
cat=bu komut göstermeye yarar.(örnek cat passwd)
ls --help |=less (ayarlarda yukarı aşağı tuşlarıyla gezmemizi sağlar.)(/ yaparak kelime aratabilirsin.)
**whoami= hangi kullanıcıda olduğumuzu söyler.
**Bilgisayar şifreyi hashlenmiş haliyle kaydeder.
Dosya uzantıları:
shadow=en önemli bilgiler var.





Arayüz:?(Tam emin değilim sor)
Gnome
XFCE
LXDE
KDE=linuxun güzel yüzü.


**3 tane Root var =1-Giriş Yaptığımız Root.2-Root Dizini 3-/root
Dosya Türleri:
Etc=Ayar dosyaları
