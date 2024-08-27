Proyecto: Gardenia
1. Descripción General
Gardenia es un sistema de gestión de plantas para el hogar que permite a los usuarios añadir sus plantas, registrar eventos como riegos, abonos y trasplantes, y recibir notificaciones sobre el cuidado necesario. A futuro, se planea desarrollar dispositivos para sensorización individual de las plantas.

2. Objetivos del Proyecto
Crear un sistema completo (backend y frontend) para la gestión de plantas de forma eficiente.
Facilitar a los usuarios el seguimiento y cuidado de sus plantas mediante notificaciones y herramientas de inteligencia artificial.
Desarrollar una base de datos y herramientas de IA para predecir cuándo regar, abonar o trasplantar las plantas.
Proporcionar a los usuarios recomendaciones personalizadas basadas en los entornos de sus plantas.
3. Público Objetivo
El público objetivo incluye a todas aquellas personas aficionadas a las plantas y a la tecnología que buscan un mayor control y cuidado de sus plantas.

4. Funcionalidades Principales
Autenticación de Usuarios: Registro y login de usuarios, incluyendo autenticación con Google.
Gestión de Plantas: Añadir, modificar o borrar plantas del usuario.
Gestión de Habitaciones: Añadir, modificar o borrar habitaciones, con características como radiador, aire acondicionado y cantidad de luz.
Gestión de Casas: Los usuarios pueden crear y gestionar múltiples casas, cada una con sus habitaciones y plantas.
Buscar Plantas: Búsqueda en una base de datos o API para ver características como frecuencia de riego, nombre científico y temperatura óptima.
5. Funcionalidades Secundarias
Identificación de Plantas mediante IA: Herramientas de IA para identificar plantas a partir de imágenes.
Predicción de Necesidades de Cuidado: IA que predice cuándo regar o trasplantar basándose en datos históricos y ambientales.
Detección y Clasificación de Plagas: Herramienta de IA para identificar plagas en las plantas a partir de fotografías.
Cementerio de Plantas: Registro de plantas fallecidas para que los usuarios las puedan recordar.
Notificaciones: Sistema de notificaciones para alertar a los usuarios sobre eventos importantes como riego, abono, trasplante, etc.
Tipos de Notificaciones: Push, Email, y Dentro de la App.
Registro Fotográfico de Crecimiento: Registro visual del crecimiento de las plantas con fotografías periódicas.
Indicadores de Salud: Muestra del estado de salud de las plantas basado en los registros y datos actuales.
Sugerencia de Plantas por Entorno: Recomendaciones de plantas que se adapten bien a las características de las habitaciones.
Alertas Basadas en Clima Local: Alertas y recomendaciones ajustadas al clima local.
Análisis y Reportes: Estadísticas y reportes sobre el cuidado de las plantas.
Integración con Asistentes Virtuales: Compatibilidad con asistentes como Alexa o Google Assistant.
Sistema de Logros y Recompensas: Desafíos y logros para mantener a los usuarios motivados en el cuidado de sus plantas.
6. Tecnologías a Utilizar
Frontend
React.js
Next.js
NextAuth
Backend
Node.js
Express.js
Base de Datos
MongoDB
Gestión del Proyecto
Git para control de versiones.
GitHub para repositorios, roadmap, y gestión de issues.
7. Desglose de Versiones
Backend
Versión 1.0

Configuración inicial del servidor con Node.js y Express.js.
Implementación de la autenticación de usuarios (registro y login).
Gestión de casas: Crear, modificar, y eliminar casas, con nombre, ubicación, y array de habitaciones.
Creación de endpoints para la gestión de habitaciones dentro de las casas.
Creación de endpoints para la gestión de plantas (añadir, modificar, eliminar).
Versión 1.1

Integración con una API externa para la búsqueda de plantas y obtención de datos.
Implementación de un sistema de notificaciones para riegos y trasplantes.
Versión 1.2

Implementación del sistema de cementerio de plantas, permitiendo que los usuarios marquen una planta como fallecida y la muevan al cementerio.
Versión 1.3

Implementación del login con Google usando OAuth2, permitiendo a los usuarios registrarse e iniciar sesión con su cuenta de Google.
Versión 1.4

Sistema de Notificaciones:
Notificaciones Push: Implementación de notificaciones push, gestionadas desde el backend usando el Web Push Protocol.
Notificaciones por Email: Configuración para enviar correos electrónicos recordando a los usuarios los cuidados pendientes de sus plantas mediante nodemailer.
Notificaciones Dentro de la App: Implementación de un sistema de alertas en la aplicación para mostrar notificaciones cuando el usuario esté utilizando la app, gestionadas desde el backend.
Configuración de Notificaciones:
Creación de una sección en la app donde los usuarios puedan personalizar sus preferencias de notificación, eligiendo el tipo de notificación (push, email, en-app) y ajustando la frecuencia (diaria, semanal, etc.).
Backend para gestionar el envío de notificaciones en función de las preferencias del usuario.
Versión 2.0

