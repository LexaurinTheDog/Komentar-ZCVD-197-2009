# Kapitola 1 — Část první (§ 1–4a): předmět úpravy, vymezení pojmů, působnost orgánů, certifikát pravosti, certifikát kontroly pravosti údajů

**Téma kapitoly:** Kapitola pokrývá vstupní část zákona č. 197/2009 Sb., o certifikaci veřejných dokladů s biometrickými údaji (dále „ZCVD" nebo „zákon"): předmět úpravy navazující na přímo použitelné nařízení Rady (ES) č. 2252/2004 (§ 1), legální definice pojmů, s nimiž zákon dále pracuje — veřejný doklad, biometrický údaj, certifikát, prvotní a následný certifikát, certifikační podmínky, certifikát pravosti, certifikát přístupu, doklad s kontaktním čipem, certifikát kontroly pravosti údajů, certifikát oprávnění kontrolního orgánu a kontrolní údaje pravosti (§ 2), rozdělení působnosti mezi Ministerstvo vnitra, Policii České republiky a Ministerstvo zahraničních věcí (§ 3) a pravidla pro poskytování certifikátu pravosti (§ 4) a certifikátu kontroly pravosti údajů (§ 4a). Komentář vychází z místní konsolidace účinné od 1. 5. 2011 (`SB-2009-00197_2011-05-01`), u níž zdroj neuvádí konec účinnosti; jde tedy o aktuální znění, pozdější změny zákona místní zdroj neobsahuje a komentář je netvrdí.

Zákon je úzce technický a institucionální: nezakládá práva a povinnosti držitelům dokladů (ty plynou ze zákona o cestovních dokladech, zákona o pobytu cizinců a zákona o azylu), nýbrž upravuje **infrastrukturu důvěry**, která umožňuje ověřit, že biometrické údaje v nosiči dat nebyly podvrženy ani pozměněny (certifikát pravosti, certifikát kontroly pravosti údajů) a že k chráněným údajům — zejména k otiskům prstů — přistupuje jen oprávněný orgán (certifikát přístupu, certifikát oprávnění kontrolního orgánu). Jádrem je dvojice „prvotní — následný certifikát": prvotní se vydává po prokázání splnění certifikačních podmínek, následný zjednodušeně na základě platného předchozího certifikátu. Výklad pojmů se musí držet textu zákona; technologické podrobnosti kryptografie zákon neupravuje a komentář je nedoplňuje.

**CERTIFIKACE VEŘEJNÝCH DOKLADŮ S BIOMETRICKÝMI ÚDAJI**

### § 1 — Předmět úpravy

> **§ 1 — Předmět úpravy**
>
> Tento zákon upravuje v návaznosti na přímo použitelný předpis Evropských společenství1) certifikaci veřejných dokladů s biometrickými údaji za účelem ověření pravosti a neporušenosti těchto údajů a jejich ochrany před neoprávněným přístupem.

**Výklad:**

#### Předmět a účel zákona

§ 1 vymezuje předmět úpravy třemi prvky. **Za prvé**, zákon upravuje *certifikaci* veřejných dokladů s biometrickými údaji — tedy nikoli vydávání dokladů samých, nýbrž vydávání, poskytování a zneplatňování certifikátů, které k dokladům přistupují jako kryptografická vrstva důvěry. **Za druhé**, činí tak „v návaznosti na přímo použitelný předpis Evropských společenství", jímž je podle poznámky pod čarou č. 1 nařízení Rady (ES) č. 2252/2004 o normách pro bezpečnostní a biometrické prvky v cestovních pasech a cestovních dokladech vydávaných členskými státy. Zákon tedy není transpozicí (nařízení se nepřebírá), ale adaptační normou: určuje vnitrostátní orgány a postupy, které nařízení předpokládá, ale samo neurčuje. Označení „Evropských společenství" je terminologický pozůstatek doby přijetí zákona; věcně jde o předpis Evropské unie. **Za třetí**, § 1 stanoví dvojí účel: (i) ověření *pravosti a neporušenosti* biometrických údajů a (ii) jejich *ochranu před neoprávněným přístupem*. Těmto dvěma účelům odpovídají dvě skupiny certifikátů v § 2: certifikát pravosti a certifikát kontroly pravosti údajů slouží účelu (i), certifikát přístupu a certifikát oprávnění kontrolního orgánu účelu (ii).

#### Vztah k dokladovým zákonům a k ochraně osobních údajů

Které doklady jsou „veřejnými doklady s biometrickými údaji", ZCVD neurčuje výčtem; definice v § 2 písm. a) je funkční a naplňují ji především cestovní doklady podle zákona o cestovních dokladech (jehož místní komentář uvádí, že pasy obsahují nosič dat s údaji o zobrazení obličeje a otiscích prstů a že biometrické údaje lze použít výlučně k ověření pravosti dokladu a totožnosti držitele), cizinecké pasy a průkazy o povolení k pobytu podle zákona o pobytu cizinců a doklady podle zákona o azylu. Účelové vázání biometrie v těchto předpisech a ZCVD se doplňují: dokladové zákony říkají, *k čemu* lze biometrické údaje použít, ZCVD říká, *jak* se technicky zajistí, že je použije jen ten, kdo smí. Biometrické údaje zpracovávané za účelem jedinečné identifikace fyzické osoby patří mezi zvláštní kategorie osobních údajů (čl. 9 GDPR, viz místní komentář); ZCVD je proto třeba číst i jako součást zákonného základu, který omezuje přístup k nim na orgány vybavené certifikátem. Sám ZCVD však o zpracování osobních údajů držitelů nic nestanoví — certifikát podle § 2 písm. c) spojuje identifikaci *osoby* (orgánu nebo výrobce) s kryptografickými daty, nikoli údaje držitele dokladu.

#### F. Kazuistika

**1. Modelová situace.** Obecní úřad obce s rozšířenou působností, který vydává cestovní pasy, se dotáže Ministerstva vnitra, zda mu ZCVD ukládá povinnost „certifikovat" každý vydaný pas a zda má držitelům pasů vydávat jakýkoli doklad o certifikaci. Současně soukromá bezpečnostní agentura požaduje po ministerstvu „certifikaci" svého čtecího zařízení, aby mohla u vstupu do areálu ověřovat pasy zaměstnanců včetně otisků prstů.

