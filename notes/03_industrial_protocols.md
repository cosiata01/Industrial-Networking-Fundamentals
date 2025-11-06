# 03 – Industrial Protocols  
*(Español abajo / Spanish below)*  

---

## 🇬🇧 English Summary  

Industrial networks rely on **communication protocols** that allow sensors, actuators, PLCs, and control systems to exchange data efficiently and safely.  
Unlike IT protocols, industrial ones are designed for **deterministic, time-critical communication**, often prioritizing availability and stability over raw speed.

### ⚙️ Main Industrial Protocols

#### 🟢 **Modbus (RTU / TCP)**
- **Modbus RTU:** Based on serial communication (RS-232/RS-485).  
- **Modbus TCP:** Ethernet-based version using TCP/IP.  
- Works with a **master/slave** model — simple, reliable, but lacks encryption.  
- Common in legacy systems still used today.

#### 🔵 **PROFINET**
- Developed by Siemens; based on **Industrial Ethernet**.  
- Uses **real-time communication** for factory automation.  
- Supports diagnostics and configuration over the same network.  
- Allows flexible topologies (star, line, ring).  

#### 🟣 **OPC UA (Open Platform Communications – Unified Architecture)**
- Modern, **platform-independent** protocol for interoperability between systems.  
- Includes **encryption, authentication, and data modeling**.  
- Often used to integrate OT systems with IT/cloud applications.  

#### 🟠 **AS-Interface (AS-i)**
- Simple and cost-effective for connecting sensors/actuators.  
- Works as a **bus system**, typically linking to PLCs via gateways.  
- Operates in the lower layers of automation (physical and data link).

### 🔑 Key Takeaways
- Each protocol fits a specific layer of automation and use case.  
- **Modbus** = simplicity, **PROFINET** = speed and reliability, **OPC UA** = interoperability and security.  
- Legacy protocols persist in industry — understanding them is key for cybersecurity.  

---

## 🇪🇸 Resumen en español  

Las redes industriales dependen de **protocolos de comunicación** que permiten el intercambio de datos entre sensores, actuadores, PLC y sistemas de control.  
A diferencia de los protocolos IT, los industriales están diseñados para **comunicaciones deterministas y críticas en tiempo real**, priorizando la disponibilidad y estabilidad sobre la velocidad pura.

### ⚙️ Principales protocolos industriales

#### 🟢 **Modbus (RTU / TCP)**
- **Modbus RTU:** Basado en comunicación serie (RS-232/RS-485).  
- **Modbus TCP:** Versión sobre Ethernet con TCP/IP.  
- Modelo **maestro/esclavo**, simple y fiable, pero sin cifrado.  
- Aún muy común en sistemas heredados.  

#### 🔵 **PROFINET**
- Desarrollado por Siemens, basado en **Ethernet industrial**.  
- Usa comunicación en **tiempo real** para automatización de fábricas.  
- Permite diagnóstico y configuración en la misma red.  
- Soporta topologías flexibles (estrella, línea, anillo).  

#### 🟣 **OPC UA (Open Platform Communications – Unified Architecture)**
- Protocolo moderno e **independiente de plataforma**.  
- Incluye **cifrado, autenticación y modelado de datos**.  
- Ideal para integrar sistemas OT con aplicaciones IT o en la nube.  

#### 🟠 **AS-Interface (AS-i)**
- Económico y sencillo para conectar sensores y actuadores.  
- Funciona como un **sistema en bus**, conectado a PLC mediante gateways.  
- Opera en las capas inferiores de automatización (física y de enlace).  

### 🔑 Puntos clave
- Cada protocolo tiene su capa y propósito dentro de la automatización.  
- **Modbus** = simplicidad, **PROFINET** = velocidad, **OPC UA** = interoperabilidad y seguridad.  
- Los protocolos heredados siguen siendo comunes, por lo que entenderlos es esencial para la ciberseguridad OT.  

---

## 💬 Personal Reflection / Reflexión personal  

> 🇬🇧 When I first compared Modbus, Profinet, and OPC UA, I realized how different their goals are. Some prioritize simplicity, others focus on speed or security. This helped me understand that industrial cybersecurity starts by knowing how each protocol behaves and where its weak points are.  

> 🇪🇸 Al comparar Modbus, Profinet y OPC UA, entendí que cada uno tiene un propósito distinto. Algunos priorizan la simplicidad, otros la velocidad o la seguridad. Esto me hizo ver que la ciberseguridad industrial comienza por conocer cómo se comporta cada protocolo y dónde están sus puntos débiles.  
