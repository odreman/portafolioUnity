# Squirrel Run 🐿️

Juego completo de aventura y plataformas donde una ardilla debe salvar su territorio derrotando enemigos y enfrentándose al jefe final MIU. Este proyecto representa el trabajo más completo del portafolio, implementando múltiples niveles, sistema de combate, variedad de enemigos y jefes, y sistemas avanzados de gestión del juego.

**[🎮 Jugar en itch.io](https://odreman.itch.io/squirrel-run)**

---

## 📖 Sobre el Juego

**Squirrel Run** es un juego de aventura y plataformas donde el personaje principal, una ardilla, debe sortear obstáculos, derrotar enemigos y enfrentarse al jefe final "MIU" para salvar su territorio. El juego cuenta con múltiples niveles, sistema de vidas, recolección de monedas y tiempo limitado por nivel.

### Historia

La ardilla es el personaje principal de esta aventura. Se encuentra en una selva que ha sido dominada por el terrible gato MIU, quien ha logrado armar un ejército de monstruos para dominar el territorio y expulsar a todo aquel que se interponga en su camino.

## 🎮 Cómo Jugar

### Controles

- **Movimiento**: Flechas del teclado o WASD
- **Salto**: Tecla Espacio
- **Disparo**: Tecla X
- **Pausa**: Click en el tiempo (panel superior derecho)

### Mecánicas Principales

- 💀 **Sistema de vidas**: Comienzas con 3 vidas por nivel
- 🏁 **Checkpoints**: Banderas que marcan puntos de respawn al perder una vida
- ⏱️ **Control de tiempo**: 3 minutos por nivel para completarlo
- 🪙 **Sistema de monedas**: Recolección de monedas de bronce, plata y oro
- 🎯 **Objetivo**: Llegar al banderín de fin de nivel
- 🎮 **Sistema de pausa**: Menú completo de pausa con opciones

### Enemigos

- **Insectos y monstruos voladores**: Se mueven por el escenario, generan daño al contacto, se derrotan disparando
- **Monstruos**: Se mueven por el escenario, atacan al acercarse, se derrotan disparando
- **Turtle**: Enemigo despiadado con arma, dispara si te aproximas, se derrota disparando
- **Gato MIU y sus Jefes**: Muy rápidos, grandes, con mucha vida y armas, se derrotan disparando

### Obstáculos

- Púas
- Fuego
- Caídas al vacío
- Lava
- Y más...

## 🛠️ Implementación Técnica

### Características Desarrolladas

Este proyecto implementa un sistema completo de juego con múltiples características avanzadas:

- **Múltiples escenas**: Sistema completo de navegación entre escenas (menú, niveles, fin de juego)
- **Sistema de combate**: Sistema de disparos completo para jugador, enemigos y jefes
- **Inteligencia artificial**: Enemigos con comportamientos distintos y patrones de ataque
- **Sistema de jefes**: Implementación de bosses con mecánicas especiales
- **Sistema de partículas**: Efectos visuales para mejorar la experiencia
- **Sistema de audio completo**: Sonidos para todos los eventos relevantes del juego
- **UI dinámica**: Múltiples paneles para pausa, game over, victoria, etc.
- **Sistema de checkpoints**: Puntos de respawn con banderas funcionales
- **Control de tiempo**: Sistema de reloj con límite de tiempo por nivel
- **Sistema de monedas**: Recolección y gestión de diferentes tipos de monedas
- **Gestión de estados**: Control avanzado del estado del juego

### Arquitectura del Código

**Escenas implementadas:**

- `LogoSceneMain` y `LogoSceneMain2`: Logos del desarrollador y del juego
- `MainMenu`: Menú principal con opciones de juego, salir, créditos y sonido
- `LevelOne`, `LevelTwo`, `LevelFinal`: Niveles del juego con mecánicas distintas
- `EndGame`: Escena de fin de juego

**Scripts principales:**

- `Player.cs` - Control completo del personaje principal
- `GameManager.cs` - Gestión general del juego y estados
- `Enemy.cs`, `EnemyAttack.cs` - Sistema de enemigos con IA
- `Bullet.cs`, `BulletPlayer.cs`, `BulletBoss.cs` - Sistema de disparos diferenciado
- `ClockTime.cs` - Control y gestión del tiempo
- `Coins.cs`, `Coin1Up.cs` - Sistema de monedas y power-ups
- `AudioManager.cs` - Gestión centralizada de sonidos
- `Flag.cs` - Sistema de checkpoints y puntos de respawn
- `Background.cs` - Control del fondo y parallax
- `BrokenPart.cs` - Efectos de destrucción y partículas
- `FlashScene.cs` - Transiciones de escena

**Tags y Layers utilizados:**

- Player, Enemy, Feet, DeadZone, Bullet, MainCamera, BulletEnemy

### Tecnologías

- **Motor**: Unity 3D v2020.0.0f1
- **Lenguaje**: C#
- **Sistemas**: Física 2D, Animators, Partículas, IA, Audio, UI/UX

## 📦 Contenido del Proyecto

- **Versión Web**: Disponible en [itch.io](https://odreman.itch.io/squirrel-run)
- **Ejecutable local**: `Executable/SquirrelRun.app` - Versión compilada para macOS

## 🎯 Objetivos del Proyecto

Este proyecto demuestra la capacidad de desarrollar un juego completo con:

- Múltiples niveles con mecánicas distintas
- Sistema de combate completo con disparos
- Variedad de enemigos con diferentes comportamientos
- Sistema de jefes (bosses) con mecánicas especiales
- Gestión completa de vidas y puntos de respawn
- Sistema de recolección (monedas)
- Control de tiempo por nivel
- Sistema de pausa y menús completos
- Múltiples escenas con transiciones fluidas

## 🎨 Detalles de Diseño

El juego fue diseñado para ofrecer una experiencia completa de aventura y plataformas:

- Múltiples niveles con desafíos progresivos
- Variedad de enemigos y obstáculos
- Sistema de combate dinámico
- Jefes finales con mecánicas únicas
- Sistema de recolección que incentiva la exploración
- UI intuitiva y completa

---

**Desarrollado por Odreman Ferrer**

*Los elementos gráficos fueron adquiridos en Envato Market.*
