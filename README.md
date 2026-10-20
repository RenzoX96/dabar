# Dabar · Hebreo bíblico

Tarjetas de repetición espaciada para el vocabulario de hebreo bíblico por frecuencia.
Transliteración según el sistema de Kelley. Funciona sin internet una vez instalada.

## Archivos

| Archivo | Para qué sirve |
|---|---|
| `index.html` | La app |
| `vocabulario.js` | **Las palabras que ven todos.** Es el único archivo que necesitas editar para agregar vocabulario |
| `sw.js` | Hace que funcione sin internet |
| `manifest.webmanifest` e íconos | Nombre e ícono en la pantalla de inicio |

## Agregar palabras para todos

1. Abre `vocabulario.js` en GitHub y toca el lápiz (Edit).
2. Antes de la última línea (`];`) agrega una línea por palabra:

```
 [61,"שָׁם","šām","Adverbio","Allá, allí; entonces",835,""],
```

Orden: número, hebreo, transliteración, categoría, significado, frecuencia, nota.
Cada línea termina en `],` y los textos van entre comillas.

3. Toca **Commit changes**. En 1–2 minutos todos ven las palabras nuevas.

Atajo: agrega las palabras en la app (Vocabulario → Agregar palabras), luego toca
**Copiar para vocabulario.js** y pega el bloque en el archivo.

## Instalar en el iPhone

Abre el link en Safari → Compartir → Añadir a pantalla de inicio.
