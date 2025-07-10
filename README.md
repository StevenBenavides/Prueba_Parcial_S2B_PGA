# Prueba_Parcial_S2B_PGA

## Prompts Indicados a la IA Chat GPT

* Tengo el siguiente esquema de un data set el cual tiene la siguiente forma:
  ![image](https://github.com/user-attachments/assets/a8d05221-9917-4419-91b1-4221bdeb53e8)

  con este esquema quiero que me ayudes con la consulata de como prodria obtener los meses con mas presencia de lluvias para despues esos datos ordenarlos de menor
  a mayor presencia de lluvia en ellos.


* Necesito que extraigas del año 2006 los datos de la temperatura promedio de cada uno de los meses para después ordenarlos de menor a mayor según sea su temperatura promedio de cada uno.

* Mira tengo la siguiente sentencia en Spark:
  ```
  dfweather.groupBy("Wind Speed (km/h)")
         .count()
         .orderBy("Wind Speed (km/h)")
         .show()
  ```
  quiero que tambien alalize por años como podria hacerlo.
