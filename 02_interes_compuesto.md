# Clase 2 --- Interés compuesto

## 1. Propósito

Que el alumno comprenda la diferencia entre interés simple e interés
compuesto y pueda calcular monto, valor presente y tasa de interés en
problemas sencillos relacionados con ahorro, inversión, créditos y
operaciones contables.

## 2. Distribución de 180 minutos

  Tiempo         Actividad
  -------------- ---------------------------------------------
  0--20 min      Revisión de tarea y repaso
  20--45 min     Diferencia entre interés simple y compuesto
  45--70 min     Fórmula del monto compuesto
  70--80 min     Descanso
  80--110 min    Valor presente
  110--135 min   Tasas y periodos de capitalización
  135--165 min   Ejercicios prácticos
  165--180 min   Cierre y tarea

------------------------------------------------------------------------

# 3. Inicio: repaso

Preguntar:

-   ¿Qué es capital?
-   ¿Qué es interés?
-   ¿Qué es monto?
-   ¿Qué es tasa?
-   ¿Qué fórmula utilizamos para interés simple?

Repasar:

`I = Cit`

`M = C + I`

------------------------------------------------------------------------

# 4. ¿Qué cambia con el interés compuesto?

Explicación sencilla:

En interés simple, el interés se calcula siempre sobre el capital
inicial.

En interés compuesto, los intereses generados se incorporan al saldo y
posteriormente también generan intereses.

Ejemplo conceptual:

Capital inicial: \$10,000\
Tasa: 10%

### Simple

Año 1: \$11,000\
Año 2: \$12,000\
Año 3: \$13,000

### Compuesto

Año 1: \$11,000\
Año 2: \$12,100\
Año 3: \$13,310

El segundo caso crece más porque cada periodo genera interés sobre un
saldo mayor.

------------------------------------------------------------------------

# 5. Fórmula del monto compuesto

`M = C(1+i)^n`

Donde:

-   `M` = monto
-   `C` = capital
-   `i` = tasa por periodo
-   `n` = número de periodos

## Ejemplo

\$10,000 al 10% anual durante 3 años:

`M = 10,000(1.10)^3`

`M = 13,310`

Interés total:

`I = M - C`

`I = 13,310 - 10,000`

`I = 3,310`

------------------------------------------------------------------------

# 6. Interpretación

En contaduría es importante distinguir:

-   cuánto se invirtió,
-   cuánto se acumuló,
-   cuánto representa el rendimiento.

Por eso:

**Capital:** \$10,000\
**Monto:** \$13,310\
**Interés generado:** \$3,310

------------------------------------------------------------------------

# 7. Valor presente

Si conocemos el monto futuro:

`C = M / (1+i)^n`

## Ejemplo

Queremos obtener \$13,310 en 3 años, con tasa de 10%.

`C = 13,310 / (1.10)^3`

`C = 10,000`

------------------------------------------------------------------------

# 8. Comparación simple vs compuesto

Utilizar una tabla:

  Año     Simple   Compuesto
  ----- -------- -----------
  0       10,000      10,000
  1       11,000      11,000
  2       12,000      12,100
  3       13,000      13,310

Pregunta:

> ¿Por qué la diferencia aumenta conforme pasan los años?

Respuesta esperada:

Porque en interés compuesto los intereses se agregan al saldo y también
generan nuevos intereses.

------------------------------------------------------------------------

# 9. Tasas y periodos

La regla más importante:

> La tasa y el número de periodos deben estar expresados en la misma
> unidad.

Si la tasa es mensual, `n` debe representar meses.

Ejemplo:

12 meses al 1% mensual:

`n = 12`

`i = 0.01`

------------------------------------------------------------------------

# 10. Capitalización

La capitalización indica con qué frecuencia se incorporan los intereses
al saldo.

Ejemplos:

-   anual,
-   semestral,
-   trimestral,
-   mensual.