**2. Právní otázka.** Dopadá ZCVD na jednotlivé úkony při vydávání dokladu a na držitele, a může být soukromá osoba adresátem certifikace podle tohoto zákona?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 1 (předmět — certifikace dokladů, dvojí účel).
- *Související ustanovení téhož zákona:* § 2 písm. a), c), g), h) (pojmy), § 3 (působnost — vydávání certifikátů výhradně ministerstvem), § 4 a § 6 (okruh příjemců certifikátu pravosti a přístupu — správní orgány, orgány jiných států, výrobce).
- *Související předpisy:* nařízení Rady (ES) č. 2252/2004 (pozn. 1); zákon o cestovních dokladech (účelové omezení použití biometrických údajů, zákaz jiného zpracování údajů z nosiče dat); čl. 9 GDPR (zvláštní kategorie údajů).

**4. Subsumpce.** Předmětem ZCVD je certifikace jako vztah mezi ministerstvem a výrobcem dokladu, resp. oprávněnými orgány; vydávající úřad ani držitel nejsou adresáty žádné povinnosti podle § 1 a násl. Soukromá agentura nespadá do žádné kategorie příjemců certifikátu podle § 4 ani § 6 (není správním orgánem oprávněným jiným právním předpisem, orgánem jiného státu ani výrobcem) a účel „ochrany před neoprávněným přístupem" podle § 1 se obrací právě proti takovému přístupu.

**5. Řešení.** Úřad vydávající pasy nemá podle ZCVD žádnou samostatnou certifikační povinnost; certifikát pravosti se vztahuje k výrobci dokladu a je součástí výroby, nikoli správního řízení o vydání pasu. Agentuře ministerstvo certifikát nevydá — chybí zákonný titul; přístup k otiskům prstů mimo okruh oprávněných orgánů je právě tím, čemu má zákon bránit, a jeho pokus by byl současně v rozporu s účelovým omezením podle dokladových zákonů.

**6. Varianty.** (a) Jde-li o správní orgán, kterému jiný právní předpis dovoluje ověřovat pravost biometrických údajů (typicky policie při hraniční kontrole), je příjemcem certifikátu podle § 4 písm. a). (b) Výrobce dokladu, který potřebuje ověřit funkčnost čipu, je příjemcem certifikátu přístupu podle § 6 odst. 1 písm. d), nikoli podle § 4.

#### G. Protiargumenty a rizika

- *„Zákon upravuje jen cestovní pasy, protože nařízení č. 2252/2004 se týká pasů."* Neutralizace: § 1 odkazuje na nařízení jako na východisko, ale definice veřejného dokladu v § 2 písm. a) je obecná (každá veřejná listina s nosičem dat s biometrickými údaji) a § 2 písm. i) výslovně přidává doklady s kontaktním čipem; okruh dokladů je určen dokladovými zákony, nikoli nařízením.
- *„Certifikace je forma zpracování biometrických údajů držitele a vyžaduje jeho souhlas."* Neutralizace: certifikát podle § 2 písm. c) nespojuje kryptografická data s údaji držitele, ale s identifikací osoby, která certifikát používá; zpracování údajů držitele se řídí dokladovými zákony a předpisy o ochraně osobních údajů.
- *Slabé místo:* § 1 nedefinuje „certifikaci" — pojem je třeba rekonstruovat z § 2 až § 7a; je výkladovou otázkou, zda pod něj spadá i vedení seznamů podle § 3 odst. 1 písm. e), f) a j), nebo zda jde o činnost pouze doprovodnou.

#### H. Praktický závěr

§ 1 vymezuje zákon jako adaptační normu k nařízení Rady (ES) č. 2252/2004, jejímž předmětem je certifikační infrastruktura (nikoli vydávání dokladů) a jejímž účelem je ověření pravosti a neporušenosti biometrických údajů a ochrana před neoprávněným přístupem k nim.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Jde o certifikaci (vztah ministerstvo — výrobce/oprávněný orgán), nebo o vydávání či používání dokladu (dokladové zákony)?
- [ ] Který z dvou účelů § 1 je ve hře — pravost údajů (certifikát pravosti, kontroly pravosti), nebo přístup k nim (certifikát přístupu, oprávnění kontrolního orgánu)?
- [ ] Je subjekt vůbec způsobilým příjemcem certifikátu podle § 4, § 4a, § 6 nebo § 6a?
- [ ] Odkazuje-li se na „předpis Evropských společenství", pracovat s nařízením č. 2252/2004 v platném znění.

**Typicky rozhodné důkazy / podklady:** znění jiného právního předpisu zakládajícího oprávnění orgánu k ověřování nebo přístupu, doklad o postavení výrobce veřejného dokladu, certifikační podmínky stanovené ministerstvem.

---

### § 2 — Vymezení pojmů

> **§ 2 — Vymezení pojmů**
>
> Pro účely tohoto zákona se rozumí
>
> - a) veřejným dokladem s biometrickými údaji (dále jen „veřejný doklad“) veřejná listina obsahující nosič dat s biometrickými údaji, v níž je uvedeno jméno, popřípadě jména, příjmení, datum narození, popřípadě jiný údaj umožňující identifikovat osobu, která veřejný doklad předkládá, jako jeho oprávněného držitele,
>
> - b) biometrickým údajem údaj o zobrazení obličeje a údaj o otiscích prstů rukou zpracovaný v nosiči dat,
>
> - c) certifikátem kryptograficky zabezpečená datová zpráva, která spojuje identifikaci osoby s kryptografickými daty používanými pro ověření pravosti a neporušenosti biometrických údajů nebo oprávněnosti přístupu k biometrickým údajům,
>
> - d) prvotním certifikátem certifikát vydaný na základě prokázání splnění certifikačních podmínek,
>
> - e) následným certifikátem certifikát vydaný zjednodušeným způsobem na základě platného prvotního certifikátu; následným certifikátem se rozumí i certifikát vydaný na základě předcházejícího platného certifikátu,
>
> - f) certifikačními podmínkami minimální bezpečnostní požadavky a důvěryhodné postupy pro vydání, poskytnutí nebo používání certifikátu,
>
> - g) certifikátem pravosti certifikát, jímž se ověřuje pravost a neporušenost biometrických údajů,
>
> - h) certifikátem přístupu certifikát umožňující přístup k biometrickým údajům o otiscích prstů rukou,
>
> - i) veřejným identifikačním dokladem s kontaktním čipem (dále jen „doklad s kontaktním čipem“) veřejná listina obsahující elektronický kontaktní čip, v níž je uvedeno jméno, popřípadě jména, příjmení, datum narození, popřípadě jiný údaj umožňující identifikovat osobu, která veřejný doklad předkládá, jako jeho oprávněného držitele,
>
> - j) certifikátem kontroly pravosti údajů certifikát, jímž se na základě kontrolních údajů pravosti ověřuje pravost a neporušenost údajů zapsaných na kontaktním čipu,
>
> - k) certifikátem oprávnění kontrolního orgánu certifikát, který umožňuje kontrolnímu orgánu přístup ve stanoveném rozsahu k údajům uloženým na kontaktním čipu,
>
> - l) kontrolními údaji pravosti zabezpečovací údaje uložené na kontaktním čipu, které umožňují s využitím certifikátu kontroly pravosti údajů ověřit pravost a neporušenost určeného rozsahu údajů uložených na kontaktním čipu.

