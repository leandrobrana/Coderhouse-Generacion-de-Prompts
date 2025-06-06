---


---

<h1 id="asistencia-nutricional-con-soporte-visual">Asistencia Nutricional con soporte visual</h1>
<p>En la práctica profesional de la nutrición, uno de los desafíos recurrentes es la elaboración de planes alimentarios personalizados que respondan con precisión a las necesidades nutricionales específicas de cada paciente. Esta tarea requiere tiempo, conocimientos actualizados y una adecuada presentación visual que facilite la aceptación y comprensión de las propuestas dietéticas.<br>
El presente trabajo busca abordar esta problemática mediante el desarrollo de un asistente nutricional basado en inteligencia artificial. Esta herramienta está pensada para asistir al profesional en la generación de recetas personalizadas, ajustadas a los requerimientos individuales de cada paciente, y en la creación de imágenes ilustrativas de los platos sugeridos. La posibilidad de visualizar las recetas no solo mejora la comunicación entre profesional y paciente, sino que también promueve la adhesión al tratamiento nutricional. Por estas razones, resulta relevante desarrollar una solución que integre estas capacidades de manera ágil y eficiente.</p>
<h1 id="desarrollo-de-la-propuesta-de-solución">Desarrollo de la propuesta de solución</h1>
<p>La solución propuesta consiste en un asistente virtual potenciado por modelos de inteligencia artificial que permite generar recetas personalizadas a partir de las restricciones nutricionales y preferencias alimentarias de cada paciente. Esta herramienta integra dos tipos de modelos IA:</p>
<ul>
<li>Texto → Texto: para la generación automática de recetas únicas, que incluyen el nombre del plato, una lista detallada de ingredientes y un instructivo paso a paso.</li>
<li>Texto → Imagen: para la creación de representaciones visuales atractivas y realistas del plato final, facilitando la presentación al paciente.</li>
</ul>
<p>Proceso de trabajo en tres etapas:</p>
<ol>
<li>
<p>Input profesional: El nutricionista redacta un prompt que describe<br>
las necesidades del paciente. Ejemplo: “Quiero desarrollar una<br>
receta para un paciente celíaco, que cumpla con un 25% de fibras,<br>
25% de vegetales de estación y 50% de carnes rojas.”</p>
</li>
<li>
<p>Generación textual: El modelo de texto produce:</p>
<ul>
<li>
<p>Nombre del plato y descripción de características nutricionales.</p>
</li>
<li>
<p>Lista de ingredientes detallada.</p>
</li>
</ul>
</li>
<li>
<p>Visualización: El modelo de texto a imagen genera una representación visual del plato con estética realista.</p>
</li>
</ol>
<h1 id="justificación-de-la-viabilidad-del-proyecto">Justificación de la viabilidad del proyecto</h1>
<p>La viabilidad técnica es alta. Existen modelos avanzados como <strong>Gemini 2.0 flash</strong> para generación de texto y  generación de imágenes, que se integran fácilmente mediante APIs ya entrenadas.</p>
<p>Desde el punto de vista de recursos, se pueden usar herramientas accesibles (como Python, bibliotecas de IA, plataformas en la nube), lo cual reduce tiempos de desarrollo y evita entrenamientos desde cero.</p>
<p>Además, el desarrollo se puede abordar en etapas modulares: primero la parte textual, luego la visual. Esto permite avances progresivos y pruebas por fase.</p>
<p>La elección de esta solución se justifica por su impacto en la práctica del nutricionista, ya que aporta eficiencia, personalización y una mejor experiencia para el paciente, sin requerir infraestructura costosa ni conocimientos técnicos avanzados del usuario final.</p>
<h1 id="objetivos">Objetivos</h1>
<ul>
<li>
<p>Desarrollar un asistente virtual que permita generar recetas personalizadas mediante IA.</p>
</li>
<li>
<p>Integrar visualizaciones realistas de platos a partir de descripciones textuales.</p>
</li>
<li>
<p>Mejorar la eficiencia y presentación de recetas</p>
</li>
</ul>
<h1 id="metodología">Metodología</h1>
<p>El proyecto se llevará a cabo mediante una <strong>estrategia iterativa en tres fases</strong>, lo cual permite desarrollar, probar y refinar cada componente por separado, garantizando resultados funcionales en cada etapa:</p>
<ol>
<li>
<p><strong>Fase 1 – Recolección de requerimientos y diseño de prompts base:</strong><br>
Se definirán diferentes perfiles de pacientes con necesidades nutricionales específicas (ej. celíacos, diabéticos, personas con sobrepeso). A partir de ellos se crearán <em>prompts tipo</em> que permitan guiar al modelo de lenguaje en la generación precisa de recetas.</p>
</li>
<li>
<p><strong>Fase 2 – Generación y validación de recetas (Texto → Texto):</strong><br>
Se implementará un proyecto en Python con integración a la API de <strong>Gemini</strong> para generar recetas a partir de los prompts definidos. Se evaluará la calidad de las salidas y se ajustarán los <em>prompts</em> para maximizar claridad, utilidad nutricional y estructura.</p>
</li>
<li>
<p><strong>Fase 3 – Visualización del plato (Texto → Imagen):</strong><br>
Utilizando un modelo como DALL·E o alternativas gratuitas como Nightcafe, se generarán imágenes realistas de los platos sugeridos. La representación visual se contrastará con las descripciones obtenidas en la fase anterior.</p>
</li>
</ol>
<p><strong>Justificación:</strong> Esta metodología modular permite testear por separado la lógica textual y visual, facilitando mejoras graduales. También se adapta a los recursos disponibles y a una entrega en fases.</p>
<h1 id="herramientas-y-tecnologías"><strong>Herramientas y tecnologías</strong></h1>
<ul>
<li>
<p><strong>Lenguaje de programación:</strong> Python (por su amplio soporte en bibliotecas de IA y facilidad de integración con APIs).</p>
</li>
<li>
<p><strong>Entorno de desarrollo:</strong> Google Colab (para documentación integrada y ejecución interactiva).</p>
</li>
<li>
<p><strong>Modelo de generación de texto:</strong> Gemini 2.0 Flash (para generar recetas completas, coherentes y ajustadas a las necesidades del usuario).</p>
</li>
<li>
<p><strong>Modelo de generación de imágenes:</strong> Gemini 2.0 Flash</p>
</li>
</ul>

