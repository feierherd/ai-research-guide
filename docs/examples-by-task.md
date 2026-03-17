---
layout: page
title: Ejemplos de uso de AI por tarea
---

Los siguientes ejemplos están construidos a partir de proyectos pasados del seminario de trabajo de graduación en ciencia política y relaciones internacionales. Para cada tarea se muestra un contexto realista, el prompt que un estudiante podría usar y una nota sobre qué hacer — y qué no hacer — con la respuesta.

---

## Tarea 1 — Mapear una literatura nueva

**Contexto:** Una estudiante quiere escribir su tesis sobre autoritarismo subnacional en Argentina. Conoce el tema por sus cursos pero no ha leído la literatura especializada. Antes de ir a Google Scholar, quiere tener un mapa preliminar del campo.

**Prompt:**

```
Estoy comenzando una tesis sobre autoritarismo subnacional en Argentina.
Sé que hay literatura sobre regímenes híbridos en las provincias, pero
no conozco bien el campo.

¿Podés ayudarme a identificar:
- los debates teóricos principales en esta literatura (por ejemplo:
  cómo se define el autoritarismo subnacional, qué lo explica),
- algunos autores que se citen frecuentemente,
- las estrategias empíricas que los investigadores usan para estudiar
  estos casos?

No necesito una revisión completa: quiero un mapa para orientar mis
búsquedas en Google Scholar.
```

**Qué hacer con la respuesta:** El modelo probablemente mencione autores como Gibson, Gervasoni o Giraudy, y debates sobre regímenes rentistas, *boundary control* y cooptación de las instituciones. Usá esos nombres como punto de partida para buscar sus artículos reales. No aceptes como válido ningún trabajo que no hayas verificado en una base de datos académica — incluso si el autor existe, el título puede ser incorrecto.

---

## Tarea 2 — Generar keywords para búsquedas bibliográficas

**Contexto:** Un estudiante quiere estudiar cómo la regulación de la inteligencia artificial se convirtió en un tema de agenda en la Unión Europea. No sabe exactamente cómo se denomina este proceso en la literatura de políticas públicas en inglés.

**Prompt:**

```
Estoy preparando una tesis sobre la regulación de la inteligencia artificial
como problema de agenda en la Unión Europea. Quiero buscar artículos en
Google Scholar y Web of Science, pero no sé qué términos usa la literatura
especializada en inglés.

¿Podés sugerirme:
- los términos técnicos más usados para este tema (tanto en la literatura
  de políticas públicas como en la de gobernanza tecnológica),
- posibles combinaciones de búsqueda útiles,
- autores o marcos teóricos que aparecen con frecuencia en este campo,
  como el Multiple Streams Framework u otros?
```

**Qué hacer con la respuesta:** El modelo probablemente sugiera términos como *agenda-setting*, *AI governance*, *regulatory frameworks*, *policy entrepreneurs*, y mencione a Kingdon o Baumgartner. Llevá esos términos a las bases de datos, verificá cuáles producen resultados relevantes y ajustá las búsquedas según lo que encuentres.

---

## Tarea 3 — Refinar una pregunta de investigación

**Contexto:** Dos estudiantes trabajan juntas en un proyecto sobre competencia política en provincias argentinas con partido dominante. Tienen una intuición clara sobre el tema pero la pregunta todavía es demasiado amplia.

**Pregunta original:** "¿Hay competencia política en las provincias argentinas donde siempre gana el mismo partido?"

**Prompt:**

```
Estamos trabajando en una tesis sobre competencia política en provincias
argentinas con partido dominante. Nuestra pregunta tentativa es:

"¿Hay competencia política en las provincias argentinas donde siempre
gana el mismo partido?"

¿Podés ayudarnos a:
- identificar qué está impreciso en esta pregunta (qué conceptos necesitan
  definición más clara, qué delimita mal el fenómeno),
- reformularla de manera más precisa y empíricamente contestable,
- distinguir si es una pregunta descriptiva o causal?
```

**Qué hace la IA bien:** El modelo debería señalar que "competencia política" necesita operacionalización (¿a qué nivel institucional — ejecutivo, legislativo, municipal?), que "siempre gana el mismo partido" requiere un umbral temporal y una definición de dominancia. También debería indicar que la pregunta original es más descriptiva que causal. Esas observaciones son genuinamente útiles.

**Límite importante:** El modelo no puede decirte si la pregunta *vale la pena hacerse* o si está bien posicionada en la literatura. Esa evaluación requiere leer los trabajos de Gervasoni, Gibson y Giraudy directamente.

---

## Tarea 4 — Articular un mecanismo causal

**Contexto:** Un estudiante estudia por qué algunos gobernadores permiten competencia política interna a nivel municipal y legislativo mientras otros no. Tiene una intuición sobre el mecanismo pero le cuesta articularla con precisión.

**Intuición del estudiante:** "Los gobernadores permiten competencia cuando tienen miedo de que el gobierno nacional los intervenga."

**Prompt:**

```
Estoy desarrollando el argumento de mi tesis. Mi intuición es que los
gobernadores de provincias con partido dominante permiten competencia
política interna (a nivel municipal y legislativo) cuando perciben que
el riesgo de intervención federal es alto.

¿Podés ayudarme a:
- articular este mecanismo con mayor precisión teórica,
- identificar qué supuestos requiere (sobre el comportamiento de los
  gobernadores, los incentivos del gobierno nacional, etc.),
- derivar al menos dos implicaciones observables que podría usar para
  evaluar si el mecanismo está operando?
```