**Výklad:**

#### Struktura definic — dvě dokladové vrstvy

§ 2 obsahuje dvanáct legálních definic „pro účely tohoto zákona", které se dělí do dvou vrstev. **Písm. a) až h)** tvoří původní vrstvu vázanou na *nosič dat s biometrickými údaji* (bezkontaktní čip cestovních dokladů). **Písm. i) až l)** tvoří vrstvu vázanou na *kontaktní čip* veřejného identifikačního dokladu; této vrstvě odpovídají § 4a, § 6a a § 7a a písm. h) až j) v § 3 odst. 1. Číslování „a" naznačuje pozdější vložení; místní konsolidace účinná od 1. 5. 2011 tuto vrstvu již obsahuje. Obě vrstvy pracují s týmž mechanismem (prvotní/následný certifikát, certifikační podmínky), liší se však tím, co se ověřuje: v první vrstvě *biometrické údaje*, ve druhé *údaje zapsané na kontaktním čipu* v určeném rozsahu.

#### Veřejný doklad a biometrický údaj (písm. a), b))

**Veřejný doklad** je definován čtyřmi znaky: (i) veřejná listina, (ii) obsahující nosič dat s biometrickými údaji, (iii) s uvedením jména, popřípadě jmen, příjmení a data narození, popřípadě jiného identifikačního údaje, (iv) umožňující identifikovat předkládající osobu jako oprávněného držitele. Definice je funkční — nezáleží na názvu dokladu, ale na tom, zda je veřejnou listinou s biometrickým nosičem; podle místních komentářů k dokladovým zákonům jde o cestovní pasy, cizinecké pasy, průkazy o povolení k pobytu a cestovní doklady azylantů. **Biometrickým údajem** je výlučně údaj o zobrazení obličeje a údaj o otiscích prstů rukou „zpracovaný v nosiči dat" — definice je taxativní a shoduje se s legální definicí v zákoně o cestovních dokladech; jiné biometrické charakteristiky zákon nezná.

#### Certifikát, prvotní a následný certifikát, certifikační podmínky (písm. c)–f))

**Certifikát** (písm. c)) je „kryptograficky zabezpečená datová zpráva" spojující identifikaci osoby s kryptografickými daty používanými buď k ověření pravosti a neporušenosti biometrických údajů, nebo k ověření oprávněnosti přístupu k nim. Zákon tedy certifikát pojímá jako datovou zprávu — nikoli jako správní rozhodnutí; osobou, jejíž identifikace se s daty spojuje, je výrobce nebo orgán, nikoli držitel dokladu. **Prvotní certifikát** (písm. d)) se vydává „na základě prokázání splnění certifikačních podmínek" — jde o vstup do systému, spojený s věcným přezkumem. **Následný certifikát** (písm. e)) se vydává „zjednodušeným způsobem na základě platného prvotního certifikátu"; druhá věta rozšiřuje pojem i na certifikát vydaný na základě předcházejícího platného certifikátu (tj. řetězení následných certifikátů). Podmínkou je *platnost* předchozího certifikátu: zneplatnění podle § 7 nebo § 7a řetěz přerušuje a vyžaduje nový prvotní certifikát. **Certifikační podmínky** (písm. f)) jsou „minimální bezpečnostní požadavky a důvěryhodné postupy pro vydání, poskytnutí nebo používání certifikátu"; stanoví je ministerstvo (§ 3 odst. 1 písm. g)). Zákon neurčuje jejich formu — jde o výkladovou otázku, zda mají povahu interního technického dokumentu, nebo aktu s vnějšími účinky vůči výrobci (viz § 5 odst. 3 a § 7 odst. 1).

#### Certifikát pravosti a certifikát přístupu (písm. g), h))

**Certifikát pravosti** ověřuje pravost a neporušenost biometrických údajů — odpovídá prvnímu účelu § 1. **Certifikát přístupu** umožňuje přístup k biometrickým údajům *o otiscích prstů rukou* — odpovídá druhému účelu. Rozdíl je zásadní: zobrazení obličeje zákon zvláštním přístupovým certifikátem nechrání (jeho ověření je kryto certifikátem pravosti), zatímco k otiskům prstů lze přistoupit jen s certifikátem přístupu podle § 6.

#### Vrstva kontaktního čipu (písm. i)–l))

**Doklad s kontaktním čipem** (písm. i)) je definován paralelně s písm. a), ale místo nosiče dat s biometrickými údaji obsahuje „elektronický kontaktní čip". **Certifikát kontroly pravosti údajů** (písm. j)) ověřuje „na základě kontrolních údajů pravosti" pravost a neporušenost údajů zapsaných na kontaktním čipu; **kontrolní údaje pravosti** (písm. l)) jsou zabezpečovací údaje uložené na čipu, které takové ověření umožňují „pro určený rozsah údajů". **Certifikát oprávnění kontrolního orgánu** (písm. k)) umožňuje kontrolnímu orgánu přístup „ve stanoveném rozsahu" k údajům na čipu. Kdo rozsah „určuje" či „stanoví", zákon v § 2 neříká; z § 3 odst. 2 písm. f) a g) plyne, že kontrolní údaje pravosti vytváří policie k údajům, které je oprávněna na čip zapisovat. Pojem „kontrolní orgán" zákon nedefinuje — z § 6a odst. 1 plyne, že jím je správní orgán oprávněný jiným právním předpisem k přístupu ke stanovenému rozsahu údajů.

#### F. Kazuistika

