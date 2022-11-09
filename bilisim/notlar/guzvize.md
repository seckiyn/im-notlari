# Bilgisayarlarin Temel Ozellikleri

1. Girdi(or. Klavye) ve Cikis(or. Ekran) islemleri
2. Aritmetik islemler
3. Veri Saklama: or. fotograflar
4. Program Calistirma(Isletimi)

Girdi elemanlari dis dunyadan bilgisayara bilgi iletir.

Cikis elemanlari bilgisayardan islenen bilgiyi dis dunyaya iletir.

Ornegin:
- Klavye ile yazmak(girdi) yazilan seyi yazici ile cikartmak(cikti)
- Kamera ile fotograf cekmek(girdi) onu ekranda goruntulemek(cikti)

**Giris Birimleri**:
- Klavye
- Tarayici
- Fare
- Mikrofon
- Kamera
- Dokunmatik Ekran
- Barkod Okuyucu

**Cikis Birimleri**:
- Yazici
- Ekran
- Kulaklik
- Hoparlor

# Bilgisayari Olusturan Parcalar

Bilgisayar kasasi, monitor, klavye, fareden olusur.

1. Bilgisayar kasasi; icindekiler:
    - Ana Kart                              : Diger parcalarin oturtuldugu yer.
    - BIOS yongasi                          : BIOS'u iceren cip.
    - Veri Yollari                          : Parcadan parcaya bilgi iletimi.
    - Ekran Karti(Graphics Processing Unit) : Goruntuyu isler.
    - Ses Karti                             : Sesi isler.
    - Fan                                   : Sogutma amaci ile kullanilir.
    - Hard Disk(Sabit Disk)                 : Depolama
    - Flash Disk; CD-DVD; Disket; Blu-Ray   : Harici depolama
    - Kamera                                : Girdi
    - CPU(Central Processing Unit)          : **Islemci**, Merkezi Islem Birimi, matematik yapar
    - RAM(Random Access Memory)             : Ana bellek, gecici bellek
    - ROM(Read-Only Memory)                 : Yalniz-okunabilir bellek, degistirilemez
    - On Bellek(Cache Memory)               : RAM-Bellek arasi veri transfer hizini duzenler
2. Ekran(Monitor): Cikis islemi
3. Fare(Mouse): Girdi islemi
4. Klavye(Keyboard): Girdi islemi; tuslarin gorevi:
    - Enter                       : Onaylama(tamam) veya yeni satira gecme
    - Fonksiyon(F1, F2, ..., F12) : F1 genelde yardim goruntulemedir.
    - Yon(Ok) Tuslari             : Sayfada hareket etme
    - Home                        : Tek basina imleci satir basina getirir, CTRL+Home dosyanin en basina getirir.
    - End                         : Home tusunun yaptiginin tam tersini yapar.
    - Page Up                     : Bir sayfa yukari
    - Page Down                   : Bir sayfa asagi
    - Shift                       : Harflerin buyuk yazilmasini ya da bir tusun ikincil karakterinin yazilmasini saglar.
    - CAPS LOCK                   : Harflerin buyuk yazilmasini saglar.
    - Num Lock                    : Rakama gecer.
    - Insert                      : ...
    - Delete                      : Imlecin sol tarafini siler.
    - Backspace                   : Imlecin sag tarafini siler.
    - Tab                         : Paragraf ekler.
    - Kontrol(CTRL)               : Coklu secim saglar.
    - Esc(Escape=Kacis)           : Iptal eder.
    - Alt                         : Tek basina gorevi yoktur.
    - Ara Cubugu(Space Bar)       : Bosluk birakir.

### Sabit Disk Parametreleri
- Disk Donus Hizi(RPM=Rotate Per Minute) : Diskin dakikada donus hizidir.
- Tampon(On) Bellek(Cache veya Buffer)   : Diskin hizini arttirir.
- Konumlama suresi(Seek Time)            : Disk uzerine okuma yazma suresi.
- Kapasite                               : Depolayabilecegi veri miktari

