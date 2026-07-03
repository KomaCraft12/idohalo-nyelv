# Világmodell

Állapot: **Kutatási dokumentum**

## Cél

Ez a dokumentum azt vizsgálja, hogy az Időháló Nyelv hogyan modellezi a világot.

Nem végleges szabályokat tartalmaz, hanem nagy kérdéseket, lehetséges irányokat és vizsgálati pontokat. Innen később alkotmánycikkek vagy specifikációk születhetnek, de csak akkor, ha egy elv átmegy a projekt saját szűrőin:

- következik-e az eddigi alapelvekből;
- nem mond-e ellent az alkotmánynak;
- használható marad-e tőle a nyelv;
- segít-e egyszerűbben vagy pontosabban gondolkodni.

## Kiinduló alapelvek

A jelenlegi elfogadott alapelvek:

1. Az idő nem lineáris.
2. Az idő események hálózata.
3. A nyelv alapegysége a mondat helyett az eseménycsomópont felé mozdulhat.
4. A nyelv filozófiája nem írhatja felül a használhatóságát.

## Alapkérdés

Mi a világ legkisebb jelentésegysége ebben a nyelvben?

Lehetséges jelöltek:

- kapcsolat;
- esemény;
- változás;
- tudat;
- hely;
- nézőpont;
- hatás;
- állapot.

## Kapcsolat mint lehetséges alap

Felmerült az irány, hogy az esemény talán nem elsődleges.

Lehetséges tétel:

> A kapcsolat megelőzi az eseményt.

Ebben a modellben az esemény nem önálló dolog, hanem kapcsolatok találkozása, sűrűsödése vagy átalakulása.

Példa:

```text
[Ember A] ── kapcsolat ── [Ember B]
       \                    /
        \                  /
          [Beszélgetés]
```

A beszélgetés nem pusztán esemény, hanem több kapcsolat metszéspontja:

- két ember kapcsolata;
- gondolat és hang kapcsolata;
- beszélő és hallgató kapcsolata;
- jelentés és figyelem kapcsolata.

## Esemény mint kapcsolati csomópont

Ha a kapcsolat az elsődlegesebb fogalom, akkor az eseménycsomópont így értelmezhető:

> Az esemény olyan csomópont, ahol kapcsolatok találkoznak és jelentést hoznak létre.

Ez nem törli az esemény fontosságát, hanem mélyebb alapot ad neki.

## Állapot kérdése

Nyitott kérdés:

> Létezik-e valódi állapot, vagy minden állapot csak lassú változás?

Lehetséges irány:

- Nincs teljes mozdulatlanság.
- Amit állapotnak nevezünk, az is változás, csak lassabb vagy stabilabb mintázat.
- A nyelv ezért nem állapotközpontú, hanem változás- és kapcsolatközpontú lehet.

Példa:

Magyarul:

> A hegy áll.

Időháló-szemléletben:

> A hegy változása emberi nézőpontból lassú és stabil.

## Pillanat kérdése

Nyitott kérdés:

> Létezik-e valódi pillanat?

Lehetséges válaszok:

1. A pillanat valós alapegység.
2. A pillanat csak emberi észlelési metszet.
3. A pillanat nem önálló létező, hanem kapcsolatok ideiglenes sűrűsödése.

A projekt egyelőre nem dönt erről.

## Önazonosság kérdése

Nyitott kérdés:

> Létezik-e valódi önmaga, állandó identitás?

Ezt óvatosan kell kezelni, mert könnyen hitbeli vagy metafizikai állítássá válhat.

A nyelvnek nem kell kijelentenie, hogy létezik vagy nem létezik örök én, lélek vagy végső önazonosság.

Tervezési szinten viszont vizsgálható:

- hogyan jelöli a nyelv a folytonosságot;
- hogyan jelöli a változó identitást;
- hogyan beszél ugyanarról a személyről különböző eseményháló-helyzetekben.

## Nézőpont

A beszélő nem kívülről nézi az időhálót.

A beszélő maga is csomópont vagy kapcsolati helyzet.

Ezért a nyelvben fontos lehet jelölni:

- honnan látja a beszélő az eseményt;
- mennyire biztos benne;
- közvetlenül tapasztalta-e;
- része volt-e;
- csak hallotta, következtette vagy hitként kezeli.

## Használhatósági korlát

A világmodell lehet mély és komplex, de a nyelv mindennapi alaprétege nem lehet túl nehéz.

Ezért:

- a kapcsolatközpontúság nem jelentheti azt, hogy minden mondatban teljes hálót kell rajzolni;
- az eseményháló a mélystruktúra lehet;
- a beszélt nyelvnek egyszerű, gyors alakokat kell adni ugyanarra a jelentésre.

## Nyitott kutatási kérdések

- Mi az elsődlegesebb: kapcsolat vagy esemény?
- Létezik-e állapot, vagy minden állapot lassú változás?
- Mi számít eseménynek?
- Mi számít kapcsolatnak?
- Van-e abszolút időpont?
- Van-e abszolút hely?
- Mi a beszélő hálóbeli szerepe?
- Hogyan lehet a kapcsolatközpontúságot egyszerűen beszélni?
- Milyen része legyen kötelező az alapnyelvben, és mi maradjon magasabb réteg?

## Következő lépés

A következő nagy feladat a kapcsolat és az esemény viszonyának vizsgálata.

Lehetséges munkadokumentum:

```text
docs/relation-event-model.md
```

Ebben külön lehet vizsgálni, hogy a kapcsolat valóban megelőzi-e az eseményt, vagy inkább az esemény és kapcsolat egymást feltételező fogalmak.
