<!-- Generado desde el banco de preguntas. No editar a mano: abrí un issue. -->
# CCAR-P · Clave de respuestas

> Cada respuesta trae el principio que la sostiene y por qué fallan las otras. El razonamiento importa más que la letra: en el examen real el escenario será distinto, el principio es el mismo.

---

### 1

**Correcta: A y C**

El caché coincide por prefijo: se reutiliza desde el primer carácter hasta el primer cambio. Todo lo variable va después de lo estable, y el orden de las definiciones de herramientas es parte de ese prefijo.

*Por qué no las otras:* B reduce tokens pero no cambia la tasa de aciertos; D es salida, no prefijo; E no interviene en la coincidencia.

---

### 2

**Correcta: A**

Un revisor anclado al razonamiento que generó el código hereda sus puntos ciegos. Por eso la revisión se hace desde contexto fresco, separado de la sesión que escribió.

*Por qué no las otras:* B y C son ajustes de configuración que no tocan el anclaje; D sería un problema de proceso visible en los tiempos.

---

### 3

**Correcta: A**

Diagnosticar antes de intervenir. Las trazas muestran si el desvío nace en la entrada, en lo recuperado, en la descripción de la herramienta o en el prompt.

*Por qué no las otras:* B adivina la causa; C y D son intervenciones grandes sin evidencia de que apunten al problema.

---

### 4

**Correcta: A**

La configuración compartida y versionada es el mecanismo de incorporación: la persona hereda la práctica probada el primer día, sin depender de que alguien se la explique.

*Por qué no las otras:* B enseña técnica sin darle el contexto del equipo; C posterga la productividad; D reproduce la fragmentación.

---

### 5

**Correcta: B y C**

La autonomía se justifica cuando el camino no se puede enumerar de antemano. Que las intervenciones no sigan un patrón listable y que los pasos aparezcan a mitad del proceso son exactamente esa condición.

*Por qué no las otras:* A y E son escala y costo: se resuelven dentro de cualquier patrón; D es prestigio, no un driver arquitectónico.

---

### 6

**Correcta: A y C**

El supervisor aporta secuenciación y un punto único donde queda registrado el orden de las decisiones. Eso es justamente lo que un esquema peer-to-peer no puede garantizar.

*Por qué no las otras:* B es trabajo del especialista; D es interno de cada agente; E es una decisión de configuración fijada de antemano, no de orquestación en ejecución.

---

### 7

**Correcta: A y B**

Descomponer sirve por dos motivos: cada paso recibe atención enfocada y cada salida intermedia se puede verificar. Sin salida estructurada entre pasos, la cadena vuelve a ser una caja negra.

*Por qué no las otras:* C confunde capacidad con estructura; D deja el prompt gigante intacto; E deshace la descomposición.

---

### 8

**Correcta: A y C**

Los pilares de valor son eficiencia, productividad, costo, transformación y cumplimiento de SLA. Horas liberadas y mejora contra un SLA contractual son medibles y le importan a quien paga.

*Por qué no las otras:* B, D y E son métricas de la construcción, no del resultado; ninguna cambia una decisión de inversión.

---

### 9

**Correcta: A y C**

Una sola llamada aumentada alcanza cuando hay una transformación y el contexto necesario cabe al lado del pedido. Es el escalón más bajo de la escalera y se elige siempre que cumpla.

*Por qué no las otras:* B pide multi-agente; D pide un agente; E pide un workflow con pasos discretos.

---

### 10

**Correcta: A**

El cuarto tramo de una arquitectura end-to-end es el feedback: las correcciones y señales de producción vuelven convertidas en datos evaluables. Sin eso no hay forma de saber si la calidad se mueve.

*Por qué no las otras:* B baja costo; C agrega revisión pero sigue sin medir nada en el tiempo; D vuelve a medir la máquina, no el acierto.

---

### 11

| # | Correcta |
|---|---|
| 1 | the architect, at design time |
| 2 | the model, at run time |
| 3 | a human reviewer, per case |
| 4 | the architect, at design time |
| 5 | the model, at run time |

Lo predecible lo fija una persona en diseño; lo que depende de lo que va apareciendo lo decide el modelo en ejecución; lo irreversible o de alto impacto lo decide un humano caso por caso.

---

### 12

**Correcta: A**

Cuando hay categorías de entrada claramente distintas, clasificar primero y derivar permite atender lo simple barato y rápido, y reservar el análisis profundo para lo que lo necesita.

