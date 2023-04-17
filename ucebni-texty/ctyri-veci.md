---
layout: default
title: Učebnní text Čtyři věci na něž myslet při rozvoji čehokoliv
description: "Přinášíme zhuštěný text o tzv. čtyřech dohodách rozvoje nejen pro ICT ve veřejné správě. Defunujeme si čtyři oblasti a podrobně si je rozebereme i se souvislostmi."
parent: Učební texty
nav_order: 11
grand_parent: Výuka EG
last_updated: 2022-06-30
---



## Čtyři klíčové věci na něž myslet: Předmět, Údaj, Dokument, Vazba

Ať už jsme architekti a připravujeme komplexní změnu v úřadu a nebo jsme analytici u dodavatelské firmy, musíme se naučit myslet komplexně a ze všech stran.


Tyto čtyři aspekty jsou důležité, aby systémy správně fungovaly a efektivně si měnily údaje. Je to důležité pro architekty a analytiky při sestavování architektury řešení a datové architektury.


### Popis každé oblasti

Definujeme si následující čtyři rámcové oblasti:

##### Předmět

- Popis:    Subjekt kterého se věc týká, nebo objekt práva jež daná věc řeší
- Kroky:    Vždy musí být jasné zda a kterých subjektů a objektů práva se daná věc týká a musí být jasná vazba na tyto subjekty a objekty.

Vždy když něco děláme, ať už je to návrh řešení či vývoj samotných aplikačních služeb a funkcí, týká se to nějakých předmětů. Za předmět musíme považovat jak subjekt, tak i objekt.

Subjekt je kupříkladu klient kterého se daná věc týká, ale kupříkladu i interní uživatel informačního systému, nebo účastník nějakého procesu či řízení apod. Jde o osobu, nebo o roli, nebo o aktéra v dané věci. Ve veřejné správě je předmětem většinou subjekt (chování k němu a k evidenci údajů o něm je svázáno legislativou a národní architekturou a musí se vždy správně uplatňovat) a jeho daná role a také objekt (kupříkladu oprávnění k řízení či nárok na něco jako objekt práva).

Na úrovni objektového řešení je předmět objektem, kde subjekt má třídu subjektu s definovanými atributy a objekt práva má třídu podle druhu objektu, apod.

Subjekt práva, nebo jen subjekt, je aktérem (v některých případech role) ve smyslu business vrstvy modelu v Archimate, ve fyzickém se jedná o skutečného člověka přicházejícího do interakce. Subjekt má dále referenční odkaz do základních registrů, jako klíčovou vazbu.

Objekt práva, nebo jen objekt, je skutečným business objektem ve smyslu business vrstvy architektury modelu Archimate, ve fyzickém světě je to skutečná věc, kterou úřad dodá či vykoná, například přiznání dávky občanovi.

##### Údaj

- Popis:    Údaj se kterým se při dané věci pracuje, ať už je to vlastní údaj, nebo údaj využívaný odjinud či údaj poskytovaný jinam
- Kroky:    U všeho je nezbytné vědět alespoň jakých skupin údajů a údajů se věc týká. Má být jasné, kde se údaje berou, kdo je za ně zodpovědný, jakou míru důvěry mají a jak se využívají pro byznysové splnění.


Vždy pracujeme s informacemi, kdy naprostá většina informací jsou spravované a vedené údaje. Údaj a skupina údajů by měla být jasná na byznysové vrstvě i na aplikační vrstvě, která nás při tvorbě informačního systému zajímá víc.

Údaj má svůj zdroj, nějak vzniká a nějak se upravuje, má svoji míru důvěryhodnosti a je někde uložen a může být využit pro nějakou byznysovou činnost, kterou provádí daná aplikační komponenta a sada aplikačních služeb a funkcí. Ve veřejné správě se údaji a jeho evidenci přikládá velký důraz, přičemž existuje několik skupin údajů a podle toho do jaké skupiny se konkrétní údaj zahrne se k němu chováme.

Každý údaj musí být vázaný na konkrétní subjekt(y) či objekt(y) tedy v našem pojetí předmět(y).

