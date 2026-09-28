# Resumen del material · Curso de Valoración de Empresas (SII – Escuela de Ingeniería UC)

Este resumen recorre los documentos del repositorio en el orden en que conviene estudiarlos. Cada sección trae las ideas clave y ejemplos con números. La mayoría de los ejemplos vienen del propio material; los marcados como **(ilustrativo)** son casos simplificados agregados para facilitar la comprensión.

| # | Archivo | Contenido | Páginas |
|---|---------|-----------|---------|
| 1 | `Valoración SII - Clase 1.pdf` | Precio, valor y patrimonio; de valor de empresa a valor del patrimonio (caso Cencosud) | 52 láminas |
| 2 | `M2 Enfoque Costos_Activos.pdf` | Enfoque de costos: método del Activo Neto Ajustado (ANAV), caso Viña Los Cipreses | 49 láminas |
| 3 | `M3 Enfoque Múltiplos (1).pdf` | Enfoque de mercado: múltiplos y elección de comparables | 38 láminas |
| 4 | `Guía - Elección de comparables mediante método de regresión lineal.pdf` | Material complementario: múltiplo PUC estimado por regresión (caso Alphabet) | 5 págs. |
| 5 | `Glosario _ Valoración de empresas.pdf` | 104 términos técnicos del curso, con índice alfabético | 9 págs. |

> **Nota:** `M3 Enfoque Múltiplos (1) (1).pdf` es una copia idéntica de `M3 Enfoque Múltiplos (1).pdf` (mismo contenido byte a byte).

---

## 1. Clase 1 · Introducción: precio, valor y patrimonio

**Profesor:** Tomás Reyes · 24-sep-2026. El curso tiene 6 clases: (1) introducción; (2-3) enfoques de costos y de mercado; (4) enfoque de ingresos; (5) intangibles, WACC/WARA y ajustes al valor; (6) situaciones especiales (pérdidas, startups, servicios).

### 1.1 Precio ≠ valor

| Precio | Valor |
|---|---|
| Un **hecho**, con fecha | Una **estimación**, con supuestos |
| Lo que alguien pagó en una transacción concreta | Lo que el activo debería valer para alguien, con un propósito |
| Observable y único | No observable; puede haber varios |

**Idea central:** en una revisión, primero se verifica la aritmética, pero lo que realmente se discute son los **supuestos**.

**Ejemplo (Cencosud, en billones de pesos):** con los mismos datos del balance salen tres cifras distintas, porque cada una responde una pregunta distinta:

| Pregunta | Cifra | Qué representa |
|---|---|---|
| ¿Cuánto vale lo que es de los dueños? | **5,7** | Capitalización bursátil (precio × acciones) |
| ¿Cuánto vale la empresa completa, con deudas y todo? | **10,8** | Valor de la empresa |
| ¿Qué queda si se vende por partes? | **4,6** | Patrimonio contable (punto de partida, no el valor de liquidación) |

Ninguna está "mal". El error está en no decir qué pregunta se está respondiendo.

### 1.2 Tres mitos de la valoración (Damodaran)
1. **"Es objetiva"**: el sesgo entra por los supuestos que se eligen, no por la aritmética.
2. **"Es precisa"**: más decimales no significan más confianza.
3. **"Mientras más cuantitativa, mejor"**: un modelo con 40 variables puede esconder mejor el sesgo.

### 1.3 Cuatro definiciones de valor
| Definición | Quién la usa | Qué supone |
|---|---|---|
| **Valor de mercado** | Transacciones, tasaciones | Comprador y vendedor informados, sin urgencia, independientes |
| **Valor de inversión** | Un comprador específico | Sus sinergias y su estrategia; por eso puede pagar más |
| **Valor razonable** (NIIF 13) | Estados financieros | Precio de salida; si cotiza, precio × cantidad, sin prima de control |
| **Valor de liquidación** | Insolvencia, garantías | Venta rápida, por partes, con descuento |

**Pregunta para un informe:** ¿qué valor está estimando? Si no lo dice, eso ya es un hallazgo.

