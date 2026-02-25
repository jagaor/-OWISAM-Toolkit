# OWISAM-TOOLKIT-GD: Auditoría de Directivas y Cumplimiento Wi-Fi 🛡️⚖️

## 📝 Descripción del Proyecto
Este proyecto consiste en el desarrollo de una herramienta avanzada en **Python** diseñada para la auditoría de redes inalámbricas bajo el estándar **OWISAM-GD (Governance & Directives)**. 

A diferencia de los escaneadores convencionales, esta solución no solo identifica parámetros técnicos, sino que los contrasta automáticamente con marcos normativos y buenas prácticas de ciberseguridad (ISO 27001, INCIBE y OWISAM). El objetivo es transformar datos crudos de red en informes de cumplimiento estratégico.

## 🚀 Alcance y Funcionalidades
**Análisis de Cumplimiento Automático:** Verificación de SSIDs, protocolos de cifrado y configuraciones de seguridad frente a políticas corporativas.
**Evaluación de Riesgos Estructurada:** Clasificación de redes según su nivel de exposición y su alineación con estándares internacionales.
**Motor de Auditoría Nativo:** Desarrollo íntegro desde cero utilizando la librería **Scapy** para la captura, inyección y filtrado de paquetes 802.11, evitando la dependencia de suites externas como Aircrack-ng.
**Generación de Reportes de Cumplimiento:** Salida detallada (JSON/Texto) que resume el estado de salud de la infraestructura Wi-Fi analizada.

## 🛠️ Stack Tecnológico
**Lenguaje:** Python 3.10+
**Librería Principal:** [Scapy](https://scapy.net/) (Manipulación de paquetes a bajo nivel).
**Entorno:** Linux con interfaz de red en modo monitor.
**Referentes Normativos:** OWISAM (Top 10), ISO/IEC 27001, Guías de INCIBE.

## 📂 Estructura del Repositorio
/src: Código fuente del motor de auditoría basado en Scapy.
/rules: Archivos de configuración con las directivas de seguridad a auditar.
/docs: Documentación técnica sobre la metodología OWISAM-GD aplicada.
/output: Ejemplos de los reportes de cumplimiento generados.

## ⚙️ Requisitos Previos
Para ejecutar esta herramienta, es necesario contar con privilegios de superusuario (root) y una tarjeta de red compatible con el modo monitor.
bash

sudo pip install scap
