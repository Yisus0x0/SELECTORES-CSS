# JESUS GRULLON 2021-0915 



## Type selector

```css
p {
  color: blue;
}

```
Selecciona todos los elementos de su tipo

## ID selector
```css
ul#long {}

```
selecciona el element con una id especifica, puede usarse junto al type selector

## Descendante Selector
```css
p strong {}

```
Selecciona todos los elementos dentro de un elemento.

## Class Selector
```css
apple.small {
  color: blue;
}

```
Selecciona la clase usando .className, puede combinarse con los demas selectores.

## Comma Combinator

```css
a, p, .fun {
  color: blue;
}

```
Combina varios elementos con comas y se puede combinar con los demas selectores.

## Universal Selector
```css
*
```
Selecciona todos los elementos. se puede combinar con los demas para filtrar la seleccion

## Adjacent Sibling Selector

```css
A + B
```
Selecciona el elemento B que es hermano adyacente del elemento A. puede ser combinado con los demas selectores.

## General Sibling Selector
```css 
A ~ B
```
Selecciona todos los elementos B que son hermanos del elemento A. Es parecido al anterior pero selecciona todos en vez de solo uno.

## Child Selector
```css
A > B
```
Selecciona todos los elementos B que son hijos directos del elemento A. 

## Pseudo Selectors

- **`:first-child`**: Selecciona el primer hijo de un elemento padre. 
- **`:only-child`**: Selecciona el único hijo de un elemento. 
- **`:last-child`**: Selecciona el último hijo de un elemento padre.
- **`:nth-child()`**: Selecciona el N hijo de su elemento padre, sin importar el tipo de elemento. El N del hijo se especifica en el parentesis
- **`:nth-last-child()`**: Selecciona el N hijo desde el final dentro de un elemento. Cuenta los hijos desde el último hasta el primero.
- **`:first-of-type`**: Selecciona el primer elemento de un tipo dentro de su elemento padre.
- **`:nth-of-type()`**: Selecciona todos los elementos de un tipo específico que están en posiciones pares dentro de su elemento padre.

- **`:only-of-type`**: Selecciona el único elemento de un tipo dentro de su elemento padre.
- **`:last-of-type`**: Selecciona el último elemento de un tipo un elemento padre.
- **`:empty`**: Selecciona todos los elementos de un tipo que no tienen hijos ni contenido alguno.
- **`:not(.small)`**: Selecciona todos los elementos de un tipo que no tienen la clase "small". clase específica.

## Attributes Selectors

- **`[Attribute]`**: Selecciona todos los elementos que tienen el atributo `Attribute`, sin importar su valor. 
- **`plate[Attribute]`**: Selecciona todos los elementos `<plate>` que tienen el atributo `Attribute`. 
- **`[Attribute="Vitaly"]`**: Selecciona todos los elementos que tienen el atributo `Attribute` con el valor exacto "Vitaly".
- **`[Attribute^="Sa"]`**: Selecciona todos los elementos que tienen el atributo `Attribute` cuyo valor comienza con "Sa".
- **`[Attribute$="ato"]`**: Selecciona todos los elementos que tienen el atributo `Attribute` cuyo valor termina en "ato".
- **`[Attribute*="obb"]`**: Selecciona todos los elementos que tienen el atributo `Attribute` cuyo valor contiene la cadena "obb".