### 1.4 La fecha de valoración
Los supuestos se juzgan con **lo que se sabía ese día**, no con lo que pasó después. También es un error el caso inverso: un informe que incorpora hechos posteriores sin declararlo.

> **Ejemplo (ilustrativo):** una empresa se valoró al 31-12-2024 suponiendo ventas de $1.000. En 2025 una crisis bajó las ventas a $600. No se puede decir que el informe "se equivocó" por no prever la crisis. La pregunta correcta es si el supuesto de $1.000 era razonable con los presupuestos, contratos y tasas conocidos al 31-12-2024.

### 1.5 ¿El precio pactado es el valor?
Un precio entre partes independientes es la **mejor evidencia** del valor de mercado, pero no lo demuestra. Solo habla por sí mismo si se cumplen tres condiciones:
- **Independencia**: si las partes están relacionadas, el precio no lo fijó el mercado.
- **Información**: si una parte sabía más, el precio refleja esa asimetría.
- **Sin urgencia**: una venta forzada da un precio de liquidación.

Si falla alguna, hay que estimar el valor con los tres enfoques.

### 1.6 Los tres enfoques, con un departamento como ejemplo
| Enfoque | Qué mira | Ejemplo con un departamento comprado para arrendar |
|---|---|---|
| **Ingresos** | Lo que el negocio va a generar, traído a hoy | Arriendo neto esperado + precio de venta final, descontados a hoy |
| **Mercado** | Lo que se paga hoy por activos comparables | Precio por m² de ventas recientes parecidas en el barrio, ajustado |
| **Costos / activos** | Lo que costaría reponerlo, o lo que queda al liquidar | Terreno + construir uno equivalente hoy − depreciación |

### 1.7 Del valor de la empresa al valor del patrimonio

```
Valor del patrimonio = Valor de la empresa
                       − Deuda financiera
                       + Efectivo excedente
                       − Participaciones no controladoras (minoritarios)
                       + Inversiones en asociadas
                       ± Otras partidas
```

**Ejemplo del material** (matriz con 80% de una filial y 30% de una asociada):

| Partida | Monto | Por qué |
|---|---|---|
| Valor de la empresa (consolidado) | 1.000 | Punto de partida |
| Deuda financiera | −400 | Es de los acreedores |
| Efectivo excedente | +50 | Es de los accionistas y no genera flujo operativo |
| Minoritarios (20% de filial que vale 500) | −100 | La filial se consolidó al 100% pero el 20% es de otros |
| Asociada (30% de 300) | +90 | No se consolida; queda fuera del EBITDA |
| Terreno sin uso | +30 | Activo que no produce flujo |
| Juicio probable | −20 | Obligación no financiera que se pagará |
| **Valor del patrimonio** | **650** | |

### 1.8 La "regla de la misma base" y la NIIF 16 (arrendamientos)
Desde 2019 (NIIF 16) el arriendo ya no se resta antes del EBITDA, así que el EBITDA "sube" sin que el negocio cambie.

**Ejemplo del material (una tienda en local arrendado, múltiplo 8x):**

| | Antes de NIIF 16 | Desde NIIF 16 |
|---|---|---|
| Ventas | 100 | 100 |
| Costos sin arriendo | −60 | −60 |
| Arriendo | −10 | (sale de aquí) |
| **EBITDA** | **30** | **40** |

- Con EBITDA 30 (arriendo restado): 30 × 8 = **240**. No se resta el pasivo por arriendo.
- Con EBITDA 40 (sin restar el arriendo): 40 × 8 = 320, **menos 80 de pasivo por arrendamiento = 240**.
- Si se olvida restar el pasivo, el valor queda inflado en 320.

**Regla:** lo que genera el EBITDA debe estar dentro del valor de la empresa, y lo que no lo genera debe quedar fuera.

