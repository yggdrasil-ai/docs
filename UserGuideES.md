# Guía de uso
¡Bienvenido a la Guía del usuario de SpokesAI! Este documento proporciona instrucciones detalladas sobre cómo aprovechar al máximo la plataforma SpokesAI.

## Primeros pasos

## Crea tu primer spoke

Piensa en crear tu primer spoke como si estuvieras contratando a alguien para hacer un trabajo. Necesitas proporcionar información sobre el trabajo en sí y sobre cómo quieres que sea ese alguien.

Veamos cómo:

1. **Entra a la app**: Al igual que entrarías a tu oficina, abre la aplicación SpokesAI y ve a la página ‘Spokes’. Aquí es donde encontrarás a todos tus ayudantes.

![Captura de pantalla de la página de spokes](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/images/spokesPageES.JPG)

2. **Crea un nuevo spoke**: Es el momento de ampliar el equipo. Haz clic en el botón ‘+’.

3. **Rellena el formulario**: ¿No contratarías sin una entrevista, verdad? Este formulario es tu oportunidad de definir a tu nuevo fichaje. Tendrás que proporcionar algunos detalles:
  - _Nombre_: Ponle a tu spoke un nombre que te guste. En este ejemplo, usaremos ‘Ripley’.
  - _Descripción corta_: Describe brevemente a tu spoke, para reconocerlo fácilmente más tarde. Este campo no afecta su comportamiento. Para nuestro ejemplo, escribiremos "Spoke de Primeros Pasos".
  - _Cerebro_: Este es el modelo de IA que dará poder a tu spoke. Determina cuán avanzadas y precisas serán sus respuestas, qué se le dará mejor y peor y, en algunos casos, aumentará el coste de las conversaciones. Por ahora, seleccionemos ‘gpt-3.5-turbo’, una buena opción en general.
  - _Idioma_: Elije el principal idioma de tu spoke. Elegiremos ‘SPA’.
  - _Primer mensaje_: Este es el primer mensaje que veréis, tú y aquellos con los que compartas tu spoke, cuando interactúen con tu él. Hazlo acogedor. Por ejemplo: ‘¡Hola! ¿En qué puedo ayudarte hoy?’.
  - _Conocimiento_: Puedes seleccionar aquí una Bibliotheca como base de conocimientos para tu spoke. Hablaremos de esto más adelante, por ahora no te preocupes.
  - _Personalidad_: Describe los rasgos de personalidad que quieres que tenga tu spoke. En el ejemplo usaremos, ‘Sarcástico y condescendiente’.
  - _Objetivo_: Define el objetivo principal que debe cumplir tu spoke. En nuestro caso: ‘Proporcionar respuestas precisas y útiles a las preguntas de los usuarios’.
  - _Contexto_: Cualquier información básica que tu spoke necesite mantener presente a lo largo de sus conversaciones. Por ejemplo: 'Ripley es una agente de atención a cliente de FutureNow, una tienda de naves espaciales'.
![Formulario de creación de Spokes relleno](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/images/spokeFormES.JPG)

4. **Guarda tu spoke**: Haz clic en ‘Guardar’ para incorporar oficialmente a Ripley.

5. **Prueba tu spoke**: Es hora de verlo en acción. Haz clic en el botón ‘Chat’ en la página de hablantes para iniciar una conversación.

![Botón 'Chat'](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/images/chatbutton.JPG)
![Conversación de prueba](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/images/testConversationES.JPG)

¡Y ya tienes tu primer spoke! Sin embargo, aún no sabe mucho sobre FutureNow... Vamos a darle una base de conocimientos interesante.

## Dale una bibliotheca a tu spoke

Una bibliotheca es una base de conocimientos que los spokes pueden utilizar en sus conversaciones. Al igual que un miembro del equipo aprendería de los documentos y las pautas de la empresa, un hablante aprende de su bibliotheca.

Proporcionemos a Ripley el conocimiento necesario sobre FutureNow.

1. **Ve a la página Bibliothecas**: Aquí puedes crear y administrar tus bases de conocimientos.

![Página Bibliothecas](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/images/bibliothecasPageES.JPG)

2. **Cree una nueva bibliotheca**: Haga clic en el botón ‘+’.

