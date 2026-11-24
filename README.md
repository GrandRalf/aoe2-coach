# Coach

Build order segéd egy valós idejű stratégiai játékhoz. A képernyő jobb oldalán átlátszó panelen mutatja,
melyik paraszt mit csináljon („7. favágótábort épít, majd fa”), és figyelmeztet, ha a városközpont nem gyárt, vagy ház kell.
Csak a képernyőt olvassa (a felső sáv számait), a játékba nem kattint bele.

Ugyanitt két kisebb segéd is letölthető: **CivHelper** (a néped erősségei és counter-táblája meccs közben) és
**TeamComp** (csapat-összeállítás javaslat a lobbyban).

## Letöltés

A legfrissebb **AoE2Coach.exe** a [Releases](../../releases/latest) oldalon. Telepíteni nem kell, csak elindítani.
A **civhelper.exe** és az **aoeteamcomp.exe** a [Releases](../../releases) listában, a „CivHelper” és „TeamComp” kiadásoknál.

**Automatikus frissítés:** mindhárom program induláskor megnézi, van-e újabb kiadás; ha igen, letölti, kicseréli magát
és újraindul. A tálcán is van **Frissítés keresése**.

## Használat

1. Indítsd el az `AoE2Coach.exe`-t, válaszd ki a build ordert a listából, **Indítás**.
2. Indítsd a meccset. A panel akkor látszik, ha a játék van előtérben (szegély nélküli ablakos módban).
3. A panelen: az épp elhagyott lépés, **aranyban az aktuális**, alatta a következők; a végén elfogynak.

Figyelmeztetések (egész meccs alatt, a felső sávban, a játékidő és a menügombok között):
**A városközpont nem gyárt!** (100 parasztig, ha van 50 élelem és szabad népesség),
**Ház kell!** (hangjelzéssel; 30 parasztig 2, fölötte 5 szabad helynél; 200-nál, gótoknál 210-nél már nem).

**Nyelv / Language:** a menü jobb felső sarkában Magyar / English választható – a panel, a figyelmeztetések, a menü,
a tálca és a build-lépések is ezen a nyelven jelennek meg (a választást megjegyzi).

## Tálcaikon (jobb klikk)

Build order választás · Hangeffektek be/ki · Gótok (210 max népesség) · Build order elölről · Build újratöltése ·
Importálás… · Importálás linkről… · Frissítés keresése · Bezárás

Gyorsbillentyűk: **Ctrl+Alt+→ / ←** következő / előző lépés, **Ctrl+Alt+End** bezárás.

## Saját build orderek

A buildek helye: `Dokumentumok\AoE2 Coach\builds`. Egy [buildorderguide.com](https://buildorderguide.com) exportot
(.txt vagy .json) a menü / tálca **Importálás…** gombjával vehetsz fel, vagy egyszerűen bemásolod ebbe a mappába:
induláskor átalakítja és finomhangolja (kezdés 2 házzal, fatábor, 2 ház + malom, ház + bányatábor).

**Beillesztés / link:** a [buildorderguide.com](https://buildorderguide.com) oldalon a build oldalán nyomd meg az
**Export → RTS** gombot (vágólapra másolja), majd a menü **Beillesztés / link…** gombja (vagy a tálca) a vágólapról azonnal
importálja – txt fájl nem kell. Ugyanez a gomb más build-oldalak linkjét is elfogadja; letölti, magyarra fordítja és
felveszi a listába.

Az angol build orderek lépéseit magyarul mutatja (a fejlesztések neve mellett zárójelben az angol).

Alapból benne: **Hera 23+2 Fast Castle Boom** (bármely nép), **Fast Castle Boom** (bármely nép),
**13 Minute Castle Drop** (Franks).

## CivHelper

Meccs közben bal alul, a súgó fölött kiírja a néped erősségeit, fő bónuszát és egy counter-táblát (lovag / íjász /
gyalogság / lovasíjász / ostrom ellen mit gyárts). A népedet a meccs felvételéből ismeri fel (a felvétel legyen
bekapcsolva), a játék nyelvét követi. Tálca: jegyzet be/ki, frissítés keresése, bezárás.

## TeamComp

A lobbyból olvassa a népeket és a csapatokat, és a saját népedből kiindulva csapat-kombót ajánl térkép és mód
(2v2 / 3v3 / 4v4) szerint. Csak lobbyban látszik, a meccs indulásakor eltűnik. Tálca: mindig látszik, frissítés
keresése, bezárás.

Mindhárom program csak kiír: nem kattint, nem nyom billentyűt a játékban.

## Követelmények

- Windows 10/11, 1920x1080 felbontás, szegély nélküli ablakos játék (angol vagy magyarított)
- Windows OCR (a Windows beépített szövegfelismerője)