**1. Modelová situace.** Výrobce veřejných dokladů má platný prvotní certifikát pravosti, jehož platnost brzy skončí. Žádá ministerstvo o „následný certifikát" a odmítá znovu prokazovat certifikační podmínky. Ministerstvo mezitím zjistí, že výrobce prvotní certifikát na čtrnáct dní pozbyl (byl zneplatněn pro změnu výrobce a znovu vydán jiné entitě ve skupině), a žádá nový prvotní certifikát.

**2. Právní otázka.** Lze vydat následný certifikát podle § 2 písm. e), není-li řetěz platných certifikátů nepřerušený?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 2 písm. d) (prvotní certifikát — prokázání podmínek), písm. e) (následný certifikát — na základě *platného* prvotního nebo předcházejícího platného certifikátu), písm. f) (certifikační podmínky).
- *Související ustanovení téhož zákona:* § 5 odst. 1–3 (vydání prvotního a následných certifikátů výrobci, povinnost prokázat plnění podmínek na požádání), § 7 odst. 1 (zneplatnění při změně výrobce).
- *Související předpisy:* nařízení Rady (ES) č. 2252/2004 (pozn. 1) jako rámec bezpečnostních prvků.

**4. Subsumpce.** Znak „platný prvotní certifikát nebo předcházející platný certifikát" není naplněn, byl-li certifikát zneplatněn; následný certifikát předpokládá kontinuitu platnosti u téže osoby. Nová entita ve skupině je z hlediska § 7 odst. 1 „změnou výrobce", a tedy důvodem zneplatnění.

**5. Řešení.** Ministerstvo vydá nový prvotní certifikát po prokázání splnění certifikačních podmínek (§ 2 písm. d), § 5 odst. 1); zjednodušený režim následného certifikátu nelze použít. Výrobce může namítat, že podmínky fakticky plnil nepřetržitě — rozhodující však není faktický stav, nýbrž platnost certifikátu jako datové zprávy.

**6. Varianty.** (a) Nedošlo-li ke změně výrobce a předchozí certifikát platí, vydá se následný certifikát zjednodušeným způsobem, přičemž výrobce musí na požádání plnění podmínek prokázat (§ 5 odst. 3). (b) Jde-li o certifikát kontroly pravosti údajů pro doklady s kontaktním čipem, platí stejná logika podle § 4a odst. 2 a 3 vůči policii.

#### G. Protiargumenty a rizika

- *„Definice v § 2 jsou jen technické a nemají právní důsledky."* Neutralizace: na pojmech „platný" a „prvotní/následný" závisí, zda se použije věcný přezkum nebo zjednodušený postup; definice tedy přímo určují procesní režim.
- *„Biometrickým údajem je jakákoli biometrická charakteristika, např. duhovka."* Neutralizace: písm. b) je taxativní — jen zobrazení obličeje a otisky prstů rukou zpracované v nosiči dat.
- *Slabé místo:* zákon používá v § 2 písm. j) „certifikát kontroly pravosti údajů", v § 7a však „certifikát kontroly platnosti údajů" a v § 2 písm. f) „certifikační podmínky", v § 7a odst. 1 však „certifikační pravidla"; jde o terminologickou nedůslednost zdroje, kterou je třeba překlenout výkladem (viz § 7a v kapitole 02).

#### H. Praktický závěr

§ 2 zakládá dvě dokladové vrstvy (nosič dat s biometrickými údaji; kontaktní čip) a čtyři druhy certifikátů, které se dělí podle účelu (pravost údajů / přístup k nim), a mechanismus prvotního a následného certifikátu závislý na nepřerušené platnosti.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Je doklad veřejnou listinou s nosičem dat s biometrickými údaji (písm. a)), nebo s kontaktním čipem (písm. i))?
- [ ] Který certifikát je ve hře: pravosti (g)), přístupu (h)), kontroly pravosti údajů (j)), oprávnění kontrolního orgánu (k))?
- [ ] Jde o prvotní certifikát (prokázání podmínek), nebo následný (platný předchozí certifikát)?
- [ ] Je řetěz platnosti nepřerušený — nebyl předchozí certifikát zneplatněn?

**Typicky rozhodné důkazy / podklady:** certifikační podmínky stanovené ministerstvem, seznam vydaných a zneplatněných certifikátů (§ 3 odst. 1 písm. e), j)), doklad o totožnosti výrobce/orgánu, předchozí certifikát a údaj o jeho platnosti.

---

### § 3 — Působnost

> **§ 3 — Působnost**
>
> (1) Ministerstvo vnitra (dále jen „ministerstvo“)
>
> - a) vydává a zneplatňuje certifikát pravosti,
>
> - b) vydává certifikát přístupu,
>
> - c) žádá příslušný orgán jiného státu o poskytnutí certifikátu pravosti a certifikátu přístupu k veřejnému dokladu vydanému tímto státem,
>
> - d) ověřuje žádost o vydání certifikátu přístupu podle odstavce 2 písm. a), jde-li o prvotní certifikát,
>
> - e) vede seznam vydaných a zneplatněných certifikátů pravosti a vydaných certifikátů přístupu,
>
> - f) vede seznam obdržených certifikátů pravosti a certifikátů přístupu k veřejným dokladům vydaným jinými státy a poskytuje údaje z tohoto seznamu správnímu orgánu uvedenému v § 4 písm. a) a v § 6 odst. 1 písm. a),
>
> - g) stanoví certifikační podmínky,
>
> - h) vydává a zneplatňuje certifikát kontroly pravosti údajů pro doklady s kontaktním čipem,
>
> - i) vydává certifikát oprávnění kontrolního orgánu pro doklady s kontaktním čipem,
>
> - j) vede seznam vydaných a zneplatněných certifikátů kontroly pravosti údajů pro doklady s kontaktním čipem a seznam vydaných certifikátů oprávnění kontrolního orgánu pro doklady s kontaktním čipem.
>
> (2) Policie České republiky (dále jen „policie“) v rozsahu potřebném pro výkon své působnosti2) a za podmínek stanovených tímto zákonem, přímo použitelným předpisem Evropských společenství1) nebo mezinárodní smlouvou, kterou je Česká republika vázána,
>
> - a) žádá příslušný orgán jiného státu o vydání certifikátu přístupu k veřejnému dokladu vydanému tímto státem,
>
> - b) žádá ministerstvo na základě § 4 písm. a) a § 6 odst. 1 písm. a) o poskytnutí nebo vydání certifikátu pravosti a certifikátu přístupu,
>
> - c) vede seznam obdržených certifikátů pravosti a certifikátů přístupu,
>
> - d) používá certifikáty pravosti a certifikáty přístupu pro určení totožnosti držitele veřejného dokladu,
>
> - e) žádá ministerstvo o vydání certifikátu kontroly pravosti údajů,
>
> - f) vytváří kontrolní údaje pravosti k údajům, které je oprávněna zapisovat na kontaktní čip,
>
> - g) používá certifikáty kontroly pravosti údajů a kontrolní údaje pravosti pro ověření pravosti a neporušenosti stanoveného rozsahu údajů uložených na kontaktním čipu,
>
> - h) žádá ministerstvo o vydání certifikátů oprávnění kontrolního orgánu,
>
> - i) vydává certifikáty oprávnění kontrolního orgánu na základě certifikátů oprávnění kontrolního orgánu vydaných ministerstvem,
>
> - j) používá certifikáty oprávnění kontrolního orgánu pro přístup ke stanovenému rozsahu údajů uložených na kontaktním čipu.
>
> (3) Ministerstvo zahraničních věcí zajišťuje předání
>
> - a) žádosti policie nebo ministerstva o vydání prvotního certifikátu přístupu příslušnému orgánu jiného státu,
>
> - b) prvotního certifikátu přístupu vydaného příslušným orgánem jiného státu policii nebo ministerstvu,
>
> - c) žádosti příslušného orgánu jiného státu o vydání prvotního certifikátu přístupu ministerstvu,
>
> - d) prvotního certifikátu přístupu vydaného ministerstvem příslušnému orgánu jiného státu,
>
> - e) prvotního certifikátu pravosti ministerstvu nebo příslušnému orgánu jiného státu.

