---
source: secondary
method: mixed
date: 2026-10-21
question: ¿Alcanza la principalidad en las cuentas en uso para llegar a $43.000 M/mes? ¿Cuánto cobra y en cuánto acredita la competencia? ¿Quién más resuelve cobro + droguería? ¿Hacia dónde se mueven los medios de pago?
opportunity: principalidad-en-farmacias
---

# Research: mercado de cobros en farmacias y principalidad

**Método.** Mezcla de tres archivos internos que compartió Ayelen el 2026-10-21 y búsqueda web. Etiquetas:
- `[archivo: padrón]`: *2026 mayo 19 Padrón de Farmacias, Acum. Trim. 2025_10 a 12.xlsx* (padrón PAMI, oct a dic 2025, con estimación de pago digital y segmentos armados por el equipo).
- `[archivo: Nubceo]`: *reporte_ceo_farmapay_integrado 2.html* (datos Nubceo desde 2026-07-01, 5 tenants y 9 CUITs, solo operaciones con comisión).
- `[archivo: MPxMES]`: *data 11 MPxMES.xlsx* (volumen Farmapay por medio y mes, 2026).
- `[dato de Ayelen]`: lo que contó en el hilo.
- `[verificado: URL — 2026-10-21]` y `[conocimiento del modelo — verificar]`.

Los archivos internos describen el mercado (padrón) o una muestra mínima de farmacias (Nubceo). Ninguno verifica por qué las farmacias hacen lo que hacen.

## Resumen: lo que cambia decisiones

1. **La meta es alcanzable con principalidad, pero exige un salto grande.** El universo de pago digital en farmacias ronda $1,1 billones/mes a precios de fines de 2025, unos $1,4 billones/mes a precios de hoy. Farmapay mueve hoy el ~1,9% de eso. Para llegar a $43.000 M las 2.150 cuentas en uso tienen que pasar de ~$12,3 M a ~$20 M promedio por mes (+63%). Si son farmacias independientes medianas, la participación estimada sube de ~24% a ~38%. El techo de esas 2.150 cuentas (~$112.000 M si fueran todas medianas) sobra para la meta.
2. **El padrón permite medir la participación por cuenta sin esperar al proxy de compras a droguería.** Trae CUIT y pago digital estimado por boca. Cruzarlo con los CUIT de Farmapay da participación = volumen Farmapay ÷ pago digital estimado, cuenta por cuenta. Esto podría reemplazar o validar la fila 2 de la agenda de investigación esta misma semana.
3. **"Los precios son competitivos" se sostiene frente a Mercado Pago, no frente al posnet bancario en débito.** En la muestra Nubceo, Farmapay cobra 1,0% en débito contra 0,8% de Prisma y First Data, aunque acredita en 2 días contra 4,4. En crédito Farmapay acredita en ~7,9 días hábiles, más lento que Prisma (4,5). El "ahorro de 4,47 pp" del reporte depende casi entero de una farmacia que paga 14,4% en Mercado Pago. Sin ella, la competencia ponderada baja de 5,7% a ~2,4%.

## 1. Dimensionamiento

**Universo.** El padrón tiene 12.099 bocas y 10.605 CUIT `[archivo: padrón]`. El 82,9% son farmacias independientes (10.026 bocas); siguen Farmacity (201), Far Mar (117), Farmaplus (73), Farmalife (67) y Soy tu Farmacia (63) `[archivo: padrón]`. Ayelen estima el total nacional entre 13.000 y 14.500 `[dato de Ayelen]`; una fuente de 2023 habla de 14.000, con ~60% en manos de farmacéuticos `[verificado: https://www.cronista.com/negocios/la-expansion-de-cadenas-como-farmacity-alentada-por-el-dnu-haria-desaparecer-a-12-000-farmacias-de-barrio/ — 2026-10-21]`. El padrón cubre ~85–90% del universo: las farmacias sin convenio PAMI no aparecen.

**Facturación.** Venta mensual (PVP + masivo, promedio oct a dic 2025): $1,606 billones; pago digital estimado al 70%: **$1,124 billones/mes** `[archivo: padrón]`. IQVIA da $1,639 billones PVP para dic-25, coherente `[archivo: padrón, hoja "Segun iqvia"]`. El 70% es un supuesto del equipo; no sabemos si incluye transferencias ni obra social.