*Por qué no las otras:* B paga el costo del caso complejo en cada consulta trivial; C mezcla dos tareas en un prompt; D parte la experiencia del usuario sin necesidad.

---

### 13

**Correcta: A**

Validar entre pasos es lo que convierte una cadena en algo depurable: el error se detecta donde nace y no contamina lo que sigue. Es la razón principal para descomponer.

*Por qué no las otras:* B detecta cuando ya se arrastró; C no cubre lo que el proceso genera; D confía la garantía a una instrucción.

---

### 14

**Correcta: A y B**

El diseño multi-agente se gana cuando las sub-tareas piden especializaciones y herramientas distintas, y cuando son independientes y pueden correr en paralelo.

*Por qué no las otras:* C es presupuesto; D es prestigio; E es escala, resoluble dentro de cualquier patrón.

---

### 15

| # | Correcta |
|---|---|
| 1 | single augmented call |
| 2 | fixed workflow |
| 3 | autonomous agent |
| 4 | multi-agent system |
| 5 | single augmented call |

Una transformación con su contexto al lado es una llamada aumentada. Una secuencia estable que se repite es un workflow. Un camino que se descubre paso a paso es un agente. Especialidades distintas coordinadas en una salida es multi-agente.

---

### 16

**Correcta: A y B**

Dos palancas reales: prioridad explícita ante conflicto, y posición fuera del medio del contexto, separada estructuralmente de la referencia.

*Por qué no las otras:* C es superstición; D infla y diluye; E es una suposición, no una práctica.

---

### 17

**Correcta: A y C**

Se recorta lo que no aporta y se deja de pagar dos veces por lo que se repite. Recuperación más precisa y prefijo cacheado bajan el costo sin tocar la calidad.

*Por qué no las otras:* B saca trazabilidad; D sacrifica calidad a ciegas; E corta el contenido en el medio de la idea.

---

### 18

**Correcta: B y D**

El razonamiento paso a paso rinde donde hay pasos encadenados y criterios que se cruzan. Comparar una cláusula contra varias políticas y ponderar señales contradictorias son exactamente eso.

*Por qué no las otras:* A, C y E son transformaciones directas: el razonamiento explícito solo agrega costo y latencia.

---

### 19

**Correcta: A**

Con calidad equivalente medida, se elige el modelo más chico que alcanza el umbral y se sostiene la evaluación para confirmar que lo sigue alcanzando.

*Por qué no las otras:* B ignora la medición que ya existe; C hace el comportamiento impredecible sin evaluar; D baja de escalón sin evidencia de que ese modelo cumpla.

---

### 20

| # | Correcta |
|---|---|
| 1 | few-shot examples |
| 2 | move the rule to an edge |
| 3 | prompt caching |
| 4 | retrieve only what is relevant |
| 5 | few-shot examples |

Formato inconsistente se arregla mostrando, no describiendo. Una regla que se pierde es un problema de posición. Contenido idéntico repetido es caché. Un documento grande con respuestas flojas en el medio y caras es recuperación selectiva.

---

### 21

**Correcta: A**

Los ejemplos cuestan tokens en cada pedido. Si las definiciones ya alcanzan y la precisión es alta, agregarlos paga costo sin comprar nada. Cada técnica se aplica según beneficio medido.

*Por qué no las otras:* B es una regla absoluta que no se sostiene; C infla el prompt sin evidencia; D gasta capacidad donde no hay problema.

---

### 22

**Correcta: A**

Resumir lo viejo y conservar textual lo que decide —identificadores, importes, compromisos— combina las dos cosas: cabe en la ventana y no se pierde el dato que rompe la respuesta si falta.

*Por qué no las otras:* B descarta información sin criterio; C corre el problema unos turnos; D tira el hilo de la conversación.

---

### 23

**Correcta: A y B**

Privilegio mínimo más compuerta antes de la acción irreversible. Una limita lo que puede alcanzar, la otra exige intervención humana antes de ejecutar.

*Por qué no las otras:* C y E son sugerencias de texto, no controles; D es detección posterior al borrado.

---

### 24

**Correcta: A y B**

MCP paga cuando hay varios consumidores y el catálogo cambia seguido: el equipo mantiene su servidor una vez y todos lo reusan.

*Por qué no las otras:* C, D y E describen un consumidor único y estable, que es el caso de la integración directa.

---

### 25

**Correcta: A y B**

