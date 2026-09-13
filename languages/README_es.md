# RefreshMate

[English](../README.md) | [中文](README_zh.md) | [日本語](README_ja.md) | [Deutsch](README_de.md) | Español | [Français](README_fr.md)

Una extensión ligera para el navegador que permite la actualización automática de páginas con intervalos personalizables y alertas por cambio de palabras clave.

> Basada en Chromium · Manifest V3 · Permisos mínimos · Solo local

---

## ¿Por qué RefreshMate?

¿Necesitas monitorizar una página para detectar cambios? RefreshMate actualiza las páginas automáticamente según tu planificación y te avisa cuando aparecen o desaparecen palabras clave — ideal para seguimiento de acciones, venta de entradas o cualquier página con contenido sensible al tiempo.

| Ventaja | Detalle |
|---------|--------|
| ⏱️ **Intervalos personalizados** | Preajustes rápidos (5s/30s/1min/5min) + entrada personalizada |
| 🎲 **Intervalo aleatorio** | Rango aleatorio anti-detección para evitar bloqueos del sitio |
| 🔔 **Alertas por palabras clave** | Notificaciones del navegador cuando aparecen o desaparecen palabras clave |
| 🔒 **Detección de CAPTCHA** | Detiene automáticamente la actualización cuando se detecta un CAPTCHA |
| 💾 **Configuración por sitio** | Cada dominio guarda su propia configuración de forma independiente |

---

## Funcionalidades

| Funcionalidad | Descripción |
|---------|-------------|
| ⏱️ **Actualización automática** | Configura intervalos desde 5 segundos hasta horas |
| 🎲 **Rango aleatorio** | Establece un rango mínimo/máximo, el intervalo se aleatoriza en cada ciclo |
| 🧹 **Actualización forzada** | Omite la caché con una recarga tipo Ctrl+Shift+R |
| 🔔 **Monitor de palabras clave** | Alerta cuando un texto aparece o desaparece en la página |
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
| 🆘 **Soporte prioritario** | — | ✅ |

La versión gratuita actualiza **solo una pestaña a la vez** en todo el navegador. Pásate a Pro para actualizar varias pestañas simultáneamente.

---

## Navegadores compatibles

| Navegador | Estado |
|---------|--------|
| Google Chrome | ✅ Totalmente compatible |
| Microsoft Edge | ✅ Totalmente compatible |
| Otros basados en Chromium | ✅ Debería funcionar |

---

## Instalación

1. Clona o descarga este repositorio
2. Abre `chrome://extensions/` (o `edge://extensions/`)
3. Activa el **modo de desarrollador**
4. Haz clic en **Cargar descomprimida** → selecciona la carpeta `RefreshMate`
5. Haz clic en el icono 🔄 de RefreshMate para empezar

### Compilación

```bash
npm install
npm run build
```

---

## Privacidad

- **activeTab** — Accede a la pestaña actual cuando interactúas con la extensión
- **tabs** — Busca pestañas para actualizar por dominio
- **storage** — Guarda la configuración localmente
- **alarms** — Programa temporizadores de actualización
- **notifications** — Notificaciones del navegador para alertas por palabras clave
- **Validación de licencia** — huella de dispositivo anónima + clave de licencia enviada a `api.annmax1983.com` una vez cada 24h. No se transmiten datos de navegación.

**[📄 Política de privacidad](privacy-policy.html)**

---

## Licencia

Copyright © 2026 RefreshMate. Todos los derechos reservados.
