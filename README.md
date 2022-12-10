# Descripción.
Repositorio para el proyecto integrador del curso Ingeniería de características de la Maestria en Ciencia de Datos de la Universidad de Sonora. En este nos interesa analizar como ha evolucionado la diabetes en el Estado de Sonora. Poder observar en que municipios hay más defunciones por esta enfermedad.

# Descripcion de la información
Se quiere analizar analizar la distribución de las defunciones por diabetes en el Estado de Sonora, pero hay pocas fuentes en las que se puede encontrar información. Se encontraron dos fuentes que son:  
1. La [página](https://www.inegi.org.mx/programas/mortalidad/#Datos_abiertos) de datos abiertos del INEGI que contiene la información de las defunciones.

2. [Cuéntame de México](https://cuentame.inegi.org.mx/monografias/informacion/son/poblacion/default.aspx?tema=me&e=26): esta página contiene la información que nos interesa sobre el número de habitantes por municipio en Sonora en el 2020, si bien se podrían encontrar estos datos en otro lugar y con un formato más manejable, se decidió usar la información de esta página  para mostrar además como es el método de web scraping para extraer los datos de una tabla en formato html y almacenar estos en un dataframe.

Si quieres ver como se descarga la información, puedes consultar [esta libreta](https://github.com/Fernando-LunaP/Proyecto_Integrador_Ing_Caracteristicas/blob/main/Codigo/01_Descargando_los_datos.ipynb)

# Limpieza de datos
En esta parte se realizaron varias tareas en la siguiente [libreta](https://github.com/Fernando-LunaP/Proyecto_Integrador_Ing_Caracteristicas/blob/main/Codigo/02_Limpieza_de_datos.ipynb) para obtener un dataframe que contenga únicamente nuestras variables de interés. Esta información se almacenó en archivos parquet. En esta [carpeta](https://github.com/Fernando-LunaP/Proyecto_Integrador_Ing_Caracteristicas/tree/main/datos) puedes ver los datos generados por las libretas o puedes ejecutarlas y obtendrás el mismo resultado.

# Análisis exploratorio de datos
Una parte importante de un proyecto de ciencia de datos es analizar la información que cae en nuestras manos, muchas veces puede que nos de una sorpresa. Se realizó un EDA automático.

<img src="https://github.com/Fernando-LunaP/Proyecto_Integrador_Ing_Caracteristicas/blob/main/Imagenes/Matriz%20de%20correlaci%C3%B3n.JPG" width="750">

Se realizó también el PCA, el proyecto realmente no lo requiere, solo unas funciones muy sencillas de agregación, pero siempre es bueno practicar, no se sabe en que momento se pueda requerir!

# Visualización
Para esta parte se realizó un tablero utilizando tableau para mostrar todas las estadísticas que consideramos relevantes. Tiene interacción pero realmente es muy sencillo, sin necesidad de tanta complejidad. Lo puedes consultar [aquí](https://public.tableau.com/app/profile/fernando.luna.ponce/viz/DiabetesenSonora/DashboardDiabetesSonora)


