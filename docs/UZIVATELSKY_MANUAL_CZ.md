# Uživatelský manuál – Bike Route Planner

## Představení produktu

**Bike Route Planner** (zkráceně **BRP**) je Android aplikace pro cyklisty, která pomáhá s plánováním tras a během jízdy poskytuje navigační instrukce. Aplikace je navržena tak, aby vám pomohla bezpečně, přehledně a efektivně dojet do cíle.

### Pro koho je aplikace určená?

Aplikace je vhodná pro různé typy cyklistů:

* **Silniční cyklisté** – hledají plynulé trasy po zpevněných površích.
* **Gravel jezdci** – chtějí kombinovat asfalt, štěrk a lehce nezpevněné cesty.
* **MTB cyklisté** – preferují lesní cesty, traily a terénní úseky.
* **Komutéři** – jezdí pravidelně do práce, do školy nebo po městě.
* **Turisté** – plánují delší výlety se stabilním tempem.
* **Průzkumníci** – chtějí objevovat nové trasy a méně známé úseky.

### Klíčové výhody

* **Offline trasování** – během jízdy není nutné připojení k internetu.
* **Vlastní plánování tras** – trasu si můžete vytvořit podle svých preferencí.
* **Navigace v overlay režimu** – trasy z BRP lze zobrazovat v aplikaci Bike Radar Overlay.
* **Více typů kol** – výpočet trasy se přizpůsobí zvolenému typu kola.
* **Více stylů tras** – můžete zvolit rychlejší, kratší, bezpečnější nebo vyváženou trasu.
* **Okruhové trasy** – aplikace umí generovat okruhy podle nastavené délky.

---

## Instalace a požadavky

### Požadavky na zařízení

* **Android 8.0** / **API 26** nebo novější
* **GPS senzor** pro určování polohy
* **Volné místo v úložišti** pro mapová data

### Instalace BRouter

Pro správné fungování potřebuje aplikace BRP nainstalovanou aplikaci **BRouter**. BRouter slouží k offline výpočtu tras.

#### Jak nainstalovat BRouter

1. Otevřete BRP. Při prvním spuštění se zobrazí dialog s možností stáhnout BRouter.
2. Přejděte do Google Play Store a nainstalujte aplikaci **BRouter**.
3. Po instalaci otevřete BRouter a stáhněte mapová data pro oblast, ve které chcete plánovat trasy.

### Instalace Bike Radar Overlay

Instalace aplikace **Bike Radar Overlay** je volitelná.

Pokud chcete zobrazovat navigační instrukce v overlay režimu, například při zamčeném displeji nebo v jízdním zobrazení, nainstalujte také aplikaci **Bike Radar Overlay**.

Bike Radar Overlay slouží k zobrazování informací během jízdy a může zároveň zobrazovat navigační instrukce z BRP.

---

## Úvod do plánování trasy

### Jak začít

1. Spusťte aplikaci **Bike Route Planner**.
2. Na hlavní obrazovce klepněte na tlačítko **Plánovač**.
3. Vyberte počáteční bod a cíl trasy.

### Výběr počátečního bodu

* **Použít GPS**: Klepněte na ikonu polohy v pravém horním rohu. Aplikace použije vaši aktuální polohu.
* **Výběr na mapě**: Klepněte a podržte místo na mapě, kde má trasa začínat.

### Výběr cíle

* **Výběr na mapě**: Klepněte a podržte místo na mapě, kde má být cíl trasy.
* **Zrušení cíle**: Cíl můžete zrušit klepnutím na ikonu **X** v pravém horním rohu.

### Přidání průjezdních bodů

Průjezdní body slouží k tomu, aby trasa vedla přes konkrétní místa.

1. Po výběru cíle klepněte na tlačítko **+**.
2. Klepněte a podržte požadované místo na mapě.
3. Tím přidáte nový průjezdní bod.

Přidat lze až **8 průjezdních bodů**.

---

## Typy kol

Aplikace podporuje 6 typů kol. Každý typ používá odlišné profilování trasy.

### 1. Road – silniční kolo

**Popis:**
Silniční profil s důrazem na zpevněný povrch, plynulost a bezpečnost.

**Preferuje:**

* asfaltové a betonové povrchy,
* cyklostezky a cyklotrasy,
* rezidenční oblasti s nižší rychlostí provozu.

**Vyhýbá se:**

