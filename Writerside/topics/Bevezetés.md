# Bevezetés

## Termék célja
Az állatorvosi rendelők hatékony működéséhez elengedhetetlen a páciensek (állatok), tulajdonosok, valamint az alkalmazottak adatainak biztonságos, naprakész és átlátható kezelése. 
A jelen szoftverspecifikációs dokumentum (SRS) egy olyan digitális rendszer specifikációit mutatja be, amely teljes körű megoldást nyújt az állatorvosi praxis adatkezelési és adminisztratív feladataira. Az alkalmazás célja az állatorvosok és az asszisztensek munkájának támogatása, az állatok egészségi állapotának nyomon követése, a kezelések, gyógyszerezések és tulajdonosi adatok rendszerezése, valamint az időpontfoglalások.

> Pénzügyi tranzakciók kezelése opcionális
{style="note"}


## Termék hatálya
A termék hatálya kiterjed az alábbi főbb funkciókra:

- Páciens (állat) nyilvántartás: az állatok kezelési, diagnosztikai és gyógyszerezési adatainak átfogó menedzselése. Az opciók közé tartozik a késői gyógyszerezés esetén értesítések küldése és a páciens azonosítása a nyakkörvén lévő BAR kóddal.

- Tulajdonosi nyilvántartás: a tulajdonosok személyes adatainak kezelése, beleértve az azonosítást lakcímkártyával vagy személyi igazolvánnyal, a kapcsolattartási adatok nyilvántartását és az időpontfoglalási rendszerhez való hozzáférést.

- Alkalmazottak nyilvántartása: munkavállalói beléptetés és jogosultságkezelés felhasználónév és jelszó, illetve jelszó nélküli bejelentkezés (passwordless) segítségével.

- Számlázási funkciók: kezelések után automatikus díjbekérő kiküldése a tulajdonos részére.

> Számlázási funkció, passwordless bejelentkezés, és nyakörvön lévő BAR kód elkészítése opcionális.
{style="note"}

> A szoftver hozzájárul az állatorvosi rendelők napi munkafolyamatainak optimalizálásához, automatizálásához, valamint a pontosság és ügyfélélmény javításához.

## Termék hatása
A szoftver segít csökkenteni a manuális adminisztráció terheit, növeli a munkafolyamatok hatékonyságát, és minimalizálja az emberi hibák lehetőségét az adatok kezelésében. 

Azáltal, hogy automatizálja a pácienskezelést, gyógyszerezést és időpontfoglalást, az állatorvosi praxisok személyzete több időt fordíthat a betegállatok kezelésére és a tulajdonosokkal való kapcsolattartásra. A szoftver elősegíti a gyors adathozzáférést és könnyű kereshetőséget, növelve ezzel az általános szolgáltatási minőséget.

## Célközönség
A szoftver célközönsége állatorvosi rendelők, klinikák és kórházak, valamint azok személyzete: állatorvosok, asszisztensek és adminisztrátorok. Emellett a tulajdonosok is célcsoportként szerepelnek, mivel számukra időpontfoglalási és kapcsolattartási funkciókat biztosít a rendszer. A rendszert úgy terveztük, hogy könnyen kezelhető legyen mind a technikailag jártas, mind a kevésbé tapasztalt felhasználók számára.

## Felhasználási módok
A szoftvert a különböző felhasználói szerepkörök eltérő módon használhatják:

- Állatorvosok: állatok adatainak és kezelési információinak nyomon követése, gyógyszerezési tervek kezelése.
- Asszisztensek: időpontfoglalások menedzselése, adminisztratív feladatok ellátása, tulajdonosi kapcsolattartás.
- Tulajdonosok: állataik egészségügyi adataihoz való hozzáférés, időpontok foglalása, értesítések fogadása a kezelésekkel és gyógyszerezéssel kapcsolatban.
- Adminisztrátorok: jogosultságkezelés, alkalmazottak beléptetése és számlázás.