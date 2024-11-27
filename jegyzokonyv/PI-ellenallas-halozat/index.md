
# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** Szabó Kristóf

**A mérés tárgya:**  $\displaystyle \pi$ Ellenállás-hálózat

**A mérés száma:**  02

**A mérés dátuma:** 2024.11.27.   

**A mérést vezette:** Sándor Péter  

**Évfolyam:** 13. E 

**Csoport:** GYAK 2  

**Helyszín:**  V3 labor 

---

## 1. Mérés célja
A $\displaystyle \pi$ ellenállás-hálózat jellemzőinek meghatározása a megadott ellenállásértékek alapján.

<details>
  
### Kapcsolási rajz:
  
  ![kapcs](https://github.com/user-attachments/assets/dbae2317-3cc8-4935-8422-341aeec8bbc8)

</details>
---

## 2. Alkalmazott mérőeszközök és készülékek

- NI myDAQ
- R1, R3 = 4,5k $\Omega$
- R2 = 1,1k $\Omega$
- Breadboard
---

### 3. Számolás
<details>
  
![keplet2](https://github.com/user-attachments/assets/f14f7bb8-bcbb-4654-9393-173a0432805d)

*A képlethez a forrás:https://www.electronics-tutorials.ws/attenuators/t-pad-attenuator.html*
</details>

Csillapítás = 6dB

Z = 1,5k

K = 1,9953

$R1,3 = Z \times (\frac {K+1}{K-1}) = 1,5k \times (\frac {1,9953+1}{1,9953-1} = 4,51k)$

$R2 = Z \times (\frac {K^2-1}{2K}) = 1,5k \times (\frac {1,9953^2-1}{2 \times 1,9953}) = 1,12k$


---

## 4. Szimuláció

![circuit-20241127-1158](https://github.com/user-attachments/assets/5d6d1a31-afb6-4ea2-9f66-ab2c48cfcbb0)

---

## 5. Gyakorlatban


</details>
