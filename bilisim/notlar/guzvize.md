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

Yazilim(Software): Yaz??l??m program ve veri olmak ??zere iki unsurdan olu??ur.

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
    - Disk Birlestirme: Par??alanma, sabit diskinizin bilgisayar??n??z?? yava??latabilecek fazladan i??lem yapmas??na yol a??ar
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

Haziran **1996** tarihinde **T??B??TAK** b??nyesinde Ulusal Akademik A?? ve Bilgi Merkezi (**ULAKB??M**) ad??yla bir merkez kurulmu??tur

## Bilgisayar Aglari

A???? olu??turan bile??enler
- A?? i??letim sistemi yaz??l??m??
- Sunucu (Server)
- ??stemci (Client)
- ??leti??im protokolleri

A???? olu??turan cihazlar
- A?? arabirim kart?? ??? Ethernet kart?? (NIC): **Fiziksel(MAC)** adresine sahiptir.
- Da????t??c?? (Hub)
- Anahtar (Switch)
- Y??nlendirici (Router)

A?? ????letim Sistemi Yaz??l??m??:
- A?? i??letim sistemi (Network Operating System - NOS) a?? i??levlerinin y??netilmesine olanak sa??layan bir yaz??l??md??r.
- En pop??ler olanlar?? **Novell NetWare**, **Linux**, **Windows Server**, **Mac OS Server**'d??r

Co??rafi Ko??ullara G??re A????n S??n??fland??r??lmas??
- Yerel Alan A???? (Local Area Network ??? LAN)           : Bir bolgedeki(or. ev) internet agidir.
- Metropol Alan A???? (Metropolitan Area Network ??? MAN) : Lan'larin birlesimidir.
- Geni?? Alan A???? (Wide Area Network ??? WAN)            : Tum internet agidir.

### Sunucu(Server)
- Bir a??da di??er kullan??c??lar taraf??ndan eri??ilen bilgisayardir.
- Gorevine gore adlandirilir.(file server, print server, database server, web server)

### Istemci(Client)
- Bir a?? ??zerinde, sunucu bilgisayarlardan hizmet alan kullan??c?? bilgisayarlar??d??r.
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

Internet yoluyla insanlar??n kullan??m??na sunulmu?? olan her metnin, resmin ya da belgenin kendine ait ve tek olan bir adresi vard??r ve buna URL (Uniform Resource Loader - ??zg??n Kaynak Adresi) ad?? verilir 

http:// www.cu.edu.tr /Content/Asp/Turkish/index.asp

- http                  : Protokol(Iletisim Kurali) adi
- cu.edu.tr             : Alan adi(domain)
- /Content/Asp/Turkish/ : Klasorler
- index                 : Dosya ismi
- .asp                  : Dosya uzantisi

## Web
Web kavram??, CERN'de bir bilgisayar programc??s?? olan **Tim Berners Lee**'nin HTML adl?? bilgisayar dilini bulup geli??tirmesiyle olu??mu??tur

### HTML
- HTML - Zengin Metin ????aret Dili - Hyper Text Markup Language
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

**??nternette arama yaparken dikkat edilmesi gereken noktalar**
- Aranan kelimelerin sonunda ekler varsa bu ekler kald??r??lmal??d??r.  ??rnek; "protokoller" yerine "protokol???
- Arama yapt??????n??zda arama sayfas??nda ??ok fazla say??da site geliyorsa aramay?? daraltabilirsiniz.  ??rnek; " G??venlik" yerine " A?? G??venli??i"
- Arad??????n??z kelimelerinin aras??nda sadece bo??luk b??rak??lmal?? ya da arama operat??rlerinden ( + , ", - ) biri kullan??lmal??d??r.
- + Operat??r??: S??k kullan??lan bir kelime istedi??iniz sonucu alman??zda ??nemliyse, kelimenin ba????na ???+??? koyarak aramaya dahil edebilirsiniz. ??rne??in: Star Wars Episode +I
- " Operat??r??: Ozellikle tirnak icine alinan kelimenin birebir bulundugu siteler arani. ??rne??in: "Star Wars Episode I"
- - Operat??r??: Arad??????n??z terimin birden fazla anlam?? varsa istemedi??iniz anlam?? ifade eden kelimelerin ??n??ne eksi (???-???) i??areti koyarak arama i??leminizi daha da ??zelle??tirebilirsiniz.  ??rne??in: ??ay -akarsu
- ~ Operat??r??: Bir kelimenin yan?? s??ra e??anlaml??lar??n??n da aranmas?? i??in kelimenin hemen ??n??ne bir tilde i??areti (~) ekleyin.  ??rne??in: ~g??da de??erleri sonucunda besin de??erleri de gelir.
- OR Operat??r??: Birka?? kelimeden yaln??zca birine sahip olabilecek sayfalar?? aramak isterseniz, kelimeler aras??na OR (b??y??k harfle) operat??r??n?? ekleyin.  ??rne??in: ??ukurova OR ??niversite
- Filetype Operat??r??: Belirli bir dosya t??r??nde arama yap??lmak istenirse dosya t??r?? filetype:dosya_uzant??s?? ??eklinde verilir.  ??rne??in: filetype:pdf ??ukurova

## Dosya Paylasimlari

- **Peer-to-peer** sunucu yerine bilgisayarlarin dogrudan birbirine veri gonderdigi ag sistemine verilen addir.

## Dosya Payla????m Yaz??l??mlar??
- Bittorrent (??nternet ??zerinden dosya payla????m yaz??l??m??na ve ayn?? tekni??i kullanan dosya takas sistemine verilen isimdir.)
- gnutella
- eDonkey
- emule
- BearShare
- iMesh
- LimeWire
- Morpheus

## Guvenlik
### K??t?? Ama??l?? Yaz??l??mlar (Malware)
- Bilgisayar sistemlerine zarar vermek, bilgi ??almak veya kullan??c??lar?? rahats??z etmek gibi ama??larla haz??rlanm???? yaz??l??mlara genel olarak verilen ad.
- Genellikle e-posta, kayna???? belirsiz programlar, forum siteleri, korsan oyun dvd ve cd???leri gibi farkl?? yollarla bilgisayarlara bula????rlar.
- En genel k??t??c??l yaz??l??m t??rleri ??unlard??r:
    - Bilgisayar vir??s??
    - Bilgisayar solucan?? (Worm): Kendini yayarak cogalir.
    - Truva at?? (Trojan): Farkli bir program gibi gozukur. (Or. Waterfalls.scr)
    - Casus yaz??l??m (Spyware): Kisinin bilgilerini toplar.
    - Klavye dinleme (Keylogger): Kisinin klavyesini dinleyerek, parola vb. bilgileri toplar.
    - Arka kap?? (Backdoor): Bir sisteme daha sonra tekrar erisebilmek icin koyulan programlardir.

## E-Ticaret

E-ticaretin farkl?? t??rleri vard??r:
- ????letmeler aras?? (B2B - Business To Business),
- ????letmeden-T??keticiye (B2C - Business To Consumer)
- T??keticiler aras?? (C2C ??? Comsumer To Consumer)

SON [MUSTAFA AKKAYA]
