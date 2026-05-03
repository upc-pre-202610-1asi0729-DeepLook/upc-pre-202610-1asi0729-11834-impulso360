# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

**Branding:**

El logotipo principal se trata de un conjunto de nodos interconectados que busca representar la conexión entre los distintos componentes de negocio desde la gestión de citas, la promoción de servicios y la relación con los clientes. El logotipo busca transmitir una imagen tecnológica, ordenada y dinámica. Se tienen dos versiones de logo una sin el nombre (para cuando se requiera más espacio) y otra con el nombre del producto.

|                           Logo                           |                             Logotipo                             |
| :------------------------------------------------------: | :--------------------------------------------------------------: |
| ![Logo1](../assets/imagenes/style-guidelines/logo-1.png) | ![Logotipo1](../assets/imagenes/style-guidelines/logotipo-1.png) |
| ![Logo2](../assets/imagenes/style-guidelines/logo-2.png) | ![Logotipo2](../assets/imagenes/style-guidelines/logotipo-2.png) |

**Typography:**

La tipografía elegida para nuestro producto, se trata de Poppins, la cual tiene un estilo clásico y ordenado. Es una fuente sans-serif moderna, legible y optimizada para diferentes pantallas. Se utilizará la familia de fuentes Poppins para todo el texto, para mantener una consistencia en toda la aplicación.

![Tipografia](../assets/imagenes/style-guidelines/tipografia.png)

En cuanto a la jerarquía tipográfica en entorno web:

- Títulos principales (H1): Poppins SemiBold, 32 px
- Encabezados de sección (H2): Poppins Medium, 24 px
- Subtítulos (H3): Poppins Medium, 20 px
- Texto de cuerpo: Poppins Regular, 18px
- Botones y elementos interactivos: Poppins Medium, 18 px

**Colors:**

La paleta de color de Impulso360 está basada en los tonos presentes en el logotipo y busca equilibrar cercanía, tecnología y dinamismo. Los tonos azules transmiten serenidad, calma y eficiencia,mientras que el naranja aporta energía, impulso y calidez. Al tratarse de colores complementarios, generan un alto impacto visual donde se equilibra lo racional con lo emocional.

Asimismo se ha incorporado un tono crema suave como color neutro de apoyo, junto con el gris, que será utilizado para dividir secciones y organizar visualmente los distintos elementos de la interfaz.

https://psicologiaymente.com/psicologia/que-significa-el-azul
https://www.espacioux.com/blog/uso-del-color-en-interfaces-ux-ui

![PaletaColores](../assets/imagenes/style-guidelines/color-palette.png)

**Spacing:**

Al tratarse de una aplicación web, se prioriza que los elementos estén ordenados y con una disposición equilibrada en la pantalla.

En cuanto a la versión Desktop todo los elementos deben ser más visibles y ocupan más espacio por lo que se establecen los siguientes espaciados.

- Margen lateral principal de la interfaz:40px
- Separación entre títulos principales y contenido: 24px
- Separación entre encabezados y párrafos: 16px
- Separación entre párrafos o bloques de texto: 24px
- Separación horizontal de elementos: 16px
- Separación vertical de elementos: 12px
- Padding de tarjetas y contenedores: 24px
- Padding de botones: vertical: 12px y horizontal: 24px.

En cuanto a la versión móvil el espacio es un recurso limitado, por lo que se necesita adaptar los espaciados de tal manera que el contenido resulte legible:

- Margen lateral principal de la interfaz:16px
- Separación entre títulos principales y contenido: 16px
- Separación entre encabezados y párrafos: 8px
- Separación entre párrafos o bloques de texto: 16px
- Separación horizontal de elementos: 8px
- Separación vertical de elementos: 12px
- Padding de tarjetas y contenedores: 16px
- Padding de botones: vertical: 14px y horizontal: 20px.

**Tono de Comunicación:**

El tono de comunicación para Impulso360 se alinea con la imagen que DeepLook busca transmitir. Por ello, debe ser cercano, claro y orientado a la acción. Este debe proyectar:

- Claridad: para que el usuario comprenda rápidamente que puede hacer en la plataforma
- Cercanía: para que la experiencia se perciba amigable y accesible.
- Confianza: para reforzar la idea de control y organización

Los mensajes dentro de la aplicación web deben sentirse directos y útiles, que realmente ayuden al usuario a navegar por la plataforma.

![]()

**Lenguaje Aplicado:**

El lenguaje de Impulso 360 debe ser funcional, simple y consistente, evitando en todo momento el uso de terminología compleja o demasiado técnica, ya que el público objetivo incluye pequeños negocios y usuarios con distintos niveles de digitalización. Las instrucciones, etiquetas y mensajes deben ser breves, comprensibles y orientados a la acción. En cuanto al idioma principal, se optará por español. Asimismo, el lenguaje empleado será funcional y se buscará mantener la homogeneidad en la terminología utilizada en botones, instrucciones y demás elementos de la interfaz.

https://www.netlanguages.com/blog/index.php/2017/08/28/what-is-functional-language/

---

### 4.1.2. Web Style Guidelines

En esta sección se detallan las decisiones de diseño que conforman la identidad visual de **DeepLook**. Estos estándares garantizan una interfaz coherente, profesional y adaptable (_responsive_), facilitando tanto el desarrollo de software como la experiencia del usuario final.

