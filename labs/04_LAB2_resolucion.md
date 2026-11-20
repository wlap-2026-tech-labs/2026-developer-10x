# Lab 2 · Resolución guiada de base, profundización y avanzado

Los ejemplos siguientes son construidos, no ejecuciones ni salidas garantizadas. Se revisa el contenido recibido realmente; una respuesta diferente no es un fallo automático.

## Base A · R1 potencial y primer criterio

### Ejemplo construido

> La petición puede afectar a la ordenación y a la información de seguimiento. Faltan criterios de urgencia, responsabilidad y necesidades de consulta. Puede estudiarse un atributo de prioridad, sin que esté decidida su representación. No se describen estados o datos para concretar cambios.

| Registro                    | Análisis                                                                                                                                                            |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| B1-A, ordenación            | “La petición puede afectar a la ordenación” se relaciona con F1/F2; no acredita atención efectiva.                                                                  |
| B1-B, ausencia de criterios | “Faltan criterios de urgencia, responsabilidad y necesidades de consulta”: F3 deja esos puntos abiertos. Conservar como ausencia legítima que da lugar a preguntas. |

La posibilidad de estudiar un atributo también puede analizarse como propuesta, sin sustituir el registro de pregunta/ausencia que pide B1-B.

Si R1, en vez de proponer, pregunta por datos, la revisión puede valorar que identifica una ausencia legítima. Si prescribe “crear Priority”, registrar prescripción sin respaldo.

**Insuficiente:** “no tiene contexto”. Sí tiene F1–F3; hay que decir qué puede y qué no puede fundamentar.

## Base B · R2 potencial y comparación

### Ejemplo construido

> T1 describe Status con Open/Closed y ausencia de atributo de prioridad. La necesidad podría afectar selección/ordenación e información consultada. No se puede decidir crear un campo o estado antes de definir urgencia y su gestión.

| Aspecto    | R1 potencial                         | R2 potencial                  | Consecuencia                                         |
| ---------- | ------------------------------------ | ----------------------------- | ---------------------------------------------------- |
| Datos      | No identifica estados                | Cita Open/Closed              | Más afirmaciones actuales contrastables con T1.      |
| Impacto    | Propone estudiar un atributo         | No prescribe representación   | Revisar el estatus, no decidir ganador por longitud. |
| Pendientes | Criterio, responsabilidad y consulta | Siguen pendientes             | T1 no resuelve negocio.                              |
| Límite     | No conoce modelo                     | Reconoce que no decide cambio | Puede ser útil para un análisis más acotado.         |

**Conclusión limitada:** T1 aporta datos que pueden utilizarse y verificarse. No demuestra que “añadir contexto mejora siempre” ni que una diferencia provenga solo de ese cambio.

**Alternativa válida:** si R2 omite T1 pero sigue siendo pertinente, explicar si falta una conexión importante para el uso. Si es más prescriptiva, revisar esa regresión. No descartar lo ocurrido porque no coincide con la guía.

## Base C · Plantilla y tercera interacción

| Campo             | Referencia posible                                                                                                     | Razón                                                                                                       |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| Petición          | Impacto de priorizar urgentes en estados                                                                               | Acota objeto distinto de una solución completa.                                                             |
| Contexto incluido | F1–F3/T1 en chat B                                                                                                     | Necesidad, estados y límites disponibles.                                                                   |
| Justificación     | Orden actual y Open/Closed; urgencia no definida                                                                       | Permite contrastar sin inventar modelo futuro.                                                              |
| Contexto excluido | Propuestas de R2 como hechos; R2 sigue en el historial de chat B y R1 no está en ese chat salvo copia del participante | No son documentación del sistema. El mensaje puede indicar cómo tratarlas, pero no las borra del historial. |
| Límites           | No hay criterio/actor/consulta acordados                                                                               | Evita cerrar decisión.                                                                                      |
| Salida            | Afirmación, respaldo, impacto y pregunta                                                                               | Facilita revisión de contenido.                                                                             |
| Comprobación      | Contrastar datos con T1 y propuestas con alcance                                                                       | Decide qué hacer con lo recibido.                                                                           |

### Cómo la plantilla influye en el mensaje

Ejemplo: el prompt de apoyo cubre “Salida solicitada” con sus cuatro columnas. La “Comprobación humana” se ejecuta fuera del mensaje. Si R2 ha propuesto un panel como si estuviera acordado, puede añadirse:

```text
La alternativa de panel que has propuesto en R2 no es un hecho del expediente
ni un acuerdo. No la uses como descripción confirmada del sistema.
```