### 1.9 ¿Qué entrega cada método? (la tabla más importante de la clase)
| Método | Entrega | Enfoque |
|---|---|---|
| Flujo de caja libre de la empresa (a la WACC) | Valor de la **empresa** | Ingresos |
| Múltiplos EV/EBITDA, EV/EBIT, EV/Ventas | Valor de la **empresa** | Mercado |
| Costo de reposición de activos operacionales | Valor de la **empresa** (aprox.) | Costos |
| Flujo de caja del accionista (al costo patrimonial) | Valor del **patrimonio** | Ingresos |
| Dividendos descontados | Valor del **patrimonio** por acción | Ingresos |
| Múltiplos P/U, P/Valor libro | Valor del **patrimonio** por acción | Mercado |
| Activos netos ajustados y liquidación | Valor del **patrimonio** | Costos |

**Los dos errores caros:**
1. Comparar un valor de **empresa** con lo que se pagó por las **acciones**. La diferencia son todas las partidas del punto 1.7.
2. Restar deuda a un valor que **ya era patrimonio**, con lo que la deuda se cuenta dos veces.

### 1.10 Sensibilidad: dónde está la discusión
Con una perpetuidad creciente (flujo que crece 3% anual, tasa 9%) el valor base es 100:

| Cambio | Valor | Efecto |
|---|---|---|
| Tasa sube a 10% | 86 | −14% |
| Crecimiento sube a 4% | 120 | +20% |
| Flujo del año 1 es 10% menor | 90 | −10% |

Un punto de tasa o de crecimiento mueve más el valor que un error de 10% en el flujo. Por eso son los supuestos que un informe más necesita sustentar.

### 1.11 Préstamos de relacionadas a valor de mercado
**Ejemplo del material:** la matriz presta 100 a la sociedad, a 5 años, **sin intereses**. La tasa de mercado es 8%.
- Valor de mercado del pasivo = 100 ÷ 1,08⁵ = **68,1**
- Diferencia que **se suma al patrimonio** = **31,9**

Si el préstamo tiene una tasa **mayor** que la de mercado, el pasivo vale más que su nominal y el patrimonio baja.

### 1.12 El EBITDA no es flujo de caja
```
Flujo de caja libre = EBITDA − impuestos − inversiones − aumento del capital de trabajo
```
Una empresa puede tener EBITDA positivo y quemar caja durante años.

> **Ejemplo (ilustrativo):** EBITDA 100, impuestos 20, inversión en maquinaria 60, aumento de inventarios y cuentas por cobrar 30. Flujo de caja libre = 100 − 20 − 60 − 30 = **−10**. La empresa "gana" 100 de EBITDA pero consume caja.

### 1.13 Taller Cencosud (resuelto, en miles de millones)
Valor de la empresa 10.850 − deuda 4.430 − arrendamientos 1.070 + caja excedente 390 − minoritarios 650 + asociadas 350 = **5.440**.

No entran en el cálculo: la **plusvalía**, porque ya está dentro del valor de la empresa; las **propiedades de inversión**, porque sus arriendos ya están en el EBITDA; el **patrimonio contable**, porque no es una partida; y las **cuentas comerciales con relacionadas**, porque son capital de trabajo.

La diferencia de 250 con la capitalización bursátil (5.690) corresponde a la caja que se consideró operativa.

### 1.14 Minoritarios: a valor de mercado, no a libro
**Ejercicio del material:** una matriz tiene el 60% de una filial que cotiza con capitalización de 500 y patrimonio contable de 250. El consolidado vale 1.000, sin deuda.
- Correcto: 1.000 − 40% × **500** = **800**
- Incorrecto (a libro): 1.000 − 40% × 250 = 900. Este cálculo sobrevalora el patrimonio en 100.

### 1.15 Partes obligatorias de un informe de valoración
1. Encargo y propósito
2. Definición de valor
3. Fecha de valoración
4. Método y por qué se eligió
5. Supuestos
6. Conciliación entre métodos
7. Ajustes al valor (control, iliquidez)
8. Limitaciones y alcance

**Orden de revisión sugerido:** (1) encargo y propósito → (2) definición de valor y fecha → (3) supuestos y conciliación. Recién después se abre el modelo. **Omitir alguna de estas partes ya es un hallazgo.**

---

## 2. Módulo 2 · Enfoque de Costos / Activos (método ANAV)

**Profesor:** Claudio Tapia. La pregunta que responde este enfoque es: *¿cuánto costaría hoy reunir, activo por activo, lo que tiene esta empresa, y cuánto de eso es de los accionistas?*

