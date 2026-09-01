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
* Consulta el informe técnico detallado en la carpeta [`/docs/informe_soc.md`](docs/informe_soc.md).
* Revisa el código de las reglas personalizadas en [`/rules/local_rules.xml`](rules/local_rules.xml).
* Las capturas de pantalla del panel de alertas se encuentran en la carpeta [`/img/`](img/).
