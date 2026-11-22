# Gold Hotel

2D naršyklės žaidimas (viešbutis matomas iš šono: apačioje registratūra, aukštuose kambariai): perimi apšiurusį viešbutį, tikrini svečius, gaudai blogiukus ir augini viešbutį pasaulis po pasaulio.

**Kaip paleisti:** atsisiųsk `index.html` ir atidaryk naršyklėje. Serverio ir interneto nereikia.

## Valdymas
| Klavišas | Veiksmas |
|---|---|
| ← / → | vaikščioti |
| ↑ / ↓ (lifte) | važiuoti į kitą aukštą |
| Pelė / pirštas | spustelk ten, kur nori eiti (liftu nuvažiuos pats) |
| Z | visas viešbutis / priartinti |
| Tarpas | skanuoti svečią prie stalo |
| E / X | įleisti / neįleisti |
| P | kviesti policiją (suima svečią šalia tavęs) |
| R | atstatyti susprogusį kambarį |
| U | tobulinimai |

## Golden restoranas
Parduotuvėje galima atidaryti restoraną (kairėje nuo lifto) ir jį gerinti iki 7 žvaigždučių. Svečiai ateina iš gatvės, užsisako prie prekystalio, šefai gamina virtuvėje, padavėjas atneša maistą, svečiai pavalgo ir sumoka.

## Struktūra
- Visas žaidimas yra viename `index.html` faile (HTML + CSS + JS, Canvas).
- Visi balanso skaičiai ir pasaulių duomenys laikomi `CONFIG` objekte. Naują pasaulį pridėsi įrašu į `CONFIG.worlds`.
- Sprendimai, kurių nėra scenarijuje, aprašyti komentare failo viršuje.
- Derinimui: `index.html?debug`, tada klavišas M prideda pinigų.
