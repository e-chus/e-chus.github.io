# Trucos BugBounty DragonJAR (HackMadrid%27)

## Plataformas
* [Hackerone](https://www.hackerone.com/) - La mas activa
* [Bugcrowd](https://www.bugcrowd.com/) - Segunda mas activa
* [YesWeHack](https://www.yeswehack.com/)
* [Yogosha](https://yogosha.com/)
* [Zerocopter](https://www.zerocopter.com/)
* [OpenBugBounty](https://www.openbugbounty.org/)
* [HackerProof](https://hackenproof.com/)
* [Intigriti](https://www.intigriti.com/)

## Gamificacion
Puntos por reportes

## Errores al empezar
* Correr antes de andar
* Todas la plataformas a la vez (centrarse en 1 -Hackerone vs Bugcrowd-)

## Trucos
* Plataforma o Compañia directamente pero no las 2
* Mejor en programas nuevos ya que tienen mas fallos
* Campañas con mas scope y mas años porque tienen menos gente buscando debido a la antiguedad
* Tabla comparativa de programas en Hackerone (Foto 5)
* Mirar Hactivity de reportes resueltos en Hackerone
* Intentar evitar los Duplicados (El mayor peligro del bounter)
* Alejarse de la mandada, hacer cosas diferentes a los demas
* Buscar un scope mas pequeño (En vez de Telefonica.es irse a Telefonica.com.co)
* Ir a lo raro (empresas grandes pero raras eJ: AT&T Mejico)
* Contratar servicios de pago y peridos de prueba de estas empresas (cuenta dropbox prueba, SIM prepago, etc ..)
* Buscar Githubs personales de gente de la empresa
* Buscar en Stackoverflow gente de la empresa que postea cosas sobre ella
* Estar atento a las actualizaciones en Hackerone (Visualping de hackerone) para nuevas alertas
* Firebounty en YesWeHack --> ultimos cambios

## Manos a la obra

### 1. Enumeracion (Foto 6)
- Dominios, subdominios, Aplicaciones, Paginas Secundaria
- [Burpsuite Scan](https://portswigger.net/web-security) - Web vulnerability scanner
- [Shodan](https://www.shodan.io/)
- [Sensis](https://www.sensis.com.au/)
- [Sublist3r](https://github.com/aboul3la/Sublist3r) - Enumerate subdomains of websites using OSINT
- [Enumall](https://github.com/jhaddix/domain) - Recon-ng and Alt-DNS are awesome. This script combines the power of these tools with the ability to run multiple domains within the same session.
- [Altdns](https://github.com/infosec-au/altdns) - Discovery subdomains that conform to patterns
- [Knock](https://github.com/guelfoweb/knock) - Subdomain Scan 
- [Subbrute](https://github.com/TheRook/subbrute) - A DNS meta-query spider that enumerates DNS records, and subdomains. 
- [massdns](https://github.com/blechschmidt/massdns) - A high-performance DNS stub resolver for bulk lookups and reconnaissance (subdomain enumeration) 
- [Recon-ng](https://github.com/lanmaster53/recon-ng) - reconnaissance framework for web-based reconnaissance quickly and thoroughly (look and feel similar to the Metasploit Framework)
- [Amass](https://github.com/OWASP/Amass) - In-depth Attack Surface Mapping and Asset Discovery
- [SubFinder](https://github.com/projectdiscovery/subfinder) - subdomain discovery tool that discovers valid subdomains for websites
- [httprobe](https://github.com/tomnomnom/httprobe) - Take a list of domains and probe for working http and https servers
- [waybackurls](https://github.com/tomnomnom/waybackurls) - Fetch all the URLs that the Wayback Machine knows about for a domain 
- [dirsearch](https://github.com/maurosoria/dirsearch) - brute force directories and files in websites.
- [wfuzz](https://github.com/xmendez/wfuzz) - replaces any reference to the FUZZ keyword by the value of a given payload
- [gobuster](https://github.com/OJ/gobuster) - brute-force URIs, DNS, subdomains, Virtual Host names on target web servers
- [EyeWitness](https://github.com/FortyNorthSecurity/EyeWitness) - take screenshots of websites, provide some server header info, and identify default credentials if possible
- [http-vulners-regex.nse](https://github.com/vulnersCom/nmap-vulners/blob/master/http-vulners-regex.nse) - script de nmap para vulnerabilidades
- [Domained](https://github.com/TypeError/domained) - Domain name enumeration tool - **VIP**
- [Exegol](https://github.com/ShutdownRepo/Exegol) -  kali light base with a few useful additional tools and some basic configuration.
- [shodan-eye](https://github.com/BullsEye0/shodan-eye) - collects all the information about all devices directly connected to the internet using the specified keywords
- [Shodan_Dorks](https://github.com/BullsEye0/shodan-eye/blob/master/Shodan_Dorks_The_Internet_of_Sh*t.txt) - collection of search queries for Shodan
- [uDork](https://github.com/m3n0sd0n4ld/uDork) - Google search techniques to obtain sensitive information in files or directories, find IoT devices, detect versions of web applications
#### [Hacker's Life](https://twitter.com/Unknownuser1806/status/1236505408073691136)
- [CloudFail](https://github.com/m0rtem/CloudFail) - Information about a target protected by Cloudflare
- [ReconDog](https://github.com/s0md3v/ReconDog) - Reconnaissance Swiss Army Knife
- [GitGot](https://github.com/BishopFox/GitGot) - Semi-automated to rapidly search public data on GitHub for sensitive secrets
- [Awesome Asset Discovery](https://github.com/redhuntlabs/Awesome-Asset-Discovery#awesome-asset-discovery) - Asset Discovery
- [Discover by leebaird](https://github.com/leebaird/discover) - Custom bash scripts used to automate various penetration testing tasks
- [Arjun](https://github.com/s0md3v/Arjun) - HTTP Parameter Discovery Suite
- [Striker](https://github.com/s0md3v/Striker) - Recon & Vulnerability Scanning Suite
- [OneForAll](https://github.com/shmilylty/OneForAll) - Subdomain collection tool 
- [Zeus-Scanner](https://github.com/Ekultek/Zeus-Scanner) - Web application reconnaissance
- [SimplyEmail ](https://github.com/SimplySecurity/SimplyEmail) -  Email recon made fast and easy
- [Ted teaming toolkit Colletion](https://0xsp.com/offensive/red-teaming-toolkit-collection) - Red Teaming/Adversary Simulation Toolkit 

### 2. Depuracion
- Cuales Responden
- Que tienen?

### 3. Fuzzing
- Carpetas abandonadas, etc...
- [wfuzz](https://github.com/xmendez/wfuzz) - replaces any reference to the FUZZ keyword by the value of a given payload

### 4. Objetivio Definido y Filtrado
- Fallos de seguridad en aplicaciones web

### 5. Servicios en la nube para automatizar tareas (Foto 4)
- Digital Ocean --> 100$ gratis en foto 
- [Kali Nube] --> @JIIturrioz en twitter

### 6. Que Reportar (Foto 3)
- Cross-Site Scripting (XSS)
- Improper Authentication
- Information Disclosure
- Privilege Scalation
- SQL Injection
- Code Injection
- Server-Side Request Forgery
- Insecure Direct Object Reference
- Improper Access Control
- Cross Site Request Forgery

### 7. Como reportar
- Que no sean tonterias
- Titulos descriptivos
- Bien explicado en ingles
- Paso a paso reproduciendo el problema
- Video explicativo si es necesario
- Impacto del fallo

### 8. Y despues...
- Seguimiento de los reportes
- Luchar por tus reportes
- Ser amable con el que revisa (triagger)
- Validar si el problema fue reparado, para asi reclamarlo!

### 9. Ultimos Tips
- Utilizar Espacios y horarios para la tarea
- Automatizar TODO lo posible (sobre todo enumeracion)
- Tener cuidado con la ANSIEDAD

## Recursos (Fotos 1 y 2)
* [List of bug bounty writeups](https://pentester.land/list-of-bug-bounty-writeups.html) - **VIP**
* [JHaddix - The Bug Hunters Methodology V3(ish)](https://www.youtube.com/watch?v=Qw1nNPiH_Go) - **VIP**
* [Intro al Bug Bounty by saamux - L4tin-HTB](https://www.youtube.com/watch?v=iVPwe0X0CT0&feature=youtu.be) - **VIP**
* [¿Cómo iniciar en Seguridad Informática / Hacking Ético?](https://www.dragonjar.org/como-iniciar-en-seguridad-informatica-hacking-etico.xhtml)
* [DrangonJar Formacion](http://dragonjar.org/formacion) -  Formacion de 3 horas
* [Web Security Academy](https://portswigger.net/web-security)
* [ExploitingBooks](https://github.com/hdbreaker/ExploitingBooks)
* ebook - Real-World Bug hunting
* [ebook - Web Application Hacker Handbook 2](http://index-of.es/EBooks/11_TheWeb%20Application%20Hackers%20Handbook.pdf)
* [Web Application Hacker Handbook extras](https://github.com/six2dez/wahh_extras)
* Personas del TOP 50 de Hackerone o Bugcrowd (RRSS)
* Reportes resueltos de las plataformas (Disclosure)
* #bugbounty en RRSS
* hacker101.com
* [OWASP TOP 10](https://owasp.org/www-project-top-ten/)
* [Programas BB Atractivos](https://www.welivesecurity.com/la-es/2017/03/10/5-programas-de-bug-bounty-atractivos/)

## Otros Recursos
* https://hackingd0.blogspot.com/2017/12/todas-nuestras-clases.html
* https://ss64.com/
* https://s4vitar.github.io/*
* http://www.h1rd.com/index.html
* https://thehackerway.com/2019/03/04/seguridad-informatica-en-50-dias-your-hacker-way/
* https://www.offensiveosint.io/offensive-osint-introduction/
* https://www.offensiveosint.io/offensive-osint-s01e01-osint-rdp/
 
## Best Tools
* burpsuite (VIP)
* nahamsec bash script lazzyrecord (recon, dirsearch)
* domained (restepo)

## los BB más faciles (para empezar)
* Inyección sql (EJ: poniendo una comilla)
* Default credentials (EJ: admin/admin)
* todnomnom persoa BB github --> way back urls  https://twitter.com/tomnomnom
* leer el manual de la aplicacion o ver los videos de explicacion intuye --> usuario/usuario

## Enlaces compartidos en el #ForoBugbounty del #C0r0n4CON (VIP)
* [C0r0n4CON](https://pastebin.com/QsRP9xrS)

## Canales de Youtube
* [Vicor Garcia](https://www.youtube.com/channel/UCjNHFaBm_0-Mo749MB3A9cQ/videos)
* [Julio Ureña](https://www.youtube.com/channel/UC2o1vzpUIvgf0VMJIMKZ_rQ/videos)
* [S4vitar](https://www.youtube.com/channel/UCNHWpNqiM8yOQcHXtsluD7Q/videos)
