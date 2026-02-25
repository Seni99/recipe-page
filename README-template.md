# Frontend Mentor - Recipe page solution

# Frontend Mentor - Recipe page solution

Esta es una solución al [desafío de la página de recetas en Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Los desafíos de Frontend Mentor ayudan a mejorar las habilidades de codificación construyendo proyectos realistas.

## Tabla de contenidos

- [Frontend Mentor - Recipe page solution](#frontend-mentor---recipe-page-solution)
- [Frontend Mentor - Recipe page solution](#frontend-mentor---recipe-page-solution-1)
  - [Tabla de contenidos](#tabla-de-contenidos)
  - [Descripción general](#descripción-general)
    - [Enlaces](#enlaces)
  - [Mi proceso](#mi-proceso)
    - [Construido con](#construido-con)
    - [Lo que aprendí](#lo-que-aprendí)

## Descripción general


### Enlaces

- URL de la solución: (https://github.com/Seni99/recipe-page.git)
- URL del sitio en vivo: https://github.com/Seni99

## Mi proceso

### Construido con

- Marcado semántico HTML5
- Propiedades personalizadas de CSS
- Flexbox
- Enfoque Mobile-first (Diseño adaptable)

### Lo que aprendí

Durante este proyecto, reforcé varios conceptos de CSS que al principio me daban problemas. Algunas de las cosas más importantes que aprendí a solucionar fueron:

1. **Importar fuentes locales:** Aprendí a usar correctamente la regla `@font-face` y a entender cómo funcionan las rutas relativas (`../`) para enlazar archivos descargados.
2. **Estilizar tablas:** Pude limpiar el diseño de una tabla predeterminada eliminando los bordes globales y aplicando un `border-bottom` sutil solo a las celdas, usando `border-collapse: collapse`.
3. **Personalizar listas:** Aprendí a usar el pseudo-elemento `::marker` para cambiar el color y el grosor de los números y puntos de las listas (`ol` y `ul`) sin afectar al texto principal.

```css
/* Un fragmento de código del que estoy orgulloso: */
.nutrition-table th,
.nutrition-table td {
    border: none;
    padding: 16px;
    text-align: left;
    border-bottom: 1px solid #e2e8f0; 
}

ol li::marker {
    color: #854632;
    font-weight: bold;
}
Colaboración con IA

Para este desafío, utilicé un asistente de IA para que me guiara paso a paso en lugar de darme el código hecho.

Herramienta: Gemini.

Lo utilicé principalmente para depurar el CSS cuando las fuentes no cargaban y para entender cómo seleccionar elementos específicos como los "puntos" de las listas. También me ayudó a recordar los comandos básicos de navegación y de Git en la terminal (cd, git add, git commit).

Resultado: Fue muy útil para entender el porqué de los errores (como el problema de las rutas en las carpetas) en lugar de solo copiar y pegar. También me surgieron muchas dudas que gracias a mis compañer@s pude arreglar. Este proyecto me resultó muy entretenido y didactico.