---
layout: page
title: Cómo escribir buenos prompts
---

La utilidad de una herramienta de IA depende casi enteramente de la calidad de las instrucciones que le das. Un prompt vago produce respuestas genéricas que no tienen en cuenta tu pregunta, tu diseño ni el contexto. 

---

## Los cuatro componentes de un prompt efectivo

Un buen prompt para tareas de investigación incluye, en general, cuatro elementos.

**Contexto:** quién sos y en qué etapa del proyecto estás. "Soy estudiante de ciencia política elaborando mi tesis de grado" es más útil que nada.

**Tarea:** qué querés que el modelo haga, con la mayor precisión posible. "Identificá amenazas a la validez interna" es más útil que "revisá mi diseño".

**Material:** el texto, la pregunta, el argumento o el párrafo sobre el que querés que trabaje. El modelo no puede ayudarte con algo que no leyó.

**Restricciones:** qué formato querés en la respuesta y qué querés que el modelo *no* haga. Si pedís críticas a un párrafo y no querés que lo reescriba, decilo explícitamente.

---

## Ejemplos comparados

Los siguientes ejemplos ilustran la diferencia entre un prompt débil y uno más efectivo para tareas habituales del seminario.

---

### Explorar un tema de tesis

**Prompt débil:**
```
Dame ideas para una tesis sobre corrupción.
```

**Prompt más efectivo:**
```
Soy estudiante de ciencia política en Argentina y estoy explorando posibles
temas para mi tesis de grado. Me interesa la corrupción judicial en América
Latina, pero todavía no tengo una pregunta precisa.

¿Podés ayudarme a identificar:
- las preguntas de investigación que los académicos trabajan en este campo,
- los principales debates teóricos,
- las estrategias empíricas más usadas?

No necesito una lista exhaustiva: quiero un mapa preliminar para orientar
mis búsquedas bibliográficas.
```

---

### Refinar una pregunta de investigación

**Prompt débil:**
```
¿Es buena mi pregunta de investigación?
```

**Prompt más efectivo:**
```
Mi pregunta de investigación tentativa es:
"¿Por qué algunos países de América Latina han avanzado más que otros
en la profesionalización de su servicio civil?"

¿Podés evaluar si esta pregunta es suficientemente precisa y empíricamente
testeable? En particular:
- ¿qué conceptos necesitan definición más precisa?
- ¿es una pregunta causal o descriptiva?
- ¿qué diseños de investigación podría usar para responderla?
```

---

### Revisar un párrafo

**Prompt débil:**
```
Mejorá este párrafo.
```

**Prompt más efectivo:**
```
Aquí está el párrafo de introducción de mi sección teórica:

[pegar párrafo]

Por favor, identificá:
- afirmaciones que no están suficientemente justificadas,
- conceptos que no están definidos con precisión,
- saltos lógicos en el argumento.

No reescribas el párrafo. Solo señalá los problemas con referencias a
oraciones específicas.
```

---

### Identificar explicaciones alternativas

**Prompt débil:**
```
¿Cuáles son las críticas a mi argumento?
```

**Prompt más efectivo:**
```
Mi argumento es que los gobiernos de izquierda en América Latina
tienen más dificultades para formalizar el mercado de trabajo porque
dependen electoralmente de los trabajadores informales.

¿Podés sugerir:
- explicaciones alternativas que también podrían producir el mismo patrón
  (mayor informalidad bajo gobiernos de izquierda),
- qué implicaciones observables distinguirían mi argumento de cada alternativa?
```

---
