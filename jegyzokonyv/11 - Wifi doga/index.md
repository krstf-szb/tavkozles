
# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** Szabó Kristóf 

**A mérés tárgya:** Wifi hálózat építése

**A mérés száma:**  11

**A mérés dátuma:** 2025. 02. 06.

**A mérést vezette:** Csontos Dénes 

**Évfolyam:** 13. E

**Csoport:** GYAK 2

**Helyszín:** Fizikai labor

---

## 1. Feladat célja

Wifi hálózat kiépítése, konfigurálása, tesztelése és dokumentációja

---

## 2. Alkalmazott eszközök és készülékek

| Gyártó                | Típus                  |
| --------------------- | ---------------------- |
| Tenda                 | W268R router           |
| Cisco                 | Catalyst 2950 switch   |
| HP                    | ProBook 450 G7 laptop  |
| Samsung               | Galaxy Z Flip4 telefon |

---

## 3. Topológia

![topologia](https://github.com/user-attachments/assets/0ff3781e-2c88-4cdc-9d68-35ef041514a2)

---

## 4. Hálózat kiépítés menete

- Topológia kialakítása

- Router Konfigurálása

- Eszközök csatlakoztatása a vezeték nélküli hálózathoz

- Tesztelés

---

## 5. Router beállítása
<details>
      
<summary> DHCP beállítása </summary>

**A DHCP a 192.168.1.192/26 tartomány első 10 IP címét osztja ki. (192.168.1.193-202)**

![dhcp](https://github.com/user-attachments/assets/fea3b8bc-5616-48cc-9677-766e511a81e5)

</details>

---

<details>

<summary> LAN adapter beállítása </summary>

**A router statikusan kapja a 192.168.1.254 IP címet**

![lan](https://github.com/user-attachments/assets/cb03bc48-9f1b-43e8-ad84-f6b5b7baa3c2)

</details>

---

<details>

<summary> Vezetéknélküli elérés beállítása </summary>

**A vezetéknélküli eléréshez a router SSID-je: vendeg1**
         
![ssid](https://github.com/user-attachments/assets/42b36634-058b-489f-9bc4-96d583d59e04)

</details>

---
 
<details>
                        
<summary> Vezetéknélküli biztonság beállítása </summary>

**A vezetéknélküli elérés védelméhez WPA2-PSK lett állítva AES algoritmussal.
A jelszó:abcd12341.**

![wirelesssec](https://github.com/user-attachments/assets/dfc3bf66-7b89-4855-b2fc-c1c98e56e217)

</details>
                        
---

## 6. Vezetékes hálózat tesztelése

<details>
  
<summary>Laptop IP beállítások</summary>

**IP lekérés:**

![ipkeres](https://github.com/user-attachments/assets/da740052-c07c-49fe-912e-18183ccde06c)

---

**IP eldobás:**

![ipeldobas](https://github.com/user-attachments/assets/e3deb20a-bd84-4f43-9535-a1442b408923)

---

**IP újrakérés:**

![ipujra](https://github.com/user-attachments/assets/cbeaa007-8e1a-4ed9-a1dd-6c8bf31c991a)

</details>

---

<details>
  
<summary>Laptop routing tábla</summary>

**IPv4**

![ipv4routing](https://github.com/user-attachments/assets/6605767e-bf1b-47d3-9989-1232683cb22b)

---

**IPv6**

![ipv6routing](https://github.com/user-attachments/assets/76fb6da6-438c-40eb-b14c-bb60a2171ce7)


</details>

---

<details>
  
<summary>Szerverek elérése</summary>

**Microsoft ping**

![microsoftping](https://github.com/user-attachments/assets/d5f3b25e-b59b-454d-b2e2-92047a011dd8)

---

**Ipon tracert**

![ipontrace](https://github.com/user-attachments/assets/d88dd51f-ffbf-4fd2-9954-7b2e539206c9)


</details>

---

<details>
  
<summary>Portok/Hálózati kapcsolatok</summary>

**Használt portok listája**

<details>
    
C:\WINDOWS\system32>netstat -a

Active Connections

  Proto  Local Address          Foreign Address        State
  
  TCP    0.0.0.0:135            Fizikai-01:0           LISTENING
  
  TCP    0.0.0.0:445            Fizikai-01:0           LISTENING
  
  TCP    0.0.0.0:5040           Fizikai-01:0           LISTENING
  
  TCP    0.0.0.0:5357           Fizikai-01:0           LISTENING
  
  TCP    0.0.0.0:7680           Fizikai-01:0           LISTENING
  
  TCP    0.0.0.0:11100          Fizikai-01:0           LISTENING
  
  TCP    0.0.0.0:49664          Fizikai-01:0           LISTENING
  
  TCP    0.0.0.0:49665          Fizikai-01:0           LISTENING
  
  TCP    0.0.0.0:49666          Fizikai-01:0           LISTENING
  
  TCP    0.0.0.0:49667          Fizikai-01:0           LISTENING
  
  TCP    0.0.0.0:49668          Fizikai-01:0           LISTENING
  
  TCP    0.0.0.0:49669          Fizikai-01:0           LISTENING
  
  TCP    0.0.0.0:49671          Fizikai-01:0           LISTENING
  
  TCP    127.0.0.1:11200        Fizikai-01:0           LISTENING
  
  TCP    127.0.0.1:11300        Fizikai-01:0           LISTENING
  
  TCP    127.0.0.1:11300        Fizikai-01:62916       ESTABLISHED
  
  TCP    127.0.0.1:62916        Fizikai-01:11300       ESTABLISHED
  
  TCP    192.168.1.193:139      Fizikai-01:0           LISTENING
  
  TCP    192.168.1.193:54743    20.199.120.151:https   ESTABLISHED
  
  TCP    192.168.1.193:57645    bud02s33-in-f10:https  TIME_WAIT
  
  TCP    192.168.1.193:57646    bud02s43-in-f14:https  TIME_WAIT
  
  TCP    192.168.1.193:57647    Festo-04:ms-do         ESTABLISHED
  
  TCP    192.168.1.193:57650    bud02s41-in-f14:https  TIME_WAIT
  
  TCP    192.168.1.193:57675    bud02s43-in-f10:https  ESTABLISHED
  
  TCP    192.168.1.193:57676    bud02s43-in-f10:https  ESTABLISHED
  
  TCP    192.168.1.193:57678    bud02s34-in-f3:https   ESTABLISHED
  
  TCP    192.168.1.193:57683    bud02s39-in-f10:https  ESTABLISHED
  
  TCP    192.168.1.193:57684    LenovoSRV:epmap        TIME_WAIT
  
  TCP    192.168.1.193:57685    LenovoSRV:49668        TIME_WAIT
  
  TCP    192.168.1.193:57686    204.79.197.239:https   ESTABLISHED
  
  TCP    192.168.1.193:57690    bud02s34-in-f10:https  ESTABLISHED
  
  TCP    192.168.1.193:57691    FujitsuSRV:microsoft-ds  ESTABLISHED
  
  TCP    192.168.1.193:57692    Degem-01:ms-do         SYN_SENT
  
  TCP    192.168.1.193:63127    bud02s34-in-f3:https   ESTABLISHED
  
  TCP    192.168.1.193:63132    ham02s13-in-f10:https  ESTABLISHED
  
  TCP    192.168.1.193:63133    ham02s13-in-f10:https  ESTABLISHED
  
  TCP    192.168.1.193:63143    a23-40-158-218:http    ESTABLISHED
  
  TCP    192.168.1.193:63196    ham02s13-in-f10:https  TIME_WAIT
  
  TCP    192.168.56.1:139       Fizikai-01:0           LISTENING
  
  TCP    [::]:135               Fizikai-01:0           LISTENING
  
  TCP    [::]:445               Fizikai-01:0           LISTENING
  
  TCP    [::]:5357              Fizikai-01:0           LISTENING
  
  TCP    [::]:7680              Fizikai-01:0           LISTENING
  
  TCP    [::]:11100             Fizikai-01:0           LISTENING
  
  TCP    [::]:49664             Fizikai-01:0           LISTENING
  
  TCP    [::]:49665             Fizikai-01:0           LISTENING
  
  TCP    [::]:49666             Fizikai-01:0           LISTENING
  
  TCP    [::]:49667             Fizikai-01:0           LISTENING
  
  TCP    [::]:49668             Fizikai-01:0           LISTENING
  
  TCP    [::]:49669             Fizikai-01:0           LISTENING
  
  TCP    [::]:49671             Fizikai-01:0           LISTENING
  
  TCP    [::1]:49670            Fizikai-01:0           LISTENING
  
  UDP    0.0.0.0:123            *:*
  
  UDP    0.0.0.0:3702           *:*
  
  UDP    0.0.0.0:3702           *:*
  
  UDP    0.0.0.0:5050           *:*
  
  UDP    0.0.0.0:5353           *:*
  
  UDP    0.0.0.0:5353           *:*
  
  UDP    0.0.0.0:5353           *:*
  
  UDP    0.0.0.0:5353           *:*
  
  UDP    0.0.0.0:5353           *:*
  
  UDP    0.0.0.0:5353           *:*
  
  UDP    0.0.0.0:5353           *:*
  
  UDP    0.0.0.0:5353           *:*
  
  UDP    0.0.0.0:5353           *:*
  
  UDP    0.0.0.0:5355           *:*
  
  UDP    0.0.0.0:54632          *:*
  
  UDP    127.0.0.1:1900         *:*
  
  UDP    127.0.0.1:49557        *:*
  
  UDP    127.0.0.1:50801        *:*
  
  UDP    127.0.0.1:58989        *:*
  
  UDP    127.0.0.1:62204        *:*
  
  UDP    192.168.1.193:137      *:*
  
  UDP    192.168.1.193:138      *:*
  
  UDP    192.168.1.193:1900     *:*
  
  UDP    192.168.1.193:2177     *:*
  
  UDP    192.168.1.193:49556    *:*
  
  UDP    192.168.56.1:137       *:*
  
  UDP    192.168.56.1:138       *:*
  
  UDP    192.168.56.1:1900      *:*
  
  UDP    192.168.56.1:2177      *:*
  
  UDP    192.168.56.1:49555     *:*
  
  UDP    [::]:123               *:*
  
  UDP    [::]:3702              *:*
  
  UDP    [::]:3702              *:*
  
  UDP    [::]:5353              *:*
  
  UDP    [::]:5353              *:*
  
  UDP    [::]:5353              *:*
  
  UDP    [::]:5353              *:*
  
  UDP    [::]:5353              *:*
  
  UDP    [::]:5355              *:*
  
  UDP    [::]:54633             *:*
  
  UDP    [::1]:1900             *:*
  
  UDP    [::1]:49554            *:*
  
  UDP    [fe80::1567:1f37:caa:4843%20]:1900  *:*
  
  UDP    [fe80::1567:1f37:caa:4843%20]:2177  *:*
  
  UDP    [fe80::1567:1f37:caa:4843%20]:49552  *:*
  
  UDP    [fe80::cf02:9cb2:81bb:f03a%16]:1900  *:*
  
  UDP    [fe80::cf02:9cb2:81bb:f03a%16]:2177  *:*
  
  UDP    [fe80::cf02:9cb2:81bb:f03a%16]:49553  *:*

</details>

**Hálózati kapcsolatok**

![halozatikapcs](https://github.com/user-attachments/assets/3817051c-a162-40d9-b268-ee46980c6567)

---

<details>
  
  <summary>DNS beállítások aktualizálása</summary>

**DNS flush**

![flushdns](https://github.com/user-attachments/assets/29bffa03-bcb2-43de-beab-fbd4513848c4)

</details>

---

<details>
  
  <summary>Hálózati meghajtók</summary>

**Csatolt hálózati meghajtók listája**

![netuse](https://github.com/user-attachments/assets/9d349659-fbe7-4dbe-b620-0cd130c004a8)

</details>

---

<details>
  
  <summary>Ipon szerver</summary>

**Az Ipon szerver tartománynevének és IP címének lekérése**

![nslookup](https://github.com/user-attachments/assets/f744a2a8-9c35-45cd-9639-40cfcc0d959d)
  
</details>

---

<details>
  
  <summary>FQDN</summary>

**FQDN megjelenítése**

![netstat-f](https://github.com/user-attachments/assets/57e7caac-fc80-4326-9e8e-63918e55b57e)

</details>

</details>

---

## 7. Vezetéknélküli hálózat tesztelése

<details>
  
  <summary>Ping</summary>

  **Ping a laptopról a telefonra**

  ![pingtelefonra](https://github.com/user-attachments/assets/63bef912-4244-4f08-8218-f57692fb555b)

</details>

---

<details>
  
  <summary>WiFi tesztelés</summary>

  **WiFi analyzer (vendeg01)**
  
  ![Screenshot_20250206_102530_WiFi Analyzer](https://github.com/user-attachments/assets/8c9b5690-0077-4bd2-b4ca-047ba6dbae26)

  ---

**Internet sebesség teszt**

![Screenshot_20250206_102926_Chrome](https://github.com/user-attachments/assets/0d8e7fba-7218-4c6d-ab3a-f600cd51675b)
  
</details>

---
