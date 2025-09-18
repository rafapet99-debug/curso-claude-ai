# Introducción a Claude AI

## Overview de Claude AI
Sitio de Claude AI: https://claude.ai/

## Creación de una cuenta en Claude AI

## Comparación con otras plataformas IA

### Prompt 1

Genera un poema lo más cercano a 500 caracteres entre 2 personas enamoradas, una llamada ChatGPT y otra Claude.

### Prompt 2

Obtén el transcript de este video y dime qué aplicación se creó en el video usando Vibe Coding: https://www.youtube.com/watch?v=qYTL61-AzGU

### Prompt 3

Quiero que recrees un juego inspirado en Hole.io, desarrollado exclusivamente con tecnologías web estándar: HTML, CSS y JavaScript (opcionalmente usando Canvas API o Three.js para los gráficos). El juego debe poder ejecutarse directamente en el navegador sin necesidad de plugins ni motores externos.
El juego debe cumplir con lo siguiente:
1.	Tecnología y rendimiento
- Todo debe funcionar con JS nativo y librerías web (Canvas API, WebGL o Three.js).
- Compatible con navegadores modernos y adaptable a escritorio y móviles.
- Movimiento fluido y físicas simples pero realistas para el agujero y los objetos.
2.	Mecánica principal
- El jugador controla un agujero negro que se mueve en un mapa.
- El agujero absorbe objetos pequeños (personas, conos, árboles, autos) y crece de tamaño progresivamente.
- A medida que crece, puede absorber objetos cada vez más grandes.
3.	Diseño visual y experiencia
- Estilo gráfico atractivo pero ligero (formas 2D/3D simples, colores vivos y modernos).
- Interfaz limpia e intuitiva, con controles fáciles (teclas o pantalla táctil).
- Animaciones suaves para la absorción y crecimiento del agujero.
4.	Progresión y recompensas
- Sistema de puntuación basado en la cantidad y tamaño de objetos absorbidos.
- Recompensas como skins para el agujero (colores o efectos visuales).
- Ítems especiales en el mapa, por ejemplo:
- Velocidad extra (boost temporal).
- Atracción magnética (absorbe objetos cercanos).
- Multiplicador de puntos (aumenta el puntaje por un tiempo limitado).
5.	Rejugabilidad y motivación
- Tablas de clasificación locales (mejores puntajes por sesión).
- Diferentes mapas o escenarios simples (ciudad, parque, playa).
- Modos de juego: tiempo limitado y modo libre.


### Prompt 4

Crea una imagen de un nuevo dinosaurio, llamado HarrySaurus, que se parezca a un conejo carnívoro


## Explorando el entorno

## Interactuando con la ventana de chat

### Prompts

### Prompt 1
Crea una canción infantil compuesta por 3 párrafos sobre los cerditos en una granja

### Prompt 2
En base al documento adjunto, qué es el burnout?

### Prompt 3
Analiza la aplicación que se está utilizando en la captura de pantalla y dime cómo crear una nueva solicitud de chat

### Prompt 4
¿De qué trata el proyecto en base al Readme?

### Definición de Estilo

Tono amigable, diciendo por favor y gracias siempre

## Actividad - Creando un sitio web usando Claude AI

### Prompt 1

Crea un sitio web dedicado a la renta de aviones a millonarios

### Generador de prompts para crear sitios web

https://hprez21.github.io/generador-sitio-ai/

# Prompt Engineering
## Fundamentos de la Ingeniería de Prompts

### Prompt 1
Escribe un correo electrónico de marketing para nuestras nuevas funciones de AcmeCloud

### Prompt 2
Prompt mejorado: https://gist.github.com/hprez21/2a1b04be857ff2c33257cade7dcd0edf

## Técnicas de optimización de prompts

### Prompt 1

Crea un panel de análisis visual con gráficos claros, atractivos y fáciles de interpretar, destacando las métricas clave de manera intuitiva
  
### Prompt 2