* nezpevněným terénním cestám,
* nekvalitním povrchům,
* technicky náročným úsekům.

**Pro koho je vhodný:**
Pro jezdce na silničních kolech, kteří chtějí plynulou a bezpečnou jízdu po kvalitním povrchu.

### 2. Gravel – gravel kolo

**Popis:**
Profil kombinující asfalt, štěrk a dobře sjízdné nezpevněné cesty.

**Preferuje:**

* asfalt a zpevněné povrchy,
* jemný štěrk,
* kvalitní lesní a polní cesty.

**Toleruje:**

* středně kvalitní nezpevněné cesty,
* cesty typu `tracktype grade 1–3`.

**Vyhýbá se:**

* špatně sjízdným povrchům,
* velmi technickým úsekům.

**Pro koho je vhodný:**
Pro gravel jezdce, kteří chtějí kombinovat silnici a lehčí terén.

### 3. MTB – horské kolo

**Popis:**
Profil pro terén, traily a technicky náročnější úseky.

**Preferuje:**

* terénní trasy a traily,
* lesní a parkové cesty,
* cesty typu `tracktype grade 1–3`.

**Toleruje:**

* nezpevněné povrchy,
* pěší stezky, pokud je jízda na kole povolena,
* kvalitní turistické cesty.

**Vyhýbá se:**

* silnicím pro motorová vozidla bez povolení pro kola,
* cestám s jednoznačným zákazem vjezdu.

**Pro koho je vhodný:**
Pro MTB jezdce, kteří chtějí jezdit v terénu.

### 4. Touring – cestovní kolo

**Popis:**
Profil pro delší vyjížďky se stabilním tempem a spolehlivým povrchem.

**Preferuje:**

* spolehlivé povrchy,
* trasy s plynulým tempem,
* delší trasy vhodné pro pohodlnou jízdu.

**Toleruje:**

* středně kvalitní nezpevněné cesty,
* klidnější komunikace s nižší rychlostí provozu.

**Pro koho je vhodný:**
Pro turistické jezdce, kteří chtějí delší a pohodlnější trasy.

### 5. Commute – komutérské kolo

**Popis:**
Profil pro každodenní dopravu s důrazem na spolehlivost, přehlednost a čas.

**Preferuje:**

* pevné povrchy,
* přímé trasy,
* známé a spolehlivé cesty.

**Toleruje:**

* cyklostezky,
* rezidenční oblasti,
* městské komunikace vhodné pro kola.

**Pro koho je vhodný:**
Pro každodenní cesty do práce, do školy nebo po městě.

### 6. Explore – průzkumný profil

**Popis:**
Profil pro objevování nových tras a méně známých úseků, i za cenu nižší předvídatelnosti.

**Preferuje:**

* nové a méně známé trasy,
* kombinaci různých povrchů,
* objevování nových míst.

**Toleruje:**

* více rizikových úseků,
* méně předvídatelné trasy,
* větší různorodost povrchů.

**Pro koho je vhodný:**
Pro jezdce, kteří chtějí objevovat nové trasy a nevadí jim větší míra nejistoty.

---

## Styly tras

Styl trasy určuje, jak aplikace vyvažuje bezpečnost, rychlost, délku a komfort.

### 1. Faster – rychlejší trasa

**Popis:**
Rychlejší profil, který dává větší prioritu času jízdy. Může vést po frekventovanějších silnicích, pokud je na nich jízda na kole povolena.

**Co dělá:**

* upřednostňuje rychlost a efektivitu,
* může přijmout silnice s vyšším provozem,
* zvolí rychlejší variantu, i když je méně klidná.

**Upozornění:**
Tento styl může vést po silnicích s vyšším provozem. Úseky se zákazem jízdy na kole zůstávají vyloučené.

**Použití:**
Vhodné, když se potřebujete dostat do cíle co nejrychleji a nevadí vám jízda po méně klidných silnicích.

### 2. Shortest – nejkratší trasa

**Popis:**
Profil s důrazem na minimální délku trasy. Může obsahovat méně komfortní nebo frekventovanější úseky, pokud je na nich jízda na kole legální.

**Co dělá:**

* minimalizuje celkovou délku trasy,
* může zvolit kratší, ale méně pohodlné cesty,
* může vést po komunikacích s vyšším provozem.

**Upozornění:**
Nejkratší trasa nemusí být vždy nejpohodlnější ani nejbezpečnější.

