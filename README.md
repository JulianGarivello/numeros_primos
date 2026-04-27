Prime Checker - Edición Marble & Erosion

Prime Checker es un aplicativo web conceptual que fusiona la teoría de números con el arte generativo digital. Diseñado para ofrecer una experiencia visual inmersiva, el sistema transforma su entorno gráfico en tiempo real basándose en la naturaleza matemática de los datos ingresados.

🌟 Visión del Proyecto

El proyecto busca visualizar la dicotomía entre la fluidez de los números primos (bloques fundamentales e indivisibles de la aritmética) y la rigidez de los números compuestos. A través de filtros de desplazamiento SVG y manipulaciones de ruido fractal, la interfaz reacciona físicamente a cada consulta del usuario.

🚀 Funcionalidades Principales

Algoritmo de Primalidad Optimizado: Implementa una verificación basada en la raíz cuadrada ($O(\sqrt{n})$), garantizando respuestas instantáneas incluso para números de gran magnitud.

Entorno Líquido (Liquid Marble): Un fondo dinámico que utiliza gradientes cónicos y filtros de turbulencia para simular la mezcla orgánica de pinturas. Se activa en estado de reposo y al hallar un número primo.

Efecto de Solidificación (Erosión): Al detectar un número compuesto, el entorno se "congela" y se "cuartea", transformándose en una textura de roca erosionada y árida.

Arquitectura Single-File: Todo el núcleo (HTML, CSS y JS) reside en un único documento, facilitando su portabilidad y ejecución inmediata.

Interfaz "Glassmorphism": Panel central con desenfoque de fondo (backdrop-blur) que permite la integración visual con el arte generativo del fondo.

🛠️ Especificaciones Técnicas

Lenguaje: JavaScript (Vanilla ES6+).

Estilos: Tailwind CSS para la estructura UI y animaciones personalizadas en CSS3 para el fondo.

Renderizado Visual: - feTurbulence: Genera el ruido base para la textura del mármol y las grietas de la roca.

feDisplacementMap: Deforma los gradientes de color para crear el movimiento fluido viscoso.

Matemáticas: Validación estricta de enteros, exclusión de números menores a 2 y lógica de divisibilidad eficiente.

🎨 Simbolismo Estético

Primos (Estado Vital): Representados por el movimiento, la adaptabilidad y el color (Verde/Esmeralda). Simbolizan la esencia pura de la materia matemática.

Compuestos (Estado Inerte): Representados por la fractura, el gris pétreo y la erosión. Simbolizan la complejidad que puede ser dividida y desmoronada.

👤 Créditos y Autoría

Este proyecto es una colaboración entre el ingenio humano y la computación avanzada:

Desarrollado por: ### César Julián Garivello

Asistencia Técnica: Inteligencia Artificial (IA)

Abril 2024 — Un experimento de Matemática Visual y Arte Generativo.