**Výklad:**

#### Tři orgány, tři role

§ 3 rozděluje působnost mezi tři orgány. **Ministerstvo vnitra** (odst. 1) je jediným vnitrostátním vydavatelem certifikátů — „certifikační autoritou" v materiálním smyslu, byť zákon tento výraz nepoužívá. **Policie České republiky** (odst. 2) je především uživatelem certifikátů při určování totožnosti držitelů a zároveň žadatelem vůči ministerstvu i vůči orgánům jiných států; ve vrstvě kontaktního čipu má navíc aktivní roli (vytváří kontrolní údaje pravosti a sama vydává odvozené certifikáty oprávnění kontrolního orgánu). **Ministerstvo zahraničních věcí** (odst. 3) má roli výlučně zprostředkovatelskou: zajišťuje předání žádostí a certifikátů mezi vnitrostátními orgány a orgány jiných států. Jiné orgány (např. obecní úřady vydávající pasy, celní správa) v § 3 nejsou; mohou být jen příjemci certifikátu podle § 4, § 4a, § 6 nebo § 6a, pokud jim jiný právní předpis zakládá oprávnění k ověřování nebo přístupu.

#### Působnost ministerstva (odst. 1)

Výčet písm. a) až j) lze uspořádat podle dokladové vrstvy a činnosti. *Vrstva nosiče dat:* vydává a zneplatňuje certifikát pravosti (a)), vydává certifikát přístupu (b)) — u něj zákon zneplatnění nepředvídá, což je rozdíl, k němuž se vrací komentář k § 7 —, žádá orgány jiných států o jejich certifikáty (c)), ověřuje žádost policie o prvotní certifikát přístupu adresovanou jinému státu (d)), vede seznam vydaných a zneplatněných certifikátů pravosti a vydaných certifikátů přístupu (e)) a seznam obdržených cizozemských certifikátů, z něhož poskytuje údaje správním orgánům podle § 4 písm. a) a § 6 odst. 1 písm. a) (f)). *Průřezově* stanoví certifikační podmínky (g)) — jediný normotvorný prvek zákona, který ovšem nemá formu právního předpisu a jehož právní povaha je výkladovou otázkou (viz § 2 písm. f)). *Vrstva kontaktního čipu:* vydává a zneplatňuje certifikát kontroly pravosti údajů (h)), vydává certifikát oprávnění kontrolního orgánu (i)) a vede příslušné seznamy (j)).

#### Působnost policie (odst. 2)

Policie jedná „v rozsahu potřebném pro výkon své působnosti" podle jiných předpisů (pozn. 2 uvádí příkladmo zákon o pobytu cizinců) a „za podmínek stanovených tímto zákonem, přímo použitelným předpisem Evropských společenství nebo mezinárodní smlouvou". Tím je její působnost dvojnásobně omezena: věcně (jen při výkonu vlastní působnosti — typicky hraniční a pobytová kontrola) a právně (jen podle ZCVD, nařízení č. 2252/2004 nebo mezinárodní smlouvy). Písm. a) a b) rozlišují žádost vůči *cizímu* orgánu (o certifikát přístupu k cizímu dokladu) a žádost vůči *ministerstvu* (o certifikáty k českým dokladům i o poskytnutí cizozemských certifikátů ze seznamu podle odst. 1 písm. f)). Písm. d) vymezuje účel použití: „určení totožnosti držitele veřejného dokladu" — koresponduje s účelovým omezením biometrie v zákoně o cestovních dokladech a zákoně o pobytu cizinců. Ve vrstvě kontaktního čipu (písm. e)–j)) policie vytváří kontrolní údaje pravosti k údajům, „které je oprávněna zapisovat na kontaktní čip" (f)), a podle písm. i) vydává certifikáty oprávnění kontrolního orgánu „na základě" certifikátů vydaných ministerstvem — jde o jediný případ, kdy certifikát vydává jiný orgán než ministerstvo, a to odvozeně (dvoustupňová hierarchie).

#### Působnost Ministerstva zahraničních věcí (odst. 3)

Předávací role MZV je omezena na *prvotní* certifikáty (přístupu v písm. a)–d), pravosti v písm. e)) a probíhá oběma směry. Následné certifikáty se tudíž vyměňují bez prostřednictví MZV. Zákon tím odráží, že prvotní výměna certifikátů mezi státy je aktem diplomatické důvěry, zatímco následné certifikáty se již vyměňují v zavedeném kanálu.

#### F. Kazuistika

