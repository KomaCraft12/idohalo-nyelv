# Eseménycsomópontok

## Mi az eseménycsomópont?

Az eseménycsomópont a nyelv tervezett alapegysége.

Nem egyszerűen egy ige vagy mondat, hanem egy jelentéscsomag, amely megmutatja, hogy egy esemény hogyan kapcsolódik az időháló többi részéhez.

## Előzetes mezők

```text
Eseménycsomópont
├── résztvevők
├── környezet
├── forrás
├── következmény
├── hatás
├── bizonyosság
├── állapot
└── kapcsolatok
```

## Példa magyarul

Magyar mondat:

> Elmentem a boltba, mert elfogyott a kenyér.

Eseményhálóként:

```text
[Kenyér elfogy]
        │
        ▼
 [Elindulás]
        │
        ▼
     [Bolt]
        │
        ▼
 [Kenyér megszerzése]
```

## Nyitott kérdés

Meg kell határozni, hogy az eseménycsomópont mely mezői kötelezőek, és melyek opcionálisak.
