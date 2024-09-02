# Kali-and-Metasploitable2
Reference:
https://docs.rapid7.com/metasploit/metasploitable-2/
https://www.kali.org/get-kali/#kali-virtual-machines

1. Information Gathering - All open ports running on the host

![image11](https://github.com/user-attachments/assets/be785558-69d3-4774-bdbc-50d14b3f5d8a)

2. Scanning - All running services and version on these ports

![image2](https://github.com/user-attachments/assets/e51dac11-73a4-493a-bc01-27ce924439ca)

3. Vulnerability - One public exploit is postgresql.
   PostgreSQL DB 8.3.0 - 8.3.7 Has public exploits
   
![image6](https://github.com/user-attachments/assets/ef0893b4-5a89-48ee-8af6-91660699cb10)

  One of the Vulnerabilities in the machine which has CVSS v3 score greater than 9
  map -sV --script vulners --script-args mincvss=9.0 10.0.0.23
  CVE-2013-1903    10.0    https://vulners.com/cve/CVE-2013-1903 Has a score of over 9 

![image9](https://github.com/user-attachments/assets/a938d76a-a431-45f9-b5dd-dff534b1eb52)

![image7](https://github.com/user-attachments/assets/78d70981-9066-4bba-97a7-59774ca54968)

![image3](https://github.com/user-attachments/assets/16b64fd9-cc56-4e67-8e6a-924a382da1e3)

4. Exploitation and Privilege Escalation - Create a user (with your name) in this machine that has a root privilege

![image5](https://github.com/user-attachments/assets/df67ee74-39de-4a91-a40b-43f7de6d9e34)

![image1](https://github.com/user-attachments/assets/3c650ba1-e2e0-422b-a0a6-f0f6346c9959)

5. Disclosure - Enumerate all the users in this machine and their corresponding hashed passwords

![image8](https://github.com/user-attachments/assets/7eb1b358-9f8d-4d82-b78e-fcf6ae066498)

