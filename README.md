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

<img width="1600" height="909" alt="WhatsApp Image 2026-09-05 at 3 04 55 PM" src="https://github.com/user-attachments/assets/531f1fb6-9665-4dfa-a0a3-fc134d70cd2a" />


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

<img width="1600" height="890" alt="WhatsApp Image 2026-09-05 at 3 04 55 PM(1)" src="https://github.com/user-attachments/assets/ed5a88ba-580d-481e-9d4a-e30f50bab683" />


PROJECT MODULE 3: HOW TO SETUP HEXSTRIKE MCP SERVER

Setup Hexstrike MCP Server on Kali linux with Claude desktop

Download Claude desktop on Kali Linux using Github:

Github repository & detailed instructions can be found here: https://github.com/aaddrick/claude-desktop-
debian

# Add the GPG key
curl -fsSL https://pkg.claude-desktop-debian.dev/KEY.gpg | sudo gpg --dearmor -o
/usr/share/keyrings/claude-desktop.gpg
# Add the repository
echo "deb [signed-by=/usr/share/keyrings/claude-desktop.gpg arch=amd64,arm64]
https://pkg.claude-desktop-debian.dev stable main" | sudo tee
/etc/apt/sources.list.d/claude-desktop.list

# Update and install
sudo apt update
sudo apt install claude-desktop
<img width="1920" height="1080" alt="Screenshot_2026-09-05_11_29_29" src="https://github.com/user-attachments/assets/676a6a71-8fb4-4b0d-a18b-781a5a9abaf1" />

<img width="1920" height="1080" alt="Screenshot_2026-09-05_11_20_44" src="https://github.com/user-attachments/assets/9c45b9ef-2b6f-4b41-a6fc-8c6665c1eb8b" />


Download Hexstrike MCP
Download Hexstrike MCP on Kali Linux using Github by running below commands.
Github repository & detailed instructions can be found here: https://github.com/0x4m4/hexstrike-ai

# 1. Clone the repository
git clone https://github.com/0x4m4/hexstrike-ai.git
cd hexstrike-ai
# 2. Create virtual environment
python3 -m venv hexstrike-env
source hexstrike-env/bin/activate # Linux/Mac
# 3. Install Python dependencies
pip3 install -r requirements.txt
python3 hexstrike_server.py

<img width="1920" height="1080" alt="Screenshot_2026-09-05_12_30_53" src="https://github.com/user-attachments/assets/b2fe5e59-b1ae-4b6d-a5c4-f3c385d62303" />

Edit MCP Server configuration on claude desktop:
<img width="1920" height="1080" alt="Screenshot_2026-09-05_13_56_54" src="https://github.com/user-attachments/assets/9c33b1fe-089b-4a05-894a-4883856143fd" />
ADD THIS BELOW:
{
"mcpServers": {
"hexstrike-ai": {
"command": "/home/kali/hexstrike-ai/hexstrike-env/bin/python",
"args": [
"/home/kali/hexstrike-ai/hexstrike_mcp.py",
"--server",
"http://localhost:8888"
]
}
}


Server is running now:
<img width="1920" height="1080" alt="Screenshot_2026-09-05_14_37_30" src="https://github.com/user-attachments/assets/463d8313-f171-480a-8c7a-f6d25b70b281" />

<img width="1920" height="1080" alt="Screenshot_2026-09-05_14_43_50" src="https://github.com/user-attachments/assets/9149c94a-51c3-422f-a847-60f2106117a9" />


END
