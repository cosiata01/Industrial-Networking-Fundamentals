# 06 – OT Security Basics and Best Practices  
*(Español abajo / Spanish below)*  

---

## 🇬🇧 English Summary  

As industrial systems become more connected, **cybersecurity in OT (Operational Technology)** has become a critical discipline.  
Unlike IT, where confidentiality is the top priority, OT security focuses on **availability and integrity** — ensuring that industrial processes continue safely and reliably.

### 🛡️ Core Principles of OT Security
- **Availability first:** Downtime can stop production or endanger safety.  
- **Defense in Depth:** Layered protection using firewalls, segmentation, monitoring, and access control.  
- **Zones and Conduits:** Divide the network into security zones (control, DMZ, enterprise) and manage data flows between them.  
- **Least Privilege:** Users and devices should only have the access they truly need.  
- **Change Management:** Any modification to PLC logic, firmware, or configuration must be tracked and authorized.  

### 🚨 Common Risks
- Unpatched or outdated PLCs and HMIs.  
- Flat networks without segmentation (easy lateral movement).  
- Remote connections without secure authentication (VPN or MFA).  
- Weak or default passwords in industrial devices.  

### 🧰 Recommended Practices
- Use **managed switches** with VLANs and port security.  
- Implement **firewalls** between IT, DMZ, and OT zones.  
- Monitor traffic with **IDS/IPS tools** adapted for industrial protocols (e.g., Zeek, Snort).  
- Back up PLC programs and SCADA configurations regularly.  

📊 **Suggested Diagram:**  
In `/diagrams/ot_defense_in_depth.png`, represent layered security: outer (IT) → DMZ → OT → control devices.

### 🔑 Key Takeaways
- OT security prioritizes **availability** and **safety**.  
- Layered security reduces risk of cascading failures.  
- The best defense starts with knowing your network and controlling access.  

---

## 🇪🇸 Resumen en español  

A medida que los sistemas industriales se vuelven más conectados, la **ciberseguridad en OT (tecnología operacional)** se ha convertido en una disciplina crítica.  
A diferencia del mundo IT, donde la prioridad es la **confidencialidad**, en OT la seguridad se centra en la **disponibilidad y la integridad**, garantizando que los procesos industriales sigan funcionando de forma segura y confiable.  

### 🛡️ Principios fundamentales de la seguridad OT
- **Disponibilidad ante todo:** Una caída puede detener la producción o poner en riesgo la seguridad.  
- **Defensa en profundidad:** Protección por capas mediante firewalls, segmentación, monitoreo y control de acceso.  
- **Zonas y conductos:** Dividir la red en zonas de seguridad (control, DMZ, empresa) y gestionar los flujos entre ellas.  
- **Mínimo privilegio:** Usuarios y dispositivos solo deben tener el acceso necesario.  
- **Gestión de cambios:** Toda modificación en PLC, firmware o configuración debe registrarse y aprobarse.  

### 🚨 Riesgos comunes
- PLC o HMI sin actualizar o con firmware obsoleto.  
- Redes planas sin segmentación (movimiento lateral fácil).  
- Conexiones remotas sin autenticación segura (VPN o MFA).  
- Contraseñas débiles o por defecto en dispositivos industriales.  

### 🧰 Buenas prácticas recomendadas
- Usar **switches gestionados** con VLANs y seguridad por puerto.  
- Implementar **firewalls** entre zonas IT, DMZ y OT.  
- Monitorear el tráfico con herramientas **IDS/IPS** adaptadas a protocolos industriales (Zeek, Snort).  
- Realizar copias de seguridad periódicas de programas de PLC y configuraciones SCADA.  

📊 **Diagrama sugerido:**  
En `/diagrams/ot_defense_in_depth.png`, muestra la defensa en capas: exterior (IT) → DMZ → OT → dispositivos de control.

### 🔑 Puntos clave
- La seguridad OT prioriza la **disponibilidad** y la **seguridad operacional**.  
- Las defensas en capas reducen el riesgo de fallos en cascada.  
- La mejor defensa comienza con conocer tu red y controlar el acceso.  

---

## 💬 Personal Reflection / Reflexión personal  

> 🇬🇧 Learning about OT security changed my mindset completely. I realized that even small configuration errors can have real physical consequences. Implementing layered protection is not just about firewalls — it’s about designing systems that fail safely.  

> 🇪🇸 Aprender sobre seguridad OT cambió completamente mi forma de pensar. Entendí que incluso pequeños errores de configuración pueden tener consecuencias físicas reales. Implementar protección en capas no se trata solo de firewalls, sino de diseñar sistemas que fallen de forma segura.  
