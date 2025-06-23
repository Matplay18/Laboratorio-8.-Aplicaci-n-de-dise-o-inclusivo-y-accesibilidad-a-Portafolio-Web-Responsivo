# Laboratorio-8.-Aplicaci-n-de-dise-o-inclusivo-y-accesibilidad-a-Portafolio-Web-Responsivo
Mateo Freire 22/06/2025 Septimo Semestre
# Mejoras de Accesibilidad Implementadas
1. Etiquetas semánticas de HTML5
Uso de: <header>, <nav>, <main>, <section>, <footer>, <article>, <form>. Permite que lectores de pantalla y motores de búsqueda comprendan mejor la estructura del contenido.
2. Jerarquía de títulos clara
Se usa un orden lógico y estructurado: <h1>, <h2>, <h3>. Mejora la navegación para usuarios con tecnologías asistidas y para la indexación en buscadores.
3. Contraste de color adecuado
Texto blanco (#FFFFFF) sobre fondo oscuro (#121212) para cumplir con WCAG nivel AA. Colores de énfasis con alto contraste para elementos de foco o destacados.
4. Texto alternativo (alt) en imágenes
Se incluye en todas las imágenes para describir claramente el contenido visual a usuarios que no pueden ver la imagen.
5. Navegación con teclado funcional
Soporte completo para navegación mediante la tecla Tab. Elementos interactivos como enlaces y botones reciben foco visible con borde destacado.
6. Formularios con etiquetas <label> asociadas
Cada campo tiene un label correctamente asociado al input por el atributo for e id.
7. Descripciones claras en botones y enlaces
Evita textos genéricos como 'haz clic aquí'. Se usan frases descriptivas como 'Ver detalles del proyecto ONG'.
8. Legibilidad y comprensión
Tipografía limpia, buena separación entre líneas, y tamaños de fuente ajustables con clamp().
# Mejoras de Diseño Inclusivo
1. Tamaños de fuente ajustables
Uso de clamp() para adaptarse automáticamente a pantallas grandes y pequeñas.
2. Foco visible para navegación por teclado
Foco con borde color naranja brillante (alta visibilidad), accesible para usuarios con visión limitada.
3. Contraste accesible
Fondo oscuro con texto blanco, cumpliendo WCAG nivel AA.
4. Compatible con lectores de pantalla
Estructura semántica + aria-label en navegación mejoran experiencia con lectores como NVDA o VoiceOver.
