---
layout: page
title: El flujo de trabajo de la tesis con IA
---

# El flujo de trabajo de la tesis con la IA

La elaboración de una tesis en ciencias sociales sigue una lógica que King, Keohane y Verba describen con precisión: el investigador parte de un fenómeno observable, construye una explicación y diseña una estrategia para evaluar esa explicación con evidencia. Esa lógica no cambia porque existan herramientas de IA. Lo que cambia es la velocidad y el costo de algunas tareas auxiliares — explorar un campo de literatura, ordenar ideas, revisar un borrador — que antes consumían tiempo desproporcionado respecto de su valor intelectual.

Esta sección mapea el proceso de elaboración del proyecto de graduación sobre las etapas en que la IA puede contribuir de manera genuina, y señala dónde la herramienta llega a su límite.

---

## Etapa 1 — Identificar un interés de investigación

La mayoría de los proyectos de tesis comienzan con un interés amplio y poco definido: "me interesa la corrupción", "quiero estudiar la justicia", "me pregunto por qué los sindicatos pierden poder". Esa indeterminación es normal al principio, pero necesita resolverse rápido. La IA puede ayudar a ese proceso de clarificación.

Un buen punto de partida es pedirle al modelo que te ayude a identificar qué preguntas de investigación estudian los académicos en el área que te interesa, qué debates existen en la literatura y qué estrategias empíricas se usan con frecuencia. El objetivo no es obtener una respuesta definitiva — es generar un mapa preliminar que oriente ***tus*** búsquedas en bases de datos académicas.

**Prompt de ejemplo:**

```
Soy estudiante de ciencia política y estoy explorando posibles temas para mi
tesis. Me interesa la relación entre el poder judicial y la corrupción en
América Latina.

¿Podés ayudarme a identificar:
- las preguntas de investigación más importantes en esta literatura,
- los debates teóricos principales,
- las estrategias empíricas que los investigadores usan habitualmente?
```

Lo que la IA genera en respuesta a este prompt es un punto de partida, no una revisión de literatura. Tratalo como una lista de hipótesis que vas a verificar buscando los trabajos reales.

---

## Etapa 2 — Explorar la literatura

Una vez identificado el tema, el paso siguiente es construir un mapa de la literatura relevante. La IA puede sugerir autores, debates y palabras clave — pero con una advertencia importante: los modelos de lenguaje tienen fecha de corte, pueden confundir autores con títulos y en ocasiones (aunque cada vez menos) generan referencias que no existen. El criterio de Grimmer, Roberts y Stewart sobre análisis de texto automatizado aplica acá con igual fuerza: la validez de la medición — en este caso, si la literatura que identificás es realmente relevante para tu pregunta — es una decisión que no podés delegar en la IA.

Para una guía detallada sobre cómo usar lsa IA en esta etapa — incluyendo cómo generar keywords, organizar la literatura y verificar fuentes — ver [Cómo explorar literatura con AI](using-ai-for-literature.md).

---

## Etapa 3 — Formular la pregunta de investigación

Una buena pregunta de investigación es empíricamente contestable, teóricamente interesante y factible dado el tiempo y los recursos disponibles. Llegar a esa pregunta es uno de los trabajos intelectuales más difíciles de la tesis, y la IA puede ser útil como interlocutor en ese proceso — no para decidir qué pregunta hacerse, sino para ayudarte a ver si la que ya tenés es suficientemente precisa.

**Prompt de ejemplo:**

```
Mi pregunta tentativa es: "¿Los fiscales investigan más a los políticos de la
oposición que a los del gobierno?"

¿Podés ayudarme a:
- identificar si es una pregunta descriptiva o causal,
- hacerla más precisa y empíricamente testeable,
- señalar ambigüedades en los conceptos centrales?
```

---

## Etapa 4 — Desarrollar el argumento

Una vez definida la pregunta, hay que construir un argumento: una explicación sobre por qué el fenómeno ocurre, que especifique el mecanismo causal y produzca implicaciones observables. La IA puede ayudarte a pensar en posibles mecanismos, pero su utilidad depende de que vos ya tengas una intuición sobre qué fuerzas están en juego.