### 2.1 ¿Cuándo conviene usarlo?
1. **Holdings o sociedades de inversión**: el valor está en lo que poseen.
2. **Empresas intensivas en activos tangibles**: inmobiliarias, agrícolas, forestales.
3. **Empresas sin flujos futuros confiables**: nuevas o con pérdidas recurrentes.
4. **Liquidación o cese de actividades.**
5. **Como piso o contraste** frente a valoraciones por flujos o por múltiplos.

### 2.2 Cuatro métodos
| Método | Qué es | Limitación principal |
|---|---|---|
| **Valor libro** | Patrimonio contable, sin ajustes | Costo histórico, lejos del valor económico actual |
| **ANAV** (Activo Neto Ajustado) | Revaloriza cada activo y pasivo a su valor económico | Requiere información detallada, partida por partida |
| **Valor de reposición** | Costo de reconstruir la empresa desde cero | Limita cada partida a su costo de reposición |
| **Valor de liquidación** | Vender todo, pagar todo, descontar costos de liquidación | Requiere mercados secundarios activos |

```
PATRIMONIO AJUSTADO = ACTIVOS AJUSTADOS − PASIVOS AJUSTADOS
```

### 2.3 Base de valor según el tipo de cuenta
| Cuenta | Criterio |
|---|---|
| Terrenos, inversiones cotizadas | Valor razonable de mercado (comparables) |
| Construcciones, maquinaria especializada | Costo de reposición **depreciado** |
| Maquinaria con mercado secundario | Precio de equipos usados comparables |
| Inventarios terminados / en proceso | Valor neto de realización (VNR) |
| Materias primas | Costo de reposición |
| Partidas de largo plazo en condiciones fuera de mercado | Valor presente |

**Principios del método:** materialidad, perspectiva de un participante de mercado, **misma fecha de corte** para todos los ajustes, y separación entre activos operacionales y no operacionales.

**Proceso en 6 etapas:** balance base → partidas fuera de balance → base de valor por partida → evidencia de respaldo → **efecto tributario (impuesto diferido)** → balance ajustado con trazabilidad.

### 2.4 Costo de reposición depreciado (CRD)
```
CRD = Costo de reposición nuevo − Depreciación física − Obsolescencia funcional − Obsolescencia económica
```
- **Física**: desgaste por uso y edad.
- **Funcional**: el activo funciona, pero su tecnología ya no es la óptima.
- **Económica**: factores externos como caída de demanda, sobrecapacidad o regulación.

> **Ejemplo del material (bodega):** reponerla nueva cuesta 2.150. Tiene vida útil de 45 años y lleva 18, así que el 40% está consumido. CRD = 2.150 − 860 = **1.290**. Su valor libro es 1.200, por lo que el ajuste es **+90**.

### 2.5 Cuentas por cobrar: análisis de antigüedad (aging)
**Ejemplo del material (caso Larkin Co.):**

| Tramo | Saldo | Prob. de cobro | Valor esperado | Provisión |
|---|---|---|---|---|
| 0-30 días | 103.000 | 99% | 101.970 | 1.030 |
| 31-60 días | 97.500 | 95% | 92.625 | 4.875 |
| 61-90 días | 39.500 | 85% | 33.575 | 5.925 |
| > 90 días | 10.000 | 5% | 500 | 9.500 |
| **Total** | **250.000** | | **228.670** | **21.330** |

El tramo de más de 90 días es solo el 4% del saldo, pero explica casi la mitad de la provisión.

### 2.6 Pagos anticipados: ¿se transfieren al comprador?
| Operación | ¿Se transfiere el beneficio? |
|---|---|
| Compra de acciones (*share deal*) | **Sí**: la sociedad continúa y la póliza o el arriendo siguen vigentes |
| Compra de activos (*asset deal*) | **Generalmente no**: se lleva a $0 |
| Campaña de marketing ya ejecutada | **No, en ningún caso**: es un costo ya consumido |

