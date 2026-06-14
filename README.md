# 🚗 Barrera Inteligente para Estacionamiento

## 📋 Descripción

Este proyecto consiste en una barrera automática para el control de acceso a un estacionamiento utilizando Arduino.
El sistema verifica si la patente de un vehículo se encuentra registrada en una base de datos. Si la patente es válida, la barrera se abre automáticamente mediante un servomotor, permitiendo el ingreso del vehículo. En caso contrario, el acceso es denegado.
Este proyecto fue desarrollado con fines educativos para aplicar conceptos de programación, electrónica y automatización.

## 🎯 Objetivos

- Automatizar el acceso a un estacionamiento.
- Iniciar mediante aproximacion.
- Registrar patentes.
- Controlar una barrera mediante un servomotor.
- Validar patentes registradas en el sistema.
- Mejorar la seguridad del acceso vehicular.

---
## ⚙️ Funcionamiento

1. El sistema recibe una patente.
2. Se verifica si la patente se encuentra registrada.
3. Si se requiere registrar una patente, se podra hacer desde el menu.
4. Si la patente es válida:
   - Se habilita el acceso.
   - El servomotor abre la barrera.
   - Después de unos segundos, la barrera vuelve a cerrarse.
5. Si la patente no está registrada:
   - Se deniega el acceso.
   - La barrera permanece cerrada.

---
## 🔧 Componentes Utilizados

- Arduino Uno
- Servomotor(SG90)
- Resistencias de 220 Ohms 
- Teclado 4x4(Pin Pad)
- Protoboard
- Cables jumper(Macho-Macho y Macho-Hembra)
- Fuente de alimentación USB
- led rojo y led verde
- sensor ultrasonico de distancia(HC-SR04)
- pantalla oled I2C 128x32(SSD1306)
- 
---
## 💻 Tecnologías Utilizadas

- Arduino UNO
- Lenguaje C

---
## 📔 Librerias Utilizadas

-Wire.h
-Adafruit_GFX.h
-Adafruit_SSD1306.h
-Keypad.h
-Servo.h
-EEPROM.h

---
## 📚 Aprendizajes

Durante el desarrollo de este proyecto se aplicaron conocimientos de:

- Programación estructurada.
- Uso de sensores.
- Entradas y salidas digitales.
- Automatización de procesos.
- Diseño de sistemas embebidos.

---
## 👨‍💻 Autor
-Juan Sarago
-Angel Quizamas
-Agustin Mayol