**Použití:**
Vhodné, když chcete co nejkratší trasu bez ohledu na komfort.

### 3. Touring / Balanced – turistická / vyvážená trasa

**Popis:**
Vyvážený profil pro běžné vyjížďky a delší trasy.

**Co dělá:**

* hledá kompromis mezi rychlostí, bezpečností a kvalitou povrchu,
* přijímá středně frekventované silnice,
* upřednostňuje kvalitní a spolehlivé povrchy.

**Použití:**
Doporučená výchozí volba pro většinu uživatelů.

### 4. Safer – bezpečnější trasa

**Popis:**
Profil se silnější preferencí klidných úseků, cyklostezek a komunikací s nižším provozem.

**Co dělá:**

* upřednostňuje bezpečnější trasy,
* výrazně penalizuje hlavní silnice bez cyklopruhů,
* preferuje cyklostezky, rezidenční oblasti a klidné cesty.

**Použití:**
Vhodné, pokud preferujete klidnější jízdu a jste ochotni jet delší trasu výměnou za vyšší bezpečnost.

---

## Popis hlavního rozhraní

### Hlavní obrazovka

```text
+---------------------------------+
| [Menu]              [Plánovač]  |
|                                 |
|   [Mapa s trasou]               |
|                                 |
| [Začít jízdu]                   |
| [Pokračovat v plánování]        |
| [Zpět do menu]                  |
+---------------------------------+
```

### Menu

Klepnutím na ikonu menu v levém spodním rohu otevřete boční nabídku s dalšími funkcemi:

* **Plánovač mapy** – návrat do plánování trasy.
* **Upravit UI** – nastavení velikosti a vzhledu rozhraní.
* **Offline data** – správa mapových dat pro BRouter.
* **Nastavení aplikace** – jazyk, zobrazení povrchů, provoz a další možnosti.
* **Ukončit** – zavření aplikace.

---

## Podrobný průvodce funkcemi

## Kapitola 1: Výběr počátku a cíle

### Výběr počátku pomocí GPS

1. Klepněte na tlačítko **Plánovač**.
2. Počkejte, až aplikace získá GPS polohu.
3. Jakmile se ikona polohy zbarví zeleně, je poloha připravena k použití.

### Výběr počátku z mapy

1. Klepněte na tlačítko **Plánovač**.
2. Klepněte a podržte místo na mapě, kde má trasa začínat.
3. Po chvíli se zobrazí potvrzovací dialog.
4. Výběr potvrďte.

### Výběr cíle z mapy

1. Po výběru počátečního bodu se zobrazí tlačítko **Do**.
2. Klepněte a podržte místo na mapě, kde má být cíl.
3. Po chvíli se zobrazí potvrzovací dialog.
4. Výběr potvrďte.

### Úprava počátku nebo cíle

* Vybraný počátek i cíl můžete na mapě přesunout.
* Klepněte na bod, podržte jej a přesuňte na nové místo.
* Novou pozici potvrďte.

### Odstranění bodu

* Klepněte na ikonu **X** vedle bodu.
* Potvrďte odstranění.

---

## Kapitola 2: Průjezdní body

### Přidání průjezdního bodu

1. Po výběru cíle klepněte na tlačítko **+**.
2. Klepněte a podržte místo na mapě, kde má být průjezdní bod.
3. Výběr potvrďte.

### Pořadí bodů

* Počáteční bod je vždy první.
* Cíl je vždy poslední.
* Průjezdní body jsou řazeny podle pořadí, ve kterém byly přidány.

### Úprava pořadí

* Pořadí průjezdních bodů aktuálně nelze měnit.
* Pokud potřebujete jiné pořadí, vytvořte novou trasu.

### Odstranění průjezdního bodu

1. Klepněte na tlačítko **Vymazat**.
2. Vyberte bod, který chcete odstranit.
3. Odstranění potvrďte.

---

## Kapitola 3: Generování okruhu

### Jak vygenerovat okruh

1. Klepněte na tlačítko **Okruh**.
2. Zvolte počáteční polohu pomocí GPS nebo výběrem na mapě.
3. Nastavte cílovou vzdálenost:

   * minimum: **5 km**,
   * doporučeno: **30 km**,
   * maximum: **150 km**.
4. Zvolte počet bodů smyčky:

   * minimum: **3 body**,
   * doporučeno: **6 bodů**,
   * maximum: **9 bodů**.
