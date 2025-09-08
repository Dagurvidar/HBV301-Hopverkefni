# 📄 Software Requirements Specification (SRS)

## 1. Inngangur

### 1.1 Tilgangur

Kerfið á að auðvelda háskóla nemum við að halda utan um frammistöðu sína á meðan á önn stendur.

### 1.2 Umfang

Kerfið mun geyma einkunnir, mætingu ásamt því að gefa notendum stöðumat svo þeir megi sjá hvernig þeir standa sig yfir önnina.

#### Einkunnir

Notandi á að geta séð yfirlit yfir allar einkunnir sýnar hjá hverjum áfanga fyrir sig (ein síða per áfanga). Þær verða birtar með grafi, meðal-, miðgildi og hæstu og lægstu einkunnir ásamt einföldu yfirliti yfir þær allar. (Hér má taka fram að fyrst einkunnir gilda misjafnt eftir stærð verkefnis gæti verið sniðugt að hafa dálk til hliðar sem sýnir hverja einkunn sem prósenta af heildareinkunn. T.d. 4/5% ef verkefnið gildir 5% af heild en notandi fékk 8 í verkefninu)

#### mæting

Sérstaklega fyrir tíma með skyldumætingu eða minnstu leyfðu mætingu til lokaprófsréttar. Þetta á að auðvelda notendum að sjá hversu marga tíma þeir eiga eftir að mæta í og ef þeir eiga t.d. eftir að mæta í fleiri tíma heldur en eru eftir myndi kerfið vara við því svo notandi geti haft samband við kennara og fundið út úr því.

#### stöðumat

Notendur ættu að sjá graf yfir það hvernig þau hafa staðið sig í hverjum áfanga fyrir sig á þeim tíma sem þau kíkja. Aukalega ætti grafið þá að spá fyrir lokaeinkunn nemenda m.þ.a. nota tölfræði út frá einkunnum hans. Það mun þá gefa spáða einkunn, lægstu spáða einkunn og hæstu spáða einkunn. Þetta mun hins vegar bara spá fyrir verkefnaeinkunn en gefur hins vegar upp hvaða lokaprófseinkunn þú munt þá þurfa til að ná. Að lokum mun nemandi líka geta séð hver lokaeinkunn hans verður m.v. mismunandi lokaprófseinkunnir.

### 1.3 Skilgreiningar

| Hugtak | Skýring                                            |
| ------ | -------------------------------------------------- |
| SRS    | Software Requirements Specification                |
| Issue  | Umræða/atriði í GitHub sem tengist ákveðinni kröfu |

### 1.4 Tilvísanir

- IEEE 830 Standard (fyrirmynd að uppbyggingu SRS)

---

## 2. Almenn lýsing

### 2.1 Notendahópar

Nemendur nota kerfið til þess að

1. Fylgjast með árangri sínum í hverjum áfanga fyrir sig.
2. Sjá spá fyrir lokaeinkunn fyrir verkefni.
3. Tryggja það að þeir missi ekki próftökurétt vegna skort á mætingu t.d. í dæmatíma m.a. með því að fá viðvörun þegar þeir eru nálægt því.

Kennarar nota kerfið til að fylgjast með framgangi námskeiðsins. Þetta er gert m.þ.a. gefa þeim nánari upplýsingar og spár um einkunnir nemenda sinna

### 2.2 Viðskiptaávinningur

- Minni hætta á að nemendur ruglist og nái ekki próftökurétti út af mætingu. Þetta minnkar hlutfall nemenda sem falla af þeirri ástæðu.
- Bætir námsupplifun með einföldu viðmóti og sameiginlegri geymslu á öllum einkunnum og mætingu.
- Bætir námsframvindu með því að upplýsa nemendur um hvernig þeim gengur yfir önnina og hjálpar þeim að setja markmið með því að spá fyrir loka verkefnaeinkunn.
- Minnkar hlutfall nemenda sem falla með því að segja þeim fyrirfram hvað þeir þurfa háa einkunn til að ná áfanganum (Gjarnan er ekki nóg að fá bara yfir 4.5 í áfanga heldur líka ákveðið háa lokaeinkunn).
- Gefur kennurum einn stað til að skrá og fara yfir allar einkunnir sem sparar þeim tíma og gefur þeim betri yfirsýn yfir hvernig áfanganum gengur.

