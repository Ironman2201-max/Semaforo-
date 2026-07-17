JOSE ALBERTO RODRIGUEZ
WILMER CHAMAPURO MOYA
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
   git clone [https://github.com/TU_USUARIO/Semaforo-.git](https://github.com/TU_USUARIO/Semaforo-.git)