Implementación de la funcionalidad de predicción de riego mediante IA.
Creación de un módulo para la predicción de trasplantes.
Desarrollo del sistema de detección y clasificación de plagas utilizando IA.
Versión 2.1

Implementación del registro fotográfico de crecimiento, permitiendo a los usuarios tomar y guardar fotos periódicamente para ver la evolución de sus plantas.
Backend para gestionar el almacenamiento de imágenes y la creación de líneas de tiempo visuales.
Versión 2.2

Indicadores de salud de plantas, basado en los datos de riego, trasplante, abono y otros factores registrados.
Backend para calcular y almacenar el estado de salud de las plantas basado en las entradas del usuario y otros datos disponibles.
Versión 2.3

Sugerencia de plantas por entorno: análisis de las características de las habitaciones y recomendación de plantas adecuadas para esas condiciones.
Backend para procesar los datos de las habitaciones y sugerir plantas adecuadas utilizando reglas predefinidas o un modelo de machine learning simple.
Versión 2.4

Implementación de alertas basadas en clima local, utilizando APIs de clima para ajustar las recomendaciones de cuidado.
Backend para integrar los datos climáticos y generar alertas o recomendaciones personalizadas.
Versión 2.5

Desarrollo de un sistema de análisis y reportes, proporcionando a los usuarios estadísticas y gráficos sobre el cuidado de sus plantas.
Backend para la generación de reportes periódicos y almacenamiento de datos históricos.
Versión 3.0

Integración con asistentes virtuales como Alexa o Google Assistant para control por voz y notificaciones.
Backend para manejar las solicitudes y respuestas de los asistentes virtuales.
Versión 3.1

Implementación de un sistema de logros y recompensas, con desafíos que motiven a los usuarios a mantener un buen cuidado de sus plantas.
Backend para el seguimiento de logros, progreso y generación de recompensas.
Frontend
Versión 1.0

Configuración inicial del proyecto con React.js y Next.js.
Creación de la interfaz para el registro y login de usuarios.
Desarrollo de las vistas para la gestión de casas, habitaciones y plantas.
Implementación del sistema de navegación.
Versión 1.1

Integración con la API externa para la búsqueda y visualización de características de plantas.
Implementación de un calendario o sistema de recordatorios visual para los eventos de cuidado de las plantas.
Versión 1.2

Creación de una interfaz para el cementerio de plantas, donde los usuarios puedan ver las plantas fallecidas y recordar sus detalles.
Versión 1.3

Implementación de la opción de login con Google en la interfaz de autenticación, facilitando el acceso mediante cuentas de Google.
Versión 1.4

Interfaz de Notificaciones:

Implementación de la UI para mostrar notificaciones push cuando la app esté en uso, integrando Web Push Protocol para recibir y gestionar las notificaciones desde el backend.
Creación de un sistema de alertas visuales dentro de la app para informar a los usuarios sobre eventos importantes.
Diseño de la interfaz de configuración para que los usuarios personalicen sus preferencias de notificación.
Gestión de Notificaciones por Email:

Implementación de una sección para que los usuarios configuren sus preferencias de notificaciones por correo electrónico. El frontend enviará las preferencias del usuario al backend, que gestionará los envíos de correos.
Versión 2.0

Implementación de la herramienta de identificación de plantas mediante imágenes.
Integración de la funcionalidad de predicción de riego en la interfaz.
Desarrollo de la interfaz para la detección y clasificación de plagas en base a fotografías.
Versión 2.1

Implementación de la interfaz de usuario para el registro fotográfico de crecimiento de las plantas.
Desarrollo de una vista de línea de tiempo para visualizar la evolución de las plantas con fotos tomadas a lo largo del tiempo.
Versión 2.2

Creación de un dashboard de salud de plantas que muestre visualmente el estado de cada planta.
Interfaz para mostrar alertas y recomendaciones basadas en el estado de salud.
Versión 2.3

Desarrollo de la funcionalidad de sugerencia de plantas por entorno, mostrando plantas recomendadas en función de las características de las habitaciones.
Implementación de una interfaz intuitiva para seleccionar las características de las habitaciones y recibir sugerencias.
Versión 2.4

Integración de alertas basadas en el clima local en el dashboard y la vista principal de la app.
Notificaciones ajustadas según el clima, como alertas de riego en días calurosos.
Versión 2.5

Implementación de la interfaz de usuario para análisis y reportes, con gráficos y estadísticas sobre el cuidado de las plantas.
Sección de reportes donde los usuarios puedan ver su historial de cuidado y recibir recomendaciones basadas en datos.
Versión 3.0

Integración de control por voz y notificaciones mediante asistentes virtuales como Alexa y Google Assistant.
Configuración de comandos y respuestas personalizadas para interactuar con el sistema.
Versión 3.1

Implementación de un sistema de logros y recompensas en la interfaz, con indicadores de progreso y notificaciones de logros alcanzados.
Interfaz de usuario para explorar logros disponibles y rastrear el progreso.
