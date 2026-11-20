# IA aplicada a la consultoría · Laboratorios S1

Materiales de la sesión 1: evaluar respuestas de IA y preparar contexto
para obtener resultados revisables.

Trabajaremos individualmente con un caso ficticio de solicitudes de
servicio técnico. El objetivo no es completar un diseño de sistema,
sino preparar conversaciones y decisiones profesionales con respaldo,
límites y comprobaciones explícitas.

## Empieza aquí

1. Abre el descriptivo del laboratorio que indique el instructor.
2. Elige cómo registrar tu trabajo: Excel o ficha Markdown incluida
   en el descriptivo. No tienes que completar ambos.
3. Sigue la ruta base y registra tus decisiones entre consultas.
4. Si terminas, continúa con las capas de profundización del descriptivo.
5. Conserva tu ficha para la reflexión y la continuidad de la formación.

Los descriptivos contienen los insumos y los pasos detallados.
Este README es el punto de entrada, no sustituye esas instrucciones.

## Materiales del participante

| Laboratorio | Instrucciones y ficha Markdown | Ficha Excel |
| --- | --- | --- |
| Lab 1 · Preparar y revisar una propuesta con IA | [Abrir descriptivo](labs/01_LAB1_descriptivo_ficha.md) | [Abrir ficha Excel](labs/LAB1_Fichas_editables.xlsx) |
| Lab 2 · Preparar contexto, ejecutar y revisar | [Abrir descriptivo](labs/03_LAB2_descriptivo_ficha.md) | [Abrir ficha Excel](labs/LAB2_Fichas_editables.xlsx) |

Para trabajar en Excel, descarga el archivo y guarda una copia propia.
Para trabajar en Markdown, copia la ficha incluida en el descriptivo
a un documento que puedas editar.

No edites los archivos originales del repositorio para registrar
tus respuestas personales.

## Qué necesitas

- Acceso al asistente de IA autorizado para la formación.
- Claude como asistente principal; el contraste del Lab 1 utiliza
  otro asistente autorizado cuando esté disponible.
- Un lugar donde guardar tu ficha, los mensajes utilizados y las respuestas.
- Acceso a estos materiales.

Los laboratorios no requieren programar, instalar conectores ni acceder
al código de un sistema real.

Si no puedes utilizar el asistente por acceso o cuota, avisa al instructor:
te indicará cómo continuar mediante una ejecución observada o una
simulación con material preparado. Identifica en tu ficha la ruta utilizada.

## Caso conductor

Actualmente, las solicitudes de servicio técnico se ordenan por fecha
de creación, de más antigua a más reciente.

Se recibe esta necesidad:

> «Queremos que las solicitudes urgentes se atiendan antes y que el
> responsable pueda comprobar qué está pasando».

No están definidos todavía el significado de urgente, quién determina
la urgencia ni qué necesita consultar el responsable.

El caso es ficticio. No representa la arquitectura ni las reglas
de PeopleNet/M4.

Utiliza los insumos del descriptivo correspondiente como referencia
del ejercicio. No completes las lagunas con datos de clientes reales.

## Lab 1 · Evaluar y dirigir una respuesta

### Recorrido

1. Obtener una propuesta inicial: R1.
2. Formar criterio propio antes de pedir una auditoría.
3. Contrastar el mismo encargo con otro asistente según el descriptivo.
4. Volver al chat principal y obtener la auditoría: R2.
5. Comprobar la auditoría con R1 y el expediente.
6. Introducir una condición humana y obtener la revisión: R3.
7. Decidir qué utilizarías y qué control aplicarías.

El contraste con otro asistente no exige repetir allí todo el laboratorio.

### Qué debes poder explicar al terminar

- Qué conservaste, corregiste o dejaste pendiente.
- Qué respaldo tiene tu decisión.
- Qué aceptaste o discutiste de la auditoría de la IA.
- Para qué utilizarías el resultado y qué comprobarías antes.

