# n8n-workflows-quantixlabs.
“Colección de más de 2.000 workflows para n8n”.
# Quantix Labs n8n Workflows Collection

Bienvenido a **Quantix Labs n8n Workflows**, una recopilación de más de **2 000 workflows** para [n8n](https://n8n.io/), la plataforma de automatización de código abierto. Este repositorio existe para compartir conocimiento y acelerar el desarrollo de automatizaciones: algunos de estos flujos se venden en otros lugares, pero aquí creemos en el poder de la comunidad y los ofrecemos de forma gratuita.

## ¿Qué incluye?

- **Automatización de correos**: plantillas para gestionar notificaciones, respuestas automáticas y seguimiento.
- **Bots de mensajería**: flujos listos para crear bots de Telegram, Discord o Slack.
- **Integraciones con IA**: ejemplos de integración con modelos GPT y otras APIs de inteligencia artificial.
- **Scraping y datos**: workflows para extraer información de sitios web y organizar datos en hojas de cálculo o bases de datos.
- **ERP/CRM**: integraciones con ERPNext, Odoo y CRM populares para automatizar procesos empresariales.
- **Utilidades variadas**: herramientas de conversión, procesado de textos, generación de informes, calendarios, etc.

La estructura de carpetas refleja las diferentes categorías de workflows. Cada archivo `.txt` contiene el JSON del flujo exportado desde n8n.

## Cómo usar estos workflows

1. **Descarga y descomprime** el archivo `Workflow-n8n.zip` desde Releases o desde la raíz del repositorio.
2. **Convierte los archivos** `.txt` a `.json` – cada archivo de este repositorio está en formato TXT, pero n8n sólo acepta flujos en formato JSON. Basta con cambiar la extensión de cada archivo a `.json` (puedes hacerlo desde tu sistema operativo o con un script) para que n8n los reconozca.
3. En tu instancia de n8n, selecciona **Import workflow** y carga el archivo `.json` (o arrástralo sobre el editor). n8n creará un nuevo flujo con las configuraciones incluidas.
4. **Adapta** cada workflow a tus credenciales y variables. Muchos flujos usan nodos genéricos; deberás configurar tus propias API keys, credenciales o conexiones.
5. **Combina y modifica**: estos ejemplos están pensados como inspiración. Úsalos como base para construir soluciones más complejas.

> **Nota:** No todos los workflows han sido probados en todas las versiones de n8n. Si encuentras un problema, abre un *issue* o envía un *pull request* para mejorarlo.

## Licencia

Distribuimos este repositorio bajo licencia **MIT**. Puedes copiar, modificar y compartir libremente el contenido. Agradecemos el reconocimiento y la contribución de mejoras. Si vendes una solución basada en estos flujos, considera contribuir de vuelta a la comunidad.

## Contribuir

¿Tienes workflows que quieras compartir? ¡Serán bienvenidos! Haz un *fork* de este repositorio, añade tus archivos en la carpeta correspondiente y envía un *pull request*. También puedes abrir un *issue* para pedir nuevas categorías o sugerir cambios.

## Sobre Quantix Labs

En [Quantix Labs](https://quantixlabs.io/) creemos en la **Quantum Intelligence**: automatizamos el presente para dominar el futuro. Ofrecemos agentes de IA, automatizaciones personalizadas y consultoría para empresas que quieren ir un paso por delante. Síguenos en [Instagram](https://instagram.com/quantixlabs.io) y únete a nuestra comunidad en Telegram para recibir más recursos, tutoriales y soporte.

---
*¡Disfruta de los workflows y construyamos juntos un ecosistema de automatización abierto!*
