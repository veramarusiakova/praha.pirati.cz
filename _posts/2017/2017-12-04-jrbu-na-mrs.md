---
date:         2017-12-04
category:     blog
tags:         it mrs tetra
layout:       post
title:        "Praha si nechává diktovat podmínky dodavatelem"
image:        overpriced.jpg
author:       Ondřej Profant
---

Pražský Magistrát v zakázce za 77 000 000 Kč bez DPH na rozvoj městské radiové sítě Praha zcela ignoruje tržní prostředí. Namísto otevřené soutěže, která je v tomto případě možná, si nechal zaslat jedinou nabídku v rámci jednacího řízení bez uveřejnění.

Piráti již před víc jak rokem [předvedli][mrs], že městská radiová síť, přes kterou komunikují například městští policisté či záchranka, není zabezpečena a kdokoliv ji může odposlouchávat.

> "Jsou to již skoro 2 roky od doby, co jsem na to upozornil příslušný odbor magistrátu. Rada města má nyní schvalovat zakázku na zalepení této bezpečnostní díry. Avšak namísto rozumného řešení opět přistoupila k nákupu technologií od KonekTelu, který takto špatné řešení dodal. Licenční politika dodavatele totiž vyžaduje poplatek za každý přijimač, zatímco konkurenční řešení pouze za každý vysílač. Jsem přesvědčen, že za cenu tohoto upgradu bychom mohli mít síť zcela novou síť s nižšími dlouhodobými náklady." říká Ondřej Profant, zastupitel za Piráty.

Magistrát opět neřeší vendor lock-in (závislost na jediném dodavateli), který zde v minulosti vznikl. Přitom je zcela reálné soutěžit jednotlivé části systému, z nichž část lze soutěžit v klasické otevřené soutěži. Zbytek je o jednání s výrobcem technologií, firmou Motorola, která v jiných zemích běžně nabízí volnou soutěž dodavatelů. Velmi podobná zakázka mezi Brnem a stejným dodavatelem se nelíbí ani ÚOHS. Úřad v rozhodnutí podrobně rozebírá, že KonekTel není jediným dodavatelem Motorola Solutions. V rozhodnutí je zmíněna např firma  AIRadio Prague, s.r.o. (IČ 25645579). V podkladech hodnocených soudním znalcem jsou dopisy od Motorola Solutions z roku 2015, které nevypovídají o aktuálním stavu trhu ve vztahu k důvodům proč zakázku řešit pomocí institutu JŘBU. Tzv. komunikační okruh, který propojuje jednotlivé vysílače (BTS) je např. zcela běžné datové připojení, které poskytují v ČR stovky firem.

Je zjevné, že kdyby Praha s Brnem spolupracovala, tak namísto složitých JŘBÚ, které jsou jim nakonec smeteny ze stolu, dávno mohly zakázku rozumně specifikovat a soutěžit v klasickém tržním prostředí, kde by vyhrál nejvhodnější dodavatel. Předražení v navrženém rozpočtu, které má RHMP schválit, je v klíčových položkách 200 - 400 % (tj. 2x - 4x vyšší cena).

Srovnání cen vysílaček z nadbídky, kteoru KonekTel předložil pražskému magistrátu a ceny za kterou městská policie Praha vysoutěžila:

| Radiostanice   |  Nabídka KonekTel | Cena MP HMP | Rozdíl |
|--------------------|-----------------------------------------------:|-----------------------------:|--------------:|
| MT3250 - ruční            |  30.403 Kč     | 11.073 Kč |  274% |
| MTM5200 - vozidlová  |  35.624 Kč    |  15.029 Kč  | 237% |



Dále na dodávkách software a hardware pro zabezpečení sítě (šifrování radiového provozu a nahrávání šifrovacích klíčů do radiostanic) porovnání cen zakázky pro Městskou policii Brno (7/2017) a cenu ze schvalovaného dokumentu RHMP


| Popis | Nabídka KonekTel 1/2017 pro MHMP | Cena MP Brno 4/2017 | Rozdíl |
|-----|----:|----:|----:|
| Authentication center (AUC), Air Interface Encryption TEA1 (AIE) a Provisioning Center (PrC) - software a hardware pro šifrování sítě | 6.314.874 Kč | 1.824.180,50 Kč | 346% |
| Key Variable Loader KVL - zařízení pro nahrávání šifrovacích klíčů do radiostanic | 162.288 Kč | 39.485,50 Kč | 410% |


A dále na dodávce BTS (základnové stanice TETRA)


| Popis | Nabídka KonekTel 1/2017 MHMP | Cena KonekTel MP Brno 7/2017 | Rozdíl |
|----|---:|---:|---:|
| Základnová radiostanice stacionární včetně skříně pro umístění technologie + 2 radiostanice pro MTS 40W | 4.598.532 Kč | 1.420.940 Kč | 323% |


U zakázky opět nejsou spočítány celkové náklady za životní cyklus (TCO). Skrytou součástí zakázky, která není zmíněna, je také nákup licencí pro jednotlivé radiostanice (ve vlastnictví např. Dopravního podniku, Městské policie, ...). Podle cen, které jsou součástí smlouvy [KonekTel a MP Brno][smlouvygov] je cena přibližně 4.000 (počet radiostanic) x cca. 2.500 Kč (cena licence na 1 radiostanici) bez ceny práce na nasazení do radiostanic (celková odhadovaná cena zakázek, které nejsou součástí schvalované nabídky, je 12 - 15 milionů Kč bez DPH).


## Odkazy

- [Ukázka nezabezpečení MRS][mrs]
- [Rozhodnutí UOHS][uohs]
- [Smlouva s městskou policii Brno 2017][smlouvygov]
- Tisk Rady R-18999

[mrs]: https://praha.pirati.cz/odposlouchavani.html
[uohs]: https://www.uohs.cz/cs/verejne-zakazky/sbirky-rozhodnuti/detail-15012.html
[smlouvygov]: https://smlouvy.gov.cz/smlouva/1675922
