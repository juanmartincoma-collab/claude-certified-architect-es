# Glosario EN → ES

Los 56 términos que aparecen en los dos exámenes. El examen es solo en inglés: si alguno de estos te hace releer el enunciado, es tiempo que perdés.

| Término | En español | Qué significa |
|---|---|---|
| **agentic** | agéntico | Sistema donde el modelo decide el próximo paso en vez de seguir una secuencia fija. |
| **allowlist** | lista de permitidos | Enumera lo que se puede ejecutar. Lo que no está, no corre. |
| **audit trail** | rastro de auditoría | Registro ordenado de qué hizo el sistema y por qué, reconstruible meses después. |
| **blast radius** | radio de daño | Cuánto puede romper una falla o un abuso antes de que algo lo contenga. |
| **canary** | canary | Sacar la versión nueva a una porción chica del tráfico para detectar daño antes de ampliar. |
| **capability bloat** | exceso de capacidades | El agente tiene tantas herramientas que empieza a elegir mal. |
| **chain-of-thought** | razonamiento paso a paso | Pedirle al modelo que razone antes de responder. Solo rinde en tareas de varios pasos. |
| **chunk** | fragmento | El pedazo en que se corta un documento para poder buscarlo. |
| **chunking** | fragmentación | Cómo se corta el documento. Si corta ideas por la mitad, el retrieval falla. |
| **context window** | ventana de contexto | Todo lo que el modelo tiene delante en una llamada. Es finita y se paga entera. |
| **correlation ID** | identificador de correlación | Une todos los pasos de una misma sesión para poder reconstruirla. |
| **drift** | deriva | Cambió lo que entra al sistema, no el sistema. |
| **embedding** | embedding | Convierte el significado de un texto en coordenadas. Textos parecidos quedan cerca. |
| **eval / evaluation suite** | suite de evaluación | Conjunto de casos con respuesta esperada que se corre para medir calidad. |
| **extended thinking** | razonamiento extendido | Modo en que el modelo dedica más cómputo a pensar antes de responder. |
| **few-shot** | few-shot | Mostrar ejemplos completos de la salida deseada en vez de describirla. |
| **golden dataset** | conjunto dorado | Casos etiquetados por expertos que definen la respuesta correcta. |
| **grounded** | fundamentado | Respaldado por una fuente recuperada. Si no hay fuente, no hay respuesta fundamentada. |
| **guardrail** | guardrail | Control que impide que cierta salida exista. Es código, no una instrucción. |
| **hallucination** | alucinación | El modelo afirma con seguridad algo que no está en la fuente ni en la herramienta. |
| **handoff** | traspaso | Entregar la operación del sistema a otro equipo. |
| **headless** | sin interfaz | Corre solo, sin que nadie mire ni pueda intervenir. Típico de CI. |
| **hook** | hook | Programa propio que el sistema ejecuta en un momento del ciclo. Verifica, no decide. |
| **human-in-the-loop** | validación humana | Una persona aprueba antes de que la acción ocurra. |
| **input schema** | esquema de entrada | Contrato que define qué parámetros acepta una herramienta y de qué tipo. |
| **lagging indicator** | indicador atrasado | Confirma un daño que ya ocurrió. Quejas, bajas de usuarios. |
| **leading indicator** | indicador adelantado | Se mueve antes de que el usuario note algo. Relevancia de retrieval, tasa de fundamentación. |
| **least privilege** | privilegio mínimo | Dar solo los permisos que el rol necesita, y ninguno más. |
| **LLM-as-judge** | modelo como juez | Un modelo puntúa las salidas con una rúbrica, calibrado contra humanos. |
| **MCP** | MCP | Protocolo estándar para exponer un sistema una vez y que cualquier aplicación lo use. |
| **model mismatch** | modelo inadecuado | El prompt está bien; el modelo elegido no da para esa tarea. |
| **observability** | observabilidad | Poder saber qué pasó adentro: trazas, métricas, muestreo de payloads. |
| **orchestrator** | orquestador | Coordina subagentes cuya cantidad se decide al leer el problema, y sintetiza. |
| **parallelization** | paralelización | Varios agentes trabajan a la vez sobre piezas definidas de antemano. |
| **progressive discovery** | divulgación progresiva | Cargar herramientas y contexto solo cuando hacen falta. |
| **prompt caching** | caché de prompts | Reutiliza el trabajo hecho sobre el prefijo estable del prompt. |
| **prompt injection** | inyección de prompt | Texto dentro de un documento que intenta darle órdenes al modelo. |
| **prompt failure** | falla de prompt | Las instrucciones se contradicen o son ambiguas. |
| **proxy variable** | variable proxy | Un dato que arrastra la señal de un atributo protegido. Ejemplo: el código postal. |
| **p95 latency** | latencia p95 | El tiempo que no supera el 95% de los pedidos. |
| **RAG** | RAG | El sistema busca documentos relevantes y se los da al modelo antes de responder. |
| **re-ranking** | reordenamiento | Segunda pasada que ordena mejor los candidatos que trajo la búsqueda. |
| **retrieval** | recuperación | Traer los fragmentos relevantes para la consulta. |
| **hybrid retrieval** | recuperación híbrida | Combina coincidencia exacta con búsqueda por significado. |
| **routing** | enrutamiento | Clasificar el pedido y mandarlo a uno de varios caminos preexistentes. |
| **runbook** | runbook | Manual operativo: cómo se mantiene vivo el sistema y qué hacer si falla. |
| **scaled score** | score escalado | Puntaje normalizado de 100 a 1.000. En estos exámenes se aprueba con 720. |
| **silent failure** | fallo silencioso | Devolver vacío o un valor por defecto cuando en realidad hubo un error. |
| **SLA** | SLA | Compromiso contractual de servicio, por ejemplo un tiempo máximo de respuesta. |
| **subagent** | subagente | Agente con su propia ventana de contexto al que se delega trabajo pesado. |
| **system prompt** | system prompt | Las instrucciones permanentes que enmarcan cada respuesta. |
| **temperature** | temperatura | Controla la variabilidad de la respuesta. No controla obediencia ni veracidad. |
| **token** | token | Unidad que el modelo procesa y por la que se cobra. Unos cuatro caracteres. |
| **tool** | herramienta | Función que el modelo puede pedir que se ejecute. El modelo no ejecuta: pide. |
| **trace** | traza | Registro completo de una sesión: entradas, contexto recuperado, herramientas y salidas. |
| **workflow** | workflow | Secuencia de pasos definida de antemano por una persona. |
