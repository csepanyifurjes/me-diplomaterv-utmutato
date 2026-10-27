# Kutatási kérdések és hipotézisek – Cheat Sheet

**A cheat sheet célja**

Ez az útmutató segít a Miskolci Egyetem Informatikai Intézet diplomatervező és szakdolgozó hallgatóinak a kutatásuk alapját képező **kutatási kérdések (Research Question - RQ)** és **hipotézisek (Hypothesis - H)** szakszerű megfogalmazásában.

---

## Szakdolgozat vs. Diplomamunka: Mi a különbség?

Bár mindkét műben elvárás a rendszerszemlélet és a szakmai precizitás, a tudományos mélységben és a hipotézisalkotásban van különbség:

| Szempont                 | Szakdolgozat (BSc / Alapképzés)                                                                      | Diplomamunka (MSc / Mesterképzés)                                                                                                 |
| :----------------------- | :--------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------- |
| **Fő fókusz**            | Meglévő módszerek, elméletek és gyakorlatok **alkalmazása**, mérnöki/szakmai feladatok megoldása.    | Újszerű megközelítések, **bizonyos szintű saját kutatás/ saját fejlesztés**, mélyebb elemzés, véleményalkotás és következtetések. |
| **Kutatási kérdések**    | Leíró, összehasonlító vagy gyakorlati problémaorientált kérdések.                                    | Komplex, ok-okozati vagy módszertani hatékonyságra vonatkozó kérdések.                                                            |
| **Hipotézisek elvárása** | **Nem mindig kötelező** (főleg mérnöki/fejlesztési témáknál elég a célkitűzés és a kutatási kérdés). | **Ajánlott**, amennyiben a téma méréssel, kísérlettel vagy adatelemzéssel igazolható, célszerű hipotézist felállítani.            |

---

## 1. A jó Kutatási Kérdés (Research Question - RQ)

A kutatási kérdés határozza meg, hogy **pontosan mire keresi a választ** a dolgozatában.

### A jó kutatási kérdés ismérvei (FINER-modell):
* **Focussed (Fókuszált):** Nem túl általános, konkrétan lehatárolt.
* **Informative (Informatív):** Nem válaszolható meg egy egyszerű "igen"-nel vagy "nem"-mel (inkább: *Hogyan...? Milyen mértékben...? Milyen kapcsolat van...?*).
* **Novel (Újszerű/Releváns):** Van szakmai vagy gyakorlati értéke.
* **Ethical (Etikus):** Megfelel a tudományetikai szabályoknak.
* **Realistic (Reális):** A rendelkezésre álló időben és erőforrásokkal megválaszolható.

---

## 2. A jó Hipotézis (Hypothesis - H)

A hipotézis egy **tesztelhető, előzetes feltételezés** a kutatási kérdése lehetséges válaszára vagy változók közötti kapcsolatára.

A _"változók közötti kapcsolat"_ a tudományos kutatás egyik alappillére. Azt jelenti, hogy a kutatás során megvizsgál két vagy több olyan tényezőt, 
amelyek képesek változni (értéket, állapotot vagy viselkedést váltani), és feltételez egyfajta ok-okozati vagy együttmozgási összefüggést 
közöttük.
_"Ha megváltoztatom az X-et (pl. algoritmust, paramétert, architektúrát), akkor az Y (pl. idő, sebesség, hibaarány) megjósolható módon reagálni fog erre."_

### A jó hipotézis aranyszabályai:

1. **Tesztelhető és cáfolható:** Olyan állítás, amelyet kísérlettel, méréssel, adatelemzéssel vagy szimulációval igazolni vagy cáfolni lehet.
2. **Kétoldalú/Semleges megközelítés:** A kutatóként nem az a célja, hogy "mindenáron igaza legyen", hanem az, hogy objektíven megvizsgálja az állítást. **A cáfolt hipotézis is értékes tudományos eredmény!**
3. **Egyértelmű változók:** Világosan megnevezi a vizsgált tényezőket (pl. *X módszer hatása Y paraméterre*).

