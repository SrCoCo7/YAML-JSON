# Informacion sobre YAML y JSON
![YAML](https://upload.wikimedia.org/wikipedia/commons/9/92/Yaml_logo.png)
![JSON](https://www.opc-router.com/wp-content/uploads/2020/08/was-ist-json_600x250px-1.jpg)
## YAML
[YAML](https://en.wikipedia.org/wiki/YAML) es un lenguaje de serialización de datos que se usa para escribir archivos de configuración para la implementación de infraestructura.
### Caracteristicas
- **Legibilidad**: Una de las principales ventajas de YAML es su legibilidad. Gracias a su diseño simple y al uso de la indentación para representar la jerarquía de datos, es fácil de leer y entender incluso para aquellos sin experiencia en programación.
- **Facilidad de uso**: Con YAML, puedes representar estructuras de datos complejas con menos líneas de código en comparación con otros formatos como JSON o XML. Esto lo convierte en una opción eficiente y fácil de manejar para los desarrolladores.
- **Interoperabilidad**: Es compatible con múltiples lenguajes de programación como Python, Ruby, Java, JavaScript, entre otros. Esto permite compartir y utilizar datos entre diferentes aplicaciones y plataformas sin problemas.
- **Flexibilidad**: Además de ser fácil de leer y escribir, es bastante flexible. Puedes representar listas, mapas, escalares y otros tipos de datos sin ningún problema, lo que lo hace adecuado para diversas aplicaciones.
### ¿Qué lo hace diferente a otros formatos?
- **Sintaxis más simple***: utiliza una sintaxis menos compleja que JSON y XML, lo que facilita su lectura y escritura. Mientras que JSON y XML utilizan corchetes y etiquetas respectivamente, YAML se basa en la indentación para representar la estructura de datos.
- **Legibilidad y estética***: YAML es más fácil de leer y entender para los humanos en comparación con JSON y XML debido a su diseño simple y el uso de la indentación. Esto facilita el mantenimiento y la colaboración en proyectos de desarrollo de software.
- **Comentarios**: A diferencia de JSON, YAML permite la inclusión de comentarios, lo que facilita la documentación y el entendimiento del código por parte de otros desarrolladores.
  
- ### Ejemplo YAML

```yaml

Marca: Hyundai
Modelo: Tucson
Puertas: 5
Capacidad maletero: 620L
```

## JSON
[JSON](https://en.wikipedia.org/wiki/JSON) es un formato de texto que forma parte del sistema de JavaScript y que se deriva de su sintaxis, pero no tiene como objetivo la creación de programas, sino el acceso, almacenamiento e intercambio de datos. Usualmente es conocido como una alternativa al lenguaje XML.
### Caracteristicas

- JSON es solo un formato de datos.
- Requiere usar comillas dobles para las cadenas y los nombres de propiedades. Las comillas simples no son válidas.
- Una coma o dos puntos mal ubicados pueden producir que un archivo JSON no funcione.
- Puede tomar la forma de cualquier tipo de datos que sea válido para ser incluido en un JSON, no solo arreglos u objetos. Así, por ejemplo, una cadena o un número único podrían ser objetos JSON válidos.
- A diferencia del código JavaScript, en el que las propiedades del objeto pueden no estar entre comillas, en JSON solo las cadenas entre comillas pueden ser utilizadas como propiedades.

  ### Ventajas
- Tiene un formato estructurado y fácil de entender.
- Separa la información o el contenido de su presentación o formato.
- Está diseñado para ser utilizado en cualquier lenguaje o alfabeto.
- La composición de los documentos tiene reglas que son muy estrictas. De esta manera, el análisis sintáctico resulta sencillo.
- Tiene soporte a cualquier tipo de datos.
- Se pueden definir estructuras complejas y reutilizables.

  ### Desventajas
- El formato es muy estricto.
- Lleva más tiempo procesarlo.
- Complejidad de analizador (parser).
- Un error en cualquier parte del formato puede hacer que el documento en su totalidad sea inválido.

  ### Ejemplo JSON
  
  ```json
  
  {
  "coches":[
  {"Marca":"Hyundai", "Modelo":"Tucson"},
  {"Marca":"Kia", "Modelo":"Sportage"},
  {"Marca":"Nissan", "Modelo":"Qashqai"},
  ]
  }

  ```

> [!NOTE]
> ## Diferencias
> | YAML  | JSON |
> | ------------- | ------------- |
> | Los comentarios se indican con un signo de almohadilla/número.  | No se permiten comentarios.  |
> | La jerarquía se indica mediante el uso de caracteres de doble espacio. Los caracteres de tabulación no están permitidos.  | Los objetos y las arrays se indican entre llaves y corchetes.  |
> | Las comillas de string son opcionales, pero admite comillas simples y dobles.  | Las strings deben estar entre comillas dobles.  |
> | El Node raíz puede ser cualquiera de los tipos de datos válidos.  | El Node raíz debe ser una array o un objeto.  |
