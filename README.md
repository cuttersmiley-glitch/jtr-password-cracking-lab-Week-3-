# jtr-password-cracking-lab-Week-3-
Cybersecurity lab demonstrating password recovery of an authorized protected PDF using John the Ripper (JTR) and Johnny.

PROJECT MODULE 1

Crack the password of attached PDF file (My Locked PDF1.pdf) using JTR
JOHN and JTR JOHNNY tools on your Windows PC.

Download John the Ripper from official website on your windows PC:
https://www.openwall.com/john/
or https://distro.ibiblio.org/openwall/projects/john/1.9.0/

Download Johnny GUI from official website:
https://openwall.info/wiki/john/johnny
OPEN JOHNY
<img width="1600" height="340" alt="image" src="https://github.com/user-attachments/assets/37deb4a2-1182-4856-a823-06caf84ebc9b" />
Then go to your files and upload this file below as shown : john.exe
<img width="1600" height="891" alt="image" src="https://github.com/user-attachments/assets/c3deb80e-8af7-495f-ad78-b526070392d3" />

Then download encrypted PDF file from your pc
[My Locked PDF1.pdf](https://github.com/user-attachments/files/31864129/My.Locked.PDF1.pdf)

Open the hash website & upload your pdf file to find its hash:
https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php
Then upload that pdf
<img width="1600" height="779" alt="image" src="https://github.com/user-attachments/assets/553e7f05-98f3-49a6-96de-36a7dcaa41c1" />

After that copy that code below it
<img width="1600" height="904" alt="image" src="https://github.com/user-attachments/assets/7fdde967-5e21-4d10-af3b-dca9267e82f1" />

Paste the hash value inside notepad. save the text file

Open Johnny again:
Click on ‘Open password file’:

Browse to the .txt file that you have just saved & click on Open. Then Click on ‘Start new attack’
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/4202d834-971e-40cf-8fa3-ab42af208505" />

FROM THAT POINT WE WILL HAVE FOUND THE PASSWORD OF THE ENCRYPTED PDF. NEXT IS TO OPEN USING THAT PASSWORD DISPLAYING THERE(good-luck). Results will display this below
<img width="1600" height="890" alt="image" src="https://github.com/user-attachments/assets/c1d7e77a-aa6d-4359-8e8b-3765c700a114" />


PROJECT MODULE 2



Crack the password of the attached PDF file (My Locked PDF1.pdf) using the
Networkwalks Hash Calculator and Password Cracker tools on your Windows
laptop.
Download the encrypted PDF file (My Locked PDF1.pdf) to your laptop from the lab page:
https://networkwalks.com/project-task-lab-password-cracking-with-networkwalks-tools/

Open the Networkwalks Hash Calculator in your web browser:
https://networkwalks.com/hash-calculator/

<img width="1600" height="909" alt="image" src="https://github.com/user-attachments/assets/e87e2ced-783a-4e9e-8218-b7ca75700ebd" />

Upload the locked PDF file to the Hash Calculator. The tool will read the file and give you the hash
value that starts with $pdf$...
Copy the full hash value.

<img width="1600" height="890" alt="image" src="https://github.com/user-attachments/assets/a78a1f4d-f0fe-481a-a189-3bc8085db5aa" />

Open the Networkwalks Password Cracker in your web browser:
https://networkwalks.com/password-cracker/

<img width="1600" height="902" alt="image" src="https://github.com/user-attachments/assets/ac4e3d81-2ee6-4db5-ae6b-bec76aeff1b9" />

Paste the hash value into the Password Cracker and start the attack. The tool will try different
passwords until it finds a match

<img width="1600" height="921" alt="image" src="https://github.com/user-attachments/assets/69b56587-bc03-4f0a-aa4d-1c7d41639647" />

Wait for the tool to finish. The cracked password will be shown on the screen.

<img width="1600" height="904" alt="image" src="https://github.com/user-attachments/assets/ea803381-39b9-4f0a-97c4-f2b533d4a217" />

Open the locked PDF file and enter the cracked password.Then enter password you get. it will display this results
![Uploading image.png…]()