Crea un panel de análisis completo y elegante. Incluye visualizaciones interactivas (gráficos de barras, líneas, áreas, mapas de calor, etc.), filtros dinámicos, segmentación por categorías y posibilidad de explorar tendencias en distintos niveles de detalle. Organiza la información de forma clara y estética, con un diseño moderno, limpio y responsivo. Usa colores armónicos, tipografías legibles y distribuye los elementos en secciones bien definidas para facilitar la interpretación. Asegúrate de incluir tantas interacciones y características relevantes como sea posible para que el dashboard sea intuitivo, atractivo y funcional.

### Prompt 3  
Crea una historia con diálogos donde participen 2 personas que están dudosos sobre si adquirir una casa o no. NUNCA uses puntos suspensivos
  
### Prompt 4
Crea una historia con diálogos donde participen 2 personas que están dudosos sobre si adquirir una casa o no. Tu respuesta será leída en voz alta por un motor de texto a voz, así que nunca uses puntos suspensivos ya que el motor de texto a voz no sabrá cómo pronunciarlos.

### Prompt 5  
Siempre que expliques un concepto difícil, incluye una metáfora sencilla.
Ejemplo, en lugar de:
“Los átomos están formados por protones, neutrones y electrones.”
Usa una metáfora como la siguiente:
“Imagina un átomo como un sistema solar en miniatura: el núcleo es el sol y los electrones giran alrededor como planetas.”
Explícame ahora qué es la computación cuántica con una metáfora.

### Prompt 6
- Escribe un artículo sobre qué son los componentes en React.
- Escribe un artículo sobre qué son los componentes en React. No uses markdown.
- Escribe un artículo sobre qué son los componentes en React. Tu respuesta debe estar compuesta de párrafos de prosa que fluyan suavemente
  
### Prompt 7
Crea una aplicación tipo contador de palabras. No te contengas. Da lo mejor de ti.

## Creando prompts reutilizables

### URLs

https://chromewebstore.google.com/detail/promptdrive/dccfgkejoobijclmdfefmigflabbjcbg

### Prompt 1

Redacta un correo electrónico con el asunto: "{{asunto}}". 
El correo está dirigido a {{destinatario}} y debe tener un tono {{tono}}. 
El propósito del correo es {{proposito}}. 
La extensión debe ser {{longitud}} y el estilo de escritura debe ser {{estilo}}. 
Incluye un saludo inicial apropiado y una despedida acorde al tono.

### Prompt 2

Una ilustración hiperrealista de {{sujeto}}, en un {{escenario}}, con un estilo {{estilo}}, iluminación {{iluminacion}}. La imagen debe transmitir {{emocion}} y estar en formato {{formato}}.

## Prompts que permiten a Claude pensar

### Prompt 1

Redacta correos electrónicos personalizados a donantes solicitando contribuciones para el programa Care for Kids de este año.

Información del programa:
<program>Programa destinado a la obtención de recursos para escuelas en zonas rurales
</program>

Información del donante:
<donor>Bruce Wayne
</donor>

Piensa paso a paso antes de escribir el correo electrónico.


### Prompt 2

- Redacta correos electrónicos personalizados a donantes solicitando contribuciones para el programa Care for Kids de este año.

Información del programa:
<program>Programa destinado a la obtención de recursos para escuelas en zonas rurales
</program>

Información del donante:
<donor>Bruce Wayne
</donor>

Piensa antes de escribir el correo electrónico. Primero, piensa qué mensajes podrían atraer a este donante dado su historial de donaciones y qué campañas han apoyado en el pasado. Luego, piensa qué aspectos del programa Care for Kids les atraerían, dado su historial. Finalmente, escribe el correo electrónico personalizado para el donante usando tu análisis.

### Prompt 3

Redacta correos electrónicos personalizados a donantes solicitando contribuciones para el programa Care for Kids de este año.

Información del programa:
<program> Programa destinado a la obtención de recursos para escuelas en zonas rurales
</program>

Información del donante:
<donor> Bruce Wayne
</donor>

