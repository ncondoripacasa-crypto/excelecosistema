# ExcelQuest - El Dominio de la Hoja de Cálculo

ExcelQuest es una aventura interactiva (estilo RPG) y gamificada diseñada para enseñar Microsoft Excel desde cero. Está orientada a estudiantes que deseen dominar esta herramienta completando "Misiones" en un "Reino Digital", combinando retos teóricos, cuestionarios y **prácticas directas en un simulador de Excel integrado**.

## ⚔️ Características Épicas
- **Diseño Dark Mode RPG:** Interfaz oscura con acentos dorados (`#d4af37`), fuentes épicas (Cinzel) y mapas de ruta verticales para los niveles.
- **Simulador de Excel:** Zona de práctica interactiva que incluye Cinta de opciones, Barra de fórmulas y una cuadrícula (grid) donde los estudiantes deben hacer clic en celdas reales.
- **Sistema de Misiones:** 10 Reinos (niveles) desbloqueables. Cada nivel contiene múltiples retos progresivos para ganar XP.
- **Persistencia Mágica:** El progreso del héroe se guarda localmente en su navegador usando \`localStorage\`.
- **Vanilla Puro:** Cero dependencias o frameworks externos. Construido exclusivamente con HTML5, CSS3 y JavaScript moderno.

## 🗺️ Estructura del Reino
- \`index.html\`: Mapa de los Reinos y contenedores de Misiones (Teoría y Práctica con Simulador).
- \`styles.css\`: Temática oscura, animaciones CSS fluidas y diseño responsivo para móviles y escritorio.
- \`script.js\`: El "Dungeon Master" (lógica). Controla los retos, la inyección del mapa, interacción del simulador y XP.
- \`assets/\`: Bóveda para futuras imágenes o recursos gráficos estáticos.

## 📜 Las 10 Misiones (Reinos)
1. El Tablero de Juego (Conceptos básicos espaciales)
2. Conociendo las Herramientas (Navegación de UI)
3. Tipos de Datos (Alineación)
4. Calculadora Básica (Matemáticas con \`=\`)
5. Funciones Esenciales (\`SUMA\`, \`MAX\`)
6. Contando Datos (\`CONTAR\`, \`CONTARA\`)
7. Funciones Lógicas (\`SI\`)
8. Manipulación de Textos (\`CONCATENAR\`)
9. Viaje en el Tiempo (\`HOY\`, \`AHORA\`)
10. Atajos de Maestro (Shortcuts del teclado)

## 🔮 Cómo Jugar Localmente
1. Clona o descarga este repositorio.
2. Navega a la carpeta principal del proyecto.
3. Haz doble clic en el archivo \`index.html\` para abrirlo en tu navegador.
4. Presiona "Iniciar Aventura" y conquista los Reinos.

## 🏰 Despliegue en GitHub Pages
Para que otros héroes puedan jugar en línea:
1. Crea un repositorio en [GitHub](https://github.com/).
2. Sube los archivos a la rama \`main\`.
3. Ve a **Settings** > **Pages**.
4. En *Source*, selecciona la rama \`main\` y dale a **Save**.
5. ¡Tu aventura estará viva en internet!

6. # ExcelQuest: Ecosistema Inteligente de Aprendizaje de Excel Básico

## Problema Educativo
En el ámbito universitario de Bolivia, se identifica una disparidad crítica entre las competencias digitales requeridas por la educación superior y las habilidades efectivas de los estudiantes de nuevo ingreso. A pesar de ser considerados nativos digitales, su interacción tecnológica suele ser pasiva y limitada al consumo de contenido, evidenciando una carencia técnica en herramientas esenciales como **Microsoft Excel**. Esta brecha no solo perjudica el desempeño académico en áreas de análisis de datos, sino que fomenta el rezago y la deserción escolar ante la incapacidad de los modelos tradicionales para atender diversos niveles de aprendizaje de forma personalizada.

## Objetivo General
Evaluar el impacto de la implementación de un ecosistema de aprendizaje de Excel Básico, soportado por un tutor inteligente con Inteligencia Artificial, orientado a reducir en al menos un **30% la brecha tecnológica** en estudiantes de primer semestre de la **Universidad La Salle Bolivia**. El estudio contempla una intervención de tres meses y la comparación de competencias digitales mediante evaluaciones diagnósticas previas y posteriores.

## Arquitectura de IA
El núcleo tecnológico del proyecto se sustenta en una arquitectura de **Modelos de Lenguaje de Gran Escala (LLM)** basados en el diseño de *Transformers*. Esta elección permite un procesamiento avanzado del lenguaje natural para ofrecer explicaciones adaptadas pedagógicamente al nivel de cada usuario.

Para garantizar la precisión técnica, se utiliza un enfoque de **Generación Aumentada por Recuperación (RAG)**. Este método permite al tutor consultar fuentes de conocimiento específicas y verificadas (manuales, guías y documentación oficial), asegurando respuestas contextualizadas que promueven el aprendizaje significativo y evitan la generación de respuestas automáticas sin base pedagógica.

## Tecnologías Usadas
- **Modelos de Lenguaje (LLM):** Arquitectura Transformer para la interacción natural.
- **Enfoque de Recuperación (RAG):** Integración de bases de conocimiento técnicas.
- **Entornos Locales:** Posible despliegue con modelos *open source* como **Llama** o **Gemma** para garantizar la soberanía de datos.
- **Análisis de Datos:** Procesamiento de datos estructurados (.csv, .xlsx) y documentación técnica no estructurada (.pdf).
- **Entornos Web:** Hosting y despliegue del prototipo a través de **Netlify**.
- **Gestión Académica:** Integración con plataformas LMS.

## Instrucciones de Uso
El acceso al prototipo es totalmente web y no requiere instalaciones locales:
1. Navegue al enlace del prototipo proporcionado en la sección siguiente.
2. Explore la propuesta de valor presentada en la *landing page*.
3. Interactúe con las secciones del ecosistema para comprender la ruta de aprendizaje.
4. Revise el planteamiento pedagógico y la funcionalidad proyectada del tutor inteligente.

## Prototipo en Producción
El prototipo funcional y la documentación visual del proyecto se encuentran disponibles en el siguiente enlace:
🔗 [ExcelQuest en Producción](https://69f2a2f94dc1be5301e6f708--excelquest.netlify.app/)

## Capturas de Pantalla
### Vista Principal (Landing Page)
![ExcelQuest Landing Page](https://via.placeholder.com/800x450.png?text=ExcelQuest+Landing+Page+Mockup)
*Interfaz principal que presenta el ecosistema de aprendizaje.*

### Tutor Inteligente (Interfaz de Chat)
![Tutor Inteligente UI](https://via.placeholder.com/800x450.png?text=Tutor+Inteligente+Interface)
*Detalle del asistente pedagógico basado en IA proporcionando retroalimentación en tiempo real.*

## Integrantes
- **Rodolfo Colomo Mena**
- **Lucia Marion Araceli Gonzales Berrios**
- **Roberto Carlos Mamani Mayta**
- **Nelson Condori Pacasa**
- **Abad Gerardo Bustamante Chuquimia**

## Consideraciones Éticas
El proyecto se rige por un marco ético estricto para el uso de IA en contextos educativos:
- **Privacidad y Seguridad:** Preferencia por modelos de ejecución local para proteger la información sensible de los estudiantes.
- **Mitigación de Sesgos:** Diversificación de contenidos y ejemplos adaptados al contexto cultural boliviano, evitando estereotipos o exclusiones tecnológicas.
- **Transparencia y Explicabilidad:** El sistema prioriza el "paso a paso", permitiendo que el usuario comprenda el razonamiento detrás de cada solución de Excel.
- **Equidad Académica:** Orientación hacia el progreso individual sin etiquetas estigmatizantes, centrándose en la mejora continua.
- **Supervisión Docente:** La IA se posiciona como una herramienta de apoyo pedagógico (*Human-in-the-loop*), manteniendo al docente como la autoridad final en la toma de decisiones educativas.

---
*Este proyecto representa una integración sinérgica entre la inteligencia artificial y la pedagogía contemporánea para transformar el desarrollo de habilidades técnicas en la educación superior.*

