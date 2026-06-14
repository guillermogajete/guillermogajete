<div align="center">
<img width="1920" height="894" alt="Image" src="https://github.com/user-attachments/assets/c8ec261e-3ae8-4db6-b9ae-b7440c3f636d" width="100%" />
</div>

<br>

<div align="center">
  <br>
  <b>Especialista en Ciberseguridad (Blue Team) & Digital Forensics | Técnico Superior en Sistemas en Red</b> <br>
  Cartagena, Región de Murcia, España <br><br>
  Bienvenido a mi portfolio técnico. Aquí encontrarás automatizaciones, scripts y metodologías documentadas para el análisis forense, respuesta a incidentes y bastionado de sistemas. <br>
  Siéntete libre de explorar mis laboratorios y contactar conmigo. <br><br>
  
  <a href="mailto:guillermogajete1987@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a> 
  <a href="https://www.linkedin.com/in/guillermo-cañavate-gajete" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a> 

</div>

<br>

---

### Sobre Mí 

Mi nombre es Guillermo y la informática siempre ha formado parte de mi vida, desde los tiempos del mítico Amstrad CPC 464 hasta las arquitecturas más modernas de la familia Windows. Son muchos años explorando este mundo, pero manteniéndome siempre en constante actualización, una exigencia innegociable en este sector.

Hace unos 5 años decidí profesionalizar mi pasión a través de la educación reglada. Comencé con el Grado Medio de Sistemas Microinformáticos y Redes (SMR) y, posteriormente, di el salto al Grado Superior de Administración de Sistemas Informáticos en Red (ASIR). Durante ese tiempo me "picó el gusanillo" de la ciberseguridad, descubriendo mi vocación por la defensa y el peritaje. Esto me llevó a dar el paso definitivo: en 2026 finalicé mis estudios de especialización en **Ciberseguridad en Entornos de las Tecnologías de la Información**.

### Enfoque Actual

- **Oposiciones:** Preparándome activamente para el Cuerpo de Técnicos Auxiliares de Informática (TAI) a nivel estatal.
- **Certificaciones:** Aumentando mis conocimientos técnicos enfocados en redes (Cisco), seguridad en entornos Microsoft (familia Security, Compliance, and Identity - SC) y profundizando en las soluciones de Qualys.
- **Entrenamiento (Blue Team):** Resolviendo laboratorios y retos de defensa en [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges).
- **Objetivo profesional:** Incorporarme a un equipo de Operaciones de Seguridad **(SOC)** o participar en **proyectos técnicos de DFIR (Digital Forensics and Incident Response)**.

---

### Arsenal Tecnológico y Herramientas Top

Mi entorno de trabajo se basa en la automatización a través de scripting y el uso de herramientas líderes en el sector DFIR y sistemas:

**Automatización y Scripting:**
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white) 

**Análisis Forense y Blue Team:**
![Volatility 3](https://img.shields.io/badge/Volatility_3-4B275F?style=for-the-badge&logo=python&logoColor=white)
![Autopsy](https://img.shields.io/badge/Autopsy-005571?style=for-the-badge&logo=linux&logoColor=white) 
![Zimmerman Tools](https://img.shields.io/badge/Zimmerman_Tools-2C3E50?style=for-the-badge) 
![Sysinternals](https://img.shields.io/badge/Sysinternals-0078D6?style=for-the-badge&logo=windows&logoColor=white) 
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white) 
![FTK Imager](https://img.shields.io/badge/FTK_Imager-B71C1C?style=for-the-badge&logo=windows&logoColor=white) 

**Sistemas y Redes:**
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white) 
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) 
![Windows 11](https://img.shields.io/badge/Windows_11-0078D6?style=for-the-badge&logo=windows-11&logoColor=white) 

---

### Proyectos Estrella (Escaparate Técnico)

A continuación, destaco algunas de mis investigaciones y herramientas desarrolladas:

#### 📱 [Análisis Forense Informático: Extracción de Datos iPad (iOS)](https://github.com/guillermogajete/enlace-al-repo)
- **Objetivo:** Extracción lógica, análisis de bases de datos SQLite y búsqueda de artefactos, comunicaciones y datos borrados en un iPad 14.4[cite: 6].
- **Entorno:** iBackup Viewer, DB Browser for SQLite, ExifToolGui, Scripting para decodificación `NSKeyedArchiver`[cite: 6].
- **Conclusiones:** Identificación de cuenta principal y sincronización iCloud. Análisis de estado de papelera (`ZTRASHEDSTATE`) demostrando la ausencia de borrado intencionado (anti-forense) de evidencias multimedia[cite: 6].

#### 🧠 [Análisis Forense de Volcado de Memoria RAM (Windows)](https://github.com/guillermogajete/enlace-al-repo)
- **Objetivo:** Automatización del análisis de un volcado `.dmp` para extraer procesos, conexiones de red, inyecciones de código y librerías[cite: 6].
- **Entorno:** Volatility 3 orquestado con scripts interactivos en Batch y PowerShell[cite: 6].
- **Conclusiones:** Detección de procesos ocultos/terminados (`psscan`), mapeo de conexiones activas y auditoría de DLLs en procesos legítimos (`explorer.exe`) logrando un análisis pericial trazable y cronometrado[cite: 6].

#### 🚑 [Kit Forense de Respuesta en Vivo para Windows 11](https://github.com/guillermogajete/enlace-al-repo)
- **Objetivo:** Herramienta portable de *First Responder* (USB_FORENSE) para extracción no invasiva de evidencias volátiles respetando el orden de volatilidad y la cadena de custodia (INCIBE)[cite: 6].
- **Entorno:** Batch scripting, Comae Toolkit (DumpIt), MFTECmd, Autoruns[cite: 6].
- **Conclusiones:** Extracción automatizada de más de 36 artefactos críticos (RAM, MFT con detección de ZoneId/ADS, Prefetch, Registro). Minimización de huella utilizando un entorno `System32` portable en modo solo lectura[cite: 6].

---

### 📈 Estadísticas en Tiempo Real

<div align="center">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=guillermogajete&include_all_commits=true&count_private=true&show_icons=true&line_height=20&title_color=7A7ADB&icon_color=2234AE&text_color=D3D3D3&bg_color=0,000000,130F40" alt="GitHub Stats">
  <br><br>
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=guillermogajete&layout=compact&theme=dark&title_color=7A7ADB&text_color=D3D3D3&bg_color=0,000000,130F40" alt="Top Languages">
</div>

<br>

<div align="center">
  <i>Un pequeño descanso técnico:</i><br><br>
  <a href="https://readme-jokes.vercel.app"><img align="center" src="https://readme-jokes.vercel.app/api" alt="README Jokes"></a>
</div>
