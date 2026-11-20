# Lab 1 · Resolución guiada de base, profundización y avanzado

Esta guía no contiene respuestas reales de Claude. Los textos potenciales son construidos para mostrar el razonamiento. Una respuesta distinta puede ser válida; no se busca reproducirla. Leer después del intento salvo contingencia identificada.

## Base A · Ejemplo completo de R1 y primera revisión

### R1 potencial, construida

> Primero hay que definir qué se considera urgente y quién puede modificarlo. Propongo mostrar las urgentes antes que las demás y mantener antigüedad para los empates. El supervisor cambiará la prioridad y el responsable consultará un panel con tiempo de resolución. Deben validarse las necesidades de consulta y probar el criterio con solicitudes representativas antes de implantar.

### Registro de referencia

| Registro | Fragmento                                                                                         | Qué afirma y respaldo                                                              | Estatus                                                           | Decisión                                                                        |
| -------- | ------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ----------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| R1-A     | Definir qué se considera urgente                                                                  | F3 identifica la carencia                                                          | Pregunta/tarea pertinente                                         | Conservar para aclaración.                                                      |
| R1-B     | El supervisor cambiará la prioridad y el responsable consultará un panel con tiempo de resolución | No hay supervisor, permiso, panel ni esa medida en F1–F3; F2 solo pide visibilidad | Supuesto y solución presentados como decididos                    | Reformular responsabilidad como pendiente y el panel como opción por validar.   |
| R1-C     | Deben validarse las necesidades de consulta                                                       | F3 deja abierto qué necesita consultar el responsable                              | Pregunta pendiente pertinente, expresada como tarea de validación | Conservar: es la aclaración que debe preceder a definir el soporte de consulta. |

El desempate por antigüedad puede conservarse si permanece explícitamente como propuesta. F1 no aprueba todo criterio futuro.

**Valoración inicial posible:** útil para preparar una conversación, pero no compartible íntegramente como especificación porque incorpora decisiones no aportadas.

### Insuficiente / suficiente / alternativa

- Insuficiente: “alucina el supervisor”. No explica el respaldo ni el uso afectado.
- Más útil: “F3 no define quién determina urgencia; el texto no puede presentar al supervisor como acordado”.
- Alternativa válida: conservar supervisor como opción etiquetada y preguntar quién asumiría esa función, sin asegurar que exista.

Si R1 solo hace preguntas, puede valorarse que evita prescribir; revisar si cubre urgencia y consulta, no obligarla a proponer un panel.

## Base B · Auditar la auditoría

### R2 potencial, construida

> «El supervisor cambiará la prioridad» carece de respaldo en F1–F3: debe aclararse quién tiene esa función. «Mantener antigüedad para empates» está confirmado por F1. «Panel» es una propuesta a validar porque F2 solo pide visibilidad.

### Registro de referencia

| Registro         | Cita y respaldo                                              | Decisión humana                                                      |
| ---------------- | ------------------------------------------------------------ | -------------------------------------------------------------------- |
| R2-A, supervisor | La cita existe; F3 deja responsabilidad abierta              | Aceptar la corrección.                                               |
| R2-B, desempate  | La idea aparece en R1, pero F1 solo describe el orden actual | Matizar: puede proponerse, no está confirmado como desempate futuro. |

**Pre:** el borrador incluye una opción y algunos supuestos.
**Post:** mantengo esa valoración y añado que la auditoría también puede convertir un dato actual en una decisión futura.

**Insuficiente:** “R2 valida mi revisión”.
**Mejor:** identificar qué conclusión se acepta y cuál se matiza, con referencia exacta.

Si la auditoría real no comete ese error, no inventarlo. Pueden justificarse dos aceptaciones y mantener el criterio inicial.

## Base C · Dirigir y comprobar la revisión

### Condición humana de ejemplo

> Mantén el desempate como alternativa; F1 solo describe el orden actual. No presentes supervisor ni panel como acordados.

### R3 potencial, construida

> A. La información aportada describe ordenación por antigüedad y una petición para atender antes urgentes y facilitar seguimiento.
> B. Se propone aclarar criterios y responsabilidades, analizar si el cambio afecta presentación y selección de atención y acordar la información que se consultará. Mantener antigüedad como desempate es una alternativa por confirmar.
> C. Falta definir urgente, quién lo determina, si cambia y qué necesita comprobar el responsable.
> D. Se han retirado supervisor y panel como prescripciones, manteniendo la necesidad de definir responsabilidad e información.