---

### A. Paleta de Colores (Colors)

La paleta de colores ha sido seleccionada para transmitir confianza, análisis y modernidad. Se utiliza una combinación de tonos oscuros para la estructura y colores vibrantes para las acciones clave.

- **Color Primario (Deep Blue):** `#082857` - Utilizado para la barra lateral (Sidebar), encabezados y elementos de menú. Transmite profesionalismo.

- **Color de Acento (Vibrant Orange):** `#F37048` - Utilizado para botones de llamado a la acción (CTAs), iconos resaltados y el número "360" del logo. Facilita la identificación de elementos interactivos.

- **Color de Fondo (Soft Gray/White):** `#F8F9FA` - Utilizado para las áreas de trabajo y paneles, reduciendo la fatiga visual.

- **Colores de Estado:**
  - Éxito: `#28A745` (Verde)
  - Error: `#DC3545` (Rojo)

![Paleta de colores del Design System en Figma](../assets/imagenes/style-guidelines/color-palette.png)

---

### B. Tipografía (Typography)

Se utiliza una tipografía de estilo _sans-serif_ para asegurar la legibilidad en pantallas digitales de alta y baja resolución.

- **Títulos (H1, H2, H3):** Se utiliza la fuente **Inter** (o la que hayas elegido en Figma) en variantes _Bold_ para jerarquizar la información. Tamaño sugerido para escritorio: 32px - 24px.

- **Cuerpo de Texto (Body):** Fuente **Inter** en variante _Regular_, con un tamaño de 16px para garantizar lectura fluida de reportes y descripciones.

- **Botones y Enlaces:** Fuente en variante _Semi-Bold_ para destacar sobre el resto del texto.

![Escala tipográfica en Figma](../assets/imagenes/style-guidelines/tipografia.png)

---

### C. Botones y Elementos de Interfaz (UI Elements)

Los botones mantienen un estilo consistente con bordes redondeados (_border-radius_: 8px) para una apariencia moderna.

- **Botón Primario:** Fondo naranja con texto blanco. Se utiliza para la acción principal de la pantalla (ej. "Ingresar" o "Crear Reporte").

- **Botón Secundario:** Bordes color azul oscuro con fondo transparente. Utilizado para acciones secundarias (ej. "Cancelar" o "Filtrar").

- **Estados (Hover & Active):** Los elementos interactivos cambian ligeramente su opacidad o tono al pasar el cursor para indicar clicabilidad.

---

### D. Iconografía (Icons)

Se utiliza un set de iconos lineales y minimalistas. La simplicidad de los trazos evita que la interfaz se vea saturada, especialmente en el menú lateral donde acompañan a las etiquetas de navegación.

- **Estilo:** Outlined (Contorneado).
- **Grosor:** 2px para mantener la consistencia visual.

![Muestra de los iconos utilizados en el Sidebar de DeepLook (Dashboard, Analítica, Reportes)](../assets/imagenes/web-applications-design/web-mockup-1.png)

---

### E. Rejilla y Adaptabilidad (Grid & Spacing)

Para asegurar que la interfaz sea _responsive_, se ha implementado un sistema de rejilla flexible.

- **Escritorio (Desktop):** Sistema de 12 columnas con márgenes laterales de 80px.

- **Móvil (Mobile):** Sistema de 4 columnas con márgenes de 16px, donde los elementos del dashboard se apilan verticalmente para facilitar la navegación táctil.

---

## 4.2. Information Architecture

Esta sección describe la estructura de la información, estilos y sistemas que se utilizarán en la plataforma web de Impulso360. Se consideran los sistemas de organización, etiquetado, búsqueda, navegación y SEO, con el fin de garantizar una experiencia clara y enfocada en la visualización de datos.

---

### 4.2.1. Organization Systems

En esta sección se define cómo se organizará la información en la plataforma Impulso360 para garantizar que los usuarios de ambos segmentos (microempresas de servicios por citas y emprendedores en proceso de digitalización) puedan navegar, encontrar y utilizar las funcionalidades de manera intuitiva y eficiente.

#### Sistemas de Organización Visual del Contenido

**1. Organización Jerárquica (Visual Hierarchy)**

Se aplicará una jerarquía visual para priorizar la información más relevante y guiar al usuario hacia las acciones principales en cada pantalla.

Casos de aplicación:

**Panel General (Dashboard):** Las métricas más importantes (Citas hoy, Clientes activos, Pendientes) se muestran en cards destacadas en la parte superior, seguidas de la lista de citas del día y el calendario. La jerarquía guía al usuario desde la vista general hacia acciones específicas.

**Agenda:** La vista semanal del calendario tiene prioridad visual (ocupa el espacio central más amplio), mientras que el calendario mensual y el panel de próximas citas se posicionan en un sidebar secundario.

**Modales de formularios (Nueva cita, Nuevo cliente, Agregar servicio):** El título del modal tiene la jerarquía más alta (header oscuro con tipografía grande), seguido de secciones claramente diferenciadas con títulos intermedios, y finalmente los campos de formulario con labels y helper texts en niveles inferiores.

**Servicios:** Los servicios destacados tienen una banda superior de color que los diferencia visualmente del resto, estableciendo una jerarquía clara entre servicios promocionados y regulares.

