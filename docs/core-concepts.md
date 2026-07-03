# Alapfogalmak

Állapot: **Kutatási dokumentum**

## Cél

Ez a dokumentum az Időháló Nyelv lehetséges alapfogalmait gyűjti össze.

Fontos: ez nem alkotmánycikk és nem végleges specifikáció. A cél az, hogy legyen egy tiszta hely, ahol vizsgálhatjuk, milyen fogalmakból épülhet fel a nyelv világmodellje.

## Kiinduló felismerés

Nem biztos, hogy a nyelvnek egyetlen végső építőeleme van.

A világ sem egyetlen dologból áll, hanem sokféle jelenségből, amelyek egymással kapcsolatban működnek. Ezért a nyelv alapja sem feltétlenül egyetlen fogalom, hanem alapfogalmak hálózata lehet.

## Nem hierarchikus alapmodell

A nyelv világmodellje nem feltétlenül ilyen:

```text
Egy alapfogalom
      ↓
Minden más
```

Hanem inkább ilyen:

```text
Kapcsolat ── Esemény
    │            │
    │            │
Változás ── Nézőpont
    │            │
    └── Jelentés ┘
```

Ebben a modellben nincs egyetlen uralkodó alapfogalom. A fogalmak egymást magyarázzák és egymással együtt alkotnak rendszert.

## Jelenlegi alapfogalom-jelöltek

| Fogalom | Státusz | Megjegyzés |
|---|---|---|
| Kapcsolat | Erős jelölt | Lehet, hogy az események kapcsolatok metszéspontjai. |
| Esemény | Erős jelölt | A nyelv felszíni és elemző szerkezetében kulcsszerepe lehet. |
| Változás | Vizsgálandó | Lehet, hogy minden állapot lassú változásként értelmezhető. |
| Nézőpont | Fontos jelölt | A beszélő mindig a háló része, nem külső megfigyelő. |
| Jelentés | Vizsgálandó | Talán kapcsolatokból és nézőpontból születik. |
| Tudat | Óvatosan kezelendő | Könnyen túl metafizikai irányba vihet. |
| Hely | Vizsgálandó | Lehet, hogy nem abszolút tér, hanem kapcsolati helyzet. |
| Állapot | Kérdéses | Lehet, hogy csak stabil vagy lassú változás. |

## Fontos tervezési döntés

A projekt jelenlegi iránya szerint nem kell mindenáron egyetlen végső építőelemet keresni.

Ehelyett azt vizsgáljuk:

> Mi az a legkisebb fogalomkészlet, amelyből a nyelv világa következetesen és használhatóan felépíthető?

## Miért fontos ez?

Ha túl korán kijelentjük, hogy „minden kapcsolat” vagy „minden esemény”, akkor elveszíthetjük a különbségeket.

A jó világmodell nem mindent egyetlen szóval akar magyarázni, hanem olyan fogalmakat választ, amelyek:

- segítik a nyelv felépítését;
- nem teszik túl bonyolulttá a használatot;
- nem mondanak ellent egymásnak;
- képesek egyszerű hétköznapi mondatok mögött is működni.

## Alapelvi óvatosság

Egy fogalom nem kerülhet alkotmányba csak azért, mert szép vagy mély.

Előbb vizsgálni kell:

1. Következik-e az eddigi rendszerből?
2. Segíti-e a kommunikációt?
3. Használható-e hétköznapi beszédben?
4. Tudunk-e rá példákat építeni?
5. Nem teszi-e túl homályossá a nyelvet?

## Kapcsolódás más dokumentumokhoz

- `docs/world-model.md` – a világmodell nagy kérdései.
- `docs/design-principles.md` – hogyan szabad a nyelvet tervezni.
- `docs/events.md` – eseménycsomópontok első vázlata.
- `constitution/0001-az-ido-termeszete.md` – az idő nemlineáris alapelve.
- `constitution/0003-a-hasznalhatosag-elve.md` – a használhatóság alkotmányos korlátja.

## Következő kérdések

- Milyen fogalmak legyenek az első szintű alapfogalmak?
- A kapcsolat és az esemény egymást feltételezik, vagy az egyik elsődlegesebb?
- A változás külön alapfogalom, vagy a kapcsolat/esemény következménye?
- A nézőpont kötelező nyelvtani elem legyen, vagy csak opcionális jelölés?
- Hogyan lehet ezt az egész rendszert egyszerű hétköznapi beszédbe sűríteni?