---

## Példák (Informatikai / Mérnöki / Műszaki kontextus)

### Gyenge / Rossz példák:
* ❌ *RQ:* Jó-e a Python a gépi tanuláshoz? *(Túl általános, triviális válasz)*
* ❌ *H:* A saját algoritmusom sokkal jobb lesz, mint a többi. *(Nem mérhető, szubjektív, nem pontos)*

### Jó példák:
* ✅ **RQ1:** *Milyen mértékben csökkenti a konvolúciós hálók (CNN) tanítási idejét a megadott adathalmazon a metszési (pruning) eljárás alkalmazása a modellpontosság romlása nélkül?*
* ✅ **H1:** *A modelltömörítési (pruning) eljárás alkalmazásával a tanítási idő legalább 20%-kal csökkenthető úgy, hogy a pontosságvesztés nem haladja meg az 1,5 százalékpontot.*


### Programozói példa:

* **Kutatási Kérdés (RQ):**
  > *Hogyan építhető fel egy meglévő, monolitikus ant colony szimulációs algoritmus olyan moduláris, webes alapú architektúrában, amely a valós idejű vizualizáció mellett is képes kezelni meghatározott mennyiségű ágens (pl. >100 hangya) párhuzamos állapotfrissítését?*

* **Hipotézis (H):**
  > *Ha a szimulációs magot aszinkron webes worker szálakra választjuk szét a rendereléstől, és a vizualizációhoz optimalizált grafikus API-t használunk, akkor a webes alapú implementáció teljesítménye nem marad el 15%-nál nagyobb mértékben a natív asztali implementációtól.*

---

## Gyakorlati tippek a megfogalmazáshoz

> **1. Kezdje a szakirodalommal!**
> Ne találjon ki hipotézist azelőtt, hogy átnézte volna az irodalmat. A jó hipotézis a korábbi kutatások hiányosságaiból (*research gap*) vagy eredményeiből táplálkozik.

> **2. Helyi kutatási szálak és konzulensi egyeztetés**
> Ne feledje, hogy a **Miskolci Egyetem oktatói és kutatói** számos szakterületen folytatnak aktív kutatásokat. Ha a kutatási kérdését vagy hipotézisét a konzulense/oktatója futó kutatásaihoz vagy korábbi publikációihoz illeszti, azzal nemcsak a saját dolgát könnyíti meg (közvetlenül elérhető szakértelem és mérések), de hozzájárul az egyetemi kutatócsoportok eredményeihez is.

> **3. Hány kérdés/hipotézis kell?**
> * **Szakdolgozatnál:** 1-2 fő kutatási kérdés (vagy célkitűzés) teljesen elegendő.
> * **Diplomamunkánál:** 2-3 jól körülhatárolt kutatási kérdés és a hozzájuk tartozó 2-3 tesztelhető hipotézis az ideális.

---

## Gyors csekklista a kutatási kérdésekhez és hipotézisekhez

Mielőtt leadja a konzulensnek a kérdéseket és hipotéziseket:

- [ ] **Nem "igen/nem" kérdés?** (A kérdés *hogyan*, *miért* vagy *milyen mértékben* kezdődik, nem pedig egy eldöntendő kérdés.)
- [ ] **Mérhető vagy tesztelhető?** (Van benne valamilyen összehasonlítás, metrika, teljesítményhatár vagy szempontrendszer?)
- [ ] **Reális a keretek között?** (A félév/diplomaterv ideje alatt, a meglevő eszközökkel megválaszolható?)
- [ ] **Illeszkedik a témához?** (Nem kalandozik el a dolgozat fő fókuszától?)
- [ ] **Van hozzá forrásalap?** (A szakirodalmi áttekintésedből vagy egy konkrét *research gap*-ből következik?)
- [ ] **Diplomamunka esetén:** Tartalmazza-e a hipotézis a várt eredményt vagy összefüggést (és nemcsak egy átfogalmazott kérdés)?