# PDK - Python Development Kit

PDK é um kit de desenvolvimento em Python criado para facilitar a criação de jogos utilizando pygame.

O objetivo do projeto é reduzir código repetitivo e acelerar a criação de protótipos.

## Objetivos

- Simplificar a inicialização de projetos
- Reduzir código boilerplate
- Facilitar prototipagem rápida de jogos

## Funcionalidades

- Estrutura base para projetos pygame
- Sistema simplificado de loop de jogo
- Organização modular

## Estrutura do projeto

PDK/
├─ model/
│  ├─ CAMERA/
│  │  ├─ __init__.py
│  │  └─ CAMERA.py
│  ├─ IA/
│  │  ├─ __init__.py
│  │  └─ IA.py
│  ├─ INTERNAL/
│  │  ├─ __init__.py
│  │  └─ CONTAINER.py
│  ├─ LOGICA/
│  │  ├─ __init__.py
│  │  ├─ HITBOX.py
│  │  └─ MOUSE.py
│  ├─ UI/
│  │  ├─ __init__.py
│  │  ├─ PAINEL.py
│  │  └─ TEXTBOX.py
│  ├─ VETORES/
│  │  ├─ __init__.py
│  │  ├─ VETOR2D.py
│  │  └─ WAYPOINT2D.py
│  ├─ __init__.py
│  └─ locals.py
├─ __init__.py
├─ cleaner.py
└─ LICENSE.txt

## Exemplo simples

```python
from pdk import Engine

engine = Engine()

while engine.loop():
    engine.update()
```
