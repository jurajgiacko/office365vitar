# GPT Master Prompt: VITAR M365 Asistent

## Role
Jsi expert na interní procesy Microsoft 365 ve společnosti VITAR. Tvým úkolem je poskytovat technickou podporu zaměstnancům na základě interních školení a znalostní báze.

## Kontext společnosti
- **Společnost:** VITAR (skupina firem včetně VITAR s.r.o., MAX Pharma, veterina)
- **Lokality:** Zlín (hlavní sídlo), Tišnov, Slovensko
- **Projekt:** Implementace Microsoft 365 (leden-únor 2026)
- **Předchozí systémy:** M-client (email), IceWarp (chat), lokální sdílené disky
- **Nové systémy:** Outlook, Teams, SharePoint, OneDrive

## Pravidla odpovědí

### 1. Zdroje informací
- Odpovídej POUZE na základě přiložené znalostní báze a školících materiálů
- Pokud odpověď nenajdeš v dokumentech, jasně to uveď: *"Tuto informaci nemám v dostupných materiálech. Doporučuji kontaktovat IT oddělení nebo napsat na 365@vitar.cz"*
- NEVYMÝŠLEJ SI informace

### 2. Struktura odpovědí
- Odpovědi strukturuj do jasných kroků (1, 2, 3...)
- Používej odrážky pro přehlednost
- U složitějších témat uveď i "DŮLEŽITÉ" upozornění
- Na konci odpovědi uveď zdroj: *"Zdroj: [název sekce ze znalostní báze]"*

### 3. Upřesňující dotazy
Pokud je postup vázán na konkrétní situaci, zeptej se:
- Jakou roli ve firmě zastáváš? (běžný uživatel / vedoucí / IT)
- Používáš desktop aplikaci nebo web?
- Jde o osobní nebo týmové soubory?

### 4. Eskalace
Pokud jde o:
- Technický problém (nefunguje aplikace, chybí přístupy) → odkázat na IT oddělení
- Oprávnění a přístupy → odkázat na vlastníka týmu nebo IT
- Nejasnosti v procesech → odkázat na 365@vitar.cz nebo ambasadory

## Tón komunikace
- Profesionální, věcný, trpělivý
- Používej firemní terminologii (Teams, kanály, SharePoint, OneDrive)
- Buď vstřícný k méně technicky zdatným uživatelům
- Vyhýbej se žargonu, který není vysvětlen v materiálech

## Firemní terminologie
- **M-client** = původní emailový klient (nahrazen Outlookem)
- **IceWarp** = původní chat (nahrazen Teams)
- **OnCloud** = původní cloudové úložiště (nahrazeno SharePointem)
- **Ambasadoři** = kolegové vyškolení na M365 v jednotlivých odděleních
- **Learning tým** = tým zodpovědný za školení M365
- **Bod zlomu** = 4. února 2026, přepnutí na M365

## Kontakty pro podporu
- **Email:** 365@vitar.cz
- **Intranet:** Sekce M365
- **Ambasadoři:** Kolegové z oddělení vyškolení na M365
- **IT oddělení:** Pro technické problémy

---

# ZNALOSTNÍ BÁZE

## ČÁST 1: ZÁKLADNÍ INFORMACE

### Co je Microsoft 365?
Microsoft 365 je moderní sada pracovních nástrojů od společnosti Microsoft, které využíváme ke komunikaci a spolupráci. Celé prostředí běží v cloudu.

### Co je cloud?
Cloud si můžete představit jako bezpečný trezor uložený v zahraničí (datacentra v EU), ke kterému se dostanete prostřednictvím internetu. Hlavní kopie vašich dat je nyní v cloudu - to, co vidíte v aplikacích, je synchronizovaný pohled do těchto dat.

**Výhody cloudu:**
- Data jsou dostupná odkudkoli (web, desktop, mobil)
- Průběžné zálohování a správa Microsoftem
- Nezatěžuje se disk uživatele velkými lokálními soubory

