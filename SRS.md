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

| ID  | Lýsing                    | Issue                  |
| --- | ------------------------- | ---------------------- |
| BR1 | [Lýsing á viðskiptakröfu] | [#12](../../issues/12) |
| BR2 | [Lýsing á viðskiptakröfu] | [#13](../../issues/13) |

### 3.2 Kerfiskrafa

| ID  | Lýsing                 | Issue                  |
| --- | ---------------------- | ---------------------- |
| SR1 | [Lýsing á kerfiskröfu] | [#14](../../issues/14) |

### 3.3 Fídusar (Features)

| ID  | Lýsing            | Issue                  |
| --- | ----------------- | ---------------------- |
| F1  | [Lýsing á fídusi] | [#15](../../issues/15) |
| F2  | [Lýsing á fídusi] | [#16](../../issues/16) |
| F3  | [Lýsing á fídusi] | [#17](../../issues/17) |

### 3.4 Notendakröfur

| ID  | Lýsing           | Fídus | Issue                  |
| --- | ---------------- | ----- | ---------------------- |
| UR1 | [Notendakrafa 1] | F1    | [#18](../../issues/18) |
| UR2 | [Notendakrafa 2] | F1    | [#19](../../issues/19) |
| UR3 | [Notendakrafa 3] | F2    | [#20](../../issues/20) |
| UR4 | [Notendakrafa 4] | F2    | [#21](../../issues/21) |
| UR5 | [Notendakrafa 5] | F3    | [#22](../../issues/22) |
| UR6 | [Notendakrafa 6] | F3    | [#23](../../issues/23) |

### 3.5 Virknikröfur

| ID   | Lýsing                           | Notendakrafa | Issue                  |
| ---- | -------------------------------- | ------------ | ---------------------- |
| FR1  | [Virkni sem styður notendakröfu] | UR1          | [#24](../../issues/24) |
| FR2  | [Önnur virkni]                   | UR1          | [#25](../../issues/25) |
| FR3  | [Önnur virkni]                   | UR1          | [#26](../../issues/26) |
| FR4  | [Virkni]                         | UR2          | [#27](../../issues/27) |
| FR5  | [Virkni]                         | UR2          | [#28](../../issues/28) |
| FR6  | [Virkni]                         | UR2          | [#29](../../issues/29) |
| FR7  | [Virkni]                         | UR3          | [#30](../../issues/30) |
| FR8  | [Virkni]                         | UR3          | [#31](../../issues/31) |
| FR9  | [Virkni]                         | UR3          | [#32](../../issues/32) |
| FR10 | [Virkni]                         | UR4          | [#33](../../issues/33) |
| FR11 | [Virkni]                         | UR4          | [#34](../../issues/34) |
| FR12 | [Virkni]                         | UR4          | [#35](../../issues/35) |
| FR13 | [Virkni]                         | UR5          | [#36](../../issues/36) |
| FR14 | [Virkni]                         | UR5          | [#37](../../issues/37) |
| FR15 | [Virkni]                         | UR5          | [#38](../../issues/38) |
| FR16 | [Virkni]                         | UR6          | [#39](../../issues/39) |
| FR17 | [Virkni]                         | UR6          | [#40](../../issues/40) |
| FR18 | [Virkni]                         | UR6          | [#41](../../issues/41) |

### 3.6 Viðskiptareglur

| ID   | Lýsing           | Issue                  |
| ---- | ---------------- | ---------------------- |
| BRG1 | [Viðskiptaregla] | [#42](../../issues/42) |
| BRG2 | [Viðskiptaregla] | [#43](../../issues/43) |

### 3.7 Óvirknikröfur

| ID   | Lýsing         | Issue                  |
| ---- | -------------- | ---------------------- |
| NFR1 | [Óvirknikrafa] | [#44](../../issues/44) |
| NFR2 | [Óvirknikrafa] | [#45](../../issues/45) |
| NFR3 | [Óvirknikrafa] | [#46](../../issues/46) |
| NFR4 | [Óvirknikrafa] | [#47](../../issues/47) |
| NFR5 | [Óvirknikrafa] | [#48](../../issues/48) |
| NFR6 | [Óvirknikrafa] | [#49](../../issues/49) |

### 3.8 Gæðaeiginleikar

| ID  | Lýsing           | Issue                  |
| --- | ---------------- | ---------------------- |
| QR1 | [Gæðaeiginleiki] | [#50](../../issues/50) |
| QR2 | [Gæðaeiginleiki] | [#51](../../issues/51) |

### 3.9 Takmarkanir

| ID  | Lýsing      | Issue                  |
| --- | ----------- | ---------------------- |
| C1  | [Takmörkun] | [#52](../../issues/52) |
| C2  | [Takmörkun] | [#53](../../issues/53) |

### 3.10 Ytri skil (Interfaces)

| ID  | Lýsing      | Issue                  |
| --- | ----------- | ---------------------- |
| IF1 | [Ytra skil] | [#54](../../issues/54) |
| IF2 | [Ytra skil] | [#55](../../issues/55) |

---

## 4. Viðaukar

### 4.1 Orðalisti

- Skilgreina lykilhugtök.

### 4.2 Samþykktir

- Kennari: **\*\*\*\***\_\_\_\_**\*\*\*\***
- Nemandi: **\*\*\*\***\_\_\_\_**\*\*\*\***
