# Hollow-Knight-magyar
Hollow Knight + minden hivatalos kiegészítő (a Pale Court kivételével) magyar nyelvű verziója. Közel 2 év munka után elkészült a teljes játék fordítás. Bár beismerem 1-2 helyen lehettem volna kicsit kreatívabb (a jövőben talán vissza is térek rá), de nagyon remélem, hogy összességében egy élvezhető és hiteles fordítás lett. 

Az implementálás folyamata:

1. Először is kell egy Hollow Knight "mod betöltő/telepítő". Ennek a segítségével minden elkészült modot be lehet tölteni a játékba. 
  Az alábbi linkeken tudjátok elérni:
      - Ez a hivatalos weblink: https://themulhima.github.io/Lumafly/
      - A githubos verzió: https://github.com/TheMulhima/Lumafly

Tudomásom szerint nincs különbség a kettő között.

2. Miután letöltött a "mod betöltő" (esetünkben Lumafly), indítsuk el (ha ez nem történt meg automatikusan). A következő ablakot kell látni.
![lumafly_main](https://github.com/user-attachments/assets/b6a99e52-3c77-4b86-8416-3151cf4f610c)
3. Nyomjunk rá a felső menüben látható "Mods" fülre, majd keressünk rá a "LanguageSupport"-ra a Mod Search keresőnél. Majd a képen is látható "Install" gomb lenyomásával töltsük le a modot. 
![lumafly_mod](https://github.com/user-attachments/assets/1f1a87e3-d4c3-4218-9031-97e487ccd0d6)
4. Utána meg kell találni a játék mappáját. Ha manuálisan nem sikerül megtalálni, akkor rányomhatunk jobb klikkel a játékra a steam könyvtárban, majd 'Manage'->'Browse local files', majd menjünk bele a 'hollow_knight_Data' mappába. Itt keressük meg a 'sharedassets0.assets' nevű fájlt, és a helyére másoljuk be a mi verziónkat (Tehát az ebben a repository-ban található 'sharedassets0.assets' fájlt).
![data_mappa](https://github.com/user-attachments/assets/57013170-0844-4d61-8091-286a574e4e58)
5. Ezután a következő útvonalon láthatjuk az általunk letöltött mod tartalmát: *\Managed\Mods\LanguageSupport\LanguageSupport. A különböző mappákban a különböző nyelvekre lefordított szövegek találhatóak. Ide kell bemásolni az innen letöltött 'HU' nevű mappánkat.
![lansupport_languages](https://github.com/user-attachments/assets/04502eab-063d-4f56-a7e1-91a561ff3be6)
6. Végül indítsuk el a játékot. Ha minden a tervek szerint történt, akkor a nyelvek között elérhető lesz a magyar.

Ismert hibák:
1. Ha a magyar nyelv beállításával lépsz ki a játékból, akkor a játék következő elindításakor, még a fő menü előtt, meg fogja kérni, hogy válassz nyelvet (ahol nem elérhető a magyar). Valószínüleg azért, mert a magyar nyelv nem volt benne az eredeti fájlokban, és a rendszer ott még nem ismeri fel. Ennél fogva miután kiválasztottunk egy nyelvet és megjelenik a fő menü, ismét be kell állítani a magyar nyelvet a beállításokban.
2. Ha a magyar nyelv beállításával nyitod meg a 'Játék' nevű menüpontot, ahol a nyelv beállítás is található, akkor a nyelv nevére angolt (English) ír. Ez nem befolyásol semmit, de megkavaró lehet.
3. Egy két 'ő' és 'ű' formátuma eltérhet a többitől a menüben. Ezek különleges betük, amiket alapvetően a játék nem ismer fel. Ezt külön kellett megoldani, és sajnos pár helyen nem teljesen emeli be jól. Ezért van szükség a módosított 'sharedassets0.assets' fájlra. Nagyon nagy köszönet Márton Pajer-nek a módosított fájlért.

Nagyon szépen köszönöm a kedves bátyámnak és édesanyámank is a segítséget.

Amennyiben vannak észrevételetek, vagy ötletek fordításokra (mondjuk a neveknél), akkor nyugodtan írjátok meg itt, vagy a discordomra -> Blash#2332.

UI: Úgy tudom nemrég készült el egy másik fordítás is, ami nem sokkal az enyém előtt jelent meg. Ezek után gondolkodtam, hogy publikáljam-e az én verziómat, de gondoltam ha már megcsináltam akkor ne legyen hiába.
