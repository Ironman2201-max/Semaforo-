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
El trabajo presenta una buena implementación desde el punto de vista de la programación. El código está organizado, utiliza una secuencia lógica de estados e incorpora correctamente las fases de verde, amarillo y todo rojo, además de coordinar el paso de peatones con el tránsito vehicular. Sin embargo, la evaluación del taller también requería documentar el diseño de la intersección y representar el algoritmo mediante un diagrama de flujo, elementos que no fueron entregados. Asimismo, la propuesta se limita a una intersección básica de dos ejes, sin contemplar giros protegidos u otros movimientos adicionales. En consecuencia, el proyecto demuestra una buena base técnica en programación, pero requiere fortalecer la documentación y el diseño funcional para cumplir completamente con los objetivos del taller.
