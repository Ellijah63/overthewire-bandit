# overthewire-bandit
overthewire bandit progress

level1: 6y2kwnwK6grgvwvpvLaa2T1cpFEKOhNR

level2: PK8fYLZg2hnHSz83plBL1iEPKdD3QToB

level3: 7ZZ2LFrykP2zEyvBl4m3clcL7tGYJPME

level4: xzTXq1rDJQVVAzdv5cHq1TQytTWufAMq

level5: 6C7h9GD8M6ai5nr7wo1RonrzFjj9yIrG

level6: pXa26xhMWaC2SvDotA4r9EgZkulOeSBW

level7: Bmnnvf82KzQlfxgAI2d1zYbr1u9pr3E3

level8: VR1ljMayciFxbnUokuQmJFw6QC9VKtub

### LEVEL 9: 
<details>
  <summary>CODE</summary>
  
  ```EjmOSvuAu7sGAHqHVcBDPirRe9T03kxl```
</details>
<details>
  <summary>SOLUTION</summary>
  
  ```strings data.txt | grep -i "==="```
</details>

### LEVEL 10:
<details>
  <summary>CODE</summary>
  
  ```B0s2khmbT9u0geKuOoVGW3JZKhndE3BG```
</details>
<details>
  <summary>SOLUTION</summary>
  
  ```base64 -d data.txt```
</details>

### LEVEL 11: 
<details>
  <summary>CODE</summary>
  
  ```pYfOY6HwUsDj5rL9UvyhU7MCmv8vN5Ro```
</details>
<details>
  <summary>SOLUTION</summary>
  
  ```tr 'A-Za-z' 'N-ZA-Mn-za-m' < data.txt```
</details>

### LEVEL 12:
<details>
  <summary>CODE</summary>
  
  ```GROozWPO8QyN0mGrjUkID0WCYkZiQxrN```
</details>
<details>
  <summary>SOLUTION</summary>
  
  ```
   xxd -r
   tar
   gzip
   bzip2
  ```
</details>

### LEVEL 13:
<details>
  <summary>CODE</summary>
  
  ```qQYQiHOBPR8zR61qxYqX45quvihF2uzk```
</details>
<details>
  <summary>SOLUTION</summary>
  
  ```
  Take private key from bandit and make private key file on host. Assign minimal privilege and attach it to ssh.
  Can not ssh from bandit server has ssh from localhost to localhost has been disabled.
  chmod 600 bandit14_sshkey.private 
  ssh -i bandit14_sshkey.private -p 2220 bandit14@bandit.labs.overthewire.org
  ```
</details>

### LEVEL 14:
<details>
  <summary>CODE</summary>
  
  ```
  ssh -i bandit14_sshkey.private -p 2220 bandit14@bandit.labs.overthewire.org
  <br>
  aaWecNkG4FhxJQxz07uiwzVP6bJiYS65
  ```
</details>
<details>
  <summary>SOLUTION</summary>
  
  ``` ```
</details>


<br>

<details>
  <summary>CODE</summary>
  
  ``` ```
</details>
<details>
  <summary>SOLUTION</summary>
  
  ``` ```
</details>