5. Vyberte preferovaný směr: **N, NE, E, SE, S, SW, W, NW**.
6. Zvolte směr jízdy: **po směru hodinových ručiček** nebo **proti směru hodinových ručiček**.
7. Klepněte na **Generovat smyčku**.

### Úprava okruhu

* Po vygenerování můžete body okruhu upravit přímo na mapě.
* Klepnutím na **Upravit smyčku** přejdete do režimu úprav.
* Klepnutím na **Znovu generovat** vytvoříte nový výpočet.

### Zrušení okruhu

* Klepněte na **Vymazat smyčku**.
* Okruh bude odstraněn, mapa však zůstane zobrazena.

---

## Kapitola 4: Spuštění navigace

### Spuštění navigace

1. Po dokončení plánování klepněte na **Jít**.
2. Aplikace začne zpracovávat trasu.
3. Po dokončení výpočtu znovu klepněte na **Jít** a spusťte navigaci.

### Během navigace

* Aplikace průběžně zobrazuje stav navigace.
* Zobrazuje instrukce k dalšímu odbočení.
* Vzdálenost k odbočce se průběžně aktualizuje.

### Pozastavení navigace

* Klepněte na **Pauza**.
* Během pauzy se navigační instrukce nezobrazují.
* Poloha se nadále sleduje.

### Pokračování po pauze

* Klepněte na **Obnovit**.
* Navigace bude pokračovat z aktuální nebo poslední známé polohy.

### Přepočet trasy

Pokud opustíte naplánovanou trasu, aplikace ji automaticky přepočítá.

* Nová trasa se vypočítá z aktuální polohy.
* Přepočet obvykle trvá několik sekund.

### Ukončení navigace

1. Klepněte na **Zrušit**.
2. Potvrďte ukončení navigace.
3. Mapa zůstane zobrazena, ale navigace se ukončí.

---

## Kapitola 5: Nastavení aplikace

### Jazyk aplikace

* **Systém** – použije se jazyk zařízení.
* **English** – angličtina.
* **Čeština** – čeština.

### Jazyk navigace

Nastavení jazyka navigace určuje jazyk navigačních instrukcí a názvů.

Dostupné možnosti jsou stejné jako u jazyka aplikace.

### Výchozí přiblížení mapy

* Nastavuje výchozí úroveň přiblížení mapy.
* Rozsah je od **3** po **19**.
* Doporučená hodnota je **14**.

### Zobrazení cyklotras

* Zobrazí na mapě zvýrazněné cyklotrasy.
* Pomáhá rozpoznat oficiální nebo značené cyklistické trasy.
* Průhlednost lze nastavit v rozsahu **25–75 %**.

### Zobrazení pěších tras

* Zobrazí na mapě turistické a pěší trasy.
* Pomáhá při plánování tras v přírodě nebo mimo město.
* Průhlednost lze nastavit v rozsahu **25–75 %**.

### Nastavení zobrazení navigace

* **Minimální přiblížení** – používá se pro vzdálenější odbočky.
* **Maximální přiblížení** – používá se pro blízké odbočky.

### Vlastní styl trasy

* **Šířka čáry** – nastavitelná v rozsahu **2–18**.
* **Barva čáry** – výběr barvy podle dostupné palety.

### Úprava rozhraní

* **Velikost tlačítek** – nastavitelná v rozsahu **85–145 %**.
* **Velikost ovládacích prvků** – ovlivňuje velikost prvků na mapě.
* **Velikost ikony jezdce** – nastavitelná v rozsahu **20–44 dp**.
* **Velikost navigačního banneru** – upravuje velikost textu a šipky.

---

## Kapitola 6: Offline data pro BRouter

### Jak stáhnout mapová data

1. V menu klepněte na **Offline data**.
2. Zobrazí se informace o aplikaci BRouter.
3. Klepněte na **Otevřít správce stahování**.
4. V aplikaci BRouter vyberte požadovanou oblast.
5. Stáhněte segmenty pro oblast, ve které chcete plánovat trasu.

### Kontrola dostupnosti dat

* Aplikace automaticky kontroluje, zda jsou potřebné segmenty stažené.
* Pokud chybí, zobrazí se varování.
* Doporučené segmenty jsou zvýrazněné.

### Přepočet doporučených segmentů

