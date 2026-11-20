# Lab 1 · Dirigir una propuesta de IA y decidir qué utilizar

**Ficha Excel:** [descarga LAB1_Fichas_editables.xlsx](LAB1_Fichas_editables.xlsx), guarda una copia y complétala en Excel o una aplicación compatible. Sus pestañas corresponden a los pasos del laboratorio. También puedes usar la [ficha Markdown](#ficha). Elige Excel o Markdown; no tienes que completar ambos.

<a id="indice"></a>
## Índice

- [Preparación](#preparacion)
- [Base A](#base-a)
- [Base B](#base-b)
- [Base C](#base-c)
- [Profundización](#profundizacion)
- [Avanzado](#avanzado)
- [Ficha Markdown](#ficha)

## 0. Tu misión y tu punto de llegada

Eres consultor y recibes una petición de evolución. Vas a trabajar con una IA para obtener un borrador, revisar su respaldo y dirigir una versión mejor preparada para una conversación de aclaración.

El reto no es demostrar que la IA falla ni conseguir un texto bonito. Es poder explicar qué has pedido, qué has recibido, qué has aceptado o corregido y para qué utilizarías el resultado.

Al terminar conservarás una sola ficha: mensajes y respuestas localizables, revisión humana, comparación antes/después y decisión de uso. Si avanzas, ampliarás esa misma ficha, sin nuevos entregables.

**Recorrido:** preparar → proponer con IA → revisar tú → pedir auditoría → comprobarla tú → dirigir revisión → decidir uso.

**Necesitas:** un asistente autorizado donde enviar prompts y un documento editable. No hacen falta código, instalaciones, búsqueda ni documentos externos. Todo el caso y los mensajes están aquí. No necesitas realizar otro lab.

**Ventana prevista:** 55 minutos de trabajo y un cierre posterior. La base puede ocupar toda la ventana; las capas son para profundizar según ritmo. No es duración pilotada.

El resultado te servirá para preparar una conversación con negocio: qué necesitas aclarar y qué alternativas puedes explorar sin presentarlas como acordadas.

## 1. El expediente que conoce la IA

La lista de solicitudes se ordena por antigüedad, pero se pide atender primero lo urgente. No conocemos cómo se decide la atención efectiva ni qué necesita ver el responsable. Tu trabajo inicial es preparar análisis y preguntas, no aprobar un diseño.

Los hechos del ejercicio son exclusivamente F1–F3, incluidos en el primer mensaje. No conoces campos, estados ni permisos del sistema. Si una respuesta los propone, debe quedar como propuesta; no prueba que existan.

Todo el expediente es ficticio. No añadas datos de clientes ni otras reglas.

<a id="preparacion"></a>
## 2. Prepara conversación y ficha

- Abre una conversación nueva para este lab, sin adjuntos ni búsqueda solicitada.
- Registra asistente, modelo visible, fecha y condiciones conocidas. Si desconoces personalización o configuración, indícalo: chat nuevo no garantiza ausencia de contexto persistente.
- Prepara tu copia del Excel o copia la ficha de la sección 9 a un documento editable. Elige una opción; no completes ambas.
- Guarda cada respuesta completa como R1, R2 y R3, o referencia su ubicación de forma que puedas volver al fragmento.

No envíes las tres peticiones seguidas. El trabajo entre mensajes determina cómo aprovecharás la interacción.

[Volver al índice](#indice)

<a id="base-a"></a>
## 3. Base A · Obtener una propuesta y formar tu primer criterio

### Punto de partida y reto

Tienes una necesidad abierta. Necesitas un borrador útil, sin confundir opciones con acuerdos. Primero leerás el resultado con criterio propio, antes de pedir que la IA lo critique.

### Acción: envía el primer mensaje completo

```text
F1 · Situación actual
Sistema ficticio de gestión de solicitudes de servicio técnico.
Actualmente las solicitudes se ordenan por fecha de creación,
de más antigua a más reciente.

F2 · Necesidad
«Queremos que las solicitudes urgentes se atiendan antes y que el responsable
pueda comprobar qué está pasando».

F3 · Información pendiente
No se ha definido qué significa urgente, quién lo determina, si esa condición
puede cambiar ni qué necesita consultar el responsable.
No se describen pantallas, asignación, notificaciones ni reglas de servicio.

ENCARGO
Basado en F1–F3, propón los pasos funcionales para abordar esta necesidad:
las solicitudes urgentes se atienden antes y el responsable puede comprobar
qué está pasando.

La propuesta se utilizará como borrador para preparar el análisis del cambio.
Indica también qué información falta definir. No escribas código.
Organiza tu respuesta en pasos y preguntas pendientes.
Extensión orientativa: hasta 450 palabras.
```

### Después de R1: tu análisis antes de continuar

1. Resume en una frase qué trabajo ha hecho la IA: ¿preguntas, pasos funcionales, diseño concreto o mezcla?
2. Selecciona tres fragmentos distintos. Busca una aportación que conservarías, otra cuya condición o respaldo debas examinar y una pregunta o ausencia relevante. Si todo es prudente, analiza tres aportaciones y sus límites: no inventes errores.
3. Para cada fragmento completa R1-A, R1-B y R1-C en la ficha: frase, qué afirma, fuente o ausencia, estatus y decisión provisional.
4. Escribe una valoración inicial de uso antes de enviar la auditoría.

**Ayuda de análisis:** “podría estudiarse un panel” propone; “el panel actual” describe algo que no figura en los insumos. “Se pide priorizar” es objetivo aportado; no significa que hoy ya se atienda por prioridad.

**Comprobación:** otra persona puede seguir tu razón sin adivinar a qué texto te refieres. No basta “correcto”, “alucinación” o “me gusta”.

### Si la respuesta toma otro camino

| Lo que recibes | Qué haces sin reiniciar |
|---|---|
| Pide aclaraciones pertinentes | Evalúa las preguntas y explica qué decisión preparan; no está obligada a inventar una solución. |
| Propone opciones con cautela | Comprueba que sean pertinentes y no se vuelvan acuerdos en otros apartados. |
| Da por ciertos roles o pantallas | Cita el fragmento y la ausencia de respaldo. No concluyas que son imposibles. |
| Solo da generalidades | Identifica qué parte del encargo queda sin tratar y qué información ya podía utilizar. |
| Incluye código | No lo ejecutes; registra que no cumple el encargo funcional. |

Envía el primer prompt completo, con F1–F3, en un chat nuevo de un segundo asistente autorizado. Puedes probar el acceso gratuito de ChatGPT o Gemini; el acceso sin cuenta puede variar. Si no puedes acceder, utiliza la respuesta facilitada en clase y marca la ruta como observada.

En tu valoración inicial, registra una diferencia relevante, una afirmación que comprobarías y qué conservarías o corregirías. No repitas todo el lab en el segundo asistente ni copies su respuesta al chat principal.

Esta consulta de contraste es independiente de la cuarta consulta opcional de las capas.

[Volver al índice](#indice)

<a id="base-b"></a>
## 4. Base B · Pedir una auditoría sin delegar la validación

### Punto de partida y reto

Tienes R1 y tu valoración inicial. La IA va a proponer una autocrítica; debes comprobarla, no aceptarla por venir en tabla.

### Acción: vuelve al chat principal donde obtuviste R1 y envía este mensaje

```text
Revisa críticamente tu respuesta anterior usando únicamente F1–F3
aportados al inicio de esta conversación.

Selecciona hasta seis afirmaciones relevantes de tu respuesta, incluyendo
alguna que conservarías. Para cada una muestra:
1. El fragmento original, sin cambiarlo.
2. Su estatus: información respaldada, propuesta, supuesto no confirmado
o pregunta pendiente. Si mezcla estatus, explica la mezcla.
3. El fragmento de F1, F2 o F3 que lo respalda; si no existe, escribe
«sin respaldo en los insumos», sin inventar citas.
4. Qué conservarías, reformularías o preguntarías antes de utilizarlo.

No fabriques defectos para completar seis filas. Distingue una propuesta
explícita de una afirmación presentada como hecho del sistema.
Si la respuesta inicial ya era prudente, conserva esa conclusión y explica
sus límites de uso. No apruebes el cambio ni escribas código.
```

### Después de R2: acepta o discute con evidencia

1. Elige dos filas o conclusiones de R2. Una puede confirmar tu análisis y otra aportar una observación distinta. Si no difieren, revisa dos confirmaciones.
2. Vuelve a R1: comprueba si la cita es literal y si su contexto cambia el sentido.
3. Vuelve a F1–F3: comprueba si el respaldo justifica la conclusión completa.
4. Decide aceptar, matizar o rechazar cada observación. Completa R2-A y R2-B.
5. Compara tu criterio inicial con el actual: ¿cambió algo?, ¿por qué? Una permanencia justificada también cuenta.

**Ayuda:** si la IA llama “invención” a una opción que estaba bien etiquetada, puede haber confundido propuesta con hecho. Si cita F2 para justificar un supervisor, el objetivo no respalda ese actor.

**Comprobación:** puedes sostener tu decisión incluso si R2 se contradice. La autocrítica es otra respuesta, no una revisión independiente ni una aprobación.

### Bifurcaciones

- **R2 no encuentra errores:** revisa cobertura y límites de uso; no pidas defectos por obligación.
- **R2 cita una frase inexistente:** registra la discrepancia y utiliza el texto real en tu condición de revisión.
- **R2 añade una regla nueva:** no la incorpores como contexto confirmado.
- **R2 te convence de cambiar de criterio:** anota qué evidencia cambió, no solo “Claude tiene razón”.

[Volver al índice](#indice)

<a id="base-c"></a>
## 5. Base C · Dirigir una revisión y decidir el uso

### Punto de partida y reto

Dispones de R1, R2 y tus decisiones. Debes traducir tu revisión en una condición concreta y comprobar después que se ha atendido.

### Antes de enviar

Escribe una condición basada en lo observado. Estructura de ayuda:
> «En [fragmento o asunto] conserva/cambia [qué] porque [dato o límite de F1–F3]».

Ejemplo construido: “Mantén el desempate como alternativa por confirmar; F1 solo describe el orden actual”. Si no existe ese problema en tu respuesta, no copies la condición: elige una fortaleza, límite o falta de concreción real.

### Acción: copia el mensaje y añade tu condición

```text
Ahora prepara una versión revisada de tu propuesta para una conversación
de aclaración. Trabaja solo con F1–F3 y con lo revisado en esta conversación.

Organízala en:
A. Qué sabemos del funcionamiento actual y de la necesidad.
B. Pasos que podemos proponer, señalando las opciones no acordadas.
C. Preguntas que deben responderse antes de concretar la solución.
D. Qué cambió respecto a la primera respuesta y por qué.

No presentes actores, pantallas, campos, avisos, plazos ni mecanismos
de aprobación como existentes o acordados si no están respaldados.
No elimines una propuesta útil solo por ser propuesta: identifícala.
No declares validado el resultado. No escribas código.
Extensión orientativa: hasta 450 palabras.
```

Añade al final: **Mi condición de revisión: [tu texto]**. El único elemento que debes completar es esa condición; F1–F3 siguen en esta conversación.

### Después de R3: verifica tres cosas

1. **Cambio:** compara un fragmento de R1 con su equivalente en R3. ¿Cambió el estatus de la afirmación o solo la redacción?
2. **Conservación:** comprueba una aportación útil que debía mantenerse.
3. **Regresión:** busca un supuesto nuevo o una condición perdida. Si no la encuentras, explica qué has comprobado.

Completa R3-Cambio, R3-Conservación y R3-Regresión. Emite la decisión final para un uso concreto: preparación de preguntas, borrador condicionado o no utilizable todavía para ese uso.

**Control humano:** precisa qué contrastarías, con qué y qué harías si no encaja. “Revisar todo” no explica la acción.

### Bifurcaciones

- **No hay cambio porque R1 ya era adecuada:** comprueba la condición y explica por qué conservar es válido.
- **Se elimina una opción útil:** identifica la pérdida y regístrala como ajuste pendiente, no como mejora automática.
- **La condición se ignora:** conserva la evidencia; podrás trabajarla en profundización.
- **R3 es más corta o larga:** no uses longitud como prueba de mejora.

[Volver al índice](#indice)

<a id="profundizacion"></a>
## 6. Profundización · Corregir sin perder una aportación útil

### Punto de partida

Utiliza R3 y tu control de cambio/conservación/regresión. No empiezas otro caso ni otro documento.

### Reto

Construir una instrucción de corrección precisa y evaluar qué tendría que cambiar y qué debería permanecer estable.

### Recorrido guiado

**P1. Selecciona un fragmento.** Elige un fragmento continuo de dos o tres frases que prescriba, generalice o sea demasiado vago para tu uso. Si es adecuado, elige un paso cuya comprobación puedas hacer más explícita sin inventar negocio. Ese bloque será el objeto de revisión de P4: copia su texto exacto en P1.

**P2. Descompón.** Separa afirmaciones: dato actual, propuesta, pendiente. Identifica qué conservarás y qué mejorarás. No critiques todo el párrafo por una sola frase.

**P3. Define tu criterio de éxito antes de pedir la revisión.** Completa:
- La versión será más utilizable si…
- No aceptaré como mejora que se pierda…
- Seguirá pendiente…

**P4. Prepara la instrucción.** Sustituye los corchetes con tu análisis; comprueba que no quedan marcadores:

```text
Revisa solo este fragmento de R3:
«[pega el fragmento exacto]».
Mi observación: [problema o límite y relación con F1–F3].
Conserva [aportación útil] y mejora [aspecto concreto].
Se considerará útil si [criterio observable].
No resuelvas por tu cuenta las preguntas pendientes.
Devuelve versión revisada y motivo del cambio.
Si mi observación es incorrecta, explícalo con los insumos.
```

**P5. Elige cómo contrastar.** Si hay disponibilidad, puedes ejecutar este mensaje como la única cuarta consulta de ampliación del lab. Si prefieres reservarla para la capa avanzada o no hay acceso, escribe una revisión humana y márcala como tal. No atribuyas ese texto a la IA.

**P6. Evalúa con el criterio previo.** Registra antes/después, conservación y posible regresión. Acepta, ajusta o rechaza la revisión. No te limites a transcribirla.

### Ayudas y comprobación

Una mejora superficial cambia “se hará” por “podría hacerse” pero deja un actor como existente sin respaldo. Una mejora sustantiva puede mantener una alternativa y convertir la decisión ausente en pregunta.

Si la IA discrepa contigo, comprueba su evidencia: no tiene que obedecer una corrección incorrecta. Si no cambia nada, verifica si tu criterio requería realmente un cambio.

**Salida:** tabla P1–P6 en la misma ficha. Debe verse tu objetivo de revisión y tu decisión final, no solo un nuevo texto.

[Volver al índice](#indice)

<a id="avanzado"></a>
## 7. Avanzado · Cambiar el uso sin inventar más certeza

### Situación nueva, ficticia

Recibes:
> «Necesitamos comunicar mañana qué cambiaremos. Utiliza la respuesta más concreta y deja las dudas como observaciones».

El mensaje expresa presión. No aporta reglas ni demuestra quién puede aprobar el cambio.

### Reto

Dirigir una revisión con IA para adaptar el resultado a una comunicación, sin confundir una propuesta con un compromiso. Si ya usaste la cuarta consulta, prepara y contrasta el mensaje sin enviarlo: no se abre una cadena ilimitada.

### Recorrido guiado

**A1. Analiza el riesgo de reutilización.** En R3, o en tu versión posterior a P6 si la realizaste, marca una frase que, copiada sin contexto, pueda interpretarse como decisión o compromiso. Si no la hay, selecciona una frase cuya cautela deba preservarse.

**A2. Separa tres contenidos.** En la ficha escribe qué comunicarías ahora, qué presentarías como alternativa y qué debe quedar pendiente. Justifica cada clasificación con F1–F3.

**A3. Redacta tu comunicación inicial.** Escribe 5–8 líneas que permitan avanzar. No inventes aprobación, plazos de implantación ni un sistema actual no descrito. Identifícala como texto humano V0.

**A4. Dirige la revisión de IA.** Completa este mensaje con tu texto y dos criterios propios. No basta “hazlo profesional”:

```text
Revisa esta comunicación antes de compartirla:
«[mi texto V0 completo]».
Contrástala con F1–F3 de esta conversación.
Necesito conservar: [criterio 1].
Necesito evitar: [criterio 2].
Señala compromisos no respaldados y también bloqueos innecesarios.
Devuelve observaciones con fragmento, una versión propuesta y sus límites.
No inventes autoridad, reglas o fechas de implantación.
```

**A5. Contrasta.** Si te queda la consulta opcional, envíalo. Si no, utiliza este fragmento ficticio para probar tu revisión, no como salida real:
> «Confirmamos que se implantará prioridad Alta/Media/Baja; el resto de condiciones se validará durante el desarrollo».
Explica qué tendría que cambiar y propón una versión humana. Una advertencia final no convierte automáticamente el compromiso en propuesta.

Si no ejecutas la consulta, aplica además tus dos criterios de A4 a tu propio V0 y escribe su revisión humana, o justifica conservarlo. Identifícala como tal: A6 comparará V0 con esa revisión. El análisis del fragmento ficticio es un apoyo, no sustituye revisar tu texto.

**A6. Decide el texto final.** Compara V0 con la revisión obtenida: salida de IA si ejecutaste, revisión humana si no. Acepta, corrige o conserva, y explica qué cambio de uso motivó tu decisión. No digas que la IA “validó” la comunicación.

### Comprobación

Tu resultado permite comunicar algo útil y mantiene visibles las decisiones no tomadas. Se distingue texto humano, salida real y fragmento ficticio. La exigencia está en dirigir y revisar la adaptación, no en añadir retórica.

### Bifurcaciones

- **La revisión propone no comunicar nada:** localiza qué dato obliga a ese bloqueo; objetivo, orden actual y pendientes siguen siendo comunicables.
- **La revisión mantiene V0 casi igual:** es válido si no convierte alternativas en compromisos; explica por qué conservas.
- **La revisión añade fechas, roles o campos:** no los aceptes como hechos o compromisos sin respaldo. Si son alternativas pertinentes, etiquétalas; registra el límite.
- **Solo añade “sujeto a validación” al final:** comprueba las frases que comprometen; una advertencia final no las corrige automáticamente. Reformúlalas.

[Volver al índice](#indice)

## 8. Gestión de respuestas y acceso

- Guarda lo obtenido; no regeneres por una variación que no te gusta.
- Si se interrumpe el acceso, conserva los pasos completados y trabaja con una salida real observada en la demostración. Marca qué ejecución es propia y cuál observada.
- Si ninguna ejecución está disponible, abre la [resolución guiada](02_LAB1_resolucion.md), distribuida con este paquete. Sus ejemplos potenciales de R1, R2, R3 y V0 permiten continuar como contingencia simulada. Marca esa ruta: no equivale a ejecución propia. No se necesitan nuevas capturas ni materiales por crear.
- No conocemos consumo fijo ni disponibilidad de mensajes. La cuarta consulta es opcional y compartida entre las capas: elígela, no la dupliques automáticamente.

<a id="ficha"></a>
## 9. Ficha única guiada

### Registro de condiciones y salidas
- Fecha, asistente/modelo visible:
- Condiciones conocidas/desconocidas:
- R1 guardada en: ____; R2: ____; R3: ____.
- Qué partes son ejecución propia, observada o simulada:

### Base A · Mi criterio antes de la auditoría
- Qué tipo de trabajo ha producido R1:
| Registro | Fragmento exacto/localizador | Qué afirma | F1/F2/F3 o ausencia | Estatus | Decisión provisional y por qué |
|---|---|---|---|---|---|
| R1-A: aportación útil | | | | | |
| R1-B: asunto a examinar | | | | | |
| R1-C: pregunta/ausencia | | | | | |

- Valoración inicial para un uso concreto:

### Base B · Mi revisión de R2
| Registro | Qué dice R2 | ¿La cita existe en R1? | ¿El respaldo justifica la conclusión? | Acepto/matizo/rechazo y motivo |
|---|---|---|---|---|
| R2-A | | | | |
| R2-B | | | | |

- Mi criterio antes:
- Mi criterio después y evidencia del cambio o permanencia:

### Base C · Condición y verificación
- Condición añadida a la tercera petición:
- Prompt efectivamente enviado, si lo adapté:
| Control | Fragmento previo | Fragmento posterior | Resultado y respaldo | Mi acción |
|---|---|---|---|---|
| R3-Cambio | | | | |
| R3-Conservación | | | | |
| R3-Regresión o comprobación de ausencia | | | | |

- Decisión de uso final:
- Sintetiza aquí, en 3–5 líneas, las preguntas prioritarias y las alternativas que llevarías a esa conversación. No es otro entregable.
- Qué contrastaré, con qué y qué haré si no coincide:
- Pendientes que el resultado no resuelve:

### P · Profundización
- P1. Fragmento exacto:
| P2. Afirmación separada | Estatus/respaldo | Conservar o mejorar y razón |
|---|---|---|
| | | |
- P3. Criterio de éxito:
- P3. Lo que no debe perderse:
- P3. Lo que seguirá pendiente:
- P4. Mensaje completo preparado:
- P5. Consulta ejecutada / revisión humana (identificar y guardar):
| P6. Antes | Después | ¿Cumple el criterio? | ¿Conserva lo útil? | ¿Introduce regresión? | Decisión |
|---|---|---|---|---|---|
| | | | | | |

### A · Avanzado
- A1. Frase con riesgo o cautela que debe preservarse:
| A2. Qué comunicaría | Qué es alternativa | Qué queda pendiente | Respaldo y razón |
|---|---|---|---|
| | | | |
- A3. Comunicación humana V0:
- A4. Mensaje completo para dirigir la revisión y sus dos criterios:
- A5. Salida real o revisión humana de mi V0 (identificar); análisis del fragmento ficticio, si lo utilicé:
| A6. Fragmento V0 | Revisión o contraste de V0 | Qué acepto/rechazo | Texto final | Por qué cambia o permanece |
|---|---|---|---|---|
| | | | | |

### Reflexión
- Una decisión que cambió tras la interacción y su evidencia:
- Algo que no delegué en la IA:
- Qué haría distinto al preparar la siguiente petición:

## 10. Finalización

La base termina cuando puedes reconstruir insumos, mensajes, salidas, revisión humana y uso final. Las capas terminan cuando puedes justificar el cambio pre/post contra un criterio definido antes de revisar. No es obligatorio completar ambas para terminar la base. Mantén la autoría y la ruta reales visibles.

[Volver al índice](#indice)
