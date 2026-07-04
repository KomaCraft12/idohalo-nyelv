# Fogalmi architektúra

Állapot: **Kutatási / munkavázlat**

## Cél

Ez a dokumentum azt írja le, hogyan válhat a fogalom vagy fogalmi csomópont a nyelv mélyrétegének alapegységévé.

Ez nem jelenti azt, hogy a hétköznapi beszélőnek mindig fogalmi gráfokban kell gondolkodnia. A fogalmi architektúra a háttérrendszer, amelyből a beszéd, az írás és a hálóírás levezethető.

## Alapötlet

A legtöbb nyelv gyakorlati szinten így működik:

```text
szó → jelentés
```

Az Időháló Nyelv lehetséges mélymodellje:

```text
fogalom
   ├── beszélt forma
   ├── sorírásos forma
   ├── hálóírásos forma
   └── kapcsolati / gráfos forma
```

Vagyis a szó nem a legmélyebb egység, hanem a fogalom egyik felszíni megjelenése.

## Fogalom vagy fogalmi csomópont

A „fogalom” jelenleg munkanév.

Lehet, hogy később saját nyelvi kifejezést kap.

A fogalmi csomópont olyan mélyrétegbeli egység, amelyhez kapcsolódhat:

- közös jelentésmag;
- beszélt alak;
- sorírásos alak;
- hálóírásos jel;
- kapcsolódó fogalmak;
- eseménybeli szerepek;
- gyakori asszociációk;
- személyes jelentésháló-lehetőségek.

## Példa elvi formában

```text
FOGALMI CSOMÓPONT: FA

Közös jelentésmag:
- élő növényi mintázat
- gyökér, törzs, ág, levél

Kapcsolódó fogalmak:
- növekedés
- föld
- víz
- fény
- árnyék
- erdő
- évszak

Beszélt forma:
- később meghatározandó

Sorírásos forma:
- később meghatározandó

Hálóírásos forma:
- később meghatározandó
```

## Miért hasznos ez?

Ez a modell segíthet abban, hogy:

- a szavak ne véletlenszerűen szülessenek;
- a szótár ne puszta fordítási lista legyen;
- a beszélt nyelv és a hálóírás ugyanabból a mélyrétegből nőjön ki;
- később akár gépi, gráfos reprezentáció is készülhessen.

## Tervezési korlát

A fogalmi architektúra nem teheti nehézzé a hétköznapi nyelvet.

A beszélőnek nem kell minden fogalmi mezőt ismernie ahhoz, hogy használja a szót.

A felszíni nyelv mindig egyszerűbb, mint a mélystruktúra.

## Nyitott kérdések

- A fogalmi csomópont legyen-e tényleges szótári egység?
- Minden szónak legyen-e fogalmi csomópontja?
- Hogyan különül el a fogalom, a szó és az esemény?
- Egy fogalom több beszélt alakot is kaphat?
- Egy beszélt alak több fogalmi csomóponthoz is kapcsolódhat?
- Hogyan kezeljük a metaforákat és személyes asszociációkat?

## Ideiglenes tétel

> A fogalom a mélyréteg egysége; a szó ennek egyik emberi, beszélhető felszíni formája.

Ez jelenleg kutatási tétel, nem végleges nyelvtani szabály.
