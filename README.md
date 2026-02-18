<div align="center">

<img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExY2V0amtucHc0cjU0MG9vOGR3c2dvam9hdzd3ZXQ1bjM0bzN4bHp1cSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/8fRwPZtbWkkX6/giphy.gif" width="100%" alt="hacker typing" />

</div>

<div align="center">

```
  ███████╗ █████╗ ███╗   ██╗████████╗ █████╗  ██████╗██████╗
  ██╔════╝██╔══██╗████╗  ██║╚══██╔══╝██╔══██╗██╔════╝██╔══██╗
  ███████╗███████║██╔██╗ ██║   ██║   ███████║██║     ██████╔╝    
  ╚════██║██╔══██║██║╚██╗██║   ██║   ██╔══██║██║     ██╔══██╗   
  ███████║██║  ██║██║ ╚████║   ██║   ██║  ██║╚██████╗██║  ██║   
  ╚══════╝╚═╝  ╚═╝╚═╝  ╚═══╝   ╚═╝   ╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝  
```

</div>

<div align="center">

```ascii
╔═════════════════════════════════════════════════════════════════════════════════╗
║   > SYSTEM BREACH DETECTED   > ACCESS GRANTED: INFINITYPAIIN  > CREW: ch0wn3rs  ║
╚═════════════════════════════════════════════════════════════════════════════════╝
```

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=00FF41&center=true&vCenter=true&width=620&lines=Welcome+to+the+Matrix...;Pwn+%7C+Reversing+%26+Assembly+%E2%80%A2+ch0wn3rs;Always+Hunting+for+Zero-Days.)](https://git.io/typing-svg)

<img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExbTM3czZ1dmdoaDViamFsN3kxOTVwb2Y3cmdvY2l6cm5icmxxYmFjaSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/dLolp8dtrYCJi/giphy.gif" width="320" alt="matrix" />

</div>

---

## 👾 `whoami`

```bash
santacrz@matrix:~$ cat /etc/shadow | grep santacrz
> TARGET: INFINITYPAIIN  |  CREW: ch0wn3rs  |  STATUS: [ ACTIVE ]
```

```javascript
class CyberWarrior {
    constructor() {
        this.username = "SanTacrZ";
        this.handle = "INFINITYPAIIN";
        this.role = "Pwn · Reversing · Assembly specialist";
        this.crew = "ch0wn3rs";
        this.arsenal = ["GDB", "radare2", "Ghidra", "ASM", "C", "Python"];
        this.stack = ["Django", "React", "Next.js", "Finance agents (C)"];
    }
    getCurrentStatus() { return "root@santacrz:~# sudo su -"; }
}
```

---

## 🔶 `LIVE SCRIPT` // decode

<div align="center">

<table>
<tr>
<td align="center" style="border: 2px solid #00FF41; border-radius: 4px; padding: 18px; background: #0D0D0D; box-shadow: 0 0 20px rgba(0,255,65,0.2);">

**$ ./decode --target binary**

<pre style="color:#00FF41; font-family: monospace; font-size: 13px; margin: 0;">
<span style="color:#6a9955;">[ SCAN ] Loading target...</span>
<span style="color:#00FF41;">[ BREACH ] Entry point: 0x00401000</span>
<span style="color:#00FF41;">[ UPLOAD ] Sections: .text .data .plt.got</span>
<span style="color:#6a9955;">[ SCAN ] Disassembling main...</span>
<span style="color:#00cc33;">[ CRITICAL ] FLAG decoder at 0x00401234</span>
<span style="color:#00FF41;">[ EXECUTE ] Exploit chain running...</span>
<span style="color:#00FF41;">[ DONE ] Access granted. Flag captured.</span>
</pre>

</td>
</tr>
</table>

</div>

---

## 🟢 `DISASSEMBLY` // x86-64

<div>

<table width="100%" style="border-collapse: collapse; border: 2px solid #00FF41; border-radius: 4px;">
<tr style="background: #0D0D0D;">
<td style="border: 1px solid #00FF41; padding: 12px; color: #00FF41; font-family: monospace; font-size: 12px;">; INFINITYPAIIN · Reversing specialist · matrix</td>
</tr>
<tr style="background: #0D0D0D;">
<td style="border: 1px solid #00FF41; padding: 12px; font-family: monospace; font-size: 12px;">
<pre style="margin:0;">
<span style="color:#6a9955;">   0x00401234</span>  <span style="color:#00FF41;">push   rbp</span>
<span style="color:#6a9955;">   0x00401235</span>  <span style="color:#00FF41;">mov    rbp, rsp</span>
<span style="color:#6a9955;">   0x00401238</span>  <span style="color:#00FF41;">sub    rsp, 0x20</span>
<span style="color:#6a9955;">   0x0040123c</span>  <span style="color:#00FF41;">mov    rax, qword [obj.flag]</span>
<span style="color:#6a9955;">   0x00401243</span>  <span style="color:#00FF41;">mov    rdi, rax</span>
<span style="color:#6a9955;">   0x00401246</span>  <span style="color:#00cc33;">call   sym.imp.decode</span>
<span style="color:#6a9955;">   0x0040124b</span>  <span style="color:#00FF41;">mov    eax, 0</span>
<span style="color:#6a9955;">   0x00401250</span>  <span style="color:#00FF41;">leave</span>
<span style="color:#6a9955;">   0x00401251</span>  <span style="color:#00FF41;">ret</span>
</pre>
</td>
</tr>
</table>

</div>

---

## ⚡ `ARSENAL` // LOADED MODULES

```bash
santacrz@matrix:~$ ls -la /opt/arsenal/
```

<table width="100%">
<tr>
<td width="50%" style="vertical-align: top;">

<div style="border: 2px solid #00cc33; border-radius: 4px; padding: 14px; background: #0D0D0D;">

**<span style="color:#00FF41;">OFFENSIVE · REVERSING · ASM</span>**

<pre style="font-size: 12px; margin: 0;">
<span style="color:#00FF41;">[████████████████████░]</span> <span style="color:#00FF41;">Pwn ...................... 95%</span>
<span style="color:#00FF41;">[████████████████████░]</span> <span style="color:#00cc33;">Reversing ................ 92%</span> ◀ specialist
<span style="color:#00FF41;">[████████████████████░]</span> <span style="color:#00cc33;">Assembly (x86/ARM) ........ 90%</span> ◀ specialist
<span style="color:#00FF41;">[████████████████████░]</span> <span style="color:#00FF41;">C ........................ 90%</span>
<span style="color:#00FF41;">[██████████████████░░░]</span> <span style="color:#00FF41;">GDB / radare2 / Ghidra .... 88%</span>
<span style="color:#00FF41;">[██████████████████░░░]</span> <span style="color:#00FF41;">Exploit dev .............. 85%</span>
<span style="color:#00FF41;">[██████████████████░░░]</span> <span style="color:#00FF41;">Bash ..................... 85%</span>
</pre>

</div>

</td>
<td width="50%" style="vertical-align: top;">

<div style="border: 2px solid #00FF41; border-radius: 4px; padding: 14px; background: #0D0D0D;">

**<span style="color:#00FF41;">WEB & BACKEND</span>**

<pre style="font-size: 12px; margin: 0;">
<span style="color:#00FF41;">[██████████████████░░░]</span> <span style="color:#00FF41;">Python ................... 88%</span>
<span style="color:#00FF41;">[████████████████░░░░░]</span> <span style="color:#00FF41;">Django ................... 80%</span>
<span style="color:#00FF41;">[██████████████████░░░]</span> <span style="color:#00FF41;">React / Next.js .......... 82%</span>
<span style="color:#00FF41;">[████████████████░░░░░]</span> <span style="color:#00FF41;">Node.js .................. 75%</span>
<span style="color:#00FF41;">[██████████████████░░░]</span> <span style="color:#00FF41;">PostgreSQL ................ 85%</span>
<span style="color:#00FF41;">[████████████████░░░░░]</span> <span style="color:#00FF41;">Java ..................... 78%</span>
</pre>

</div>

</td>
</tr>
</table>

<div align="center">

**<span style="color:#00FF41;">TOOLCHAIN</span>** <span style="color:#6a9955;">//</span>  
`ASM` `C` `Python` `GDB` `radare2` `Ghidra` `Django` `React` `Next.js` `PostgreSQL` `Docker` `Kali`

</div>

---

## 🏴‍☠️ `CTF SQUAD` // ch0wn3rs

```bash
santacrz@matrix:~$ grep -r "FLAG" /var/log/ctf/
```

<div align="center">

<img src="https://media.giphy.com/media/3o7btPCcdNniyf0ArS/giphy.gif" width="320" alt="access" />

**<span style="color:#00FF41;">ch0wn3rs</span>** <span style="color:#6a9955;">//</span> *Elite Cybersecurity Club*

[![CTFtime](https://img.shields.io/badge/CTFtime-Ch0wn3rs_%23408704-00ff41?style=for-the-badge&labelColor=0d1117)](https://ctftime.org/team/408704)
[![Website](https://img.shields.io/badge/Website-ch0wn3rs.ninja-00ff41?style=for-the-badge&labelColor=0d1117)](https://ch0wn3rs.ninja/)
<a href="https://ctftime.org/team/408704/"><img src="https://ctftime.org/static/img/s/32x32.png" width="28" height="28" alt="CTFtime"/></a>

</div>

<div style="border: 2px solid #00FF41; border-radius: 4px; padding: 14px; background: #0D0D0D;">

```
                      ┌─────────────────────────────────────────────────────────────────┐
                      │ CREW STATUS .................................................   │
                      ├─────────────────────────────────────────────────────────────────┤
                      │ 2026  Overall: #65  │  45.925 pts  │  Country: #1               │
                      │ Gigs: Nullcon Goa HackIM 2026 (#12) · PascalCTF 2026 (#63)     │
                      ├─────────────────────────────────────────────────────────────────┤
                      │ ROSTER: Fu11shoot · 02loveslollipop · Neyi21 · hrcamilo11 ·    │
                      │         INFINITYPAIIN (Pwn / Reversing · Assembly)              │
                      └─────────────────────────────────────────────────────────────────┘
```

</div>

<div align="center">

[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/SanTacrZ)
[![HackTheBox](https://img.shields.io/badge/HackTheBox-9FEF00?style=flat-square&logo=hackthebox&logoColor=black)](https://app.hackthebox.com/profile/SanTacrZ)

</div>

---

## 📊 `SYSTEM METRICS`

```bash
santacrz@matrix:~$ cat /proc/github_stats
```

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=SanTacrZ&show_icons=true&theme=dark&bg_color=0d1117&title_color=00ff41&text_color=00ff41&icon_color=00ff41&border_color=00ff41&hide_border=true" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=SanTacrZ&theme=dark&background=0d1117&ring=00ff41&fire=00ff41&currStreakLabel=00ff41&border=00ff41&currStreakNum=00ff41&sideNums=00ff41&sideLabels=00ff41&dates=00ff41&hide_border=true" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SanTacrZ&layout=compact&theme=dark&bg_color=0d1117&title_color=00ff41&text_color=00ff41&border_color=00ff41&hide_border=true" />

</div>

---

## 💀 `ACTIVE PROJECTS`

```bash
santacrz@matrix:~$ ps aux | grep santacrz
```

<table style="border: 2px solid #00FF41; border-radius: 4px; border-collapse: collapse;">
<tr style="background: #0D0D0D;">
<td style="border: 1px solid #00FF41; padding: 10px 14px; color: #00FF41; font-weight: bold;">PID</td>
<td style="border: 1px solid #00FF41; padding: 10px 14px; color: #00FF41; font-weight: bold;">PROJECT</td>
<td style="border: 1px solid #00FF41; padding: 10px 14px; color: #00FF41;">STATUS</td>
</tr>
<tr style="background: #0D0D0D;">
<td style="border: 1px solid #00FF41; padding: 8px 14px; color: #00cc33;">1337</td>
<td style="border: 1px solid #00FF41; padding: 8px 14px; color: #00FF41;">Pwn & Reversing (ASM)</td>
<td style="border: 1px solid #00FF41; padding: 8px 14px; color: #00FF41;">ACTIVE</td>
</tr>
<tr style="background: #0D0D0D;">
<td style="border: 1px solid #00FF41; padding: 8px 14px; color: #00cc33;">31337</td>
<td style="border: 1px solid #00FF41; padding: 8px 14px; color: #00FF41;">CTF · ch0wn3rs</td>
<td style="border: 1px solid #00FF41; padding: 8px 14px; color: #00FF41;">ACTIVE</td>
</tr>
<tr style="background: #0D0D0D;">
<td style="border: 1px solid #00FF41; padding: 8px 14px; color: #00cc33;">8080</td>
<td style="border: 1px solid #00FF41; padding: 8px 14px; color: #00FF41;">Django + React / Next</td>
<td style="border: 1px solid #00FF41; padding: 8px 14px; color: #00FF41;">ACTIVE</td>
</tr>
<tr style="background: #0D0D0D;">
<td style="border: 1px solid #00FF41; padding: 8px 14px; color: #00cc33;">9000</td>
<td style="border: 1px solid #00FF41; padding: 8px 14px; color: #00FF41;">Finance agents (C)</td>
<td style="border: 1px solid #00FF41; padding: 8px 14px; color: #00FF41;">ACTIVE</td>
</tr>
</table>

---

## 🌐 `NETWORK CONNECTIONS`

```bash
santacrz@matrix:~$ netstat -tuln | grep ESTABLISHED
```

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sebastian-santacruz-060227113)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SanTacrZ)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tu@email.com)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/tu-servidor)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/SanTacrZ)

</div>

---

## 🎯 `PHILOSOPHY`

```python
#!/usr/bin/env python3
class HackerMindset:
    def __init__(self):
        self.principles = [
            "Break it before someone else does",
            "Security through obscurity is no security",
            "We are the glitch in the system"
        ]
    def get_motto(self):
        return "root@matrix:~# echo 'The code is the law'"
```

> **<span style="color:#00FF41;">"In a world of 1s and 0s, we are the exception handlers."</span>**  
> <span style="color:#00FF41;">— SanTacrZ / INFINITYPAIIN</span>

---

## 🔥 `CONTRIBUTION GRAPH`

<div align="center">

```bash
santacrz@matrix:~$ git log --graph --oneline --all
```

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=SanTacrZ&theme=github-dark&bg_color=0d1117&color=00ff41&line=00ff41&point=00ff41&area=true&hide_border=true)

</div>

---

## 🚨 `SECURITY NOTICE`

<div style="border: 2px solid #00FF41; border-radius: 4px; padding: 16px; background: #0D0D0D;">

<pre style="margin:0; color:#00FF41;">
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃  ⚠️  WARNING: AUTHORIZED PERSONNEL ONLY             ┃
┃  This profile contains classified intel.           ┃
┃  Unauthorized access → pull request. You're cool.  ┃
┃  Want to collaborate? Hit me up. 🤝                ┃
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
</pre>

</div>

<div align="center">

**Thanks for visiting. Stay curious, stay ethical, stay pwning.**

**ch0wn3rs** · [ch0wn3rs.ninja](https://ch0wn3rs.ninja/) · [CTFtime](https://ctftime.org/team/408704)

![Profile Views](https://komarev.com/ghpvc/?username=SanTacrZ&color=00ff41&style=flat-square)

</div>

<div align="center">

<img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExbTM3czZ1dmdoaDViamFsN3kxOTVwb2Y3cmdvY2l6cm5icmxxYmFjaSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/dLolp8dtrYCJi/giphy.gif" width="100%" alt="matrix" />

</div>
