**Kreirati aplikaciju koji će imati korisnički interfejs kao što je dato na slici i sledeću funkcionalnost:**

-	Prilikom odabira radio-dugmeta, sadržaj gornjeg polja se briše i adekvatno se menja tekst na labeli:
    
    a)	ako je selektovano radio-dugme 3 najjeftinije ponude, na labeli treba da piše Destinacija, dok
    b)	ukoliko je selektovano radio-dugme Sve ponude za datum, tekst na labeli treba da bude Datum. Tom prilikom tekstualno polje ne treba da menja svoju poziciju na prozoru aplikacije.
    
-	Pritiskom na dugme Prikaži iščitavaju se pdaci iz datoteke ponude.txt sa lokalnog diska (u svakoj liniji datoteke je sadržan ulaz) oblika:
    
    a)	Agencija, Destinacija, datum polaska, broj noćenja, cena u evrima
    
        Kontiki, Kusadasi, 26.06.2013., 7, 200
        
        Filip, Santorini, 29.06.2013., 10, 400
        
        Robinson, Hurgada, 02.07.2013., 14, 850
        
        Filip, Tasos, 03.07.2013., 10, 300
        
        Robinson, Tasos, 25.06.2013., 7, 200

    b)	ako je izabrano radio-dugme 3 najjeftinije ponude, prikazujuse podaci o tri najjeftinije ponude za destinaciju čiji je naziv unet u gornje polje
        
        ukoliko među njima ima više ponuda sa istom cenom, one su sortirane rastuće po datumu polaska (ukoliko im je i datum polaska isti, prikazati ih u proizvoljnom redosledu),
        
        ukoliko nema nijedne ponude za odabranu destinaciju, ispisuje se poruka tome,
        
        ukoliko ih ima, ali manje od 3, prikazuju se sve koliko ih ima.
        
        ukoliko korisnik nije popunio polje, ispisati poruku o tome.
        
    c)	ako je izabrano radio dugme sve ponude za datum, u proizvoljnom poretku, prikazuju se podaci o svim ponudama koje će biti u toku (započete, ali ne i završene) na dan unet u gornje tekstualno polje
        
        ukoliko nema takvih ponuda, ispisuje se poruka o tome
        
        ukoliko u tekstualnom polju nije ispravan podatak, ispisaće odgovarajuću poruku o tome.
        
![6](https://scontent.fbeg6-1.fna.fbcdn.net/v/t1.15752-9/96423168_762013134561047_5089613168624271360_n.jpg?_nc_cat=108&_nc_sid=b96e70&_nc_eui2=AeFddIHceznbcFVCM4a7z-2uFsXSk1OK4GUWxdKTU4rgZT9LdybLzGcpirqSd-cwe7k&_nc_ohc=67b2J-btjScAX-euSHZ&_nc_ht=scontent.fbeg6-1.fna&oh=3a4b7095f8282fe212dd5a1530ed65aa&oe=5EDDBC4E)