Ajuste a precios de hoy: inflación acumulada ene–sep 2026 de 23,6% `[verificado: https://www.canal26.com/economia/2026/10/13/la-inflacion-de-septiembre-fue-de-19-y-acumula-un-alza-de-236-en-lo-que-va-del-2026/ — 2026-10-21]`. Sumando parte de dic-25, el factor es ~×1,25 (estimación propia, supone volumen real constante). Universo digital ≈ **$1,4 billones/mes** a precios de sep-26.

**Segmentos del padrón (pago digital estimado por mes, pesos de oct a dic 2025):**

| Segmento | Bocas | Rango | Mediana | % del volumen digital | % independientes |
|---|---|---|---|---|---|
| 1 Micro | 2.420 | < $13 M | $5,2 M | 1,2% | 93% |
| 2 Pequeña | 2.419 | $13–35 M | $23,2 M | 5,0% | 90% |
| 3 Media | 2.419 | $35–67 M | $48,7 M | 10,6% | 86% |
| 4 Grande | 2.419 | $67–130 M | $92,3 M | 20,3% | 81% |
| 5 Mayor | 2.420 | > $130 M | $215,3 M | 62,8% | 64% |

Independientes: mediana $41,8 M/mes, promedio $75,7 M `[archivo: padrón]`. El segmento 5 concentra casi dos tercios del volumen y dos de cada tres de sus bocas son independientes.

**Cuenta para la meta (agenda, fila 5).**
- Farmapay sep-26: $26.400 M = ~1,9% del universo digital a precios de hoy. Meta $43.000 M = ~3,1%.
- Por cuenta en uso: $26.400 M ÷ 2.150 = **$12,3 M/mes**.
- Participación estimada si la cuenta típica es una independiente mediana ($41,8 M × 1,25 = $52 M): **~24%**. Si es una boca promedio ($93 M × 1,25 = $116 M): **~11%**. En los dos casos, muy por debajo del 50%.
- Para la meta solo con principalidad en las 2.150 cuentas: +$16.600 M/mes, es decir +$7,7 M por cuenta (+63%). Con la independiente mediana, la participación pasa de ~24% a ~38%.
- Comparación: reactivar las 800 sin uso al promedio actual suma ~$9.800 M, el 59% de lo que falta.

Supuestos frágiles: el volumen Farmapay incluye transferencias y el 70% de pago digital tal vez no; no sabemos en qué segmentos están las cuentas Farmapay. El cruce por CUIT lo resuelve.

## 2. Precios y acreditación

Muestra Nubceo: 5 tenants y 9 CUITs, desde 2026-07-01, $849 M en ventas con comisión `[archivo: Nubceo]`.

| Plataforma | Medio | % comisión | % costo cuotas | Días hábiles prom. | Monto en muestra |
|---|---|---|---|---|---|
| Farmapay | Débito | 1,00 | 0 | 2,0 | $37,7 M |
| Farmapay | Crédito | 2,10 | 0 | 7,9 | $11,0 M |
| Prisma | Débito | 0,80 | 0 | 4,4 | $109,6 M |
| Prisma | Crédito | 1,97 | 4,52 | 4,5 | $116,4 M |
| Prisma | QR | 0,80 | 0 | 0 | $35,7 M |
| Prismanet | Débito | 0,93 | 0 | 3,5 | $7,9 M |
| Prismanet | Crédito | 1,86 | 1,35 | 9,7 | $13,9 M |
| First Data | Débito | 0,80 | 0 | 2,9 | $1,0 M |
| First Data | Crédito | 3,92 | 0 | 6,7 | $3,2 M |
| Mercado Pago | QR | 1,03 | 0 | 0 | $183,4 M |
| Mercado Pago | Crédito | 6,94 | 0,15 | 8,4 | $117,4 M |
| Mercado Pago | Débito | 12,44 | 0 | 6,3 | $211,3 M |
| Naranja | Crédito | 1,80 | 4,10 | 4,3 | $0,4 M |

