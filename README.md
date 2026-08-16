# Kairós — Prototipo de Seguridad Cognitiva y Adaptación Cultural

> Prototipo de producto informático orientado a fortalecer la prevención de riesgos digitales mediante la integración de psicología cognitiva, factores culturales y diseño centrado en el usuario.

---

## Descripción

**Kairós** es un prototipo académico desarrollado como parte del **Proyecto Integrador de la asignatura Ingeniería y Pensamiento Humano**.

El proyecto parte de una premisa fundamental: un sistema de ingeniería no puede considerarse verdaderamente eficaz si ignora los procesos cognitivos, emocionales y culturales de las personas que interactúan con él.

A partir de esta perspectiva, Kairós propone una experiencia digital orientada a estudiantes extranjeros que llegan a instituciones de educación superior en Ecuador y que, durante su proceso de adaptación, pueden encontrarse con situaciones de incertidumbre, presión, desconocimiento del contexto local y posibles riesgos asociados con fraudes, estafas o malentendidos administrativos.

La propuesta busca favorecer una respuesta **deliberada y consciente**, promoviendo que el usuario se detenga, verifique la información disponible y tome una decisión antes de actuar impulsivamente.

---

## Objetivo

Diseñar un producto informático que aplique principios de **psicología cognitiva y factores culturales** para ayudar a estudiantes extranjeros a reconocer y responder de forma deliberada, y no impulsiva, ante situaciones de riesgo durante su proceso de adaptación a un nuevo país.

El diseño considera que la seguridad no depende únicamente de identificar técnicamente una amenaza, sino también de la manera en que una persona percibe, interpreta y responde ante ella.

---

## Problemática

Durante sus primeros meses en un nuevo país, los estudiantes extranjeros pueden enfrentarse a situaciones que combinan:

- Desconocimiento del contexto local.
- Diferencias culturales.
- Barreras lingüísticas.
- Presión de tiempo.
- Estrés y activación emocional.
- Incertidumbre frente a instituciones.
- Sobrecarga de información.
- Posibles intentos de fraude o estafa.

En este contexto, una alerta técnicamente correcta puede perder efectividad si su lenguaje, tono, estructura o presentación no coinciden con la manera en que el usuario interpreta la situación.

Por ello, Kairós propone abordar la prevención desde una perspectiva que combine **seguridad informática y comprensión del comportamiento humano**.

---

## Público objetivo

Kairós está dirigido principalmente a:

**Estudiantes extranjeros de intercambio o de nuevo ingreso que llegan a instituciones de educación superior en Ecuador.**

El proyecto reconoce que este grupo presenta diversidad en aspectos como:

- País de origen.
- Idioma materno.
- Estilo de comunicación.
- Tolerancia a la incertidumbre.
- Experiencias previas de adaptación.
- Confianza hacia determinadas instituciones.

Por esta razón, Kairós evita plantear una solución única y propone adaptar la forma en que se comunica una situación de riesgo según las características del usuario.

---

## Fundamento interdisciplinario

El desarrollo conceptual de Kairós integra conocimientos provenientes de diferentes áreas:

| Área | Aplicación en Kairós |
|---|---|
| Psicología cognitiva | Percepción, atención, memoria y toma de decisiones |
| Neurociencia | Activación simpática, estrés y decisiones bajo presión |
| Diseño de interfaces | Jerarquía visual, principios Gestalt y affordances |
| Factores culturales | Adaptación del lenguaje, tono y estructura de las alertas |
| Ciberseguridad | Prevención de fraudes, estafas e ingeniería social |
| Diseño centrado en el usuario | Adaptación de la experiencia según las necesidades del usuario |

Estos fundamentos permiten trasladar conceptos estudiados durante la asignatura hacia una propuesta concreta de producto informático. 

---

## Funcionalidades propuestas

El concepto de Kairós contempla seis funcionalidades principales.

### 1. Detector de momentos de riesgo

Analiza textos pegados o reenviados, como mensajes, anuncios o correos, en busca de indicadores asociados con urgencia y presión emocional.

La finalidad es ayudar al usuario a identificar situaciones que podrían requerir una verificación adicional antes de actuar.

### 2. Perfil cultural del estudiante

Un breve cuestionario inicial permite establecer información como:

- País de origen.
- Idioma preferido.
- Estilo de comunicación.

Esta información permite adaptar la manera en que se presenta una alerta, sin modificar los criterios fundamentales de identificación del riesgo.

### 3. Fricción cultural adaptativa

En lugar de presentar únicamente una advertencia genérica, Kairós introduce una pausa breve antes de que el usuario continúe.

La intervención puede presentarse mediante:

**Modo narrativo:** explicación de un caso similar para facilitar la comprensión.

**Modo checklist:** presentación directa de datos y pasos concretos de verificación.

### 4. Banco de normas locales

Presenta información sobre situaciones y prácticas habituales en Ecuador mediante analogías con situaciones equivalentes del país de origen del estudiante.

Su propósito es disminuir la incertidumbre cultural y facilitar la interpretación del contexto.

