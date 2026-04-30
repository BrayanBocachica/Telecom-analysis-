# Telecom-analysis-
Este es un análisis de los registro de ConnectaTel para entender cómo los clientes usan realmente los servicios móviles (llamadas y mensajes) durante el 2024.
Se utilizaron 3 datasets: 'plan' con el nombre de los planes ofrecidos, su precio y sus caracteristicas; 'users' con la información de los usuarios; y 'usage' con el registro de llamadas y mensajes de texto.
Primero se realizó una exploración de cada dataset para saber qué información contenian (número de filas y columnas, tipo de datos). 
En seguida se realizo una identificación de problemas de datos (valores nulos, invalidos o sentinels y una revisión de fechas)
Luego una vez identificados los problemas se realizó una limpieza básica de los datos (normalizar valores y fechas imposibles)
Posteriormente con la limpieza hecha se realizo una agrupación por comportamiento de uso y por edades, junto a un resumen estadistico de la información más relevante 
Y finalmente utilizar distintos gráficos como histogramas y bloxplots para encontrar patrones o correlaciones de manera gráfica
Para resumir los hallazgos se realizo un resumen ejecutivo resumido donde se encuentran también recomendaciones a partir del anális realizado
Todo el código esta listo para ejecutarse por lo que solo basta con abrir el archivo en Google Colab si se requiere
