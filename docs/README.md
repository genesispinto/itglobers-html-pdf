<h1 align="center"> Visualizador de PDF</h1>

Muestra un archivo PDF 

____________
## :hammer:Configuración del proyecto

- :pushpin: `Paso 1 - Configuración Básica`: 
  Asegurarse que esta en el ambiente correcto de vtex

- :pushpin: `Paso 2 - Clone estos archivos` con el link proporcionado en el repositorio 
- :pushpin: `Paso 3 - Instalacion de nodos de react`: 
  Ingresar a la carpeta de react ejecutando el comando en consola ```$ cd react```
  y dentro de esta instalar lo siguiente: <br>
  :pencil2:`1` Nodos de react ejecutando en consola el comando ```$ yarn``` <br>
- :pushpin: `Paso 4 - Volver a carpeta principal del proyecto y linkear app a su Tienda`: 
  Ejecute comando en consola ```$ vtex link```
  ________
__________
## :key:Dependencias

1. Store-theme: Coloque esta dependencia en el archivo `manifest.json` de su tienda

```ruby
  "dependencies": 
  {
    "itglobers.pdf-reader": "0.x"
  }
```
## :key:Manera de llamar al componente: 
Ejemplo:
```
"flex-layout.row#example":{
    "children":["pdf-reader"]
    }
```

## :black_nib:Autor

 [<sub>Génesis Pinto</sub>](https://github.com/genesispinto) 