Lectura:
- **El 12,44% de "débito" en Mercado Pago es anómalo.** Una tasa de débito no llega a ese nivel. Viene casi todo de Farmacia Fabris (14,4% de costo total, 85% en MP). Puede ser una clasificación errónea, cobros con financiación o retenciones mal imputadas. Hay que revisarlo antes de usar el reporte como argumento comercial.
- **El "ahorro potencial" depende de ese caso.** Competencia ponderada: 5,72% con Fabris y ~2,4% sin Fabris (cálculo propio con los totales del reporte), contra 1,25% de Farmapay. Farmapay sigue más barato en la mezcla, pero por menos.
- **Mismo medio contra mismo medio:** en débito Farmapay es 0,2 pp más caro que el posnet bancario y acredita 2 días antes. En crédito cobra una comisión parecida, sin costo de cuotas (¿no ofrece cuotas?), y acredita más tarde que Prisma. Ojo: el reporte mide la acreditación de Farmapay con `settlement.date` y la del resto con `settlement.updatedAt`, así que la comparación de días no es pareja.
- Mercado Pago publicó en 2023 una tabla de QR: débito 1,24% en el momento y crédito de 6,49% (en el momento) a 1,79% (35 días) `[verificado: https://www.iprofesional.com/tecnologia/386153-mercado-pago-que-debes-saber-sobre-comisiones-plazos-y-montos — 2026-10-21, artículo de 2023]`. Tarifas de 2026: desconocidas, no encontré fuente oficial actual.

**Participación de Farmapay en la muestra** `[archivo: Nubceo]`: 0,13% (Selma), 5,5% (Fabris), 1,75% y 0% en los CUIT de Farmanobel, 80,6% (Del Viejo Palermo) y 95,7% (Hauresz). **7 de 9 CUIT están por debajo del 50%.** No es representativo (9 CUIT, varios de un mismo grupo), pero sirve como calibración del cruce con el padrón.

## 3. Competidores del rubro farma

- **POS de droguería.** Las droguerías ofrecían su propio POS: el 100% de lo cobrado iba directo a la droguería y a la cuenta corriente de la farmacia, que se quedaba sin liquidez ni efectivo `[dato de Ayelen]`. No pude verificar en la web qué droguerías lo ofrecen hoy ni en qué condiciones (la página de servicios de Del Sud bloquea la lectura). Estado actual: **desconocido**.
- **Qué prueba:** existe demanda de que el cobro alimente la cuenta corriente con la droguería. **Qué no prueba:** que las farmacias quieran concentrar en un solo medio. El modelo 100% las ahogaba, y la derivación configurable de Farmapay (1–99%) es justo la respuesta a ese dolor.
- **Concentración de droguerías** en el padrón (droguería PAMI por boca): Suizo Argentina 2.397, Kellerhoff 1.138, Del Sud ~2.100 sumando sucursales, Monroe Americana 843, Asoprofarma 693, Cofarsur 504, 20 de Junio 498 `[archivo: padrón]`. Unas pocas droguerías tocan a la mayoría de las farmacias: son un canal o un competidor según el acuerdo.
- **Conciliadores multiplataforma** (Nubceo y similares): resuelven la dispersión sin concentrarla. Su penetración en farmacias es **desconocida**. Que Farmapay tenga menos de 20 farmacias ahí sugiere que es baja `[dato de Ayelen]`.

## 4. Tendencias

**Mercado (BCRA, julio 2026)** `[verificado: https://www.bcra.gob.ar/archivos/Pdfs/PublicacionesEstadisticas/Informes/informe-mensual-pagos-minoristas-2026-07.pdf — 2026-10-21]`:
- Pagos con transferencia interoperables: 116,9 M de operaciones (+70,7% interanual), $3 billones (+66,6% real). El 98,9% se inicia con QR.
- Tarjeta de débito (junio): −6,9% en cantidad y −13,4% real en monto.
- Tarjeta de crédito (junio): +1,6% en cantidad y −10,2% real en monto.

El mercado se mueve con fuerza hacia QR y transferencia, y la tarjeta cae en términos reales.

**Farmapay** `[archivo: MPxMES]`:

| Período | Total ($ mil M) | Crédito | Débito | QR | Transf. | Ticket transf. |
|---|---|---|---|---|---|---|
| T1 (total) | 44,06 | 22,3% | 53,1% | 17,0% | 7,5% | $31 k |
| T2 (total) | 64,88 | 21,7% | 51,0% | 19,9% | 7,4% | $30 k |
| Julio | 24,94 | 19,9% | 52,1% | 20,6% | 7,3% | $31 k |
| Agosto | 25,36 | 21,3% | 50,9% | 20,0% | 7,7% | $32 k |
| Septiembre | 26,39 | 20,7% | 50,0% | 20,4% | 8,9% | $32 k |
| Octubre (parcial) | 17,46 | 18,7% | 44,9% | 18,5% | 17,9% | **$71 k** |

