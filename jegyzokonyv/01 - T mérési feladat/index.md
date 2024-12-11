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
  
  ![](https://github.com/GyorgyPeter/tavkozles/blob/main/jegyzokonyv/T-ellenallas-halozat/kepek/K%C3%A9perny%C5%91k%C3%A9p%202024-11-13%20133415.png)
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
  
![](https://github.com/GyorgyPeter/tavkozles/blob/main/jegyzokonyv/T-ellenallas-halozat/kepek/circuit-20241120-1216.png)

</details>

---

## 5. Gyakorlatban

<details>

![](https://github.com/krstf-szb/tavkozles/blob/main/jegyzokonyv/T-ellenallas-halozat/Kepek/setupmk2.jpg)

**Generátor**:

![](https://github.com/GyorgyPeter/tavkozles/blob/main/jegyzokonyv/T-ellenallas-halozat/kepek/K%C3%A9perny%C5%91k%C3%A9p%202024-11-20%20131428.png)

**Oscilloscope**:

![](https://github.com/GyorgyPeter/tavkozles/blob/main/jegyzokonyv/T-ellenallas-halozat/kepek/K%C3%A9perny%C5%91k%C3%A9p%202024-11-20%20131409.png)

</details>
