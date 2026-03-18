# ✍️ Módulo 2 — Prompt Engineering Profesional

**Estado:** 🔄 En curso (2/6 lecciones completadas)  
**Fecha de inicio:** 17/03/2026  
**Duración estimada total:** ~14.5h

---

## 🎯 Objetivo del módulo

Dominar el Prompt Engineering desde zero-shot hasta meta-prompting y system prompts empresariales. La habilidad más rentable y la más rápida de monetizar. Primer servicio vendible.

---

## 📋 Tracker de lecciones

| Lección | Tema | Estado | Fecha | Nota |
|---------|------|--------|-------|------|
| 05 | Los 4 pilares de un prompt efectivo | ✅ | 17/03/2026 | 9, 9.5, 10/10 |
| 06 | Zero-shot, Few-shot y Role Prompting | ✅ | 17/03/2026 | 7.5, 9, 10/10 |
| 07 | Chain of Thought y Tree of Thought | ⏳ | — | — |
| 08 | System Prompts empresariales | ⏳ | — | — |
| 09 | Meta-prompting | ⏳ | — | — |
| 10 | Biblioteca de prompts en Notion/GitHub | ⏳ | — | — |

---

## 📝 Notas por lección

### Lección 05 — Los 4 Pilares de un Prompt Efectivo

**Concepto clave:** Todo prompt profesional se apoya en 4 pilares. Cuando un prompt falla, siempre es porque uno o más pilares está débil o ausente.

1. **Contexto** — Quién eres, para quién, en qué sector, qué sabe el destinatario
2. **Instrucción** — Verbo claro y específico (no "ayúdame con...")
3. **Formato** — Tabla, lista, JSON, email, plantilla, código...
4. **Restricción** — Límites: longitud, tono, lo que NO debe incluir, idioma

**Dato del mercado:** Las ofertas de prompt engineering en LinkedIn crecieron un 434% desde 2023. El mercado global pasará de 673M$ (2026) a 6.700M$ (2034).

**Fórmula combinada:** [CONTEXTO] + [INSTRUCCIÓN] + [FORMATO] + [RESTRICCIÓN] = prompt profesional

**Ejercicios realizados:**
- **Ejercicio 1 — Post LinkedIn** (9/10): Prompt con rol copywriter, contexto personal, estructura 5 bloques, objetivo psicológico.
- **Ejercicio 2 — Explicar ML** (9.5/10): Estructura de 6 puntos con "cuándo usarlo y cuándo NO" como iniciativa propia.
- **Ejercicio 3 — Ideas negocio IA** (10/10): Convertí la frase más vaga posible en prompt con criterios de filtrado y 8 puntos por idea.

→ Los 3 prompts completos están en [prompt-library-sprint1.md](./prompt-library-sprint1.md)

---

### Lección 06 — Zero-shot, Few-shot y Role Prompting

**Concepto clave:** 3 formas de instruir al modelo, como a un empleado nuevo:

1. **Zero-shot** — Solo instrucción, sin ejemplos. Funciona para tareas simples y bien definidas.
2. **Few-shot** — 2-5 ejemplos resueltos antes de la tarea. El modelo replica el patrón. Mejora la precisión un 30% vs zero-shot.
3. **Role Prompting** — Asignar identidad/rol al modelo. Cambia tono, vocabulario y enfoque.

**Regla clave:** La calidad de los ejemplos importa más que la cantidad. Rendimientos decrecientes a partir de 4-5 ejemplos. La consistencia de formato es lo que hace funcionar el few-shot.

**Fórmula profesional:** ROLE (quién eres) + FEW-SHOT (ejemplos) + 4 PILARES = prompt de nivel consultoría

**Cuándo usar cada técnica:**
- Zero-shot → tareas simples, traducciones, resúmenes, preguntas directas
- Few-shot → clasificaciones con criterio de negocio, tono específico, tareas ambiguas
- Role → siempre que el tipo de respuesta dependa de quién la da

**Ejercicio: 3 técnicas, 1 problema — Descripciones Google Business para taller mecánico:**
- **Versión A — Zero-shot** (7.5/10): Funcional pero genérico. El modelo adivina el estilo.
- **Versión B — Few-shot** (9/10): 2 ejemplos propios. El modelo replica el patrón. Entregable al cliente.
- **Versión C — Role + Few-shot + 4 pilares** (10/10): Versión completa profesional. Nivel agencia de marketing.

**Conclusión:** La diferencia de calidad entre zero-shot y role+few-shot es visible e inmediata.

→ Los 3 prompts completos están en [prompt-library-sprint1.md](./prompt-library-sprint1.md)

---

## 🔑 Mi patrón de prompting (firma personal)

Desarrollado a lo largo de las Lecciones 05 y 06:

1. **Rol experto definido** — Siempre asigno una identidad profesional al modelo
2. **Contexto personal real** — Mi situación, mi cliente, mi audiencia concreta
3. **Estructura numerada con propósito** — Cada bloque del prompt tiene una función
4. **Restricciones por negación** — Defino lo que NO quiero, no solo lo que quiero
5. **Objetivo psicológico al cierre** — Qué debe sentir o pensar quien lea el resultado

---

## 🔗 Recursos clave

- [LearnPrompting.org (ES)](https://learnprompting.org/es/docs/intro) — Curso gratuito
- [Prompting Guide (ES)](https://www.promptingguide.ai/es) — Referencia técnica gratuita
- [Guía oficial Anthropic](https://docs.anthropic.com/es/docs/build-with-claude/prompt-engineering/overview)
- [Alaimo Labs — De Zero-Shot a Meta Prompting](https://alaimolabs.com/es/articles/ai/de-zero-shot-a-meta-prompting) — Artículo gratuito
- [Marketing4ecommerce — Zero-shot, Few-shot y CoT](https://marketing4ecommerce.net/zero-shot-few-shot-y-chain-of-thought-prompting-ia/) — Artículo gratuito

---

## ✅ Entregable del Sprint 1

Biblioteca de prompts profesionales: [prompt-library-sprint1.md](./prompt-library-sprint1.md)  
6 prompts documentados con categoría, técnica, modelo recomendado y nota de evaluación.
