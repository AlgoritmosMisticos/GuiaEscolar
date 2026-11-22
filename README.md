# Buscar Maestro — Plataforma de Reseñas y Consulta Docente (UdeG)

Plataforma web interactiva diseñada para que estudiantes de la **Universidad de Guadalajara** (con enfoque inicial en el Centro Universitario de Ciencias Exactas e Ingenierías — **CUCEI**) consulten, califiquen y publiquen opiniones y preguntas sobre el personal docente, organizadas por centro universitario, carrera, semestre y materia.

**Demo en vivo:** [          ](         )

---

## Características Principales

* **Navegación Académica Estructurada:** Exploración por Centro Universitario (CUCEI, CUAAD, CUCBA, CUCEA, CUCS, CUCSH, CUGDL), Carrera (Ingeniería en Computación e Ingeniería Informática), Semestre (1 a 9) y Materia.
* **Sistema de Reseñas y Preguntas:** Publicación de calificaciones con estrellas (1 a 5), comentarios detallados y preguntas sobre docentes, con opción de publicación anónima.
* **Buscador y Filtros Dinámicos:** Búsqueda en tiempo real por nombre de profesor, materia o palabra clave, además de filtros por unidad de aprendizaje y calificación mínima promedio.
* **Moderación Automática de Contenido:** Filtro léxico preventivo que bloquea groserías, insultos y evasiones tipográficas, permitiendo la crítica académica constructiva sin falsos positivos.
* **Sincronización en la Nube:** Integración con **Firebase Firestore** para persistir y actualizar en tiempo real usuarios, publicaciones y el catálogo de maestros.
* **Diseño Responsivo y Tema Adaptativo:** Interfaz compatible con dispositivos móviles y escritorio, con soporte automático para modo claro y oscuro.

---

## Tecnologías Utilizadas

* **Frontend:** HTML5, CSS3 (Grid, Flexbox, variables CSS y diseño responsivo) y JavaScript (ES6+ Modules).
* **Base de Datos y Backend as a Service:** Firebase Firestore.
* **Control de Versiones y Despliegue:** Git, GitHub Projects y GitHub Pages.

---

## Optimización Algorítmica

Como parte del proyecto de **Análisis de Algoritmos (2026B)**, se evaluaron y optimizaron las operaciones críticas de consulta y agregación de datos:

* **Filtrado y Cálculo de Promedios:** Optimización de complejidad cuadrática $O(N^2)$ a lineal $O(N)$ mediante técnicas de programación dinámica / memoización para evitar recomputaciones redundantes.
* **Búsqueda de Docentes:** Reducción de complejidad lineal $O(M)$ a logarítmica $O(\log M)$ aplicando búsqueda binaria sobre catálogos ordenados.

---

