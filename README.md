# SOC Home Lab: Detección de Amenazas con Wazuh

Proyecto de laboratorio SOC implementado en un entorno virtualizado para la monitorización de endpoints, análisis de registros de autenticación y creación de reglas de detección personalizadas.

## Arquitectura del Laboratorio
* **Ubuntu Server**: Wazuh Manager (SIEM centralizado).
* **Ubuntu Desktop**: Endpoint monitorizado (Agente Wazuh y cortafuegos UFW).
* **Kali Linux**: Máquina atacante para emulación de amenazas (reconocimiento y fuerza bruta).

## Objetivos del Proyecto
* Monitorización de telemetría y eventos de seguridad en sistemas Linux.
* Análisis de registros e identificación de ataque.
* Creacion de reglas personalizadas básicas en Wazuh para la detección de escaneos de red (Nmap) y ataques de fuerza bruta (Hydra).

## Evidencias y Documentación
* **Informe Técnico Oficial**: Puedes consultar el análisis L1 completo en formato PDF en la ruta [`/docs/Informe_SOC_L1_Wazuh.pdf`](docs/Informe_SOC_L1_Wazuh.pdf).
* **Reglas Personalizadas**: El código fuente de las reglas de detección se encuentra en la carpeta [`/rules/`](rules/).
* **Capturas de Evidencias**: Las imágenes del panel de Wazuh están alojadas en la carpeta [`/img/`](img/).
