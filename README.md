# WebscrapingInstagram con Selenium
<br>
(TRADUCIDO AL ESPAÑOL)
<br>
Este repositorio contiene una colección de cuadernos relacionados con el web scraping y la automatización de Instagram.
<br>
<br>
<img src="https://user-images.githubusercontent.com/32107652/209244834-8f60b608-1584-44f0-beb5-fa8b2310b085.jpeg" width=500>

## VERSIÓN ACTUAL (EXTRACCIÓN DE MINIATURAS)
Consultar <b>WebscrapingInstagram_completeUpdated_DEC2022.ipynb</b> generado y probado el 22 de diciembre de 2022.
<br>
Este archivo muestra los comandos de Selenium actualizados, que han cambiado desde el momento en que filmé mi <a href="https://youtu.be/iJGvYBH9mcY" target="_blank">tutorial de YouTube</a> y ahora.
<br>
Para su información, en la nueva versión de Selenium, los comandos con esta sintaxis:

```driver.find_elements_by_tag_name("input")```

fueron reemplazados con comandos de esa sintaxis:

```driver.find_elements(By.TAG_NAME, "input")```

## CURRENT VERSION (IMAGE EXTRACTION)

Consultar <b>ImageExtracting_Updated-DEC2022.ipynb</b> generado y probado el 22 de diciembre de 2022.
<br>
Este archivo incluye nueva sintaxis de Selenium, correcciones a problemas de desplazamiento y una búsqueda de palabras clave más eficiente.
<br>

## VERSIONES ANTIGUAS

<b>PLEASE NOTE:</b> the notebooks below were not updated to the current Selenium syntax!!!

- <b>WebscrapingInstagram_completeNotebook</b>: 
  contained 90% automated code for extracting Instagram <b>Thumbnails</b>
  <br>
  it was working great 2 years ago, now it must be adjusted to the new Selenium syntax.

- <b>WebscrapingInstagram_starterNotebook:</b>
  contains the starter files for the Python Simplified tutorial on Youtube:
  <br>
  https://youtu.be/iJGvYBH9mcY

- <b>ImageExtracting_bot:</b>
  contains a 100% automated code for extracting Instagram <b>Images</b>
  <br>
  as well as ERROR FIXES and WIDER FUNCTIONALITY
  <br>
  must be adjusted to the new Selenium syntax.

- <b>Commenting_bot:</b>
  contains a 100% automated code for commenting on all photos from a certain hashtag presented live with We Are Growth Hackers:
  <br>
  https://youtu.be/XnEgVZsZgco