La salida prepara una conversación de aclaración con negocio.
No es una solución aprobada.

## Lab 2 · Preparar contexto y revisar su uso

### Recorrido

Utiliza conversaciones distintas de las del Lab 1:

- Chat A nuevo: contexto funcional → primera respuesta.
- Chat B nuevo: contexto funcional y técnico → segunda respuesta.
- Chat B, continuación: petición sobre estados → tercera respuesta.

Recordatorio: A → B → B.

No copies la respuesta de A en B.

Antes de la tercera consulta, completa las siete decisiones de la plantilla:

1. Petición.
2. Contexto incluido.
3. Justificación.
4. Contexto excluido.
5. Límites.
6. Salida solicitada.
7. Comprobación humana.

Compara tu preparación con el prompt de apoyo: adáptalo si lo necesitas
o justifica por qué lo mantienes.

Indicar que excluyes información en la plantilla no elimina el historial
del chat B. No trates propuestas anteriores como hechos confirmados.

### Qué debes poder explicar al terminar

- Qué permite comprobar la descripción técnica.
- Qué incertidumbres siguen abiertas.
- Por qué seleccionaste ese contexto.
- Qué conservarías o corregirías de la tercera respuesta.
- Qué verificarías antes de utilizar el resultado.

La salida prepara una conversación con el equipo técnico.
No es una especificación ni una estimación aprobadas.

## Consultas y capas de profundización

Sigue el presupuesto de consultas del descriptivo de cada laboratorio.

- La ruta principal utiliza tres mensajes en el asistente principal.
- El Lab 1 incorpora además el contraste con un segundo asistente.
- Cada laboratorio dispone de una única cuarta consulta opcional
  de ampliación, compartida entre sus capas.
- Si no hay disponibilidad o ya has utilizado esa ampliación,
  continúa con la alternativa de revisión humana indicada.
- No es obligatorio completar todas las capas para cerrar la ruta base.

No regeneres respuestas buscando errores ideales ni para que coincidan
con la resolución docente.

## Criterios de trabajo

- Distingue hechos aportados, hipótesis y decisiones pendientes.
- Una propuesta no es un acuerdo.
- No documentado no significa inexistente ni excluido.
- La auditoría de la IA también necesita revisión.
- Una tabla organiza el contenido, pero no lo valida.
- Más contexto no garantiza una respuesta mejor.
- Justifica tus observaciones con fragmentos o ausencias concretas.
- Conserva lo útil al corregir.
- Define un control humano concreto antes de reutilizar el resultado.

No buscamos un asistente ganador ni una única redacción correcta.

## Seguridad y uso de información

Utiliza únicamente material sintético o expresamente autorizado
para este entorno.

No incorpores datos personales, documentación confidencial, lógica
propietaria ni información de clientes por iniciativa propia.
Quitar nombres no equivale a tener autorización.

No subas al repositorio credenciales, datos reales de clientes
ni conversaciones con información confidencial.

## Material docente y recuperación

Consulta estos materiales cuando lo indique el instructor o cuando
se active una contingencia.

| Material | Enlace |
| --- | --- |
| Resolución orientativa · Lab 1 | [Abrir resolución](labs/02_LAB1_resolucion.md) |
| Resolución orientativa · Lab 2 | [Abrir resolución](labs/04_LAB2_resolucion.md) |

Las resoluciones incluyen ejemplos docentes construidos; no deben
presentarse como respuestas reales de Claude ni como resultados que
el asistente deba reproducir.

Estos enlaces están visibles en el repositorio: esta sección organiza
su uso, pero no restringe el acceso.

## Qué conservar para S2

- La ficha del Lab 1 y su decisión de uso.
- La plantilla del Lab 2 y sus límites.
- Los mensajes y respuestas utilizados, identificando su procedencia.
- Las preguntas sobre urgencia, responsables y seguimiento.
- Los hechos respaldados y las comprobaciones pendientes.

Continuamos desde ese trabajo preparatorio, no desde una solución
ya aprobada.