Piensa antes de escribir el correo electrónico en etiquetas <thinking>. Primero, piensa qué mensajes podrían atraer a este donante dado su historial de donaciones y qué campañas han apoyado en el pasado. Luego, piensa qué aspectos del programa Care for Kids les atraerían, dado su historial. Finalmente, escribe el correo electrónico personalizado en etiquetas <email>, usando tu análisis.


## Usando etiquetas XML

### Prompt 1

Analiza este acuerdo de licencia de software para identificar riesgos y responsabilidades potenciales:
ACUERDO DE LICENCIA DE SOFTWARE

Este Acuerdo de Licencia ("Acuerdo") se celebra entre SoftwareTech S.A. ("Licenciante") y Cliente XYZ ("Licenciatario").

1. Concesión de licencia: El Licenciante otorga al Licenciatario una licencia no exclusiva, intransferible y limitada para usar el software.
2. Propiedad intelectual: Todo el software y su documentación siguen siendo propiedad exclusiva del Licenciante.
3. Limitación de responsabilidad: El Licenciante no será responsable por daños indirectos, incidentales o consecuentes que surjan del uso del software.
4. Indemnización: El Licenciatario acuerda indemnizar y mantener indemne al Licenciante frente a cualquier reclamación derivada del uso indebido del software.
5. Terminación: El presente acuerdo podrá rescindirse en caso de incumplimiento por parte del Licenciatario.


Concéntrate en las cláusulas de indemnización, limitación de responsabilidad y propiedad intelectual. Además, señala cualquier término inusual o preocupante. Aquí está nuestro contrato estándar como referencia:
CONTRATO ESTÁNDAR DE LICENCIA DE SOFTWARE

1. Concesión de licencia: Se otorga una licencia de uso no exclusiva y revocable.
2. Propiedad intelectual: Los derechos de autor y demás derechos relacionados con el software pertenecen al Licenciante.
3. Limitación de responsabilidad: La responsabilidad del Licenciante se limita al monto pagado por el Licenciatario por el uso del software.
4. Indemnización: El Licenciatario indemnizará al Licenciante en la medida en que la ley lo permita.
5. Terminación: El contrato podrá terminarse por incumplimiento sustancial, previa notificación.
Proporciona un resumen de hallazgos y recomendaciones para nuestro equipo legal.

### Prompt 2

Analiza este acuerdo de licencia de software para riesgos y responsabilidades legales.

Somos una empresa multinacional considerando este acuerdo para nuestra infraestructura de datos central.

<agreement>
ACUERDO DE LICENCIA DE SOFTWARE

Este Acuerdo de Licencia ("Acuerdo") se celebra entre SoftwareTech S.A. ("Licenciante") y Cliente XYZ ("Licenciatario").

1. Concesión de licencia: El Licenciante otorga al Licenciatario una licencia no exclusiva, intransferible y limitada para usar el software.
2. Propiedad intelectual: Todo el software y su documentación siguen siendo propiedad exclusiva del Licenciante.
3. Limitación de responsabilidad: El Licenciante no será responsable por daños indirectos, incidentales o consecuentes que surjan del uso del software.
4. Indemnización: El Licenciatario acuerda indemnizar y mantener indemne al Licenciante frente a cualquier reclamación derivada del uso indebido del software.
5. Terminación: El presente acuerdo podrá rescindirse en caso de incumplimiento por parte del Licenciatario.
</agreement>

Este es nuestro contrato estándar de referencia:
<standard_contract>
CONTRATO ESTÁNDAR DE LICENCIA DE SOFTWARE

1. Concesión de licencia: Se otorga una licencia de uso no exclusiva y revocable.
2. Propiedad intelectual: Los derechos de autor y demás derechos relacionados con el software pertenecen al Licenciante.
3. Limitación de responsabilidad: La responsabilidad del Licenciante se limita al monto pagado por el Licenciatario por el uso del software.
4. Indemnización: El Licenciatario indemnizará al Licenciante en la medida en que la ley lo permita.
5. Terminación: El contrato podrá terminarse por incumplimiento sustancial, previa notificación.
</standard_contract>

<instructions>
1. Analiza estas cláusulas:
- Indemnización
- Limitación de responsabilidad
- Propiedad intelectual