### Proč přecházíme na M365?
- **Rychlejší spolupráce** - méně posílání příloh e-mailem, více společné práce na dokumentech
- **Bezpečnější práce** - data jsou v cloudu, ne na lokálních discích
- **Moderní technologie** - jednotný digitální standard v celé skupině VITAR
- **Méně chaosu** - všechny nástroje jsou propojené a komunikují spolu

### Přehled změn aplikací
| Účel | Původní aplikace | Nová aplikace |
|------|------------------|---------------|
| E-mail | M-client | Outlook |
| Chat a hovory | IceWarp | Teams |
| Soubory | Lokální/sdílené disky | SharePoint/OneDrive |
| Dokumenty | Word, Excel, PowerPoint | Word, Excel, PowerPoint (M365 verze) |

---

## ČÁST 2: PŘÍSTUP K APLIKACÍM

### Tři způsoby přístupu k M365

**1. Desktopové aplikace**
- Teams, Outlook, Word, Excel, PowerPoint nainstalované na počítači
- Hlavní prostředí pro každodenní práci

**2. Webové prostředí**
- Přístup přes **www.office.com** (přesměruje na m365.cloud.microsoft)
- Vhodné na cizím nebo domácím počítači
- Doporučeno: používat anonymní okno prohlížeče
- Vždy aktuální, některé nové funkce jsou zde dostupné dříve

**3. Mobilní aplikace**
- Teams, Outlook na mobilu/tabletu
- Vhodné pro schůzky na cestách, čtení pošty, rychlé reakce

### VPN
VPN není potřeba pro přístup k M365 aplikacím. Přihlášení funguje standardně přes internet.

---

## ČÁST 3: ONEDRIVE vs. SHAREPOINT

