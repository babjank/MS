# MS

Tema: Vjerojatnost

Sadržaj:
0.Uvod
Malo povijesne podloge i osnovni koncepti vjerojatnosti. Prikazan kako se jednostavan pokus pretvara u vjerojatnost te napisane dvije jednostavne funkcije njeno računanje.

1.Vjerojatnost
Napisane neke korisne formule koje se često koriste.

2.Slučajne varijable
Teorija iza diskretnih i neprekidnih slučajnih varijabli. Prikazan graf fje distribucije za njajednostavniju - Bernulijeva distrobuciju. Osim toga prikazana jedna diskretna (Binomna) i neprekidna (Normalna) slučajna varijabla. Za diskretne varijable sam sama implementirala njihove funkcije gustoće i distribucije u pythonu, dok za normalnu koristila funkcije iz biblioteke scipy.stats.norm. Za sve sam usporedila grafove za različite vrijednosti parametra.

3.Matematičko očekivanje
Napisano kako se računa očekivanje i varijanca iz funkcija gustoće te napravljen primjer računanja toga pomoću sympy biblioteke za Binomu slučajnu varijablu.

4.Linearna zavisnost
Za razne slučajne varijable računat njihov Pearsonov koeficijent te shvaćanje kakve izmjene utječu na njihovu linernu zavisnost pomoću grafičkih prikaza.

5.Opisna statistika i rad sa podacima
Uzela sam tablicu evidencije dolazaka članova na aktivnosti u 1.kvartalu ove godine te na njima prikazala bar i barh graf. Napisala funkciju gdje je moguće odabrati koje vrijednosti iz opisne statistike želim izračunati. Koristila sam biblioteke pandas i xlrd za to.
Također prikazano na kraju kako bi se moglo koristiti widgete za interaktivan i kontinuirani rad sa tim podacima.

Napomene:
-pri kompajliranju čitave bilježnice će stati na ćelijama gdje se koristi input naredba, tamo slobodno za početak možete upisati samo 0 pa kasnije isprobati druge mogućnosti
-u widgetu treba samo birati imena osoba koje želite upisati da su bili na toj aktivnosti i onda pokrenuti za svakoga ćeliju ispod kako bi se spremilo