---

## 3. Kröfur fyrir kerfið

### 3.1 Viðskiptakröfur

| ID  | Lýsing                                                                           | Issue |
| --- | -------------------------------------------------------------------------------- | ----- |
| BR1 | [Bæta skipulag nemenda m.þ.a. halda utan um einkunnir á einum stað]              | [#5]  |
| BR2 | [Halda utan um mætingu nemenda og veita viðvaranir ef próftökuréttur er í hættu] | [#6]  |

### 3.2 Kerfiskrafa

| ID  | Lýsing                                                                              | Issue |
| --- | ----------------------------------------------------------------------------------- | ----- |
| SR1 | [Kerfið skal birta viðmót fyrir mætingu og einkunnir í Canvas undir hverjum áfanga] | [#7]  |

### 3.3 Fídusar (Features)

| ID  | Lýsing                              | Issue |
| --- | ----------------------------------- | ----- |
| F1  | [Innsending verkefna og prófa]      | [#8]  |
| F2  | [Einkunnagjöf og endurgjöf kennara] | [#10] |
| F3  | [Yfirlit yfir námsframvindu]        | [#11] |

### 3.4 Notendakröfur

| ID  | Lýsing                                                                                                                    | Fídus | Issue |
| --- | ------------------------------------------------------------------------------------------------------------------------- | ----- | ----- |
| UR1 | [Sem nemandi vil ég geta skilað verkefnum rafrænt í kerfið svo að ég þurfi ekki að skila á pappír eða með tölvupósti]     | F1    | [#9]  |
| UR2 | [Nemendur geta séð einkunnir sínar og hversu hátt þær gilda að lokaeinkunn]                                               | F1    | [#12] |
| UR3 | [Sem nemandi vil ég fá staðfestingu þegar ég hef skilað verkefni svo að ég viti að skilin hafi tekist]                    | F2    | [#16] |
| UR4 | [Sem kennari vil ég geta skráð einkunnir beint í kerfið svo að nemendur hafi strax aðgang að þeim]                        | F2    | [#17] |
| UR5 | [Sem nemandi vil ég geta skoðað endurgjöf frá kennara svo að ég læri af verkefnum og prófum]                              | F3    | [#19] |
| UR6 | [Sem kennari vil ég geta séð heildaryfirlit yfir námsárangur hópsins svo að ég geti metið hvort kennsluaðferðirnar virki] | F3    | [#20] |

### 3.5 Virknikröfur

| ID   | Lýsing                                                                                                                           | Notendakrafa | Issue |
| ---- | -------------------------------------------------------------------------------------------------------------------------------- | ------------ | ----- |
| FR1  | [Kerfið á að leyfa nemanda að hlaða upp verkefnaskrá í PDF eða DOCX formi.]                                                      | UR1          | [#27] |
| FR2  | [Kerfið á að vista skrá með tengingu við réttan áfanga og réttan skilafrest.]                                                    | UR1          | [#28] |
| FR3  | [Kerfið á að gefa villuboð ef skráin er í röngu sniði eða of stór.]                                                              | UR1          | [#29] |
| FR4  | [Kerfið á að birta staðfestingarskilaboð eftir að verkefni hefur verið skilað.]                                                  | UR2          | [#30] |
| FR5  | Kerfið á að senda tölvupóst eða tilkynningu í appi þegar skil hefur verið móttekið.[]                                            | UR2          | [#31] |
| FR6  | [Kerfið á að geyma skráða staðfestingu sem nemandi getur skoðað síðar.]                                                          | UR2          | [#32] |
| FR7  | [Kerfið á að leyfa kennara að skrá einkunn á verkefni eða próf.                                                                  |
| ]    | UR3                                                                                                                              | [#33]        |
| FR8  | [Kerfið á að tryggja að aðeins skráðir kennarar geti skráð einkunnir.]                                                           | UR3          | [#34] |
| FR9  | [Kerfið á að vista einkunnir varanlega og leyfa útflutning í CSV/Excel.]                                                         | UR3          | [#35] |
| FR10 | [Kerfið á að leyfa kennara að skrifa texta sem endurgjöf við verkefni.]                                                          | UR4          | [#36] |
| FR11 | [Kerfið á að sýna endurgjöf á sama stað og einkunnir.]                                                                           | UR4          | [#37] |
| FR12 | [Kerfið á að leyfa nemanda að skoða eldri endurgjafir aftur hvenær sem er.]                                                      | UR4          | [#38] |
| FR13 | [Kennari skoðar áfanga og sér dreifirit yfir einkunnir allra nemenda.]                                                           | UR5          | [#39] |
| FR14 | [Kerfið á að sýna meðaleinkunn og staðalfrávik fyrir bekkinn.]                                                                   | UR5          | [#40] |
| FR15 | [Kerfið á að leyfa útflutning á árangursgögnum fyrir hópinn í Excel/CSV.]                                                        | UR5          | [#41] |
| FR16 | [Kerfið skal sýna samanburð á einkunnum í hverjum áfanga með vægi þeirra í heildareinkunn.]                                      | UR6          | [#42] |
| FR17 | [Kerfið skal leyfa nemanda að sía eða flokka einkunnir eftir áföngum, verkefnum eða prófum.]                                     | UR6          | [#43] |
| FR18 | [Kerfið skal veita yfirlit í myndrænu formi (t.d. súlurit eða línurit) sem sýnir hvernig einkunnir leggja saman að lokaeinkunn.] | UR6          | [#44] |

### 3.6 Viðskiptareglur

| ID   | Lýsing                                             | Issue |
| ---- | -------------------------------------------------- | ----- |
| BRG1 | [Aðeins kennari getur skráð mætingu nemenda]       | [#13] |
| BRG2 | [Kennari hefur tvo virka daga til að skrá mætingu] | [#14] |

### 3.7 Gæðaeiginleikar

| ID  | Lýsing                                                                                             | Issue |
| --- | -------------------------------------------------------------------------------------------------- | ----- |
| QR1 | [Yfirlit einkunna og mætinga skal vera á sömu síðu]                                                | [#18] |
| QR2 | [Kerfið ætti alltaf að innihalda allar einkunnir sem nemandi hefur fengið um leið og hann fær þær] | [#15] |

### 3.8 Takmarkanir

| ID  | Lýsing                                                                                                                              | Issue |
| --- | ----------------------------------------------------------------------------------------------------------------------------------- | ----- |
| C1  | [Kerfið verður að útfæra sem Canvas Module, þ.e. hluti af Canvas]                                                                   | [#23] |
| C2  | [Forritið verður að fá einkunnir frá öppum eins og Gradescope frekar en að kennari setji einkunnir inn á bæði Canvas og Gradescope] | [#24] |

### 3.9 Ytri skil (Interfaces)

| ID  | Lýsing                                                                                                           | Issue |
| --- | ---------------------------------------------------------------------------------------------------------------- | ----- |
| IF1 | [Einkunnakerfið mun ná í einkunnir frá forritum utan Canvas í gegnum tilsvarandi tæknir (API, file export etc.)] | [#25] |
| IF2 | [Einkunna-/mætingarkerfið mun fá upplýsingar um hver notandi er í gegnum Canvas SSO]                             | [#26] |

---

## 4. Viðaukar

### 4.1 Orðalisti

- Skilgreina lykilhugtök.

### 4.2 Samþykktir

- Kennari: **\*\*\*\***\_\_\_\_**\*\*\*\***
- Nemandi: **\*\*\*\***\_\_\_\_**\*\*\*\***