Se registra la modificación y su motivo. Si no hubo ese supuesto, no copiar esa línea por obligación. Mantener el prompt íntegro es válido si el participante justifica que refleja sus decisiones y deja fuera de él las acciones humanas de revisión.

### R3 potencial, construida

| Afirmación                         | Respaldo | Impacto posible                              | Pregunta                                                 |
| ---------------------------------- | -------- | -------------------------------------------- | -------------------------------------------------------- |
| Status tiene Open/Closed           | T1       | No determina representación futura           | ¿Cómo se relacionaría urgencia con el ciclo de atención? |
| No hay prioridad                   | T1       | Analizar cómo representar urgencia           | ¿Quién la determina y si cambia?                         |
| Se pide información al responsable | F2       | Revisar qué necesita consultar               | ¿Qué debe poder comprobar?                               |
| No hay transiciones descritas      | T1       | No puede concretarse una transición afectada | ¿Qué reglas actuales relevantes deben documentarse?      |

Cierre potencial: no hay base para añadir Urgent ni asegurar que no cambiará ningún estado.

### Registro de referencia

- B3-Dato1: Open/Closed coincide con T1.
- B3-Dato2: ausencia de prioridad coincide con T1.
- B3-Hipótesis: relación con ciclo de atención es pregunta, no regla aportada.
- B3-Límite: no prescribe ni descarta modificación; útil para análisis preliminar.
- Estructura: las columnas ayudan a separar afirmación y respaldo; hay que verificar cada fila porque tener tabla no prueba corrección.
- Acción: conservar el borrador, confirmar preguntas antes de especificar; no usar como aprobación técnica.

**Insuficiente:** “la tabla es correcta”. El formato puede contener datos falsos: revisar filas.
**Otra resolución válida:** una respuesta sin tabla pero sustantivamente prudente puede ser aprovechable, aunque deba registrarse incumplimiento de la estructura solicitada.
**Si responde solo “falta información”:** valorar prudencia, pero pedir o preparar relación con datos actuales. No forzar solución para darle apariencia de profundidad.
**Si prescribe o descarta cambios sin razones:** señalar qué fundamento falta. Una hipótesis etiquetada no es una invención por sí sola.
**Si se parece a R2:** evaluar si responde a la pregunta concreta y registrar lo observado sin dar por demostrado fallo o éxito.

## P · Profundización desarrollada

### P1. Clasificación documental

| Documento | Qué afirma                                               | Qué no acredita                                   | Tratamiento posible                          |
| --------- | -------------------------------------------------------- | ------------------------------------------------- | -------------------------------------------- |
| T1        | Descripción actual Open/Closed, sin prioridad            | Histórico completo o verdad de un sistema externo | Base actual del ejercicio, con su alcance.   |
| D1        | Se planteó Urgent, sin confirmar aprobación/implantación | Que exista hoy o que jamás existiera              | Separar como incertidumbre relevante.        |
| D2        | Reglas de otro proyecto                                  | Aplicabilidad a este caso                         | Excluir como hecho; no importar sus estados. |

### P2. Frase seleccionada

Ejemplo de frase que una R3 real podría contener, pero que no figura
en la R3 potencial de Base C: “El sistema solo tiene Open y Closed”.
Puede acotarse como “T1 describe…”, sin resolver por intuición
el histórico de D1.

### P3. Criterio previo

Preservar el dato de T1, declarar incertidumbre D1 y no importar D2. No convertir la nota en implantación ni hacer incierto todo el expediente.

### P4. Consulta completa posible

```text
Revisa esta afirmación de tu respuesta anterior:
«El sistema solo tiene Open y Closed».
T1 describe actualmente Open/Closed y ausencia de atributo de prioridad.
D1 es una propuesta anterior: menciona Urgent pero no confirma aprobación
ni implantación y no está reconciliada con T1.
D2 describe otro proyecto con New/Assigned/Resolved y avisos por correo;
no es documentación de este caso.
Necesito que la revisión preserve el alcance de T1 y separe lo no confirmado.
Explica qué puede mantenerse, qué incertidumbre debe declararse
y qué habría que verificar antes de usar la conclusión.
No conviertas Urgent en estado actual ni afirmes que jamás existió.
No importes reglas de D2. Devuelve versión revisada y justificación.
```

Aquí el criterio ya está cumplimentado como ejemplo de resolución. El descriptivo conserva el campo editable [mi criterio concreto] para que cada participante incorpore su propia decisión.

### P5. Revisión potencial, no ejecutada

> «Según la descripción actual T1, Status contiene Open y Closed. D1 recoge una propuesta anterior sobre Urgent cuyo estado no está confirmado. Antes de utilizar esta conclusión como descripción exhaustiva o histórica, debe aclararse esa nota. D2 no es evidencia de este caso».

