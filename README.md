SAYI SİSTEMLERİ
Sayma işleminin hangi ölçütlere göre yapılacağını belirleyen kurallar bütününe sayma sistemi adı verilir.
Dünyada yaygın olarak kullanılan dört farklı sayma sistemi vardır. Bunlar, onlu, sekizli, on altılı ve ikili sayma sistemleridir. Bu dördü arasında en yaygın kullanılan sayma sistemi ise, tabii ki, onlu sistemdir. İnsanların elleri ve ayaklarında on parmak olduğunu düşünürsek, bu sistemin neden daha yaygın kullanıldığını anlamak aslında hiç de zor değil!
Bilgisayar elektronik bir cihaz olduğu için elektrik akımın geçirilmesi (1) ya da geçirilmemesi (0) durumlarını işleyebilir. Bu nedenle ikili sayı sistemi temel alarak veri işlerler ve saklarlar.
En küçük bellek birimi sadece 0 ve 1 değerlerini alabilen ikili sayı sisteminde bir basamağa denk gelen Bit'tir.
1 Bayt (Byte) = 8 Bit
1024 Byte = 1 KiloByte (KB)
1024 KiloByte = 1 MegaByte (MB) 1024 MegaByte = 1 GigaByte 1024 GigaByte = 1 TeraByte
1024 TeraByte = 1 PetaByte
1024 PetaByte = 1 EksaByte 1024 EksaByte = 1 ZettaByte 1024 ZettaByte = 1 YottaByte 1024 YottaByte = 1 BrontoByte 1024 BrontoByte = 1 GeopByte 1024 GeopByte = 1 SaganByte 1024 SaganByte = 1 EpicByte Neden 1000 değil de 1024
Bilgisayar 2'li sayı sistemine göre çalıştığı için 10^3 değil 2^10 sayma sistemi temel alınır.
Onlu sistemin yaygınlığını düşünerek, sayma sistemleri konusunu anlatmaya onlu sayma sisteminden başlayalım.
ONLU SAYI SİSTEMİ
Günlük hayatımızda en çok kullandığımız sayı sistemi olup, bütün işlemler aşağıda gösterilen 10 adet rakam ile gerçekleştirilir:
0, 1, 2, 3, 4, 5, 6, 7, 8, 9
Onlu sayı sisteminde rakamlarla gösterilen bir sayının elde edilişini 4753 sayısı üzerinden incelemeye çalışalım:
4 . 10 3 + 7 . 10 2 + 5 . 10 1 + 3 . 10 0 = 4. 1000 + 7. 100 + 5. 10 + 3. 1 = 4000+700+50+3 = 4753
 Her basamakta yer alan rakam 10 (mavi renkle gösterilen) sayısının katları (bg-orangecu renkle gösterilen değerde) ile çarpılır. En sağda yer alan 10 sayısının katı 0 ile başlar ve sol tarafa doğru birer birer artar. Elde edilen değerler toplanarak sayı elde edillir.
