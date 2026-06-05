# Cybersecurity Incident Report - Brute Force Attack Analysis

## Descripción del proyecto

Este proyecto documenta la investigación de un incidente de ciberseguridad que afectó al sitio web yummyrecipesforme.com.

Durante el incidente, un atacante obtuvo acceso no autorizado al panel administrativo mediante un ataque de fuerza bruta. Posteriormente modificó el código fuente del sitio web para distribuir malware a los visitantes y redirigirlos a un sitio web malicioso.

---

## Objetivos

* Analizar el incidente de seguridad.
* Identificar el método utilizado por el atacante.
* Reconocer los protocolos de red involucrados.
* Determinar la causa raíz del incidente.
* Recomendar controles de seguridad para prevenir eventos similares.

---

## Conceptos de ciberseguridad aplicados

* Brute Force Attack
* Malware
* DNS
* HTTP
* JavaScript malicioso
* Redirección maliciosa
* Control de acceso
* Two-Factor Authentication (2FA)
* Gestión de credenciales

---

## Hallazgos principales

* Un atacante obtuvo acceso al panel administrativo mediante un ataque de fuerza bruta.
* La cuenta administrativa utilizaba una contraseña por defecto.
* El sitio web fue modificado para distribuir malware.
* Los visitantes eran redirigidos a un dominio malicioso.
* Se identificó el uso de los protocolos DNS y HTTP durante el incidente.
* La ausencia de controles contra ataques de fuerza bruta facilitó la intrusión.

---

## Estructura del proyecto

attack-analysis.md → Análisis técnico del incidente

assets/ → Diagramas, dashboards y evidencias visuales

---

## Recomendación principal

Implementar autenticación de dos factores (2FA) en todas las cuentas administrativas para reducir significativamente el riesgo de acceso no autorizado.

---

## Conclusión

El incidente demostró cómo una contraseña débil o por defecto puede comprometer por completo un sitio web. La implementación de controles de autenticación más robustos y la supervisión continua de los accesos administrativos son medidas fundamentales para proteger los sistemas contra ataques de fuerza bruta.