### P6. Antes/después y decisión

- Antes: afirmación absoluta sin alcance documental.
- Después: dato actual acotado y discrepancia visible.
- Conservación: no se cambia Open/Closed por Urgent.
- Verificación pendiente: aclarar qué ocurrió con la propuesta D1.
- Decisión: utilizar para análisis preliminar con esa salvedad, no cerrar inventario histórico.

**Insuficiente:** “T1 gana porque es más reciente”. Los documentos tienen distinto estatus y alcance, y D1 sigue sin aclararse.
**Otra resolución válida:** mantener “según T1…” si ya estaba escrito y añadir la nota de incertidumbre en otro apartado.
**Si la salida afirma que Urgent nunca existió:** falta evidencia; rechazar esa conclusión. **Si importa D2:** excluir la regla no aplicable. **Si solo dice “no sabemos nada”:** recuperar lo que T1 sí describe.

## A · Avanzado desarrollado

### A1. Piezas y función

Lee D1 en la sección 6 del descriptivo aunque no hayas realizado P1–P6. Esa lectura no obliga a completar la capa anterior.

| Pieza                               | Por qué conservarla                 | Riesgo de perderla                                          |
| ----------------------------------- | ----------------------------------- | ----------------------------------------------------------- |
| Necesidad                           | Da sentido al impacto               | Analizar estados en abstracto.                              |
| Orden actual                        | Conecta con funcionamiento descrito | Confundir cambio y situación base.                          |
| Open/Closed y ausencia de prioridad | Referencia técnica pertinente       | Inventar estados actuales.                                  |
| Pendientes/D1 cuando corresponda    | Acota certeza y alcance             | Convertir representación en acuerdo o borrar incertidumbre. |
| Tarea y salida                      | Hace revisable la petición          | Respuesta no orientada al uso.                              |

### A2. V0 posible, con margen bajo 180 palabras

```text
Caso ficticio: solicitudes ordenadas por fecha de creación, de más antigua
a más reciente. Se pide atender antes las urgentes y dar información al responsable.
T1 describe Status: Open/Closed, sin atributo de prioridad.
Faltan criterio de urgencia, quién lo determina, si cambia y qué debe consultar
el responsable. D1 propuso Urgent sin confirmar aprobación o implantación;
no lo trates como estado actual ni afirmes que jamás existió.
Analiza el posible impacto en estados. Separa datos descritos, hipótesis
y preguntas necesarias antes de decidir. No prescribas ni descartes cambios
sin análisis ni importes reglas de otros proyectos.
```

Si necesitas el conteo exacto, compruébalo en el editor; el ejemplo no acredita una medición del entorno. No incluye todo el modelo técnico porque el alcance es una pregunta acotada, no diseño completo.

### A3. Comparación con la preparación extensa

| Retirado                            | Motivo                                             | Límite                                                             |
| ----------------------------------- | -------------------------------------------------- | ------------------------------------------------------------------ |
| Lista completa de campos y API REST | No imprescindible para esta pregunta sobre estados | Reincorporar si otra tarea depende de arquitectura/datos.          |
| Texto íntegro de D2                 | Otro alcance                                       | Mantener exclusión de reglas ajenas si existe riesgo de confusión. |
| Historia de la conversación         | No constituye fuente actual                        | Conservar solo acuerdos que estén realmente confirmados.           |

La selección puede ser distinta si se justifica. No existe equivalencia universal entre un prompt corto y otro largo.

### A4. Controles previos

| Riesgo                          | Señal                                          | Acción                                   |
| ------------------------------- | ---------------------------------------------- | ---------------------------------------- |
| Urgent como hecho               | Existencia o transición afirmada               | Contrastar T1/D1 y reetiquetar/aclarar.  |
| No cambiar estados sin análisis | Conclusión cerrada sin razones                 | Pedir fundamento y preguntas pendientes. |
| Perder objetivo                 | Inventario de campos sin priorización/consulta | Recuperar relación necesidad/impacto.    |

### A5. Evaluación de salida o fragmentos de contingencia

X introduce estado, transición y panel no acordados: no utilizar como especificación. Y conserva descripción y abre preguntas: utilizable como análisis preliminar, aunque aún no prepara la implementación.

Si hubo salida real, aplicar los mismos controles a sus frases, no declarar equivalencia con X/Y. Un chat nuevo no reproduce el historial de R3; identificar ese cambio de condición.

### A6. V1 y decisión

