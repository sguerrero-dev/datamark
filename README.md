# DataMark

Prototipo funcional de **DataMark**, plataforma SaaS de analítica en tiempo real y automatización de marketing multicanal.
Proyecto de Ingeniería de Software · Universidad de la Costa (CUC) · 2026-2.

**Integrantes:** Jonathan Molina · Orlando Hernández · Santiago Guerrero

## Links

| Qué | Link |
|---|---|
| App en vivo (GitHub Pages) | https://sguerrero-dev.github.io/datamark/ |
| Inicio de sesión | https://sguerrero-dev.github.io/datamark/#login |
| Registro de empresa | https://sguerrero-dev.github.io/datamark/#registro |
| Repositorio | https://github.com/sguerrero-dev/datamark |

## Cuentas de demostración

| Rol | Correo | Contraseña | Pantalla inicial |
|---|---|---|---|
| SuperAdmin | admin@datamark.co | `demo123` | https://sguerrero-dev.github.io/datamark/#admin |
| Usuario Empresa | empresa@cafearhuaco.co | `demo123` | https://sguerrero-dev.github.io/datamark/#inicio |
| Analista / Marketer | analista@cafearhuaco.co | `demo123` | https://sguerrero-dev.github.io/datamark/#inicio |

En la pantalla de inicio de sesión también hay botones para entrar directo con cada rol. Los links de cada pantalla funcionan después de iniciar sesión.

### Pantallas por rol

- **SuperAdmin:** [Inicio](https://sguerrero-dev.github.io/datamark/#admin) · [Empresas](https://sguerrero-dev.github.io/datamark/#empresas) · [Usuarios y permisos](https://sguerrero-dev.github.io/datamark/#usuarios) · [Suscripciones](https://sguerrero-dev.github.io/datamark/#suscripciones) · [Monitoreo](https://sguerrero-dev.github.io/datamark/#monitoreo)
- **Usuario Empresa:** [Inicio](https://sguerrero-dev.github.io/datamark/#inicio) · [Canales](https://sguerrero-dev.github.io/datamark/#canales) · [Automatizaciones](https://sguerrero-dev.github.io/datamark/#automatizaciones) · [Contactos](https://sguerrero-dev.github.io/datamark/#contactos) · [Reportes](https://sguerrero-dev.github.io/datamark/#reportes)
- **Analista / Marketer:** [Inicio](https://sguerrero-dev.github.io/datamark/#inicio) · [Analítica por canal](https://sguerrero-dev.github.io/datamark/#analitica) · [Segmentación](https://sguerrero-dev.github.io/datamark/#segmentacion) · [Reportes](https://sguerrero-dev.github.io/datamark/#exportar) · [Campañas](https://sguerrero-dev.github.io/datamark/#campanas)
- **Todos:** [Configuración](https://sguerrero-dev.github.io/datamark/#configuracion)

## Qué incluye

- Inicio de sesión por rol, registro de empresa (Habeas Data) y cierre de sesión (R1-1 a R1-5).
- Panel en tiempo real: cifra principal, gráfica de área con filtros (Hoy, 7 días, 30 días y canal), objetos con más interacción, rendimiento por canal y feed «Actividad en vivo» con pausa (RF13, RF14).
- Clic en un evento o contacto: perfil con historial y automatizaciones aplicadas.
- Canales: conectar / desconectar red social, formulario y pasarela de pago con avisos de éxito o fallo (R2-1 a R2-5).
- Automatizaciones: asistente de 3 pasos para crear, editar, pausar y eliminar reglas (RF18 a RF21). Las reglas activas se aplican a los eventos en vivo.
- Reportes y campañas con aviso de ejecución exitosa o fallida (RF22) y generación de reportes PDF/Excel (RF15, RF17).
- Analista: analítica por canal, segmentación y campañas.
- SuperAdmin: estado de la plataforma, empresas, usuarios y permisos (RF23 a RF27), suscripciones y monitoreo.
- Buscador global con **Ctrl+K**, notificaciones, menú lateral colapsable y diseño responsivo.

Los datos son de prueba (mocks) con la misma forma de los JSON del WebSocket definidos en la guía de interfaz; los cambios se guardan en el navegador.

## Ejecutar

Es un solo archivo: abre `index.html` en el navegador o publícalo con GitHub Pages.
