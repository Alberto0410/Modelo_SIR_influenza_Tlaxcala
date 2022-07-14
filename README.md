# Modelo SIR y la influenza A-H1N1 en Talxcala
En este proyecto se modeló la epidemia del virus de influenza A-H1N1 con base en el modelo SIR. Los datos manejados son tomados de la página oficial del gobierno https://www.gob.mx/salud/acciones-y-programas/informes-semanales-para-la-vigilancia-epidemiologica-de-influenza-2018

Se tomó en particular al estado de Tlaxcala para poder hacer este proyecto.

En este repositorio se encuentran 4 archivos.
1. proyecto.- Este es el notebook en donde se realizó el código del modelo SIR
2. Animacion-virus.- es un pequeño gif de un virus modelado con ayuda de **Paraview**
3. Presentacion.- Es una presentación que fue utilizada para la exposición de este proyecto
4. Presentación.mp4 .- Es la presentación ya mencionada pero en forma de video ya que en la primer diapositiva se encuentra el GIF del virus

Para poder utilizar el modelo SIR se necesitan de tres paramentro conocidos como $\alpha$ y $\beta$, los cuales representan la tasa de recuperación y la tasa de infección respectivamente.

Como dichos parametros son desconocidos decidimos utilizar el método de Grid Search para aproximarlos.

Finalmente, una vez encontrados decidimos tomar los datos de la siguiente temporada (2019-2020) y ver que tan bien ajustaban a dichos datos.
