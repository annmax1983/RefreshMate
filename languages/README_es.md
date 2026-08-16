# RefreshMate
[English](../README.md) | [中文](README_zh.md) | [日本語](README_ja.md) | [Deutsch](README_de.md) | Español | [Français](README_fr.md)

Una extensión ligera de navegador para actualizar páginas automáticamente con intervalos configurables y alertas de cambios de palabras clave.

> Basado en Chromium · Manifest V3 · Permisos mínimos · Solo local

---

## ¿Por qué RefreshMate?

¿Necesitas monitorear una página para detectar cambios? RefreshMate actualiza páginas automáticamente según tu horario y te alerta cuando las palabras clave aparecen o desaparecen — perfecto para el seguimiento de acciones, la venta de entradas o cualquier página sensible al tiempo.

| Ventaja | Detalle |
|---------|---------|
| ⏱️ **Intervalos personalizados** | Atajos rápidos (5s/30s/1min/5min) + entrada personalizada |
| 🎲 **Intervalo aleatorio** | Rango aleatorio anti-detección para evitar bloqueos |
| 🔔 **Alertas de palabras clave** | Notificaciones del navegador al aparecer/desaparecer |
| 🔒 **Detección de CAPTCHA** | Detiene la actualización al detectar CAPTCHA |
| 💾 **Ajustes por sitio** | Cada dominio guarda su propia configuración |

---

## Funciones

| Función | Descripción |
|---------|-------------|
| ⏱️ **Actualización automática** | Intervalos desde 5 segundos hasta horas |
| 🎲 **Rango aleatorio** | Rango mínimo/máximo, intervalo aleatorio en cada ciclo |
| 🧹 **Forzar actualización** | Omite la caché (estilo Ctrl+Shift+R) |
| 🔔 **Monitor de palabras clave** | Alerta cuando el texto aparece o desaparece |
| ⚠️ **Detención por CAPTCHA** | Detecta patrones comunes de CAPTCHA y se detiene automáticamente |
| 🖼️ **Superposición flotante** | Mini temporizador de cuenta atrás en la página |
| ⌨️ **Pausa automática** | Pausa al escribir en campos de entrada |
| 💾 **Memoria de dominio** | Ajustes por sitio guardados automáticamente |

---

## Gratis vs. Pro

| Función | Gratis | Pro (Licencia) |
|---------|--------|-----------------|
| 🗂️ **Pestañas simultáneas** | **1 pestaña** a la vez | ✅ Ilimitado |
| 🎲 **Rango de intervalo aleatorio** | — | ✅ |
| 🔔 **Alertas de palabras clave / regex** | — | ✅ |
| 🔄 **Detección de cualquier cambio** | — | ✅ |
| 🆘 **Soporte prioritario** | — | ✅ |

La versión gratuita actualiza **solo una pestaña a la vez** en todo el navegador. Mejora a Pro para actualizar varias pestañas simultáneamente.

---

## Navegadores compatibles

| Navegador | Estado |
|-----------|--------|
| Google Chrome | ✅ Totalmente compatible |
| Microsoft Edge | ✅ Totalmente compatible |
| Otros basados en Chromium | ✅ Debería funcionar |

---

## Instalación

1. Clona o descarga este repositorio
2. Abre `chrome://extensions/` (o `edge://extensions/`)
3. Activa el **modo desarrollador**
4. Haz clic en **Cargar descomprimida** → selecciona la carpeta `RefreshMate`
5. Haz clic en el icono 🔄 RefreshMate para empezar

### Compilación

```bash
npm install
npm run build
```

---

## Privacidad

- **activeTab** — Accede a la pestaña actual al interactuar
- **tabs** — Encuentra pestañas para actualizar por dominio
- **storage** — Guarda los ajustes localmente
- **alarms** — Programa los temporizadores de actualización
- **notifications** — Notificaciones del navegador para alertas de palabras clave
- **Validación de licencia** — huella digital anónima del dispositivo + clave de licencia enviadas a `api.annmax1983.com` una vez cada 24 h. No se transmiten datos de navegación.

**[📄 Política de privacidad](../privacy-policy.html)**

---

## Licencia

Copyright © 2026 RefreshMate. Todos los derechos reservados.

---

> **Nota:** Este repositorio es **solo para la exhibición del proyecto**.