2. Señala términos inusuales o preocupantes.

3. Compara con nuestro contrato estándar.

4. Resume hallazgos en etiquetas <findings>.

5. Lista recomendaciones accionables en etiquetas <recommendations>.</instructions>


## Reduciendo alucinaciones

### Prompt 1

Como nuestro asesor de fusiones y adquisiciones, analiza este informe sobre la potencial adquisición de AcmeCo por ExampleCorp.
<report>
INFORME DE ADQUISICIÓN: POSIBLE COMPRA DE ACMECO POR EXAMPLECORP

Resumen Ejecutivo:
ExampleCorp está evaluando la adquisición de AcmeCo, un proveedor regional de soluciones de logística. El objetivo principal es ampliar la presencia en el mercado norteamericano y diversificar la cartera de clientes.

Proyecciones Financieras:
- Ingresos actuales de AcmeCo: USD 150 millones anuales, con un crecimiento proyectado del 8% anual durante los próximos 3 años.
- EBITDA actual: 18% sobre ventas.
- Sinergias estimadas: reducción de costos operativos de aproximadamente USD 12 millones anuales tras la integración, principalmente en sistemas de TI y optimización de la cadena de suministro.
- Costos de integración previstos: USD 20 millones distribuidos en dos años.

Riesgos de Integración:
- Diferencias culturales entre los equipos directivos de ambas compañías.
- Sistemas tecnológicos incompatibles que requerirán migraciones costosas.
- Dependencia de AcmeCo en dos clientes principales, que representan el 40% de sus ingresos.

Obstáculos Regulatorios:
- La transacción podría estar sujeta a revisión por parte de la autoridad de competencia local debido al incremento de cuota de mercado en el sector logístico regional.
- No se identifican actualmente restricciones internacionales relevantes.

Notas Adicionales:
- El informe carece de información detallada sobre litigios pendientes o pasivos ambientales.
- No se incluye un análisis exhaustivo de la retención de talento clave tras la adquisición.
 </report>
Concéntrate en las proyecciones financieras, riesgos de integración y obstáculos regulatorios.

### Prompt 2

Redacta un comunicado de prensa para nuestro nuevo producto de ciberseguridad, AcmeSecurity Pro, usando solo información de estos informes de producto y reportes de mercado.
<documents> 
INFORME DE PRODUCTO: ACMESecurity Pro

- AcmeSecurity Pro es una solución integral de ciberseguridad diseñada para pequeñas y medianas empresas.
- Incluye detección de amenazas en tiempo real, protección contra ransomware y filtrado avanzado de correo electrónico.
- El producto está disponible en modalidad de suscripción mensual o anual.
- Una de sus ventajas diferenciales es la facilidad de implementación, con un tiempo promedio de despliegue de 48 horas.
- Compatible con sistemas Windows, macOS y Linux.

REPORTE DE MERCADO: TENDENCIAS EN CIBERSEGURIDAD 2025

- El mercado global de ciberseguridad se estima en 210 mil millones USD en 2025, con un crecimiento anual del 12%.
- Las pequeñas y medianas empresas representan el segmento de mayor crecimiento, debido al aumento de ataques de ransomware.
- La demanda por soluciones de rápida implementación y bajo costo de mantenimiento se ha incrementado significativamente.
- Los clientes buscan cada vez más proveedores que ofrezcan soporte técnico especializado y tiempo de respuesta reducido.
 </documents>
Después de redactar, revisa cada afirmación en tu comunicado de prensa. Para cada afirmación, encuentra una cita directa de los documentos que la respalde. Si no puedes encontrar una cita de respaldo para una afirmación, elimina esa afirmación del comunicado de prensa y marca donde fue eliminada con corchetes vacíos [].



## Actividad - Creando contenido para redes sociales

### Brief

https://1drv.ms/t/c/2c11b62be5eb284d/EdCJ7V0kJJdPv_KpSM_sOmEBXHsf8EXFnyAUW29yzYHDIQ?e=dLWItQ

### Prompt 1

Escribe 2 posts para redes sobre nuestro producto.

