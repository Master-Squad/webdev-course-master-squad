# Lección 7: Errores Comunes y Consejos Finales

# Error Común N°1: Olvidar cerrar etiquetas

Cuando una etiqueta HTML no se cierra correctamente, el navegador puede interpretar el contenido de manera inesperada.

## ❌ Código incorrecto

```html
<h1>Juana Del Valle

<p class="descripcion">
Estudiante de Cocina
```

## ✅ Código correcto

```html
<h1>Juana Del Valle</h1>

<p class="descripcion">
Estudiante de Cocina
</p>
```

### Recomendación

Verifica siempre que cada etiqueta tenga una apertura y un cierre correspondiente.

---

# Error Común N°2: Clase mal escrita

HTML y CSS deben utilizar exactamente el mismo nombre de clase.

## ❌ Código incorrecto

```html
<p class="descripccion">
Estudiante de Cocina
</p>
```

```css
.descripcion{
    color:#3498db;
}
```

## ✅ Código correcto

```html
<p class="descripcion">
Estudiante de Cocina
</p>
```

```css
.descripcion{
    color:#3498db;
}
```

### Recomendación

Una sola letra diferente impedirá que los estilos se apliquen correctamente.

---

# Error Común N°3: Error de sintaxis en CSS

Los bloques de CSS deben escribirse utilizando llaves.

## ❌ Código incorrecto

```css
h1
color:#2c3e50;
```

## ✅ Código correcto

```css
h1{
    color:#2c3e50;
}
```

### Recomendación

Revisa siempre que cada selector tenga sus llaves de apertura y cierre.

---

# Consejos para Principiantes

## Consejo 1: Practica constantemente

La mejor forma de aprender programación es creando proyectos y experimentando con nuevas ideas.

---

## Consejo 2: Realiza cambios pequeños

Haz cambios pequeños y prueba el resultado frecuentemente.

Esto te permitirá encontrar errores más rápido y comprender mejor cómo funciona tu código.

---

## Consejo 3: Mantén tu código ordenado

Utiliza una indentación adecuada y organiza tu código para que sea más fácil de leer y mantener.

Ejemplo:

```html
<div class="perfil">
    <h1>Juana Del Valle</h1>
    <p>Estudiante de Cocina</p>
</div>
```

---

# Próximos Pasos

Ahora puedes continuar aprendiendo sobre:

- Diseño web responsivo.
- Flexbox y CSS Grid.
- JavaScript.
- Frameworks modernos de desarrollo web.

---

# Felicitaciones

¡Felicitaciones por completar el curso **Fundamentos de Desarrollo Web**!

Esperamos que este sea el inicio de muchos proyectos y nuevos aprendizajes en el mundo de la programación.

Muchas gracias por acompañarnos y ¡hasta la próxima!