**El salto de octubre viene del ticket, no de la frecuencia.** Las transferencias son el 9,9% de las operaciones en octubre contra 9,4% en septiembre. Lo que se duplicó es el ticket promedio, de $32 k a $71 k. Eso apunta a pocas operaciones grandes (¿pocas cuentas, pagos no de mostrador?), no a que el mostrador esté pasando de tarjeta a transferencia. Es una hipótesis para la fila 1 de la agenda: hay que mirarlo por cuenta.

El crédito baja despacio de 22% a 19–21%, en línea con el mercado.

## Impacto en creencias

| Creencia (de overview.md) | Veredicto | Evidencia |
|---|---|---|
| #1 [opportunity] [value] Participación < 50% del volumen con comisión, y el reparto se vive como costo | **Apoya** la parte de participación; **no dice nada** de si se vive como costo | Estimación agregada ~11–24% `[archivo: padrón + MPxMES]`; 7 de 9 CUIT bajo 50% `[archivo: Nubceo]`. Muestra no representativa y supuestos de pago digital sin validar |
| #2 [product] [value] La derivación a droguerías es lo que retiene | **No dice nada** (contexto a favor) | El POS 100% de droguería dejaba sin liquidez a la farmacia `[dato de Ayelen]`: la derivación parcial resuelve un dolor conocido. No dice por qué se quedan las recurrentes |
| #3 [product] [value] Las 800 sin uso usaron Farmapay como complemento | **No dice nada** | En Nubceo, 3 CUIT usan Farmapay de forma marginal (0–5,5%), consistente con un uso complementario, pero ninguno está entre las sin uso |
| #4 [product] [value] Los ~61 días de onboarding enfrían | **No dice nada** | — |
| #5 [product] [viability] Crédito por acreditación rápida; la transferencia no desplaza al cobro con comisión | **Contradice** la parte de acreditación; **tensiona** la de transferencia | Crédito Farmapay ~7,9 días contra Prisma 4,5 `[archivo: Nubceo]` (medición dispar). Mercado: PCT +66,6% real y tarjetas en caída `[verificado: BCRA]`. Interno: el salto de octubre es de ticket, no de frecuencia `[archivo: MPxMES]` |
| #6 [opportunity] [viability] Principalidad sin bajar la comisión | **Apoya parcialmente** | Farmapay ya es más barato en la mezcla (1,25% contra ~2,4–5,7%) `[archivo: Nubceo]`, pero en débito es 0,2 pp más caro que el posnet bancario. Concentrar débito del banco no le ahorra a la farmacia, salvo por acreditación |
| #7 [product] [viability] La comisión no es motivo de abandono | **No dice nada** sobre motivos | Aviso para la acción de casos de éxito: el ahorro es claro contra Mercado Pago y discutible contra el posnet bancario en débito |

## Qué sigue necesitando research primario

**Análisis interno (antes de encuestar o entrevistar):**
- Cruzar CUIT de Farmapay con el padrón: participación por cuenta y segmento de cada cuenta. Calibrar con los 9 CUIT de Nubceo. Resuelve la fila 2 de la agenda y afina la fila 5.
- Transferencias de octubre por cuenta: ¿pocas cuentas y tickets grandes? (fila 1 de la agenda).
- Revisar el 12,44% de débito en Mercado Pago del reporte antes de usarlo comercialmente.

**Encuesta (`/design-survey`: cuántos, cuánto, con qué frecuencia):** cuántos medios usa cada farmacia, qué % del cobro pasa por cada uno, horas por semana de conciliación, qué medio es el principal y quién lo eligió.

**Entrevistas (`/design-interview`: por qué, qué hacen hoy):** si el reparto se vive como costo (#1, parte 2, fila 4 de la agenda); por qué eligen crédito en un medio u otro (#5); qué rol cumple la derivación para quedarse (#2); qué pasó con el POS de droguería y si alguna lo usa todavía.