**1. Modelová situace.** Policie potřebuje při hraniční kontrole ověřovat otisky prstů v pasech vydávaných určitým třetím státem. Obrátí se přímo na velvyslanectví tohoto státu s žádostí o certifikát přístupu a současně požádá ministerstvo, aby jí pro doklady s kontaktním čipem vydalo certifikát umožňující přístup ke všem údajům na čipu bez omezení rozsahu.

**2. Právní otázka.** Je policie oprávněna žádat cizí orgán přímo, a může získat přístup k údajům na kontaktním čipu v neomezeném rozsahu?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 3 odst. 2 úvodní část (omezení na rozsah působnosti a podmínky ZCVD, nařízení nebo mezinárodní smlouvy), odst. 2 písm. a) (žádost vůči cizímu orgánu), písm. h) a j) (certifikát oprávnění kontrolního orgánu — přístup „ke stanovenému rozsahu údajů"); odst. 3 písm. a) (předání žádosti o prvotní certifikát přístupu prostřednictvím MZV); odst. 1 písm. d) (ověření žádosti ministerstvem).
- *Související ustanovení téhož zákona:* § 2 písm. k) (certifikát oprávnění kontrolního orgánu — „ve stanoveném rozsahu"), § 6 odst. 1 písm. c) (certifikát přístupu orgánu třetího státu jen podle mezinárodní smlouvy), § 6a odst. 1.
- *Související předpisy:* nařízení Rady (ES) č. 2252/2004 (pozn. 1); zákon o pobytu cizinců (pozn. 2 — působnost policie při kontrole cizinců, místní komentář uvádí povinnost cizince strpět porovnání biometrických údajů z nosiče dat).

**4. Subsumpce.** Policie smí o certifikát přístupu k cizímu dokladu žádat (odst. 2 písm. a)), ale jde-li o prvotní certifikát, zákon počítá s ověřením žádosti ministerstvem (odst. 1 písm. d)) a s předáním prostřednictvím MZV (odst. 3 písm. a)); přímé oslovení velvyslanectví tento postup obchází. Přístup k údajům na kontaktním čipu je pojmově omezen na „stanovený rozsah" (§ 2 písm. k), § 3 odst. 2 písm. j)); neomezený přístup zákon nezná.

**5. Řešení.** Žádost o prvotní certifikát přístupu je třeba směrovat cestou ministerstvo (ověření) — MZV (předání) — cizí orgán; následné certifikáty již mohou jít přímo. Certifikát oprávnění kontrolního orgánu vydá ministerstvo jen v rozsahu, který policii přiznává jiný právní předpis; požadavek na neomezený přístup je nutno odmítnout.

**6. Varianty.** (a) Jde-li o certifikát přístupu k *českému* dokladu, žádá policie ministerstvo přímo (odst. 2 písm. b)) a MZV se neúčastní. (b) Jde-li o orgán třetího státu, který žádá český certifikát přístupu, je podmínkou mezinárodní smlouva (§ 6 odst. 1 písm. c)); bez ní ministerstvo certifikát nevydá.

#### G. Protiargumenty a rizika

- *„Policie je samostatnou certifikační autoritou, protože podle odst. 2 písm. i) vydává certifikáty."* Neutralizace: vydává je jen „na základě" certifikátů ministerstva a jen ve vrstvě kontaktního čipu; její oprávnění je odvozené a nemůže překročit rozsah certifikátu nadřazeného.
- *„Odst. 1 písm. g) zmocňuje ministerstvo k vydání právního předpisu."* Neutralizace: zákon mluví o „stanovení certifikačních podmínek", nikoli o vyhlášce; jde o technické podmínky v mezích § 2 písm. f); zda mají vnější závaznost vůči výrobci, je výkladovou otázkou, kterou je třeba řešit s ohledem na § 5 odst. 3 a § 7 odst. 1.
- *Slabé místo:* u certifikátu přístupu a certifikátu oprávnění kontrolního orgánu zákon výslovně nesvěřuje ministerstvu zneplatnění (srov. písm. a) a h) oproti písm. b) a i)); seznam podle písm. e) proto obsahuje jen *vydané* certifikáty přístupu.

#### H. Praktický závěr

§ 3 soustřeďuje vydávání certifikátů u Ministerstva vnitra, policii přisuzuje roli uživatele a žadatele (s odvozenou vydavatelskou rolí u kontaktního čipu) a MZV roli předávacího kanálu pro prvotní certifikáty ve styku s jinými státy.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Který orgán jedná a v jaké roli — vydavatel (ministerstvo), uživatel/žadatel (policie), zprostředkovatel (MZV)?
- [ ] Jde o prvotní certifikát ve styku s jiným státem — pak cesta ministerstvo (ověření) → MZV (předání)?
- [ ] Jedná policie v rozsahu své působnosti podle jiného předpisu a za podmínek ZCVD, nařízení nebo mezinárodní smlouvy?
- [ ] Je rozsah přístupu k údajům na kontaktním čipu „stanoven" jiným právním předpisem?

**Typicky rozhodné důkazy / podklady:** žádost o certifikát a doklad o jejím ověření ministerstvem, záznam o předání prostřednictvím MZV, seznamy podle odst. 1 písm. e), f), j), znění jiného právního předpisu zakládajícího působnost policie nebo kontrolního orgánu, mezinárodní smlouva u třetích států.

---

### § 4 — Certifikát pravosti

> **§ 4 — Certifikát pravosti**
>
> Ministerstvo poskytne certifikát pravosti
>
> - a) správnímu orgánu, který může za podmínek stanovených jiným právním předpisem3) ověřit pravost a neporušenost biometrických údajů ve veřejném dokladu,
>
> - b) příslušnému orgánu jiného státu.

**Výklad:**

#### Poskytnutí, nikoli vydání