Justificación: La jerarquía visual ayuda a usuarios con poca experiencia digital (segmento objetivo) a identificar rápidamente qué es más importante y dónde deben enfocar su atención.

**2. Organización Secuencial (Step-by-step)**

Se aplicará una organización secuencial en procesos que requieren completar pasos en un orden específico para lograr un objetivo.

Casos de aplicación:

**Tutorial Interactivo (Ayuda):** El tutorial para nuevos usuarios presenta 5 pasos secuenciales numerados:

1. Configura tu perfil del negocio
2. Agrega tus servicios
3. Registra tu primera cita
4. Registra un cliente
5. Comparte tu perfil digital

Cada paso muestra su estado (Completado, En progreso, Pendiente) y guía al usuario linealmente hacia la adopción completa de la plataforma.

**Formularios de registro (Nuevo cliente, Nueva cita, Agregar servicio):** Aunque no son wizards de múltiples pasos, las secciones dentro de cada formulario siguen un orden lógico progresivo:
Información básica → Detalles específicos → Configuración adicional

**Guías rápidas (Ayuda):** Los tutoriales paso a paso presentan instrucciones secuenciales ilustradas que el usuario debe seguir en orden para completar tareas como "Cómo registrar una nueva cita".

Justificación: Los usuarios en proceso de digitalización necesitan orientación clara y progresiva para aprender a usar la plataforma sin sentirse abrumados.

**3. Organización Matricial**

Se aplicará una organización matricial cuando el usuario necesita comparar múltiples elementos simultáneamente basándose en diferentes atributos.

Casos de aplicación:

**Tabla de Clientes:** Presenta información en una matriz de filas (clientes) y columnas (atributos: nombre, teléfono, última cita, total citas, estado). El usuario puede escanear horizontalmente para ver todos los datos de un cliente, o verticalmente para comparar el mismo atributo entre diferentes clientes.

**Agenda Semanal:** El calendario semanal es una matriz donde:

- Filas: Franjas horarias (08:00, 09:00, 10:00...)
- Columnas: Días de la semana (Lun, Mar, Mié, Jue, Vie)
- Celdas: Citas programadas

Esto permite al usuario visualizar rápidamente la distribución de citas por día y hora.

**Horarios de Atención (Perfil del negocio):** Tabla matricial donde:

- Filas: Días de la semana
- Columnas: Horario de apertura, cierre, estado (activo/inactivo)

Facilita la configuración y comparación de horarios entre diferentes días.

Justificación: La organización matricial es eficiente para presentar datos estructurados que requieren comparación multi-dimensional, facilitando la toma de decisiones informadas.

#### Esquemas de Categorización del Contenido

**1. Categorización Cronológica**

Casos de aplicación:

**Agenda:** Las citas se organizan cronológicamente por fecha y hora. La vista predeterminada muestra la semana actual, permitiendo navegación hacia semanas pasadas/futuras.

**Historial de Citas (Panel de cliente):** Las citas de un cliente se listan en orden cronológico inverso (más reciente primero), mostrando fecha, hora y servicio.

**Notificaciones:** Las notificaciones se ordenan cronológicamente de más reciente a más antigua, con timestamps relativos ("Hace 5 min", "Hace 1 hora", "Ayer, 17:30").

**Próximas Citas (Panel General):** Las citas futuras se listan cronológicamente ascendente (próxima primero).

Justificación: Para información temporal como citas y eventos, la organización cronológica es la más intuitiva y permite a los usuarios ubicarse temporalmente de forma natural.

**2. Categorización por Tópicos/Temática**

Casos de aplicación:

**Navegación Principal (Sidebar):** Los elementos del menú están agrupados por temas funcionales:

- PRINCIPAL: Panel general, Agenda, Clientes, Servicios (funciones operativas core)
- HERRAMIENTAS: Perfil del negocio, Ayuda (funciones de configuración y soporte)

**Servicios:** Los servicios pueden filtrarse/categorizarse por tipo:

- Veterinaria
- Estética
- Prevención
- Cirugía

**Ayuda:** El contenido de ayuda se organiza por tópicos:

- Tutorial interactivo
- Guías rápidas (Cómo registrar cita, Cómo agregar cliente, etc.)
- Preguntas frecuentes (agrupadas por tema)

**Formularios:** Las secciones dentro de modales están agrupadas temáticamente:

- Información personal
- Información de contacto
- Detalles del servicio/cita

Justificación: La categorización por tópicos agrupa contenido relacionado, reduciendo la carga cognitiva y facilitando que usuarios encuentren funcionalidades según su necesidad temática.

**3. Categorización según Estado/Status**

Casos de aplicación:

**Agenda (Tabs de filtrado):** Las citas pueden filtrarse por estado:

- Todas
- Confirmadas
- Pendientes
- Canceladas

**Clientes:** Se categorizan por estado:

- Activos
- Inactivos

**Servicios:** Se categorizan por estado:

- Activo (disponible para nuevas citas)
- Inactivo (no disponible)
- Destacado (promocionado en perfil digital)

**Notificaciones:** Filtros por estado de lectura:

- Todas
- No leídas
- Alertas

**Tutorial Interactivo (Ayuda):** Los pasos se categorizan por estado de progreso:

- Completado
- En progreso
- Pendiente

Justificación: La categorización por estado permite a los usuarios gestionar su flujo de trabajo enfocándose en acciones pendientes o elementos que requieren atención inmediata.

