# Análisis de Ataque por Fuerza Bruta

## Resumen del incidente

Un ex empleado obtuvo acceso no autorizado al panel administrativo del sitio web yummyrecipesforme.com mediante un ataque de fuerza bruta. Una vez dentro del sistema, modificó el código fuente del sitio web e insertó código JavaScript malicioso.

El código agregado solicitaba a los visitantes descargar un archivo ejecutable. Después de ejecutar el archivo, los usuarios eran redirigidos a un sitio web diferente que contenía malware.

## Tipo de ataque identificado

Brute Force Attack (Ataque de Fuerza Bruta)

## Evidencia observada

* Acceso no autorizado a la cuenta administrativa.
* Uso de contraseñas por defecto.
* Modificación del código fuente del sitio web.
* Inserción de código JavaScript malicioso.
* Descarga de archivos ejecutables por parte de los visitantes.
* Redirección a un sitio web con malware.

## Protocolos identificados

### DNS

Utilizado para resolver la dirección IP de los dominios involucrados durante la navegación.

### HTTP

Utilizado para solicitar las páginas web y transferir el contenido que contenía el código malicioso.

## Impacto técnico

* Compromiso del sitio web.
* Distribución de malware a visitantes.
* Redirección a sitios web maliciosos.
* Acceso no autorizado al panel administrativo.

## Impacto para el negocio

* Pérdida de confianza por parte de los usuarios.
* Daño reputacional.
* Posibles pérdidas económicas.
* Riesgo para la información y dispositivos de los clientes.

## Causa raíz

La cuenta administrativa mantenía una contraseña por defecto y no existían controles adecuados para prevenir ataques de fuerza bruta.

## Recomendación

Implementar autenticación de dos factores (2FA) para las cuentas administrativas. De esta manera, incluso si un atacante descubre una contraseña válida, seguirá necesitando un segundo factor de autenticación para acceder al sistema.