### Registro de referencia

| Control      | Antes                       | Después                     | Evaluación                                                            |
| ------------ | --------------------------- | --------------------------- | --------------------------------------------------------------------- |
| Cambio       | Supervisor decidido         | Responsabilidad por aclarar | Cambia el estatus de manera pertinente.                               |
| Conservación | Definir urgente             | Sigue como pregunta         | Conserva información necesaria.                                       |
| Regresión    | Antigüedad como alternativa | Sigue etiquetada            | No se ha perdido esa condición; revisar que no se contradiga después. |

**Decisión:** utilizar para preparar preguntas, contrastando cada afirmación actual con F1–F3 y marcando alternativas antes de compartir. No usar como solución aprobada.

**Insuficiente:** R3 añade “todo sujeto a validación” pero sigue afirmando que un supervisor decidirá. La advertencia final no corrige necesariamente la prescripción.

**Alternativa válida:** mantener un panel como opción explícita si se relaciona con una pregunta de consulta; no tiene que desaparecer toda propuesta.

**Si no cambia:** comprobar si la condición ya estaba atendida. **Si empeora:** registrar lo perdido y utilizarlo como objeto de profundización. No asumir que tercera respuesta es mejor por ser posterior.

## P · Profundización desarrollada

### P1. Punto de partida

Fragmento de una R3 hipotética distinta de la utilizada en Base C
(aquella ya mantenía la antigüedad como alternativa):

> «Mantendremos siempre antigüedad dentro de cada grupo; así preservaremos la regla actual y el responsable podrá controlar la atención».

### P2. Descomposición

| Afirmación                   | Estatus                                        | Tratamiento                          |
| ---------------------------- | ---------------------------------------------- | ------------------------------------ |
| Siempre antigüedad por grupo | Regla futura no acordada                       | Mantener solo como propuesta.        |
| Preserva regla actual        | F1 describe antigüedad, pero no los grupos     | Precisar alcance de la continuidad.  |
| Permite controlar atención   | No se define qué consulta ni atención efectiva | No afirmarlo como efecto demostrado. |

### P3. Criterio previo

- Éxito: distinguir ordenación actual, opción de desempate y visibilidad pendiente.
- No perder: la posibilidad de aprovechar antigüedad como criterio.
- Pendiente: acuerdo sobre urgencia, desempate y consulta.

### P4. Mensaje de revisión completo posible

```text
Revisa solo este fragmento de R3:
«Mantendremos siempre antigüedad dentro de cada grupo; así preservaremos
la regla actual y el responsable podrá controlar la atención».
Mi observación: F1 describe antigüedad, pero no grupos futuros; F3 no define
qué necesita consultar el responsable.
Conserva la opción de antigüedad y mejora la separación entre hechos,
alternativas y resultados aún no comprobados.
Se considerará útil si no da por acordado el desempate ni el seguimiento.
No resuelvas por tu cuenta las preguntas pendientes.
Devuelve versión revisada y motivo del cambio.
Si mi observación es incorrecta, explícalo con los insumos.
```

### P5. Revisión potencial — no ejecución

> «La ordenación actual es por antigüedad. Puede estudiarse mantenerla como desempate cuando se defina la urgencia. Antes de concluir qué permite comprobar al responsable, debe aclararse su necesidad de información y cómo se revisará».

### P6. Evaluación pre/post

| Criterio                | Resultado                                                           |
| ----------------------- | ------------------------------------------------------------------- |
| No prescribir desempate | Cumplido en este ejemplo.                                           |
| Conservar opción útil   | Conserva antigüedad como alternativa.                               |
| No prometer seguimiento | Lo convierte en cuestión de análisis.                               |
| Límite                  | No especifica solución, por lo que no sirve todavía para implantar. |

**Decisión:** aceptar para análisis preliminar. Si la revisión fuera humana, se identifica como tal.

**Resolución insuficiente:** “Quizá mantendremos siempre antigüedad y el panel sujeto a validación”. Sigue mezclando universalidad, solución nueva y cautela genérica.

**Otra resolución válida:** formular una pregunta sobre desempate y no recomendar opción todavía, explicando por qué ese uso requiere más neutralidad.

**Si el texto inicial era correcto:** el éxito puede consistir en mantenerlo y añadir qué verificación necesita, sin modificar sus hechos. **Si la IA discrepa:** contrastar si la evidencia justifica el desacuerdo; no es obligatorio aceptar nuestra corrección por ser humana.

