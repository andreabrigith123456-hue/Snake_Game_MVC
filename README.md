# Snake_Game_MVC
ANDREA PUMISACHO 
INGENIERIA EN CIBERSEGURIDAD
Desarrollo de mi juego de la serpiente
Este desarrollo aplica el patrón MVC para separar la lógica de colisiones de la interfaz gráfica, optimizando el rendimiento en entornos educativos.
Este es un desarrollo profesional del clásico juego "Snake", implementado en Python utilizando la librería Pygame. El proyecto destaca por el uso del patrón de diseño Modelo-Vista-Controlador (MVC), garantizando una separación clara entre la lógica de negocio, la interfaz de usuario y el control de eventos.

Descripción del Proyecto
El objetivo es ofrecer una experiencia de juego fluida mientras se gestionan estructuras de datos dinámicas para el cuerpo de la serpiente. El sistema procesa en tiempo real:

Movimiento mediante vectores de dirección.

Detección de colisiones (bordes y cuerpo).

Generación aleatoria de objetivos (comida).

Gestión de puntuación progresiva.

Arquitectura del Sistema (Patrón MVC)
Para este desarrollo se ha cuestionado la programación monolítica tradicional, optando por una estructura modular que facilita el mantenimiento y la escalabilidad:

Modelo (Model): Gestiona los datos internos. Contiene la lista de segmentos de la serpiente, las coordenadas de la comida y el estado del puntaje. No tiene conocimiento de la interfaz gráfica.

Vista (View): Se encarga puramente del renderizado. Utiliza Pygame para dibujar los elementos en la ventana basándose exclusivamente en los datos proporcionados por el Modelo.

Controlador (Controller): El puente de comunicación. Captura los eventos del teclado (KEYDOWN) y traduce las entradas del usuario en cambios de estado para el Modelo.
