---
layout: page
title: AI, diseño de investigación e inferencia
---

# AI, diseño de investigación e inferencia

Las discusiones sobre AI en la academia tienden a concentrarse en el plagio o en la productividad. Esas discusiones son importantes, pero evaden la pregunta más interesante: ¿qué puede hacer el AI por el proceso de inferencia científica, y qué no puede hacer? Esta sección aborda esa pregunta tomando como punto de referencia los textos metodológicos del curso.

---

## La lógica de la inferencia científica

King, Keohane y Verba argumentan que la investigación en ciencias sociales — cualitativa o cuantitativa — se organiza alrededor de la misma lógica: el investigador observa una parte del mundo, construye una explicación, y evalúa esa explicación produciendo implicaciones observables que la evidencia podría refutar. Lo que distingue al conocimiento científico del opinático no es el método, sino la disposición a que los datos contradigan las hipótesis.

Los modelos de lenguaje no tienen esa disposición. Generan texto que maximiza la coherencia y la plausibilidad — lo que produce respuestas que suenan convincentes con independencia de si son verdaderas. Esa característica no los hace inútiles, pero define con precisión los límites de su utilidad: son buenos generando argumentos plausibles, no buenos evaluando si esos argumentos son correctos.

La implicación para el uso del AI en la investigación es directa. El AI puede ayudarte en las tareas que requieren generar opciones — posibles preguntas, posibles mecanismos, posibles diseños, posibles fuentes de datos. La evaluación de esas opciones — cuál pregunta es más interesante, cuál mecanismo es más creíble, cuál diseño es más válido — requiere criterio sustantivo que el AI no tiene.

---

## Causalidad y diseño

Dunning argumenta que la calidad de la inferencia causal depende fundamentalmente del diseño de investigación, no de la sofisticación del análisis estadístico posterior. Un diseño débil produce estimaciones sesgadas con independencia de cuántas variables de control se incluyan. Un diseño sólido — como un experimento natural que asigna el tratamiento de manera casi aleatoria — produce inferencias creíbles aunque el análisis sea relativamente simple.

El AI no puede identificar un experimento natural por vos. Reconocer que una reforma electoral, una lotería de títulos de propiedad o un umbral burocrático producen variación exógena en la variable de interés requiere conocimiento profundo del caso, intuición empírica, y familiaridad con la literatura sobre diseño. Eso es exactamente el tipo de juicio sustantivo que distingue a un investigador competente.

Lo que el AI sí puede hacer es ayudarte a pensar en las amenazas a la validez interna de un diseño que ya propusiste — confusores, selección, derrames, efectos de anticipación — y a buscar en la literatura diseños similares al tuyo. Esa contribución es genuina y puede ser valiosa, siempre que ya tengas claro lo que querés evaluar.

---

## Medición y validez

Grimmer, Roberts y Stewart advierten, en el contexto del análisis de texto automatizado, que la validez de la medición es una responsabilidad que no puede delegar el investigador. Cualquier herramienta — un clasificador de machine learning, un modelo de tópicos, o un LLM — produce medidas que deben validarse contra el fenómeno que se pretende capturar. Sin esa validación, el análisis estadístico no mide lo que dice medir.

El principio aplica con igual fuerza al uso de AI en la fase de diseño. Si le pedís al modelo que genere indicadores para medir "independencia judicial" y usás esos indicadores sin evaluar si capturan el concepto que te interesa, tu análisis tiene un problema de validez de constructo — con independencia de lo refinado que sea el resto del diseño.

La solución no es evitar el AI sino usarlo de manera adecuada: como generador de opciones de medición que vos evaluás contra la teoría y contra el conocimiento sustantivo del caso.

---

## ¿Puede el AI mejorar la ciencia social?

Bail (2024) plantea esa pregunta directamente y ofrece una respuesta matizada. Los modelos de lenguaje grandes pueden acelerar tareas de síntesis y organización, y en algunas aplicaciones específicas — como el análisis de texto a gran escala o la generación de ítems para encuestas — tienen potencial para expandir lo que los investigadores pueden hacer. Al mismo tiempo, Bail señala riesgos concretos: la homogeneización de ideas si los investigadores dependen de los mismos modelos, la dificultad de reproducir resultados que dependen de prompts específicos, y la tendencia de los modelos a confirmar los supuestos implícitos en las preguntas que se les hacen.

Ese último punto merece atención especial. Si le preguntás al AI "¿por qué la independencia judicial reduce la corrupción?", el modelo va a construir un argumento que justifica esa relación — porque la pregunta presupone que la relación existe. Si en cambio preguntás "¿bajo qué condiciones la independencia judicial no reduce la corrupción, y por qué?", obtenés un tipo de respuesta muy diferente. La calidad del razonamiento que el AI produce depende críticamente de la calidad de las preguntas que le hacés — lo que devuelve la responsabilidad intelectual al investigador.

---

## Síntesis: qué puede y qué no puede hacer el AI en la investigación científica

El AI puede:

- generar un mapa preliminar de debates en una literatura,
- sugerir posibles mecanismos causales para explorar,
- identificar amenazas potenciales a la validez interna de un diseño,
- proponer keywords para búsquedas bibliográficas,
- revisar la claridad y estructura de un argumento ya escrito,
- simular la crítica de un revisor o colega.

El AI no puede:

- evaluar si una pregunta de investigación es interesante o importante,
- decidir si un mecanismo es creíble dado el contexto histórico e institucional del caso,
- identificar la variación exógena que hace viable un diseño de inferencia causal,
- validar que una medida captura el concepto teórico que se pretende estudiar,
- reemplazar la lectura directa de la literatura relevante,
- tomar la responsabilidad intelectual del trabajo.

La distinción entre estas dos listas no es casual. Refleja la diferencia entre generar opciones plausibles y evaluar opciones con criterio — que es, en definitiva, lo que hace la investigación científica.