## A · Avanzado desarrollado

### A1. Riesgo

Una frase de R3 o de la revisión posterior a P6, como “implantar clasificación de prioridad”, puede salir del contexto y parecer un compromiso, aunque antes se presentara como borrador. Si la cautela ya es correcta, el objetivo es preservarla.

### A2. Clasificación para comunicar

| Comunicar ahora         | Alternativa                        | Pendiente                                         | Respaldo y razón                                                                                               |
| ----------------------- | ---------------------------------- | ------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| Objetivo y orden actual | Mantener antigüedad como desempate | Definición de urgente, responsabilidad y consulta | F1/F2 respaldan objetivo y estado descrito; F1 no acuerda desempates futuros; F3 deja abiertos los pendientes. |

La presión no añade acuerdos. Tampoco obliga a bloquear toda comunicación.

### A3. Texto humano V0 de ejemplo

> Podemos preparar para mañana un análisis de la necesidad y de las decisiones pendientes. La información actual describe ordenación por antigüedad y una petición de priorizar urgentes y facilitar seguimiento. Podemos presentar alternativas condicionadas, pero no comunicar como acordados campos, roles o pantallas. Para concretar el cambio deben aclararse urgencia y necesidades de consulta y confirmar quién puede decidir. El documento distinguirá objetivo, propuesta y cuestiones abiertas, sin prometer una implantación aún no definida.

### A4. Mensaje completo de revisión posible

```text
Revisa esta comunicación antes de compartirla:
«Podemos preparar para mañana un análisis de la necesidad y de las decisiones
pendientes. La información actual describe ordenación por antigüedad y una
petición de priorizar urgentes y facilitar seguimiento. Podemos presentar
alternativas condicionadas, pero no comunicar como acordados campos, roles
o pantallas. Para concretar el cambio deben aclararse urgencia y necesidades
de consulta y confirmar quién puede decidir. El documento distinguirá objetivo,
propuesta y cuestiones abiertas, sin prometer una implantación aún no definida».
Contrástala con F1–F3 de esta conversación.
Necesito conservar un avance comunicable.
Necesito evitar compromisos de solución no acordados.
Señala compromisos no respaldados y también bloqueos innecesarios.
Devuelve observaciones con fragmento, una versión propuesta y sus límites.
No inventes autoridad, reglas o fechas de implantación.
```

### A5. Cómo evaluar respuesta o contingencia

Si se utiliza el fragmento ficticio de la actividad (“Confirmamos… Alta/Media/Baja”), se rechaza su compromiso no respaldado. Puede reformularse como alternativa por analizar, pero no basta añadir “validaremos después”.

Después se aplican los dos criterios también a la propia V0 y se escribe su revisión humana, o se justifica conservarla. Ese texto, no el fragmento ficticio aislado, proporciona el después para A6.

Una salida real puede mantener V0 con pequeños ajustes: no exigir cambios artificiales. Si propone “no comunicar nada”, comprobar qué dato obliga a ese bloqueo; probablemente aún hay objetivo y preguntas comunicables. Si añade reglas o fechas, no aceptarlas como acuerdos sin respaldo.

### A6. Pre/post posible

- Pre: recomendación para conversación de aclaración.
- Post: comunicación de objetivo, alternativas y pendientes, no anuncio de implantación.
- Texto final: V0 puede mantenerse si satisface los dos criterios; registrar por qué. Si no se ejecutó, identificar la revisión de V0 como humana.
- Límite: no se conoce quién aprueba ni se han acordado reglas; sigue pendiente.

**Resolución insuficiente:** “Claude ha validado la comunicación”.
**Más útil:** “Mantengo estas frases porque no convierten alternativas en compromisos y permiten comunicar el análisis disponible”.
**Alternativa válida:** texto más breve que conserve alcance y pendientes, sin obligación de usar la misma redacción.


## Criterios de revisión y preguntas frecuentes

Estos criterios son orientaciones generales. Los ejemplos de esta guía son construidos y no describen una ejecución concreta.

### No descrito no equivale a excluido

Si F3 indica que no se describen pantallas, asignación, notificaciones o reglas de servicio, no puede deducirse que existan, que no existan o que estén excluidos. Corresponde preguntar por su situación y pertinencia antes de fijar el alcance.

