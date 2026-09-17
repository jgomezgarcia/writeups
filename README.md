<div align="center">

# 🛡️ Writeups — José Gómez García

### Pentesting · Active Directory · Explotación de sistemas

Colección de writeups técnicos de máquinas y salas de ciberseguridad ofensiva, escritos no solo para documentar lo que funcionó, sino el razonamiento detrás de cada decisión y los tropiezos por el camino — lo que de verdad demuestra cómo pienso al enfrentarme a un objetivo nuevo.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jos%C3%A9_G%C3%B3mez_Garc%C3%ADa-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/josegomezgarc%C3%ADa/)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-jgomez7-red?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/jgomez7)
[![HackTheBox](https://img.shields.io/badge/HackTheBox-Profile-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black)](https://profile.hackthebox.com/profile/019fa8db-797f-707e-b730-abe6edb38505)
[![CyberProfile](https://img.shields.io/badge/CyberProfile-josegomezgarcia-6B4EFF?style=for-the-badge&logo=readdotcv&logoColor=white)](https://cyber-profile.com/u/josegomezgarcia)

</div>

---

## 👤 Sobre mí

Estudiante/practicante de ciberseguridad ofensiva, enfocado en pentesting de infraestructura y Active Directory. Resuelvo salas y máquinas de TryHackMe y HackTheBox de forma constante, y documento cada una como si fuera un informe real de pentest: qué se encontró, por qué funcionó el ataque, y qué haría distinto la próxima vez.

Este repositorio es mi cuaderno de campo público — la evidencia de cómo abordo un objetivo desde cero hasta compromiso total, no solo la lista de comandos finales.

## 🛠️ Skills & Herramientas

**Reconocimiento y enumeración**

![Nmap](https://img.shields.io/badge/Nmap-black?style=flat-square&logo=nmap&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Kerbrute](https://img.shields.io/badge/Kerbrute-black?style=flat-square)
![Enum4linux](https://img.shields.io/badge/Enum4linux-black?style=flat-square)

**Active Directory**

![BloodHound](https://img.shields.io/badge/BloodHound-black?style=flat-square)
![Impacket](https://img.shields.io/badge/Impacket-black?style=flat-square)
![CrackMapExec](https://img.shields.io/badge/CrackMapExec%2FNetExec-black?style=flat-square)
![Mimikatz](https://img.shields.io/badge/Mimikatz-black?style=flat-square)
![Evil--WinRM](https://img.shields.io/badge/Evil--WinRM-black?style=flat-square)

**Explotación & post-explotación**

![Metasploit](https://img.shields.io/badge/Metasploit-black?style=flat-square&logo=metasploit&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Hashcat](https://img.shields.io/badge/Hashcat-black?style=flat-square)
![John the Ripper](https://img.shields.io/badge/John%20the%20Ripper-black?style=flat-square)

**Sistemas & scripting**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

## 📚 Índice de writeups

### TryHackMe

| Writeup | Categoría | Técnicas |
|---|---|---|
| [Attacktive Directory](tryhackme/attacktive-directory.md) | Active Directory | Kerbrute, AS-REP Roasting, SMB, Backup Operators / DCSync, Pass-the-Hash |

### HackTheBox

_Próximamente._

## 🗂️ Estructura del repo

```
writeups/
├── tryhackme/          # Writeups de salas de TryHackMe
├── hackthebox/         # Writeups de máquinas de HackTheBox
├── assets/             # Capturas de cada writeup, en una subcarpeta con su mismo nombre
└── TEMPLATE.md         # Plantilla para escribir un writeup nuevo
```

## 📝 Metodología

Cada writeup sigue la misma estructura ([TEMPLATE.md](TEMPLATE.md)):

1. **Reconocimiento** — qué se escaneó y por qué esa huella apunta a un tipo de objetivo concreto.
2. **Explotación paso a paso** — cada comando con el razonamiento detrás, no solo el resultado.
3. **Lo que no sale en la mayoría de writeups** — errores, permisos inesperados o configuraciones que costó entender. Es la parte que más se aprende al releerla meses después, y la que casi nunca se documenta.

## 📬 Contacto

¿Buscas incorporar a alguien con perfil de pentesting/Active Directory a tu equipo? Puedes encontrarme en [LinkedIn](https://www.linkedin.com/in/josegomezgarc%C3%ADa/) o revisar mi progreso en [TryHackMe](https://tryhackme.com/p/jgomez7) y [HackTheBox](https://profile.hackthebox.com/profile/019fa8db-797f-707e-b730-abe6edb38505).
