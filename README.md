# ev2_jorquera-ugalde
# Evaluación Parcial 2 

## Nombre: Valentina Jorquera, Antonella Ugalde  
## Carrera: Informática Biomédica  
## Ramo: Big Data 
## Docente: Fernando Fuentes
## Fecha: 01/06/2025

---

## 🧠 Introducción

En esta evaluación pusimos en práctica los conocimientos adquiridos durante las sesiones de clases, especialmente los relacionados con el desarrollo web utilizando HTML y CSS. El objetivo fue construir un sitio web básico con estructura y estilo, aplicando buenas prácticas de codificación y diseño.

## Creación del Bucket
Ingresamos al taller GSP823 en Google Skills Boost para abrir la consola de google cloud. Con el usuario que este nos da abrimos la consola de google en una pestaña incognita e iniciamos sesión con este.

![image](https://github.com/user-attachments/assets/ab554310-09a6-4412-a071-870364a609c3)

## Conexión a Bigquery y conexion de usuario
Nos dirigimos a Bigquery y subimos la base de datos transformada a CSV. 

![image](https://github.com/user-attachments/assets/ec233137-9181-40bb-8ba0-5930db2fd80a)

Aquí se va dando el paso a paso para poder llegar a la asignación de roles
![Captura de Pantalla 2025-07-01 a la(s) 19 49 56](https://github.com/user-attachments/assets/20e76144-7b8e-4432-b8ed-69b6de3472f3)

![Captura de Pantalla 2025-07-01 a la(s) 19 51 27](https://github.com/user-attachments/assets/8987cebb-06a3-4d32-8830-5fda71d12b0d)

## DataPrep
Nos dirigimos a dataprep que se encuentra al ingresar al menú > View all products > Analytics. Aquí creamos un flujo con el archivo que subimos anteriormente.

![Captura de Pantalla 2025-07-01 a la(s) 19 52 41](https://github.com/user-attachments/assets/ea07b4e5-c842-4cf9-9e0e-473f8827930a)

## Limpieza de base de datos.
Hacemos 7 limpiezas, en donde se eliminaron columnas con los datos considerados como ismissing e ismismatched. Tambien la tabla llamada "state/province" se cambia a "state_province". Así finalmente obtenemos 100% de valores válidos. 

![Captura de Pantalla 2025-07-01 a la(s) 19 53 33](https://github.com/user-attachments/assets/5cdb777b-d41b-4dfe-ba77-42c97cc20a28)
![Captura de Pantalla 2025-07-01 a la(s) 19 54 11](https://github.com/user-attachments/assets/dbad5517-a904-4d0f-9d57-ae82cc70557e)

## Creación de gráficos:

### Gráfico 1

Este gráfico muestra la distribución geográfica y la frecuencia de avistamientos de OVNIs tanto en Estados Unidos como en el resto del mundo. California (CA) lidera con 3.561 reportes, seguida por Washington (WA) con 1.555 y Florida (FL) con 1.544. El mapa evidencia una alta concentración de avistamientos en América del Norte, especialmente en la costa oeste de EE.UU. Aunque se registran reportes en otras regiones del mundo, su frecuencia es considerablemente menor. Esto sugiere que Estados Unidos, y en particular algunos de sus estados, concentra la mayor parte de la actividad reportada en torno a fenómenos aéreos no identificados.

![Captura de Pantalla 2025-07-01 a la(s) 19 56 17](https://github.com/user-attachments/assets/d0939731-95f2-4e4c-9aae-bccf9a755bae)

### Gráfico 2

Este gráfico presenta un análisis realizado con BigQuery sobre avistamientos de OVNIs, clasificados según la forma descrita por los testigos. Llama la atención que la categoría más común corresponde a "light" (luces), con 5.440 reportes que representan el 37,5% del total. También se observan frecuentemente formas definidas como triángulos (17,8%), círculos (17,1%) y bolas de fuego (14,6%). Por otro lado, las formas menos frecuentes se agrupan bajo la categoría "other" (13%). Estos datos indican que muchos avistamientos corresponden a fenómenos luminosos difíciles de definir con claridad.

![Captura de Pantalla 2025-07-01 a la(s) 19 55 05](https://github.com/user-attachments/assets/d3b28f24-6e16-42e5-bca2-5d361e7f5e5f)

### Gráfico 3

El gráfico representa un análisis de avistamientos de OVNIs realizado con BigQuery, organizados por año (Year) y número de reportes (Sightings). Se evidencia una distribución desigual, con ciertos años registrando significativamente más avistamientos. Destaca el año 1, con 10.163 reportes, lo que probablemente refleja datos faltantes o errores en el registro. También sobresalen los años 3 y 91, con más de 6.000 y 5.900 reportes respectivamente. Esta variabilidad sugiere posibles inconsistencias en la base de datos, errores de codificación o años particulares marcados por un aumento en el interés público o en la ocurrencia de fenómenos anómalos.

![Captura de Pantalla 2025-07-01 a la(s) 19 55 42](https://github.com/user-attachments/assets/5b9e5c3e-dd42-40ff-bce3-3ccef2ce6fb2)



