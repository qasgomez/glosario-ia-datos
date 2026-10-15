# Cómo trabajamos en este proyecto

## Reglas de oro

- Nadie escribe directamente en `main`. Todo entra por Pull Request.
- Cada Pull Request necesita al menos una aprobación de otra persona.
- Se revisa el trabajo, no a la persona. Los comentarios son respetuosos y concretos.

## Flujo de trabajo

1. Tomá un Issue y asignátelo.
2. Creá una rama desde el Issue.
3. Escribí o corregí tu archivo en esa rama.
4. Abrí un Pull Request con `Closes #número` en la descripción.
5. Atendé los comentarios de la revisión con nuevos commits en la misma rama.
6. Cuando te aprueben, integrá con *Squash and merge* y borrá la rama.

## Convenciones

- **Nombres de archivo:** minúsculas, sin tildes ni espacios, con guiones (`aprendizaje-supervisado.md`).
- **Mensajes de commit:** una frase que diga qué cambió ("Agrego el término overfitting").
- **Título del Pull Request:** el nombre del término o del cambio.
- **Índice:** cada término nuevo se enlaza en `index.md`, debajo del marcador.

## Contenido

- Escribí con tus palabras. No se copian definiciones textuales de otras fuentes.
- Citá las fuentes que usaste en la sección *Fuentes*.
- Si usaste una herramienta de IA para ayudarte, declaralo en el Pull Request y comprobá cada dato en una fuente confiable: los modelos pueden equivocarse o inventar información.

## ¿Te trabaste?

Abrí un Issue con la etiqueta `ayuda` o mencioná a un compañero con `@usuario`. Preguntar es parte del trabajo.