### 2.7 Intangibles
El enfoque de costos es, en general, el **menos apropiado** para intangibles, porque el valor de una marca depende de lo que generará y no de lo que costó crearla. Sí sirve para **software interno**, **fuerza de trabajo organizada** y **permisos con costo de renovación conocido**.

### 2.8 El lado del pasivo
Un error en el pasivo afecta el resultado **exactamente igual** que un error del mismo monto en el activo.
- **Provisiones** (indemnización por años de servicio, garantías, litigios): revisar los supuestos actuariales.
- **Pasivos contingentes no reconocidos** (avales, garantías, litigios "posibles"): buscarlos en notas, actas de directorio y contratos.
- **Deuda financiera a valor de mercado:**
  - Tasa pactada **mayor** que la de mercado → el pasivo vale más → el patrimonio **baja**.
  - Tasa pactada **menor** que la de mercado → el pasivo vale menos → el patrimonio **sube**.
  - Préstamos de relacionadas: evaluar si en el fondo son un **aporte de capital encubierto** y, si lo son, reclasificarlos a patrimonio.

### 2.9 ★ Impuesto diferido: el ajuste más omitido
**Ejemplo del material:** un terreno con valor libro 400 vale 950 en el mercado. La revalorización es 550 y, con tasa de 27%, genera un **pasivo por impuesto diferido de 149**. Si no se reconoce, el patrimonio queda sobrestimado en 149.

### 2.10 Caso aplicado: Viña y Frigorífico Los Cipreses S.A. ($MM)
Viña exportadora con 75 ha propias, 40% de una distribuidora en el exterior, deuda bancaria y un préstamo preferente de su matriz extranjera.

| Ajuste | Monto | Cómo se obtuvo |
|---|---|---|
| Cuentas por cobrar | (85) | Aging + un cliente en quiebra en el exterior (recupera 20 de 120) |
| Inventarios | +310 | Etiquetas obsoletas (20); vino reserva en proceso a VNR +150; vino embotellado a VNR +180 |
| Pagos anticipados | (40) | La campaña publicitaria en Asia se lleva a $0 |
| Viñedos (activos biológicos) | +540 | Comparables: joven $28 MM/ha, maduro $35 MM/ha (excluyendo ventas entre relacionadas) |
| Propiedades, planta y equipo | +860 | Terreno +700 (comparables $21,3 MM/ha), bodega +90, línea de vinificación +70 |
| Inversión en asociada | +95 | (el material muestra el ajuste sin detallar el cálculo) |
| Activo por impuesto diferido | (60) | Solo se recuperan pérdidas por 444 de 667 según la proyección |
| **Total activos** | **+1.620** | 10.695 → **12.315** |
| Provisiones | +45 | Indemnización +30 (menor tasa y menor rotación); garantías +15 (lote de corchos defectuosos) |
| Pasivo por impuesto diferido | +450 | (310 + 540 + 860 − 43 ya vendido) × 27% |
| Deuda con matriz | (95) | Tasa pactada 3% vs. mercado 6,2%: vale 1.405, no 1.500 |
| **Total pasivos** | **+400** | 4.430 → **4.830** |
| **PATRIMONIO** | **+1.220** | 6.265 → **7.485** (+19,5%) |

**Lecciones del caso:**
1. El ajuste individual más grande (impuesto diferido, 450) estaba en el **pasivo**. Un análisis que solo mira activos lo pasa por alto.
2. El resultado sigue siendo un **piso**: la marca queda en $40 MM, que es su costo de registro. Si por el enfoque de ingresos valiera $400 MM, la diferencia es el *goodwill* que el enfoque de costos no captura.

### 2.11 Checklist para revisar un ANAV
- ¿Hay tasaciones, cotizaciones o informes técnicos que respalden cada ajuste relevante?
- ¿Se revisaron **activo y pasivo**, o solo un lado del balance?
- ¿Se reconoció el **impuesto diferido** de las revalorizaciones?
- ¿Se usó costo para intangibles cuando correspondía usar ingresos?
- ¿Los pasivos con relacionadas están a **condiciones de mercado**?
- ¿Se contrastó el resultado con otro enfoque?

