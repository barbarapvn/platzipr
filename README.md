# Platzom

Platzom es un idioma inventado para el [curso de Fundamentos de JavaScript](https://platzi.com/js) de [Platzi](https://platzi.com), el mejor lugar de educación online.

## Descripción del idioma

- Si la palabra termina en "ar", se le quitan esas dos letras.
- Si la palabra inicia con Z, se le añade "pe" al final.
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión medio.
- Por último, si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra, pero intercalando letras mayúsculas y minúsculas.

## Instalación

El readme siempre tiene que tener instrucciones de instalación.

```
npm install platzom
```

## Uso

```
import platzom from 'platzom'

platzom("Programar") // Program
```

## Créditos

Autores

## Licencia

[MIT](https://opensource.org/licenses/MIT)