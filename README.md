# Práctica 2 UT02 - OWASP Juice Shop + OWASP ZAP Vulnerability Scan

Este proyecto se ha ejecutado como práctica del módulo "Puesta en Producción Segura" del curso de especialización en Ciberseguridad.
Se muestra una auditoría de seguridad web realizada como práctica formativa sobre la aplicación vulnerable **OWASP Juice Shop** utilizando **OWASP ZAP**, una herramienta automatizada de análisis de seguridad para aplicaciones web.

---

## 🔧 Herramientas utilizadas
- Entorno Virtual en una máquina kali Linux, alojada en oracle VM Virtualbox 7.0.20
- OWASP Juice Shop (`http://127.0.0.1:3000`)
- OWASP ZAP 2.15.0
- Navegador Firefox + proxy ZAP

## 🎯 Objetivos
- Simular un entorno de pentesting web.
- Detectar y documentar vulnerabilidades reales.
- Demostrar habilidades en análisis automatizado y validación manual de riesgos.
- Afianzar conceptos impartidos en clase
- Mejorar el uso de las herramientas de OWASP
- Generar un reporte en HTML

## 📋 Logros realizados
- 🏆 *Zero Stars Achievement* (modificación del `rating` vía interceptación con ZAP).
- 🔍 Escaneo automatizado completo con reporte HTML incluido.

## 📄 Principales vulnerabilidades detectadas
- 🔴 Open Redirect (`High`)
- 🟠 Falta de anti-clickjacking headers
- 🟠 Inclusión de Session ID en URLs
- 🟡 Disclosure de IPs privadas y errores de aplicación
- 🔵 Otras informativas (comentarios sospechosos, encabezados faltantes)

## 📌 Notas

Este proyecto forma parte del aprendizaje y no está destinado a producción.  
Realizado como parte del ciclo de Grado de especialización en Ciberseguridad.

## 📂 Archivos importantes
📷  [Reporte_HTML](https://github.com/nerxtkd/juice-shop-owasp-zap-audit/blob/main/report/ZAP-Report-127.0.0.1.html)
📄  [Juice-Shop-Owasp-Zap-Audit_UT02_Práctica2_PPS.pdf](https://github.com/nerxtkd/Documentaciones/blob/main/Juice-Shop-Owasp-Zap-Audit_UT02_Pr%C3%A1ctica2_PPS.pdf)

## 👩‍💻 Autora:
Trabajo realizado por Nerea C. 
Puedes ver otros proyectos en mi perfil de GitHub: [@nerxtkd](https://github.com/nerxtkd)