| Fragmento V0                                      | Control                 | Evidencia potencial                             | Decisión                                              | Cambio o conservación                                                                         |
| ------------------------------------------------- | ----------------------- | ----------------------------------------------- | ----------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| “T1 describe Status: Open/Closed”                 | Urgent como hecho       | X introduce Urgent; Y mantiene alcance          | X no sirve como acuerdo; Y puede servir para análisis | Mantener el anclaje a T1, revisar la salida, no culpar automáticamente a la frase del prompt. |
| “No prescribas ni descartes cambios sin análisis” | Descarte sin fundamento | Y deja decisión abierta                         | Aceptar ese límite, no declarar validado diseño       | Puede conservarse si satisface el uso.                                                        |
| “Se pide atender antes…”                          | Pérdida de necesidad    | Si una salida omite el objetivo, falta conexión | Pedir o preparar vínculo necesidad/impacto            | Conservarlo explícito en V1.                                                                  |

- V1 puede conservar V0 si los controles no revelan ambigüedad material; explicar por qué.
- Si falta información del responsable, añadirla antes de reutilizar.
- Si la salida prescribe Urgent, no basta acumular prohibiciones: comprobar que contexto y alcance estaban claros y registrar el límite del resultado.
- Decisión: utilizar para preparar análisis; no como regla aprobada ni prueba de que la representación será independiente de estados.

**Insuficiente:** “lo hice más corto y funcionará mejor”.
**Más útil:** señalar qué se retiró, qué permanece, qué salida se revisó y para qué uso se acepta.
**Alternativa válida:** rechazar la versión breve para una tarea técnica más amplia porque faltaría información, manteniéndola solo para el análisis acotado.

## Criterios complementarios de revisión

Los siguientes ejemplos son construidos y orientativos. No documentan ejecuciones del instructor ni respuestas garantizadas.

### Ausencia de documentación no equivale a ausencia de funcionalidad

Una afirmación como «hoy no hay trazabilidad de transiciones» no está respaldada por T1. T1 indica que no se documentan reglas de transición; no acredita la inexistencia de reglas ni de registros históricos.

Condición de revisión posible, solo si aparece ese problema:

```text
No uses como hecho la afirmación de que no hay trazabilidad de transiciones:
T1 no permite concluirlo. Distingue ausencia de documentación y ausencia
de funcionalidad.
```

No es un cuarto mensaje obligatorio: puede añadirse a la tercera petición tras preparar las siete decisiones. La revisión posterior debe comprobar si la corrección se ha atendido y si se introducen nuevos supuestos.

### No convertir una alternativa en obligación

«Habría que añadir al menos un atributo» requiere revisión si después se contempla derivar urgencia de Category. La ausencia de atributo de prioridad es un dato; crear uno es una alternativa de diseño, no una consecuencia obligatoria.

Tampoco puede asegurarse que el impacto sea menor solo porque la urgencia no cambie durante la vida del ticket. El impacto depende de la solución y de los componentes afectados.

### Formular cuestiones sin aparentar conclusiones

En una tabla, es preferible «¿Priorizar exige cambiar los estados?» a un rótulo afirmativo como «Priorizar exige cambiar los estados», aunque las columnas siguientes lo cuestionen. Los fragmentos pueden circular separados de su contexto.

### No añadir verificaciones redundantes

El ejercicio establece que D2 pertenece a otro proyecto. Se excluye como evidencia del sistema sin exigir una comprobación adicional de esa pertenencia. La incertidumbre relevante es qué ocurrió con D1 y cómo se relaciona con la descripción de T1.

La fecha puede ayudar a interpretar documentos, pero no demuestra aprobación ni implantación. Un documento más reciente no convierte una propuesta en funcionamiento actual.

## Ejemplo complementario de avanzado: V0, controles y V1

Este ejemplo no añade consultas ni entregables. Si se empleó la cuarta consulta en profundización, se trabaja mediante contraste simulado y revisión humana identificada.

### V0 autocontenida

```text
Caso ficticio: solicitudes ordenadas por fecha de creación, de más antigua
a más reciente. Se pide atender antes las urgentes y permitir al responsable
comprobar qué está pasando.
T1 describe Status: Open/Closed, sin atributo de prioridad.
Faltan definición de urgencia, quién la determina, si cambia y qué necesita
consultar el responsable.
D1 menciona una propuesta anterior de Urgent, sin confirmar aprobación
ni implementación y sin reconciliar con T1.
Analiza el posible impacto de priorizar en los estados. Separa datos
aportados, hipótesis y preguntas para decidir.
No des por aprobado crear Urgent ni conservar necesariamente los estados
actuales. No confundas ausencia de documentación con inexistencia.
No escribas código.
```