### HHD ve SSD
- HHD(Hybrid Hard Drive): Melez bir yapidir.
- SSD(Solid State Drive): Kati hal surucusu. Mekanik olmadigi icin hizlidir.

### USB(Universal Serial Bus)
...

### Hafiza Karti
...

### Optik Surucu
- Isik ile bilgileri kaydedip okur.
- CD, DVD, BLU-RAY ornek verilebilir.

### Disket
- Manyetik veri saklama birimidir.

### Monitorler
#### Ekran Ozellikleri
- Cozunurluk: Piksel ile olculur.
- Ekran Boyutu: Ekranin kosegen uzunlugu. Inc ile olculur.
- En/Boy Orani(Aspect Ratio): En boy oranidir. Or. 4:3 ya da 16:9(Wide Screen)
- LCD(Liquid Crystal Display): Sivi Kristal Ekran
# Yazilim, Donanim, Program ve Veri Kavrami

Donanim(Hardware): Bilgisayarin fiziksel kismi.

Yazilim(Software): Yazılım program ve veri olmak üzere iki unsurdan oluşur.

Program: Kurallari takip eder. Programlama dilleri ile yazilir. Compiler ile makina koduna cevrilmesi gerekir.

Veri: Girdiden islenmemis bilgilerdir.

# Dosya ve Klasor Kavrami

Dosya(File): **dosyaadi**.**dosyauzantisi** seklindedir. Word, Excel kullanilir. Uzantisi(hikmet.**txt**), kapladigi bir yer(byte olarak), kaydedildigi tarih ve saati vardir. Yeni sistemlerde(windows) uzanti zorunlulugu yoktur.

Dosya uzantisi dosya ile ilgili bilgiler verir.

**F2** kullanilarak **dosya ismi** degistirilebilinir.

Windows uzerinde klasorlerde /, \, :, ?, *. ", <, >, | **karakterleri bulunamaz.** 

**Delete** tusu dosyayi **Geri Donusum Kutusu**'na gonderir. **Shift + Delete** **tamamen** siler.

**Windows Gezgini** kullanilarak dosyalar ve klasorler incelenebilinir.

**Kes-Kopyala-Yapistir Yontemleri:**
1. Kopyalama:
    - **Windows Gezgini** uzerinde **Duzenle menusu** ile,
    - **Sag tik** ile cikan menu uzerinden,
    - **CTRL + C** tus kombinasyonu ile,
    - **Suruklenirken** **CTRL** tusuna basili tutulmasi,
2. Kesme:
    - **Windows Gezgini** uzerinde **Duzenle menusu** ile,
    - **Sag tik** ile cikan menu uzerinden,
    - **CTRL + X** tus kombinasyonu ile,
    - **Shift** tusu basili iken suruklenmesi
3. Yapistirma:
    - **Windows Gezgini** uzerinde **Duzenle menusu** ile,
    - Sag tik menusu ile,
    - **CTRL + V** tus kombinasyonu ile

**ALT + ENTER** ile dosya-klasor ozellikleri penceresi acilir.


**Uzanti ornekleri:**
- doc veya docx: Word(_doc_ument)
- xls veya xlsx: Excel(e_X_ce_L_ _S_heet)
- gif, jpg, png : Resim dosyalari
- pps, ppt veya pptx: PowerPoint
- bas: Basic(_bas_ic programlama dili ile yazilmis programlar)
- for: Fortan(_for_tran ile yazilmis programlar)
- exe: Calistirilabilir dosyalar(programlar, _exe_cutable)
- txt: Text-metin dosyasi
- bmp: Tarayici ile taranmis resim
- sys: Sistem dosyalari(_sys_tem)
- dll: Microsoft windowsta kullanilan kutuphane dosyasi

## Byte Kavrami

- 1 Byte     = 8 bit
- 1 MegaByte = 1024 Byte
- 1 GigaByte = 1024 MegaByte
- 1 TeraByte = 1024 GigaByte

## Klasor(Dizin; Folder; Directory)

- Dosyalari birbirinden ayirir.
- C:// **root(kok)** ana klasordur.