> **Relevancia tributaria:** la bibliografía del módulo cita los arts. 41 E y 41 F de la LIR y el art. 64 del Código Tributario. Son las normas donde estas técnicas se aplican en fiscalización: precios de transferencia, exceso de endeudamiento y tasación.

---

## 3. Módulo 3 · Enfoque de Mercado: Múltiplos

**Profesor:** Claudio Tapia.

### 3.1 La idea
```
Múltiplo = Lo que se paga por el activo / Lo que se recibe a cambio
```
Se hace en tres pasos: (1) buscar comparables y sus valores de mercado; (2) convertirlos a múltiplos; (3) comparar o aplicar el múltiplo a la empresa analizada.

> **Analogía (ilustrativa):** si en tu barrio los departamentos se venden a 60 UF/m² y el tuyo tiene 50 m², un primer valor de referencia es 60 × 50 = 3.000 UF. El "múltiplo" aquí es UF/m².

### 3.2 Múltiplos de patrimonio vs. múltiplos de empresa
| | Valor de la empresa (EV) | Valor del patrimonio |
|---|---|---|
| Qué mide | El negocio completo, antes de cómo se financia | Lo que reciben los accionistas |
| Fórmula | Capital propio + deuda neta | Precio × N° de acciones |
| Múltiplos | EV/EBITDA, EV/Ventas, EV/Book | P/U, Bolsa/Libro |

**Regla práctica:** si los comparables tienen niveles de deuda muy distintos, conviene usar múltiplos de EV.

### 3.3 Ejemplos del material
**Datos:** utilidad neta $12,42 MM; EBITDA $30,5 MM; 5,4 MM de acciones a $30; deuda neta $88 MM.

- **P/U:** UPA = 12,42 / 5,4 = $2,30 → P/U = 30 / 2,30 = **13,04x**
- **EV/EBITDA:** patrimonio = 30 × 5,4 = $162 MM → EV = 162 + 88 = $250 MM → 250 / 30,5 = **8,2x**

**Comparación con 6 empresas:** su empresa transa a $36 con UPA $2, es decir, P/U = 18.

| Comparable | 1 | 2 | 3 | 4 | 5 | 6 | Promedio | **Mediana** |
|---|---|---|---|---|---|---|---|---|
| P/U | 17,96 | 29,08 | 19,99 | 34,20 | 18,65 | 19,66 | 23,25 | **19,82** |

Precio implícito con la mediana: 19,82 × $2 = **$39,64**, mayor que $36. Con el promedio: 23,25 × 2 = $46,5. En ambos casos la acción está **subvalorada** respecto de sus comparables.

### 3.4 Qué múltiplo usar según industria y etapa
| Industria | Múltiplo preferido |
|---|---|
| Bancos y aseguradoras | P/Valor libro, P/U |
| Retail | EV/EBITDA, EV/Ventas |
| Tecnología / SaaS | EV/Ventas |
| Minería | EV/EBITDA, EV/reservas |
| Aerolíneas y hoteles | EV/EBITDAR |
| Agroindustria y viñas | EV/EBITDA, EV/Ventas, EV/hectárea |
| Holdings | P/NAV con descuento de holding |

| Etapa | Múltiplo |
|---|---|
| Startup sin EBITDA | EV/Ventas proyectadas, rondas de inversión comparables |
| En crecimiento | EV/EBITDA proyectado, PEG |
| Madura | EV/EBITDA histórico, P/U, Dividend Yield |

### 3.5 Los múltiplos dependen de fundamentos
Un P/U alto no siempre significa "cara". Depende del **crecimiento**, del **riesgo** y de la **tasa de reparto (payout)**:
```
P/U ≈ Payout × (1 + g) / (rE − g)
```
> **Ejemplo (ilustrativo):** con payout 50%, rE = 10%. Si g = 2%: P/U ≈ 0,5 × 1,02 / 0,08 ≈ **6,4x**. Si g = 5%: P/U ≈ 0,5 × 1,05 / 0,05 ≈ **10,5x**. Solo por crecer más, la misma empresa "merece" un múltiplo mayor.

### 3.6 Elección de comparables (lo más importante del módulo)
**Primer filtro:** industria y subsegmento (ACTECO / GICS), modelo de negocio, mercado de destino y tamaño.

