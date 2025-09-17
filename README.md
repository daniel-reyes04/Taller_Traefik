# Taller_Traefik

# preguntas

## ¿Qué ventaja aporta enrutar por host (dominio) vs por puerto?
una de las ventajas es que al entrutar por puerto no se requiere un DNS, ya que este es el nombre que le damos como direccion, y no una direccion ip tal ves mas dificl para ingresar al momento de buscar la pagina y lo unico que cambia es el puerto mediante se ingresa a la ruta, mientras que enrutar por host o dominio tiene un puerto estandar para todas las peticiones que se pueden llegar a realizar, el trafico se puede dirigir a distintos servicios segun la solicitud 

## ¿Qué diferencia hay entre etiquetas en los servicios y usar archivos de configuración?
La diferencia es como se declaran los enrutamientos, mientras que en las etiquetas en los servicios se configuran y escriben en el mismo archivo que define el servicio y viaja en el mismo contenedor, los archivos de configuracion tienen un archivo aparte en el cual se definen y su configuracion viaja independiente al contenedor 

## como se entera traefik de que habia servicios nuevos?
Para saber que tiene servicios nuevos lo que hace traefik es moniotorizar la infraestructura sobre la cual esta asentado, por ejemplo en un contenedor una vez se ha desplegado el contenedor se extrae la información que necesita para dirigir el tráfico a ese nuevo servicio

## Integrantes
## Daniel Alejandro Reyes León
## Anderson Eduardo Carvajal Oliveros
