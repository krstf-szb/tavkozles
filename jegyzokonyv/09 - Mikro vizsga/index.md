
# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** Szabó Kristóf
**A mérés tárgya:** Komplex Távközlési Hálózat Tervezése, Telepítése és Mérése
**A mérés száma:** 09
**A mérés dátuma:** 2025. 01. 28.
**A mérést vezette:** Sándor Péter  

**Évfolyam:** 13. E  
**Csoport:** GYAK 2  
**Helyszín:** V3 Labor

---

## 1. Mérés célja

A kiépített antennás hálózat adatátviteli paramétereinek meghatározása.


<details>
  <summary>
    A mérés menete
  </summary>
  1. Előkészítés és tervezés
    1.1. Eszközök gyári beállításainak visszaállítása (Factory Reset)
    1.2. Hálózati topológia tervezése
  2. Eszközök telepítése és konfigurálása
    2.1. Mikrotik LHG18 LTE antenna beállítása
    2.2. Mikrotik nRay 60GHz antennapár beállítása
    2.3. SOHO router beállítása AP módban
  3. Hálózati tesztelés és hibakeresés
    3.1. Ping teszt végrehajtása
    3.2. Sávszélesség mérése (iperf használata)
  4. Dokumentáció és értékelés
</details>

---

## 2. Alkalmazott mérőeszközök és készülékek

| Gyártó neve | Típus       |
| ------------| ----------- |
| Mikrotik | LHG18 LTE antenna |
| Mikrotik | nRay 60GHz mikrohullámú antenna szett |
| ASUS | RT-AX58 |

---
## 3. Kapcsolási rajz

![Megnevezetlen diagram](https://github.com/user-attachments/assets/3dc9ae66-df74-4f65-a75e-24abb0690100)


---
## 4. Antennák teljesítménye különböző frekvenciákon

| RSSI | RSRP | SINR | RSRQ |
| ---- | ---- | ---- | ---- |
| -51 dBm | -85 dBm | 20 dB | -13 dB |


WAN 100.82.157.99

---