### Prompt 2

Actúa como estratega de social media. Crea 2 posts por plataforma (LinkedIn, X, Instagram) para el lanzamiento de AcmeSecurity Pro.

Contexto:
- Audiencia: decisores de PyMEs (IT/Operaciones) sin equipo de seguridad dedicado.
- Objetivo: awareness + generación de leads (demo/prueba 30 días).
- Mensajes clave (usa SOLO el <brief> y <market_report> que pegué arriba):
  seguridad para PyMEs, despliegue en 48 horas, detección en tiempo real,
  protección ransomware, filtrado de correo, compatibilidad multiplataforma,
  rapidez de implementación y soporte.
- Estilo: profesional y accesible. No uses puntos suspensivos.

Requisitos por plataforma:
- LinkedIn: 2 publicaciones de 80–150 palabras; 1 dato de mercado por post.
- X: 2 publicaciones <250 caracteres + 2–3 hashtags con criterio.
- Instagram: 2 captions de 80–120 palabras + CTA claro.

Entrega en JSON con campos: plataforma, copy, hashtags, cta.
Si falta información, di claramente: “No lo sé con certeza”.

### Prompt 3

Estos posts se usarán en una campaña de 7 días con pauta ligera. Prioriza claridad sobre tecnicismos. 
Cada copy debe responder: ¿por qué ahora? y ¿por qué AcmeSecurity Pro?


### Prompt 4

Ejemplos de tono:
- “Actualiza tu defensa en días, no en meses.”
- “Menos tiempo desplegando, más tiempo creciendo.”
Regla: cuando expliques un concepto difícil, usa una metáfora sencilla (p.ej., “Zero Trust es como pedir identificación en cada puerta de la oficina”).


### Prompt 5

Actúa como estratega de social media. Crea 2 posts por plataforma (LinkedIn, X, Instagram) para el lanzamiento de AcmeSecurity Pro.

Contexto:
- Audiencia: decisores de PyMEs (IT/Operaciones) sin equipo de seguridad dedicado.
- Objetivo: awareness + generación de leads (demo/prueba 30 días).
- Mensajes clave (usa SOLO el <brief> y <market_report> que pegué arriba):
  seguridad para PyMEs, despliegue en 48 horas, detección en tiempo real,
  protección ransomware, filtrado de correo, compatibilidad multiplataforma,
  rapidez de implementación y soporte.
- Estilo: profesional y accesible. No uses puntos suspensivos.

Requisitos por plataforma:
- LinkedIn: 2 publicaciones de 80–150 palabras; 1 dato de mercado por post.
- X: 2 publicaciones <250 caracteres + 2–3 hashtags con criterio.
- Instagram: 2 captions de 80–120 palabras + CTA claro.

Formato de salida:
<entrega>
  <posts>
    <post plataforma="LinkedIn" id="L1"><copy>...</copy><hashtags>...</hashtags><cta>...</cta></post>
    ...
  </posts>
  <imagenes>
    <prompt id="I1">Una ilustración hiperrealista de {{sujeto}}, en un {{escenario}}, con un estilo {{estilo}}, iluminación {{iluminacion}}. La imagen debe transmitir {{emocion}} y estar en formato {{formato}}.</prompt>
  </imagenes>
</entrega>

### Prompt 6

Redacta un post para {{plataforma}} usando los documentos adjuntos.
Audiencia: {{audiencia}}. Objetivo: {{objetivo}}. Tono: {{tono}}.
Restricciones: {{restricciones}}.
Formato de salida: {{formato}}.
Incluye CTA: {{cta}}.

Datos:
LinkedIn
Profesionales de marketing digital y gerentes de innovación
Inspirar a la audiencia a adoptar nuevas tecnologías de IA para optimizar procesos
Profesional, motivador y cercano
Extensión máxima de 5 párrafos, sin tecnicismos excesivos, lenguaje claro
Post en texto para LinkedIn
Invitar a agendar una demo gratuita

### Prompt 7

