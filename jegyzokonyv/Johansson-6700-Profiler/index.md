
# MÉRÉSI JEGYZŐKÖNYV

---

**A mérést végző neve:** Szabó Kristóf 

**A mérés tárgya:** Johansson 6700 Profiler programozható antennaerősítő-szűrő használata

**A mérés száma:**  04

**A mérés dátuma:**  2024. 12. 04. 

**A mérést vezette:** Sándor Péter  

**Évfolyam:** 13. E  

**Csoport:** GYAK 2  

**Helyszín:** V3 Labor

---

## 1. Mérés célja

A gyakorlat célja, hogy a diákok elsajátítsák a Johansson 6700 Profiler antennaerősítő-szűrő beállításainak gyakorlati használatát különböző antennák jeleinek kezelésére. A feladat során a diákok beállítják a csatornákat, optimalizálják a jelszinteket és vizsgálják a bejövő és kimenő jeleket spektrum analizátor segítségével.

---

## 2. Alkalmazott mérőeszközök és készülékek

| Műszer neve                         | Típus                  | Gyártási szám |
|-------------------------------------|------------------------|---------------|
| Johansson                           | 6700 Profiler          | 28806         |
| Metek                               | HDD Spektrumanalizátor | 211112002390  |
| SMART                               | HD550                  | ...    |
| ...                 | ...       | ...           |

---
## 3. Feladat leírása

### 1. Eszközök bekapcsolása és bekötése


<summary>45 - 1000 MHz közötti ablakban érkező jelek mentése.</summary>
<details>
  
![392387804-2f111542-4d61-4703-ab87-aa67ebedad50](https://github.com/user-attachments/assets/3b561ba1-d581-4a3f-85f8-b72c4b558657)
</details>

SMARTHD550 antenna csatlakoztatása a Johansson 6700 Profiler egyik illeszkedő bemenetére.

FM antenna bekötése a profiler FM bemenetére.

A spektrum analizátor csatlakoztatása a Johansson 6700 Profiler kimenetére, a kimenő jelek méréséhez.

### 2. Csatornaáthelyezés és jelszint-optimalizálás

A Johansson 6700 csatornaáthelyezési funkciójának (frekvenciakonverter) használata, és a DVB-T jelek különböző frekvenciákra való áthelyezése.
<br>
(Példa: A DVB-T jelek áthelyezése növekső sorrendbe a 41-es csatornától kezdve.)



<details>
  
<summary>Csatornák leírása:</summary>

![Csatornák](https://github.com/user-attachments/assets/fa621570-52fc-4338-b623-62cb5c120959)

</details>

A kimenő jelszintek egységesítése 100dBu -ra, függetlenül a bejövő jelek eltérő szintjétől.

A bemeneti és kimeneti jelszintek rögzítése a spektrum analizátor segítségével, és azok feljegyzése.

Az LTE szűrő vizsgálata az eszközben, hogy megszűri-e a 790 MHz feletti zavaró jeleket.

<details>
  
<summary>Frekvenciakonvertált jelek:</summary>

![392387794-d9c9e5ed-3fe1-4a06-98a5-6dd57d3704b3](https://github.com/user-attachments/assets/f6d5fbd3-40e0-490a-a5da-e516e34212d5)
</details>

---

## 4. Jelszintek frekvenciakonvertelés előtt/után

Beérkező csatornák:

|Csatorna|multiplex C|multiplex D|multiplex B|Miskolc Városi TV|multiplex A|multiplex E|
|--|--|--|--|--|--|--|
|Csatorna száma|28|31|35|41|45|48|
|Frekvencia (MHz)|530|554|586|634|666|690|
|Jelszint (dB)|61|64|62|48|63|58|

<details>
  
![392387804-2f111542-4d61-4703-ab87-aa67ebedad50](https://github.com/user-attachments/assets/3b561ba1-d581-4a3f-85f8-b72c4b558657)
</details>

Frekvenciakonvertelt csatornák:

|Csatorna|multiplex C|multiplex D|multiplex B|Miskolc Városi TV|multiplex A|multiplex E|
|--|--|--|--|--|--|--|
|Csatorna száma|41|42|43|44|45|46|
|Frekvencia (MHz)|634|642|650|658|666|674|
|Jelszint (dB)|100|100|100|100|100|100|

<details>
  
![392387794-d9c9e5ed-3fe1-4a06-98a5-6dd57d3704b3](https://github.com/user-attachments/assets/f6d5fbd3-40e0-490a-a5da-e516e34212d5)
</details>

A feladatnak megfelelően a beérkező csatornák a Johanssn 6700 profiler segítégével át lettek helyezve egy másik csatornára, és a jelük fel lett egységesen erősítve 100dB-re

<details>
  
<summary>Grafikon:</summary>

![Névtelen terv](https://github.com/user-attachments/assets/8ea6c17b-3f1e-4c92-93dc-5f67a10d43a9)

</details>

---
