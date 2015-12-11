# Vje-tina-2015---Projekt
Project for c#

Projekt: <b>LAN SoundStream</b>

Aplikacija za Windows 10 pomoæu koje je moguæi stream zvuka sa jednog raèunala/mobitela na drugo raèunalo/mobitel preko lokalne mreže.

(U daljnjem tekstu pod "raèunalo" se misli na ureðaj koji ima instaliran Windows 10, bilo mobitel ili raèunalo (ili nešto treæe?))

Recimo da imamo raèunalo koje nema zvuènu karticu ili je pokvarena. Umjesto kupnje nove zvuène kartice, što je skupo ili nezgrapno (recimo ako je u pitanju laptop), a imate drugo raèunalo na raspolaganju koje ima funkcionalnu zvuènu karticu, i oba raèunala su umrežena, možemo instalirati ovaj program na oba raèunala, postaviti da jedno bude izvor (source) zvuka (nepotpuno funkcionalno raèunalo), a drugo odredište (destination) zvuka (funkcionalno raèunalo) i time imati omoguæen zvuk na nefunkcionalnom raèunalu.

Program bi imao dva naèina rada: za izvor i za odredište zvuka.
//PROBLEM: izvor zvuka = raèunalo koje šalje zvuk drugome ili raèunalo koje emitira zvuk koji primi od drugog raèunala? rješenje: sender i receiver? igra s nazivima!!

Odredišnim naèinom rada bi u poèetku odredišno raèunalo bilo dostupno na lokalnoj mreži i èekalo da se neko izvorišno raèunalo poveže s njim.

Izvorišnim naèinom rada bi se u poèetku otvorio popis dostupnih odredišnih raèunala i moguænost odabira jednog od njih.
//FUTURE PLANS: password protected connection?
//FUTURE PLANS: moguænost odabira više raèunala?

Jednom kada su raèunala povezana može zapoèeti slanje streama zvuka s izvorišnog na odredišno raèunalo, koje traje dok god postoji mrežna povezanost raèunala.

Moguæe je mijenjanje glasnoæe i izvora i zvuka.
//FUTURE PLANS: kvaliteta zvuka?