Crea 2 posts para redes sociales, antes de escribir, evalúa internamente:
1) Qué objeciones tiene una PyME ante soluciones de seguridad.
2) Qué beneficios del <brief> responden esas objeciones.
3) Cómo adaptar el mismo mensaje a LinkedIn vs X vs Instagram.
No muestres este análisis; entrega solo los posts finales.

### Prompt 8

Revisa tus posts contra esta rúbrica (responde con un checklist):
- Claridad (1–5)
- Ajuste a audiencia PyME (1–5)
- Mensajes clave presentes y citables del <brief> (1–5)
- Diferenciador “despliegue en 48 horas” visible (Sí/No)
- CTA claro (Sí/No)
- Longitud por plataforma (OK/Atención)
- Propuesta de imagen coherente con el copy (1–5)
- Cumple “sin puntos suspensivos” (Sí/No)
Luego sugiere 3 mejoras concretas y reescribe solo los posts que lo necesiten.


### Prompt 9

Crea una propuesta de calendario de contenidos para el mes de Septiembre, en formato markdown que tengan las siguientes columnas para el producto en los archivos adjuntos:
Día | Plataforma | Objetivo | Gancho | Copy Resumen | CTA | Creativo

# Configuraciones y Artefactos
## Estableciendo tonos de respuestas generales

### Métodos ó enfoques preferidos
-	Explica primero con un resumen y luego con más detalle si lo pido
-	Organiza la respuesta en pasos o listas numeradas
-	Prioriza ejemplos prácticos en lugar de teoría abstracta

### Términos comunes o conceptos que usas
-	Habla en términos de negocio, como ROI, métricas clave, stakeholders
-	Explica en lenguaje educativo usando aprendizaje activo, competencias, metodologías
-	Manén un vocabulario propio del ámbito creativo como storytelling, brainstorming, moodboard, narrativa visual.

### Escenarios típicos que encuentres
-	Resume documentos largos en secciones y puntos clave
-	Da repuestas rápidas y concisas
-	Explica conceptos complejos con analogías fáciles de comprender

### Preferencias comunes
-	Siempre presenta pros y contras en tablas
-	Siempre usa bullet lists para una mejor comprensión
-	Siempre termina usando una cita de alguien famoso experto en el tema


## Probando estilos

### Prompt

Explícame porqué el cielo es azul

## Creando proyectos

### Sitio Gutenberg

https://www.gutenberg.org/browse/languages/es

### Configuración del proyecto

Fábulas modernas
Un nuevo libro de fábulas para el día de hoy


### Prompt 1

Crea una fábula original, inspirada en el estilo clásico de Esopo, pero adaptada a los jóvenes de hoy en día.
•	El tema central debe girar en torno a los adolescentes y jóvenes que pasan demasiado tiempo con el celular, mostrando cómo esto afecta sus relaciones, su atención y sus oportunidades.
•	La fábula debe incluir personajes animales o simbólicos, con un tono narrativo sencillo y atractivo, fácil de entender para jóvenes.
•	El relato debe transmitir un mensaje moral claro y actual, con un cierre contundente que invite a la reflexión.
•	Al final, incluye una explicación breve y explícita de la moraleja, escrita en un lenguaje cercano a los adolescentes, para que comprendan cómo aplicar la enseñanza en su vida cotidiana.

## Revisando artefactos creados

### Prompt 1

Crea una aplicación sencilla que funcione como un contador de palabras y caracteres.
- Debe permitir al usuario escribir o pegar texto en un área de texto.
- Mostrar en tiempo real:
  - El número de palabras.
  - El número de caracteres con y sin espacios.
- La interfaz debe ser limpia y minimalista, con un área grande para el texto y un panel de resultados debajo o al lado.
- Usa HTML, CSS y JavaScript (sin frameworks pesados).
- Opcional: agrega un botón para limpiar el texto y reiniciar los contadores.

### Artefacto creado

https://claude.ai/public/artifacts/fa702933-4ead-42ed-88a8-16f521408f75

## Creando artefactos con la API de Claude

### Prompt 1

