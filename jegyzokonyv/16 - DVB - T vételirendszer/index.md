



# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** Szabó Kristóf

**A mérés tárgya:** DVB-T vételirendszer

**A mérés száma:** 16

**A mérés dátuma:** 2025.03.19.

**A mérést vezette:** Sándor Péter  

**Évfolyam:** 13. E  
**Csoport:** GYAK 2  
**Helyszín:** V3 labor

---

## 1. Mérés célja

DVB-T vételirendszer kiépítése, set-top boxxal való összedugása, mérése majd a mért jel dokumentálása.

---

## 2. Alkalmazott mérőeszközök és készülékek

| Gyártó neve                         | Típus       |
| ----------------------------------- | ----------- |
| METEK | HDD |
| OPTICUM | NYTRO BOX plus |
| OPTICUM | SMART HD 550 |

---

### 3. **Mérési helyszín és környezet**
- **Antenna magassága**: ~90cm
- **Környezet jellemzői**: Beltér, száraz, szélcsend, szobahőmérséklet
- **Adó távolsága**: ~~760m

---

## 4. Csatornák mérése

### Jelosztó nélkül:

| Multiplex   | Frekvencia (MHz) | ERP (kW) | Jelszint (dBuV) | Noise Margin | MER (dB) | Packet errors | Moduláció |
|-------------|------------------|----------|-----------------|--------------|----------|---------------|-----------|
| C           | 530              | 3,2      | 60,5            | 12,9         | 29,1     | 0,00          | 64QAM     |
| D           | 554              | 4,6      | 58,2            | 11,4         | 27,6     | 0,00          | 64QAM     |
| B           | 586              | 3,9      | 57,7            | 10,9         | 27,6     | 0,00          | 64QAM     |
| Miskolc TV  | 634              | 0,126    | 47,2            | 20,0         | 22,7     | 0,00          | QPSK      |
| A           | 666              | 5        | 56,0            | 4,1          | 20,8     | 0,00          | 64QAM     |
| E           | 690              | 4,1      | 57,2            | 10,7         | 26,9     | 0,00          | 64QAM     |


![its_snapshot_0001](https://github.com/user-attachments/assets/4b23f190-1448-447a-b3b0-ba2087706a96)
![its_snapshot_0002](https://github.com/user-attachments/assets/1617de02-2fe8-49c4-bb19-d0f04b2d37c2)
![its_snapshot_0003](https://github.com/user-attachments/assets/68929c26-6c12-42b9-ab86-3924ddd9b4d8)

![its_snapshot_0004](https://github.com/user-attachments/assets/c673d97a-8320-4af7-9523-6dd034ffe464)
![its_snapshot_0005](https://github.com/user-attachments/assets/ec8eef01-e660-4d76-b140-554314ae0d26)
![its_snapshot_0006](https://github.com/user-attachments/assets/0d9a5d0b-6d31-4221-bc6f-377489ac119b)

---

### Jelosztóval:

| Multiplex  | Jelszint (dBuV) | Noise Margin | MER (dB) | Packet errors | Csillapítás (dB) |
|------------|-----------------|--------------|----------|---------------|------------------|
| C          | 60,0            | 8,7          | 24,8     | 0,00          | 0,5              |
| D          | 55,5            | 8,1          | 24,3     | 0,00          | 2,7              |
| B          | 55,3            | 12,8         | 29,8     | 0,00          | 2,4              |
| Miskolc TV | 42,2            | 15,4         | 19,1     | 0,00          | 5                |
| A          | 50,5            | 7,4          | 24,0     | 0,00          | 5,5              |
| E          | 52,1            | 7,2          | 23,4     | 0,00          | 5,1              |

![its_snapshot_0013](https://github.com/user-attachments/assets/9020cda1-315f-45ba-b141-7c7918485cc7)
![its_snapshot_0014](https://github.com/user-attachments/assets/96ab3cc6-8b88-40b6-810f-199e0d729f57)
![its_snapshot_0015](https://github.com/user-attachments/assets/46f630b4-df50-4b41-bdc1-b774f9b520e1)

![its_snapshot_0016](https://github.com/user-attachments/assets/b4608f99-1d5a-41bd-92f8-358fb2592f39)
![its_snapshot_0017](https://github.com/user-attachments/assets/0a946b11-91a4-4e0c-b5ba-b28ceb1e2a8a)
![its_snapshot_0018](https://github.com/user-attachments/assets/0d6f26a9-0236-47bf-9eae-ec56299ce842)

---

## 5. Diagrammok

Csillapítás:

![image](https://github.com/user-attachments/assets/679739a1-3b3d-42a2-adde-7d10af87d923)


Noise Margin:

![image](https://github.com/user-attachments/assets/eb362a2a-7fff-497f-b323-666869ff1935)


MER érték:

![image](https://github.com/user-attachments/assets/a2489659-5470-4fff-b79a-1d5a0ea96c58)


---
## 6. Mérési eredmények elemzése:

  A jelosztó beépítése után, 6dB tervezett csillapítás helyett, drasztikusan kevesebb volt helyenként a csillapítás értéke.

 