**Herramientas estadísticas:**
- **Mediana, no promedio**, porque es robusta a valores extremos.
- **Outliers:** un dato es atípico si queda por debajo de Q1 − 1,5 × RIC o por encima de Q3 + 1,5 × RIC. No se descarta automáticamente, pero sí se exige una explicación (prima estratégica, utilidad no recurrente, OPA anunciada).
- **Coeficiente de variación** (desviación estándar / media): el múltiplo con menor dispersión es mejor predictor para esa industria.
- **Regresión (R²):** se prefiere el múltiplo que mejor explica las diferencias entre empresas.

**Matriz de comparabilidad ponderada (ejemplo del material):**

| Criterio | Peso | A | B | C | D |
|---|---|---|---|---|---|
| Industria / modelo | 30% | 5 | 4 | 5 | 3 |
| Tamaño | 20% | 3 | 5 | 2 | 1 |
| Liquidez bursátil | 30% | 5 | 1 | 2 | 1 |
| Calidad de utilidad | 20% | 4 | 3 | 2 | 3 |
| **Puntaje** | | **4,4** | 3,1 | 2,9 | 1,8 |

**Checklist:** misma industria, tamaño razonable, **presencia bursátil real**, utilidad normalizada y que **no sea parte relacionada**.

### 3.7 Advertencias
- **Trampa de valor (*value trap*):** un múltiplo bajo no siempre significa una empresa barata. Puede que el mercado esté anticipando un deterioro del negocio.
- **Limitaciones:** si el mercado sobrevalora a los comparables, ese error se traspasa a la empresa analizada. En Chile hay pocos comparables líquidos. El múltiplo no captura marca ni contratos propios, y es sensible a partidas no recurrentes.
- **EV/EBITDAR post NIIF 16:** si se suma el arriendo al EBITDA, también hay que sumar el pasivo por arrendamiento a la deuda neta.

**Mensaje final:** la calidad del análisis está en la **elección de comparables**, no en la fórmula.

---

## 4. Guía complementaria · Comparables por regresión lineal

Es una tercera forma de elegir comparables. En lugar de achicar la muestra, se usa la muestra amplia (sin outliers) y se **controlan estadísticamente** las diferencias entre empresas.

### 4.1 El modelo
```
PUC_i = γ + α1·Payout_i + α2·Beta_i + α3·Crecimiento_i + α4·Crecimiento_i² + ε_i
```
- **PUC** = P/U dividido por el crecimiento de la utilidad.
- Se incluye el crecimiento **al cuadrado** porque su relación con el múltiplo no es lineal.
- Un beta más alto significa más riesgo y, por lo tanto, un múltiplo menor.

### 4.2 Caso Alphabet
Ecuación estimada: `PUC = 1,06 − 0,55 × Beta + 0,58 × Crec. − 0,32 × Crec.²` (payout = 0 para Alphabet)

- Datos de Alphabet: beta 0,93; crecimiento 31% (al cuadrado ≈ 10%).
- PUC estimado = 1,06 − 0,55 × 0,93 + 0,58 × 0,31 − 0,32 × 0,10 ≈ **0,699**
- PUC real = **0,806**, mayor que el estimado → Alphabet está **levemente sobrevalorada** frente a sus comparables.
- Precio implícito = 0,699 × UPA 5,7 × 0,31 × 100 = **$123,51**, contra un precio real de **$144,85** → misma conclusión.

> **Advertencia de lectura:** la guía tiene inconsistencias internas. En la Tabla 2 los coeficientes de payout (−0,55) y beta (−0,32) aparecen invertidos respecto de la ecuación (3). El texto menciona un coeficiente de beta de "−1,14" y un beta de 0,92, mientras la tabla dice 0,93. También hay referencias rotas ("¡Error! No se encuentra el origen de la referencia"). El cálculo final usa −0,55 para el beta y 0,93, que es lo que reproduce el 0,699.

---

## 5. Glosario