**4. Categorización Alfabética**

Casos de aplicación:

**Búsqueda de Clientes (Modal Nueva cita):** Cuando el usuario escribe en el campo de búsqueda, los resultados del dropdown se ordenan alfabéticamente por nombre de cliente para facilitar la localización rápida.

**Lista de Clientes (función de búsqueda):** Si el usuario utiliza la función de búsqueda, los resultados se presentan alfabéticamente por defecto.

**Selección de Servicios (dropdowns):** Los servicios en campos de selección (como en el formulario Nueva cita) se listan alfabéticamente para facilitar la búsqueda visual.

Justificación: El orden alfabético es universalmente conocido y facilita la búsqueda cuando el usuario conoce el nombre del elemento que busca.

**5. Categorización por Audiencia (Segmentos de Usuarios)**

Si bien Impulso360 tiene dos segmentos objetivo claramente definidos, no se aplica categorización por audiencia visible en la interfaz porque ambos segmentos comparten las mismas funcionalidades core de la plataforma.

Sin embargo, existen diferenciaciones sutiles en la experiencia:

**Tutorial interactivo y Guías rápidas (Ayuda):** Están diseñadas pensando en usuarios con baja experiencia digital (ambos segmentos), utilizando lenguaje simple y pasos ilustrados.

**Tono de comunicación:** El lenguaje en toda la plataforma es funcional, claro y directo, evitando tecnicismos, alineado con el perfil de usuarios que están digitalizándose.

Justificación: Aunque existen dos segmentos, sus necesidades funcionales son homogéneas (gestión de citas), por lo que la interfaz no requiere vistas diferenciadas por tipo de usuario.

#### Tabla Resumen

| Pantalla              | Organización Visual     | Esquema de Categorización                                                          |
| --------------------- | ----------------------- | ---------------------------------------------------------------------------------- |
| Panel General         | Jerárquica              | Cronológica (citas próximas) + Estado (pendientes/confirmadas)                     |
| Agenda                | Jerárquica + Matricial  | Cronológica + Estado (filtros por confirmada/pendiente/cancelada)                  |
| Clientes              | Jerárquica + Matricial  | Alfabética (búsqueda) + Estado (activo/inactivo) + Cronológica (última cita)       |
| Servicios             | Jerárquica              | Tópicos (categoría: Veterinaria, Estética...) + Estado (destacado/activo/inactivo) |
| Perfil del Negocio    | Jerárquica + Matricial  | Tópicos (agrupación de campos)                                                     |
| Ayuda                 | Jerárquica + Secuencial | Tópicos (tutorial, guías, FAQ) + Secuencial (pasos del tutorial)                   |
| Notificaciones        | Jerárquica              | Cronológica + Estado (leído/no leído)                                              |
| Modales (Formularios) | Jerárquica + Secuencial | Tópicos (secciones del formulario)                                                 |

---

### 4.2.2. Labeling Systems

En esta sección se detalla el sistema de etiquetado de DeepLook, diseñado para ofrecer una experiencia de usuario intuitiva mediante términos breves y reconocibles. Estas etiquetas permiten que tanto los visitantes como los usuarios finales comprendan las funciones del software sin ambigüedades.

#### Etiquetas de Navegación (Sidebar & Menu Labels)

Representan los destinos principales dentro de la plataforma. Se utilizan sustantivos cortos que describen el área de trabajo.

- **Dashboard:** Acceso al panel de control con métricas generales.
- **Analítica:** Sección dedicada a la visualización profunda de datos recogidos.
- **Reportes:** Listado de documentos generados y registros históricos.
- **Configuración:** Panel para personalizar la cuenta y parámetros del sistema.
- **Cerrar Sesión:** Acción para finalizar la sesión de usuario de forma segura.

#### Etiquetas de Acción y Control (Command Labels)

Utilizadas en botones y elementos interactivos para disparar funciones específicas observadas en los mockups.

- **Ingresar:** Botón de acceso en la pantalla de Login.
- **Crear Nuevo:** Iniciar la configuración de un nuevo reporte o proyecto.
- **Filtrar:** Opción para segmentar datos (por fecha, tipo o estado).
- **Descargar:** Acción para obtener reportes en formato local (PDF/Excel).
- **Guardar:** Confirmar cambios en los formularios de configuración.

#### Etiquetas de Estado y Datos (Informational Labels)

Identifican el estado de los procesos o categorías de información dentro de las tablas y dashboards.

- **En Proceso:** Indica que el análisis de datos está activo.
- **Completado:** Reporte finalizado y listo para revisión.
- **Pendiente:** Registro que requiere acción por parte del usuario.
- **Métricas:** Título de sección para indicadores clave de rendimiento (KPIs).
- **Usuario:** Nombre o rol del responsable asignado a una tarea.

#### Etiquetas de Formulario (Field Labels)

Nombres de campos específicos utilizados para la entrada de datos, garantizando que el usuario sepa qué información ingresar.

- **Correo electrónico:** Campo para la identificación del usuario.
- **Contraseña:** Campo de seguridad para el acceso.
- **Nombre del Proyecto:** Identificador de cada flujo de trabajo.
- **Rango de Fechas:** Selector temporal para la visualización de datos.

---

### 4.2.3. SEO Tags and Meta Tags

