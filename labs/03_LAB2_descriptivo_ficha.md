# Lab 2 · Preparar contexto, ejecutar y revisar una petición reutilizable

**Ficha Excel:** [Descarga la ficha Excel](LAB2_Fichas_editables.xlsx), guarda una copia y complétala en Excel o una aplicación compatible. También puedes utilizar la [ficha Markdown de la sección 10](#ficha). Elige una opción; no completes ambas.

<a id="indice"></a>
## Índice

- [Preparación](#preparacion)
- [Base A](#base-a)
- [Base B](#base-b)
- [Base C](#base-c)
- [Profundización](#profundizacion)
- [Avanzado](#avanzado)
- [Ficha](#ficha)

## 0. Misión y resultado

Vas a utilizar IA para analizar una necesidad con distinta información y después dirigir una pregunta más concreta. Debes poder explicar por qué seleccionaste el contexto, qué utilizó realmente la respuesta y qué revisión necesita.

Al terminar tendrás una sola ficha con R1/R2/R3 guardadas o localizables, comparación, siete decisiones de preparación, prompt efectivamente enviado y decisión de uso. Las capas incorporan incertidumbre documental y transferencia a otra persona, no otro proyecto.

**Autonomía:** todo el expediente y los prompts están aquí; no necesitas Lab 1 ni material adicional. Caso ficticio, sin datos de clientes.

**Medios:** asistente autorizado y documento editable. Sin búsquedas, código, instalaciones o integraciones.

**Recorrido principal:** chat A con información funcional → chat B con información funcional/técnica → tercera consulta en chat B sobre estados. Tres mensajes; una cuarta consulta opcional, compartida por las dos capas. No equivale a consumo fijo.

**Ventana prevista:** 70 minutos, con reflexión posterior. Base y capas comparten la ventana según ritmo; no se exige completar todo ni se declara tiempo pilotado.

El resultado te servirá para preparar una conversación con el equipo técnico: qué datos están respaldados, qué decisiones siguen abiertas y qué necesitas comprobar antes de concretar el impacto.

## 1. Información que cambia y qué debemos mantener

F1 describe orden actual; F2, necesidad; F3, pendientes. T1 describe campos, estados y ausencia de prioridad. Los textos completos aparecen en los mensajes; no es necesario copiarlos desde otro archivo.

Para comparar las dos primeras ejecuciones mantenemos tarea y salida y añadimos T1. Usaremos chats separados para no arrastrar una conversación de análisis. Registra condiciones conocidas: chat nuevo no acredita ausencia de personalización.

No intentamos demostrar causalidad. Una respuesta puede ser parecida, más prudente, más prescriptiva o menos útil. Conserva lo que ocurra sin regenerar para cumplir una expectativa.

<a id="preparacion"></a>
## 2. Preparación

Prepara tu copia del Excel o copia la ficha de la sección 10 a un documento editable. Registra asistente/modelo/fecha y abre chat A. Guarda respuestas completas y mensajes enviados. Utiliza el mismo modelo y funciones en A y B si están disponibles; si cambian, anótalo y limita la comparación.

[Volver al índice](#indice)

<a id="base-a"></a>
## 3. Base A · Primera ejecución con contexto funcional

### Punto de partida y reto

Pides analizar impacto con una descripción incompleta. Te interesa observar cómo trata lo que no conoce, no exigir una solución cerrada.

### Acción: envía en chat A

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

TAREA
Analiza el posible impacto técnico de implementar esta necesidad.
Indica qué información falta definir.

SALIDA
Separa: hechos aportados, impactos posibles y preguntas pendientes.
Si planteas alternativas, identifícalas como propuestas, no como acuerdos.
No escribas código. Extensión orientativa: hasta 350 palabras.
```

### Revisión antes de seguir

Guarda R1. Completa B1-A y B1-B: una afirmación y una pregunta o ausencia. Escribe qué puede comprobarse con F1–F3 y qué no.

**Ayuda:** una pregunta pertinente puede ser el resultado más útil. Una propuesta de datos no acredita que esos datos existan.

**Comprobación:** distingues ordenación documentada y objetivo de atención. No calificas de error que no enumere estados que no se le han dado.

**Bifurcaciones:** si pide aclaraciones, valora cobertura; si inventa una tabla, registra ausencia de respaldo; si devuelve generalidades, indica qué parte del contexto sí podía aprovechar. No repitas la consulta buscando fallos.

[Volver al índice](#indice)

<a id="base-b"></a>
## 4. Base B · Segunda ejecución con contexto técnico

### Acción: abre chat B y envía completo

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

T1 · Descripción técnica sintética disponible
Arquitectura: API REST y base de datos.
Entidad Ticket: TicketID, UserID, CreationDate, Status, Category.
Status tiene actualmente Open y Closed.
Ordenación actual: fecha de creación, de más antigua a más reciente.
No existe ningún campo o atributo de prioridad.
No se documentan endpoints, integraciones, permisos ni reglas de transición.

TAREA
Analiza el posible impacto técnico de implementar esta necesidad.
Indica qué información falta definir.

SALIDA
Separa: hechos aportados, impactos posibles y preguntas pendientes.
Si planteas alternativas, identifícalas como propuestas, no como acuerdos.
No escribas código. Extensión orientativa: hasta 350 palabras.
```

### Comparación humana

Guarda R2. No envíes aún la tercera petición.

1. Selecciona cuatro observaciones relevantes repartidas entre las respuestas: datos actuales, impactos, preguntas y supuestos/límites. No tienen que ser errores ni diferencias.
2. Cita los fragmentos y relaciona cada uno con F1–F3/T1 o ausencia.
3. Explica qué consecuencia tienen para el uso. “R2 es más técnica” no es suficiente.
4. Registra una cautela que ya era necesaria sin T1 y una información que solo T1 permite contrastar.
5. Escribe qué no permite concluir esta comparación de dos respuestas.

**Comprobación:** no conviertes “ahora sabemos que no hay prioridad” en “está decidido crear Priority”.

### Bifurcaciones

| Resultado                | Cómo analizarlo                                                                       |
| ------------------------ | ------------------------------------------------------------------------------------- |
| R1 y R2 son parecidas    | Comprueba si R2 utiliza T1 y si la similitud es razonable para la pregunta.           |
| R2 aprovecha T1          | Identifica qué dato y qué afirmación mejora su respaldo. No generalices causalidad.   |
| R2 prescribe más cambios | Separa dato añadido y solución no acordada; más detalle no equivale a mejor análisis. |
| R2 omite T1              | Señala qué oportunidad de contraste falta y su importancia para el uso.               |

[Volver al índice](#indice)

<a id="base-c"></a>
## 5. Base C · Preparar la tercera petición antes de enviarla

### Punto de partida y reto

La pregunta es «¿Qué impacto tiene esto en los estados del ticket?». Necesitas hacerla comprensible y revisable. Todavía no debes decidir crear un estado ni asegurar que permanecerán intactos.

### Completa las siete decisiones

| Campo               | Pregunta que debes resolver ahora                                                                                                                |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Petición            | ¿Qué aspecto concreto analizaremos?                                                                                                              |
| Contexto incluido   | ¿Qué datos de F1–F3/T1 son necesarios?                                                                                                           |
| Justificación       | ¿Qué permite interpretar o comprobar cada selección?                                                                                             |
| Contexto excluido   | ¿Qué propuestas de R2, que siguen en el historial del chat B, o de R1, que está en chat A, no son hechos y cómo evitas tratarlas como acordadas? |
| Límites             | ¿Qué no se sabe ni se ha acordado?                                                                                                               |
| Salida solicitada   | ¿Qué estructura ayudará a revisar el resultado?                                                                                                  |
| Comprobación humana | ¿Qué contrastarás, con qué y qué harás si no coincide?                                                                                           |

Escribe en tu ficha. No hace falta eliminar información por brevedad: puedes conservar los insumos completos con justificación. En chat B no estás borrando R2 del historial: seleccionas qué se usa como hecho y qué debe mantenerse como propuesta. R1 no está en ese chat salvo que tú la copies.

### Haz que la plantilla influya en el mensaje

El prompt siguiente es un apoyo editable, no una solución que sustituye tus siete decisiones. Antes de enviarlo:

1. Identifica un campo de tu plantilla que cubre y señala cómo.
2. Identifica un campo que debe resolverse fuera del mensaje, o un aspecto que necesita adaptación.
3. Cambia o añade una línea cuando tu preparación lo requiera. Si lo conservas tal cual, justifica por qué representa tus decisiones.
4. Guarda el texto efectivamente enviado y cualquier modificación propia. Una instrucción nueva en el mensaje no borra las respuestas anteriores del chat.

### Acción: tercera consulta en chat B

```text
Con F1–F3 y T1 disponibles en esta conversación, analiza esta pregunta:
«¿Qué impacto tiene priorizar las solicitudes urgentes en los estados del ticket?».

No está decidido modificar los estados ni conservarlos necesariamente.

Organiza la respuesta en una tabla con:
- Afirmación o cuestión a revisar.
- Dato aportado que la respalda, o «sin dato suficiente».
- Impacto posible, expresado como hipótesis cuando corresponda.
- Pregunta que permitiría decidir.

Distingue Open/Closed, que son datos del estado actual descrito,
de cualquier representación futura de urgencia.
No conviertas la ausencia de prioridad en obligación de crear un campo.
No inventes una transición ni presentes una propuesta como aprobada.
Cierra indicando qué no puede decidirse todavía.
No escribas código. Extensión orientativa: hasta 350 palabras.
```

### Revisión humana de R3

1. Comprueba dos afirmaciones sobre el estado actual contra T1.
2. Elige una hipótesis o pregunta: explica qué decisión permitiría preparar.
3. Busca una prescripción o descarte sin análisis. Si no aparece, registra qué revisaste.
4. Evalúa la estructura solicitada: ¿ayuda a localizar respaldo o solo organiza afirmaciones sin justificar? Regístralo en «Evaluación de la estructura».
5. Decide para qué utilizarías R3 y qué no habilita todavía.

Completa B3-Dato1, B3-Dato2, B3-Hipótesis y B3-Límite. No todas las filas deben contener fallos.

**Importante:** esta tercera consulta cambia tarea, instrucciones e historial. No atribuyas su resultado únicamente a más contexto.

### Bifurcaciones

| Resultado de R3                                                  | Qué haces sin regenerar automáticamente                                                                          |
| ---------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| Cumple la tabla, pero afirma estados o transiciones no aportados | Cita la afirmación y su ausencia de respaldo: la estructura no valida el contenido.                              |
| Es prudente, pero no utiliza tabla                               | Registra el incumplimiento de formato y valora el contenido por separado.                                        |
| Solo dice “falta información”                                    | Reconoce la prudencia y recupera de T1 los datos que sí permiten analizar: Open/Closed y ausencia de prioridad.  |
| Prescribe Urgent o descarta cambios sin análisis                 | Señala el fragmento y qué fundamento falta. No rechaces una hipótesis bien etiquetada solo por mencionar Urgent. |
| Usa T1, pero se parece a R2                                      | Revisa si responde a la nueva tarea; similitud no acredita por sí sola fallo ni éxito.                           |

[Volver al índice](#indice)

<a id="profundizacion"></a>
## 6. Profundización · Introducir incertidumbre documental sin convertirla en hecho

### Punto de partida

Tienes R3 y tu ficha. Aparecen estos documentos construidos para la capa:

**D1 — Propuesta anterior no confirmada:** «Se planteó el estado Urgent. No consta si se aprobó o implementó y la nota no está reconciliada con la descripción actual».

**D2 — Otro proyecto:** «Los estados son New, Assigned y Resolved; las urgencias se comunican por correo». No es documentación de este sistema.

T1 sigue siendo la descripción actual proporcionada. Estos documentos no son resultados de una búsqueda real ni implementan RAG.

### Reto

Dirigir una revisión que preserve el alcance de T1 y haga visible lo que D1 no permite saber, sin importar reglas de D2.

### Recorrido guiado

**P1. Clasifica antes de escribir.** Para T1/D1/D2 registra origen dentro del ejercicio, alcance, qué afirma y qué no acredita. “Actual/antiguo” no sustituye al análisis.

**P2. Selecciona una frase de R3.** Puede ser correcta según T1 pero necesitar alcance documental, como “el sistema solo tiene…”. Si no hay tal frase, elige una conclusión cuyo uso exija aclarar D1.

**P3. Define qué debe preservarse y qué debe hacerse visible.** No modificar T1 por intuición; tampoco afirmar que Urgent nunca existió. Escribe el criterio previo de revisión.

**P4. Prepara la consulta siguiente.** Completa el fragmento y el criterio, sin marcadores pendientes:

```text
Revisa esta afirmación de tu respuesta anterior:
«[frase real de R3]».
T1 describe actualmente Open/Closed y ausencia de atributo de prioridad.
D1 es una propuesta anterior: menciona Urgent pero no confirma aprobación
ni implantación y no está reconciliada con T1.
D2 describe otro proyecto con New/Assigned/Resolved y avisos por correo;
no es documentación de este caso.
Necesito que la revisión [mi criterio concreto].
Explica qué puede mantenerse, qué incertidumbre debe declararse
y qué habría que verificar antes de usar la conclusión.
No conviertas Urgent en estado actual ni afirmes que jamás existió.
No importes reglas de D2. Devuelve versión revisada y justificación.
```

**P5. Contrasta con autoría visible.** Si eliges esta capa para la cuarta consulta opcional, envíala en chat B. Si reservas la consulta para avanzado o no hay acceso, redacta una revisión humana marcada. Conserva texto previo y posterior.

**P6. Decide con el criterio de P3.** ¿La revisión separa descripción actual, propuesta histórica y duda? ¿Ha convertido una incertidumbre en respuesta? Acepta, ajusta o rechaza y explica qué debe verificarse después.

### Comprobación y bifurcaciones

- Si concluye “Urgent nunca existió”, pide o prepara el respaldo: D1 no permite afirmarlo.
- Si incorpora New/Assigned/Resolved, revisa alcance de D2.
- Si mantiene “según T1”, puede ser correcto; no obligues a cambiar una frase ya bien acotada.
- Si dice “todo es incierto”, distingue lo descrito por T1 de lo que D1 no confirma.

**Salida:** registros P1–P6. Una fuente no confirmada no invalida todo ni se vuelve verdad por estar en el contexto.

[Volver al índice](#indice)

<a id="avanzado"></a>
## 7. Avanzado · Transferir la interacción sin historial invisible

### Situación y reto

Otra persona no verá chat B. Debes preparar un solo mensaje para continuar el análisis. El reto es preservar significado y revisión; un máximo de 180 palabras es una restricción didáctica secundaria, no un límite de Claude ni garantía de menor consumo.

### Recorrido guiado

**A1. Identifica las piezas que no perderías.** Para cada una, explica qué falla si desaparece: necesidad, estado actual pertinente, pendientes, tarea y salida. Lee también D1, definido en la sección 6, aunque no realices profundización. Decide cómo tratar esa incertidumbre para el uso que darás al mensaje; no hace falta completar P1–P6 para seguir esta capa.

**A2. Prepara V0 autocontenida.** No “como antes”, “esto” sin antecedente ni soluciones de R3 como hechos. Incluye límites y una salida revisable. Puedes redactar primero completo y después retirar redundancia.

**A3. Audita la reducción.** Compara con tu plantilla inicial: qué retiraste, por qué, qué condición podría perderse y para qué uso aceptarías V0. No borres algo esencial solo para cumplir longitud.

**A4. Establece controles previos.** Para estos riesgos, define señal y acción: Urgent como hecho, ausencia de cambios afirmada sin análisis y pérdida del objetivo de priorización/consulta.

**A5. Contrasta V0.** Si no has usado la cuarta consulta y hay disponibilidad, abre una conversación nueva y ejecuta una vez V0. Registra que no estás reproduciendo exactamente las condiciones de chat B. Si ya usaste la ampliación o no puedes ejecutar, analiza estos dos fragmentos construidos con tus controles:

- X: «Añadiremos Urgent y pasaremos a ese estado los casos urgentes; el responsable tendrá un dashboard».
- Y: «La descripción actual indica Open/Closed; la urgencia no tiene representación acordada. Hay que aclarar sus reglas y la consulta del responsable antes de decidir si cambia el modelo de estados».

**A6. Construye V1 y decide su uso.** Conserva V0 y registra qué cambiaste o por qué la mantienes. Identifica el fragmento de V0 relacionado con cada revisión; si una información falta por completo, anota «ausente en V0». Explica qué no puede decidirse con la salida obtenida o los fragmentos revisados. Etiqueta simulación cuando corresponda.

### Comprobación y bifurcaciones

Si una salida cumple el formato pero carece de respaldo, la estructura no la valida. Si V0 ya preserva lo necesario, mantenerla con evidencia es válido. Si la versión breve pierde contexto decisivo, retírala de su uso previsto o recupera la información aunque haya que replantear esa restricción; no fuerces equivalencia.

**Salida:** piezas y función, V0, comparación, controles, salida real o simulación identificada y V1 con decisión. No solo un prompt corto.

[Volver al índice](#indice)

## 8. Gestión del acceso y las variaciones

La ruta principal utiliza tres mensajes. Hay una sola ampliación ejecutable por defecto: elige profundización o avanzado para la cuarta consulta; la otra capa puede prepararse y contrastarse sin ejecución adicional, con autoría identificada.

Si el acceso se interrumpe, utiliza una ejecución real observada en clase y marca esa ruta. Si nadie puede ejecutar, abre la [resolución vigente](04_LAB2_resolucion.md), distribuida en el paquete local. Sus ejemplos de R1–R3 permiten continuar como contingencia simulada: no equivalen a ejecución propia. No se necesitan capturas o datos por crear. No regeneres buscando una “respuesta mejor” y no prometas cuotas por número de mensajes.

## 9. Cierre antes de la ficha

La base termina con comparación, plantilla y revisión de R3, no con copiar sus frases. La profundización debe mostrar tratamiento de incertidumbre. Avanzado debe demostrar transferencia y controles, no solo brevedad. En la reflexión revisa una decisión propia y conserva su antes/después.

<a id="ficha"></a>
## 10. Ficha única guiada

### Condiciones

- Asistente/modelo/fecha y funciones conocidas:
- Cambios entre chats A/B:
- Ruta propia/observada/simulada por tramo:
- R1 guardada en: ____; R2: ____; R3: ____.

### Base A · Antes de añadir T1

| Registro | Fragmento real o ausencia en R1 | Qué afirma/pregunta | F1–F3 o ausencia | Mi decisión provisional |
| -------- | ------------------------------- | ------------------- | ---------------- | ----------------------- |
| B1-A     |                                 |                     |                  |                         |
| B1-B     |                                 |                     |                  |                         |

### Base B · Comparación

| Aspecto           | Fragmento R1 | Fragmento R2 | Fuente/ausencia | Igualdad/diferencia observada | Consecuencia para el uso |
| ----------------- | ------------ | ------------ | --------------- | ----------------------------- | ------------------------ |
| Datos actuales    |              |              |                 |                               |                          |
| Impactos          |              |              |                 |                               |                          |
| Pendientes        |              |              |                 |                               |                          |
| Supuestos/límites |              |              |                 |                               |                          |

- Lo que T1 permite contrastar:
- Cautela que ya hacía falta sin T1:
- Lo que no demuestra esta comparación:

### Base C · Siete decisiones antes de enviar R3

| Campo               | Contenido o selección concreta | Razón que permite revisarlo |
| ------------------- | ------------------------------ | --------------------------- |
| Petición            |                                |                             |
| Contexto incluido   |                                |                             |
| Justificación       |                                |                             |
| Contexto excluido   |                                |                             |
| Límites             |                                |                             |
| Salida solicitada   |                                |                             |
| Comprobación humana |                                |                             |

- Campo que cubre el prompt de apoyo y cómo:

- Campo que resuelvo fuera del prompt o aspecto que necesita adaptación:

- Línea que cambio/añado y motivo, o justificación de enviarlo tal cual:

- Mensaje efectivamente enviado y condición propia, si existe:
  
  | Control               | Fragmento R3 | Respaldo/ausencia | Qué permite o no | Mi acción |
  | --------------------- | ------------ | ----------------- | ---------------- | --------- |
  | B3-Dato1              |              |                   |                  |           |
  | B3-Dato2              |              |                   |                  |           |
  | B3-Hipótesis/pregunta |              |                   |                  |           |
  | B3-Límite             |              |                   |                  |           |

- Evaluación de la estructura solicitada: ¿ayuda a localizar respaldo y qué incumple, si procede?:

- Decisión de uso y pendientes: resume en 3–5 líneas los datos respaldados, las decisiones abiertas y las comprobaciones necesarias antes de concretar el impacto. No es otro entregable ni requiere otra consulta.

### P · Profundización

| P1. Documento | Qué afirma | Alcance/estatus | Qué NO acredita | Tratamiento y razón |
| ------------- | ---------- | --------------- | --------------- | ------------------- |
| T1            |            |                 |                 |                     |
| D1            |            |                 |                 |                     |
| D2            |            |                 |                 |                     |

- P2. Frase de R3 y por qué revisarla:
- P3. Qué conservar, qué hacer visible y criterio de éxito:
- P4. Prompt preparado completo:
- P5. Consulta real / revisión humana identificada y guardada:
  
  | P6. Antes | Después | ¿Preserva T1? | ¿Hace visible incertidumbre? | ¿Importa reglas ajenas? | Decisión y verificación pendiente |
  | --------- | ------- | ------------- | ---------------------------- | ----------------------- | --------------------------------- |
  |           |         |               |                              |                         |                                   |

### A · Avanzado

| A1. Pieza de contexto | Por qué hace falta | Riesgo de retirarla |
| --------------------- | ------------------ | ------------------- |
|                       |                    |                     |

- A2. V0 autocontenida:
  
  | A3. Qué retiro | Por qué | Qué riesgo controlo o límite acepto |
  | -------------- | ------- | ----------------------------------- |
  |                |         |                                     |

| A4. Riesgo                     | Señal en la salida | Acción humana |
| ------------------------------ | ------------------ | ------------- |
| Urgent como hecho              |                    |               |
| Descartar cambios sin análisis |                    |               |
| Omitir objetivo                |                    |               |

- A5. Condiciones de consulta/simulación y salida o fragmentos analizados:
  
  | A6. Fragmento V0 o ausencia | Control aplicado | Evidencia observada | Mi decisión | Cambio en V1 o razón de conservar |
  | --------------------------- | ---------------- | ------------------- | ----------- | --------------------------------- |
  |                             |                  |                     |             |                                   |

- V1 final y alcance de utilización:

- Qué sigue pendiente y por qué:

### Reflexión final

- Decisión de contexto inicial:
- Qué mostró una respuesta real, si hubo ejecución:
- Decisión final y evidencia:
- Qué no atribuyo causalmente a este ejercicio:

[Volver al índice](#indice)