* Po změně počátku nebo cíle se doporučené segmenty přepočítají.
* Klepnutím na **Obnovit** spustíte nový výpočet.

---

## Kapitola 7: Integrace s Bike Radar Overlay

### Jak nastavit integraci

1. Nainstalujte aplikaci **Bike Radar Overlay**.
2. Spusťte Bike Radar Overlay a dokončete základní nastavení.
3. V BRP naplánujte trasu a spusťte navigaci.
4. Navigační data se budou odesílat do aplikace Bike Radar Overlay.

### Co se přenáší do Bike Radar Overlay

* **Vzdálenost k odbočce** – v metrech.
* **Typ odbočení** – například „Doprava“, „Doleva“ apod.
* **Název ulice** – název komunikace, po které jedete.
* **Čas do cíle** – odhadovaný čas příjezdu.
* **Stav navigace** – například aktivní navigace, jízda nebo ztráta GPS.

### Zobrazení v Bike Radar Overlay

* Bike Radar Overlay může zobrazovat navigaci na zamčené obrazovce nebo v jízdním režimu.
* Pokud je další odbočka blíže než **200 m**, displej se může rozsvítit.
* Upozornění z radaru má vyšší prioritu než navigační instrukce.

---

## Kapitola 8: Vysvětlení zvolené trasy

### Proč aplikace zvolila určitou trasu?

Aplikace může zobrazit shrnutí trasy, které pomáhá pochopit, proč byla trasa vypočítána právě tímto způsobem.

Shrnutí může obsahovat:

* **Délku** – celkovou vzdálenost trasy.
* **Trvání** – odhadovaný čas jízdy.
* **Povrch** – procentuální zastoupení jednotlivých povrchů, například asfaltu nebo štěrku.
* **Provoz** – podíl úseků s různou úrovní provozu.
* **Rizika** – počet problematických úseků, například ostrých odbočení nebo otoček.

### Problematičtější úseky

Aplikace označuje problematické úseky oranžově.

Může jít například o:

* **možné otočení do protisměru**,
* **ostré obrácení směru**,
* **návrat po stejné cestě**.

### Závazné filtry

Aplikace vylučuje například tyto typy úseků:

* `highway=motorway` – dálnice,
* `bicycle=no` – zákaz jízdy na kole,
* `access=private` bez výjimky,
* `construction` – staveniště nebo úseky ve výstavbě.

---

## Kapitola 9: Variabilní nastavení tras

### Proč existuje více profilů?

Každý typ kola a styl trasy používá vlastní profilovací logiku, protože různí jezdci mají různé požadavky:

* **Silniční kolo** vyžaduje především kvalitní a plynulý povrch.
* **Gravel kolo** zvládne kombinaci asfaltu a lehčího terénu.
* **MTB kolo** je vhodné i pro terénní a technické úseky.

### Jak funguje profilování?

Profilování je založeno na kombinaci několika faktorů:

1. **Typ kola** – určuje, jaké povrchy a cesty jsou fyzicky vhodné.
2. **Styl trasy** – určuje kompromis mezi rychlostí, bezpečností a délkou.
3. **Uživatelské preference** – například vyloučení schodů, zákazů nebo rizikových úseků.

### Příklady kombinací profilů

#### Road + Safer

* Upřednostní cyklostezky a rezidenční oblasti.
* Vyhne se hlavním silnicím, pokud je dostupná vhodná alternativa.
* Trasa může být delší, ale bezpečnější.

#### Gravel + Faster

* Povolí lehčí terén.
* Dává větší prioritu rychlosti.
* Může zvolit rychlejší variantu přes štěrkové nebo nezpevněné cesty.

#### MTB + Safer

* Povolí terénní úseky.
* Vyhne se nebezpečným nebo nevhodným cestám.
* Upřednostní bezpečnější průjezd terénem.

---

## Kapitola 10: Typické scénáře použití

### Scénář 1: Denní cesta do práce

1. Spusťte BRP.
2. Zvolte **Commute** a styl **Faster**.
3. Vyberte počátek, například domov.
4. Vyberte cíl, například práci.
5. Spusťte navigaci.

### Scénář 2: Víkendový výlet

1. Spusťte BRP.
2. Zvolte **Gravel** nebo **Touring**.
3. Zvolte styl **Safer** nebo **Touring / Balanced**.
4. Vyberte cíl a zkontrolujte navrženou trasu.
5. Spusťte navigaci.

