# Línea de Fuego
Línea de Fuego es un juego de carreras (racing game) orientado a niños de 8 a 12 años, con una estética vibrante y mecánicas pensadas para ser accesibles pero progresivamente desafiantes. Cada mundo tiene un jefe de carrera.
#
Estructura general:
#
El juego se organiza en 3 mundos, cada uno con 2 mapas y 9 niveles cada mapa:
#
Mundo 1 – Isla Tropical: Playa Alegre (dificultad 2) y Selva Enredada (dificultad 4).
#
Mundo 2 – Metrópolis Ciberpunk: Neón City (dificultad 6) y Autopista Elevada (dificultad 7).
#
Mundo 3 – Cosmos: Gravedad Cero (dificultad 8) y Agujero Negro (dificultad 10).

En el proceso, se ganarán monedas, las cuales se podrán utilizar para compras de herramientas especiales, en poderes únicos o en adquisiciones de nuevos vehículos.

# Fase 1. Analisis
Requerimientos Funcionales
Progreso de niveles: lista ordenada de 6 niveles; desbloqueo por condicionales según puntaje mínimo y estado del nivel anterior.
Activación de atajos: detección de zonas ocultas (cascada, rampa, portal) que otorgan ventajas inmediatas (reducción de tiempo o teletransporte).
Mecánicas de jefes: cada mundo incluye un jefe IA con ataque único.
Uso de power-ups: recolección de cajas sorpresa y activación independiente de herramientas inmutables mediante botón.
Sistema de recompensas: al finalizar la carrera, un ciclo calcula y otorga automáticamente monedas y objetos estéticos según el nivel superado.

Requerimientos No Funcionales
Robustez y tolerancia a fallos: manejo de excepciones (comandos inválidos, archivos dañados) sin congelar ni cerrar el juego.
Usabilidad para el público objetivo: colores vibrantes y sonidos cómicos/caricaturescos para mantener el interés de niños de 8-12 años y evitar frustración.
Arquitectura de memoria: segmentación estricta de variables globales (estados macro, ej. puntaje total) vs. locales (datos efímeros, ej. multiplicador de velocidad en una curva).
Integridad de datos: datos fijos de herramientas/inventario almacenados en tuplas inmutables para evitar alteraciones en tiempo de ejecución.
Retroalimentación auditiva en tiempo real: ajuste dinámico del ritmo de la música en la última vuelta y efectos de sonido inmediatos ante acciones del jugador.

# Fase 2. Diseño
Diagrama de Flujo; "Línea de Fuego"

# Fase 3. Desarrollo / Código
Programación Orientada a Objetos (Poo) | Videojuego

# Fase 4. Presentación


Programador Junior.
