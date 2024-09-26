# Deep Q-Learning Snake Agent

Este proyecto implementa un agente de aprendizaje por refuerzo (Reinforcement Learning) utilizando Deep Q-Learning para jugar el clásico juego de Snake. El agente aprende a maximizar su puntuación moviéndose de manera óptima para evitar colisiones y comer comida.

## Descripción del Proyecto

El agente se entrena utilizando un modelo de red neuronal con Deep Q-Learning, lo que le permite aprender a través de la experiencia jugando múltiples partidas. El modelo es capaz de tomar decisiones basadas en el estado actual del juego, el cual incluye la posición de la comida, la dirección de movimiento y posibles peligros de colisión.

## Estructura del Proyecto

El proyecto está compuesto por varios archivos:

- `agent.py`: Contiene la lógica principal del agente de aprendizaje por refuerzo, incluyendo la definición del modelo de red neuronal y las funciones de entrenamiento.
- `model.py`: Define la arquitectura de la red neuronal y el entrenador de Q-Learning.
- `game.py`: Implementa el entorno del juego de Snake, que es controlado por el agente.
- `helper.py`: Contiene funciones auxiliares, como la visualización de gráficos de puntuación.
- `human.py`: Contiene el juego tal cual para usarlo como usuario.

## Requisitos

- Python 3.10 o superior
- Bibliotecas necesarias:
  - `torch`: Para implementar la red neuronal.
  - `pygame`: Para operaciones matemáticas.
  - `matplotlib`: Para visualizar las puntuaciones del agente.

Instalar dependencias con:

```bash
pip install -r requirements.tx
```

## Para entrenar al agente:

```
python agent.py
```

## Para jugarlo como humano:

```
python human.py
```

https://github.com/patrickloeber/snake-ai-pytorch

## Built by
- [@Brun0Galli](https://github.com/Brun0Galli)

## Suggestions by
- [@EnriqueGomezTagle](https://github.com/enriquegomeztagle) / [@kikinacademy](https://github.com/kikinacademy)

## Inspired on
- [snake-ai-pytorch](https://github.com/patrickloeber/snake-ai-pytorch)