Para mantenerlo sencillo, utilizar ejemplos donde la tasa por periodo
esté claramente indicada.

------------------------------------------------------------------------

# 11. Ejemplo mensual

Una cuenta tiene \$20,000 y genera 1% mensual durante 6 meses.

`M = 20,000(1.01)^6`

`M ≈ 21,230.40`

Interés:

`21,230.40 - 20,000 = 1,230.40`

------------------------------------------------------------------------

# 12. Encontrar la tasa

Partiendo de:

`M = C(1+i)^n`

despejar:

`i = (M/C)^(1/n) - 1`

No profundizar en demostraciones algebraicas.

## Ejemplo

\$10,000 se convierten en \$12,100 en 2 años.

`i = (12,100/10,000)^(1/2)-1`

`i = 0.10`

`i = 10%`

------------------------------------------------------------------------

# 13. ¿Dónde aparece esto en contaduría?

Utilizar ejemplos como:

-   inversiones de una empresa,
-   cuentas bancarias,
-   créditos,
-   saldos acumulados,
-   valor de dinero en el tiempo,
-   comparación de alternativas financieras.

Evitar por ahora productos financieros reales complejos.

------------------------------------------------------------------------

# 14. Actividad con Excel

Pedir a los alumnos crear una hoja con:

  Año     Saldo inicial   Interés   Saldo final
  ----- --------------- --------- -------------
  1              10,000     1,000        11,000
  2              11,000     1,100        12,100
  3              12,100     1,210        13,310

Explicar que Excel no sustituye el razonamiento:

1.  primero identificamos la fórmula;
2.  después verificamos los resultados con la herramienta.

------------------------------------------------------------------------

# 15. Ejercicios

### Ejercicio 1

\$15,000 al 8% compuesto anual durante 3 años.

Calcular monto e interés.

### Ejercicio 2

\$25,000 al 1% mensual durante 12 meses.

Calcular monto.

### Ejercicio 3

Una empresa necesita \$50,000 dentro de 2 años. Tasa compuesta anual de
8%.

Calcular valor presente.

### Ejercicio 4

Una inversión de \$20,000 se convierte en \$24,200 después de 2 años.

Calcular tasa anual compuesta.

------------------------------------------------------------------------

# 16. Respuestas

### 1

`M = 15,000(1.08)^3`

`M ≈ 18,895.68`

`I ≈ 3,895.68`

### 2

`M = 25,000(1.01)^12`

`M ≈ 28,170.70`

### 3

`C = 50,000/(1.08)^2`

`C ≈ 42,866.94`

### 4

`i = (24,200/20,000)^(1/2)-1`

`i = 0.10`

`i = 10%`

------------------------------------------------------------------------

# 17. Cierre

Preguntar:

1.  ¿Cuál es la principal diferencia entre interés simple y compuesto?
2.  ¿Qué significa capitalizar?
3.  ¿Qué representa `n`?
4.  ¿Por qué la tasa debe coincidir con el periodo?
5.  ¿Cuándo utilizaríamos valor presente?

------------------------------------------------------------------------

# 18. Tarea

1.  Resolver un problema de interés compuesto anual.
2.  Resolver un problema mensual.
3.  Comparar una inversión con interés simple y otra con interés
    compuesto.
4.  Elaborar en Excel una tabla de crecimiento durante 5 periodos.

### Evidencia

Guardar el archivo de Excel y una hoja con los procedimientos. Ambos
forman parte del portafolio.

### Lectura

Solicitar lectura introductoria sobre interés compuesto y valor del
dinero en el tiempo. El alumno deberá escribir **5 conceptos que haya
comprendido** y un ejemplo de aplicación contable.

------------------------------------------------------------------------

# 19. Registro docente

Observar especialmente:

-   uso correcto de porcentajes,
-   uso de paréntesis,
-   comprensión del exponente,
-   diferencia entre tasa y periodo,
-   interpretación del resultado.