Vlastní údaj je takový údaj, který jsem vytvořil v konkrétní roli, tento údaj je buď určen k výhradnímu užití mnou, případně je to údaj, který jsem vytvořil a poskytuji ho v rámci propojeného datového fondu, tudíž z pohledu propojeného datového fondu je to poskytovaný údaj. Pokud je tento údaj v rámci propojeného datového fondu konzumován, je z pohledu konzumenta „poskytovaný údaj“.

Vztah k údaji je dále definován jako Primární editor, Sekundární editor, Správce, Konzument. Dále pak má údaj mimo jiné attributy Spárovaný (údaj mající vazbu na subjekt nebo objekt), Provozní (údaj sloužící k provozu vlastního systému).
##
## Dokument

- Popis:    Dokument jako nosič statické informace zakotvené v konkrétním čas, ať už jde o dokument doručený nebo dokument vzniklý z vlastní činnosti
- Kroky:    Pokud se v dané věci pracuje s dokumentem (ať už digitálním či analogovým), musíte to vědět a umět s tím pracovat. Zvlášť v situaci, kdy je dokument výstupem dané věci.

Dokumentem se v tomto kontextu myslí opravdu formalizovaný dokument. Dokument je vlastně reprezentace údajů a informací zafixovaná v čase. Ve veřejné správě se rozlišuje mezi doručeným dokumentem (od někoho jiného a já ho eviduji a spravuji a využívám z něj informace) a dokumentem vlastním (já ho vytvářím s využitím evidovaných údajů a odesílám ho ven). Rámec pro správu dokumentů je zase pro veřejnou správou velice úzký a je třeba ho respektovat opravdu vždy.

##### Vazba

- Popis: Vazba ve formě jakékoliv integrace či propojování údajů nebo služeb. Jde buď o technickou integraci na aplikační úrovni, nebo o byznysovou vazbu
- Kroky: Přes abstraktnost pojmu Vazby by měly být u každé věci známé byznysové vazby jako závislosti a aplikační a technické vazby jako integrace na technické úrovni a třeba i vazby na určité údaje či evidence a jak je získat a jak s nimi pracovat. Klíčové jsou zejména integrace na další komponenty a systémy.

Význam vazba je v našem případě trochu složitější a proto bude jeho rozbor obsáhlejší. Vazbou myslíme vazbu z byznysového (tedy logického) hlediska, tak i z aplikačního (tedy technického) hesldiska.

Za vazbu na byznysové úrovni můžeme považovat jakoukoliv důležitou souvislost (dependency), na kterou je třeba myslet. Kupříkladu vazba u klientského subjektu je "Referenční identia ze základních registrů" a musíme myslet na to, abychom splnili související povinnosti. Obecně povinnosti a jejich splnění jsou docela klíčovými vazbami. Ve sféře ISVS jsou obdobně důležité vazby i na subjekt a objekt o které se jedná.

Po technické stránce za vazbu považujeme integraci na zdroje dat při využívání údajů a na čtenáře při poskytování údajů. Tedy jak technickou vazbu díky které se uskutečňuje výměna údajů, tak ale i vazbu na údaje v určitém systému a evidenci.

### Souvislosti mezi předmětem a údajem a dokumentem a vazbami
 Už jsme si řekli, že všechno souvisí se vším. V dalších odstavcích si detailně rozebereme souvislosti všech čtyř oblastí mezi sebou, což je velice důležité.

**Předmět**