**Qué hacer con la respuesta:** El modelo puede ayudar a formalizar el argumento en términos de incentivos y costos estratégicos, y a pensar en implicaciones observables (por ejemplo: "si el mecanismo opera, deberíamos ver mayor competencia interna en años en que hay tensión entre el gobernador y el ejecutivo nacional"). Verificá que esas implicaciones sean consistentes con la literatura que ya leíste sobre federalismo y política provincial.

---

## Tarea 5 — Identificar explicaciones alternativas

**Contexto:** Una estudiante estudia la efectividad de la Operación Althea de la Unión Europea en Bosnia y Herzegovina. Su argumento es que la misión es efectiva en el corto plazo pero no logra generar sostenibilidad institucional porque no resuelve las tensiones étnicas subyacentes del Acuerdo de Dayton.

**Prompt:**

```
Mi argumento es que la Operación Althea (UE) en Bosnia y Herzegovina
es efectiva para mantener la estabilidad inmediata, pero no logra
generar paz sostenible porque el diseño institucional del Acuerdo de
Dayton perpetúa las divisiones étnicas que generan el conflicto.

¿Podés sugerir explicaciones alternativas que también producirían el
patrón que observo — efectividad de corto plazo sin sostenibilidad
a largo plazo?

Para cada alternativa, ¿qué implicaciones observables la distinguirían
de mi argumento?
```

**Por qué es útil este prompt:** Las explicaciones alternativas son exactamente lo que un revisor o un jurado de tesis va a plantear. Anticiparlas antes de presentar el argumento es una práctica central del diseño de investigación riguroso. La IA puede sugerir alternativas como capacidades institucionales locales insuficientes, falta de voluntad política de los actores locales, o dependencia de recursos externos.

---

## Tarea 6 — Evaluar un diseño de investigación

**Contexto:** Una estudiante propone estudiar las condiciones bajo las cuales los Estados regulan la inteligencia artificial usando process tracing sobre el AI Act de la Unión Europea.

**Prompt:**

```
Mi diseño propone estudiar las condiciones bajo las cuales los Estados
buscan regular la inteligencia artificial. Para eso, uso process tracing
sobre la formulación del AI Act de la Unión Europea, aplicando el
Multiple Streams Framework de Kingdon.

¿Podés evaluar este diseño identificando:
- qué puede establecer el process tracing en un solo caso y qué no puede,
- qué riesgos existen al usar un único caso para hacer inferencias
  sobre "los Estados" en general,
- qué amenazas hay a la validez de la aplicación del MSF a este caso,
- qué podría fortalecerse en el diseño?
```

**Qué hace el AI bien aquí:** El modelo debería señalar la tensión entre el alcance de la pregunta ("los Estados") y el diseño de caso único, la importancia de especificar qué tipo de inferencia hace el process tracing (causal vs. descriptiva) y posibles alternativas como la selección de un caso de control. Esas observaciones son válidas y pueden usarse para ajustar el argumento sobre los alcances del trabajo. Sin embargo, la decisión sobre si el diseño es aceptable dado el alcance de una tesis de grado es una conversación que tenés que tener con tu mentor y con el profesor del seminario, no con la IA.

---

## Tarea 7 — Revisar un párrafo

**Contexto:** Una estudiante escribió el párrafo de introducción de su sección de argumento. Quiere recibir críticas sobre su lógica antes de mostrárselo al docente.

**Párrafo:**

> "En las provincias con partido dominante existe poca competencia política porque los gobernadores utilizan los recursos del Estado para cooptar a la oposición. Esto genera un círculo vicioso donde la oposición no puede competir efectivamente, lo que a su vez refuerza el poder del partido dominante. Sin embargo, a nivel municipal y legislativo existe mayor pluralismo, lo que sugiere que la competencia no está completamente ausente."

**Prompt:**

```
Aquí está el párrafo de introducción de mi sección de argumento:

"En las provincias con partido dominante existe poca competencia política
porque los gobernadores utilizan los recursos del Estado para cooptar a
la oposición. Esto genera un círculo vicioso donde la oposición no puede
competir efectivamente, lo que a su vez refuerza el poder del partido
dominante. Sin embargo, a nivel municipal y legislativo existe mayor
pluralismo, lo que sugiere que la competencia no está completamente
ausente."

¿Podés identificar:
- afirmaciones que necesitan respaldo empírico o teórico,
- saltos lógicos en el argumento,
- conceptos que no están definidos con suficiente precisión?

No reescribas el párrafo. Solo señalá los problemas con referencias
a oraciones específicas.
```

**Qué hace la IA bien:** El modelo probablemente señale que "cooptar a la oposición" es un mecanismo que requiere evidencia, que "círculo vicioso" es una afirmación de equilibrio que no está del todo desarrollada y que la última oración introduce una observación que parece contradecir la primera sin explicar la relación entre ambas. Esas son críticas útiles. La estudiante puede entonces revisar el párrafo con sus propias palabras, no con las del modelo.

---

## Una nota sobre todos estos ejemplos

En cada caso, la IA produce material útil para pensar — no conclusiones para copiar. La diferencia entre usar la IA como herramienta para pensar y usarlo como atajo se hace evidente exactamente en el momento en que tenés que defender tu trabajo oralmente: si el argumento es tuyo, podés defenderlo; si lo generó el modelo, no.
