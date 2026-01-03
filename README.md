# Regresion_Lineal_Datos_Medicos PCA
Lo que hice en este código fue básicamente armar un "predictor" de enfermedades. Imagina que es como enseñarle a alguien a diagnosticar pacientes basándose en sus análisis clínicos.

Aquí te lo explico súper fácil:

Paso 1: Organizar los datos. Agarré una tabla con info de pacientes (como azúcar en la sangre y edad) y "limpié" los números para que todos estén en la misma escala. Así, la computadora no se confunde con valores muy altos o muy bajos.

Paso 2: Hacerlo visual (PCA). Como eran muchos datos por cada persona, los "comprimí" para poder verlos en una gráfica 3D. Es como tomar una foto de un objeto desde el mejor ángulo para entender su forma; así pude ver cómo se separan los pacientes sanos de los que tienen diabetes.

Paso 3: El examen. Dividí los datos en dos: una parte para que la computadora "estudie" y otra para hacerle un examen con casos que nunca ha visto.

Paso 4: La predicción (Regresión Lineal). Usé un modelo que traza una línea de tendencia para intentar adivinar el resultado. Al final, calculé qué tanto se equivocó (el error RMSE), que me dio 0.48.

En resumen: Limpié la información, la resumí para poder verla en una gráfica y entrené a mi computadora para que aprenda a predecir quién tiene diabetes con un margen de error bastante bajo.

<img width="445" height="301" alt="image" src="https://github.com/user-attachments/assets/92503b0c-cf9f-4ba8-8589-7f0c6d342ee3" />
