# Simulación de Ataque a un Servidor Empresarial Vulnerable

Este proyecto tiene como objetivo la simulación de un ataque real a un servidor Ubuntu configurado con intenciones vulnerables, con el fin de analizar las debilidades de seguridad comunes y proponer soluciones prácticas.

---

## Objetivos

- Simular un entorno empresarial con servicios expuestos como Apache, MySQL y SSH mal configurados.
- Llevar a cabo pruebas de fuerza bruta, enumeración de servicios y escalada de privilegios desde una máquina atacante.
- Documentar paso a paso todo el proceso de intrusión y explotación.
- Concienciar sobre la importancia de buenas prácticas de seguridad.

---

## Entorno de trabajo

- **Host**: Windows 11
- **Máquinas virtuales**: VirtualBox
  - Ubuntu Server (objetivo)
  - Arch Linux (atacante)
- **Herramientas utilizadas**:
  - `Nmap`, `Hydra`
  - `Apache`, `MySQL`, `SSH`
  - `Rockyou.txt`, `nano` con SUID
  - `Packet Tracer` (para la infraestructura de red)
  - `Alacritty` (terminal en Arch)

---

## Contenido del repositorio

| Archivo/Carpeta      | Descripción                                                              |
|----------------------|---------------------------------------------------------------------------|
| `index.html`         | Página web vulnerable con pistas para el atacante                        |
| `red.pkt`            | Infraestructura de red creada en Cisco Packet Tracer                     |
| `ataque.mp4`         | Video que muestra la ejecución del ataque paso a paso                    |
| `Pasos_realizados.pdf`| Documento con la explicación detallada de cada fase de la configuración y ataque        |

---

## Resultados

A través de esta simulación se identificaron las siguientes vulnerabilidades críticas:

- Contraseñas débiles y reutilizadas
- Base de datos con credenciales almacenadas sin cifrado
- Binarios mal configurados con permisos SUID (como `nano`)
- Escalada de privilegios hasta `root`
- Servicios expuestos sin controles de acceso adecuados

---

## Datos relevantes

Estas son los resultados de porcentaje sobre las causas más comunes de brechas de seguridad en servidores Linux:

- Contraseñas débiles: 35%
- Configuración insegura de servicios: 30%
- Escalada de privilegios: 20%
- Exposición innecesaria de servicios: 15%

---

## Referencias

- [Guía de Nmap](https://nmap.org/book/)
- [Hydra GitHub](https://github.com/vanhauser-thc/thc-hydra)
- [GTFOBins](https://gtfobins.github.io/)
- [Ubuntu Server ISO](https://ubuntu.com/download/server)
- [Arch Linux ISO](https://archlinux.org/download/)
- [Packet Tracer Web](https://www.netacad.com/courses/packet-tracer)

---

## Conclusión

Este entorno evidencia cómo una mala configuración y prácticas laxas en servidores pueden comprometer gravemente la infraestructura empresarial.
---

## Contacto

Proyecto desarrollado con fines educativos en el marco de un trabajo de fin de grado.  

**Autor**: Carlos Andrés Aragón Nacimba.

**Año**: 2025

---
