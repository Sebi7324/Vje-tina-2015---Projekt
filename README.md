# Vještina-2015 - Projekt: LAN SoundStream
Project for C#

### Projekt

UWP Aplikacija za Windows 10 pomoću koje je omogućen stream zvuka sa jednog računala/mobitela na drugo računalo/mobitel preko lokalne mreže.

Napomena: U daljnjem tekstu pod "računalo" se misli na uređaj koji ima instaliran Windows 10, bilo mobitel ili računalo (ili nešto treće?).

### Primjer
Recimo da imamo računalo koje nema zvučnu karticu ili je pokvarena. Umjesto kupnje nove zvučne kartice, što je skupo i/ili nezgrapno (recimo ako je u pitanju laptop), a imate na raspolaganju drugo računalo koje ima funkcionalnu zvučnu karticu i oba računala su umrežena, možemo instalirati ovaj program na oba računala, postaviti da jedno bude izvor (source) zvuka (nepotpuno funkcionalno računalo), a drugo odredište (destination) zvuka (funkcionalno računalo) i time imati omogućen zvučni izlaz na nefunkcionalnom računalu.

### Detalji
Program bi imao dva načina rada: 
* za izvor zvuka
* za odredište zvuka.


Izvorišnim načinom rada bi se pomoću lokalne IP adrese (koju upišemo na početku) ostvarila mrežna veza između dva računala i bilo omogućeno streamanje zvuka s tog računala.

Odredišnim načinom rada bi odredišno računalo bilo dostupno na lokalnoj mreži i čekalo da se neko izvorišno računalo poveže s njim. Jednom kad se poveže bi računalo zvuk koji dobije slalo na vlastiti zvučni izlaz.

Veza i stream traju dok god postoji mrežna povezanost računala ili dok se veza ne prekine ručno.

### Problemi:
1. nazivi: izvor zvuka = računalo koje šalje zvuk drugome ili računalo koje emitira zvuk koji primi od drugog računala? ponuđena rješenja:
   * emitter i receiver?
   * origin i clone?
   * source i destination?

### Planovi za budućnost:
* izvorišnim načinom rada bi se u početku otvorio popis dostupnih odredišnih računala i mogućnost odabira jednog od njih
* promjena glasnoće i izvora i zvuka
* povezivanje osigurano lozinkom
* mogućnost odabira više računala istovremeno
* promjena kvalitete zvuka
* daleka budućnost: izrada aplikacije za sve platforme (iOS, Android, Windows Phone, MacOS, Linux...); naglasak na Raspberry PI - idealan, čak i novi PI Zero!
