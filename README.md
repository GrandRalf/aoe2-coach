# AoE2 Coach

Build order segéd az **Age of Empires II: Definitive Edition**-höz. A képernyő jobb oldalán átlátszó panelen mutatja,
melyik paraszt mit csináljon („7. favágótábort épít, majd fa”), és figyelmeztet, ha a városközpont nem gyárt, vagy ház kell.
Csak a képernyőt olvassa (a felső sáv számait), a játékba nem kattint bele.

## Letöltés

A legfrissebb **AoE2Coach.exe** a [Releases](../../releases/latest) oldalon. Telepíteni nem kell, csak elindítani.

## Használat

1. Indítsd el az `AoE2Coach.exe`-t, válaszd ki a build ordert a listából, **Indítás**.
2. Indítsd a meccset. A panel akkor látszik, ha a játék van előtérben (szegély nélküli ablakos módban).
3. A panelen: az épp elhagyott lépés, **aranyban az aktuális**, alatta a következők; a végén elfogynak.

Figyelmeztetések (egész meccs alatt): **A városközpont nem gyárt!** (100 parasztig, ha van 50 élelem),
**Ház kell!** (hangjelzéssel), több városközpontnál: **Nem gyárt minden városközpont**.

## Tálcaikon (jobb klikk)

Build order választás · Hangeffektek be/ki · Build order elölről · Build újratöltése · Importálás… · Bezárás

Gyorsbillentyűk: **Ctrl+Alt+→ / ←** következő / előző lépés, **Ctrl+Alt+End** bezárás.

## Saját build orderek

A buildek helye: `Dokumentumok\AoE2 Coach\builds`. Egy [buildorderguide.com](https://buildorderguide.com) exportot
(.txt vagy .json) a menü / tálca **Importálás…** gombjával vehetsz fel, vagy egyszerűen bemásolod ebbe a mappába:
induláskor átalakítja és finomhangolja (kezdés 2 házzal, fatábor, 2 ház + malom, ház + bányatábor).

Alapból benne: **Hera 23+2 Fast Castle Boom** (bármely nép), **13 Minute Castle Drop** (Franks).

## Követelmények

- Windows 10/11, 1920x1080 felbontás, AoE2 DE (angol vagy a HUN v1.6 magyarítással)
- Windows OCR (a Windows beépített szövegfelismerője)
