# Gold Hotel

2D naršyklės žaidimas: perimi apšiurusį viešbutį, tikrini svečius, gaudai blogiukus ir augini viešbutį pasaulis po pasaulio.

**Kaip paleisti:** atsisiųsk `index.html` ir atidaryk naršyklėje. Serverio ir interneto nereikia.

## Valdymas
| Klavišas | Veiksmas |
|---|---|
| Rodyklės / WASD | vaikščioti |
| Tarpas | skanuoti svečią prie stalo |
| E / X | įleisti / neįleisti |
| P | kviesti policiją (suima svečią šalia tavęs) |
| R | atstatyti susprogusį kambarį |
| U | tobulinimai |

## Struktūra
- Visas žaidimas yra viename `index.html` faile (HTML + CSS + JS, Canvas).
- Visi balanso skaičiai ir pasaulių duomenys laikomi `CONFIG` objekte. Naują pasaulį pridėsi įrašu į `CONFIG.worlds`.
- Sprendimai, kurių nėra scenarijuje, aprašyti komentare failo viršuje.
- Derinimui: `index.html?debug`, tada klavišas M prideda pinigų.