§ 4 používá sloveso „poskytne", zatímco § 5 mluví o „vydání" certifikátu pravosti výrobci. Rozdíl je systémový: certifikát pravosti se *vydává* výrobci veřejného dokladu (ten jím zabezpečuje biometrické údaje při výrobě dokladu) a *poskytuje* se těm, kdo pravost údajů ověřují. Ověřující subjekt tedy nedostává vlastní certifikát, ale certifikát výrobce, s nímž pak porovnává údaje v nosiči dat. Tomu odpovídá i § 3 odst. 1 písm. e) a f) (seznamy vydaných a obdržených certifikátů) a § 7 odst. 2 (předávání seznamu zneplatněných certifikátů „subjektům uvedeným v § 4").

#### Dva okruhy příjemců

**Písm. a)** — správní orgán, který může „za podmínek stanovených jiným právním předpisem" ověřit pravost a neporušenost biometrických údajů. Poznámka pod čarou č. 3 odkazuje příkladmo na zákon o cestovních dokladech; podle jeho místního komentáře přísluší kontrola cestovního dokladu včetně ověření pravosti a porovnání biometrických údajů policii. Oprávnění k ověřování tedy zakládá vždy jiný předpis — ZCVD jej neuděluje, jen k němu dodává technický prostředek. Správní orgán bez takového zákonného oprávnění certifikát pravosti nedostane. Zákon nestanoví, že poskytnutí předchází žádost; u policie plyne žádost z § 3 odst. 2 písm. b). **Písm. b)** — příslušný orgán jiného státu; zde zákon žádnou další podmínku neklade (na rozdíl od certifikátu přístupu v § 6 odst. 1 písm. b), c)), což odpovídá tomu, že certifikát pravosti umožňuje jen *ověřit* údaje, nikoli k nim *přistoupit* — jeho poskytnutí cizím orgánům je v zájmu důvěryhodnosti českých dokladů v zahraničí. Předání prvotního certifikátu pravosti cizímu orgánu zajišťuje MZV (§ 3 odst. 3 písm. e)).

#### Forma poskytnutí

Zákon neupravuje, jakou formou ministerstvo certifikát poskytne, ani nepředvídá rozhodnutí o jeho neposkytnutí. Poskytnutí certifikátu je svou povahou faktický úkon (předání datové zprávy), nikoli správní řízení podle části druhé správního řádu; podle místního komentáře ke správnímu řádu se na jiné úkony správních orgánů subsidiárně použije část čtvrtá (§ 154 a násl.). Je výkladovou otázkou, jak se správní orgán, který se domnívá, že splňuje podmínky písm. a), brání proti neposkytnutí — zákon mu žádný procesní nástroj nedává.

#### F. Kazuistika

**1. Modelová situace.** Celní úřad požádá ministerstvo o poskytnutí certifikátu pravosti k českým cestovním pasům, aby mohl při kontrole zboží ověřovat pravost pasů cestujících. Ministerstvo odmítne s tím, že celní úřad nemá podle žádného předpisu oprávnění ověřovat biometrické údaje.

**2. Právní otázka.** Postačí k poskytnutí certifikátu pravosti obecná kontrolní působnost správního orgánu, nebo je nutné zvláštní zákonné oprávnění k ověřování biometrických údajů?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 4 písm. a) (správní orgán, který může za podmínek jiného předpisu ověřit pravost a neporušenost biometrických údajů).
- *Související ustanovení téhož zákona:* § 1 (účel — ochrana údajů), § 3 odst. 1 písm. f) (poskytování údajů ze seznamu cizozemských certifikátů jen orgánům podle § 4 písm. a)), § 7 odst. 2.
- *Související předpisy:* zákon o cestovních dokladech (pozn. 3 — podle místního komentáře náleží kontrola dokladu včetně biometrie policii; údaje z nosiče dat nelze zpracovávat jinak, než stanoví zákon); správní řád, část čtvrtá (§ 154 a násl.).

**4. Subsumpce.** Znak „může za podmínek stanovených jiným právním předpisem ověřit pravost a neporušenost biometrických údajů" vyžaduje výslovné oprávnění k zacházení s biometrickými údaji v nosiči dat; obecná kontrolní působnost tento znak nenaplňuje, zejména když dokladový zákon zpracování údajů z nosiče dat váže na zákon.

**5. Řešení.** Ministerstvo certifikát neposkytne; postup je správný. Celní úřad se může spolehnout na vizuální a strojově čitelné prvky dokladu, biometrické ověření však náleží orgánu s výslovným oprávněním. Procesní obrana proti neposkytnutí je výkladově nejasná (viz výše).

**6. Varianty.** (a) Založí-li později zákon celním orgánům výslovné oprávnění ověřovat biometrické údaje, stanou se příjemcem podle písm. a) bez změny ZCVD. (b) Orgán jiného státu certifikát pravosti dostane bez dalších podmínek (písm. b)); prvotní certifikát mu předá MZV.

#### G. Protiargumenty a rizika

- *„Certifikát pravosti není citlivý, může být poskytnut komukoli."* Neutralizace: zákon okruh příjemců vymezuje taxativně (správní orgán s oprávněním, orgán jiného státu); poskytnutí mimo tento okruh by bylo bez zákonného podkladu.
- *„Odmítnutí poskytnutí je rozhodnutím, proti němuž je odvolání."* Neutralizace: zákon o rozhodnutí nemluví a poskytnutí má povahu faktického úkonu; opačný výklad je možný, ale opírá se jen o obecnou subsidiaritu správního řádu — jde o výkladovou otázku.
- *Slabé místo:* § 4 nepracuje s kategorií prvotní/následný certifikát, ačkoli § 3 odst. 3 písm. e) mluví o předání „prvotního certifikátu pravosti" cizímu orgánu; následné certifikáty pravosti se tedy cizím orgánům zřejmě poskytují bez prostřednictví MZV.

#### H. Praktický závěr

§ 4 určuje, komu ministerstvo *poskytne* certifikát pravosti vydaný výrobci: správnímu orgánu s výslovným zákonným oprávněním ověřovat biometrické údaje a příslušnému orgánu jiného státu.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Zakládá jiný právní předpis správnímu orgánu oprávnění ověřovat pravost a neporušenost biometrických údajů?
- [ ] Jde o orgán jiného státu — pak bez další podmínky, prvotní certifikát cestou MZV.
- [ ] Je příjemce zapsán jako adresát seznamu zneplatněných certifikátů podle § 7 odst. 2?

**Typicky rozhodné důkazy / podklady:** ustanovení jiného předpisu zakládající oprávnění k ověřování, žádost orgánu, záznam o poskytnutí certifikátu, seznam podle § 3 odst. 1 písm. e).

---

### § 4a — Certifikát kontroly pravosti údajů

