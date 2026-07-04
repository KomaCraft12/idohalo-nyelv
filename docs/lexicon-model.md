# Szótármodell

Állapot: **Kutatási / munkavázlat**

## Cél

Ez a dokumentum azt vizsgálja, hogyan nézhet ki az Időháló Nyelv szótára.

A cél nem egy egyszerű fordítási lista, hanem egy olyan szótári rendszer, amely tükrözi a fogalmi csomópontokat, kapcsolódó jelentéseket és használati rétegeket.

## Hagyományos szótár

Egy hagyományos szótár gyakran ilyen:

```text
fa = tree
```

Ez hasznos, de kevés információt ad a fogalom kapcsolatairól.

## Időháló-szótár lehetséges formája

Egy későbbi szótári bejegyzés ilyen mezőkből állhat:

```text
Fogalom:
Beszélt forma:
Sorírásos forma:
Hálóírásos jel:
Közös jelentésmag:
Kapcsolódó fogalmak:
Gyakori eseményszerepek:
Gyakori kapcsolatok:
Személyes jelentésháló-lehetőségek:
Példák:
Megjegyzések:
```

## Példa: FA

```text
Fogalom: FA
Beszélt forma: később meghatározandó
Sorírásos forma: később meghatározandó
Hálóírásos jel: később meghatározandó

Közös jelentésmag:
- élő növényi mintázat
- gyökérrel, törzzsel, ágakkal és levelekkel

Kapcsolódó fogalmak:
- növekedés
- föld
- víz
- fény
- árnyék
- erdő
- évszak
- anyag

Gyakori eseményszerepek:
- nő
- árnyékot ad
- gyümölcsöt adhat
- eléghet
- kivágható
- otthont adhat más élőlényeknek

Személyes jelentésháló-lehetőségek:
- gyerekkor
- nyugalom
- otthon
- emlék
- félelem
- szentség
```

## Fontos elv

A szótár nem akarja meghatározni minden ember belső jelentését.

A személyes jelentésháló csak lehetőség, nem kötelező jelentés.

## Szótári rétegek

A szótárnak több szintje lehet.

### 1. Gyors szótár

Egyszerű fordítás vagy rövid magyarázat.

Példa:

```text
FA = fa / tree
```

### 2. Tanulói szótár

Közös jelentésmag + néhány példa.

### 3. Teljes fogalmi szótár

Kapcsolódó fogalmak, eseményszerepek, hálóírásos forma, asszociációk.

## Használhatósági korlát

A hétköznapi tanuló nem kényszeríthető arra, hogy minden szót teljes fogalmi hálóként tanuljon.

Ezért a szótárnak rétegzettnek kell lennie:

- gyors keresés;
- tanulói magyarázat;
- mély fogalmi elemzés.

## Kapcsolat más dokumentumokkal

- `docs/meaning-network.md` – a szó mint jelentésháló-kulcs.
- `docs/concept-architecture.md` – fogalmi csomópont mint mélyréteg.
- `docs/thinking-model.md` – a nyelv gondolkodási lehetőségeket kínál.
- `docs/design-principles.md` – a használhatóság és kommunikáció elsődlegessége.

## Nyitott kérdések

- Mely mezők legyenek kötelezőek egy szótári bejegyzésben?
- Milyen legyen a gyors szótári forma?
- Hogyan jelenjen meg a hálóírásos jel?
- Hogyan kezeljük a többjelentésű szavakat?
- Egy beszélt forma kapcsolódhat-e több fogalmi csomóponthoz?
- Mikor kell egy asszociációt közösséginek, és mikor személyesnek tekinteni?

## Ideiglenes tétel

> A szótár nem szavak listája, hanem fogalmi csomópontok rétegzett térképe.

Ez jelenleg munkahipotézis.
