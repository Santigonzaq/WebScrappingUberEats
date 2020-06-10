################# WEB SCRAPPING UBER EATS ##################

### Arhivo principal: Scrapping.ipynb
    #En dicho archivo se realiza todo el proceso de webscrapping sobre la página de uberEats. Se aclara la posibilidad
    de extender dicho archivo para varios países, probado especialmente en Colombia, Peru, Ecuador y Chile.

    #Las celdas de dicho archivo están tratadas de explicar lo máximo posible, así como los comentarios respectivos
    en las lineas de código.

    #Este arhchivo produce un CSV de salida, con la información scrappeada de los restaurantes, dicha información está
    Sin limpiar y organizar. Se hicieron 2 corridas, una para Colombia y otra para Ecuador. Dichos CSV, posteriormente 
    los leen los notebooks Limpieza_Datos_xxxx, para cada país respectivamente.

### Limpieza de datos: Limpieza_Datos_xxxx.ipynb:
    #Este archivo lee el insumo que aporta el webscrapping, para limpiar y organizar los datos correspondientes a los 
    restaurantes, ya que después del scrapping llegan muy sucios.

    #Después de realizar la limpieza, se generan archivos de excel de salida Colombia_Limpios , Ecuador_Limpios, con la
    información respectiva para los restaurantes de dichos países.

###Requirements.txt:

    #Se listan todas las librerías necesarias para correr los notebooks.


############## Santiago González Quiroz  cel: 301 202 98 52, sangonzalezqui@unal.edu.co ########################
############## LinkedIn: https://www.linkedin.com/in/santigonzaq/ ########################
    