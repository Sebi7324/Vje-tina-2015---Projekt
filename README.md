# Vje-tina-2015---Projekt
Project for c#

Projekt: <b>LAN SoundStream</b>

Aplikacija za Windows 10 pomo�u koje je mogu�i stream zvuka sa jednog ra�unala/mobitela na drugo ra�unalo/mobitel preko lokalne mre�e.

(U daljnjem tekstu pod "ra�unalo" se misli na ure�aj koji ima instaliran Windows 10, bilo mobitel ili ra�unalo (ili ne�to tre�e?))

Recimo da imamo ra�unalo koje nema zvu�nu karticu ili je pokvarena. Umjesto kupnje nove zvu�ne kartice, �to je skupo ili nezgrapno (recimo ako je u pitanju laptop), a imate drugo ra�unalo na raspolaganju koje ima funkcionalnu zvu�nu karticu, i oba ra�unala su umre�ena, mo�emo instalirati ovaj program na oba ra�unala, postaviti da jedno bude izvor (source) zvuka (nepotpuno funkcionalno ra�unalo), a drugo odredi�te (destination) zvuka (funkcionalno ra�unalo) i time imati omogu�en zvuk na nefunkcionalnom ra�unalu.

Program bi imao dva na�ina rada: za izvor i za odredi�te zvuka.
//PROBLEM: izvor zvuka = ra�unalo koje �alje zvuk drugome ili ra�unalo koje emitira zvuk koji primi od drugog ra�unala? rje�enje: sender i receiver? igra s nazivima!!

Odredi�nim na�inom rada bi u po�etku odredi�no ra�unalo bilo dostupno na lokalnoj mre�i i �ekalo da se neko izvori�no ra�unalo pove�e s njim.

Izvori�nim na�inom rada bi se u po�etku otvorio popis dostupnih odredi�nih ra�unala i mogu�nost odabira jednog od njih.
//FUTURE PLANS: password protected connection?
//FUTURE PLANS: mogu�nost odabira vi�e ra�unala?

Jednom kada su ra�unala povezana mo�e zapo�eti slanje streama zvuka s izvori�nog na odredi�no ra�unalo, koje traje dok god postoji mre�na povezanost ra�unala.

Mogu�e je mijenjanje glasno�e i izvora i zvuka.
//FUTURE PLANS: kvaliteta zvuka?