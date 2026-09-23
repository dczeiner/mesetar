# Esti mesetár

Családi mesekönyvtár egy háromévesnek: hivatalos, ingyenes archívumos sorozatok és ellenőrzött
YouTube-listák, mért epizódhosszakkal.

Statikus oldal, nincs build. A `index.html` mellett a `manifest.json` és az ikonok teszik
telepíthetővé: iPhone-on Safari → Megosztás → Hozzáadás a Főképernyőhöz.

A `thumbs/` mappa képkockái a hivatkozott műsorokból származnak, kizárólag családi,
nem nyilvános használatra — az oldal `noindex`, és a `robots.txt` tiltja a bejárást.
