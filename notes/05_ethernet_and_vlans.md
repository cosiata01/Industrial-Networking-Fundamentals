# 05 – Industrial Ethernet and VLAN Segmentation  
*(Español abajo / Spanish below)*  

---

## 🇬🇧 English Summary  

**Industrial Ethernet** has become the backbone of modern OT networks, replacing older serial communication methods.  
It offers higher bandwidth, standardized infrastructure, and integration with IT systems — but it also introduces cybersecurity challenges.

### ⚙️ Industrial Ethernet Basics
- Uses standard Ethernet technologies (IEEE 802.3) with ruggedized hardware.  
- Enables deterministic communication through time-sensitive networking (TSN) or prioritized traffic (QoS).  
- Supports **Industrial protocols** like Profinet, Ethernet/IP, and Modbus TCP.  
- Common speeds: 100 Mbps, 1 Gbps (sometimes 10 Gbps in high-end systems).  

### 🔒 VLANs (Virtual Local Area Networks)
- VLANs logically segment a single physical network into multiple isolated zones.  
- Improve performance, manageability, and security by separating traffic types (e.g., control vs supervision).  
- Common practice in OT: assign different VLANs for PLCs, HMIs, SCADA servers, and engineering stations.  
- Managed switches enable VLAN configuration and inter-VLAN routing control.  

📊 **Suggested Diagram:**  
In `/diagrams/vlan_segmentation_example.png`, illustrate VLANs separating traffic between control, SCADA, and IT zones, showing a firewall or router between them.  

### 🔑 Key Takeaways
- VLANs enhance both performance and security in industrial networks.  
- Proper VLAN design minimizes broadcast storms and limits lateral movement during attacks.  
- Ethernet in OT must balance performance with determinism and reliability.  

---

## 🇪🇸 Resumen en español  

El **Ethernet industrial** se ha convertido en la columna vertebral de las redes OT modernas, reemplazando los antiguos métodos de comunicación serie.  
Ofrece mayor ancho de banda, infraestructura estandarizada e integración con sistemas IT — pero también introduce nuevos retos de ciberseguridad.  

### ⚙️ Fundamentos de Ethernet industrial
- Utiliza tecnologías Ethernet estándar (IEEE 802.3) con hardware reforzado.  
- Permite comunicación determinista mediante **TSN (Time-Sensitive Networking)** o priorización de tráfico (**QoS**).  
- Soporta **protocolos industriales** como Profinet, Ethernet/IP y Modbus TCP.  
- Velocidades comunes: 100 Mbps, 1 Gbps (hasta 10 Gbps en sistemas avanzados).  

### 🔒 VLANs (Redes de área local virtuales)
- Las VLAN segmentan lógicamente una red física en varias zonas aisladas.  
- Mejoran el rendimiento, la gestión y la seguridad al separar tipos de tráfico (por ejemplo, control y supervisión).  
- En entornos OT es común asignar VLANs distintas para PLC, HMI, servidores SCADA y estaciones de ingeniería.  
- Los switches gestionados permiten configurar VLANs y controlar el enrutamiento entre ellas.  

📊 **Diagrama sugerido:**  
En `/diagrams/vlan_segmentation_example.png`, muestra VLANs que separen tráfico entre zonas de control, SCADA e IT, con un firewall o router entre ellas.  

### 🔑 Puntos clave
- Las VLAN mejoran tanto el rendimiento como la seguridad de las redes industriales.  
- Un diseño adecuado de VLAN reduce tormentas de broadcast y limita el movimiento lateral durante un ataque.  
- Ethernet en OT debe equilibrar rendimiento con comunicación determinista y fiabilidad.  

---

## 💬 Personal Reflection / Reflexión personal  

> 🇬🇧 Understanding VLANs was a turning point for me. I used to see networks as flat systems, but now I understand how segmentation can prevent one compromised device from affecting others. It’s one of the simplest yet most powerful defenses in OT security.  

> 🇪🇸 Comprender las VLAN fue un punto de inflexión para mí. Antes veía las redes como sistemas planos, pero ahora entiendo cómo la segmentación puede evitar que un dispositivo comprometido afecte a los demás. Es una de las defensas más simples pero poderosas en la seguridad OT.  