Crea una aplicación web interactiva para practicar los tiempos verbales en inglés usando IA.
Requisitos principales:
1.	La aplicación debe tener un menú desplegable con los tiempos verbales ya prerellenados (por ejemplo: Present Simple, Past Perfect, Future Continuous, etc.).
2.	Al elegir un tiempo verbal, el usuario podrá pulsar un botón que diga "Iniciar ejercicio".
3.	Al iniciar, se deben generar automáticamente 10 preguntas de opción múltiple relacionadas con el tiempo verbal seleccionado.
- Cada pregunta mostrará una frase en español y cuatro posibles traducciones al inglés.
- Solo una opción será correcta.
4.	Al finalizar el cuestionario, la app debe mostrar el puntaje final del usuario (ej. “Acertaste 7/10”).
5.	Con ayuda de la IA, la app debe generar un análisis personalizado de los errores del usuario, explicando en qué tiempos verbales o estructuras suele fallar y sugiriendo cómo mejorar.
Tecnología sugerida:
- Frontend en HTML, CSS y JavaScript (puede ser React para hacerlo más dinámico).
- Uso de un modelo de IA para la generación de preguntas y el análisis de resultados.
Opcional:
- Incluir un botón para repetir el ejercicio con nuevas preguntas.
- Mostrar el tiempo estimado de práctica y evolución del usuario con el tiempo.


## Actividad Práctica - Creando artefactos sobre el caso JFK

### URLs