### 5. Puntos de calma

Kairós plantea una lógica de gamificación invertida.

En lugar de premiar únicamente la rapidez, el sistema reconoce la acción de **detenerse y verificar antes de actuar**, reforzando el pensamiento deliberado.

### 6. Modo comunidad

Permite que otros estudiantes indiquen que una situación similar también les ocurrió.

La finalidad es generar conocimiento compartido y una capa adicional de confianza social, evitando la exposición innecesaria de datos personales.

Estas funcionalidades forman parte del diseño conceptual desarrollado para Kairós. 

---

## Flujo del prototipo

La propuesta se estructura mediante siete pantallas principales:

| # | Pantalla | Función |
|---|---|---|
| 01 | Bienvenida y perfil cultural | Configuración inicial del usuario |
| 02 | Panel principal | Visualización de puntos de calma, alertas recientes y progreso |
| 03 | Intervención | Presentación de la pausa adaptativa |
| 04 | Banco de normas locales | Consulta de analogías entre prácticas culturales |
| 05 | Modo comunidad | Consulta de experiencias compartidas |
| 06 | Historial y aprendizajes | Registro de situaciones revisadas |
| 07 | Perfil y configuración | Gestión de idioma, comunicación y privacidad |

El flujo busca acompañar al usuario desde la identificación de una posible situación de riesgo hasta una toma de decisión más consciente y deliberada. 

---

## Sistema de diseño

El sistema visual de Kairós responde a una lógica funcional y psicológica.

### Paleta de colores

| Color | Código | Uso |
|---|---|---|
| Guinda | `#800020` | Situaciones de riesgo real |
| Teal | `#2C6E7F` | Estado normal, calma y confianza |
| Dorado | `#D4AF37` | Logros y puntos de calma |

El color guinda se reserva para momentos de riesgo real, evitando utilizar constantemente una señal visual de alta intensidad emocional.

El teal representa el estado normal de la aplicación y se relaciona con una experiencia de calma y confianza.

El dorado se utiliza para representar logros y puntos de calma.

La selección cromática responde a decisiones relacionadas con la prevención de la fatiga de alertas y la jerarquía visual de la interfaz.

---

## Principios de diseño aplicados

El prototipo incorpora principios psicológicos y de interacción estudiados durante el proyecto:

- Principios Gestalt.
- Ley de Weber.
- Carga cognitiva.
- Memoria de trabajo.
- Teoría de la autodeterminación.
- Condicionamiento operante.
- Affordances.
- Diseño culturalmente adaptable.

Una de las restricciones principales del diseño consiste en evitar introducir más de tres piezas de información nueva simultáneamente en una pantalla.

Esta decisión busca reducir la sobrecarga cognitiva y facilitar la comprensión durante situaciones que pueden implicar presión o estrés.

---

## Diseño responsive

El prototipo será desarrollado como una **aplicación web responsive**, con el objetivo de proporcionar una experiencia coherente en diferentes tamaños de pantalla.

Se contemplan principalmente dos contextos de uso:

### Computador

La interfaz aprovechará un espacio de visualización más amplio para organizar información, navegación, paneles y elementos de consulta.

### Dispositivo móvil

La interfaz se adaptará a pantallas reducidas, priorizando:

- Legibilidad.
- Jerarquía visual.
- Navegación sencilla.
- Acciones principales claramente identificables.
- Reducción de información innecesaria.
- Interacción adecuada mediante dispositivos táctiles.

El diseño responsive permitirá que el prototipo mantenga su estructura visual y funcional sin depender de un único tipo de dispositivo.

---

## Tecnologías y entorno de desarrollo

La elaboración del prototipo se realizará utilizando **Visual Studio Code** como entorno principal de desarrollo.

El proyecto será construido como una aplicación web y se orientará a diferentes tamaños de pantalla mediante principios de diseño responsive.

### Entorno

- Entorno de desarrollo: Visual Studio Code.
- Tipo de producto: Aplicación web.
- Diseño: Responsive Design.
- Dispositivos objetivo: Computadores y teléfonos móviles.
- Publicación del prototipo: GitHub Pages.

Las tecnologías específicas de implementación podrán documentarse y actualizarse en esta sección a medida que avance el desarrollo del prototipo.

---

## Evaluación del concepto

Como parte del proyecto se realizó una prueba de usabilidad simulada mediante la metodología **think-aloud**, utilizando tres perfiles de estudiantes extranjeros con diferentes características culturales y estilos de comunicación.

A cada participante se le presentó una situación de riesgo relacionada con un anuncio de arriendo que contenía señales de urgencia.

Los resultados mostraron diferentes estrategias de interacción según el perfil de cada participante.

### Principales observaciones

- Un perfil valoró especialmente la intervención narrativa.
- Otro prefirió acceder directamente a información estructurada mediante un checklist.
- Otro utilizó el componente comunitario para comprobar si otros estudiantes habían experimentado una situación similar.

Los resultados refuerzan la necesidad de utilizar una comunicación adaptable en lugar de una única forma de alerta.

---

