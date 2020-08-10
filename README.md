<!--Encabezados-->

# Mi título h1

## Mi título h2

### Mi título h3

#### Mi título h4

##### Mi título h5

###### Mi título h6

<!--Enfasis-->

<!--Italica-->

_Esto es un texto con italica_

<!--Negrita-->

**Esto es un texto con negrita**

<!--Tachado-->

~~Esto es un texto tachado~~

<!--Lista Desordenada <ul>-->

- Naranja

  - Naranja2

- Manzana
- Etc

<!--Lista Ordenada <ol>-->

1. Naranja

   1.1 Naranja2

2. Manzana
3. Etc

<!--Link-->

[omniversal.pro](https://www.omniversal.pro)

<!--Link con Titulo personalizado-->

[omniversal.pro](https://www.omniversal.pro "Titulo personalizado")

> Esta es una cita

<!--Separadores-->

---

---

<!--Mostrar codigo(una linea)-->

`console.log("Hola mundo")`

<!--Mostrar codigo varias lineas-->

```javascript
const express = require("express");
const app = express();
const path = require("path");
const puerto = 3000;

app.use(express.urlencoded({ extended: false }));
app.use(express.json());

app.use(require("./routes/index"));

app.use(express.static(path.join(__dirname, "public")));

app.listen(puerto, () => {
  console.log("Servidor en el puerto: " + [puerto]);
});
```

```python
print("Hola Mundo")
```

```html
<h1>Hola Mundo</h1>
```

<!--Tablas-->

| Las Tablas |  Son  | Geniales |
| ---------- | :---: | -------: |
| col 3      |  gg   |   \$1300 |
| col 4      |       |     \$12 |
| fila 1     | facil |          |

<!--Imagenes-->

![visual studio code logo](vscodelogo.png "vscode logo")

<!--Github Markdown-->

<!--Checklist-->

- [x] Tarea 1
- [x] Tarea 2
- [ ] Tarea 3
- [x] Tarea 4

<!--Etiquetar un usuario-->

@oscarzatell

<!--Emojis-->

:heart_eyes:
