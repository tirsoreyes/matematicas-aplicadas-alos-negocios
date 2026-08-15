# Clase 5 --- Estimación e intervalos de confianza

## 1. Propósito

Introducir al alumno de manera práctica y sencilla en la estimación
estadística aplicada a negocios.

Al terminar, el estudiante deberá comprender:

-   población,
-   muestra,
-   parámetro,
-   estimación,
-   intervalo de confianza,
-   tamaño de muestra.

No se busca desarrollar estadística avanzada. El objetivo es que el
alumno pueda interpretar resultados y entender cómo una muestra puede
utilizarse para obtener información sobre una población.

## 2. Distribución

  Tiempo         Actividad
  -------------- -----------------------------
  0--15 min      Repaso de clases anteriores
  15--40 min     Población y muestra
  40--65 min     Parámetros y estimación
  65--75 min     Descanso
  75--105 min    Intervalo de confianza
  105--135 min   Interpretación práctica
  135--160 min   Tamaño de muestra
  160--175 min   Caso práctico
  175--180 min   Cierre

------------------------------------------------------------------------

# 3. Introducción

Comenzar con una pregunta:

> Una empresa tiene 10,000 clientes. ¿Es necesario preguntarle a los
> 10,000 cuánto gastan para conocer el gasto promedio?

Probablemente no.

Explicar que una muestra adecuadamente seleccionada puede proporcionar
información útil sobre una población.

------------------------------------------------------------------------

# 4. Población

La población es el conjunto total que nos interesa estudiar.

Ejemplos:

-   todos los clientes de una empresa;
-   todos los trabajadores de una organización;
-   todas las facturas de un periodo;
-   todas las ventas de un negocio.

------------------------------------------------------------------------

# 5. Muestra

Una muestra es una parte de la población.

Ejemplo:

Población = 10,000 clientes.

Muestra = 100 clientes seleccionados.

La finalidad es utilizar información de esos 100 para obtener una
estimación sobre los 10,000.

------------------------------------------------------------------------

# 6. Parámetro

Un parámetro describe una característica de toda la población.

Ejemplo:

El gasto promedio real de los 10,000 clientes.

Normalmente no conocemos ese valor directamente.

------------------------------------------------------------------------

# 7. Estadístico

Un estadístico se calcula utilizando la muestra.

Ejemplo:

El gasto promedio de los 100 clientes seleccionados.

Este valor puede utilizarse para estimar el promedio de toda la
población.

------------------------------------------------------------------------

# 8. Estimación

Estimación puntual:

Utilizar un solo valor como aproximación del parámetro.

Ejemplo:

Una muestra de 100 clientes tiene gasto promedio de \$850.

Nuestra estimación puntual del gasto promedio poblacional es:

**\$850**

Explicar:

> No estamos diciendo que todos los clientes gastan \$850. Estamos
> utilizando la muestra para estimar el promedio de la población.

------------------------------------------------------------------------

# 9. ¿Por qué necesitamos un intervalo?

Una muestra no representa perfectamente a toda la población.

Por eso, en lugar de decir:

> "El promedio es exactamente \$850."

es más razonable decir:

> "Estimamos que el promedio poblacional se encuentra dentro de cierto
> intervalo."

Ese intervalo incorpora incertidumbre.

------------------------------------------------------------------------

# 10. Intervalo de confianza

Un intervalo de confianza es un rango de valores que se utiliza para
estimar un parámetro poblacional con determinado nivel de confianza.

Para mantenerlo sencillo:

-   90%
-   95%
-   99%

El nivel de 95% será el ejemplo principal.

------------------------------------------------------------------------

# 11. Ejemplo conceptual

Una empresa analiza una muestra de clientes y obtiene:

Promedio = \$850

Supongamos que el intervalo de confianza al 95% es:

`$820 a $880`

Interpretación sencilla:

> Con el procedimiento utilizado y un nivel de confianza del 95%,
> estimamos que el promedio poblacional se encuentra dentro de ese
> intervalo.

### Evitar decir

"Hay 95% de probabilidad de que el parámetro esté dentro del intervalo."

Para un curso introductorio es preferible enseñar la interpretación
estándar del procedimiento sin entrar en discusiones avanzadas de
probabilidad.

------------------------------------------------------------------------

# 12. Fórmula introductoria

Para una media, en un escenario sencillo, puede presentarse:

`IC = media ± margen de error`

El margen de error depende de:

-   variabilidad de los datos,
-   tamaño de muestra,
-   nivel de confianza.

No desarrollar teoría avanzada de distribuciones si el grupo no la
necesita.

------------------------------------------------------------------------

# 13. Ejemplo

Una muestra tiene:

Media = \$850

Margen de error = \$30

Entonces:

Límite inferior:

`850 - 30 = 820`

Límite superior:

`850 + 30 = 880`

Intervalo:

`[820, 880]`

------------------------------------------------------------------------

# 14. ¿Qué ocurre si aumenta la muestra?

Idea fundamental:

Una muestra más grande normalmente permite obtener una estimación más
precisa, manteniendo constantes las demás condiciones.

Ejemplo conceptual:

Muestra de 25 → mayor incertidumbre.

Muestra de 100 → menor incertidumbre.

No afirmar que una muestra grande garantiza automáticamente que la
muestra sea representativa; la forma de seleccionar la muestra también
importa.

------------------------------------------------------------------------

# 15. Tamaño de muestra

El programa contempla la determinación del tamaño adecuado de la
muestra.

Para mantener la clase sencilla, presentar la idea antes que la fórmula.

El tamaño de muestra depende, entre otros elementos, de:

-   tamaño de la población,
-   nivel de confianza,
-   margen de error permitido,
-   variabilidad.

------------------------------------------------------------------------

# 16. Fórmula introductoria para población grande

Cuando se trabaja con una población grande y una proporción, puede
utilizarse:

`n = Z²pq / E²`

Donde:

-   `n` = tamaño de muestra;
-   `Z` = valor asociado al nivel de confianza;
-   `p` = proporción esperada;
-   `q = 1-p`;
-   `E` = margen de error.

Para un ejemplo sencillo:

Nivel de confianza 95%:

`Z ≈ 1.96`

Si no conocemos la proporción:

`p = 0.5`

`q = 0.5`

Margen de error:

`E = 0.05`

Entonces:

`n = (1.96² × 0.5 × 0.5)/(0.05²)`

`n ≈ 384.16`

Se redondea hacia arriba:

**n = 385**

------------------------------------------------------------------------

# 17. Interpretación empresarial

Una empresa tiene una población muy grande y quiere realizar una
encuesta.

En lugar de preguntar a miles de personas, puede diseñar una muestra.

La muestra debe:

1.  tener un tamaño adecuado;
2.  seleccionarse de manera apropiada;
3.  utilizar un nivel de confianza;
4.  establecer un margen de error.

------------------------------------------------------------------------

# 18. Actividad práctica con Excel

Utilizar una lista sencilla de 30 o 50 valores de ventas.

Los alumnos deberán:

1.  obtener promedio;
2.  identificar mínimo y máximo;
3.  seleccionar una muestra;
4.  calcular promedio de la muestra;
5.  comparar muestra y población;
6.  comentar las diferencias.

No es necesario utilizar una base de datos real.

------------------------------------------------------------------------

# 19. Caso práctico

Una tienda tiene 2,000 clientes y quiere conocer el gasto promedio.

Se selecciona una muestra de 100 clientes.

El gasto promedio de la muestra es \$900.

Supongamos que el margen de error calculado es \$40.

Intervalo:

`900 ± 40`

`[860, 940]`

Pregunta:

> ¿Qué significa este resultado para el administrador?

Respuesta esperada:

Que el análisis permite estimar el promedio poblacional dentro del
intervalo obtenido, bajo las condiciones del procedimiento.

------------------------------------------------------------------------

# 20. Actividad de cierre

Cada alumno debe inventar una situación contable o empresarial en la que
tenga sentido utilizar una muestra.

Ejemplos:

-   auditoría;
-   satisfacción de clientes;
-   ventas;
-   gastos;
-   tiempos de atención;
-   facturas;
-   inventarios.

Debe identificar:

1.  población;
2.  muestra;
3.  variable que quiere estudiar;
4.  posible promedio o proporción;
5.  por qué sería útil una muestra.

------------------------------------------------------------------------

# 21. Tarea final

Preparar un pequeño caso empresarial de estimación.

Debe contener:

### 1. Contexto

Explicar la situación de una empresa.

### 2. Población

Indicar qué conjunto se desea estudiar.

### 3. Muestra

Proponer una muestra razonable.

### 4. Variable

Indicar qué se va a medir.

### 5. Estimación

Calcular o proponer una estimación.

### 6. Intervalo

Construir un ejemplo sencillo de intervalo de confianza utilizando los
datos proporcionados por el profesor.

### 7. Interpretación

Explicar el resultado en palabras, sin limitarse a presentar la fórmula.

------------------------------------------------------------------------

# 22. Lectura

Solicitar una lectura introductoria sobre:

-   población,
-   muestra,
-   parámetro,
-   estadístico,
-   estimación,
-   intervalo de confianza.

Entregar una síntesis de máximo una página.

El alumno debe incluir:

-   5 conceptos;
-   una aplicación a contaduría;
-   una pregunta que todavía tenga sobre el tema.

------------------------------------------------------------------------

# 23. Portafolio de evidencias

El alumno debe conservar:

-   ejercicios de clase;
-   tablas de Excel;
-   tareas;
-   lecturas;
-   actividades prácticas;
-   conclusiones;
-   caso final.

El programa establece que el portafolio representa **20%** de la
evaluación.

------------------------------------------------------------------------

# 24. Evaluación global sugerida

Respetar los porcentajes establecidos por el programa:

  Evidencia                    Porcentaje
  -------------------------- ------------
  Exámenes                            40%
  Rúbrica                             20%
  Bitácora                            20%
  Portafolio de evidencias            20%
  **Total**                      **100%**

Para la rúbrica puede evaluarse el caso práctico final considerando:

-   identificación correcta del problema;
-   procedimiento;
-   uso de fórmulas;
-   interpretación;
-   presentación;
-   uso adecuado de Excel.

------------------------------------------------------------------------

# 25. Clase 6 reservada

Esta clase no se desarrolla como contenido obligatorio.

Debe conservarse como **sesión de contingencia**.

Puede utilizarse para:

-   aplicar examen;
-   revisar temas difíciles;
-   recuperar contenidos que no hayan quedado claros;
-   revisar portafolios;
-   presentar casos;
-   resolver dudas;
-   recuperar una clase perdida por suspensión;
-   realizar una actividad integradora.

### Recomendación

No anunciar desde el principio que la clase está "libre". Reservarla
como margen docente.

------------------------------------------------------------------------

# 26. Reflexión final para el profesor

El curso debe mantenerse práctico.

La secuencia pedagógica recomendada es:

**Concepto → ejemplo sencillo → fórmula → problema → interpretación →
aplicación contable.**

Evitar:

-   demostraciones matemáticas largas;
-   fórmulas sin contexto;
-   problemas excesivamente complicados;
-   demasiada teoría estadística;
-   ejercicios que requieran conocimientos que el grupo todavía no
    tiene.

El objetivo no es que memoricen muchas fórmulas.

El objetivo es que puedan mirar una situación de negocios y preguntarse:

1.  ¿Qué información tengo?
2.  ¿Qué me están solicitando?
3.  ¿Qué concepto matemático corresponde?
4.  ¿Qué fórmula necesito?
5.  ¿Qué significa el resultado para la empresa?

Ese razonamiento debe ser el hilo conductor de las cinco sesiones.