En esta sección se definen las etiquetas de optimización para motores de búsqueda (SEO) y metadatos que se implementarán para mejorar la visibilidad del proyecto en la web y garantizar una correcta interpretación por parte de los navegadores y plataformas sociales.

#### Landing Page (Sitio Web Estático)

El objetivo de estas etiquetas es el posicionamiento orgánico para atraer a dueños de negocios o analistas interesados en la solución de DeepLook.

- **Title:** DeepLook | Optimiza tu Negocio con Análisis de Datos Inteligente
- **Description:** Transforma los datos de tu empresa en decisiones estratégicas. Con DeepLook, obtén analítica avanzada y dashboards en tiempo real para potenciar tu crecimiento.
- **Keywords:** análisis de datos, business intelligence, dashboard para empresas, optimización de negocios, DeepLook, software de analítica, gestión de reportes.
- **Author:** DeepLook Team
- **Robots:** index, follow
- **Viewport:** width=device-width, initial-scale=1.0 (Para asegurar la adaptabilidad responsive en móviles).

#### Web Application (Plataforma de Usuario)

Aquí las etiquetas están orientadas a la funcionalidad y seguridad, evitando que motores de búsqueda indexen información privada de los usuarios, pero manteniendo la identidad de la marca.

- **Title:** Dashboard | DeepLook App
- **Description:** Panel de control principal de DeepLook. Gestiona tus proyectos, visualiza métricas y genera reportes detallados.
- **Keywords:** dashboard DeepLook, gestión de proyectos, analítica de datos privada, reportes inteligentes.
- **Author:** DeepLook Team
- **Robots:** noindex, nofollow (Por seguridad, se recomienda que las páginas internas de la aplicación no sean rastreadas por buscadores).

#### Etiquetas para Redes Sociales (Open Graph & Twitter Cards)

Para asegurar que, al compartir el enlace de DeepLook, se visualice de manera profesional en plataformas como LinkedIn o WhatsApp.

- **og:title:** DeepLook - Inteligencia de Datos al alcance de tu mano.
- **og:description:** La herramienta definitiva para la visualización y análisis de métricas empresariales.
- **og:image:** URL de una imagen destacada del logo o dashboard

---

### 4.2.4. Searching Systems

El sistema de búsqueda de DeepLook ha sido diseñado como una herramienta de soporte crítico para evitar la desorientación del usuario ante grandes conjuntos de datos. Se centra en la inmediatez y en la precisión, permitiendo que el analista localice registros específicos en segundos.

#### Mecanismos de Búsqueda

La plataforma ofrece dos niveles de búsqueda para asistir al usuario:

- **Búsqueda Global (Exploratoria):** Ubicada en la parte superior de la aplicación, permite buscar por términos generales como nombres de proyectos, identificadores de usuarios o etiquetas de reportes. Esta búsqueda utiliza un sistema de auto-completado que sugiere resultados mientras el usuario escribe.

![Busqueda Global](../assets/imagenes/style-guidelines/busqueda-global.png)

- **Búsqueda Filtrada (Específica):** Implementada directamente sobre las tablas de datos y paneles de analítica, diseñada para usuarios que buscan un dato puntual bajo criterios específicos.

![Busqueda Filtrada](../assets/imagenes/style-guidelines/busqueda-filtrada.png)

#### Opciones de Filtrado

Para reducir el volumen de información y evitar la sobrecarga visual, se ofrecen los siguientes filtros observados en la interfaz:

- **Filtro por Rango de Fechas:** Permite segmentar la información por periodos de tiempo (Hoy, últimos 7 días, mes actual o rango personalizado). Es esencial para comparar el rendimiento del negocio en etapas distintas.

![FiltroFecha](../assets/imagenes/style-guidelines/filtro-fecha.png)

- **Filtro por Estado (Status):** Permite clasificar los resultados según su situación actual (ej. "Completado", "En Proceso", "Pendiente").

- **Filtro por Categoría/Tipo:** Segmenta los datos según la naturaleza del análisis o el tipo de métrica seleccionada.

#### Visualización de Resultados

La presentación de los datos post-búsqueda mantiene la consistencia visual para asegurar una lectura fluida:

- **Resaltado de Coincidencias:** El sistema enfatiza los términos buscados dentro de los resultados para una rápida identificación.

- **Estado "Sin Resultados":** En caso de no encontrar coincidencias, se muestra una ilustración minimalista con un mensaje claro y sugerencias para ajustar los filtros, evitando una pantalla en blanco que confunda al usuario.

- **Actualización Dinámica:** Los resultados se actualizan en tiempo real sin necesidad de recargar la página completa, manteniendo el contexto del área de trabajo actual.

---

### 4.2.5. Navigation Systems

El sistema de navegación de DeepLook ha sido diseñado para minimizar el esfuerzo del usuario en la localización de información, utilizando patrones de diseño familiares que garantizan una curva de aprendizaje mínima tanto en el sitio informativo como en la plataforma de gestión.

#### Navigation Strategies

Se han implementado las siguientes estrategias de navegación para facilitar el flujo del usuario:

- **Navegación Jerárquica:** Organizada mediante una barra lateral persistente en la Web Application, permitiendo que el usuario se mueva entre secciones de igual importancia (Dashboard, Reportes, Configuración) con un solo clic.

- **Navegación Secuencial:** Utilizada principalmente en los flujos de registro y login, donde el usuario debe completar pasos específicos en un orden lógico.