İKİLİ SAYI SİSTEMİ
İkili sayılar sayıların 2 tabanında yazılmasıyla elde edilir. Dolayısıyla tüm sayılar 0 ve 1 rakamları kullanılarak ifade edilirler. Elektronik devrelerindeki kolay uygulanabilmeleri nedeniyle günümüz bilgisayarlarının neredeyse tamamında kullanılırlar.
Günlük hayatta sayıları ifade etmek için onluk taban [decimal] kullanılır. Bunun anlamı, her sayının 0, 1, 2, 3, 4, 5, 6, 7, 8 ve 9 rakamları kullanılarak ifade edilmesidir. Sayıların en sağındaki basamağına birler, ikincisine onlar ve üçüncüsüne de yüzler basamağı denildiği genel olarak bilinmektedir.
Bu basamaklara daha yakından bakıldığında sayıların çarpma ile ifade edildiği anlaşılacaktır. Örneğin 5, 5 × 100, yani 5 çarpı 10'un sıfırıncı kuvveti olarak düşünülebilir. Yani 5 × 1 = 5. 50'yi ele alırsak, 50 = 5 × 101 = 5 × 10. 5 bu defa onlar basamağında olduğundan bir sonraki kuvveti kullandık.
İkili sayı sisteminde en solda yer alan bit (yüksek bit) sayının işaret bit'i olarak kullanılır.
Örneğin, aşağıda gösterildiği gibi işaretsiz 8 bit'lik bir sayıda elde edilebilecek azami sayı 255 iken işaret bit'inin sağladığı değer olan 128 devre dışı kaldığından, işaretli sayıda elde edilebilecek azami değer 127 sayısıdır.
27 + 26 + 25 + 24 + 23 + 22 + 21 + 20
128 + 64 + 32 + 16 + 8 + 4 + 2 + 1 = 255 (İşareti olmayan sayılar için azami değer) 0 + 64 + 32 + 16 + 8 + 4 + 2 + 1 = 127 (İşareti olan sayılar için azami değer)
İkili sayı sisteminde bir byte (8 bit'lik)'lık sayılar pozitif sayıları ifade etmek için kullanıldığında 0 - 255 arası (256 adet), negatif sayıları ifade etmek için kullanıldığında ise 0 - 127 arası (128 adet) değer alır.
İşaret bit'i 1 ise sayı negatif, 0 ise sayı pozitiftir. 1 0 0 0 0 0 0 0 = -127 = 128
0 1 1 1 1 1 1 1 = 127 21 sayısını ele alalım:
-21 ve bu sayıyla aynı şekilde ifade edilen pozitif sayıyı bulmak için aşağıdaki yöntemi kullanabiliriz:
sayı + tamlayan sayı = 8 bit ile elde edilebilecek azami sayı miktarı 21 + 235 = 256
Burada -21 ve 235 sayılarını ikili sayı sisteminde aynı şekilde ifade edebileceğimizi buluyoruz:
1 1 1 0 1 0 1 1 = -21 = 235

 SEKİZLİ SAYI SİSTEMİ
Sayısal Sistemler her ne kadar ikili sayı sistemini kullansalar da bir tasarımcı için binary (ikili) sayılarla işlem yapmak zahmetli bir işlem olduğundan farklı sayı sistemlerinin kullanımı tasarımcılar arasında yaygınlaşmıştır. Kullanılan bu sayı sistemlerinden Sekizli (oktal) Sayı sisteminin tabanı sekiz olup 0, 1, 2, 3, 4, 5, 6, 7 rakamları bu sayı sisteminde kullanılır.
İşlemci yalnız ikili sistemi anladığı, kullanıcı ise 10` lu sisteme alıştığı için 60′ lı yıllara kadar bilgisayarla kullanıcı arasında iletişim zorluğu vardı. Bu zorluklar özellikle bilgisayara adres bilgisi aktarmak, bilgisayardan adres bilgisi almak, registerlerin durumlarını izleyerek gereken ayarlamaları yapmak, belleğin içeriğini kontrol etmek ve gereken değişiklikleri yapmak, işlemciye hemen kullanılacak veriyi aktarmak vs. gibi problemlerin çözümü sırasında yoğun olarak karşıya çıkmaktaydı. Bu problemi hafifletmek amacı ile 2’ li sistemden daha anlaşılır, bilgisayar için ise ikili sistem kadar anlaşılabilen bir aralık sayı sisteminin olması gerekirdi. Böyle bir sistem olarak 8’ li sayı sistemi seçilmişti. Bu tercih sebebi ise 8 = 23 olduğu için, 8′ li sayının her bir rakamının yerine mekanik olarak onun 3 rakamlı ikili karşılığını koymakla 8’ li sayının 2’ li karşılığını almasıdır.
Örnek 1 (34507,0216)8 = (?)2
(34507,0216)8 = 011 100 101 000 111 , 000 010 001 110 sonucu elde edilir. 34507,0216
Örnek 2 Sekizlik tabanda verilen 736,4 sayısının onlu tabanda karşılığını bulalım.
(736,4)8 = (7×82 + 3×81 + 6×80 + 4×8-1) = (478,5)10 sayısı elde edilir.
ON ALTILI SAYI SİSTEMİ
Katsayı: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15 olmak üzere 16 adet adet mevcuttur. Ancak dikkat etmeniz gerekmeyen bir nokta var. Örnek olarak 16 evlilikten 114 tanesi ele alınmıştır. Bu sayı 16'lık sayı sisteminde 1–1–4 sayılarında mı, 11–4 sayılarından mı, 1–14 yapısından mı oluştuğunu anlamamız oldukça güç. Bu nedenle çift haneli harfler temsil edilmektedir.
16 → 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A (10), B (11), C (12), D (13), E (14), F (15)
Eğer 11–4 yazmak istersek: B4 yazmamız yeterli olacaktır.
Dizin: Sağdan sola doğru 0'dan başlayarak her katsayıya bir sayı verilir.
Çarpan: Sistem tabanı 16 olduğu için 16'nın üzerine indeksin yazılması ile oluşan sayıdır.

ÖRNEKLER
Örnek ikili sayı: 11010100
İkili sayı sisteminden sekizli sayı sistemine dönüşüm (11010100)2 = (324)8
İkili sayı sisteminden onlu sayı sistemine dönüşüm
(11010100)2 = 212
İkili sayı sisteminden on altılı sayı sistemine dönüşüm
(11010100)2 = (D4)16
Örnek on altılı sayı: DF82
On altılı sayı sisteminden onlu sayı sistemine dönüşüm (DF82)16 = 57218
On altılı sayı sisteminden sekizli sayı sistemine dönüşüm
(DF82)16 = (157602)8
On altılı sayı sisteminden ikili sayı sistemine dönüşüm
(DF82)16 = (1101111110000010)2