- Souvislosti na předmět: Zejména mezi subjektem a s ním souvisejícími kauzami a případy jako objekty. Existují i byznysové vazby mezi jednotlivými subjekty, jako jsou rodiče, manželé, jednatelé firem apod. To se řeší v rámci správy mandátů viz Mandáty, role a práva v elektronické komunikaci v Národním architektonickém plánu.
- Souvislosti na údaj: O subjektu vedeme údaje. To jsou buď agendové údaje vedené v AIS a sdílené v rámci PPDF, identifikační údaje včetně vlastních identifikátorů a vazby na referenční identity a dále provozní údaje. Příslušné systémy vždy využívají aktuální údaje ze základních registrů a z PPDF. Jsme schopni z datové architektury zjistit, jaké skupiny údajů k subjektu vedeme a kde, víme o jejich aktuálnosti a o způsobech aktualizace. Údaje se týkají i objektu jako byznysové věci, o které se vede evidence či se zpracovává v daném ISVS, a to s vazbou na všechny subjekty a objekty. I u těchto údajů o nich víme veškeré informace. Subjektu údajů jsme schopni jednak poskytnout všechny o něm vedené údaje a jednak jsme schopni jeho údaje poskytovat v rámci PPDF. Údaje  vedené k subjektu údajů, jsme schopni poskytnout jednak subjektu jako takovému a zároveň, jsme je schopni poskytnout do PPDF.
- Souvislosti na dokument: Určitého subjektu se týkají dokumenty, ať už je v roli odesílatele, příjemce či dotčeného subjektu. Vazby subjektu na dokumenty vedeme v ESSL, ve Jmenném rejstříku a vedeme je i v daných agendách v AIS. Také pro správu a tvorbu dokumentů platí, že u subjektu využijeme jeho referenční identitu a vždy víme přesně, o který subjekt se jedná a v jaké roli. Objekty mají souvislost s dokumenty tu, že určité byznysové věci jako objektu (dávky, rozhodnutí, žádost) se týká jeden či více dokumentů většinou seřazených do spisu.
- Souvislosti na vazby: Byznysové vazby mezi subjekty a objekty: Subjekty mají mezi sebou vazby dvojího druhu. Jednak jsou to vazby zákonné, kupříkladu rodič a dítě a nebo manželé a nebo jednatel firmy. Jednak jsou to vazby klientské, kupříkladu zastupovaný subjekt a subjekt jednající oprávněně jeho jménem. Tyto vazby musíme někde evidovat a znát je, a to zejména v rámci elektronické identifikace role subjektu ve vztahu k řešené kauze, neboť nám určují roli, kterou daný subjekt vykonává. Například Zákonný zástupce zastupující nezletilou osobu. Všechny kauzy a byznysové věci řešené se subjektem jsou objekty, jež mají vazbu na subjekt. Technické vazby: Evidence subjektů musí realizovat vazby na eGSB a ISZR pro referenční identitu a referenční údaje a pro získání a sdílení údajů z PPDF o subjektu a o objektech v daných kontextech. Pak jsou samozřejmé technické vazby jako vnitřní integrace a vnější integrace.

**Údaj**

- Souvislosti na předmět: Každý spravovaný a evidovaný údaj se týká buď subjektu (či více), nebo objektu (či více). Takové věci říkáme kontext údaje. Údaj, jež se týká subjektu, s ním musí být svázán využitím buď AIFO (agendový identifikátor fyzické osoby) z dané agendy, nebo vlastním identifikátorem subjektu, pokud je vedena společná evidence subjektů. A vždy s vazbou na referenční identity či na námi spravované jednotné identity v úřadu. Údaje vedené o subjektu se vedou v evidenci subjektů, údaje vedené v kontextu agendy a kontextu jsou vedené v příslušném AIS, jež je schopen je poskytovat a aktualizovat do PPDF a jež je spravuje.
- Souvislosti na údaj: Údaje závisí na jiných údajích. VS rozlišuje referenční údaje, údaje využívané (odjinud), údaje poskytované (jinam), agendové údaje a provozní údaje. Pro každou skupinu existují povinnosti a realizační pravidla.
- Souvislosti na dokument: Údaje reprezentované v daném čase se fixují mimo jiné v podobě dokumentu, ať už jde o dokument doručený (údaje, jež my využíváme), ale zejména o vlastní dokument (s našimi údaji).
- Souvislosti na vazby: Evidence údajů v rámci AIS musí splňovat veškeré požadavky týkající se práva na digitální služby a práva na sdílení a využívání a poskytování údajů v rámci PPDF a subjektu údajů. Technicky musí každá komponenta spravující a evidující údaje umožňovat integraci (nějakým způsobem) na další komponenty systému. Zejména pak na integrační platformy zajišťující externí vnější integraci prostřednictvím ISZR a eGSB pro využívání a sdílení údajů. Další důležitou vazbou je realizace služeb souvisejících se správou, evidencí a poskytováním údajů, kupříkladu pro elektronické formuláře, portálová řešení, PVS a PO atd.


