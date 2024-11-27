# Pseudo class and elements

## Pseudo class

A pseudo-class is used to define the special state of an element.

```css
selector:pseudo-class {
  property: value;
}
```

1. `hover`

```css
a:hover {
  color: blue;
}
```

2. `:focus`

```css
input:focus {
  border-color: green;
}
```

3. `:active`

```css
input:focus {
  border-color: green;
}
```

### Example

```js
/* hold click */
ul li:active {
  /* short */
  transition: all ease-in 200ms;
  background-color: red;
}
input {
  border: 1px solid rgba(117, 117, 117, 0.389);
  border-radius: 4px;
  padding: 8px;
}
/* when i focused/hold touch/click the element */
input:focus {
  background-color: red;
}

/* doing something with element */
input:active {
  box-shadow: 0 0 8px rgba(0, 0, 0, 0.444);
  outline: none;
  border: none;
}
```

## Pseudo Element

1. `:nth-child(n)`

```css
li:nth-child(2) {
  font-weight: bold;
}
```

2. Pseudo Element 

```css

```
