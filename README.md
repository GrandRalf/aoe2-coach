# AoE2 Coach

Build order segéd az **Age of Empires II: Definitive Edition**-höz. A képernyő jobb oldalán átlátszó panelen mutatja,
melyik paraszt mit csináljon („7. favágótábort épít, majd fa”), és figyelmeztet, ha a városközpont nem gyárt, vagy ház kell.
Csak a képernyőt olvassa (a felső sáv számait), a játékba nem kattint bele.

## Letöltés

A legfrissebb **AoE2Coach.exe** a [Releases](../../releases/latest) oldalon. Telepíteni nem kell, csak elindítani.

**Automatikus frissítés (v1.2-től):** induláskor a menü megnézi, van-e újabb kiadás; ha igen, a **Frissítés** gombbal
letölti, kicseréli magát és újraindul. A tálcán is van **Frissítés keresése**. (A v1.1-ről egyszer még kézzel kell letölteni.)

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
Importálás… · Importálás linkről (aoecompanion)… · Frissítés keresése · Bezárás

Gyorsbillentyűk: **Ctrl+Alt+→ / ←** következő / előző lépés, **Ctrl+Alt+End** bezárás.

## Saját build orderek

A buildek helye: `Dokumentumok\AoE2 Coach\builds`. Egy [buildorderguide.com](https://buildorderguide.com) exportot
(.txt vagy .json) a menü / tálca **Importálás…** gombjával vehetsz fel, vagy egyszerűen bemásolod ebbe a mappába:
induláskor átalakítja és finomhangolja (kezdés 2 házzal, fatábor, 2 ház + malom, ház + bányatábor).

**Beillesztés / link:** a [buildorderguide.com](https://buildorderguide.com) oldalon a build oldalán nyomd meg az
**Export → RTS** gombot (vágólapra másolja), majd a menü **Beillesztés / link…** gombja (vagy a tálca) a vágólapról azonnal importálja – txt fájl nem kell.
Ugyanez a gomb egy `https://aoecompanion.com/build-guides/...` vagy `https://aoecompanion.com/b/...` linket is elfogad;
letölti, magyarra fordítja és felveszi a listába.

Az angol build orderek lépéseit magyarul mutatja (a fejlesztések neve mellett zárójelben az angol).

Alapból benne: **Hera 23+2 Fast Castle Boom** (bármely nép), **Fast Castle Boom (aoecompanion)** (bármely nép),
**13 Minute Castle Drop** (Franks).

## Követelmények

- Windows 10/11, 1920x1080 felbontás, AoE2 DE (angol vagy a HUN v1.6 magyarítással)
- Windows OCR (a Windows beépített szövegfelismerője)
