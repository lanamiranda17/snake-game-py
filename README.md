# Snake Game | Python

Implementação do clássico **Jogo da Cobrinha (Snake Game)** em Python, utilizando a biblioteca Pygame para renderização gráfica, movimentação e detecção de colisões. Desenvolvido com o objetivo de consolidar o aprendizado em python e usar novas bibliotecas.

O jogo inclui obstáculos gerados aleatoriamente, sistema de pontuação e aumento progressivo da dificuldade conforme a cobra coleta alimentos.

---

## Funcionalidades

- **Movimentação:** controle da cobra pelas teclas direcionais.
- **Pontuação:** incremento dos pontos a cada alimento coletado.
- **Obstáculos dinâmicos:** geração de novos obstáculos conforme a pontuação aumenta.
- **Dificuldade progressiva:** aumento da quantidade de obstáculos durante a partida.
- **Detecção de colisões:** encerramento do jogo ao atingir o próprio corpo ou um obstáculo.
- **Movimentação contínua:** a cobra atravessa as bordas da tela e reaparece no lado oposto.

## Tecnologias

- **Python 3**
- **Pygame**

## Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/lanamiranda17/Jogo-da-Cobrinha.git
cd Jogo-da-Cobrinha
```

### 2. Instale o Pygame

```bash
pip install pygame
```

### 3. Execute o jogo

```bash
python SnakeGame.py
```

## Controles

| Tecla | Ação |
|---|---|
| <escape>↑</escape> | Mover para cima |
| <escape>↓</escape> | Mover para baixo |
| <escape>←</escape> | Mover para a esquerda |
| <escape>→</escape> | Mover para a direita |

## Regras

O objetivo é coletar o maior número possível de alimentos sem colidir com os obstáculos ou com o próprio corpo.

A cada alimento coletado, a cobra cresce, a pontuação aumenta e um novo obstáculo é adicionado ao cenário.

O jogo termina quando ocorre uma colisão.
