# Uživatelský manuál - Bike Route Planner

## Představení produktu

**Bike Route Planner** (zkráceně BRP) je Android aplikace pro cyklisty, která vám pomáhá plánovat trasu a během jízdy poskytuje navigační instrukce. Aplikace je navržena tak, aby vám co nejlépe pomohla bezpečně a efektivně dosáhnout cíle.

### Pro koho je aplikace určená?

Aplikace je určena pro všechny typy cyklistů:
- **Silniční cyklisté** - hledají plynulé trasy po zpevněných povrzech
- **Gravel jízdelci** - chtějí kombinaci asfaltu a lehce nezpevněných cest
- **MTB cyklisté** - vyhledávají lesní trasy a traily
- **Komuniti** - denně jezdí do práce nebo po městě
- **Turisté** - hledají delší výlety s stabilním tempem
- **Průzkumníci** - chtějí objevovat nové úseky

### Klíčové výhody

- **Offline routing** - nemusíte mít připojení k internetu během jízdy
- **Vlastní plánování tras** - vytváříte trasu podle svých preferencí
- **Navigace do overlayu** - trasy z BRP se zobrazují v VARIA_RADAR aplikaci
- **Více typů kol** - profilování podle toho, co jste za kola
- **Více stylů tras** - rychlejší, kratší, bezpečnější nebo vyvážené
- **Okruhové trasování** - generování okruhů s nastavenou délkou

---

## Instalace a požadavky

### Požadavky zařízení

- **Android 8.0** (API 26) nebo novější
- **GPS senzor** - nutný pro polohové služby
- **Nějaké volné místo** pro mapová data

### Instalace BRouter

Aplikace BRP potřebuje k fungování nainstalovanou **BRouter** aplikaci. BRouter je aplikace pro offline trasování, kterou vytvořil Filip Němek.

#### Jak nainstalovat BRouter:

1. Otevřete BRP a při prvním spuštění se zobrazí dialog s možností stáhnout BRouter
2. Přejděte na Google Play Store a nainstalujte aplikaci **BRouter**
3. Po instalaci otevřete BRouter a stáhněte mapová data pro oblast, kde plánujete jet

### Instalace VARIA_RADAR (volitelné)

Pokud chcete mít navigaci zobrazenou v overlayu (například naHelmetu nebo auto), nainstalujte aplikaci **VARIA_RADAR**.

VARIA_RADAR je aplikace pro detekci vozidel zezadu a zobrazování navigačních instrukcí v režimu lock-screen / riding display.

---

## Úvod k plánování trasy

### Jak začít

1. Spusťte aplikaci **Bike Route Planner**
2. Na hlavní obrazovce zatlačte na tlačítko **Plánovač**
3. Nyní vyberte počátek a cíl trasy

### Výběr počátku

- **Použít GPS**: Zatlačte na ikonu polohy v pravém horním rohu - aplikace použije aktuální polohu
- **Výběr na mapě**: Zatlačte a držte na mapě místo, kde má počátek být

### Výběr cíle

- **Výběr na mapě**: Zatlačte a držte na mapě místo, kde má cíl být
- **Zrušení cíle**: Výběr bodu potvrďte zatlačením na ikonu X vpravo nahoře

### Přidání přesypných bodů (stopovers)

- Po výběru cíle zatlačte na **+** tlačítko
- Poté zatlačte na mapu a držte - tím přidáte přesypný bod
- Můžete přidat až 8 přesypných bodů

---

## Typy kol (Bike Type)

Aplikace podporuje 6 typů kol, každý s jiným profilováním trasy:

### 1. Road (Silniční kolo)

**Popis**: Silniční profil s důrazem na pevný povrch, plynulost a bezpečnost.

**Co preferuje**:
- Asfaltové a betonové povrchy
- Cyklostezky a cyklo trasové komunikace
- Rezidenční oblasti s nízkou rychlostí

