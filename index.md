# 📝 Banco de Ideas

_Creado el 19 de mayo de 2026_

---

## Ideas pendientes

### 💡 Idea 1: Contestadora automática para WhatsApp
- **Fecha:** 19 mayo 2026
- **Descripción:** Sistema de contestadora de mensajes donde pueda decirle "respóndele a tal persona" y envíe un mensaje por WhatsApp automáticamente.
- **Posibles funcionalidades:**
  - Identificar contacto por nombre o número
  - Enviar mensaje de texto automáticamente
  - Posible integración con voz para dictar el mensaje
  - Respuestas rápidas predefinidas
  - Historial de mensajes enviados
- **Notas técnicas:**
  - **Opción A - WhatsApp Cloud API (oficial):**
    - API oficial de Meta, gratuita hasta 1000 conversaciones/mes
    - Requiere cuenta de desarrollador en Meta y verificar un número de negocio
    - Se usa con curl o librerías Python
    - Ventajas: confiable, soportado oficialmente, mensajes automáticos
    - Desventajas: proceso de verificación, restricciones de plantillas
  
  - **Opción B - WhatsApp Web automation (no oficial):**
    - selenium/playwright para automatizar WhatsApp Web
    - Librerías como: `pywhatkit`, `selenium-whatsapp`, `whatsapp-web.js`
    - Ventajas: más flexible, no requiere verificación
    - Desventajas: menos estable, puede banearte si detectan
  
  - **Opción C - Librerías de terceros:**
    - `twilio` API para WhatsApp (pagada pero fácil de usar)
    - `callmebot` API gratuita (limitada)
    - `wenbot` u otras soluciones open-source
  
  - **Integración con TTS:** Ya tenemos TTS configurado (es-MX-DaliaNeural) para convertir voz a texto del mensaje
  - **Integración con Hermes:** Se podría crear un comando como "respóndele a María que llego tarde"
- **Estado:** ⏸️ Standby - opciones investigadas, pendiente de reactivar

### 💡 Idea 2: Portafolio de desarrollo web
- **Fecha:** 19 mayo 2026
- **Descripción:** Crear un portafolio profesional de desarrollo web para mostrar proyectos, habilidades y experiencia.
- **Estado:** 📋 Investigación en curso → ver `investigacion-portafolio-web.md`

### 💡 Idea 3: Monitoreo de cámaras en múltiples locaciones con notificaciones
- **Fecha:** 20 mayo 2026
- **Descripción:** Sistema que monitoree cámaras de seguridad Tapo y Steren distribuidas en varias ciudades/locaciones y envíe notificaciones automáticas si alguna cámara se apaga o pierde conexión. Integración con Zoho Cliq y Telegram como canales de notificación.
- **Posibles funcionalidades:**
  - Monitoreo remoto de cámaras Tapo (vía API cloud de Tapo)
  - Monitoreo de cámaras Steren (vía API cloud de Tuya/Steren Home)
  - Detección de estado offline/apagado en tiempo real
  - Notificaciones automáticas por Zoho Cliq y Telegram
  - Dashboard con estado de todas las cámaras
  - Historial de eventos (cuándo se cayó, cuándo volvió)
- **Notas técnicas:**
  - **Tapo:** Librerías `pytapo` o `k4t1/tapo` - se autentican con email/contraseña de la app Tapo, consultan estado de todas las cámaras remotamente sin necesidad de acceder a la red local
  - **Steren Home:** Probablemente usa plataforma Tuya Cloud → se necesita cuenta developer en developer.tuya.com con Access ID y Access Secret
  - **Zoho Cliq:** Webhook de entrada (incoming webhook) → POST a URL del canal con el mensaje
  - **Arquitectura:** Cron job cada 5-10 min → script Python → API cloud → notificación si hay cámaras offline
  - **Ventaja del enfoque cloud:** No necesita acceso a las redes locales de cada locación, todo se resuelve vía APIs de los fabricantes
  - **Alternativa si la API no existe:** Agentes locales en cada locación que reporten estado a un servidor central
- **Estado:** 🆕 Nueva - investigación pendiente de APIs de Tapo y Steren Home

---

## Ideas en desarrollo

---

## Ideas completadas

---