Sin identificador de correlación no se puede reconstruir una sesión, y sin el contexto recuperado y las llamadas a herramientas no se ve dónde se rompió.

*Por qué no las otras:* C es presentación; D es justamente lo que no escala y se hace por muestreo; E es metadato de despliegue.

---

### 26

**Correcta: A y B**

Traer material relacionado pero inútil es un problema de qué se recupera y en qué orden. Re-ranking corrige el orden; el corte por idea completa corrige la unidad recuperada.

*Por qué no las otras:* C inunda el contexto; D no cambia lo recuperado; E descarta la búsqueda semántica que sí funciona.

---

### 27

**Correcta: A y B**

Cuando la visibilidad difiere por usuario y existe una vía para manipular al modelo, la única frontera confiable es que la credencial no alcance lo que ese usuario no puede ver.

*Por qué no las otras:* C, D y E describen escenarios donde no hay separación que proteger.

---

### 28

**Correcta: A y B**

El chunking se delata cuando el pedazo recuperado no contiene la unidad de sentido completa: falta la excepción que estaba al lado, o el fragmento arranca y termina en el aire.

*Por qué no las otras:* C es variabilidad de muestreo; D es escala del índice; E es comportamiento correcto.

---

### 29

**Correcta: A**

Las herramientas se diseñan orientadas a la tarea, no como espejo de la API interna, y solo se presentan las relevantes a cada pedido. La complejidad queda del lado del sistema, donde es determinística.

*Por qué no las otras:* B compra capacidad sin reducir la confusión; C agrega latencia a cada llamada; D descarta las interfaces tipadas y hace los errores más difíciles de detectar.

---

### 30

| # | Correcta |
|---|---|
| 1 | chunking |
| 2 | indexing |
| 3 | search strategy |
| 4 | access control |
| 5 | chunking |

El corte define la unidad de sentido; el indexado define qué versión existe; la estrategia de búsqueda define cómo se encuentra; el control de acceso define quién puede verlo. Cada síntoma apunta a una sola de las cuatro.

---

### 31

**Correcta: A**

El aislamiento entre inquilinos se resuelve en la consulta, no en el prompt: si el filtro por metadato no devuelve el documento, el modelo no puede citarlo aunque quiera.

*Por qué no las otras:* B y D dejan la separación en manos de una instrucción; C confía en que la relevancia haga de control de acceso.

---

### 32

**Correcta: A**

Frescura en minutos pide indexado incremental disparado por el cambio, y una reconstrucción completa periódica que corrige la deriva acumulada. Las dos piezas juntas.

*Por qué no las otras:* B llega con horas de retraso; C empeora deliberadamente la frescura; D pierde la búsqueda semántica.

---

### 33

**Correcta: A y B**

La selección falla por solape y ambigüedad: se hace explícito el límite de cada herramienta y se eliminan los solapes de raíz.

*Por qué no las otras:* C institucionaliza una preferencia arbitraria; D agranda la superficie de confusión; E multiplica llamadas y costo.

---

### 34

| # | Correcta |
|---|---|
| 1 | MCP server |
| 2 | direct API integration |
| 3 | agent-to-agent protocol |
| 4 | MCP server |
| 5 | direct API integration |

Muchos consumidores presentes y futuros sobre el mismo sistema piden MCP. Llamadas determinísticas dentro de un pipeline propio piden integración directa. Cruzar la frontera de otra organización pide agente a agente.

---

### 35

**Correcta: A y B**

La evaluación en producción vive de dos fuentes: una muestra puntuada con criterio estable y las correcciones reales que hacen los usuarios aguas abajo.

*Por qué no las otras:* C mide siempre la misma distribución vieja; D es anécdota; E es proxy débil y ambiguo.

---

### 36

**Correcta: A y B**

Se saca trabajo que no aporta: el prefijo repetido se reutiliza y el razonamiento explícito se retira de donde no cambia el resultado.

*Por qué no las otras:* C acelera el proceso de release, no el producto; D y E recortan capacidad y sí cuestan calidad.

---

### 37

**Correcta: A y B**

Drift es que cambió lo que entra: un idioma nuevo o consultas notablemente distintas en forma son evidencia directa de que la distribución se movió bajo un sistema que no se tocó.

*Por qué no las otras:* C es consecuencia del volumen; D descarta un problema de infraestructura pero no explica calidad; E es crecimiento, no cambio de forma.

---

### 38

**Correcta: A y B**

