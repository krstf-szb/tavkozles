# MÉRÉSI JEGYZŐKÖNYV

---

**A mérést végző neve:** Szabó Kristóf
<br>
**A mérés tárgya:** T Ellenálláshálózat
<br>
**A mérés száma:**  01
<br>
**A mérés dátuma:** 2024. 11. 20.
<br>
**A mérést vezette:** Sándor Péter
<br>

**Évfolyam:** 13. E  
**Csoport:** GYAK 1  
**Helyszín:** V3 labor   

---

## 1. Mérés célja
A T ellenállás-hálózat jellemzőinek meghatározása a megadott ellenállásértékek alapján.

<details>
  
 **Kapcsolási rajz**:
 
  ![Képernyőkép 2024-11-13 133415](https://github.com/user-attachments/assets/4193d6d4-7f32-417f-bade-8a58ad50b0dc)

</details>

---

## 2. Alkalmazott mérőeszközök és készülékek

- NI myDAQ
- R1, R3 = 220 $\Omega$
- R2 = 950 $\Omega$
- Breadboard

---

## 3. Számolás
<details>
  
**Képlet**:
  
![keplet](https://github.com/user-attachments/assets/f6ac521b-6188-43b1-b4ae-3bfeab951d5c)


*A képlethez a forrás:https://www.electronics-tutorials.ws/attenuators/t-pad-attenuator.html*

</details>

**Számolás**:

Csillapítás = 6dB

Z = 680

K = 1,9953

$R1,2 = Z \times ( \frac {K - 1} {K + 1} ) = 680 \times ( \frac {1,9953 - 1}  {1,9953 + 1} ) = 255,96$

$R3 = 2Z \times (\frac {K} {K^2 - 1}) = 2 \times 680 \times (\frac {1,9953} {1,9953^2 - 1}) = 910,23$

---

## 4. Szimuláció

<details>
  
![circuit-20241120-1216](https://github.com/user-attachments/assets/c8c9e154-6e29-4686-a3cc-5489c8500af5)


</details>

---

## 5. Gyakorlatban

<details>
  
![setupmk2](https://github.com/user-attachments/assets/30c2160b-ba1e-411e-8010-03c3fd858c8a)


**Generátor**:

![Képernyőkép 2024-11-20 131428](https://github.com/user-attachments/assets/bb1bb91a-1fcb-4dfb-a92c-d9a050764c7a)


**Oscilloscope**:

![Képernyőkép 2024-11-20 131409](https://github.com/user-attachments/assets/7363f3cb-06ef-4f76-8b5d-aca59716d4f3)


</details>