### Scénář 3: MTB výlet

1. Spusťte BRP.
2. Zvolte **MTB**.
3. Zvolte styl **Safer** nebo **Touring / Balanced**.
4. Vyberte cíl v terénu.
5. Spusťte navigaci.

### Scénář 4: Okruhová jízda

1. Spusťte BRP.
2. Zvolte **Gravel** nebo **MTB**.
3. Klepněte na **Okruh**.
4. Nastavte délku, například **30–50 km**.
5. Vygenerujte okruh a případně upravte jeho body.
6. Spusťte navigaci.

---

## Kapitola 11: Obecné tipy

### Tip 1: Zkontrolujte pokrytí mapovými daty

Před plánováním delší trasy ověřte, zda máte stažené potřebné segmenty:

1. Klepněte na **Offline data**.
2. Zkontrolujte, zda jsou segmenty pro danou oblast dostupné.
3. Pokud chybí, stáhněte je v aplikaci BRouter.

### Tip 2: Použijte GPS pro rychlý výběr počátku

1. Klepněte na ikonu GPS.
2. Počkejte, až se ikona zbarví zeleně.
3. Potvrďte použití aktuální polohy.

### Tip 3: Zkontrolujte varování před jízdou

Před zahájením jízdy doporučujeme:

1. Zkontrolovat oranžová varování na mapě.
2. Přečíst si vysvětlení problematických úseků.
3. Zvážit, zda trasa odpovídá vašim schopnostem a typu kola.

### Tip 4: Pauza je bezpečná

Pokud potřebujete přestávku:

1. Klepněte na **Pauza**.
2. Aplikace bude nadále sledovat vaši polohu.
3. Po obnovení bude navigace pokračovat z aktuální nebo poslední známé polohy.

### Tip 5: Využijte Bike Radar Overlay

Pokud používáte Bike Radar Overlay:

1. Nainstalujte aplikaci **Bike Radar Overlay**.
2. Spusťte navigaci v BRP.
3. Navigační instrukce můžete sledovat i při zamčeném displeji.
4. Pokud Bike Radar Overlay zobrazuje také radarová upozornění, mají tato upozornění přednost před navigačními instrukcemi.

---

## Časté dotazy

### Proč se trasa vypočítává tak dlouho?

Offline výpočet trasy může trvat několik sekund. Doba výpočtu závisí na:

* délce trasy,
* složitosti oblasti,
* výkonu zařízení,
* dostupnosti GPS signálu,
* dostupnosti stažených mapových dat.

### Proč mi aplikace nenavrhuje trasu přes terén?

Záleží na zvoleném profilu:

* **Road** se terénu většinou vyhýbá.
* **Gravel** lehčí terén povoluje.
* **MTB** je určený i pro terénní úseky.

Zkontrolujte nastavení typu kola a stylu trasy.

### Proč se navigace nezobrazuje v Bike Radar Overlay?

Zkontrolujte:

1. zda je aplikace Bike Radar Overlay nainstalovaná,
2. zda jste v BRP opravdu spustili navigaci, ne pouze plánování,
3. zda má Bike Radar Overlay potřebná oprávnění, například oprávnění k oznámením.

### Proč se po pauze přepočítává trasa?

Aplikace může trasu automaticky přepočítat, pokud se vzdálíte od původní trasy.

Typicky k tomu dojde, když:

* opustíte trasu o více než přibližně **18 metrů**,
* aplikace vyhodnotí, že je vhodné navrhnout novou trasu z aktuální polohy.

### Proč se mi nezobrazuje trasa na mapě?

Zkontrolujte:

1. zda je GPS signál stabilní,
2. zda jsou načtená mapová data,
3. zda máte při prvním načtení dostupné připojení k internetu,
4. zda jsou pro danou oblast stažené potřebné segmenty BRouter.

---

## Licenční informace

Aplikace využívá:

* **BRouter** – GPL-3.0, offline trasování.
* **osmdroid** – Apache-2.0, zobrazení map.
* **OpenStreetMap** – ODbL, mapová data.

---

## Poděkování

Aplikace byla vytvořena s cílem podpořit cyklistickou komunitu a nabídnout nástroj pro plánování tras s důrazem na bezpečnost, komfort a flexibilitu.

Děkujeme za vaši podporu a za používání aplikace **Bike Route Planner**.