Tiene **104 términos** organizados por clase, con índice alfabético. Su numeración de clases es distinta a la del curso SII: Clase 1 = dividendos descontados, 2 = flujos de caja descontados, 3 = crecimiento y WACC, 4 = valoración de una empresa real, 5-6 = valoración relativa. Estos son los términos más útiles, con un ejemplo cada uno:

| Término | Definición breve | Ejemplo (ilustrativo) |
|---|---|---|
| **Capitalización de mercado** | Precio de la acción × acciones en circulación | 1 millón de acciones a $5.000 = $5.000 millones |
| **Deuda financiera neta** | Deuda que paga intereses − efectivo | Deuda 800 − caja 200 = 600 |
| **Valor de la firma (EV)** | Capital propio + deuda financiera neta | 5.000 + 600 = 5.600 |
| **Modelo de Gordon** | P₀ = Div₁ / (rE − g) | Dividendo $100, rE 10%, g 2% → P₀ = 100 / 0,08 = **$1.250** |
| **Crecimiento sostenible** | g = tasa de retención × ROE | Retiene 60%, ROE 15% → g = 9% |
| **CAPM** | rE = rf + β × (rm − rf) | rf 5%, β 1,2, premio 6% → rE = 12,2% |
| **Beta** | Sensibilidad de la acción frente al mercado | β = 1,5: si el mercado sube 1%, la acción sube ~1,5% |
| **Beta ajustado** | β* = ⅔β + ⅓ (tiende a 1) | β = 1,6 → β* = 1,4 |
| **WACC** | Promedio del costo del patrimonio y de la deuda después de impuestos | E = 60%, rE = 12%; D = 40%, rD = 6%, τ = 27% → WACC = 7,2% + 1,75% ≈ **8,95%** |
| **Flujo de caja libre a la firma** | EBIT × (1 − τ) − inversión neta − Δ capital de trabajo | 1.000 × 0,73 − 200 − 50 = **480** |
| **Valor terminal** | FCL(N+1) / (WACC − g) | 500 / (0,09 − 0,03) = **8.333** |
| **Crecimiento estable** | No puede superar el crecimiento de la economía | Suponer 8% perpetuo en Chile no es creíble |
| **VAOC** | Parte del precio que viene del crecimiento futuro | Precio 1.250 − precio sin crecimiento (UPA/rE) = VAOC |
| **Tasa efectiva vs. marginal** | Efectiva = impuestos pagados / utilidad; marginal = tasa legal | Partir con la efectiva y converger a la marginal en el valor terminal |
| **Mediana** | Valor central; mejor que el promedio en múltiplos | {8, 9, 10, 11, 40}: promedio 15,6, mediana **10** |
| **Z-score de un múltiplo** | (Múltiplo − promedio histórico) / desviación estándar | No confundir con el Z de Altman (predicción de quiebra) |
| **Split de acciones** | Divide acciones sin cambiar el valor total | Split 2×1: 100 acciones a $50 pasan a 200 acciones a $25 |

---

## 6. Diez ideas para llevar a una revisión de valoración

1. **Precio es un dato; valor es una estimación.** Primero se revisa la aritmética y luego se discuten los supuestos.
2. **¿Qué valor estima el informe?** (mercado, inversión, razonable o liquidación) **¿A qué fecha?**
3. **¿El método entrega valor de empresa o de patrimonio?** Restar la deuda dos veces es un error caro.
4. **Regla de la misma base:** lo que genera el EBITDA va dentro del valor de la empresa. Revisar el tratamiento de arriendos (NIIF 16).
5. **Minoritarios, asociadas y préstamos de relacionadas van a valor de mercado**, no a libro.
6. **Un punto de tasa o de crecimiento** mueve el valor entre 14% y 20%. Ahí está la discusión.
7. En un ANAV: ¿se revisó **también el pasivo**? ¿Se reconoció el **impuesto diferido**?
8. El enfoque de costos es un **piso**: no captura el goodwill ni el valor de la marca.
9. En múltiplos, la calidad está en los **comparables**: misma industria, liquidez real, **no relacionados**, utilidad normalizada y uso de la mediana.
10. **Un informe que omite alguna de sus 8 partes ya entregó un hallazgo.**
