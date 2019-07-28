---
title: 'Uue keele õpingud'
date: '2019-05-02'
spoiler: 'Uue keele õpingud'
---

Alustasin uue programmeerimiskeele- C# õppimisega ning mõtlesin kirjutada mõned olulised asjad, mida seni olen õppinud ning millele tähelepanu pöörata.

- C# on _keysensitive_ ehk tuleb olla väga tähelepanelik suure ja väikese algustähega.
- Vigade korral aitab Visul Studios punane loogeline joon, mis tuleb vigasele kohale alla ning sa saad selle ära parandada.
- C# keelt on lihtne ära tunda kahe märgi poolest: loogelised sulud {} ja semikoolon ;. Loogelisi sulge esineb koodis palju ning semikoolon on iga rea lõpus (v.a kui defineerime klassi või meetodit).
- Kui soovid ühte rida välja kommenteerida (nt teha endale märkmeid, kirjutada kommentaar), siis kirjuta rea algusesse //
- Kui soovid mitut rida välja kommenteerida, kirjuta /\* _tekst mida soovid välja kommenteerida_ \*/

Järgnevalt on näha koodi, mida ükskõik millises programmeerimiskeeles esimesena kirjutatakse ehk "Hello World!" kirjutamine:

```
x = 7;
y = x + 3;
Console.WriteLine(y);
```

Pildil on ka lühidalt seletatud, mis asjad on klass ja meetod.

Koodis on olulised asjad ka muutujad, mida näeme järgneval pildil:

![](http://52.28.251.54/wp-content/uploads/2019/05/image-1.png)

Pildil on muutujateks x ja y, millele me oleme andnud mingid väärtused. Kui koodi käivitame saame vastuseks 10, sest kui liidame x (mis on 7) ning 3, saame tulemuseks 10.

NB! Väga oluline on panna muutujatele head nimed, et sina ja teised saaksid hästi aru, mida need tähistavad. Ülal pildil oleme teinud lihtsa arvutuse, kuid kui hiljem kirjutame keerulisemat koodi, on hästi näha, kui oluline on panna muutujatele head nimed.

Oluline on ka osata muutujate nimesid õigesti kirjutada. See tähendab, et kui soovid kirjutada muutujale nime, mis koosneb näiteks kahest sõnast, siis need kirjutatakse kokku ja \_camelcase'\_is ehk teise sõna esimene täht on suur ning kõik teised tähed on väikesed. Näiteks ülemisel pildil oleva muutuja x võime asendada nimega numberSeven.