> **§ 4a — Certifikát kontroly pravosti údajů**
>
> (1) Ministerstvo poskytne certifikát kontroly pravosti údajů správnímu orgánu, který může za podmínek stanovených jiným právním předpisem ověřovat pravost a neporušenost údajů uložených na kontaktním čipu.
>
> (2) Ministerstvo vydá prvotní certifikát kontroly pravosti údajů policii, pokud splňuje certifikační podmínky.
>
> (3) Na základě předložení platného prvotního certifikátu kontroly pravosti údajů nebo předcházejícího platného certifikátu kontroly pravosti údajů ministerstvo vydává policii následné certifikáty kontroly pravosti údajů, pokud i nadále splňuje certifikační podmínky.

**Výklad:**

#### Paralela k § 4 a § 5 ve vrstvě kontaktního čipu

§ 4a spojuje v jednom ustanovení to, co pro vrstvu nosiče dat upravují § 4 (poskytnutí) a § 5 (vydání). **Odst. 1** je paralelou § 4 písm. a): ministerstvo *poskytne* certifikát kontroly pravosti údajů správnímu orgánu, který může za podmínek jiného právního předpisu ověřovat pravost a neporušenost údajů na kontaktním čipu. Chybí paralela k § 4 písm. b) — orgán jiného státu zde není, což odpovídá tomu, že doklad s kontaktním čipem je vnitrostátním identifikačním dokladem, nikoli cestovním dokladem podle nařízení č. 2252/2004. **Odst. 2 a 3** jsou paralelou § 5 odst. 1 a 2: ministerstvo *vydá* prvotní certifikát policii, splňuje-li certifikační podmínky, a následné certifikáty na základě platného prvotního nebo předcházejícího platného certifikátu, „pokud i nadále splňuje certifikační podmínky".

#### Policie jako adresát vydání

Rozdíl proti § 5 spočívá v tom, komu se certifikát *vydává*: nikoli výrobci dokladu, ale policii. Důvod plyne z § 3 odst. 2 písm. f) a g) — policie sama vytváří kontrolní údaje pravosti k údajům, které je oprávněna zapisovat na kontaktní čip, a potřebuje tedy certifikát, jímž tyto údaje zabezpečí; ověřovat pak může každý správní orgán podle odst. 1, kterému ministerstvo certifikát poskytne. Policie je tak ve vrstvě kontaktního čipu v postavení obdobném výrobci ve vrstvě nosiče dat. Chybí ovšem paralela k § 5 odst. 3 (povinnost prokázat plnění podmínek na požádání); zda ji lze dovodit z podmínky „pokud i nadále splňuje certifikační podmínky" v odst. 3, je výkladovou otázkou — vůči policii jako orgánu téhož resortu je tato kontrola spíše otázkou vnitřní koordinace než vynutitelné povinnosti.

#### F. Kazuistika

**1. Modelová situace.** Obecní úřad obce s rozšířenou působností ověřuje při výkonu své agendy údaje zapsané policií na kontaktní čip dokladu a žádá ministerstvo o certifikát kontroly pravosti údajů. Současně policie žádá o následný certifikát, ačkoli od vydání prvotního certifikátu změnila technické prostředí a certifikační podmínky již zjevně neplní.

**2. Právní otázka.** Komu a za jakých podmínek ministerstvo certifikát kontroly pravosti údajů poskytne, resp. vydá?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 4a odst. 1 (poskytnutí správnímu orgánu s oprávněním podle jiného předpisu), odst. 2 (prvotní certifikát policii při splnění podmínek), odst. 3 (následný certifikát při trvajícím splnění podmínek).
- *Související ustanovení téhož zákona:* § 2 písm. j), l) (pojmy), § 3 odst. 1 písm. h), j) a odst. 2 písm. e)–g), § 7a (zneplatnění).
- *Související předpisy:* jiný právní předpis zakládající oprávnění úřadu ověřovat údaje na čipu (zákon o dokladu s kontaktním čipem — místně nekomentován, proto obecně).

**4. Subsumpce.** Úřad je příjemcem podle odst. 1 jen tehdy, zakládá-li mu jiný právní předpis oprávnění ověřovat pravost údajů na čipu; samotná agenda nestačí. Policie splňuje znak odst. 3 jen „pokud i nadále splňuje certifikační podmínky"; při zjevném neplnění není následný certifikát vydán.

**5. Řešení.** Úřadu ministerstvo certifikát poskytne po ověření zákonného oprávnění. Policii následný certifikát nevydá; řešením je uvedení prostředí do souladu s certifikačními podmínkami a — podle okolností — nový prvotní certifikát, zneplatní-li ministerstvo dosavadní podle § 7a.

**6. Varianty.** (a) Plní-li policie podmínky nadále, vydá se následný certifikát zjednodušeně na základě platného předchozího. (b) Orgán jiného státu certifikát kontroly pravosti údajů podle § 4a nedostane — ustanovení s ním nepočítá.

#### G. Protiargumenty a rizika

- *„§ 4a odst. 1 umožňuje poskytnout certifikát kteremukoli orgánu veřejné moci."* Neutralizace: podmínkou je oprávnění podle jiného právního předpisu ověřovat údaje na kontaktním čipu, stejně jako u § 4 písm. a).
- *„Policie nemusí prokazovat plnění podmínek, protože § 4a neobsahuje obdobu § 5 odst. 3."* Neutralizace: odst. 3 podmiňuje vydání následného certifikátu trvajícím splněním podmínek; ministerstvo tedy musí mít možnost je ověřit, byť zákon nestanoví výslovnou povinnost prokazování — výkladová otázka.
- *Slabé místo:* absence orgánů jiných států v § 4a může být problémem při přeshraničním uznávání dokladů s kontaktním čipem; řešení musí hledat jiný právní předpis.

#### H. Praktický závěr

§ 4a přenáší mechanismus certifikátu pravosti na doklady s kontaktním čipem: poskytuje se správním orgánům s oprávněním ověřovat údaje na čipu, vydává se policii (prvotní po splnění podmínek, následný při jejich trvajícím plnění).

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Žádá správní orgán o *poskytnutí* (odst. 1 — oprávnění podle jiného předpisu), nebo policie o *vydání* (odst. 2, 3)?
- [ ] U prvotního certifikátu: prokázáno splnění certifikačních podmínek?
- [ ] U následného: platí předchozí certifikát a podmínky jsou nadále plněny?

**Typicky rozhodné důkazy / podklady:** certifikační podmínky, doklad o jejich splnění policií, předchozí certifikát, ustanovení jiného předpisu zakládající oprávnění ověřujícího orgánu, seznam podle § 3 odst. 1 písm. j).

---
