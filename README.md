# Cómo obtuve trabajo remoto gracias a la comunidad de Python (y cómo tú también puedes hacerlo)

Charla relámpago con la temática: Python en Ecuador.
Charla dada en el [meetup de Python Ecuador](https://www.meetup.com/es/python-ecuador/events/253932934/).

## Dependencias

Slides creados con [reveal.js](https://github.com/hakimel/reveal.js).

## Uso

- Navega por los slides con <kbd>espacio</kbd>.
- Entra al modo presentador con <kbd>s</kbd> para ver las notas.

## Colaborar

- Haz un fork del proyecto
- Crea una nueva rama
- Haz los cambios
- ¡Envía un pull request!

### Estructura del proyecto

| Archivo          | Descripción                                  |
|------------------|----------------------------------------------|
| `css/`           | Hojas de estilo usadas por reveal.js         |
| `css/custom.css` | Estilos personalizados para esta diapositiva |
| `img/`           | Imágenes usadas en los slides                |
| `js/`            | Librería reveal.js                           |
| `lib/`           | Librerías usadas por reveal.js               |
| `plugin/`        | Plugins usados en el proyecto                |
| `index.html`     | Contenido de los slides                      |

### Visualización

Para ver los slides basta con abrir el archivo `index.html` en tu navegador,
pero recomiendo hacerlo desde un servidor web.

¿Instalar apache para ver unos slides? No, si tienes python puedes ejecutar el
siguiente comando sobre el directorio donde está el proyecto.

```sh
python -m http.server
```

Y abre tu navegador en <http://localhost:8000>.

Si deseas pre-visualizar los cambios mientras editas el documento,
recomiendo usar [live-preview](https://www.npmjs.com/package/live-server).

Instálalo con `npm install -g live-server` y ejecuta el comando `live-server`
sobre el directorio del proyecto.
