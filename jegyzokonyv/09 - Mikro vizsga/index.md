
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
    
        Az egyik laptopon futtassa szerverként:
        
![-s](https://github.com/user-attachments/assets/26717c8f-def1-4dcb-b08d-c8a15b57640b)

        A másik végponti eszközön futtassa kliensként:
        
![-c ](https://github.com/user-attachments/assets/87467df8-b453-4c00-9d88-8134314d8974)

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

![casda1](https://github.com/user-attachments/assets/ab5f79bf-0a25-4f28-b159-c179a7fd129f)


---
## 4. Adatátvitel értékei

| RSSI | RSRP | SINR | RSRQ |
| ---- | ---- | ---- | ---- |
| -52 dBm | -83 dBm | 17 dB | -11 dB |

![teszt1](https://github.com/user-attachments/assets/26c0b2aa-8ef9-47d2-8cd2-c715bb4a92d3)



---