- **Navegación de Desplazamiento (Scrolling):** Aplicada en la Landing Page para presentar la propuesta de valor de forma narrativa, desde el encabezado hasta el pie de página.

#### Landing Page Navigation

La navegación en el sitio estático es fluida y directa, diseñada para la conversión:

- **Menú Superior (Sticky Header):** Un menú que permanece visible al hacer scroll, permitiendo acceso rápido a "Beneficios", "Precios" y el botón de "Iniciar Sesión".

- **Call to Action (CTA) Contextuales:** Botones estratégicamente ubicados (ej. "Comienza Gratis") que dirigen al usuario directamente al flujo de registro.

- **Footer Navigation:** Un pie de página con enlaces secundarios, términos legales y redes sociales.

#### Web Application Navigation

Una vez dentro de la aplicación, el sistema se vuelve funcional y eficiente, como se observa en los diseños:

- **Sidebar Navigation (Menú Lateral):** Es el eje central de la aplicación. Utiliza iconos y etiquetas claras para segmentar las herramientas de análisis.

![Sidebar Navigation](../assets/imagenes/style-guidelines/sidebar-navigation.png)

- **Breadcrumbs (Migas de Pan):** Ubicadas en la parte superior de las páginas internas para que el usuario sepa siempre su ubicación actual.

- **Barra de Búsqueda y Filtros:** Permite una navegación de búsqueda directa dentro de grandes volúmenes de datos, facilitando el acceso a reportes específicos sin navegar por carpetas.

- **User Profile Menu:** Ubicado en la esquina inferior izquierda, permite el acceso rápido a la gestión de cuenta y la acción de cerrar sesión

![User Profile Menu](../assets/imagenes/style-guidelines/user-profile-menu.png)

#### Componentes de Navegación:

- **Menú de Usuario:** Acceso a perfil y ajustes.
- **Menú Lateral:** Navegación por módulos de trabajo.
- **Controles de Datos:** Paginación y filtros en tablas para navegar por los resultados de análisis.

---

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

![LP1](../assets/imagenes/style-guidelines/lp-wireframe-1.png)

![LP2](../assets/imagenes/style-guidelines/lp-wireframe-2.png)

---

### 4.3.2. Landing Page Mock-up

![LP1](../assets/imagenes/style-guidelines/lp-mockup-1.png)

![LP2](../assets/imagenes/style-guidelines/lp-mockup-2.png)

---

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

![wireframe1](../assets/imagenes/web-applications-design/web-wireframe-1.png)

![wireframe2](../assets/imagenes/web-applications-design/web-wireframe-2.png)

![wireframe3](../assets/imagenes/web-applications-design/web-wireframe-3.png)

![wireframe4](../assets/imagenes/web-applications-design/web-wireframe-4.png)

![wireframe5](../assets/imagenes/web-applications-design/web-wireframe-5.png)

![wireframe6](../assets/imagenes/web-applications-design/web-wireframe-6.png)

![wireframe7](../assets/imagenes/web-applications-design/web-wireframe-7.png)

![wireframe8](../assets/imagenes/web-applications-design/web-wireframe-8.png)

![wireframe9](../assets/imagenes/web-applications-design/web-wireframe-9.png)

![wireframe10](../assets/imagenes/web-applications-design/web-wireframe-10.png)

---

### 4.4.2. Web Applications Wireflow Diagrams

![wireflow1](../assets/imagenes/web-applications-design/wireflow-1.png)

![wireflow2](../assets/imagenes/web-applications-design/wireflow-2.png)

![wireflows1](../assets/imagenes/wireflows/wireflows-1.png)

![wireflows2](../assets/imagenes/wireflows/wireflows-2.png)

![wireflows3](../assets/imagenes/wireflows/wireflows-3.png)

![wireflows4](../assets/imagenes/wireflows/wireflows-4.png)

![wireflows5](../assets/imagenes/wireflows/wireflows-5.png)

![wireflows6](../assets/imagenes/wireflows/wireflows-6.png)

---

### 4.4.2. Web Applications Mock-ups

![mockup1](../assets/imagenes/web-applications-design/web-mockup-1.png)

![mockup2](../assets/imagenes/web-applications-design/web-mockup-2.png)

![mockup3](../assets/imagenes/web-applications-design/web-mockup-3.png)

![mockup4](../assets/imagenes/web-applications-design/web-mockup-4.png)

![mockup5](../assets/imagenes/web-applications-design/web-mockup-5.png)

![mockup6](../assets/imagenes/web-applications-design/web-mockup-6.png)

![mockup7](../assets/imagenes/web-applications-design/web-mockup-7.png)

![mockup8](../assets/imagenes/web-applications-design/web-mockup-8.png)

![mockup9](../assets/imagenes/web-applications-design/web-mockup-9.png)

![mockup10](../assets/imagenes/web-applications-design/web-mockup-10.png)

---

### 4.4.3. Web Applications User Flow Diagrams

![]()

---

## 4.5. Web Applications Prototyping

