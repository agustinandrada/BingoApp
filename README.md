
# BingoApp

Bingo Electron App es una aplicación de escritorio interactiva creada con Electron, diseñada para jugar al Bingo de manera sencilla y entretenida. La aplicación presenta una grilla con números del 1 al 90, permitiendo a los usuarios seleccionar números, verlos destacados y activar eventos especiales como "Bingo" y "Línea" con efectos visuales personalizados.


## Tech Stack

**Client:** HTML5 & CSS3, JavaScript.

**Server:** Electron

## Authors

- [@agustinandrada](https://www.github.com/agustinandrada)


## Documentation

Grilla de Números: Grilla dinámica con números del 1 al 90.

Selección de Números: Al hacer clic en un número, este se resalta y se muestra en grande al costado.

Eventos Especiales:
Bingo: Muestra un modal personalizado con efectos visuales.

Línea: Similar al evento de Bingo, pero para una línea.

Resetear Grilla: Botón para reiniciar la selección de números y restaurar la grilla a su estado original.

Interfaz Intuitiva: Diseño responsivo y atractivo con animaciones suaves al interactuar con los botones.

Efectos Visuales: Modales personalizados para mejorar la experiencia del usuario.

# Installation

### Prerrequisitos
- Node.js (v12 o superior)
- Git

### Installation
```bash
  npm i
```

```bash
  npm start
```



    
## Run Locally

Clone the project

```bash
  git clone https://github.com/agustinandrada/IngresoDomselaar.git
```

Go to the project directory

```bash
  cd IngresoDomselaar
```

Install dependencies

```bash
  npm install
  composer install
```

Create Database and make migrations

```bash
  php artisan migrate --seed
```

Start the server

```bash
  php artisan serve
```


## Roadmap

Una vez que la aplicación esté en funcionamiento, podrás interactuar con ella de la siguiente manera:

#### Seleccionar Números:

Haz clic en cualquier número de la grilla para seleccionarlo.
El número seleccionado se resaltará en verde y se mostrará en grande en el área de visualización.

### Activar Eventos Especiales:

#### Bingo 
Haz clic en el botón "Bingo!" para activar un evento especial que mostrará un modal personalizado indicando que has ganado.
#### Línea
Similar al Bingo, pero para indicar una línea completada.

#### Resetear Grilla:
Haz clic en el botón "Reset" para deseleccionar todos los números y restaurar la grilla a su estado inicial.


## Contact

Si tienes alguna pregunta, sugerencia o problema, no dudes en contactarme:

Nombre: Agustin Andrada
Correo Electrónico: agustinandrada1@gmail.com