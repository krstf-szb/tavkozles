
# MÉRÉSI JEGYZŐKÖNYV

---

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
  <summary> <strong>Kapcsolási rajz:</strong></summary>
  <p align="center">
    
  <img width="60%" height="60%" src="https://github.com/user-attachments/assets/dbae2317-3cc8-4935-8422-341aeec8bbc8">
  
</p>

</details>



---

## 2. Alkalmazott mérőeszközök és készülékek

- NI myDAQ
- R1, R3 = 4,5k $\Omega$ ($4 \times 9,1k \Omega$)
- R2 = 1,1k $\Omega$ ($2 \times 2,2k \Omega$)
- Breadboard
<details>
  
  *A mérés során használt ellenállások értéke eltér a kiszámolt ellenállásoktól*
</details>

---

### 3. Számolás
<details>
  
<summary><strong>Képlet:</strong></summary>

  <p align="center">
    
   <img width="50%" height="50%" src="https://github.com/user-attachments/assets/f14f7bb8-bcbb-4654-9393-173a0432805d">
    
  </p>
  
*A képlethez a forrás:https://www.electronics-tutorials.ws/attenuators/t-pad-attenuator.html*
</details>

Csillapítás = 6dB

Z = 1,5k

K = 1,9953

$R1,3 = Z \times (\frac {K+1}{K-1}) = 1,5k \times (\frac {1,9953+1}{1,9953-1}) = 4,51k$

$R2 = Z \times (\frac {K^2-1}{2K}) = 1,5k \times (\frac {1,9953^2-1}{2 \times 1,9953}) = 1,12k$


---

## 4. Szimuláció
<details>
  
<summary>Falstad szimuláció</summary>
  
   <p align="center">
    
   <img width="70%" height="70%" src="https://github.com/user-attachments/assets/5d6d1a31-afb6-4ea2-9f66-ab2c48cfcbb0">
    
  </p>
  
</details>

---

## 5. Gyakorlatban
<details>
  
  <summary>MyDAQ-on összerakva</summary>
  
**Összerakva:**

<p align="center">
    
   <img width="70%" height="70%" src="https://github.com/user-attachments/assets/15593e3a-5bcb-46b6-b51c-f8c2e971daff">
    
  </p>
  
**Oscilloscope:**

<p align="center">
    
   <img width="50%" height="50%" src="https://github.com/user-attachments/assets/e8c28c88-d6a3-4f19-9b6b-bc8c59593ee5">
    
  </p>
  
**Generátor:**
<p align="center">
    
   <img width="50%" height="50%" src="https://github.com/user-attachments/assets/adf93eb9-c190-482b-b2c4-08f5f5d2fcbf">
    
  </p>
  

</details>