**Dokument**

- Souvislosti na předmět: Odesílatel a příjemce dokumentu jsou subjekty, další subjekty k dokumentu jsou dotčenými subjekty. Vazby subjektů a dokumentů vedeme v ESSL, ve Jmenném rejstříku a udržujeme i v příslušném AIS. Dokument se týká určité věci, která je většinou byznysovým objektem. Odesílatel nám jako subjekt doručuje dokument určitým kanálem. Příjemci zasíláme vlastní dokument definovaným kanálem podle našich povinností.
- Souvislosti na údaj: Dokument je statickým nosičem informací ve formě zafixovaných údajů. Zatímco dokument je statickým prostředkem, tak údaje jsou dynamickými údaji. U doručených dokumentů, ale zejména u dokumentů vlastních, musí být vždy jasné, jaké údaje jsou jimi reprezentovány a v jakém čase. To se týká i konceptuální datové architektury, kde je nutné myslet třeba i na takové věci, jako nevyžadování dokumentů, pokud existují údaje vedené v PPDF. Další důležitou souvislostí je vedení a správa metadat o dokumentech v příslušné evidenci dokumentů (ESSL) a vedení údajů o dokumentech, včetně transakčního protokolu v ESSL a transakcí spojených s údaji a dokumenty v AIS.
- Souvislosti na dokument: U dokumentů obecně rozlišujeme na: Doručené dokumenty (odjinud) a Vlastní dokumenty (naše) a u obou vedeme řádně spisovou službu v ESSL se všemi požadavky. Analogové dokumenty při příjmu digitalizujeme autorizovanou konverzí nebo jinou konverzí. Vlastní dokumenty jsou platné jen tehdy, pokud jsou opatřené kvalifikovanými validačními prvky.
- Souvislosti na vazby: Dokumenty spravujeme a evidujeme v ESSL, což je systém, jež splňuje požadavky NSESSS, veškeré úkony spojené s dokumenty se realizují rozhraním a službami ESSL, a to i v samostatných evidencích, kdy ISSD splňuje požadavky ESSL. Jednotlivé AIS jsou věcnými správci dokumentů, ale po stránce spisové služby je spravuje ESSL.


**Vazby**
- Souvislosti na předmět: Vše, co děláme, má vlastně vazbu alespoň na jeden subjekt či objekt práva a tyto všechny vazby musíme mít na paměti. Co se týče technických/aplikačních/datových vazeb u subjektů, námi spravované a evidované subjekty, jsou-li vedeny v základních registrech, musí mít vazbu na referenční identity a musíme zajistit řádné využívání údajů o subjektech, včetně jejich aktualizací, notifikací, reklamací apod.
- Souvislosti na údaj: Technické vazby údajů jsou jedním z pilířů EG. Musíme dodržovat povinnosti využívání a poskytování údajů z a do propojeného datového fondu (PPDF), a to nejen u referenčních údajů, ale i u všech ostatních údajů vedených v AISech. Technicky se pak realizuje využíváním služeb ISZR a eGSB, tedy vazbami prostřednictvím referenčního rozhraní VS.
- Souvislosti na dokument: Dokument je spravován a evidován v ESSL, tedy úkony spojené s dokumentem se realizují prostřednictvím rozhraní ESSL. Dokument má vazbu na spis, jež může obsahovat další dokumenty. Dokument má vazbu dále na subjekty, kterých se týká, a to odesílatele, příjemce a dotčené subjekty, tyto vazby se evidují ve Jmenném rejstříku v ESSL.
- Souvislosti na vazby: Klíčové jsou byznysové vazby z byznys vrstvy architektury a technické vazby uskutečňující integraci dané komponenty či systému. Integrace je vnitřní (na systémy téhož správce) a vnější (na systémy jiného správce prostřednictvím eGSB a referenčního rozhraní).

{% include ucebni-texty-footer.html %}