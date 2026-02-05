# Código en Markdown

Markdown permite mostrar fragmentos de código
sin que se ejecuten.

Esto es fundamental para documentación,
ya que permite explicar ejemplos de forma clara
y segura dentro de GitHub.

---

## Código en línea

El código en línea se usa para resaltar
pequeñas partes de código dentro de un texto.

Se escribe usando una sola comilla invertida.

### Cómo se escribe

```md
Usa `print()` para mostrar texto en Python.
```

### Cómo GitHub lo renderiza

Usa `print()` para mostrar texto en Python.

---

## Bloques de código

Los bloques de código se usan cuando
se necesita mostrar varias líneas de código.

Se escriben usando tres comillas invertidas
antes y después del bloque.

---

## Bloque de código sin lenguaje

Este tipo de bloque se usa cuando
no es necesario resaltar un lenguaje específico.

### Cómo se escribe

```md
con las ``` el texto a escribir ``
```
Texto de ejemplo
Varias líneas
```
es utilizar las ``` en las lineas ```
```

### Cómo GitHub lo renderiza

```
Texto de ejemplo
Varias líneas
```

---

## Bloque de código con lenguaje

Cuando se especifica un lenguaje,
GitHub aplica colores (syntax highlighting).

Esto mejora mucho la legibilidad del código.

### Cómo se escribe

```md
```python
print("Hola mundo")
tambien la parte de abajo se ultiliza ```
```


### Cómo GitHub lo renderiza

```python
print("Hola mundo")
```

---

## Lenguajes comunes en bloques de código

Algunos lenguajes frecuentemente usados:

- python
- javascript
- html
- css
- bash
- json

GitHub reconoce automáticamente estos lenguajes
y aplica el resaltado correspondiente.

---

## Buenas prácticas al mostrar código

- Usa código en línea solo para fragmentos pequeños
- Usa bloques de código para ejemplos completos
- Siempre especifica el lenguaje si es posible
- No mezcles código con texto en el mismo bloque

Un buen uso del código hace que la documentación
sea más clara y profesional.
