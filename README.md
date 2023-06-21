# Silent Aim Bot

Silent Aim Bot is a powerful Python script designed to enhance your aiming skills and gain a competitive advantage in Valorant. This intelligent bot automates the aiming and shooting process by detecting enemies and precisely firing at them within the blink of an eye. Take your gameplay to the next level with Silent Aim Bot!

## Features

✨ **Automatic Aiming and Shooting**: The bot automatically aims at enemies within your field of view (FOV) and triggers precise shots, eliminating the need for manual aiming.

🌈 **Color-Based Enemy Detection**: Utilizing advanced color detection algorithms, Silent Aim Bot specifically targets enemies with a vibrant purple color, allowing you to swiftly eliminate your opponents.

⚙️ **Customizable Fire Key**: Tailor the bot to your preferences by easily configuring the fire key to match your gameplay style.

⏱️ **Instant Reaction Time**: With lightning-fast reaction times, the bot detects enemies in real-time and instantly fires, ensuring you never miss a critical shot.

🔄 **Switchable Modes**: Choose from different modes such as "Operator/Marshal," "Guardian," and "Vandal/Phantom/Shotguns" to adapt your shooting strategy based on the weapon you're using.

🐇 **Bunny Hop Capability**: Activate the bunny hop feature to effortlessly perform bunny hops, increasing your mobility and evasiveness in the game.

## Requirements

To run Silent Aim Bot, you'll need:

- Python 3.x
- `keyboard` library
- `pyautogui` library
- `time` library
- `ctypes` library
- `PIL` (Python Imaging Library) library
- `winsound` library
- `os` library
- `mss` (ScreenShot) library
- `colorama` library

## Usage

### Step-by-Step Guide (English)

1. **Clone or Download**: Clone or download the Silent Aim Bot repository from GitHub.

2. **Install Dependencies**: Install the required libraries by running `pip install -r requirements.txt` in your command prompt.

3. **Customize Settings**: Open the script and modify the fire key (default: "Z") and the enemy color values to match the purple color of enemies in Valorant.

4. **Run the Script**: Launch the script by running `python main.py` in your command prompt.

5. **Activate the Aim Bot**: Use the specified control key combination (default: "Ctrl + Alt") to toggle the aim bot on and off.

6. **Switch Weapons**: Press the designated key combination (default: "Ctrl + Tab") to switch between different weapon modes based on your preference.

7. **Adjust Field of View (FOV)**: Increase or decrease the FOV circle size by using the specified key combinations (default: "Ctrl + Up" to increase, "Ctrl + Down" to decrease).

8. **Bunny Hop**: Enable or disable the bunny hop feature by pressing the assigned key combination (default: "Ctrl + Space").

9. **Enjoy Enhanced Aiming**: Immerse yourself in the game and experience enhanced aiming capabilities, precise shots, and swift eliminations with Silent Aim Bot.

### Instrucciones Paso a Paso (Español)

1. **Clonar o Descargar**: Clona o descarga el repositorio de Silent Aim Bot desde GitHub.

2. **Instalar Dependencias**: Instala las bibliotecas requeridas ejecutando `pip install -r requirements.txt` en la línea de comandos.

3. **Personalizar Configuración**: Abre el script y modifica la tecla de disparo (por defecto: "Z") y los valores de color de los enemigos para que coinc

idan con el color púrpura de los enemigos en Valorant.

4. **Ejecutar el Script**: Inicia el script ejecutando `python main.py` en la línea de comandos.

5. **Activar el Aim Bot**: Utiliza la combinación de teclas especificada (por defecto: "Ctrl + Alt") para activar o desactivar el aim bot.

6. **Cambiar de Arma**: Presiona la combinación de teclas designada (por defecto: "Ctrl + Tab") para cambiar entre diferentes modos de armas según tu preferencia.

7. **Ajustar Campo de Visión (FOV)**: Aumenta o disminuye el tamaño del círculo del campo de visión (FOV) utilizando las combinaciones de teclas especificadas (por defecto: "Ctrl + Arriba" para aumentar, "Ctrl + Abajo" para disminuir).

8. **Bunny Hop**: Habilita o deshabilita la función de bunny hop presionando la combinación de teclas asignada (por defecto: "Ctrl + Espacio").

9. **Disfruta de un Mejor Aiming**: Sumérgete en el juego y experimenta capacidades de apuntado mejoradas, disparos precisos y eliminaciones rápidas con Silent Aim Bot.

## Contributing

Contributions to Silent Aim Bot are welcome! If you have any ideas, bug reports, or feature suggestions, please open an issue on the GitHub repository.

Follow us on Instagram [@CodeTotrader](https://www.instagram.com/CodeTotrader) for more exciting projects and coding inspiration!

## Mathematics Behind the Bot

Silent Aim Bot utilizes the following mathematical formula to detect enemies:

- Distance Formula: The bot captures a portion of the screen and analyzes the RGB values of each pixel within the specified field of view (FOV) circle. It compares these RGB values with the defined enemy color (purple) using a tolerance range. If the RGB values fall within the tolerance range, indicating a match with the enemy color, the bot triggers the fire key ("Z") to shoot at the enemy.

This mathematical algorithm allows for precise enemy detection and rapid response, giving you an edge in your Valorant gameplay.

```python
distance = sqrt((x2 - x1)**2 + (y2 - y1)**2)
```

Feel free to customize the instructions and languages further as per your requirements.
