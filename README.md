# Cisco Packet Tracer Labs 🖧

Ejercicios prácticos de redes simuladas con Cisco Packet Tracer.
Parte de mi proceso de formación en IT Support / Redes.

## Laboratorios

### Lab 1 — LAN básica con switch
- 3 PCs conectadas a un switch Cisco 2960
- Asignación manual de IPs (192.168.1.x)
- Verificación de conectividad con ping

### Lab 2 — Routing entre dos subredes
- 4 PCs divididas en dos subredes
- Router Cisco 1941 con dos interfaces configuradas por CLI
- Comandos: ip address, no shutdown, show ip interface brief

### Lab 3 — DHCP automático en dos subredes
- Servidor DHCP con dos pools (LAN1 y LAN2)
- Configuración de ip helper-address en el router
- Las PCs reciben IP automáticamente sin configuración manual

- ### Lab 4 — VLANs en switch Cisco
- 4 PCs conectadas a un switch Cisco 2960
- VLAN 10 (Administración): PC0 y PC1 en puertos Fa0/1 y Fa0/2
- VLAN 20 (Sistemas): PC2 y PC3 en puertos Fa0/3 y Fa0/4
- Verificación de aislamiento: PCs en VLANs distintas no se comunican
- Comandos: vlan, switchport mode access, switchport access vlan, show vlan brief

## Herramientas
- Cisco Packet Tracer
- Router: Cisco 1941
- Switch: Cisco 2960
