# PF_Laboratorio – Proyecto Final de Computación Gráfica

Este repositorio contiene el código fuente del **Proyecto Final de Computación Gráfica** desarrollado por el equipo 8. El proyecto consiste en una simulación 3D interactiva de un laboratorio, que incluye animaciones complejas, recorrido de cámara y control de personajes, todo implementado con **OpenGL** y **C++**.

## 🚀 Características Principales

- ✅ Simulación completa de un laboratorio viejo y uno nuevo.
- 🎮 Movimiento libre de cámara con teclado y mouse.
- 🧍‍♂️ Personaje controlable con animaciones de avance, giro y retroceso.
- 🪑 Animaciones detalladas de sillas, gabinetes y transiciones visuales.
- 🌞 Control de iluminación dinámica.
- 🎥 Recorridos automáticos de cámara activables por teclado.

## 🖥️ Requisitos

- Visual Studio 2019 o superior
- Windows con soporte para OpenGL
- Librerías externas:
  - GLEW
  - GLFW
  - GLM
  - SOIL2

## 📦 Estructura del Proyecto

PF_Laboratorio/
│
├── External Libraries/ # Dependencias externas (GLEW, GLFW, etc.)
├── PF_Laboratorio/ # Código fuente principal del proyecto
│ ├── shaders/ # Shaders GLSL usados en la escena
│ ├── models/ # Modelos 3D usados (formatos .obj o .fbx)
│ ├── textures/ # Imágenes para texturizado
│ └── main.cpp # Archivo principal de ejecución
├── PF_Laboratorio.sln # Solución de Visual Studio
├── .gitignore # Archivos ignorados por Git
└── README.md # Este archivo


## 🎮 Controles del Programa

### Movimiento de Cámara:
- `W`, `A`, `S`, `D` o flechas: Mover la cámara
- Mouse: Cambiar orientación de la vista

### Teclas Especiales:
- `ESC`: Salir del programa
- `ESPACIO`: Encender/apagar luces del laboratorio
- `R`: Activar recorrido automático 1
- `T`: Activar recorrido automático 2 (desactiva el anterior)
- `M`: Iniciar/Cancelar caída del laboratorio nuevo
- `L`: Activar animación remolino (sillas viejas)
- `J`: Activar caída de sillas nuevas
- `G`: Activar caída de gabinetes del laboratorio nuevo
- `B`: Activar caída de gabinetes del laboratorio viejo
- `1` a `5`: Control de movimiento y giros del personaje

### Solución recomendada:

1. Desactiva todas las excepciones desde el menú **Depurar > Configuración de excepciones**.
2. Haz clic derecho sobre el proyecto y selecciona **“Limpiar”**.
3. Cierra cualquier instancia del `.exe` desde el Administrador de tareas.
4. Vuelve a compilar y ejecuta.
5. Si sigue fallando:
   - Comenta la carga de todos los modelos.
   - Corre el programa sin modelos.
   - Agrega primero el **laboratorio nuevo** y luego los demás modelos.

## 👥 Equipo de Desarrollo

- 317290967 – José 
- 319296738 – Diego
- 319281998 – Eduardo  

## 📄 Licencia

Este proyecto es de uso académico. Todos los derechos reservados por el equipo de desarrollo.

---

🎓 *Desarrollado como parte del curso de Computación Gráfica – UNAM 2025*
