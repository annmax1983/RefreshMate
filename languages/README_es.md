# RefreshMate

[English](../README.md) | [中文](README_zh.md) | [日本語](README_ja.md) | [Deutsch](README_de.md) | Español | [Français](README_fr.md)

Una extensión ligera para el navegador que permite la actualización automática de páginas con intervalos personalizables. Los intervalos aleatorios y las alertas por cambio de palabras clave son funciones Pro.

> Chrome / Edge / Firefox · Manifest V3 · Permisos mínimos · Solo local

---

## ¿Por qué RefreshMate?

¿Necesitas monitorizar una página para detectar cambios? RefreshMate actualiza las páginas automáticamente según tu planificación. Pro añade avisos cuando aparecen o desaparecen palabras clave — ideal para seguimiento de acciones, venta de entradas o cualquier página con contenido sensible al tiempo.

| Ventaja | Detalle |
|---------|--------|
| ⏱️ **Intervalos personalizados** | Preajustes rápidos (5s/30s/1min/5min) + entrada personalizada |
| 🎲 **Intervalo aleatorio (Pro)** | Rango aleatorio anti-detección para evitar bloqueos del sitio |
| 🔔 **Alertas por palabras clave (Pro)** | Notificaciones del navegador cuando aparecen o desaparecen palabras clave |
| 🔒 **Detección de CAPTCHA** | Detiene automáticamente la actualización cuando se detecta un CAPTCHA |
| 💾 **Configuración por sitio** | Cada dominio guarda su propia configuración de forma independiente |

---

## Funcionalidades

| Funcionalidad | Descripción |
|---------|-------------|
| ⏱️ **Actualización automática** | Configura intervalos desde 5 segundos hasta horas |
| 🎲 **Rango aleatorio (Pro)** | Establece un rango mínimo/máximo, el intervalo se aleatoriza en cada ciclo |
| 🧹 **Actualización forzada** | Omite la caché con una recarga tipo Ctrl+Shift+R |
| 🔔 **Monitor de palabras clave (Pro)** | Alerta cuando un texto aparece o desaparece en la página |
| ⚠️ **Detección de CAPTCHA** | Detecta patrones comunes de CAPTCHA y se detiene automáticamente |
| 🖼️ **Superposición flotante** | Mini temporizador de cuenta atrás en la página |
| ⌨️ **Pausa automática** | Se pausa al escribir en campos de entrada |
| 💾 **Memoria por dominio** | Configuración por sitio guardada automáticamente |

---

## Gratis vs Pro

| Capacidad | Gratis | Pro (Licencia) |
|------------|------|----------------|
| 🗂️ **Pestañas simultáneas** | **1 pestaña** a la vez | ✅ Ilimitadas |
| 🎲 **Rango de intervalo aleatorio** | — | ✅ |
| 🔔 **Alertas por palabra clave / regex** | — | ✅ |
| 🔄 **Detección de cualquier cambio en la página** | — | ✅ |

La versión gratuita actualiza **solo una pestaña a la vez** en todo el navegador. Pásate a Pro para actualizar varias pestañas simultáneamente.

---

## Navegadores compatibles

| Navegador | Estado |
|---------|--------|
| Google Chrome | ✅ Totalmente compatible |
| Microsoft Edge | ✅ Totalmente compatible |
| Mozilla Firefox | ✅ Totalmente compatible |
| Otros basados en Chromium | ✅ Debería funcionar |

> **Nota sobre Firefox:** Firefox no dispone de documento offscreen, así que el sonido de aviso se reproduce directamente desde el script de fondo; la versión de Firefox no solicita el permiso `offscreen`. El resto de funciones se comporta igual que en Chrome / Edge.

---

## Instalación

| Tienda | Enlace |
|---|---|
| Chrome Web Store | [Instalar en Chrome](https://chromewebstore.google.com/detail/camggpihgjdgbjnidhdalapchepdflbg) |
| Complementos de Microsoft Edge | [Instalar en Edge](https://microsoftedge.microsoft.com/addons/detail/ikgfdokioakgjgcmofboemcmahhnijjg) |
| Complementos de Firefox (AMO) | 🔜 En revisión: el enlace se añadirá al publicarse |

> Instale solo desde las tiendas oficiales de arriba; evite sitios de descarga de terceros.

---

## Privacidad

- **activeTab** — Accede a la pestaña actual cuando interactúas con la extensión
- **tabs** — Busca pestañas para actualizar por dominio
- **storage** — Guarda la configuración localmente
- **alarms** — Programa temporizadores de actualización
- **notifications** — Notificaciones del navegador para alertas por palabras clave
- **Validación de licencia** — un identificador de instalación aleatorio + clave de licencia enviada a `api.annmax1983.com` una vez cada 2h. No se transmiten datos de navegación.

**[📄 Política de privacidad](privacy-policy.html)**

---

## Licencia

Copyright © 2026 RefreshMate. Todos los derechos reservados.