Un juez sirve si aplica el mismo criterio que los humanos y si alguien verifica cada tanto que no se corrió. Rúbrica derivada de la guía real, más calibración periódica.

*Por qué no las otras:* C introduce sesgo del mismo autor; D deja al juez definir su propia vara; E sesga la muestra a los casos dudosos.

---

### 39

**Correcta: A y B**

Se amplía cuando la calidad de la tarea se sostiene y los controles de seguridad no se degradan. Esas son las dos dimensiones que un canary existe para vigilar.

*Por qué no las otras:* C es proceso; D es un beneficio, no una condición de seguridad; E es un parámetro del propio canary.

---

### 40

**Correcta: A**

La pregunta es cuál de las dos versiones es mejor con tráfico real, y eso lo contesta una comparación simultánea. El canary responde otra pregunta: si la versión nueva rompe algo.

*Por qué no las otras:* C vuelve a medir la misma distribución offline; D es muestreo de opiniones.

---

### 41

| # | Correcta |
|---|---|
| 1 | leading indicator of quality |
| 2 | lagging indicator of quality |
| 3 | cost signal |
| 4 | availability signal |
| 5 | leading indicator of quality |

Los indicadores adelantados se generan dentro del pipeline y se mueven antes de que el usuario note algo. Los atrasados los produce un usuario ya molesto. Costo y disponibilidad son dimensiones aparte: importan, pero no dicen si la respuesta fue correcta.

---

### 42

**Correcta: A**

La calidad de un resumen es cobertura de lo importante y fidelidad a la fuente. Una rúbrica aplicada contra el documento mide eso y se puede correr sobre cada salida.

*Por qué no las otras:* B mide compresión, no calidad; C castiga resúmenes buenos redactados distinto; D es una señal indirecta y ambigua.

---

### 43

**Correcta: A**

Se separa la señal rápida de la garantía: un subconjunto que corre en minutos atrapa las regresiones groseras en cada cambio, y la suite completa protege lo que sale a producción.

*Por qué no las otras:* B frena el ritmo de trabajo; C deja días sin señal; D vuelve a la anécdota.

---

### 44

**Correcta: A y B**

Un dominio regulado exige las dos caras: datos etiquetados por expertos que prueben competencia en lo típico y lo de alto riesgo, y casos adversarios que prueben que los límites aguantan.

*Por qué no las otras:* C mide lo que no importa acá; D es teatro sobre ejemplos elegidos; E llega cuando el riesgo ya salió.

---

### 45

**Correcta: A y B**

Un requisito absoluto se hace cumplir en la salida, no en la instrucción. Bloquear lo no respaldado y exigir la fuente son dos capas del mismo control preventivo.

*Por qué no las otras:* C es una petición en texto; D detecta después de enviado; E no cambia lo que el modelo se permite afirmar.

---

### 46

**Correcta: A**

La compuerta va donde la acción es irreversible y de impacto externo. Lo de bajo riesgo fluye solo, que es lo que sostiene el caso de negocio.

*Por qué no las otras:* B destruye la eficiencia; C revisa después del daño; D deja la mayoría de las cancelaciones sin control.

---

### 47

**Correcta: A**

Los dos deberes conviven si se diseñan juntos: el rastro conserva lo que la auditoría necesita y la identidad se elimina o se seudonimiza. Retrofitear esto después es carísimo.

*Por qué no las otras:* B rompe la auditoría; C supone una jerarquía que no existe; D describe el objetivo sin ningún mecanismo.

---

### 48

**Correcta: A**

Un guardrail tiene dos formas de fallar y se calibra midiendo las dos sobre casos etiquetados. Cuál se tolera más depende del daño relativo en ese negocio, y esa es una decisión explícita.

*Por qué no las otras:* B usa la queja como métrica; C ignora el costo del bloqueo indebido; D cambia una garantía por una petición.

---

### 49

**Correcta: A**

La cadena entera es tu superficie de riesgo: cada subprocesador que toca el dato cuenta, y hay que saber qué pasa cuando uno se cae o se degrada. Los contratos reparten culpa, no evitan el incidente.

*Por qué no las otras:* B y C dejan huecos deliberados; D confunde responsabilidad legal con evaluación de riesgo.

---

### 50

**Correcta: A**

Cuando la decisión tiene efecto sobre la persona, lo exigible es entender en qué se basó y poder pedir revisión humana. Eso es lo que la transparencia significa cuando hay algo en juego.

*Por qué no las otras:* B avisa sin dar nada accionable; C entrega un número que nadie puede interpretar; D expone lógica interna sin volverla comprensible.