[Repositorio documentos del caso](https://github.com/Shaier/JFK_Records)

### Prompt 1

Crea un reporte de 1 hoja que muestre los principales misterios que nunca fueron resueltos sobre el caso JFK

### Prompt 2

Crea un sitio interactivo que muestre una línea del tiempo de los hechos del caso

### Prompt 3

Construye un grafo que muestre las conexiones entre los principales involucrados y las organizaciones mencionadas en los documentos.

### Prompt 4

Muestra un recorrido geográfico de Lee Harvey Oswald según los informes del FBI antes del asesinato

# Servidores MCP
## Qué es MCP
## Instalando Node.js y Claude Desktop

### URLs

[Claude Desktop](https://claude.ai/download)

[NodeJS](https://nodejs.org/es)

## Usando MCP de forma local
## Servidores MCP populares

### Links

- [Claude MCP Community](https://www.claudemcp.com/)
- [Listado servidores MCP](https://github.com/modelcontextprotocol/servers)
- [Awesome MCP Servers](https://mcpservers.org/)

## Integrando un servidor remoto gratuito MCP con Claude

### Links

- [Awesome MCP Servers](https://mcpservers.org/)

### Prompt 1

¿Cuál es la criptomoneda que ha tenido mejor comportamiento y en la que me recomiendas invertir?

## Integrando un servidor remoto con autenticación MCP con Claude

### Prompt 1

¿Qué eventos hay en mi calendario para esta semana?

### Prompt 2

Lista los archivos asociados a mi cuenta

## Potenciando el uso de servidores MCP con zapier

### Links

- [Zapier MCP](https://zapier.com/mcp)

### Prompt 1

Busca 10 videos en YouTube que tengan una gran cantidad de Views y dime qué debo abarcar si quiero hacer un video de la temática "Claude AI", para que sea igual de exitoso

## Seguridad y riesgos

### Links

[MCP Security Issues](https://www.docker.com/blog/mcp-security-issues-threatening-ai-infrastructure/)

## Trabajo futuro

[Roadmap MCP](https://modelcontextprotocol.io/development/roadmap)

## Actividad Práctica - Creando contenido usando servidores MCP

### Brief

https://1drv.ms/t/c/2c11b62be5eb284d/EdCJ7V0kJJdPv_KpSM_sOmEBXHsf8EXFnyAUW29yzYHDIQ?e=dLWItQ

### Prompt 1

A partir del brief de mi producto, crea un post para Instagram usando Canva ideal para destacar la seguridad de mi producto. Incluye elementos relacionados a hackers, además de usar el color #160752 como principal

### Prompt 2

Lee mis eventos de hoy/mañana y resúmelos en 5 viñetas.

### Prompt 3

Encuentra 3 huecos de 30 min esta semana de entre 10 de la mañana a 12 del día

### Prompt 4

Redacta un borrador de correo de disponibilidad para Luis Hernández (luis@hernandez.com) con esos huecos, invitando a conocer el producto del brief

### Prompt 5

Usando el navegador, busca 2 competidores de mi producto

### Prompt 6

Crea un post de 1000 palabras para mi sitio, indicando porqué mi solución es la mejor, usando las mejores prácticas de escritura como el uso de títulos, elementos para destacar elementos, etc.

### Prompt 7

A partir del brief de mi producto, crea un sitio web usando archivos html + archivos css + archivos js guardando los archivos localmente (Usa una nueva carpeta para este proyecto). Usa el color #160752 como principal para la interfaz, y dedice los mejores elementos para una página tipo SPA.

# Claude Code
## Introduction a Claude Code

### Links

- [Claude Code](https://claude.com/product/claude-code)

## Configurando Claude Code

### Comandos

npm install -g @anthropic-ai/claude-code

claude --help

## Generación de código usando Claude Code

### Prompt 1

¿Qué archivos hay en la carpeta?

### Prompt 2

Crea una aplicación web que permita generar contraseñas seguras y aleatorias. Se debe poder indicar la longitud de la contraseña, así como si deben o no usarse caracteres especiales. Además, debe existir un historial de las contraseñas generadas.

### Prompt 3

Los colores no me gustan, quiero que se vea mas empresarial.

### Prompt 4

Crea pruebas unitarias para validar que la interfaz se vea bien al momento de agregar una nueva contraseña en la lista, y no se distorsione o salga de la pantalla

## Usando archivos y proyectos existentes

### Links

[Cara Ecommerce](https://github.com/anuragino/Cara-Ecommerce-Website)

[API de productos](https://fakestoreapi.com/docs#tag/Products)

### Prompt 1

Modifica el diseño de la tienda, siendo que es un sitio orientado a la venta de ropa para mi emprendimiento llamado “PlayerIAs”. Usa esta paleta de colores:
Principal: #1E90FF, #FFD60A, #FFFFFF, #121212, #FF5A76
Secundaria: #F2F2F2, #40E0D0, #A3EB34 
También modifica los textos para que estén alienados con mi tipo de tienda


### Prompt 2

Ahora, necesito que el sitio sea dinámico. Esto significa que alguien me ha pasado la documentación de una API para llenar la información del sitio, la cual es esta. Analiza la documentación y haz que el sitio se conecte a la api: https://fakestoreapi.com/docs#tag/Products
Cuida siempre el tamaño de las imágenes para que no se desordene la interfaz gráfica

## Actividad Práctica - Creando una extensión de Google Chrome

### Links

[Base extensión Google Chrome](https://1drv.ms/u/c/2c11b62be5eb284d/Edud89-2tmJCggRkzLjPG7sBk5VV_SpeRQfsndq4yYG_oQ?e=QOSOY2)

### Prompt 1

Toma los archivos como base para crear una extensión de Chrome.
Necesito que los adaptes para implementar un plugin tipo modo de lectura enfocado, con las siguientes características:
1.	Eliminación de distracciones: Oculta todos los elementos irrelevantes de la página (barras laterales, anuncios, menús, pop-ups, etc.), mostrando únicamente el contenido principal del artículo o texto.
2.	Personalización visual para lectura cómoda:
- Fondo en color sepia suave.
- Texto en un tono oscuro contrastante y agradable a la vista.
- Ajustes de tipografía para mejorar la legibilidad (ej. tamaño adecuado, interlineado cómodo, márgenes equilibrados).
3.	Compatibilidad básica: Asegúrate de que funcione en sitios web comunes de lectura (blogs, periódicos digitales, plataformas educativas).
4.	Opciones de activación: Que el usuario pueda activar y desactivar el modo enfocado desde el ícono de la extensión en la barra de Chrome.
El objetivo final es tener una extensión ligera y práctica que proporcione una experiencia de lectura limpia y relajante, similar a un “lector inmersivo” personalizado.