Se conserva necesidad, estado actual pertinente, incertidumbres y tarea. Se retiran el historial y los campos que no resultan imprescindibles para esta pregunta acotada; deben recuperarse si cambia el uso. D2 no se incorpora porque describe otro proyecto.

### Controles y contraste simulado

| Riesgo | Señal | Decisión de referencia |
|---|---|---|
| Urgent como hecho | X propone añadir Urgent y un dashboard | No utilizar como compromiso ni especificación: no están acordados. |
| Descarte de cambios sin análisis | Una salida afirma que los estados no deben cambiar sin justificarlo | Mantener la decisión abierta y pedir fundamento. |
| Pérdida del objetivo | La salida solo enumera estados y olvida atención y consulta | Recuperar ambos objetivos antes de utilizarla. |

El fragmento Y del descriptivo conserva la descripción actual y las preguntas necesarias. Puede orientar un análisis preliminar; no aprueba el diseño. X/Y son fragmentos construidos, no ejecuciones de V0.

### V1 y decisión de uso

Conservar V0 y añadir:

```text
Presenta una tabla con: afirmación, respaldo o ausencia, impacto posible
y pregunta que permitiría decidir.
```

Razón del cambio: hacer explícita una estructura que facilite localizar el respaldo. La tabla no garantiza corrección. El contraste simulado no demuestra cómo responderá un chat nuevo.

Decisión: utilizar V1 para continuar un análisis acotado sin depender del historial. No utilizarla como especificación aprobada ni atribuirle una mejora de rendimiento no medida.

## Resultado útil: nota preliminar para la conversación técnica

Esta síntesis se escribe en el campo existente de decisión de uso. No requiere otra consulta ni un nuevo entregable.

### Ejemplo construido

> Según T1, Ticket tiene Status con Open/Closed y no tiene atributo de prioridad. Esto no obliga por sí solo a crear un campo ni a cambiar los estados. Antes de concretar el impacto debemos aclarar cómo se define y representa la urgencia y qué necesita consultar el responsable. También debemos verificar qué ocurrió con la propuesta Urgent de D1 y localizar la documentación relevante sobre reglas, API e integraciones. D2 no se usa como evidencia de este sistema. La nota prepara el análisis técnico; no aprueba una solución ni permite estimar todavía su implementación.

### Qué aporta al trabajo

- Separa el funcionamiento descrito de las alternativas futuras.
- Localiza decisiones funcionales que condicionan el análisis técnico.
- Identifica comprobaciones concretas en lugar de afirmar que «falta contexto».
- Permite preparar una conversación con el equipo técnico sin presentar un diseño prematuro.

No demuestra ahorro de tiempo, exactitud completa ni mejora general de productividad.

## Preguntas frecuentes

**¿Debo utilizar el mismo chat que en Lab 1?**
No. Lab 2 empieza con chat A nuevo. El segundo mensaje va en chat B nuevo y el tercero permanece en B.

**¿Más contexto garantiza una respuesta mejor?**
No. Permite contrastar más afirmaciones, pero la respuesta todavía puede introducir supuestos o ignorar datos.

**¿La ausencia de prioridad obliga a crear un campo?**
No. La representación depende de decisiones funcionales y técnicas todavía abiertas.

**¿Debo cambiar Open/Closed para representar urgencia?**
El expediente no permite decidirlo. Tampoco permite asegurar que los estados deban permanecer intactos.

**¿D1 invalida T1?**
No automáticamente. D1 registra una propuesta sin confirmar su destino. Hay que conservar el alcance de T1 y declarar esa incertidumbre.

**¿Debo investigar si D2 corresponde a este sistema?**
No en este ejercicio: ya se establece que pertenece a otro proyecto. No se importan sus estados ni notificaciones.

**¿Necesito ejecutar una quinta consulta para completar avanzado?**
No. Si la cuarta consulta se utilizó en profundización, avanzado puede completarse con los fragmentos simulados y una revisión humana de V0/V1, identificando esa ruta.

**¿Qué resultado me llevo?**
Una nota preliminar con datos respaldados, decisiones abiertas y verificaciones necesarias para conversar con el equipo técnico. No una solución implementable ni una estimación aprobada.

## Reflexión y límites

Debe poder reconstruirse qué información se proporcionó, qué respondió la IA y qué decidió la persona. Más contexto o formato no garantizan exactitud. La comparación no aísla todas las causas y las resoluciones no acreditan ejecuciones. Solo una prueba real con registros permite hablar del comportamiento observado en ese entorno.


Transferir una interacción no consiste solo en resumirla: exige conservar los hechos, las incertidumbres y los controles necesarios para continuar sin inventar acuerdos.
