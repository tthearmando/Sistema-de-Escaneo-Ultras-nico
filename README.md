# Sistema de Escaneo Ultrasónico
 Este proyecto es un sistema de radar basado en Arduino, que utiliza un sensor ultrasónico HC-SR04 y un servomotor para escanear el entorno y visualizar los datos en Processing. El servomotor gira el sensor en un rango determinado, mientras que el sensor mide la distancia a los objetos cercanos. Luego, los datos se envían a Processing para generar una representación visual del radar en tiempo real.

## ⚙️ **Funcionamiento**
1. El **servomotor gira** de un lado a otro en un rango predefinido (0° a 180°).
2. En cada posición, el **sensor ultrasónico HC-SR04** mide la distancia a los objetos cercanos.
3. Los datos de distancia se envían a la computadora a través del **puerto serie**.
4. En **Processing**, los datos se interpretan y se genera un **gráfico en forma de radar** que muestra los objetos detectados.

## 🛠 **Materiales Necesarios**
- **Arduino UNO**
- **Sensor ultrasónico HC-SR04**
- **Servomotor SG90**
- **Protoboard y cables jumper**
- **Computadora con Processing instalado**
- **Cable USB para conectar Arduino a la PC**

## 🔌 **Esquemático**
El siguiente diagrama muestra la conexión entre los componentes:

# **Radar Ultrasónico con Arduino y Processing**

## 📌 Descripción
Este proyecto consiste en un **radar ultrasónico** construido con **Arduino** y visualizado en **Processing**. Utiliza un **sensor ultrasónico HC-SR04** montado en un **servomotor** para escanear el entorno y detectar objetos cercanos. La información se transmite a Processing, donde se genera una interfaz visual que representa el radar en tiempo real.

---

## ⚙️ **Funcionamiento**
1. El **servomotor gira** de un lado a otro en un rango predefinido (0° a 180°).
2. En cada posición, el **sensor ultrasónico HC-SR04** mide la distancia a los objetos cercanos.
3. Los datos de distancia se envían a la computadora a través del **puerto serie**.
4. En **Processing**, los datos se interpretan y se genera un **gráfico en forma de radar** que muestra los objetos detectados.

---

## 🛠 **Materiales Necesarios**
- **Arduino UNO**
- **Sensor ultrasónico HC-SR04**
- **Servomotor SG90**
- **Protoboard y cables jumper**
- **Computadora con Processing instalado**
- **Cable USB para conectar Arduino a la PC**

---

## 🔌 **Esquemático**
El siguiente diagrama muestra la conexión entre los componentes:

![Esquemático](C:\Users\DTCsoporte\Documents\GitHub\Sistema-de-Escaneo-Ultras-nico\Esquematico.png)


- **VCC del HC-SR04** → **5V de Arduino**
- **GND del HC-SR04** → **GND de Arduino**
- **Trig del HC-SR04** → **Pin 10 de Arduino**
- **Echo del HC-SR04** → **Pin 11 de Arduino**
- **Señal del servomotor** → **Pin 12 de Arduino**
- **VCC del servomotor** → **5V de Arduino**
- **GND del servomotor** → **GND de Arduino**

## 🖥 **Requisitos del Software**
Para ejecutar este proyecto, necesitarás instalar los siguientes programas:

- **Arduino IDE** (para cargar el código en Arduino) - [Descargar](https://www.arduino.cc/en/software)
- **Processing** (para visualizar el radar) - [Descargar](https://processing.org/download/)

## 🚀 **Cómo Usarlo**
1. **Descarga o clona este repositorio** en tu computadora.
2. **Abre el Arduino IDE** y carga el archivo `radar_1.ino` en tu placa Arduino.
3. **Conecta Arduino a la computadora** mediante un cable USB.
4. **Abre Processing** y ejecuta el código `radar_2.pde`.
5. **Observa la interfaz gráfica del radar** en Processing y mira cómo detecta objetos en su entorno.

## 📜 **Licencia**
Este proyecto es de **código abierto** y puedes modificarlo y mejorarlo según tus necesidades.

¡Disfruta construyendo tu propio **radar ultrasónico con Arduino**! 🚀
