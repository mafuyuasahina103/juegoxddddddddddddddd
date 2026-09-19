# 🦖 Dino Run Adventure

¡Hola, programador o programadora! 👋
Con esta guía vas a preparar tu computador para crear y jugar tu propio juego del dinosaurio.

Solo sigue los pasos **en orden**. ¡Tú puedes! 💪

---

## ✅ Lo que necesitas

| Cosa | ¿Ya la tienes? |
|------|----------------|
| Python 🐍 | ¡Sí, ya lo tienes! |
| Un editor para escribir código (VS Code) | Paso 1 |
| Pygame (la herramienta para hacer juegos) | Paso 2 |
| Las imágenes del juego (sprites) | Paso 3 |

---

## 📝 Paso 1: Instalar VS Code

VS Code es el "cuaderno" donde vas a escribir tu código.

1. Abre el navegador y busca: **descargar VS Code**
2. Entra a la página que dice **code.visualstudio.com**
3. Haz clic en el botón grande de **Download**
4. Abre el archivo que se descargó y presiona **Siguiente** hasta que termine
5. ¡Listo! Ábrelo. Tiene un ícono azul 🔵

> 💡 Si en tu computador ya hay un editor de Python instalado (como IDLE o Thonny), puedes usar ese y saltar este paso.

---

## 🎮 Paso 2: Instalar Pygame

Pygame es la herramienta mágica que nos deja hacer videojuegos con Python.

### 2.1 Abre la "terminal"

La terminal es una ventana negra donde escribes órdenes para el computador.

- **En Windows:** presiona la tecla **Windows** 🪟, escribe **cmd** y presiona **Enter**
- **En Mac:** presiona **Command + Espacio**, escribe **Terminal** y presiona **Enter**

### 2.2 Escribe esta orden y presiona Enter

```
pip install pygame
```

Espera un poquito. Cuando termine, verás un mensaje que dice **Successfully installed pygame** 🎉

> 💡 Si sale un error que dice que `pip` no existe, prueba con esta:
> ```
> python -m pip install pygame
> ```
> (En Mac, si no funciona, cambia `python` por `python3`)

### 2.3 Comprueba que quedó bien

Escribe esto en la terminal:

```
python -c "import pygame"
```

- Si aparece un mensaje con el número de versión de pygame → ¡todo bien! ✅
- Si aparece un error rojo → mira la sección **"Si algo sale mal"** al final.

---

## 🖼️ Paso 3: Preparar la carpeta del proyecto

1. Crea una carpeta nueva en tu escritorio. Ponle de nombre: **DinoRun**
2. Dentro de esa carpeta, pon tu archivo del juego: **juego.py**
3. Dentro de **DinoRun**, crea otra carpeta que se llame exactamente: **sprites**
4. Dentro de **sprites**, pon estas 5 imágenes:

| Imagen | Para qué sirve |
|--------|----------------|
| `Dino Normal.png` | El dinosaurio corriendo 🦖 |
| `Dino Dunk.png` | El dinosaurio agachado |
| `Cactus.png` | El cactus 🌵 |
| `Roca.png` | La roca 🪨 |
| `Pajaro.png` | El pájaro 🐦 |

Tu carpeta tiene que verse así:

```
DinoRun/
├── juego.py
└── sprites/
    ├── Dino Normal.png
    ├── Dino Dunk.png
    ├── Cactus.png
    ├── Roca.png
    └── Pajaro.png
```

> ⚠️ **¡Muy importante!** Los nombres deben ser **idénticos**: con mayúsculas, con espacios y sin errores. Si uno está distinto, el juego no arranca.

---

## ▶️ Paso 4: ¡A jugar!

1. Abre **VS Code**
2. Ve a **File → Open Folder** (Archivo → Abrir carpeta) y elige la carpeta **DinoRun**
3. Haz clic en el archivo **juego.py**
4. Presiona el botón **▶️** (arriba a la derecha)

**O si prefieres la terminal:** entra a la carpeta y escribe:

```
python juego.py
```

---

## 🕹️ Cómo se juega

| Tecla | ¿Qué hace? |
|-------|-----------|
| **Espacio** o **⬆️** | El dinosaurio salta |
| **⬇️** | El dinosaurio se agacha |
| **R** | Volver a jugar (cuando pierdes) |

🎯 **Objetivo:** salta los cactus y las rocas, y agáchate para pasar por debajo de los pájaros. ¡Consigue el mayor puntaje!

---

## 🆘 Si algo sale mal

| Lo que ves | Lo que pasó | Cómo arreglarlo |
|------------|-------------|-----------------|
| `No module named pygame` | Pygame no se instaló | Repite el **Paso 2** |
| `FileNotFoundError` o `No such file` | El computador no encuentra una imagen | Revisa que la carpeta se llame **sprites** y que los nombres de las 5 imágenes estén idénticos |
| `pip no se reconoce` | pip no está listo | Usa `python -m pip install pygame` |
| Pygame no se deja instalar | Puede ser un tema de versión | Prueba con `pip install pygame-ce` |
| El juego no abre | Estás en la carpeta equivocada | Abre la carpeta **DinoRun** completa en VS Code |

**Si nada de esto funciona, ¡levanta la mano y pide ayuda a tu profe!** 🙋

---

¡Diviértete programando! 🚀
