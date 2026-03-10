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

### Model

A pasta "Model" é o coração do projeto, contendo módulos que funcionam para diferentes áreas de um desenvolvimento com pygame.
Dentre estes temos os principais módulos:
- INTERNAL
- LOGIC
- UI

Estes grupos fornecem todas as funcionalidades que seus nomes auto descrevem, sendo possivel focar em um só grupo sem que tudo quebre ao mexer com outro.

Cada grupo é independente do outro, sendo possível ter jogos diretamente no terminal com o grupo "LOGIC" ou imagens estáticas com o grupo "UI";
no entanto, peço que não mexa no grupo internal a menos que tenha certeza de que sabe oque esta fazendo, pois este grupo requer conhecimentos um pouco mais avançados sobre POO e Modularização.

## Exemplo simples

```python
from pdk import Engine

engine = Engine()

while engine.loop():
    engine.update()
```
