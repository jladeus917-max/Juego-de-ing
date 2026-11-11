# Juego Sin Internet de Ingeniería en Energía

**Carrera de Ingeniería en Energía - Universidad de Guayaquil (Ecuador)**

Un juego educativo offline tipo RPG de carrera universitaria donde eres un estudiante de Ingeniería en Energía y debes aprobar todas las materias del pensum (9 semestres, 153 créditos) para graduarte.

![Dashboard](screenshot-dashboard.jpg)

## Características

- **100% Offline**: No requiere internet. Abre `index.html` en cualquier navegador moderno.
- **Sistema de Semestres**: Avanza semestre por semestre.
- **Créditos y Notas**: Cada materia tiene créditos (CR2/CR3/CR4). Obtén calificaciones al aprobar.
- **Barra de Progreso**: Visualiza tu avance hacia los 153 créditos.
- **Minijuegos Educativos**: Cuestionarios de opción múltiple por materia para "estudiar" y aprobar.
- **Guardado Local**: Usa `localStorage` para persistir tu progreso (nombre, materias aprobadas, notas, semestre actual).
- **Estilo Universitario**: Colores azul/verde energía, interfaz tipo dashboard, iconos representativos (emoji), animaciones suaves.
- **Graduación**: Completa todas las materias para obtener tu título de Ingeniero en Energía.

![Quiz](screenshot-quiz.jpg)

## Pensum Basado en

El juego está basado en la estructura del pensum de la carrera de **Ingeniería en Energía** de la **Universidad de Guayaquil**, organizado en campos:

- Campo Básico General Científico Disciplinar
- Campo Básico Específico Profesional
- Campo Socio Humanístico
- Campo Investigativo

Incluye materias como Algoritmos y Programación, Cálculo (Diferencial, Integral, Multivariado), Física, Termodinámica, Energías Renovables (Solar, Eólica, Hidráulica, Geotérmica, Hidrógeno), Smart Grids, Investigación, y más. Total 153 créditos en 9 semestres.

**Nota**: "Fracciones Diferenciales" se interpreta como Ecuaciones Diferenciales. Las electivas son genéricas con preguntas de energía sostenible.

## Instalación y Uso

1. Descarga o clona este repositorio.
2. Abre el archivo `index.html` directamente en tu navegador (Chrome, Firefox, Edge, Safari).
3. Ingresa tu nombre de estudiante.
4. Estudia las materias del semestre actual respondiendo los cuestionarios.
5. Aprueba (mínimo 70%) para sumar créditos y avanzar.
6. Tu progreso se guarda automáticamente. Puedes cerrar y continuar después.

No se necesita instalar nada ni conexión a internet.

## Capturas de Pantalla

### Dashboard Principal
![Dashboard](screenshot-dashboard.jpg)

### Cuestionario de Estudio
![Quiz](screenshot-quiz.jpg)

### Pantalla de Graduación
![Graduation](screenshot-graduation.jpg)

## Tecnologías

- HTML5 + CSS3 + JavaScript Vanilla (sin dependencias externas)
- localStorage para persistencia
- Renderizado con DOM
- Diseño responsive y animaciones CSS

## Créditos

- Basado en el pensum de **Ingeniería en Energía - Universidad de Guayaquil (Ecuador)**.
- Creado como proyecto educativo offline para facilitar el aprendizaje y la revisión de la malla curricular.
- Preguntas generadas con fines educativos y de práctica.

## Licencia

Este proyecto está bajo la **Licencia MIT**. Ver el archivo [LICENSE](LICENSE) para más detalles.

---

**¡Empieza tu carrera hacia la graduación y contribuye a un futuro energético sostenible!**

Abre `index.html` y comienza a estudiar.