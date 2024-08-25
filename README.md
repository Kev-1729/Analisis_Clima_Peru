# Extracción y visualización de los climas del Perú mediante WebScraping
#### Video Demo:  <URL https://www.youtube.com/watch?v=5MPpUO0e-ds&ab_channel=KevinJonathanT.A.>
#### Description: Esta software se encargará de extraer y analizar información climática específica de un departamente y region del Perú mediante el uso de web scraping. Utilizará la biblioteca BeautifulSoup y demas librerias para recopilar datos meteorológicos del Servicio Nacional de Meteorología e Hidrología del Perú (SENAMHI). El usuario podrá ingresar la ubicación de interés, y el software proporcionará una visualización de los datos climáticos de esa zona, facilitando una comprensión más clara y un análisis detallado del patrón climático en ese lugar, tambien el siftware permitira el guardado a lo largo del tiempo de esos datos, para futuras vizualizaciones.
- Primero nuestra función Información(website): Realizará una solicitud HTTP al sitio web proporcionado como parámetro, el cual nos devolverá una respuesta.
- En la función main(): Obtendrá realizara el web scraping para obtener los datos climáticos y lo almacenara en un archivo CSV. También solicitará un input donde se pasara la ubicación que queremos analizar.
- Función actualizar(d, archivo): Actualiza el archivo CSV, evitando duplicados y asegurando que los datos estén actualizados y no vacíos.
- Función grafico_lineplot(df, ubicacion): Generará un gráfico lineal que muestre la evolución de las temperaturas a lo largo de los días.
- Función grafico_puntos(df, ubicacion): Generará un gráfico de dispersión que represente las temperaturas en función de los días en esa ubicacion.