Una auditoría puede detectar esta confusión y reproducirla en otro apartado. Cada observación debe contrastarse por separado; no se acepta o rechaza toda la auditoría en bloque.

### Explorar alternativas sin imponer requisitos

El consultor puede plantear ejemplos como preguntas de aclaración sin esperar a que el solicitante los mencione espontáneamente. Debe distinguir entre información necesaria, alternativas de solución y acuerdos.

Ejemplo construido de revisión:

- Antes: «Los ejemplos de estado, tiempos e historial solo entrarán si el solicitante los menciona».
- Después: «Podemos preguntar si necesita consultar situación actual, tiempos de espera o evolución. Estas opciones ayudan a aclarar la necesidad; no son requisitos ni soluciones acordadas».
- Criterio: conservar la exploración útil sin atribuir al solicitante necesidades no confirmadas.

La confirmación de una necesidad no aprueba por sí sola una solución ni su implementación. Qué información se necesita consultar y cómo ofrecerla son decisiones distintas.

### Revisar el cambio de uso

Una alternativa útil durante el análisis puede parecer un compromiso al trasladarla a una comunicación. La cautela debe acompañar a la afirmación concreta: añadir «pendiente de validación» al final no corrige automáticamente una prescripción anterior.

#### V0 construida para practicar la revisión

> La propuesta de cambio es priorizar las solicitudes urgentes y facilitar al responsable el seguimiento mediante información de estado, tiempos e historial. Antes de desarrollar, aclararemos qué significa urgente, quién lo determina y qué necesita consultar el responsable. El orden por antigüedad se mantendría dentro de cada grupo. Los detalles quedarán sujetos a confirmación.

#### Revisión de referencia

- Estado, tiempos e historial se adelantan a la confirmación de la necesidad de consulta.
- Mantener antigüedad por grupos es una alternativa, no un acuerdo. El condicional puede resultar insuficiente para comunicar ese estatus.
- «Los detalles» minimiza decisiones que todavía afectan a la solución.

#### V1 construida como alternativa de comunicación

> La necesidad expresada es atender antes las solicitudes urgentes y permitir al responsable comprobar qué está pasando. Actualmente, las solicitudes se ordenan por antigüedad. Para concretar el cambio debemos aclarar qué significa urgente, quién lo determina y qué implica atender antes. También debemos identificar qué necesita consultar el responsable. Podemos explorar alternativas de ordenación y consulta como apoyo a esa conversación. Todavía no están acordados los niveles de prioridad, el orden futuro ni funcionalidades como un historial. El siguiente paso es resolver estas preguntas antes de comprometer una solución.

Decisión de referencia: utilizar V1 para preparar la aclaración, no para anunciar funcionalidades aprobadas. Este ejemplo complementa la capa avanzada; no requiere otra consulta ni otro entregable.

### Preguntas frecuentes

**¿Puedo introducir una opción que no aparece en F1–F3?**
Sí, como pregunta o propuesta explícita y pertinente. No como hecho actual, necesidad confirmada o solución aprobada.

**¿Una propuesta sin respaldo es necesariamente un error?**
No. Hay que comprobar si se presenta como alternativa o se atribuye indebidamente al sistema o a un acuerdo.

**¿Debo aceptar la auditoría si cita F1, F2 o F3?**
No automáticamente. Comprueba la cita y si respalda la conclusión completa.

**¿El apartado «qué cambió» demuestra que la revisión es correcta?**
No. Contrasta también el contenido revisado: el resumen puede omitir contradicciones o describir cambios que no se han realizado.

**¿Confirmar una necesidad equivale a aprobar su implementación?**
No. Deben distinguirse necesidad, solución propuesta y decisión de implementación.

**¿Necesito otra consulta para corregir cada problema?**
No. Puedes hacer una corrección humana localizada y justificarla. Identifica su autoría y conserva el antes/después.

### Reflexión de cierre

Dirigir la IA es decidir qué conservar, qué reformular y para qué puede utilizarse el resultado. Revisar no consiste en eliminar todas las alternativas, sino en mantener claro su estatus. Una respuesta más concreta no está necesariamente más respaldada.

## Balance del lab

La evidencia de aprendizaje es cómo se dirige, contrasta y utiliza la interacción. La secuencia no garantiza mejores respuestas por número de turnos. La ejecución observada, la propia y la simulación se registran de forma distinta. La duración humana no se deduce de esta guía.
