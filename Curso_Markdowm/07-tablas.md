# Tablas en Markdown

Las tablas permiten organizar información
en filas y columnas de forma clara.

Se utilizan cuando es necesario mostrar
datos estructurados de manera comparativa.

GitHub renderiza las tablas automáticamente
cuando se escriben con la sintaxis correcta.

---

## ¿Qué es una tabla en Markdown?

Una tabla es una estructura formada por:
- Columnas
- Filas
- Encabezados

Cada columna representa un tipo de información,
y cada fila representa un registro.

---

## Tabla básica

Una tabla básica tiene:
- Una fila de encabezados
- Una fila separadora
- Una o más filas de contenido

### Cómo se escribe

```md
| Nombre | Lenguaje |
|--------|----------|
| Ana    | Python   |
| Luis   | Java     |
```

### Cómo GitHub la renderiza

| Nombre | Lenguaje |
|--------|----------|
| Ana    | Python   |
| Luis   | Java     |

---

## Alineación de columnas

Markdown permite alinear el contenido
de las columnas usando dos puntos `:`.

- Izquierda: `:---`
- Centro: `:---:`
- Derecha: `---:`

### Cómo se escribe

```md
| Nombre | Nivel | Puntaje |
|:-------|:-----:|--------:|
| Ana    | Alto  | 95      |
| Luis   | Medio | 80      |
```

### Cómo GitHub la renderiza

| Nombre | Nivel | Puntaje |
|:-------|:-----:|--------:|
| Ana    | Alto  | 95      |
| Luis   | Medio | 80      |

---

## Cuándo usar tablas

Las tablas son recomendables cuando:

- Comparas valores
- Muestras resultados
- Organizas datos repetitivos

No son recomendables para texto largo.

---

## Buenas prácticas al usar tablas

- Usa encabezados claros
- Mantén las tablas simples
- Evita tablas muy grandes
- No uses tablas para maquetar texto

Las tablas bien usadas
mejoran la claridad del documento.