## Privacidad y consideraciones éticas

La privacidad constituye un aspecto fundamental para el desarrollo futuro de Kairós.

Algunas funcionalidades pueden involucrar información relacionada con:

- Nacionalidad.
- Idioma.
- Situación del usuario.
- Experiencias compartidas dentro de la comunidad.

Por esta razón, el desarrollo deberá considerar:

- Minimización de datos.
- Consentimiento informado.
- Protección de información personal.
- Privacidad en el modo comunidad.
- Políticas claras de conservación y eliminación de información.
- No utilización de la información para reportar actividad migratoria.

Estas consideraciones forman parte de las limitaciones y líneas de trabajo futuro identificadas en el proyecto.

---

## Alcance del prototipo

El presente repositorio corresponde al **prototipo académico de Kairós**.

Su propósito en esta etapa es materializar visual e interactivamente la propuesta conceptual desarrollada durante el Proyecto Integrador.

El prototipo no representa todavía un sistema de producción ni una herramienta de seguridad completamente desplegada.

Las funcionalidades y mecanismos de análisis podrán evolucionar en futuras etapas de desarrollo y validación.

---

## Trabajo futuro

Entre las principales líneas de desarrollo se contemplan:

- Realizar pruebas con estudiantes extranjeros reales.
- Ampliar la evaluación de usabilidad.
- Evaluar longitudinalmente el impacto de los puntos de calma.
- Ampliar el banco de normas locales a diferentes países.
- Profundizar la adaptación cultural.
- Incorporar criterios de accesibilidad.
- Fortalecer las medidas de privacidad.
- Evaluar la comprensión y confianza de los usuarios.
- Analizar la efectividad de las intervenciones frente a situaciones reales de riesgo.

Un desarrollo posterior requeriría una validación con una muestra más amplia y representativa de estudiantes extranjeros. 

---

## Contexto académico

**Proyecto Integrador**

**Asignatura:** Ingeniería y Pensamiento Humano

**Producto:** Kairós — Prototipo de Seguridad Cognitiva y Adaptación Cultural

El proyecto representa la aplicación práctica de los conocimientos estudiados durante la asignatura, integrando psicología, neurociencia, percepción, aprendizaje, memoria, motivación y factores culturales en el diseño de un producto informático.

La propuesta busca demostrar que la seguridad informática no depende exclusivamente de mecanismos técnicos, sino también de la comprensión de la persona que interactúa con el sistema.

Como futura Ingeniera en Ciberseguridad, este proyecto plantea una perspectiva centrada en una pregunta fundamental:

> ¿Por qué una persona razonable podría confiar en una situación de riesgo?

Comprender esa dimensión humana permite plantear soluciones de seguridad que no solamente detecten amenazas, sino que también ayuden a las personas a tomar mejores decisiones.

---

## Estado del proyecto

**Prototipo académico en desarrollo**

El repositorio documenta la evolución del prototipo de Kairós y servirá como espacio para su desarrollo, presentación y publicación web.

La versión final estará orientada a su visualización tanto desde computadores como desde dispositivos móviles.

---

## Acceso al prototipo

El enlace al prototipo web estará disponible una vez finalizada su implementación y publicación mediante GitHub Pages.

**Prototipo:** En desarrollo

**Repositorio:** `proyecto-kairos`

---

## Autora

**Elizabeth Guzmán**

Proyecto desarrollado para la asignatura **Ingeniería y Pensamiento Humano**.

---

## Referencias bibliográficas

El proyecto se fundamenta en aportes relacionados con psicología, percepción, memoria, aprendizaje, motivación, factores culturales, usabilidad y diseño de sistemas.

Entre las principales referencias utilizadas se encuentran:

- Anderson et al. — Advertencias de seguridad y habituación.
- Carlson — Fisiología de la conducta.
- Feldman — Psicología.
- Goldstein — Sensación y percepción.
- Hall — Comunicación y cultura.
- Hofstede — Dimensiones culturales.
- Krug — Usabilidad.
- Marcus y Gould — Diseño intercultural de interfaces.
- Miller — Memoria y procesamiento de información.
- Nielsen — Usabilidad.
- Norman — Diseño de productos y sistemas.
- Oberg — Choque cultural.
- Ryan y Deci — Teoría de la autodeterminación.
- Sweller — Carga cognitiva.
- Vygotsky — Aprendizaje y desarrollo.
- Zhang et al. — Riesgos de estafas dirigidas a estudiantes internacionales.

---

## Conclusión

Kairós representa una aproximación interdisciplinaria al diseño de productos informáticos seguros.

Su propuesta parte de una idea central: **la seguridad informática no termina donde termina el código, sino donde comienza la decisión de la persona que interactúa con él.**

Por medio de la integración de psicología cognitiva, factores culturales, diseño centrado en el usuario y principios de ciberseguridad, Kairós busca transformar un momento de incertidumbre y presión en una oportunidad para detenerse, verificar y decidir.

---

**Kairós**

*Detenerse. Verificar. Decidir.*

*La seguridad también comienza con una decisión humana.*
