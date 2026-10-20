# Farmapay

mode: existing · commercial

Farmapay es la plataforma de pagos digitales, procesamiento transaccional y gestión financiera para farmacias y droguerías en Argentina. Integra cobros con tarjeta de crédito, débito, QR, botones de pago y transferencias; deriva automáticamente un porcentaje de cada cobro a las droguerías proveedoras y gestiona su cuenta corriente; automatiza retenciones impositivas y liquida comisiones. En el mercado desde 2025.

## Para quién

- **Quién contrata:** el titular o la administración de cada farmacia o red de farmacias.
- **Quién opera:** colaboradores operativos y cajeros, en el día a día del mostrador.
- **Quién supervisa en las redes:** team leads y mandos medios farmacéuticos, que siguen rendimiento por sucursal, volumen de ventas y medios de pago preferidos.
- **Quién controla el proceso:** áreas de Operaciones, Compliance y Finanzas (plazos de onboarding, reglas de derivación, liquidación de comisiones, impacto fiscal neto).

## Modelo de ingresos

- Comisión por cobro según medio de pago: tarjeta de crédito (con acreditación en menos días), tarjeta de débito y QR.
- Sin comisión en cobros por transferencia.
- Derivación configurable por la farmacia: entre 1% y 99% de cada cobro va directo a una o más droguerías, con gestión automática de la cuenta corriente.

## Lo que sabemos

Fuente de todo el embudo: datos compartidos por Ayelen el 2026-10-20 (sistema de origen y fecha de corte a confirmar).

- 4.424 leads ingresados; 3.651 cuentas aprobadas (82,5%).
- 2.950 cuentas activadas, es decir que transaccionaron al menos una vez (80,8% de las aprobadas).
- 2.150 cuentas en uso (≥1 transacción en los últimos 30 días) y 800 sin uso: 27% de las activadas no operó en el último mes.
- 716 cuentas recurrentes: su promedio de transacciones a 30 días supera el promedio de la plataforma (24% de las activadas).
- Onboarding: 34 días promedio desde el ingreso hasta el legajo y 27 días más hasta la activación (~61 días en total).
- 773 legajos en revisión: 88 en proceso V1 y 685 en V2 (251 anterior a firma, 42 observados, 383 pendientes de firma).
- No sabemos todavía por qué las cuentas recurrentes usan Farmapay ni por qué las 800 dejaron de usarlo (confirmado por Ayelen: no hay información).

## Creencias no verificadas

Ordenadas por impacto × incertidumbre. La primera es la próxima a atacar.

1. [product] [value] Las cuentas recurrentes se quedan por la derivación automática a droguerías y la gestión de cuenta corriente, no por el cobro en sí: si perdieran la derivación, la mayoría volvería a su medio de cobro anterior.
   - Primer ataque: comparar la cantidad de reglas de derivación activas por cuenta entre recurrentes y sin uso.
2. [product] [value] Las 800 cuentas sin uso nunca reemplazaron su medio de cobro principal (posnet bancario, Mercado Pago): usaron Farmapay como complemento y lo abandonaron porque no les cambió la operación diaria.
3. [product] [value] Los ~61 días de onboarding enfrían a la farmacia: las cuentas con altas más largas tienen menor tasa de activación y de uso a 30 días.
4. [product] [viability] Las farmacias eligen cobrar con tarjeta de crédito en Farmapay por la acreditación más rápida y aceptan pagar más comisión por eso; el cobro por transferencia, que no genera ingresos, no está desplazando al cobro con comisión.
5. [product] [viability] El nivel de comisiones no es motivo de abandono ni de que una farmacia aprobada no llegue a activarse.
   - Acción prevista: mostrar casos de éxito con el ahorro en comisiones frente a otras plataformas.