**Co se vyhýbá**:
- Terénní cesty bez zpevnění
- Kvalitou špatné povrchy
- Technicky náročné úseky

**Pro koho**: Pro jezdce silničních kol, kteří chtějí plynulou a bezpečnou jízdu.

### 2. Gravel (Gravel kolo)

**Popis**: Kombinace asfaltu, štěrku a dobře sjízdných cest.

**Co preferuje**:
- Asfalt a zpevněné povrchy
- Jemný štěrk a hrubší terén
- Kvalitní lesní a polní cesty

**Co toleruje**:
- Středně kvalitní nezpevněné cesty
- Tracktype grade 1-3

**Co nepřipouští**:
- Špatně sjízdné povrchy
- Velmi technické úseky

**Pro koho**: Pro jezdce gravel kol, kteří chtějí kombinaci silnice a jemného terénu.

### 3. MTB (Off-road kolo)

**Popis**: Profil pro teren, traily a techničtější úseky.

**Co preferuje**:
- Terénní trasy a traily
- Lesní a parkové cesty
- Tracktype grade 1-3

**Co toleruje**:
- Nezpevněné povrchy
- Pěší stezky, pokud je jízda povolena
- Kvalitní pěší cesty

**Co vyhýbá**:
- Silnice pro motorová vozidla bez povolení pro kola
- Cesty s výraznými zákazy

**Pro koho**: Pro MTB jezdce, kteří chtějí jezdit v terénu.

### 4. Touring (Cestovní kolo)

**Popis**: Delší vyjížďky se stabilním tempem a spolehlivým povrchem.

**Co preferuje**:
- Spolehlivé povrchy
- Trasy se stabilní rychlostí
- Delší trasy s plynulým tempem

**Co toleruje**:
- Středně kvalitní nezpevněné cesty
- Cesty s nízkou rychlostí

**Pro koho**: Pro turistické jezdce, kteří chtějí delší trasy s pohodlným tempem.

### 5. Commute (Komutérské kolo)

**Popis**: Každodenní přeprava s důrazem na jistotu a čas.

**Co preferuje**:
- Pevné povrchy
- Přímé trasy
- Spolehlivé a známé cesty

**Co toleruje**:
- Cyklostezky
- Rezidenční oblasti

**Pro koho**: Pro každodenní jezdce do práce nebo školy.

### 6. Explore (Průzkumník)

**Popis**: Objevování nových úseků i za cenu menší předvídatelnosti.

**Co preferuje**:
- Nové a neznámé trasy
- Kombinaci povrchů
- Objevení nových míst

**Co toleruje**:
- Více rizikových úseků
- Méně předvídatelné trasy

**Pro koho**: Pro průzkumníky, kteří chtějí objevovat nové trasy.

---

## Stily tras (Route Style)

Každý styl tras definuje, jak moc se priorizuje bezpečí, rychlost nebo délka trasy:

### 1. Rychlejší (Faster)

**Popis**: Kratší nebo rychlejší profil. Může obsahovat frekventovanější silnice, kde je jízda na kole legální.

**Co dělá**:
- Prioritu na rychlost a délku trasy
- Může přijmout silnice s vyšším provozem
- Pokud je alternativa rychlejší, zvolí ji i přes provoz

**Upozornění**: Tento styl může vést po silnicích s větším provozem, kde je jízda na kolo legální. Cyklo-zakázané cesty zůstávají vyloučeny.

**Použití**: Když potřebujete co nejrychleji dosáhnout cíle a jste ochotni jet na menších silnicích.

### 2. Nejkratší (Shortest)

**Popis**: Preference nejkratší trasy. Může obsahovat méně komfortní nebo frekventovanější úseky, kde je jízda na kole legální.

**Co dělá**:
- Prioritu na minimální délku trasy
- Může vybrat kratší, ale méně pohodlné cesty
- Může vést po silnicích s vyšším provozem