El uso más productivo en esta etapa es pedirle al modelo que identifique explicaciones alternativas al mecanismo que estás proponiendo. Eso es exactamente lo que exige el diseño de investigación riguroso: antes de presentar tu argumento, tenés que haber considerado qué otras explicaciones producirían el mismo patrón observado.

**Prompt de ejemplo:**

```
Mi argumento es que los fiscales investigan más a los políticos de la oposición
porque tienen menos restricciones políticas para hacerlo que cuando el gobierno
es el acusado.

¿Podés sugerir explicaciones alternativas que también podrían producir ese
mismo patrón empírico? ¿Qué implicaciones observables diferenciarían mi
argumento de esas alternativas?
```

---

## Etapa 5 — Diseñar la investigación

El diseño de investigación es el corazón metodológico de la tesis. Determina qué evidencia es relevante, cómo vas a recolectarla y qué inferencias podés extraer. Dunning (2012) argumenta que la calidad de la inferencia depende del diseño, no del tamaño de la muestra ni de la sofisticación estadística. La IA no puede diseñar tu investigación — pero puede ayudarte a pensar en las fortalezas y debilidades de distintas estrategias.

Una aplicación particularmente útil es pedirle al modelo que identifique amenazas a la inferencia causal en el diseño que estás proponiendo. Los textos de Green y Gerber sobre la sub-provisión de experimentos, o los capítulos de Dunning sobre experimentos naturales, te pueden ayudar a identificar esas posibles amenazas.

**Prompt de ejemplo:**

```
Mi diseño propone comparar el número de investigaciones judiciales contra
políticos oficialistas y opositores en Argentina entre 2003 y 2015,
usando datos del Poder Judicial de la Nación.

¿Podés identificar:
- posibles fuentes de sesgo de selección en este diseño,
- amenazas a la inferencia causal,
- estrategias que podrían mitigar esos problemas?
```

---

## Etapa 6 — Identificar y recolectar datos

**En esta etapa, la IA puede ayudarte a pensar en qué tipos de datos existen para estudiar tu pregunta y dónde podrían encontrarse. La decisión sobre qué datos recolectar y cómo construir las variables, en cambio, requiere conocimiento sustantivo del caso que el AI no tiene.**

El criterio que el programa del seminario plantea para la entrega intermedia aplica directamente aquí: antes de seguir avanzando, tenés que poder responder con precisión qué datos concretos vas a usar, si tenés acceso a ellos y qué resultado empírico confirmaría o refutaría tu argumento. Si no podés responder esas tres preguntas, el diseño está incompleto.

**Prompt de ejemplo:**

```
Quiero estudiar el comportamiento de los fiscales federales en Argentina.
¿Qué tipos de datos podrían usarse para estudiar este tema?

Por ejemplo:
- registros administrativos del sistema judicial,
- cobertura mediática de casos,
- bases de datos de cargos públicos,
- declaraciones juradas.

¿Cuáles serían los dersafios de medición más frecuentes en cada tipo?
```

---

## Etapa 7 — Escribir y revisar

La IA es más útil en la escritura como revisor de claridad, no como redactor. Si le pasás un párrafo que ya escribiste y le pedís que identifique problemas de estructura o argumento, el resultado suele ser útil. Si le pedís que escriba el párrafo por vos, el resultado tiende a ser genérico, excesivamente fluido, y carente de la especificidad que requiere un trabajo académico.

La regla práctica es sencilla: el AI puede sugerirte cómo decir mejor algo que ya entendés. No puede entender algo por vos y después explicarlo.

**Prompt de ejemplo:**

```
Aquí está el párrafo de introducción de mi sección de diseño de investigación:

[pegar párrafo]

¿Podés identificar:
- afirmaciones que no están suficientemente justificadas,
- términos que no están definidos con precisión,
- saltos lógicos en el argumento?

No reescribas el párrafo: solo señalá los problemas.
```

---

## Una regla simple

El AI puede ayudarte a pensar. No puede pensar por vos. La responsabilidad intelectual del trabajo — la pregunta que elegiste, el argumento que construiste, el diseño que propusiste, la evidencia que analizaste — es tuya.
