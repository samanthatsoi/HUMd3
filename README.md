## Documentacion por graph.html <br />
_Por: Samantha Tsoi_ <br />
Fecha de la última actualización: 05/07/2019 <br/>
<br />

#### Resumen:
<br />
Hacer los gráficos con los archivos cargados de 'Seguimiento-Gestion-HUMDrive.xlsx'. El código hace tres gráficos. Los gráficos se separan por los valores. Por ejemplo, el primer gráfico tiene las categorías más usadas en 'Seguimiento-Gestion-HUM.xlsx' y el última tiene las categorías menos usadas. A ver los puntos exactos en los gráficos, puedes hover a cualquier punto. Igual a clarificar y diferenciar las líneas en los gráficos, puedes hover a cualquier línea. <br />

<br />

#### Antes de ejecutarlo:
<br />
1. Asegúrate de que ya corras el 'Seguimiento-Gestion-HUMDrive.ipynb' con las instrucciones incluido para que tengas los datos más actualizados. <br />
2. Encontrarás cuatro archivos hechos de la ejecución de "'Seguimiento-Gestion-HUMDrive.ipynb'" en la carpeta "HUMd3". 
![colabfolderview](https://user-images.githubusercontent.com/8455299/60748436-da9be180-9f5b-11e9-9df8-0e99264bb4b8.png)
<br />
3. Carga los archivos y ponlos en la misma carpeta donde 'graph.html' se ubica. 
![filessamefolder](https://user-images.githubusercontent.com/8455299/60749790-2d31c980-9f6d-11e9-9e75-084166fb0291.png)
 <br />
 
#### Para ejecutarlo:
<br />
1. Abre la Terminal en tu Mac (o Console en tu Windows/PC).
<br /> <br />
2. Entra la carpeta donde los archivos ('graph.html', 'df1819.csv', 'dfcito.csv', 'dffilo.csv' y 'dfisimo.csv') se ubican. <br />
...2a. Usa 'cd [nombre_de_carpeta]' a entrar una carpeta. <br />
...2b. Usa 'cd ..' a regresar a la última carpeta. <br />
...2c. Puede encontrar la carpeta actual tipeando 'pwd' en tu Terminal (en Windows/PC, el comando es 'cwd'). <br />
...2d. Puede encontrar los archivos y las carpetas en la carpeta actual tipeando 'ls' en tu Terminal (Mac) o Console (Windows/PC)

Ejemplo:
![linux](https://user-images.githubusercontent.com/8455299/59278378-dff15f00-8c2f-11e9-91be-dc415e9b66db.png)
<br />
<br />
3. Cuando has llegado a la carpeta donde los archivos se ubican, escribe 'python3 -m http.server' en el Terminal o Console.

![http server](https://user-images.githubusercontent.com/8455299/59278591-48d8d700-8c30-11e9-8b47-fa0ba643ec4c.png)
<br />
<br />
4. Abre un browser (Chrome, Safari, etc.) y va a http://0.0.0.0:8000/graph.html <br>
Listo!

![listo](https://user-images.githubusercontent.com/8455299/59278780-a5d48d00-8c30-11e9-8271-22360dac9b08.png)