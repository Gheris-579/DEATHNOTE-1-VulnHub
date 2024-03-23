# DEATHNOTE-1-VulnHub
Level - easy  Description : don't waste too much time thinking outside the box . It is a Straight forward box .  This works better with VirtualBox rather than VMware

<p>netdiscover -u eth0</p>

![Screenshot 2024-03-22 194002](https://github.com/Gheris-579/DEATHNOTE-1-VulnHub/assets/103877241/bd50c87b-ee50-4f1d-bd85-d3d282cf0704)

<p>nmap -sS -sV -sC -p- ip</p>
<ol>
  <li>The -sS option in nmap tells you to perform a stealth scan, that is, a scan in which the software tries not to be detected by the target host.</li>
  <li>The -sV option in nmap tells you to perform a version scan, that is, to try to identify the versions of services that respond to open ports.</li>
  <li>The -sC option in nmap tells you to run a scan script, that is, to use a set of predefined scripts to search for vulnerabilities or other information about running services.</li>
</ol>

![Screenshot 2024-03-22 194247](https://github.com/Gheris-579/DEATHNOTE-1-VulnHub/assets/103877241/de40d3b2-7c62-40a4-bcbc-69b676bbc743)

<p>nano /etc/hosts</p>

![Screenshot 2024-03-22 194610](https://github.com/Gheris-579/DEATHNOTE-1-VulnHub/assets/103877241/25ccb3f2-dad2-4e3e-8bed-f1367d0374f7)

![Screenshot 2024-03-22 194915](https://github.com/Gheris-579/DEATHNOTE-1-VulnHub/assets/103877241/8bb24cc1-ca44-41f6-bd2d-2e84488aea47)


![Screenshot 2024-03-22 195256](https://github.com/Gheris-579/DEATHNOTE-1-VulnHub/assets/103877241/31fa0e66-003e-4cc9-a9f5-dd6f4bea5abb)

<p>this page was created with WordPress.</p>

![Screenshot 2024-03-22 195453](https://github.com/Gheris-579/DEATHNOTE-1-VulnHub/assets/103877241/1a213f8e-7922-44a7-a950-32301ffe8234)

<p>gobuster dir -u http://deathnote.vuln/wordpress/ -w /usr/share/wordlists/Discovery/Web-Content/directory-list-2.3-medium.txt</p>

![Screenshot 2024-03-22 195823](https://github.com/Gheris-579/DEATHNOTE-1-VulnHub/assets/103877241/904ab1b4-463b-4805-856e-8374ac12eab5)

![Screenshot 2024-03-22 200338](https://github.com/Gheris-579/DEATHNOTE-1-VulnHub/assets/103877241/ab8662f6-f682-4483-a56b-65baa252b720)

<p>wpscan --url http://deathnote.vuln/wordpress/ -e u</p>

![Screenshot 2024-03-22 200817](https://github.com/Gheris-579/DEATHNOTE-1-VulnHub/assets/103877241/fabeefba-235e-4615-8f59-e5a9fd46b509)

<p>Password</p>

![7](https://github.com/Gheris-579/DEATHNOTE-1-VulnHub/assets/103877241/0b34962d-aa78-4cd4-a963-4364c8c689ec)


<p>User:kira  pass:iamjustic3</p>

![Screenshot 2024-03-22 201122](https://github.com/Gheris-579/DEATHNOTE-1-VulnHub/assets/103877241/aadcd586-5e17-4546-8bae-7cd7f295dd91)


![Screenshot 2024-03-22 202604](https://github.com/Gheris-579/DEATHNOTE-1-VulnHub/assets/103877241/8df873c2-f174-4984-a9d2-10bef858ec54)


<p>hydra -l l -P note ssh://192.168.56.103</p>

<ol>
  <li>l in username</li>
</ol>

![Screenshot 2024-03-22 203211](https://github.com/Gheris-579/DEATHNOTE-1-VulnHub/assets/103877241/bbf7ca5a-468f-4813-b58d-3c8a030a34ed)