3. **Suba sus documentos**: Copie y pegue la url o suba los documentos PDF que quieras usar para crear la bibliotheca. No es necesario que comparta idioma con nuestros spokes. Agreguemos toda la documentación de FutureNow que tenemos disponible:
	- [FutureNow summary and description](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/examples/Future%20Now.pdf)
	- [FutureNow products](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/examples/FutureNowProducts.pdf)

![Formulario de creación de bibliotheca](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/images/bibliothecaFormES.JPG)

4. **Guarde su nueva bibliotheca**: Haga clic en ‘Guardar’ para finalizar la creación de su biblioteca. Espere unos minutos hasta que aparezca en la página Bibliothecas (pruebe a recargar la página).

![Página Bibliothecas con la nueva bibliotheca](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/images/bibliothecaExample.JPG)

5. **Asigne la biblioteca a su spoke**: Vuelva a la página ‘Spokes’ y seleccione el spoke al que desea proporcionar la bibliotheca - Ripley en nuestro caso. En la configuración del spoke, busque el menú desplegable ‘Conocimiento’ y seleccione su recién creada bibliotheca. Haga click en el icono de chat bajo el formulario para probarlo.

![Conversación de ejemplo con bibliotheca 1](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/images/testConversationKnowledgeES.JPG) ![Conversación de ejemplo con bibliotheca 2](https://storage.googleapis.com/yggdrasil-ai-hermod-public/docs/images/testConversationKnowledge2ES.JPG)

Os invitamos a comprobar sus respuestas 😉

## Entidades de SpokesAI

### Spoke

En el mundo de nuestra aplicación, un **Spoke** es un asistente personal de IA. Es un modelo de IA avanzado diseñado para comprender, procesar y responder al lenguaje humano, llevando a cabo tareas y acciones como lo haría un miembro de un equipo humano.

#### Configurando tu spoke:

Cuando configuras tu Spoke, establece las reglas y pautas que éste seguirá. Es como describir el ayudante que quieres:

- **Nombre y descripción**: Para identificar fácilmente cada cada Spoke y sus tareas específicas.
- **Cerebro**: este es el cerebro de tu Spoke, el modelo de IA que impulsa su funcionamiento. Generalmente, `gpt-3.5-turbo` (de OpenAI) o `llama-2` (de código abierto de Meta) son buenas opciones para spokes básicos, mientras que `gpt-4` es una selección más cara pero más potente.
- **Idioma**: determina el idioma que tu Spoke utiliza de forma predeterminada para interactuar con los usuarios. Aún podrá entender otros.
- **Primer Mensaje**: Esta es la línea de apertura de tu Spoke, su forma de saludar al mundo. ¡Hazlo amigable y atractivo!
- **Conocimiento**: Equipa a tu Spoke con una sólida base de conocimientos (una bibliotheca) para que pueda proporcionar información precisa. Las bibliothecas se gestionan en una página propia.
- **Personalidad**: Crea una personalidad para tu Spoke. ¿Será divertido y tranquilo o más formal y reservado? Tú decides.
- **Objetivo**: Defina el propósito final de tu Spoke, su misión. Esto guiará las decisiones y acciones de tu ayudante.
- **Contexto**: Proporcione cualquier información general que tu Spoke deba tener en cuenta durante las conversaciones.
- **Acciones**: Asigna tareas a tu Spoke. Ya sea enviar un correo electrónico o iniciar la ejecución de un Zap, son las tareas que podrá realizar cuando lo necesite.

#### Mejores prácticas

Crear el Spoke perfecto es un poco como cocinar: necesitas los ingredientes adecuados en las cantidades justas. Nuestros consejos se resumen en cinco:

1. **Sé específico**: cuantos más detalles proporcione, mejor podrá tu Spoke comprender su función.
2. **Establezca objetivos claros**: un objetivo bien definido mantiene a tu Spoke centrado en lo que es importante para ti.
3. **Desarrolla una personalidad consistente**: Una personalidad consistente hace que las interacciones con tu Spoke sean más atractivas y divertidas
4. **Equípalo con conocimiento**: Cuanto más sepa tu Spoke, con mayor precisión podrá responder preguntas.
5. **Que sea sincero**: Si no quieres que tu Spoke sea demasiado creativo, dile que avise cuando no sabe algo y que nunca mienta, incluyéndolo en su personalidad.

Recuerda, no se trata sólo de configurar tu Spoke, sino de aprender, probar y ajustar continuamente.

### Bibliotheca

Piensa en una **Bibliotheca** como el conjunto de conocimientos a la que tu Spoke puede acceder. Es una recopilación de documentos (actualmente archivos PDF) en un formato que tu Spoke puede usar como fuente de información. Puede proporcionar respuestas más detalladas y precisas haciendo referencia a esta base de conocimientos.

#### Configurando tu Bibliotheca:

Crear una Bibliotheca es similar a construir una biblioteca. Tienes que aportar fuentes a las que tu Spoke pueda recurrir en sus conversaciones:

- **Crear una nueva Bibliotheca**: navega a la página 'Bibliothecas' y haz clic en el botón '+'. Esto te permitirá crear una nueva Bibliotheca.
    
- **Agregar documentos**: proporciona URLs o carga los documentos de los que deseas que tu Spoke aprenda. Los documentos deben estar en formato PDF.
    
- **Asignar la Bibliotheca a un Spoke**: Una vez que hayas creado tu Bibliotheca, puedes asignarla a un Spoke. Esto se hace en la configuración de Spoke, donde encontrarás un menú desplegable de 'Conocimiento' con tus bibliothecas.
    
Recuerde, cuanto más relevantes y completas sea tu Bibliotheca, mejores respuestas darán tu Spokes.

### Acción

En SpokesAI, una **Acción** es una tarea o actividad que un Spoke puede realizar. Es una habilidad que tiene tu Spoke. Las acciones amplían las capacidades de Spoke más allá de simplemente responder consultas. Les permiten interactuar con varios sistemas, herramientas y plataformas para realizar tareas como enviar correos electrónicos, actualizar registros, iniciar procesos y más.

#### Acciones públicas

Las acciones públicas son acciones predefinidas que todos los usuarios de SpokesAI pueden usar. Son desarrolladas y mantenidas por el equipo de SpokesAI y cubren tareas y funcionalidades comunes. Incluyen:

[TO DO: Agregar lista de acciones públicas con descripciones breves]

Para utilizar una acción pública, simplemente agréguela a su configuración de Spoke.

#### Acciones de usuario

Además de las acciones públicas, también puedes crear tus propias acciones. Éstas se conocen como acciones de usuario.

##### Acciones de Zapier

Zapier es una herramienta de automatización en línea que conecta más de 3000 aplicaciones y es una de las formas más sencillas de crear tus propias acciones. Al integrar SpokesAI con Zapier, puedes crear acciones que permitan a tus spokes interactuar con esas aplicaciones. A continuación se muestra un proceso simplificado paso a paso:

[TO DO: agregar una guía paso a paso sobre cómo crear acciones de Zapier]

##### Acciones personalizadas

[TO DO: Trabajar esta sección]

Para tareas más complejas o necesidades específicas, es posible que necesites crear tus propias acciones desde cero. Esto requerirá algunos conocimientos de programación y comprensión de la API de SpokesAI.

Puedes encontrar información detallada sobre cómo hacer esto en la [Documentación técnica](#).

Ten en cuenta que, si bien las acciones pueden mejorar en gran medida las capacidades de tus spokes, deben diseñarse y usarse de manera responsable para garantizar experiencias de usuario positivas y respetar la privacidad y el consentimiento del usuario.

### Integraciones

**Las integraciones** son esencialmente puentes que conectan otras plataformas, herramientas o servicios con Spokes. Permiten que sus Spokes funcionen en otros entornos, ampliando de manera efectiva su alcance y utilidad. ¡Mediante integraciones, tus Spokes pueden funcionar sin problemas dentro de tus plataformas de mensajería favoritas, herramientas de atención al cliente, canales de redes sociales y más!

#### Integraciones incluidas

SpokesAI viene con varias integraciones prediseñadas que puedes habilitar para tus Spokes:

- **iFrame**: permite que Spoke funcione dentro de una página web o aplicación. Esta integración es ideal para incorporar Spoke a su sitio web para atención al cliente, chat en vivo...
- **Telegram**: conecta tu Spoke a Telegram. Tu Spoke puede ser fácilmente un bot de Telegram, capaz de interactuar con quién lo compartas.
- **Slack**: vincula tu Spoke a tu espacio de trabajo de Slack. Puedes usar tu Spoke como un bot inteligente de Slack en cada canal, brindando asistencia, actualizaciones y respuestas a consultas sobre documentación a tu equipo.

[TO DO: agregar instrucciones detalladas o enlaces a guías para configurar cada integración]

#### Construye tu propia integración

¿Qué sucede si deseas utilizar Spokes con una plataforma que aún no es compatible con las integraciones incluidas de SpokesAI? ¡Ahí es donde entra en juego la API SpokesAI! La API permite crear integraciones personalizadas, conectando sus Spokes a prácticamente cualquier plataforma o servicio.

El proceso de creación de tu propia integración implica el uso de la API SpokesAI para enviar los mensajes correspondientes a tu Spoke y recuperar sus respuestas. Luego, éstas se pueden mostrar en la plataforma de tu elección.

Para obtener instrucciones más detalladas, consulta la documentación de la API de SpokesAI. Crear tu propia integración requiere algunos conocimientos técnicos, ¡pero abre infinitas posibilidades para usar tus Spokes!

Recuerde, las integraciones pueden mejorar enormemente las capacidades y el alcance de su Spoke. Ya sea que esté utilizando integraciones incluidas o creando las suyas propias, asegúrese de diseñarlas y utilizarlas de manera responsable para crear experiencias de usuario positivas.

## Guía de la App

La aplicación consta de cinco secciones principales: Inicio, Spokes, Bibliothecas, Integraciones y Configuración. Cada sección está diseñada para facilitar la gestión de una entidad.

1. **Inicio**: tu punto de partida. Este panel alberga la sección 'Publicaciones' que destaca noticias sobre cambios en la aplicación, tutoriales y otro contenido relevante. Pon atención a esta página para obtener actualizaciones, noticias y consejos sobre el uso de SpokesAI. Aquí también puedes encontrar enlaces a las páginas principales de la aplicación.
    
2. **Spokes**: Aquí es donde tus ayudantes cobra vida. La página Spokes te permite administrar tus Spokes. Puedes crearlos, eliminarlos y editarlos. Aquí también encontrarás plantillas de spokes preconfigurados, listos para adaptarse a tus necesidades específicas. Utiliza estas plantillas como base para acelerar el proceso de creación de tus spokes. Además, está disponible la opción de generar un iframe para cada Spoke, lo que le brinda la posibilidad de incrustarlos en cualquier página web.
    
3. **Bibliothecas**: La página de Bibliothecas es el depósito de conocimientos para tus Spokes. Aquí puedes crear, editar y eliminar bibliotecas. ¡Piensa en ello como una biblioteca, donde tus Spokes van a estudiar!

4. **Integraciones**: Desde esta página, puedes administrar tus integraciones, dejando que tus spokes salgan a jugar en diferentes plataformas, como Slack o Telegram.

5. **Configuración**: Por último, pero no menos importante, la página de configuración contiene los detalles de tu cuenta de usuario. Aquí puedes encontrar tu clave API, la cantidad total de conversaciones abiertas que tienes y la cantidad total de Spokes que has creado. Aquí también se muestra el uso de tu suscripción y una lista de las conversaciones que aún tiene abiertas, para continuarlas o finalizarlas.
    
Navegar por estas cinco páginas te brindará control total sobre tus Spokes y el entorno en el que operan.

```
NOTA: Si quieres cambiar el idioma o cerrar sesión, usa el ícono de "usuario" en la esquina superior derecha.
```

## Informacion adicional

Ten en cuenta que esta guía es una descripción general. Para obtener información técnica detallada, los desarrolladores pueden consultar la [Documentación técnica](#). Si tienes preguntas adicionales, visita nuestra sección [Preguntas frecuentes](FAQ.md), habla con nuestros agentes de soporte en la aplicación o [comunícate con nuestro equipo de soporte](#).

## Resolución de problemas

Si tienes algún problema usando nuestra app, habla con nuestros agentes de soporte en la aplicación o [comunícate con nuestro equipo de soporte](#).
