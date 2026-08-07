# Cómo contribuir

Gracias por querer mejorar esto. Hay tres formas de ayudar, ordenadas por lo útiles que son.

## 1. Reportar una pregunta discutible

La contribución más valiosa. Si una pregunta admite dos respuestas defendibles, está mal escrita y hay que arreglarla. [Abrí un issue](../../issues/new/choose) con el número de la pregunta, qué opción elegiste y por qué te parece que también es válida.

Lo mismo aplica a explicaciones flojas: si la clave dice *por qué* sin convencerte, decilo.

## 2. Corregir errores

Erratas, enlaces rotos, datos desactualizados del examen —precios, cantidad de preguntas, políticas—. Los datos oficiales cambian sin aviso; si detectás una diferencia con la guía vigente de Anthropic, avisá e incluí la fuente.

## 3. Traducir

El material está en español. Si querés llevarlo a portugués o a otro idioma, abrí un issue antes de empezar para coordinar.

## Lo que no se acepta

**Contenido del examen real.** No se aceptan preguntas, opciones ni escenarios que provengan de un examen rendido, ni parafraseados, ni "de memoria". Es una violación del acuerdo de confidencialidad que firma cada candidato y pone en riesgo la credencial de quien lo aporta. Cualquier contribución de ese tipo se rechaza y se borra.

Si aportás una pregunta nueva, tiene que ser **original tuya**, escrita contra los objetivos publicados del blueprint, con un escenario inventado.

## Cómo se escribe una buena pregunta

Si vas a proponer una, seguí las reglas que usa el banco:

- **Enunciado corto**, dos o tres líneas. Un escenario con una restricción clara.
- **Cuatro opciones** si es de una sola respuesta; **cinco opciones y dos correctas** si es de respuesta múltiple.
- **Opciones del mismo largo**, dentro de unos pocos caracteres entre sí. Si la correcta es la más larga, la pregunta se responde midiendo, no razonando.
- **Sin justificaciones adentro de la opción.** Nada de "…para que el modelo no pueda devolver lo que no puede recuperar". Eso delata la respuesta. La opción afirma; la explicación justifica.
- **Distractores plausibles**: cada uno debe fallar por un motivo identificable, no por ser absurdo.
- **Una explicación** que enuncie el principio, y una línea de por qué falla cada alternativa.

## Estructura del repositorio

Los archivos `examen.md` y `respuestas.md` se **generan** desde un banco de preguntas común: no los edites a mano, porque el cambio se pierde en la próxima generación. Abrí un issue y se corrige en el origen.

Las guías (`guia.md`) y el glosario sí se editan directamente.
