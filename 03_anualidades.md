# Clase 3 --- Anualidades

## 1. Propósito

Que el alumno comprenda las anualidades como pagos o depósitos
periódicos y pueda resolver casos sencillos de anualidades simples
ciertas, anticipadas y diferidas.

## 2. Distribución

  Tiempo         Actividad
  -------------- -------------------------------
  0--20 min      Repaso de interés compuesto
  20--45 min     Concepto de anualidad
  45--75 min     Anualidad ordinaria
  75--85 min     Descanso
  85--115 min    Valor futuro y valor presente
  115--140 min   Anualidad anticipada
  140--160 min   Anualidad diferida
  160--180 min   Caso práctico y cierre

------------------------------------------------------------------------

# 3. ¿Qué es una anualidad?

Explicación:

Una anualidad es una serie de pagos o depósitos realizados en intervalos
regulares.

Ejemplos:

-   pagos mensuales de un crédito,
-   depósitos mensuales de ahorro,
-   pagos de una renta,
-   aportaciones periódicas.

No significa necesariamente que los pagos sean anuales. Pueden ser
mensuales, trimestrales, etc.

------------------------------------------------------------------------

# 4. Anualidad simple cierta

Explicar que:

-   los pagos son iguales,
-   los periodos son regulares,
-   conocemos la cantidad de pagos,
-   la tasa corresponde al periodo.

Ejemplo:

Una persona deposita \$1,000 cada mes durante 12 meses.

Tenemos:

`R = 1,000`

`n = 12`

Si la tasa es 1% mensual:

`i = 0.01`

------------------------------------------------------------------------

# 5. Valor futuro de una anualidad ordinaria

Cuando los depósitos se hacen al final de cada periodo:

`VF = R [((1+i)^n - 1)/i]`

Donde:

-   `VF` = valor futuro
-   `R` = pago periódico
-   `i` = tasa por periodo
-   `n` = número de pagos

## Ejemplo

Depósito mensual de \$1,000 durante 12 meses al 1% mensual:

`VF = 1,000[((1.01)^12 - 1)/0.01]`

`VF ≈ 12,682.50`

------------------------------------------------------------------------

# 6. Interpretación contable

El alumno debe distinguir:

-   total aportado,
-   intereses generados,
-   saldo final.

En el ejemplo:

Aportaciones:

`1,000 × 12 = 12,000`

Valor futuro:

aproximadamente \$12,682.50

Interés acumulado:

aproximadamente \$682.50

------------------------------------------------------------------------

# 7. Valor presente de una anualidad

Cuando queremos saber cuánto vale hoy una serie de pagos futuros:

`VP = R [(1-(1+i)^(-n))/i]`

## Ejemplo

Pagos de \$1,000 mensuales durante 12 meses, con 1% mensual:

`VP ≈ 11,255.08`

Interpretar:

> Aunque la suma de pagos sea \$12,000, su valor presente es menor
> porque el dinero tiene un valor temporal.

------------------------------------------------------------------------

# 8. Anualidad anticipada

En una anualidad anticipada el pago se realiza al **inicio** de cada
periodo.

Ejemplos:

-   renta pagada al comenzar el mes,
-   algunos contratos de arrendamiento,
-   determinados planes de ahorro.

Fórmula del valor futuro:

`VF_anticipada = VF_ordinaria(1+i)`

Fórmula del valor presente:

`VP_anticipada = VP_ordinaria(1+i)`

Explicar la idea antes de la fórmula:

> Si cada pago ocurre un periodo antes, cada pago tiene un periodo
> adicional para generar rendimiento.

------------------------------------------------------------------------

# 9. Anualidad diferida

En una anualidad diferida los pagos no comienzan inmediatamente; existe
un periodo de espera.

Ejemplo:

Una persona obtiene un beneficio financiero hoy, pero empieza a realizar
pagos dentro de 6 meses.

Para resolverla:

1.  calcular el valor de la anualidad en el momento en que comienza;
2.  llevar ese valor al presente si es necesario.

No introducir fórmulas complicadas si el grupo todavía no domina el
concepto.

------------------------------------------------------------------------

# 10. Caso contable

Una empresa decide crear un fondo para comprar equipo dentro de 2 años.

Depositará \$2,000 mensuales en una cuenta que paga 1% mensual.

Preguntar:

1.  ¿Es una anualidad?
2.  ¿Cuántos pagos habrá?
3.  ¿Cuál es la tasa por periodo?
4.  ¿Los depósitos se hacen al inicio o al final?

Después resolver como anualidad ordinaria.

------------------------------------------------------------------------

# 11. Actividad en Excel

Crear:

  Mes     Depósito   Saldo
  ----- ---------- -------
  1          2,000     ...
  2          2,000     ...
  3          2,000     ...

Pedir que calculen el crecimiento del fondo.

El objetivo es que vean que la fórmula representa un proceso que también
puede visualizarse periodo por periodo.

------------------------------------------------------------------------

# 12. Ejercicios

### A

Depositar \$1,500 mensuales durante 12 meses al 1% mensual. Calcular
valor futuro.

### B

Una persona recibirá 12 pagos mensuales de \$2,000. Tasa de 1% mensual.
Calcular valor presente.

### C

Repetir A suponiendo que los depósitos se realizan al inicio de cada
mes.

### D

Diseñar un ejemplo de anualidad diferida relacionado con un negocio.

------------------------------------------------------------------------

# 13. Respuestas aproximadas

### A

`VF = 1,500[((1.01)^12-1)/0.01]`

`VF ≈ 19,023.74`

### B

`VP = 2,000[(1-(1.01)^(-12))/0.01]`

`VP ≈ 22,510.16`

### C

`VF anticipada ≈ 19,213.98`

### D

La respuesta puede variar. Lo importante es identificar:

-   periodo de espera,
-   pagos,
-   frecuencia,
-   tasa.

------------------------------------------------------------------------

# 14. Preguntas de comprensión

1.  ¿Qué diferencia hay entre una anualidad y un pago único?
2.  ¿Qué significa que una anualidad sea ordinaria?
3.  ¿Qué significa anticipada?
4.  ¿Qué significa diferida?
5.  ¿Por qué una anualidad anticipada produce un valor mayor que una
    ordinaria con las mismas condiciones?

------------------------------------------------------------------------

# 15. Tarea

Elaborar un caso de una empresa o persona relacionado con:

-   ahorro,
-   crédito,
-   renta,
-   inversión.

El caso debe contener:

1.  cantidad del pago;
2.  frecuencia;
3.  número de pagos;
4.  tasa;
5.  pregunta financiera;
6.  procedimiento;
7.  resultado;
8.  interpretación.

### Lectura

Lectura introductoria sobre anualidades simples, anticipadas y
diferidas.

Entregar una ficha de una página con:

-   definición de cada tipo,
-   diferencia,
-   ejemplo.

### Evidencia

La ficha y el problema resuelto se incorporan al portafolio.

------------------------------------------------------------------------

# 16. Registro docente

Verificar que los alumnos no memoricen únicamente fórmulas. Antes de
calcular deben identificar:

**¿Qué tipo de operación tengo?**

-   pago único,
-   anualidad ordinaria,
-   anualidad anticipada,
-   anualidad diferida.