---

### 51

**Correcta: A**

El problema es enviar más datos personales de los que el propósito requiere. Minimizar antes de cruzar la frontera resuelve eso y el monitoreo sigue funcionando sobre contenido desidentificado.

*Por qué no las otras:* B protege el viaje, no el procesamiento en destino; C acorta la exposición sin reducirla; D es notificación.

---

### 52

**Correcta: A**

Sacar los atributos explícitos no elimina el sesgo: el distrito escolar arrastra la misma señal. La respuesta es evaluación por segmentos, remediación y monitoreo permanente.

*Por qué no las otras:* B confunde cumplimiento formal con equidad; C ignora las palancas de la capa de aplicación; D esconde el daño.

---

### 53

**Correcta: A**

El principio violado es la separación de confianza: lo recuperado es entrada no confiable, se delimita como dato y no tiene autoridad de instrucción.

*Por qué no las otras:* B restringe fuentes sin arreglar el modelo de confianza; C bloquearía documentos legítimos; D protege secretos, no conducta.

---

### 54

**Correcta: A y B**

Discovery existe para recuperar el problema detrás de la solución propuesta y para fijar qué va a significar éxito. Todo lo demás depende de esas dos cosas.

*Por qué no las otras:* C compromete precio sobre algo no validado; D y E son productos del diseño, prematuros acá.

---

### 55

**Correcta: A**

Se compromete lo que se controla —cuándo va a existir la evidencia— y se ata la decisión de salida a esa evidencia. Es gestión de expectativas con base en ingeniería.

*Por qué no las otras:* B compromete una fecha que no se puede sostener; C bloquea la conversación; D decide el alcance sin el responsable.

---

### 56

**Correcta: A**

El comité no pide el prompt: pide entender qué pasa y qué lo controla. Flujo de decisión, controles y evidencia de evaluación, contados en su idioma, es lo que responde de verdad esa pregunta.

*Por qué no las otras:* B entrega material que no pueden evaluar; C cierra la conversación; D muestra conducta sin mostrar control.

---

### 57

**Correcta: A**

Un piloto exitoso prueba la hipótesis, no la operación. Volumen, casos raros, soporte y costo cambian de escala, y eso se pone sobre la mesa antes de comprometer la fecha.

*Por qué no las otras:* B es pesimismo sin dato; C dilata sin agregar información nueva; D es una consecuencia, no la conversación.

---

### 58

**Correcta: A**

El registro de decisiones existe para eso: quien llega después ve la opción descartada y el motivo, y no gasta un trimestre en volver a descubrirlo. Es lo que hace el traspaso sostenible.

*Por qué no las otras:* B documenta el qué sin el por qué; C y D ponen condiciones que vacían la práctica.

---

### 59

**Correcta: A**

La precisión sí se puede comprometer si se define contra qué se mide y con qué frecuencia se revisa. Eso convierte una expectativa difusa en un acuerdo verificable por las dos partes.

*Por qué no las otras:* B renuncia a lo que el cliente necesita; C acepta sin definir la medición; D salta a la sanción sin definir el objeto.

---

### 60

**Correcta: A**

La jugada profesional es cuantificar calidad, retrabajo y exposición regulatoria contra el ahorro, recomendar, y dejar decidir a quien tiene la responsabilidad.

*Por qué no las otras:* B es engaño; C oculta información material; D escala antes de tener la conversación.

---

### 61

**Correcta: A**

La expectativa se gestiona con la realidad de ingeniería: presupuesto de latencia a la vista, SLA que el pipeline pueda honrar, y velocidad percibida mejorada con streaming.

*Por qué no las otras:* B firma un incumplimiento; C sacrifica la capacidad que justifica el sistema; D garantiza que la brecha aparezca en producción.

---

### 62

**Correcta: A**

El patrocinador financió un resultado de negocio: el reporte encabeza con los criterios acordados en discovery y deja lo técnico como respaldo.

*Por qué no las otras:* B es más de lo mismo con otra frecuencia; C profundiza el desalineamiento; D elimina el lazo.

---

### 63

**Correcta: A**

Los secretos van en variables de entorno y la configuración los referencia. Todo lo demás termina, tarde o temprano, dentro de un repositorio o dentro de una ventana de contexto.

*Por qué no las otras:* B depende de que nadie se equivoque una vez; C documenta la ubicación del secreto; D lo mete en el contexto del modelo.

---

