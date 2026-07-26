JOSE ALBERTO RODRIGUEZ
--
WILMER CHAMAPURO MOYA --
FELIX EMILIO AYOVI ORDOÑEZ --  Darwin Andres Murillo Torres -- Yefferson Murillo Ibarguen
# Semáforo Inteligente con ESP32

Proyecto diseñado para simular el comportamiento real de un sistema de semáforos viales utilizando el microcontrolador ESP32. Ideal para aprender los fundamentos de control de tiempos, manejo de GPIO (pines de entrada/salida) y lógica de programación en sistemas embebidos.

---

## 🚀 Características
* **Simulación Real:** Control de tiempos preciso para las transiciones de luces (Verde, Amarillo, Rojo).
* **Modular:** Código estructurado que permite ajustar fácilmente los tiempos de espera de cada luz.
* **Plataforma:** Desarrollado para el ecosistema ESP32.

## 🛠️ Componentes Utilizados
* **Microcontrolador:** ESP32 (Cualquier variante como NodeMCU-32S).
* **Actuadores:** 3 LEDs (Rojo, Amarillo, Verde).
* **Resistencias:** 3 resistencias de $220\ \Omega$ (para proteger los LEDs).
* **Otros:** Protoboard y cables de conexión (Jumpers).

## 🔌 Conexión de Pines (Esquema Sugerido)
| Componente | Pin ESP32 |
| :--- | :--- |
| LED Rojo | GPIO 23 |
| LED Amarillo | GPIO 22 |
| LED Verde | GPIO 21 |
| GND (Tierra) | GND |

## 💻 Requisitos e Instalación
1. Descarga e instala [Arduino IDE](https://www.arduino.cc/en/software).
2. Asegúrate de tener instalado el gestor de tarjetas para **ESP32** en el IDE.
3. Clona este repositorio:
   ```bash
   git clone https://github.com/Ironman2201-max/Semaforo-.git

Análisis:
El trabajo presenta una propuesta organizada para el control de una intersección básica con semáforos vehiculares y peatonales. La incorporación de una fase de Todo Rojo constituye un aspecto positivo desde el punto de vista de la seguridad operacional, al igual que la coordinación entre el paso vehicular y peatonal. El diagrama muestra una secuencia lógica y continua del ciclo semafórico.

No obstante, la propuesta puede fortalecerse mediante un diseño gráfico de la intersección, el uso de un diagrama de flujo con simbología estandarizada y una fundamentación técnica más detallada de los tiempos y de la lógica empleada. Asimismo, la incorporación de giros protegidos permitiría representar una intersección más completa y cercana a un sistema de semaforización real.
