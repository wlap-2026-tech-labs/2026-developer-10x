# Lab 2 · Contexto y revisión — alternativa reducida

Utiliza esta alternativa en lugar del Lab 2 original durante esta práctica. No necesitas completar ambos documentos ni la ficha Excel. Trabajarás con tres mensajes y guardarás tres notas breves.

## 1. Preparación

- El caso es ficticio y todo el material necesario está incluido.
- Utiliza el asistente autorizado.
- Abre un documento o nota donde escribir tres observaciones.
- Conserva las conversaciones para consultar las respuestas.
- Mantén el mismo asistente y modelo entre A y B si está disponible; si cambia, anótalo.

## 2. Primera petición · Contexto funcional

«Abre una conversación nueva, que llamaremos chat A. Copia y envía este mensaje completo.»

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

Lee R1 y guarda tu primera nota:
¿Qué pregunta de la respuesta te ayudaría a aclarar la necesidad con negocio?
Si no encuentras una pregunta útil, escribe tú una a partir de la información pendiente.
Basta con una o dos frases.

## 3. Segunda petición · Añadir contexto técnico

«Abre otra conversación nueva, que llamaremos chat B. No continúes en el chat A. Copia y envía este mensaje completo.»

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

Lee R2 y guarda tu segunda nota:
Señala una afirmación de la respuesta que puedas comprobar con T1 y el dato que la respalda.
Si la respuesta no aprovecha T1, señala un dato técnico relevante que haya dejado sin utilizar.
Basta con una o dos frases.

No necesitas encontrar diferencias ni declarar que R2 es mejor que R1. Dos respuestas no demuestran que todas sus diferencias se deban al contexto.

## 4. Tercera petición · Acotar el análisis

«Continúa en el chat B. Antes de enviar el siguiente mensaje, localiza la frase que indica que todavía no está decidido cambiar los estados.»

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

Lee R3 y guarda tu tercera nota:
Elige una conclusión que llevarías a la conversación con el equipo técnico e indica qué falta confirmar antes de utilizarla.
Si ninguna conclusión te parece utilizable, señala una y qué habría que corregir o comprobar.
Basta con una o dos frases.

Esta tercera petición cambia la tarea y las instrucciones y utiliza el historial del chat B. Su resultado no se explica únicamente por disponer de más contexto.

## 5. Tus tres notas

1. Pregunta útil para negocio:
   
2. Afirmación respaldada por T1 y dato que la respalda:
   
3. Conclusión para el equipo técnico y comprobación pendiente:

Escribe aquí tus notas, o consérvalas en tu documento si ya las has escrito. No las dupliques. Si seguiste alguna de las alternativas indicadas, registra esa observación en el apartado correspondiente.

## 6. Puesta en común y problemas de acceso

Comparte una de tus tres notas cuando lo indique el instructor.

Si no puedes ejecutar los mensajes, sigue una ejecución compartida por el instructor y realiza las mismas tres notas. Indica que has trabajado con una ejecución observada.