# Windows Isletim Sistemi

Isletim Sistemleri Ornekleri:
- Windows(Vista, XP, 10, 11)
- DOS
- XENIX
- MACINTOSH(Mac)
- Linux(Ubuntu, **Pardus**: TUBITAK'in gelistirdigi sistem)

## Windows Masaustu Ogeleri

- **Bilgisayarim**: **Windows Gezginini** acar.
- Ag Komsulari: Diger bilgisayarlara ulasilir.
- Belgelerim: **Windows Gezginini**'nde Belgeler klasorunu acar.
- Geri Donusum Kutusu: Yakinda silinen dosyalar buradadir.
- Internet Explorer: Internet tarayicisi

## Windows Programlari
- Calistir: herhangi bir programin calistirilmasini saglar
- Ekran Alintisi Araci: Ekranin bir kismini kaydedilmesini saglar
- Sistem Araclari:
    - Disk Temizleme: Diski temizler
    - Disk Birlestirme: Parçalanma, sabit diskinizin bilgisayarınızı yavaşlatabilecek fazladan işlem yapmasına yol açar
    - Gorev Zamanlayici: Bir programi otomatik olarak acilmasini saglar.
    - Sistem Bilgisi: Bilgisayar bilgilerini bulundurur.
    - Sistem Geri Yukleme: Gerekirse bilgisayari eski bir zamandaki durumuna geri dondurur.

## Gorev Cubugu

Programlarin kolayca acilabilecegi ekranin altinda bulunan bar. Sol tarafinda **Baslat** simgesi bulunur.

## Ara Komutunun Kullanimi

'*' ve '?' karakterler jokerdir. Herhangi bir harf yerine gecebilirler. Ornegin:
- b* : b ile baslayan tum dosyalar
- br*: br ile baslayan tum dosyalar
- *.doc: .doc ile biten(Word dosyalari)
- *.xls: .xls ile biten(Excel dosyalari)
- a*4.doc: a ile baslayip 4.doc ile biten tum dosyalar
- mat??n.*: mat ile baslayip iki rastgele karaterden sonra n. gelen herhangi bir sey ile biten tum dosyalar

## Denetim Masasi

Bilgisayar ayarlari burada bulunur.

## Klasorler ile Ilgili Islemler

Shift basili ise ilk tiklanan noktadan baslayip son tiklanan noktadaki tum dosylari secer.

CTRL basili tutarak rastgele dosyalar secilebilinir.

# Internet

Aglarin agidir. TDK tarafindan **Genel Ag** olarak Turkce'lestirmesi onerilmistir.

www(World Wide Web): Tarayici ile gosterilir.

Web Sayfasi: Adresleri vardir.

Ornek: http://www.cu.edu.tr
- www: World Wide Web
- cu : Domain Name(Alan adi)
- edu: Uzanti(_Edu_cation)
- tr : Turkiye alan kodu

Ornek Uzantilar
- .com : Ticari kuruluslar(_com_mercial)
- .gov : Resmi kurumlar(_gov_erment)
- .edu : Egitim kurumlari(_edu_cation)
- .mil : Askeri kurumlar(_mil_ilatary)
- .org : Organizasyonlar(_org_anization)
- .net : Internet servis saglayicilar

## Internetin Tarihcesi

**1969**'da ABD Savunma Bakanligi - Ileri Arastirma Proje Ajansi (**DARPA**) tarafindan olusturulan **ARPANET** projesi ile baslar.

Turkiye'nin ilk internet baglantisi 12 Nisan 1993 PTT'den saglanan hat kullanilarak **ODTU**'den ABD'de bulunan **NSFNet**(National Science Foundation Network)'e baglanilarak gerceklistirildi.

Haziran **1996** tarihinde **TÜBİTAK** bünyesinde Ulusal Akademik Ağ ve Bilgi Merkezi (**ULAKBİM**) adıyla bir merkez kurulmuştur

## Bilgisayar Aglari

Ağı oluşturan bileşenler
- Ağ işletim sistemi yazılımı
- Sunucu (Server)
- İstemci (Client)
- İletişim protokolleri

Ağı oluşturan cihazlar
- Ağ arabirim kartı – Ethernet kartı (NIC): **Fiziksel(MAC)** adresine sahiptir.
- Dağıtıcı (Hub)
- Anahtar (Switch)
- Yönlendirici (Router)

Ağ İşletim Sistemi Yazılımı:
- Ağ işletim sistemi (Network Operating System - NOS) ağ işlevlerinin yönetilmesine olanak sağlayan bir yazılımdır.
- En popüler olanları **Novell NetWare**, **Linux**, **Windows Server**, **Mac OS Server**'dır

Coğrafi Koşullara Göre Ağın Sınıflandırılması
- Yerel Alan Ağı (Local Area Network – LAN)           : Bir bolgedeki(or. ev) internet agidir.
- Metropol Alan Ağı (Metropolitan Area Network – MAN) : Lan'larin birlesimidir.
- Geniş Alan Ağı (Wide Area Network – WAN)            : Tum internet agidir.

### Sunucu(Server)
- Bir ağda diğer kullanıcılar tarafından erişilen bilgisayardir.
- Gorevine gore adlandirilir.(file server, print server, database server, web server)

### Istemci(Client)
- Bir ağ üzerinde, sunucu bilgisayarlardan hizmet alan kullanıcı bilgisayarlarıdır.
- Internete giren bilgisayar.

### Iletisim Protokolleri
- TCP/IP protokolleri:
    - Kopru Metni Aktarim Protokolu(HyperText Transfer Protocol - HTTP)
    - Dosya Aktarim Protokolu(File Transfer Protokol- FTP)
    - Basit Posta Aktarim Protokolu(Simple Mail Transfer Protocol - SMTP)
- **HTTP**     : **Web** sayfalarinin aktarilmasini saglar.
- FTP      : Dosya aktarimini saglar.
- SMTP     : Posta gonderimini saglar.
## Internetle ilgili kavramlar

- IP(Internet Protocol): Her bilgisayarin kendine ait numarasi. or. 192.168.2.1
    - Farkli bilgisayarlarin veri yollamak icin kullanilir.
    - Bilgisayarlarin birbirini tanimasini saglar.
    - IPV4(192.168.2.1) ve IPV6(fe80::2682:352b:42c0:1c)(IPV4 yeterli olmadigi icin gelistirilmistir.)
- Alan Adi(Domain Name): IP yerine kelime kullanmak icin gelistirilmistir.
    - Web sitesinin adi ve adresidir.
    - **DNS**(Alan Adi Sistemi - Domain Name System) IP-yi alan adina esler.
- FTP(File Transfer Protocol): Dosya alip gonderme protokoludur.

## URL

Internet yoluyla insanların kullanımına sunulmuş olan her metnin, resmin ya da belgenin kendine ait ve tek olan bir adresi vardır ve buna URL (Uniform Resource Loader - Özgün Kaynak Adresi) adı verilir 

http:// www.cu.edu.tr /Content/Asp/Turkish/index.asp

- http                  : Protokol(Iletisim Kurali) adi
- cu.edu.tr             : Alan adi(domain)
- /Content/Asp/Turkish/ : Klasorler
- index                 : Dosya ismi
- .asp                  : Dosya uzantisi

## Web
Web kavramı, CERN'de bir bilgisayar programcısı olan **Tim Berners Lee**'nin HTML adlı bilgisayar dilini bulup geliştirmesiyle oluşmuştur

### HTML
- HTML - Zengin Metin İşaret Dili - Hyper Text Markup Language
- Internet dilidir.
- En son surumu HTML5'tir.
- Kucuktur ve buyuktur isaretlerini kullanan tag sistemi uzerine kurulmustur. Or <p>Paragraf</p>

## Tarayicilar
- HTML'i isleyen ve goruntuleyen programlardir.
- Internet Explorer, Mozilla Firefox, Google Chrome, Opera, Apple Safari

## Arama Motorlari
- **Robot** internet uzerindeki sitelerini otomatik olarak gezer.
- Bu siteler **indekslenerek**  hizli bir sekilde aranabilir hale getirilir.
- **Kullanici arabirimi** ise bu olusturulan indeksin aranmasini saglar.
- Google, Yandex, Yahoo, Bing ornek verilebilinir.

**İnternette arama yaparken dikkat edilmesi gereken noktalar**
- Aranan kelimelerin sonunda ekler varsa bu ekler kaldırılmalıdır.  Örnek; "protokoller" yerine "protokol“
- Arama yaptığınızda arama sayfasında çok fazla sayıda site geliyorsa aramayı daraltabilirsiniz.  Örnek; " Güvenlik" yerine " Ağ Güvenliği"
- Aradığınız kelimelerinin arasında sadece boşluk bırakılmalı ya da arama operatörlerinden ( + , ", - ) biri kullanılmalıdır.
- + Operatörü: Sık kullanılan bir kelime istediğiniz sonucu almanızda önemliyse, kelimenin başına “+” koyarak aramaya dahil edebilirsiniz. Örneğin: Star Wars Episode +I
- " Operatörü: Ozellikle tirnak icine alinan kelimenin birebir bulundugu siteler arani. Örneğin: "Star Wars Episode I"
- - Operatörü: Aradığınız terimin birden fazla anlamı varsa istemediğiniz anlamı ifade eden kelimelerin önüne eksi (“-”) işareti koyarak arama işleminizi daha da özelleştirebilirsiniz.  Örneğin: Çay -akarsu
- ~ Operatörü: Bir kelimenin yanı sıra eşanlamlılarının da aranması için kelimenin hemen önüne bir tilde işareti (~) ekleyin.  Örneğin: ~gıda değerleri sonucunda besin değerleri de gelir.
- OR Operatörü: Birkaç kelimeden yalnızca birine sahip olabilecek sayfaları aramak isterseniz, kelimeler arasına OR (büyük harfle) operatörünü ekleyin.  Örneğin: Çukurova OR Üniversite
- Filetype Operatörü: Belirli bir dosya türünde arama yapılmak istenirse dosya türü filetype:dosya_uzantısı şeklinde verilir.  Örneğin: filetype:pdf Çukurova

## Dosya Paylasimlari

- **Peer-to-peer** sunucu yerine bilgisayarlarin dogrudan birbirine veri gonderdigi ag sistemine verilen addir.

## Dosya Paylaşım Yazılımları
- Bittorrent (İnternet üzerinden dosya paylaşım yazılımına ve aynı tekniği kullanan dosya takas sistemine verilen isimdir.)
- gnutella
- eDonkey
- emule
- BearShare
- iMesh
- LimeWire
- Morpheus

## Guvenlik
### Kötü Amaçlı Yazılımlar (Malware)
- Bilgisayar sistemlerine zarar vermek, bilgi çalmak veya kullanıcıları rahatsız etmek gibi amaçlarla hazırlanmış yazılımlara genel olarak verilen ad.
- Genellikle e-posta, kaynağı belirsiz programlar, forum siteleri, korsan oyun dvd ve cd’leri gibi farklı yollarla bilgisayarlara bulaşırlar.
- En genel kötücül yazılım türleri şunlardır:
    - Bilgisayar virüsü
    - Bilgisayar solucanı (Worm): Kendini yayarak cogalir.
    - Truva atı (Trojan): Farkli bir program gibi gozukur. (Or. Waterfalls.scr)
    - Casus yazılım (Spyware): Kisinin bilgilerini toplar.
    - Klavye dinleme (Keylogger): Kisinin klavyesini dinleyerek, parola vb. bilgileri toplar.
    - Arka kapı (Backdoor): Bir sisteme daha sonra tekrar erisebilmek icin koyulan programlardir.

## E-Ticaret

E-ticaretin farklı türleri vardır:
- İşletmeler arası (B2B - Business To Business),
- İşletmeden-Tüketiciye (B2C - Business To Consumer)
- Tüketiciler arası (C2C – Comsumer To Consumer)


