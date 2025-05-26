🛡️ Red Team Lab – Simulación de Ataque con Havoc
📝 Descripción
Laboratorio práctico de Red Team para simular un ataque controlado usando Havoc como Command and Control (C2). El entorno consta de dos máquinas virtuales (Windows 10 y Debian 12) conectadas por un túnel SSH.

🚀 Pasos Realizados
🖥️ Preparación del entorno

Descargué y configuré las ISOs oficiales de Windows 10 y Debian 12 en VirtualBox (4096 MB de RAM, modo puente, Guest Additions).

⚙️ Instalación de herramientas en Debian

Instalé net-tools, openssh-server, git, python3-pip y cloné/compilé Havoc.

🔗 Creación del túnel SSH

Configuré un túnel SSH inverso desde Windows hacia Debian para garantizar la comunicación del payload.

💣 Ejecución del ataque

Generé el payload (Informe_Urgente.exe) en Havoc, lo transferí con un servidor HTTP sencillo y lo ejecuté en Windows.

🎯 Control remoto

Obtuve acceso total a la máquina Windows desde Havoc y realicé acciones básicas de control y exploración.

✅ Conclusión
Este laboratorio demuestra cómo es posible simular un ataque de Red Team con Havoc y un túnel SSH, logrando acceso remoto a un sistema Windows en un entorno controlado.

