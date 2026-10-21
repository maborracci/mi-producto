# Encuesta: medios de cobro en farmacias que usan Farmapay

- **Objetivos de aprendizaje:**
  1. **Cuántos medios usa cada farmacia y qué parte del cobro pasa por cada uno.** Calibra el cruce con el padrón (creencia #1, parte 1; fila 2 de la agenda). Decide: si la mayoría declara que Farmapay ya es su medio principal, la principalidad deja de ser la palanca hacia los $43.000 M.
  2. **Cuánto cuesta conciliar varios medios y quién lo hace.** Mide el tamaño del costo del reparto (creencia #1, parte 2). Decide: si el control lleva poco tiempo y casi no hay sorpresas, la conciliación no sirve como argumento para concentrar.
  3. **Qué medio es el principal, quién lo eligió y con qué criterio.** Cuenta los criterios conocidos (acreditación, comisión, derivación, banco, costumbre) y si la transferencia está ganando lugar (creencias #2 y #5). Decide qué argumento probar primero en las entrevistas y en la solución.
  4. **Reclutar entrevistados** para la fila 4 de la agenda (8 a 10 titulares o administradores con participación baja).
- **Respondentes:** titulares, socios, administración o encargados de farmacias independientes y redes de hasta 50 bocas que cobraron con Farmapay en los últimos 30 días (cuentas en uso, ~2.150). Fuera: cajeros y empleados de mostrador, cadenas de más de 50 bocas, cuentas sin uso.
- **Duración estimada:** 3 de filtro + 10 preguntas, ~6 minutos (la Q2 es la más pesada).
- **Campo oculto:** `cuenta` (id de la cuenta Farmapay) y `canal`, en el link. Permite cruzar cada respuesta con el volumen real, el padrón y el estado en el embudo sin preguntar el CUIT.

## Texto de apertura (para la persona que responde)

> Hola, somos el equipo de Farmapay. Queremos entender cómo cobran hoy en la farmacia, con todos los medios que usen, no solo con Farmapay. Son unos 6 minutos. No hay respuestas correctas, y los números aproximados están bien. Tus respuestas quedan asociadas a tu cuenta para poder entenderlas mejor; no las usamos para ofrecerte nada.

## Filtro

S1. ¿Cuál es tu rol en la farmacia? [opción única]
   - Titular o socio/a
   - Administración o finanzas
   - Encargado/a de una o varias sucursales
   - Cajero/a o atención en mostrador
   - Otro
   → descalifica si "Cajero/a o atención en mostrador" u "Otro"

S2. ¿Cuántas farmacias (bocas) tiene el negocio, contando esta? [opción única]
   - 1
   - 2 a 5
   - 6 a 20
   - 21 a 50
   - Más de 50
   → descalifica si "Más de 50"

S3. En los últimos 30 días, ¿cobraron alguna venta con Farmapay? [opción única]
   - Sí
   - No
   - No sé
   → descalifica si "No"

## Preguntas

Q1. En los últimos 30 días, ¿con qué medios cobraron ventas en la farmacia? Marcá todos los que usaron. [opción múltiple]
   - Farmapay (tarjeta o QR)
   - Posnet de un banco o procesadora (Payway, Fiserv, Getnet u otro)
   - Mercado Pago (QR o Point)
   - Otro QR o billetera (MODO, Cuenta DNI, Naranja X, Ualá u otra)
   - Transferencia a la cuenta de la farmacia
   - Posnet o sistema de cobro de una droguería
   - Efectivo
   - Otro (¿cuál?)
   > Objetivo: 1

Q2. Pensando en el último mes, de cada $100 que cobraron, ¿cuántos pasaron, más o menos, por cada medio? [suma constante = 100, solo los medios marcados en Q1]
   > Objetivo: 1. Es la participación declarada; se compara cuenta por cuenta con el volumen real de Farmapay y el pago digital estimado del padrón.

Q3. De lo que cobran con tarjeta y QR, ¿por cuál medio pasa la mayor parte? [opción única, misma lista de Q1 sin transferencia ni efectivo, más "Más o menos parejo entre dos o más" y "No sé"]
   > Objetivo: 1 y 3. Control de la Q2, más fácil de responder.

Q4. ¿Cómo llegó ese medio a ser el principal? [opción única]
   - Lo elegí yo (o el titular)
   - Lo eligió la administración o el contador
   - Lo sugirió o lo pidió la droguería
   - Vino con la cuenta o el crédito del banco
   - Nadie lo decidió, se fue dando
   - Otro
   > Objetivo: 3

Q5. ¿Qué pesó más para que ese medio sea el principal? Elegí hasta 2. [opción múltiple, máximo 2]
   - Acredita más rápido
   - Cobra menos comisión
   - Manda la plata directo a la droguería o a la cuenta corriente
   - Viene con la cuenta del banco (o con crédito, cheques, etc.)
   - Los clientes lo piden (promociones, cuotas, reintegros)
   - Es el que ya teníamos
   - Es el más fácil para el mostrador
   - Otro
   > Objetivo: 3

Q6. En una semana normal, ¿cuánto tiempo le dedica alguien de la farmacia a controlar que lo cobrado por cada medio coincida con lo que se acreditó? [opción única]
   - No lo controlamos
   - Menos de 30 minutos
   - Entre 30 minutos y 1 hora
   - Entre 1 y 3 horas
   - Más de 3 horas
   - No sé
   > Objetivo: 2

Q7. ¿Quién hace ese control? Marcá todos los que correspondan. [opción múltiple]
   - Yo (o el titular)
   - Alguien de administración de la farmacia
   - El contador o un estudio externo
   - Un encargado de sucursal
   - Lo hace un sistema (conciliador, sistema de gestión)
   - Nadie
   > Objetivo: 2

Q8. En el último mes, ¿cuántas veces les pasó que un medio de cobro acreditó menos de lo esperado y no supieron enseguida por qué (por una retención, una comisión, un contracargo u otra cosa)? [opción única]
   - Ninguna
   - 1 vez
   - 2 o 3 veces
   - 4 veces o más
   - No sé
   > Objetivo: 2. Conducta concreta en lugar de opinión sobre si "cuesta".

Q9. En los últimos 6 meses, ¿cambió por dónde pasan la mayor parte de los cobros? [opción única]
   - Sí, pasamos más ventas por transferencia
   - Sí, pasamos más ventas por Farmapay
   - Sí, pasamos más ventas por otro medio (¿cuál?)
   - Sí, dejamos de usar un medio (¿cuál?)
   - No cambió
   - No sé
   > Objetivo: 3 (creencia #5: ¿la transferencia está desplazando al cobro con comisión?)

Q10. ¿Qué es lo más difícil de manejar cobros por varios medios a la vez? [abierta, opcional]
   > Objetivo: 2. Lenguaje propio para las entrevistas y para la solución.

## Filtro + opt-in (reclutamiento de entrevistas)

R1. ¿Decidís vos qué medios de cobro usa la farmacia, o participás de esa decisión? [opción única]
   - Sí, lo decido
   - Participo de la decisión
   - No
   → no es candidato si "No"

R2. ¿Aceptarías una charla de 30 minutos, por teléfono o videollamada, para contarnos cómo manejan los cobros? No es una llamada de venta. [sí / no]

R3. Si respondiste que sí, ¿cómo te contactamos? Nombre y WhatsApp o mail. [abierta, opcional, solo si R2 = sí]

## Distribución

| Canal | A quién llega y su sesgo | Alcance aprox. | Link |
|---|---|---|---|
| Mail o WhatsApp de Farmapay a las cuentas en uso | Todo el segmento, pero contestan más las cuentas comprometidas (las 716 recurrentes), que son las que menos reparten. Sobrerrepresenta a las satisfechas. | ~2.150 (cuentas en uso; cantidad sin fuente confirmada) | `?canal=masivo&cuenta={id}` |
| Comercial o post venta, al cerrar una llamada que ya estaba prevista, a cuentas en uso por debajo del promedio | Las que más reparten y menos contestan un envío masivo. Sesgo: post venta llama a quien tiene un problema, más disconformes. Quien llama manda el link y no lee las preguntas, para no influir. | ~1.430 (2.150 en uso − 716 recurrentes, si las recurrentes están todas dentro de las en uso) | `?canal=llamada&cuenta={id}` |

Descartado: grupos de WhatsApp con droguerías (decisión de Ayelen, 2026-10-21). El viajante es el acreedor de la cuenta corriente y puede sesgar lo que la farmacia declara sobre cobros por fuera.

- **n objetivo:** al menos 30 respuestas válidas de cuentas por debajo del promedio y al menos 30 de redes (2 a 50 bocas). Con menos de 30 por segmento, los resultados son direccionales.
- **Factibilidad:** con un 5% a 10% de respuesta en el envío masivo salen ~110 a 215 respuestas, suficiente para las cuentas por debajo del promedio, sobre todo con el refuerzo de las llamadas. Las redes son el riesgo: no sabemos cuántas de las cuentas en uso son redes. Si son menos de ~300, es difícil llegar a 30 y ese corte queda direccional.
- **Primera revisión:** 2026-10-30, para tener entrevistados reclutados antes del 2026-11-11.
- **Cierre:** abierta hasta llegar al n objetivo.
