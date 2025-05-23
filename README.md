# Detalles IAsistente
Un plugin de WordPress que integra un chatbot de IA personalizable. Este chatbot funciona con una base de conocimiento definida por el usuario a través de un archivo JSON. El sistema procesa el JSON cargado para generar respuestas contextualmente relevantes, asegurando que el chatbot solo responda preguntas basadas en la información proporcionada.

== Descripción ==

**IAsistente** es un **asistente virtual inteligente** que permite a los visitantes de tu sitio web obtener información sobre tu empresa de manera instantánea y precisa. Este chatbot está diseñado para **responder preguntas basándose exclusivamente en la información que le proporcionas**, asegurando que las respuestas estén siempre alineadas con tus datos corporativos.

Características principales:

* **Interfaz flotante** moderna y profesional que se integra elegantemente en tu sitio.
* **Respuestas basadas en los datos de tu empresa** cargados en formato JSON.
* **Configuración sencilla** de la API de inteligencia artificial (OpenAI, Deepseek o compatible).
* **Personalización completa del diseño**: ajusta colores, posición y título para que coincida con tu marca.
* **Completamente responsive**: funciona perfectamente en dispositivos móviles y tablets.
* **Soporte para Markdown** en las respuestas para un formato enriquecido.
* **Historial de conversación** para una mejor experiencia de usuario.
* **Fácil integración** con cualquier tema de WordPress.

El plugin utiliza la API de inteligencia artificial de tu elección para procesar las preguntas de los usuarios y generar respuestas coherentes y contextuales, siempre y cuando la información se encuentre en tu archivo JSON.

== Instalación ==

1.  Sube el archivo ZIP del plugin a tu instalación de WordPress desde `Plugins > Añadir nuevo > Subir plugin`.
2.  Activa el plugin a través del menú `Plugins` en WordPress.
3.  Dirígete a la sección `IAsistente` en el menú de administración de WordPress.
4.  Configura tu API key y sube el archivo JSON con los datos de tu empresa.
5.  El chatbot aparecerá automáticamente en tu sitio web.

== Configuración ==

Después de activar el plugin, sigue estos pasos para configurarlo:

1.  Obtén una **API key** de OpenAI, Deepseek o tu proveedor de IA preferido.
2.  Prepara un archivo **JSON** con toda la información relevante de tu empresa.
3.  Ve a `IAsistente` en el menú de WordPress.
4.  Ingresa los siguientes datos:
    * **URL de la API**
    * **API Key**
    * **Modelo a utilizar** (de tu proveedor de IA)
5.  Sube el **archivo JSON** con los datos de tu empresa.
6.  **Personaliza la apariencia** del chatbot (opcional) para que se adapte a tu sitio.

== Preguntas frecuentes ==

= ¿Qué formato debe tener el archivo JSON? =
El archivo JSON puede contener cualquier información estructurada sobre tu empresa que desees que el chatbot utilice para responder. Aquí tienes un ejemplo básico de cómo podría lucir:

```json
{
    "nombre_empresa": "Mi Empresa",
    "descripcion": "Somos una empresa dedicada a la provisión de servicios innovadores...",
    "servicios": ["Servicio 1: Desarrollo Web", "Servicio 2: Consultoría Digital"],
    "contacto": {
        "email": "info@miempresa.com",
        "telefono": "+123456789",
        "direccion": "Calle Ficticia 123, Ciudad"
    },
    "horario_atencion": "Lunes a Viernes, de 9:00 AM a 6:00 PM"
}
```