**Upozornění**: Tento styl může vést po méně komfortních nebo provoznějších úsecích, kde je jízda na kole legální.

**Použití**: Když chcete co nejkratší trasu bez ohledu na komfort.

### 3. Turistický (Touring / Balanced)

**Popis**: Vyvážený profil pro běžné výjizde a delší trasy.

**Co dělá**:
- Kompromis mezi rychlostí, bezpečností a kvalitou
- Přijímá středně frekventované silnice
- Upřednostňuje kvalitní povrchy

**Použití**: Výchozí volba pro většinu uživatelů, kteří chtějí vyváženou trasu.

### 4. Bezpečnější (Safer)

**Popis**: Silnější preference pro klidné úseky, cyklostezky a nižší provoz.

**Co dělá**:
- Prioritu na bezpečné trasy
- Silně penalizuje hlavní silnice bez cyklopruhů
- Upřednostňuje cyklostezky, rezidenční oblasti a klidné cesty

**Použití**: Když preferujete klidnou jízdu a jste ochotni jet déle pro větší bezpečí.

---

## Popis hlavního rozhraní

### Hlavní obrazovka

```
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

### Menu (levý spodní roh)

Zatlačením na ikonu menu otevřete boční menu s dalšími funkcemi:
- **Plánovač mapy**: Zpět do plánování
- **Upravit UI**: Nastavení velikosti a vzhledu
- **Offline data**: Správa BRouter mapových dat
- **Nastavení aplikace**: Jazyk, povrch, provoz atd.
- **Podpora**: Ko-fi podpora pro vývoj
- **Ukončit**: Zavřít aplikaci

---

## Podrobný průvodce funkcemi

### Kapitola 1: Výběr počátku a cíle

#### Výběr GPS počátku

1. Zatlačte na tlačítko **Plánovač**
2. Počkejte na získání GPS polohy (ikonka vpravo nahoře)
3. Když se ikonka zelení, poloha je připravena

#### Výběr počátku z mapy

1. Zatlačte na tlačítko **Plánovač**
2. Zatlačte a držte na mapě místo, kde má počátek být
3. Po chvíli se zobrazí potvrzovací dialog
4. Zatlačte na potvrzení

#### Výběr cíle z mapy

1. Po výběru počátku se zobrazí tlačítko **Do**
2. Zatlačte a držte na mapě místo, kde má cíl být
3. Po chvíli se zobrazí potvrzovací dialog
4. Zatlačte na potvrzení

#### Úprava počátku/cíle

- Po výběru můžete počátek a cíl přesouvat na mapě
- Zatlačte a držte na bodě, poté přesuňte na nové místo
- Potvrďte zatlačením

#### Odstranění bodu

- Zatlačte na ikonu X vedle bodu
- Potvrďte odstranění

---

### Kapitola 2: Přesypné body

#### Přidání přesypného bodu

1. Po výběru cíle zatlačte na tlačítko **+** (přidat bod)
2. Zatlačte a držte na mapě místo, kde má být přesypný bod
3. Potvrďte výběr

#### Pořadí bodů

- Počátek je vždy první
- Cíl je vždy poslední
- Přesypné body jsou upřednostněny podle pořadí výběru

#### Úprava pořadí

- Aktuálně nelze změnit pořadí bodů
- Pokud chcete jiné pořadí, vytvořte novou trasu

#### Odstranění přesypného bodu

- Zatlačte na tlačítko **Vymazat**
- Vyberte bod, který chcete odstranit
- Potvrďte

---

### Kapitola 3: Generování okruhu

#### Jak generovat okruh

1. Zatlačte na tlačítko **Okruh**
2. Zvolte počáteční polohu (GPS nebo výběr na mapě)
3. Nastavte cílovou vzdálenost:
   - Minimálně: 5 km
   - Doporučeno: 30 km
   - Maximálně: 150 km
4. Zvolte počet smyček:
   - Minimálně: 3 body
   - Doporučeno: 6 bodů
   - Maximálně: 9 bodů
5. Zvolte preferovaný směr (N, NE, E, SE, S, SW, W, NW)
6. Zvolte směr jízdy (Po směru hodinových ručiček nebo proti)
7. Zatlačte na **Generovat smyčku**

#### Úprava okruhu

- Po generování můžete upravit body v mapě
- Zatlačte na **Upravit smyčku** pro úpravu
- Zatlačte na **Znovu generovat** pro nový výpočet

#### Zrušení okruhu

- Zatlačte na **Vymazat smyčku**
- Okruh bude odstraněn, ale mapa zůstane

---

### Kapitola 4: Spuštění navigace

#### Start navigace

1. Po dokončení plánování zatlačte na **Jít**
2. Aplikace začne zpracovávat trasu
3. Po dokončení zatlačte na **Jít** pro spuštění navigace

#### Během navigace

- Aplikace vás průběžně informuje o stavu
- Zobrazuje instrukce pro další odbočení
- Vzdálenost k odbočce se aktualizuje každou vteřinu

#### Pauza navigace

- Zatlačte na **Pauza** pro pozastavení
- Během pauzy se nezobrazují instrukce
- Pozice se stále sleduje

#### Pokračování po pauze

- Zatlačte na **Obnovit**
- Navigace se obnoví z poslední polohy

#### Přepočet trasy (Reroute)

- Pokud opustíte trasu, aplikace automaticky přepočítá
- Zobrazí novou trasu z aktuální pozice
- Toto trvá několik sekund

#### Zrušení navigace

- Zatlačte na **Zrušit**
- Potvrďte zrušení
- Mapa zůstane, navigace se ukončí

---

### Kapitola 5: Nastavení aplikace

#### Jazyk

- **Systém**: Použije jazyk zařízení
- **English**: Angličtina
- **Čeština**: Čeština

#### Jazyk navigace

- Stejné možnosti jako pro jazyk aplikace
- Nastaví jazyk pro instrukce a názvy

#### Výchozí přiblížení mapy

- Nastaví výchozí přiblížení mapy
- Od 3 (celá země) do 19 (ulice)
- Doporučeno: 14

#### Zobrazit cyklotrasování

- Zobrazí podtržené cyklotrasové stezky na mapě
- Umožňuje vidět označené cyklo trasové cesty
- Možnost změnit průhlednost (25-75%)

#### Zobrazit pěší trasy

- Zobrazí pěší trasy na mapě
- Umožňuje vidět označené turistické trasy
- Možnost změnit průhlednost (25-75%)

#### Nastavení zobrazení navigace

- **Minimální přiblížení**: Vzdálené odbočky
- **Maximální přiblížení**: Blízké odbočky

#### Vlastní styl trasy

- **Šířka čáry**: Od 2 do 18
- **Barva čáry**: Výběr barev podle palety

#### Úprava rozhraní

- **Velikost tlačítek**: Od 85% do 145%
- **Velikost řídicích prvků**: Vliv na velikost prvků na mapě
- **Velikost ikony jezdce**: Od 20 dp do 44 dp
- **Velikost navigačního banneru**: Nastavení velikosti textu a šipky

---

### Kapitola 6: Offline data (BRouter)

#### Jak stáhnout mapová data

1. Zatlačte na **Offline data** v menu
2. Zobrazí se informace o BRouter
3. Zatlačte na **Otevřít správce stahování**
4. V BRouter aplikaci vyberte oblast
5. Stáhněte segmenty pro oblast

#### Zkontrolování dostupnosti

- Aplikace automaticky kontroluje, zda jsou segmenty staženy
- Pokud ne, zobrazí varování
- Doporučené segmenty jsou zvýrazněny

#### Recalculace doporučených segmentů

- Po změně počátku nebo cíle se segmenty přepočítají
- Zatlačte na **Obnovit** pro znovu výpočet

---

### Kapitola 7: VARIA_RADAR integrace

#### Jak nastavit integraci

1. Nejprve nainstalujte VARIA_RADAR aplikaci
2. Spusťte VARIA_RADAR a dokončete nastavení
3. V BRP spusťte navigaci
4. Navigační data se budou odesílat do VARIA_RADAR

#### Co se přenáší do VARIA_RADAR

- **Vzdálenost k odbočce**: V metrech
- **Typ odbočení**: Zpráva typu "Doprava", "Doleva", atd.
- **Jméno ulice**: Název ulice, kudy jezdíte
- **Čas do cíle**: Estimated Time of Arrival
- **Stav navigace**: Aktivní, Doba jetí, Ztráta GPS

#### Zobrazování v VARIA_RADAR

- Aplikace zobrazi navigaci na lock-screen (po zamčení displeje)
- Pokud je vzdálenost menší než 200m, displej se rozsvítí
- Radar alert má vyšší prioritu než navigace

---

### Kapitola 8: Logické vysvětlení tras

#### Proč aplikace zvolila určitou trasu?

Aplikace vypíše shrnutí trasy:
- **Délka**: Celková vzdálenost
- **Trvání**: Odhadovaný čas
- **Povrch**: Procento různých povrchů (asfalt, štěrk, atd.)
- **Provoz**: Procento různých úrovní provozu
- **Rizika**: Počet problémových úseků (U-turny, ostrá odbočení)

#### Problémové úseky

Aplikace označuje problémové úseky oranžově:
- **Možný zpětný chod (U-turn)**
- **Ostré obrácení**
- **Vrácení po stejné cestě**

#### Závazné filtry

Aplikace vyloučí:
- `highway=motorway` (dálnice)
- `bicycle=no` (zákaz jízdy na kolo)
- `access=private` bez výjimky
- `construction` (stavby)

---

### Kapitola 9: Variabilní nastavení

#### Proč existuje více profilů?

Každý typ kola a styl tras má odlišný profilovací kód, protože:
- **Silniční kolo** potřebuje plynulý povrch
- **Gravel kolo** může zvládnout jemný terén
- **MTB kolo** může jít i po trasech

#### Jak funguje profilování?

Profilování funguje na základě:
1. **Výběru typu kola** - určuje, co je fyzicky vhodné
2. **Výběru stylu tras** - určuje, jak se kompromituje mezi bezpečím a rychlostí
3. **Uživatelských preferencí** - vyloučení schodů, zákazů, atd.

#### Příklady profilů

**Road + Safer**:
- Zvolí cyklostezky a rezidenční oblasti
- Vyhnou se hlavním silnicím
- Může být delší, ale bezpečnější

**Gravel + Fast**:
- Povolí jemný terén
- Priorita na rychlost
- Může zvolit rychlejší cestu přes terén

**MTB + Safe**:
- Povolí terény
- Zamezí nebezpečným úsekům
- Upřednostní bezpečné trasy

---

### Kapitola 10: Typické scénáře použití

#### Scénář 1: Denní cesta do práce

1. Spusťte BRP
2. Zvolte **Komutérské kolo** + **Rychlejší**
3. Zvolte počátek (domů) a cíl (práce)
4. Spusťte navigaci

#### Scénář 2: Výlet na víkend

1. Spusťte BRP
2. Zvolte **Gravel** nebo **Touring**
3. Zvolte **Bezpečnější** nebo **Turistický**
4. Zvolte cíl a výběr trasy
5. Spusťte navigaci

#### Scénář 3: MTB výlet

1. Spusťte BRP
2. Zvolte **MTB**
3. Zvolte **Bezpečnější** nebo **Turistický**
4. Zvolte cíl v terénu
5. Spusťte navigaci

#### Scénář 4: Okruhová jízda

1. Spusťte BRP
2. Zvolte **Gravel** nebo **MTB**
3. Zatlačte na **Okruh**
4. Nastavte délku (30-50 km)
5. Generujte okruh a upravte body
6. Spusťte navigaci

---

### Kapitola 11: Všeobecné tipy

#### Tip 1: Zkontrolujte pokrytí mapami

Před plánováním dlouhé trasy zkontrolujte, zda jsou segmenty staženy:
1. Zatlačte na **Offline data**
2. Zkontrolujte, zda jsou segmenty pro danou oblast staženy
3. Pokud ne, stáhněte je v BRouter

#### Tip 2: Použijte GPS místo výběru

Pro rychlé výběry:
1. Zatlačte na ikonu GPS
2. Počkejte na zelenou ikonu
3. Potvrďte výběr

#### Tip 3: Zkontrolujte varování

Před zahájením jízdy:
1. Zkontrolujte oranžové výstrahy na mapě
2. Přečtěte si vysvětlení problémových úseků
3. Zvažte, zda trasa odpovídá vašim schopnostem

#### Tip 4: Pauza je bezpečná

Pokud potřebujete pauzu:
1. Zatlačte na **Pauza**
2. Aplikace stále sleduje polohu
3. Po obnovení pokračuje z poslední polohy

#### Tip 5: Využijte VARIA_RADAR

Pokud máte VARIA_RADAR:
1. Nainstalujte VARIA_RADAR aplikaci
2. Zapojte navigaci do VARIA_RADAR
3. Můžete sledovat navigaci i při zamčeném displeji
4. V případě rizika (auto zezadu) se rozsvítí

---

## Časté dotazy (FAQ)

### Q: Proč se mi vypočítává trasa tak dlouho?

**A**:Offline trasování může trvat několik sekund, záleží na:
- Délce trasy
- Složitosti trasy
- Výkonu zařízení
- Dostupnosti GPS signálu

### Q: Proč mi aplikace nedoporučuje trasy přes terén?

**A**: To záleží na vybraném profilu:
- **Road** vyloučí terény
- **Gravel** a **MTB** je povolí
- Zkontrolujte nastavení typu kola

### Q: Proč se mi navigace v VARIA_RADAR nezobrazuje?

**A**: Zkontrolujte:
1. Zda je VARIA_RADAR nainstalována
2. Zda jste v BRP spustili navigaci (nejen plánování)
3. Zda má VARIA_RADAR povolení k notifikacím

### Q: Proč se mi po pauze přepočítává trasa?

**A**: Aplikace automaticky přepočítá trasu, když:
- Opustíte trasu více než 18 metrů
- To zajišťuje, že jste stále na správné trase

### Q: Proč se mi nezobrazují trasy na mapě?

**A**: Zkontrolujte:
1. Zda je GPS signál stabilní
2. Zda jsou mapy načteny (čeká na GPS)
3. Zda máte připojení k internetu (při prvním načtení)

---

## Podpora a feedback

### Kde najít pomoc?

- **GitHub issues**: https://github.com/JoshuaxCZ/BIKE_ROUTE_PLANNER/issues
- **Ko-fi podpora**: V aplikaci v menu (vyžaduje dev mode)

### Jak poskytnout feedback?

1. Otevřete GitHub issues
2. Popište problém nebo návrh
3. Přidejte informace o zařízení a Android verzi
4. Přiložte případné screenshoty

---

## Verze a změny

### Verze 0.9.13

- Stabilita a vylepšení
- Vylepšené trasování
- Vylepšená navigace

---

## Licenční informace

Aplikace využívá:
- **BRouter** (GPL-3.0) - offline trasování
- **osmdroid** (Apache-2.0) - zobrazení map
- **OpenStreetMap** (ODbL) - mapa

---

## Poděkování

Aplikace byla vytvořena s cílem podpořit cyklistickou komunitu a poskytnout nástroj pro plánování tras s důrazem na bezpečnost a komfort.

Děkujeme za vaši podporu a používání Bike Route Planner!