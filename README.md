# FreeTR Sablonok

Sablon fájlok a [FreeTR](https://freetr.hu) programhoz.

## Használat

A .sbl fájlokat csak be kell másolni a FreeTR **Sablon** könyvtárába

## Szerkesztés

A sablon fájlok közönséges .ftr fájlok .sbl kiterjesztéssel. 

1. nevezd át az .sbl fájlt .ftr-re
2. nyisd meg a FreeTR-ben
3. végezd el a módosításokat, mentsd el
4. nevezd át a .ftr fájlt .sbl-re

## Sablonok

### EING_igeo.sbl

Új **mérési vázlat** rétegcsoport

- 300: egyéb
- 301: megszűnő jel
- 302: változási vázrajz főbb méretek
- 303: új részletpontok pontszámai
- 304: ingatlan-nyilvántartási térkép méretei
- 305: eredeti/korábbi mérési vázlat adatai
- 306: helyszíni mérés adatai / abszcissza
- 307: kitűzési méretek / ordináta
- 308: fonott kerítés
- 309: sövény
- 310: fa kerítés
- 311: drót kerítés
- 312: 0.5 mm-es vonal
- 313: 0.4 mm-es vonal
- 351: jog határa (vonal) -> szélső kontúr vonalhoz
  
Új vonaltípusok 

- 27: jog határa (0.5 mm, 30-20 szaggatott) -> 351-es réteghez beállítva

Új jelkulcsok

- 205: nyíl (2.5 mm) - vezetékjog szélességekhez
- 206: nyíl (4.0 mm)
- 253: szám karika
- 254: pont nullkör
- 300: északjel

### DAT_igeo.sbl

Új **mérési vázlat** rétegcsoport

- 300: egyéb
- 301: megszűnő jel
- 302: változási vázrajz főbb méretek
- 303: új részletpontok pontszámai
- 304: ingatlan-nyilvántartási térkép méretei
- 305: eredeti/korábbi mérési vázlat adatai
- 306: helyszíni mérés adatai / abszcissza
- 307: kitűzési méretek / ordináta
- 308: fonott kerítés
- 309: sövény
- 310: fa kerítés
- 311: drót kerítés
- 312: 0.5 mm-es vonal
- 313: 0.4 mm-es vonal
  
Új vonaltípusok 

- 27: jog határa (0.5 mm, 30-20 szaggatott) -> 53-as réteghez beállítva

Új jelkulcsok

- 205: nyíl (2.5 mm) - vezetékjog szélességekhez
- 206: nyíl (4.0 mm)
- 253: szám karika
- 254: pont nullkör
- 300: északjel
