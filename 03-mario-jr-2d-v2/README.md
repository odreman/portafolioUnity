# Mario Jr 2D V2 🍄

Versión mejorada del juego de plataformas **Mario Jr 2D**, una reinterpretación del clásico Super Mario Bros con elementos propios y mecánicas adicionales. Esta versión evolucionada incluye mejoras significativas en gameplay, enemigos más complejos, sistema de power-ups y múltiples sistemas avanzados.

**[🎮 Jugar en itch.io](https://odreman.itch.io/mario-jr)**

---

## 📖 Sobre el Juego

Esta versión representa una evolución significativa del juego original de plataformas 2D, incorporando sistemas más complejos y mecánicas avanzadas que mejoran la experiencia de juego. El proyecto demuestra el progreso en el desarrollo de videojuegos, implementando inteligencia artificial, sistemas de partículas, gestión de estados y múltiples tipos de enemigos.

## 🎮 Cómo Jugar

### Controles

- **Movimiento**: Flechas del teclado o WASD
- **Salto**: Tecla Espacio
- **Disparo**: Tecla X (solo cuando el personaje está en estado gigante)

### Mecánicas Principales

- 🍄 **Sistema de Power-ups**: Consume hongos para obtener el estado gigante y habilitar el disparo
- ⏱️ **Control de tiempo**: Tienes 3 minutos para completar el nivel
- 🏁 **Checkpoints**: Las banderas marcan puntos de respawn si pierdes una vida
- 💀 **Sistema de vidas**: Comienzas con 3 vidas
- 🎯 **Objetivo**: Llegar al banderín de fin de nivel

### Enemigos

- **BUG**: Enemigo básico que se mueve por el escenario, se derrota saltando sobre él
- **Turtle**: Enemigo con inteligencia artificial que persigue al jugador en rango de visión y dispara proyectiles
- **Koopa**: Enemigos rápidos que pueden derrotarse saltando sobre ellos o disparándoles

### Power-ups

- **Hongo**: Otorga el estado gigante y habilita el sistema de disparo

## 🛠️ Implementación Técnica

### Características Desarrolladas

Este proyecto implementa múltiples sistemas avanzados:

- **Sistema de animaciones complejo**: Múltiples animaciones del personaje (idle, walk, jump, run, shoot, die, etc.)
- **Inteligencia artificial**: Enemigos con IA que persiguen al jugador cuando están en rango de visión
- **Sistema de disparo**: Implementado cuando el personaje está en estado gigante
- **Sistema de partículas**: Efectos visuales en las banderas y otros elementos del juego
- **Sistema de checkpoints**: Banderas que marcan puntos de respawn con funcionalidad completa
- **Gestión de estados**: Control avanzado del estado del jugador (normal, gigante, etc.)
- **Sistema de física 2D**: Implementación avanzada de física para movimiento y colisiones
- **Sistema de audio**: Gestión completa de sonidos y música
- **UI dinámica**: Múltiples paneles de interfaz de usuario
- **Control de tiempo**: Sistema de reloj con límite de tiempo por nivel

### Arquitectura del Código

**Scripts principales implementados:**

- `PlayerMovement.cs` - Control completo del personaje principal
- `GameManager.cs` - Gestión general del juego y estados
- `Turtle.cs`, `TurtleWeapon.cs` - Enemigo con IA y sistema de armas
- `KoopaTropa.cs`, `IEnemy.cs` - Sistema de enemigos con interfaz
- `Bullet.cs` - Sistema de disparos y proyectiles
- `ClockTime.cs` - Control y gestión del tiempo
- `CheckPoint.cs` - Sistema de checkpoints con respawn
- `Block.cs` - Comportamiento de bloques interactivos
- `AudioManager.cs` - Gestión centralizada de sonidos

### Tecnologías

- **Motor**: Unity 3D v2020.3.0f1
- **Lenguaje**: C#
- **Sistemas**: Física 2D, Animators, Partículas, IA básica

## 📦 Contenido del Proyecto

- **Versión Web**: Disponible en [itch.io](https://odreman.itch.io/mario-jr)
- **Ejecutable local**: `Ejecutable/MarioJr2.app` - Versión compilada para macOS
- **Video explicativo**: [Ver en YouTube](https://youtu.be/W0n-ux1MltI)

## 🎨 Mejoras Implementadas

Esta versión V2 incluye mejoras significativas respecto a la versión original:

### R1: Sistema de Animaciones
- Múltiples animaciones del personaje (idle, walk, jump, run, shoot, die, etc.)
- Transiciones fluidas entre estados

### R2: Sistema de Partículas
- Efectos visuales en las banderas
- Partículas para mejorar la experiencia visual

### R3: Inteligencia Artificial
- Enemigos con IA que persiguen al jugador
- Sistema de detección de rango de visión
- Comportamientos diferenciados por tipo de enemigo

### R4: Sistema de Disparo
- Implementación completa de disparos cuando el personaje está en estado gigante
- Sistema de proyectiles con física

### R5: Sistema de Checkpoints
- Banderas que marcan puntos de respawn
- Sistema de guardado de posición

### R6: Organización del Código
- Uso extensivo de Tags y Layers para mejor organización
- Arquitectura modular y escalable

## 🎯 Objetivos del Proyecto

Este proyecto demuestra la evolución en el desarrollo de videojuegos, implementando:

- Sistemas de juego más complejos y avanzados
- Inteligencia artificial básica para enemigos
- Múltiples sistemas integrados (partículas, audio, UI, física)
- Gestión avanzada de estados del juego
- Mejoras significativas en la experiencia de usuario

---

**Desarrollado por Odreman Ferrer**

*Este proyecto forma parte de mi portafolio de desarrollo de videojuegos. El código fuente y assets propietarios no están incluidos por razones de derechos de autor.*
