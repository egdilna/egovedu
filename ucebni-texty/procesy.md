---
layout: default
title: Učebnní text Procesy v úřadu
description: Učební text - procesní dekompozice a jak se vlastně ze strategického a architektonického hlediska dívat na procesy
parent: Učební texty
nav_order: 12
grand_parent: Výuka EG
last_modified_date: 2024-08-20
---

## Procesy v úřadu a jak na jejich zanesení do architektury a dalších zdrojů

### Vztah procesní dekompozice a architektury

V organizaci může být několik stovek procesů, záleží na tom, jak definujeme proces a jak podrobní budeme v jeho výkladu. Takový stav se strašně špatně udržuje a navíc se i špatně kategorizuje a organizuje do nějakých uchopitelnějších celků. Přesto je nutností mít o procesech přehled.

Zcela zásadní je, že detailní procesní dekompozice <mark>nepatří do architektury, neboť se často mylně zaměňuje architektura a procesní řízení</mark>. Důležité tedy je:

1. Si předem určit, jak hluboko nás procesy zajímají v rámci Enterprise architektury organizace a jaké podrobnosti opravdu potřebujeme mít v architektuře
2. Pokud budeme dělat procesní mapování organizace, v čem a jak ho budeme dělat, abychom tím zbytečně nezaplevelovali ostatní významné zdroje znalostí
3. Co vlastně a v jaké podrobnosti potřebujeme o procesech vědět, zda ná stačí jen proces a jeho vykonavatel, nebo opravdu potřebujeme mít každý proces detailně rozkreslený
4. Kdo jsou účastníci (aktéři) procesů a odkud je budeme brát, zda z detailních procesních modelů, z architektury, nebo v nějaké kombinaci obojího


### Logické dělení procesů v organizaci


Procesy a činnosti  (z architektonického hlediska lze podle potřeby zaměňovat)  v organizaci můžeme rozdělit na tři základní skupiny. Úřady vykonávají všechny tři skupiny, ostatní organizace vykonávají pouze druhou a třetí skupinu, když nevykonávají veřejnou správu.

![Diagram Dělení procesů do skupin](https://raw.githubusercontent.com/egdilna/architektura-urady/Schvalene/diagramy/archimate-model/deleni-procesu-cinnosti.png)

1. Skupina Procesy výkonu veřejné správy : Procesy a činnosti v organizaci, pokud je orgánem veřejné moci vykonává působnost dle agendového modelu veřejné správy, tak vykonává veřejnou správu. Procesy spojené s výkonem agendy veřejné správy jsou procesy výkonu veřejné správy. K nim organizace využívá agendové informační systémy.
    * Činnosti v přenesené působnosti : Činnosti jež jsou stanoveny jako výkon přenesené působnosti, stanovuje agendový zákon a jsou realizovány územě samosprávným celkem příkazem  zákona jako přenesená působnost. Musí mít vazbu na agendu a činnost v rámci Registru práv a povinností prostřednictvím agendového modelu veřejné správy
    * Činnosti v samostatné působnosti : Činnosti jimiž je realizována samostatná působnost územně samosprávných celků není přenesenou působností ze zákona, ale zákon či jiný právní předpis stanovuje věc jako samostatnou působnost. I při samostatné působnosti musí být dodržovány obecné principy veřejnoprávních činností, avšak činnosti samostatné působnosti si upravuje územně samosprávný celek sám a nevychází většinou z činnosti agendového modelu veřejné správy.
2. Skupina Veřejnoprávní procesy : Procesy a činnosti v organizaci, které sami nejsou výkon veřejné správy, ale slouží jako podpůrné pro procesy veřejné správy a pro fungování organizace a jsou také obecně nařízené zákonem. Jde o společné procesy a schopnosti organizace jako celku, jako například spisová služba, ekonomika, personalisty ka nebo zpráva rozpočtu (určuje )
3. Skupina Provozní procesy : Procesy a činnosti v organizaci, které slouží pro její vnitřní fungování a udržování obecných povinností. Buď nejsou zákonem přímo regulovány anebo jsou stanoveny jako obecné s tím, že organizace je může vykonávat libovolným způsobem. Nejedná se přitom o výkon veřejné správy. Příkladem je nákup kancelářských potřeb, knihy jízd a nebo požární ochrana



Příklady procesů dle skupin:

1. Výkon veřejné správy: sociální dávky, řidičské průkazy, cestovní doklady, Portál občana, místní poplatky, živnostenské oprávnění, sdílení údajů, správa ISVS
2. Veřejnoprávní činnosti a procesy: výkon spisové služby, zadávání veřejných zakázek, rozpočet, publikace otevřených dat, hlášení zaměstnanců, žádosti o informace, vykazování pro státní pokladnu, řízení ICT
3. Provozní procesy: drobné nákupy, účetnictví, kniha jízd, objednávání klientů, docházka