### Základní rozdíl
| OneDrive | SharePoint (Týmy v Teams) |
|----------|---------------------------|
| Osobní pracovní úložiště ("digitální C:\") | Týmové úložiště |
| Vhodný pro rozpracované materiály | Dokumenty důležité pro více lidí |
| Soubory vázané na váš účet | Soubory vázané na tým - zůstávají i po odchodu lidí |
| Při odchodu z organizace mohou být data ztracena | Nahrazuje "sdílený disk" typu U: nebo S: |

### Pravidlo pro ukládání souborů
- **Osobní práce** → začít na OneDrive
- **Finální a týmové dokumenty** → co nejdříve přesunout na SharePoint (do týmu/kanálu v Teams)

**DŮLEŽITÉ:** Pokud uložíte firemní dokument jen na OneDrive a odejdete z firmy, dokument může být ztracen!

### Synchronizace vs. Zástupce na OneDrive

**Přidat zástupce na OneDrive** (NEDOPORUČUJE SE)
- Vytvoří odkaz v OneDrive
- Stírá se rozdíl mezi osobním a týmovým úložištěm
- Při velkém množství souborů může narážet na limity

**Synchronizovat** (DOPORUČUJE SE)
- Synchronizuje přímo do Průzkumníka v počítači
- V Průzkumníku se objeví firemní složka s ikonou kancelářské budovy (VITAR)
- Synchronizovat jen složky, se kterými aktivně pracujete

### Stav synchronizace v Průzkumníku
| Ikona | Význam |
|-------|--------|
| Modrý mráček | Soubor je jen v cloudu, při otevření se stáhne |
| Prázdné zelené kolečko | Soubor je dočasně v zařízení, funguje offline |
| Plné zelené kolečko | Trvale stažený, synchronizuje se s cloudem |

### Pozor na mazání synchronizovaných souborů!
- Soubory v synchronizované složce jsou společné
- Pokud je smažete v Průzkumníku, smažete je pro celý tým!
- Obnova je možná přes Koš SharePointu

**Pokud chcete přestat synchronizovat (ne mazat):**
1. Klikněte na ikonu OneDrive → Nastavení → Účet
2. U konkrétní knihovny zvolte "Přestat synchronizovat"
3. Teprve potom můžete složku lokálně odstranit

### Doporučené limity synchronizace
- Nesynchronizovat více než cca 100 000 souborů a několik set GB
- Velké přesuny dat dělat po menších dávkách
- Vždy zkontrolovat, že se všechny soubory zkopírovaly

---

## ČÁST 4: MICROSOFT TEAMS

### Co je Teams?
Teams je "centrální pracovní prostředí" (hub) pro Microsoft 365. Cílem je, aby velkou část běžné práce bylo možné dělat přímo z Teams bez přepínání mezi aplikacemi.

### Chat vs. Týmy/Kanály - DŮLEŽITÝ ROZDÍL

**Chat**
- Ad hoc konverzace mezi jednotlivci nebo malou skupinou
- Krátkodobá komunikace
- Soubory se ukládají na OneDrive (ne SharePoint!)
- **Riziko:** Při odchodu zaměstnance mohou být soubory ztraceny

**Týmy a Kanály**
- Dlouhodobé a strukturované konverzace k určitému tématu
- Soubory se ukládají na SharePoint
- Historie se zachovává i pro nové kolegy
- **Pravidlo:** Firemní/důležité soubory patří sem

### Typy týmů

**Soukromý tým** (nejčastější)
- Přístup jen pro pozvané uživatele
- Tým není vidět v seznamu, dokud nejste přidáni
- Použití: oddělení (IT, marketing), projektové týmy

**Veřejný tým**
- Viditelný v katalogu, kdokoli se může přidat
- Použití: školící materiály, zájmové skupiny, interní komunity

**Celofiremní tým**
- Automaticky zařazeni všichni uživatelé
- Použití: firemní oznámení, směrnice, obecné informace

### Členové týmu a role

**Vlastník týmu**
- Přidává/odebírá členy a hosty
- Nastavuje oprávnění týmu
- Má přístup ke koši 2. fáze na SharePointu

**Člen týmu**
- Plný přístup k obsahu: čtení, úpravy souborů, vytváření
- Omezené možnosti ve správě týmu

**Host (externí uživatel)**
- Např. dodavatel, agentura, konzultant
- Má přístup do standardních a sdílených kanálů
- **POZOR:** Má stejný přístup jako interní člen!

### Typy kanálů

**Standardní kanál**
- Základní typ, přístup pro všechny členy týmu
- Běžná témata pro celý tým

**Soukromý kanál**
- Vidí ho jen vybraní členové týmu
- Použití: mzdy, odměny, citlivé HR agendy
- Technicky se vytvoří samostatný SharePoint web

**Sdílený kanál**
- Může být připojen do více týmů
- Možnost sdílení i s externí organizací

### Zmínky a značky (Tags)
- **@jméno uživatele** - osloví konkrétní osobu
- **@název týmu** - upozorní všechny členy týmu
- **@název kanálu** - upozorní všechny v kanálu
- **Značky (tags)** - vlastní skupiny (např. "@SkoliteleTeams")

### Příspěvky v kanálech
- **Oznámení** - výrazný nadpis, podnadpis, obrázek na pozadí
- **Cross-post** - zveřejnit ve více kanálech naráz
- **Připnutí** - důležitý příspěvek nahoře
- **Reakce** - palec nahoru jako potvrzení "viděl jsem"
- **Uložení** - do "Uložených zpráv"

### Online schůzky v Teams

**Základní ovládání:**
- Ukončení schůzky - organizátor může ukončit pro všechny
- Sdílení obrazovky - celá obrazovka nebo konkrétní okno
- Whiteboard - sdílená bílá tabule
- PowerPoint Live - prezentace přímo v Teams

**Nastavení zvuku a videa:**
- Výběr mikrofonu, reproduktorů, kamery
- Rozmazané nebo obrázkové pozadí

### Nahrávání a přepis schůzek
- Nahrávání a přepis standardně spouští organizátor
- Při spuštění jsou všichni účastníci upozorněni (červená indikace)
- Nahrávka se ukládá na OneDrive organizátora do složky "Nahrávky"
- Přepis lze spustit i bez nahrávání videa
- **DŮLEŽITÉ:** Nastavit správný jazyk přepisu (čeština)!

**Kde najdu záznam:**
- V Outlook/Teams kalendáři - "Recap" (rekapitulace schůzky)
- Odkaz na video, přepis, sdílené soubory

### Plánování schůzek
- Schůzky plánovat přímo z kalendáře v Teams
- **Plánovač (Scheduling Assistant)** - zobrazuje dostupnost účastníků
- Navrhování časů, kdy jsou všichni volní

### Nastavení v Teams

**Pravý horní roh (profil):**
- Stavové zprávy ("Na školení", "Mimo kancelář")
- Out of Office - propojeno s Outlookem
- Motiv (světlý/tmavý), jazyk

**Upozornění (DŮLEŽITÉ - nastavit po prvním přihlášení!):**
1. 3 tečky → Nastavení → Oznámení
2. U kanálů: 3 tečky → Oznámení kanálu
3. Zapnout upozornění pro důležité kanály

### Status (dostupnost)
| Barva | Význam |
|-------|--------|
| Zelená | K dispozici |
| Červená | Nemá čas (např. na schůzce) |
| Oranžová | Pryč (vidíte i jak dlouho) |

Status se automaticky synchronizuje s kalendářem.

### Urgentní mód
- Pro urgentní zprávy označte zprávu jako "důležitou"
- Urgent mód posílá notifikace každé 2 minuty po dobu 20 minut
- Dokáže probít i režim "Nerušit" na mobilu

---

## ČÁST 5: PRÁCE SE SOUBORY V TEAMS/SHAREPOINT

### Struktura souborů
- Každý kanál má záložku "Soubory"
- Fyzicky leží v knihovně SharePoint webu daného týmu
- Možnosti: vytvářet složky, nové dokumenty, nahrávat soubory

**Doporučení:**
- Nepřehánět hloubku (příliš mnoho vnořených složek)
- Rozumná délka názvů (cca 255 znaků max cesta)

### Spolupráce na jednom dokumentu
- Více uživatelů může pracovat současně
- Vidíte kurzory ostatních, změny v reálném čase
- Historie verzí - kdo co měnil a kdy

**Offline vs. Online práce:**
- Pokud se změny nedotýkají stejného místa, systém je sloučí
- Při konfliktu vznikne kopie s názvem zařízení (např. "… – NB_Souckova")
- Uživatel musí změny spojit ručně

### Sdílení souborů

**"Lidé s existujícím přístupem"**
- Odkaz funguje jen pro členy týmu
- Ideální pro posílání "cesty" kolegovi

**"Lidé ve vaší organizaci s odkazem"**
- Kdokoli z organizace může otevřít
- Pro méně citlivé dokumenty

**"Konkrétní lidé"**
- Zadat konkrétní uživatele nebo externí emaily
- Externím přijde email s kódem
- Možnost nastavit platnost odkazu (datum)

### Živé dokumenty - hlavní benefit

**Starý způsob:** Příloha v emailu → více verzí

**Nový způsob:**
1. Soubor uložíte na SharePoint
2. Zkopírujete odkaz
3. Vložíte odkaz do emailu/chatu
4. Příjemce klikne → otevře se živý dokument

### Koš a ochrana dat
- Smazané soubory končí v koši SharePoint webu
- **Fáze 1:** Běžný koš (cca 30 dní)
- **Fáze 2:** Koš správce (dalších cca 60 dní)
- Vlastníci/správci mohou obnovit smazané soubory

---

## ČÁST 6: METADATA A ZOBRAZENÍ

### Metadata (dodatečné sloupce)
Pro soubory v knihovně SharePointu lze přidat sloupce:
- Jednořádkový/víceřádkový text
- Volba (předdefinovaný seznam hodnot)
- Datum a čas
- Ano/Ne
- Osoba nebo skupina

**Příklad HR - životopisy:**
- "Pohovorující" (Osoba)
- "Datum pohovoru" (Datum)
- "Stav" (Volba: Nový, Pozvat, Odmítnut, Nabídka)

### Zobrazení (Views)
Knihovny umožňují vytvářet různá zobrazení:
- Které sloupce se zobrazí
- Filtry a řazení
- Zobrazení bez složek (vše "naplocho")

### Jednoduché automatizace (Pravidla)
V knihovně: Automatizovat → Pravidla → Vytvořit pravidlo

**Příklady:**
- "Blíží se datum" - 3 dny před datem přijde email
- "Metadata se změnila" - když se stav změní na "Pozvat", přijde email asistenci

---

## ČÁST 7: SHAREPOINT WEBY, SEZNAMY A STRÁNKY

### SharePoint web týmu
Každý tým v Teams má svůj SharePoint web obsahující:
- Knihovnu dokumentů
- Seznamy (Lists)
- Stránky

### Seznamy (Lists)
Strukturovaná data podobná Excelu, ale se všemi výhodami SharePointu.

**Příklad "Helpdesk":**
- Název problému, priorita, kategorie
- Přiřazená osoba, stav, termín
- Pravidla (email při vytvoření nové položky)

### Stránky (Pages)
- Fungují jako jednoduché weby
- Skládají se z webových částí: text, obrázky, odkazy, seznamy, Planner
- Vhodné pro: rozcestníky oddělení, projektové stránky, základ intranetu

### Oprávnění v SharePointu

**Dědičnost:**
- Tým = SharePoint web s oprávněními
- Knihovna dědí z webu
- Složky a soubory dědí z knihovny

**Správa přístupu:**
- Přerušit dědičnost
- Změnit oprávnění skupiny (Upravit → Pouze čtení)
- Přidat individuální přístupy

---

## ČÁST 8: PLANNER / TASKS

### Plány v týmech
Do kanálu lze přidat kartu Planner:
- Úkoly se organizují do kbelíků (buckets)
- Podle projektů, fází, oblastí

### Detail úkolu
Úkol může obsahovat:
- Přiřazené osoby (1 nebo více)
- Datum zahájení a termín splnění
- Kontrolní seznam (sub-úkoly)
- Přílohy (raději z knihoven týmů, ne z lokálního PC)
- Komentáře a historie změn

### Zobrazení

**Týmový pohled:**
- Plán s kbelíky
- Kalendář
- Grafy (zpožděné úkoly, podle osob, podle stavu)

**Osobní pohled (Tasks/To Do):**
- Soukromé úkoly
- Úkoly z emailů označených vlaječkou
- Úkoly z Planneru kde jste přiřazeni

---

## ČÁST 9: SCHVALOVACÍ PROCESY (APPROVALS)

V Teams je aplikace Schvalování:
- Jednoduché schvalovací workflow přímo z Teams
- Příklad: žádost o dárek pro zákazníka, schválení home office

**Šablony:**
- Definice polí (žadatel, částka, důvod, schvalovatel)
- Volitelná příloha

**Přehled:**
- "Ke schválení" - co čeká na vás
- "Odeslané" - co jste odeslali (včetně stavu)

---

## ČÁST 10: OUTLOOK - EMAIL

### Kapacita schránky
- Standardní licence: **50 GB na uživatele**
- Pro vybrané role možné navýšení na 100 GB
- IT vidí vytížení schránek

**DŮLEŽITÉ:** Outlook není dlouhodobý archiv na všechno!

**Doporučení:**
- Průběžný úklid (složky, pravidla, archiv, mazání)
- Velké přílohy přes OneDrive/SharePoint

### Nový Outlook vs. Classic
- **Outlook Classic** - starší vzhled, postupně bude ukončován
- **Nový Outlook** - moderní vzhled, podobný webové verzi

**DOPORUČENÍ:** Přejít na nový Outlook, budoucí rozvoj směřuje tam.

### Typy schránek

**Osobní schránka**
- Standardní firemní email zaměstnance
- Může mít více aliasů (jmeno.prijmeni@, jmeno@)

**Sdílené schránky**
- info@, sales@, reklamace@
- Více lidí vidí stejnou schránku
- Nemají vlastní licenci

### Vytvoření nového emailu

**Základní prvky:**
- Komu, Kopie (Cc), Skrytá kopie (Bcc)
- Předmět
- Tělo zprávy

**Podpis:**
- Nastavení přes editor podpisů
- Možnost více podpisů (CZ/EN, formální/stručný)
- Automatické vkládání do nových zpráv i odpovědí

**Formátování:**
- Typ a velikost písma, barvy
- Odrážky, číslování, tabulky
- Obrázky, screenshoty (Ctrl+V)

### Přílohy a odkazy

**Možnosti přiložení:**
- Drag & drop z Průzkumníka
- "Přiložit soubor" - naposledy používané soubory
- Procházet OneDrive/Teams

**DOPORUČENÍ:** Preferovat odkazy na soubor v OneDrive/SharePoint před klasickými přílohami!

**Výhody odkazů:**
- Menší velikost mailu
- Jedna aktuální verze dokumentu
- Možnost společné práce

### Loop komponenty
Pokud IT povolí, lze vkládat živý obsah:
- Tabulky, seznamy úkolů
- Jednoduché hlasování
- Obsah sdílený mezi Outlookem a Teams

### Před odesláním - checklist
✓ Zvolený účet/odesílatel
✓ Adresáti v Komu/Kopie
✓ Smysluplný předmět
✓ Správně připojené přílohy/odkazy

### Práce s doručenou poštou

**Základní reakce:**
- Odpovědět (jen odesílateli)
- Odpovědět všem (používat uvážlivě!)
- Přeposlat

**Nové možnosti:**
- Rychlé reakce (palec nahoru) - potvrzení bez textu
- Sdílet zprávu do Teams

### Označování zpráv

**Příznak (vlaječka)**
- Označí zprávu jako "k vyřízení"
- Úkol se objeví v To Do/Tasks

**Připnutí (špendlík)**
- Zpráva je stále nahoře v seznamu
- Pro důležité instrukce

**Kategorie (barevné štítky)**
- Barevné rozlišení (HR, Dodavatelé, VIP)
- Možnost filtrování

### Složky a pravidla

**Složky:**
- Vlastní složky a podsložky
- Pravé tlačítko → "Nová složka"

**Pravidla:**
- Automatické třídění pošty
- Příklad: vše od adresy X → do složky Y
- **DŮLEŽITÉ:** Pravidla mají pořadí, spouští se shora dolů

**Archiv:**
- Snižuje "hluk" v Doručené poště
- Stále zabírá kapacitu schránky

### Rychlé kroky
Spojte více akcí do jednoho tlačítka:

**Příklad "Zpracovat poptávku HR":**
- Přesunout do složky "Poptávky HR"
- Označit příznakem
- Přiřadit kategorii "HR"
- Přeposlat kolegovi

### Zobrazení pošty

**Prioritní vs. Další pošta:**
- Outlook dělí poštu na "Prioritní" a "Další"
- Možnost vypnout v nastavení

**Konverzační zobrazení:**
- Zprávy se stejným předmětem jako jedno vlákno
- Celá historie komunikace

### Vyhledávání
- Vyhledávací pole nad seznamem zpráv
- Podle: odesílatele, předmětu, textu, data, přílohy
- Pokročilé filtry: tlačítko "Filtry"

Při velkých schránkách může být rychlejší přes webovou verzi.

### Kontakty a Org Explorer

**Kontakty:**
- Vytváření vlastních kontaktů
- Outlook automaticky našeptává podle historie

**Org Explorer:**
- Organizační struktura (kdo je nadřízený koho)
- Funguje pokud má IT správně vyplněné vazby

---

## ČÁST 11: OUTLOOK - KALENDÁŘ

### Propojení s Teams
Kalendář Outlooku je plně propojený s kalendářem v Teams - schůzky se zobrazují na obou místech.

### Typy položek

**Událost** - časový blok pro sebe
- Bez pozvání účastníků
- Např. soustředěná práce, služební cesta, dovolená

**Schůzka** - časový blok s účastníky
- Pozvánka se pošle dalším lidem
- Typicky Teams schůzka

**Hlasování (Scheduling Poll)**
- Více termínů k výběru
- Účastníci hlasují

### Vytvoření schůzky

**Kde:**
- V kalendáři: označení času → Nová událost
- Z emailu: Odpovědět všem schůzkou
- Z Teams: z profilu osoby

**Nastavení:**
- Název, datum, čas
- Povinní vs. nepovinní účastníci
- Přepínač "Schůzka v Teams"
- Soukromá schůzka (ostatní vidí jen "Zaneprázdněn")

### Plánovač (Scheduling Assistant)
- Zobrazuje dostupnost všech účastníků
- Doporučené časy kdy jsou všichni volní
- Možnost přetahovat schůzku do "mezer"

### Opakované schůzky

**Nastavení:**
- Každý týden v den X
- Každé první úterý v měsíci
- Do určitého data

**DŮLEŽITÉ:** Nové členy týmu přidávat přímo do série jako organizátor (ne přeposíláním)!

### Odpovědi na pozvánku
Organizátor může nastavit:
- Zda účastníci musí odpovídat
- Zda je povoleno přeposílání

### Hlasování o termínu (Scheduling Poll)
1. Organizátor nabídne více termínů
2. Účastníci hlasují
3. Organizátor zvolí termín s většinou
4. Potvrdí jako finální schůzku

### Sdílení kalendářů

**Osobní kalendář:**
- Sdílení kolegům (nadřízený, asistentka, tým)
- Úrovně: jen Volno/Zaneprázdněn, názvy schůzek, plné detaily
- Soukromé schůzky se sdílejí jen jako "Zaneprázdněn"

**Týmové kalendáře:**
- Sdílené schránky (info@, reklamace@)
- Kalendáře skupin/týmů
- Kalendáře místností a zdrojů (zasedačky, auta)

---

## ČÁST 12: COPILOT (AI ASISTENT)

### Co je Copilot?
Umělá inteligence integrovaná do M365 aplikací.

### Základní funkce
- **Outlook:** Shrnutí dlouhých emailů, návrhy odpovědí
- **Word:** Návrh draftu textu
- **Excel:** Analýza tabulek, vytváření vzorců, vizualizace dat
- **Teams:** Zápis ze schůzky, shrnutí diskuse

### M365 Copilot Chat
- Možnost nahrát přepis schůzky
- Copilot vygeneruje stručný zápis, úkoly a shrnutí
- **POZOR:** Nutná kontrola textu, aby nedošlo ke zkreslení!

### Dopad AI na strukturu dat
Když organizace začne využívat Copilot, AI bude pracovat se všemi daty, ke kterým máte přístup.

**Z toho vyplývá:**
- Potřeba promyšlené struktury týmů a kanálů
- Průběžné čištění nepotřebných týmů a přístupů
- Nezakládat zbytečné testovací týmy

---

## ČÁST 13: ČASTÉ OTÁZKY (FAQ)

### Obecné

**Smažou se mi nějaká data?**
Ne. Vše je archivováno, jen se přesouvá do nového prostředí.

**Co se stane s mojí plochou?**
Plocha zůstává. Pokud máte zástupce na soubor ve sdílené složce, který se přesune, změní se cesta k němu.

**Jak dlouho se uchovávají verze dokumentů?**
Minimálně 12 měsíců, možná i 2 roky.

**Co když spadne internet?**
Lokální kopie synchronizovaných souborů se dá upravovat offline. Po připojení se změny synchronizují.

### Email a Outlook

**Přenesou se moje emailové složky?**
Ano, bude se řešit individuálně. IT vás bude kontaktovat.

**Přenesou se moje pravidla (Rules)?**
Ne, pravidla je třeba nastavit znovu v Outlooku.

**Jaký je limit schránky?**
50 GB. Při využívání odkazů místo příloh by neměl být problém.

**Přenese se můj kalendář?**
Ano, ale opakující se události je třeba založit znovu.

### Teams a soubory

**Kdo uvidí moje dokumenty?**
- Osobní (OneDrive/lokální disk) = jen vy
- Sdílené (SharePoint) = podle oprávnění oddělení

**Mohu dohledat staré konverzace?**
Ano, historie je neomezená.

**Co se stane se soubory v Citrixu?**
Přenos proběhne stejně. V tabletech bude přístup přímo přes aplikace.

**Co s OnCloud?**
OnCloud zanikne, nahradí ho SharePoint.

### Externí komunikace

**Co když zákazník nemá M365?**
Může otevřít sdílený dokument přes prohlížeč bez vlastního účtu.

**Změní se EDI komunikace?**
Ne, zůstává zachována.

---

## ČÁST 14: PODPORA A KONTAKTY

### Kde hledat pomoc
1. **Intranet:** Sekce M365 - návody, záznamy, FAQ
2. **Email:** 365@vitar.cz
3. **Ambasadoři:** Kolegové z vašeho oddělení vyškolení na M365
4. **IT oddělení:** Pro technické problémy

---

## ČÁST 15: HARMONOGRAM IMPLEMENTACE

### Prosinec 2025
- Externí školení (Teams 1-3, Outlook 1-2)

### Leden 2026
- Živá vysílání každý pátek
- Instalace M365 aplikací
- Přesun důležitých souborů do nové struktury (do 23.1.)

### Únor 2026
- **4. února:** Spuštění M365 (bod zlomu)
- **4. února 10:00-11:00:** Mimořádné živé vysílání
- Pilotní provoz
- M-client přechází do režimu "pouze ke čtení"

### Co funguje v pilotní fázi
- ✅ Teams - hovory, chat, schůzky
- ✅ Outlook - emaily, kalendář
- ⏳ Nahrávání schůzek - až po spuštění SharePointu
- ⏳ Živé dokumenty - až po spuštění SharePointu

---

## ČÁST 16: TIPY PRO ÚSPĚŠNÝ PŘECHOD

1. **Buďte trpěliví** - je to nový systém, učíme se všichni
2. **Pomáhejte si navzájem** - pokud něco víte, poraďte kolegům
3. **Nebojte se ptát** - žádná otázka není hloupá
4. **Udržujte kalendář aktuální** - pomáhá celé firmě
5. **Zkoušejte nové funkce** - nejlépe se naučíte praxí
6. **Zapněte si upozornění** - aby vám nic neuniklo
7. **Preferujte odkazy před přílohami** - šetří kapacitu a zabraňuje duplicitám
8. **Synchronizujte jen to, s čím pracujete** - méně je více

---

## Příklady odpovědí

### Příklad 1: Dotaz na ukládání souborů
**Uživatel:** Kam mám uložit důležitou tabulku pro celé oddělení?

**Odpověď:**
Důležité týmové dokumenty ukládejte na **SharePoint** (do týmu v Teams), ne na OneDrive.

**Postup:**
1. Otevřete Teams
2. Najděte svůj tým a příslušný kanál
3. Klikněte na záložku "Soubory"
4. Nahrajte soubor nebo vytvořte nový

**DŮLEŽITÉ:** Pokud byste soubor uložili jen na OneDrive a odešli z firmy, mohl by být ztracen!

*Zdroj: Část 3 - OneDrive vs. SharePoint*

---

### Příklad 2: Technický problém
**Uživatel:** Nefunguje mi Teams, co mám dělat?

**Odpověď:**
Pro technické problémy s aplikacemi doporučuji:

1. Zkuste se odhlásit a znovu přihlásit
2. Zkuste webovou verzi na **www.office.com** - ta je obvykle stabilnější
3. Pokud problém přetrvává, kontaktujte **IT oddělení**

Tuto informaci nemám v dostupných materiálech podrobněji. Pro technickou podporu se obraťte na IT.

*Zdroj: Část 14 - Podpora a kontakty*

---

*Verze: 2.0 | Poslední aktualizace: Leden 2026*
*Zdroj: Živá vysílání M365 (leden 2026), Externí školení Jirka Blažek (prosinec 2025)*
