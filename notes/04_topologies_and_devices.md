# 04 – Industrial Network Topologies and Devices  
*(Español abajo / Spanish below)*  

---

## 🇬🇧 English Summary  

Industrial networks can be organized in several **topologies**, each affecting how devices communicate and how resilient the system is against failures.  
Choosing the right topology depends on factors such as scalability, fault tolerance, and real-time requirements.  

### 🔗 Common Topologies
- **Bus:** All devices share the same communication line. Simple but vulnerable — if the cable fails, the whole network may stop.  
- **Star:** Each device connects to a central switch or hub. Easy to expand and troubleshoot, but depends on the switch’s reliability.  
- **Ring:** Devices form a loop. Provides redundancy — if one link fails, data can still flow in the opposite direction.  
- **Tree / Hierarchical:** Combination of star and bus topologies, often used in large-scale industrial environments.  

### 🧠 Key Devices
- **Switches:** Connect multiple devices within the same network. Industrial switches are rugged and often managed for VLANs, redundancy (STP/RSTP), and monitoring.  
- **Routers:** Connect different networks or subnets; manage traffic between OT and IT zones.  
- **Gateways:** Translate communication between different protocols (e.g., Modbus ↔ OPC UA).  
- **Firewalls:** Segment and protect network traffic across zones (IT/DMZ/OT).  

📊 **Suggested Diagram:**  
Include in `/diagrams/industrial_topology_example.png` a simple drawing showing PLCs, sensors, an HMI, and a SCADA system connected via switches and gateways.  

### 🔑 Key Takeaways
- Topology design directly affects network reliability and security.  
- Redundancy (like ring or dual-homed star) increases availability.  
- Proper use of switches, routers, and gateways reduces single points of failure.  

---

## 🇪🇸 Resumen en español  

Las redes industriales pueden organizarse en diferentes **topologías**, y cada una influye en la forma en que los dispositivos se comunican y en la resiliencia del sistema ante fallos.  
Elegir la topología adecuada depende de factores como la escalabilidad, la tolerancia a fallos y los requisitos de tiempo real.  

### 🔗 Topologías comunes
- **Bus:** Todos los dispositivos comparten la misma línea de comunicación. Es simple, pero si el cable falla, toda la red puede detenerse.  
- **Estrella:** Cada dispositivo se conecta a un switch o concentrador central. Es fácil de ampliar y diagnosticar, pero depende de la fiabilidad del switch.  
- **Anillo:** Los dispositivos forman un bucle. Aporta redundancia: si un enlace falla, los datos pueden fluir por el camino contrario.  
- **Árbol / Jerárquica:** Combinación de topología en estrella y bus, usada en entornos industriales grandes.  

### 🧠 Dispositivos principales
- **Switches:** Conectan varios dispositivos en la misma red. Los industriales son robustos y suelen permitir VLANs, redundancia (STP/RSTP) y monitoreo.  
- **Routers:** Conectan diferentes redes o subredes; gestionan el tráfico entre zonas OT e IT.  
- **Gateways:** Traducen la comunicación entre protocolos distintos (por ejemplo, Modbus ↔ OPC UA).  
- **Firewalls:** Segmentan y protegen el tráfico entre zonas (IT/DMZ/OT).  

📊 **Diagrama sugerido:**  
Incluye en `/diagrams/industrial_topology_example.png` un esquema con PLC, sensores, HMI y sistema SCADA conectados mediante switches y gateways.  

### 🔑 Puntos clave
- El diseño de la topología impacta directamente en la fiabilidad y la seguridad de la red.  
- La redundancia (como anillo o estrella dual) mejora la disponibilidad.  
- Un uso adecuado de switches, routers y gateways evita puntos únicos de fallo.  

---

## 💬 Personal Reflection / Reflexión personal  

> 🇬🇧 Drawing different topologies helped me visualize how communication flows in an industrial network. I realized that reliability is not only about cables and switches but about designing with redundancy and segmentation in mind.  

> 🇪🇸 Dibujar las distintas topologías me ayudó a visualizar cómo fluye la comunicación en una red industrial. Comprendí que la fiabilidad no depende solo de los cables o los switches, sino de diseñar pensando en la redundancia y la segmentación.  