[Clic para ver Web Applications Prototyping](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231e504_upc_edu_pe/IQDkANW1YLFYQ6FNR_bfRoZyAXyOxM27YPBsThiLQ3RiUEM?e=OVhfHV&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

---

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming

Link de la herramienta Miro:
https://miro.com/app/board/uXjVHcT2IXY=/?share_link_id=761504321242

![boundedcontext1](../assets/imagenes/needfinding/bounded-context-1.png)

![boundedcontext2](../assets/imagenes/needfinding/bounded-context-2.png)

### 4.6.2. Software Architecture Context Diagram

![context-diagram](../assets/imagenes/domain-driver-software-architecture/context-diagram.png)

---

### 4.6.3. Software Architecture Container Diagrams

![container-diagram](../assets/imagenes/domain-driver-software-architecture/container-diagram.png)

---

### 4.6.4. Software Architecture Components Diagrams

![components-diagram](../assets/imagenes/domain-driver-software-architecture/component-diagram.png)

![components-diagram](../assets/imagenes/domain-driver-software-architecture/component-diagram-1.png)

![components-diagram](../assets/imagenes/domain-driver-software-architecture/component-diagram-2.png)

---

## 4.7. Software Object-Oriented Design

El diseño orientado a objetos del sistema se ha estructurado siguiendo los patrones de Domain-Driven Design (DDD), donde cada Bounded Context actúa como una unidad de cohesión lógica. El modelo integrado asegura que las entidades core (como Appointment y Client) mantengan una comunicación clara a través de sus límites, mientras que los servicios de soporte (IAM, Notifications) proporcionan las capacidades transversales necesarias. Este diseño garantiza la escalabilidad del sistema y facilita la implementación de microservicios o módulos independientes en el futuro.

### 4.7.1. Class Diagrams

![class-diagram](../assets/imagenes/diagrams/class-diagram.png)

#### Class dictionary:

**1. IAM (Gestión de Identidad y Acceso)**

**Clase: UserAccount**

Descripción: Es la entidad principal de seguridad. Representa las credenciales y el estado de acceso de cualquier persona que utilice la plataforma, ya sea un emprendedor (Owner), su personal (Staff) o un cliente final (Client).

Atributos:

- id (Long): Identificador único generado por el sistema.
- username (String): Nombre de usuario único (usualmente el correo electrónico).
- passwordHash (String): Representación cifrada de la contraseña para seguridad.
- isActive (boolean): Indica si la cuenta tiene permitido el acceso al sistema.
- hasCompletedTutorial (boolean): Marca si el usuario ya visualizó la guía de inicio rápido.
- roles (List<Role>): Colección de permisos o perfiles asignados al usuario.

Métodos:

- authenticate(String rawPass): Compara la contraseña ingresada con el hash almacenado para permitir el acceso.
- changePassword(String newPass): Genera un nuevo hash y actualiza la credencial de acceso.
- markTutorialAsCompleted(): Cambia el estado del tutorial para no mostrarlo en futuros inicios de sesión.
- deactivate(): Inhabilita la cuenta sin eliminar los datos históricos asociados.

**Clase: SessionToken**

Descripción: Objeto encargado de gestionar la persistencia de una sesión activa sin requerir la contraseña en cada petición.

Atributos:

- tokenHash (String): Cadena única que identifica la sesión actual.
- expiresAt (DateTime): Fecha y hora en la que el token dejará de ser válido.
- ipAddress (String): Dirección de red desde donde se originó la sesión por seguridad.

Métodos:

- isValid(): Comprueba si el token no ha expirado y pertenece a una sesión activa.
- revoke(): Invalida el token inmediatamente, forzando un nuevo inicio de sesión.

**Clase: SupportTicket**

Descripción: Representa una solicitud de asistencia técnica o duda comercial enviada por el usuario al equipo de Impulso 360.

Atributos:

- id (Long): Código de seguimiento del ticket.
- subject (String): Título o tema breve del problema.
- message (String): Descripción detallada de la consulta.
- status (TicketStatus): Estado del ticket (Abierto, En Progreso, Resuelto).

Métodos:

- reply(String response): Registra una respuesta o actualización en el hilo del ticket.
- close(): Marca la solicitud como finalizada una vez resuelto el problema.

**2. Perfil del Negocio (Business Profile)**

**Clase: BusinessProfile**

Descripción: Almacena la información comercial y estética del negocio. Es la cara pública del emprendimiento en la plataforma.

Atributos:

- legalName (String): Nombre oficial registrado legalmente.
- publicDisplayName (String): Nombre comercial que verán los clientes.
- description (String): Texto explicativo sobre los servicios y valores del negocio.
- logoUrl / coverImageUrl (String): Enlaces a las imágenes de identidad visual.
- themeColor (String): Código de color para personalizar la interfaz del cliente.
- isPublished (boolean): Indica si el perfil es visible para el público general.

Métodos:

- updateProfile(Object data): Actualiza múltiples campos de información del negocio a la vez.
- publish() / unpublish(): Alterna la visibilidad del perfil en la aplicación cliente.

**Clase: BusinessSubscription**

Descripción: Gestiona la relación comercial entre el negocio e Impulso 360, controlando el acceso a funciones según el plan contratado.

Atributos:

- startDate / endDate (DateTime): Periodo de vigencia de la suscripción actual.
- status (SubscriptionStatus): Estado del pago (Prueba, Activo, Expirado).

Métodos:

- activateTrial(): Inicia el periodo de prueba gratuita definido en el plan.
- upgradePlan(SubscriptionPlan newPlan): Cambia el nivel de suscripción y actualiza las funciones disponibles.

**3. Gestión de Clientes (Client Management)**

**Clase: Client**

Descripción: Entidad que representa al consumidor final. Puede ser un perfil creado por el dueño o una cuenta activa de un usuario cliente.

Atributos:

- firstName / lastName (String): Nombre y apellidos del cliente.
- email / phone (String): Datos de contacto para notificaciones y seguimiento.

Métodos:

- updateContactInfo(String email, String phone): Actualiza los medios de comunicación del cliente.
- getFullName(): Retorna el nombre completo formateado para reportes y agendas.

**Clase: ClientHistory**

Descripción: Acumula datos estadísticos del cliente para ayudar en la toma de decisiones comerciales.

Atributos:

- totalAppointments (int): Contador de citas asistidas exitosamente.
- totalNoShows (int): Contador de citas a las que el cliente no asistió.
- lifetimeValue (double): Ingreso total acumulado generado por este cliente.

Métodos:

- incrementAppointments(): Suma una unidad al historial de asistencia.
- recordNoShow(): Registra una inasistencia y afecta negativamente el perfil del cliente.
- # calculateLTV(): Método protegido que recalcula el valor histórico basado en los pagos realizados.

**4. Gestión de Citas (Appointment Management)**

**Clase: Appointment**

Descripción: Es el objeto core que representa la reserva de un espacio de tiempo para la prestación de un servicio.

Atributos:

- scheduledAt (DateTime): Fecha de la cita.
- startTime / endTime (Time): Rango horario reservado.
- status (AppointmentStatus): Estado actual (Programada, Completada, Cancelada, etc.).

Métodos:

- schedule(): Valida y confirma la creación de la reserva.
- reschedule(DateTime newDate, Time newTime): Cambia la fecha u hora, verificando nuevamente la disponibilidad.
- cancel(): Libera el espacio en la agenda y cambia el estado a cancelado.

**Clase: Service**

Descripción: Detalle de cada prestación ofrecida por el negocio (ej. "Corte de cabello", "Asesoría").

Atributos:

- name (String): Nombre del servicio.
- durationMinutes (int): Tiempo estimado que consume el servicio.
- price (double): Costo base del servicio.
- isFeatured (boolean): Indica si el servicio aparece destacado en el perfil.

Métodos:

- updatePrice(double newPrice): Modifica el valor comercial del servicio.
- setFeatured(boolean featured): Cambia el estado de promoción del servicio.

**5. Notificaciones (Notifications)**

**Clase: Notification**

Descripción: Encargada de la comunicación saliente para reducir el ausentismo de los clientes.

Atributos:

- recipientAddress (String): Destino (email o teléfono).
- content (String): Texto del mensaje enviado.
- type (NotificationType): Categoría (Recordatorio, Confirmación, Promoción).

Métodos:

- dispatch(): Envía el mensaje a través del proveedor externo de mensajería.
- retry(): Intenta reenviar la notificación en caso de error técnico.

**6. Panel y Seguimiento (Dashboard & Analytics)**

**Clase: DashboardReport**

Descripción: Compila datos transaccionales para presentar una visión global de la salud del negocio.

Atributos:

- periodStart / periodEnd (Date): Rango de fechas que abarca el análisis.
- generationDate (DateTime): Momento exacto en que se calculó el reporte.

Métodos:

- generate(): Procesa las citas y pagos para extraer las métricas del periodo.
- exportToPDF(): Genera un documento descargable con los resultados del reporte.

**Clase: KPI**

Descripción: Representa un indicador específico de rendimiento dentro de un reporte.

Atributos:

- metricName (String): Nombre del indicador (ej. "Tasa de Cancelación").
- numericValue (double): Valor calculado para la métrica.

Métodos:

- calculateVariance(): Compara el valor actual con el del periodo anterior para mostrar la tendencia de crecimiento o decrecimiento.

---

## 4.8. Database Design

En esta sección, el equipo presenta y explica los diagramas de base de datos diseñados para dar soporte a cada uno de los Bounded Contexts del sistema Impulso 360. El diseño se fundamenta en un modelo relacional que garantiza la persistencia robusta de la información, permitiendo que las reglas de negocio desde la gestión de suscripciones hasta el seguimiento analítico de citas se ejecuten de manera íntegra y eficiente.

Las principales características consideradas en el diseño son:

- **Integridad Referencial Estricta:** Implementación de llaves primarias (PK) y foráneas (FK) para asegurar que no existan datos huérfanos, especialmente en la relación entre citas, clientes y negocios.

- **Normalización y Rendimiento:** Las tablas han sido normalizadas hasta la tercera forma normal (3FN) para minimizar la redundancia, utilizando tipos de datos optimizados para MySQL (como BIGINT UNSIGNED para índices y DECIMAL para valores financieros).

- **Soporte B2B2C:** La estructura permite la coexistencia de múltiples negocios independientes dentro de la misma base de datos, manteniendo la privacidad de la información mediante el uso de identificadores de negocio (business_id) en las entidades transaccionales.

- **Políticas de Borrado:** Uso de ON DELETE CASCADE para sub-entidades dependientes (como horarios de un negocio) y ON DELETE SET NULL para mantener históricos de citas incluso si un usuario elimina su cuenta personal.

### 4.8.1. Database Diagrams

![database-diagram](../assets/imagenes/diagrams/database-diagram.png)
