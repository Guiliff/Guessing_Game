# 🎯 Guessing Game - ![Linguagem C](https://img.shields.io/badge/feito%20em-C-blue.svg)

Um simples jogo de adivinhação escrito em linguagem C, executado no terminal. O objetivo
é adivinhar corretamente um número secreto gerado aleatoriamente entre 0 e 50. O jogo
possui três níveis de dificuldade, cada um com uma quantidade limitada de tentativas.
## 🚀 Como Jogar
1. **Clone ou copie o código** para sua máquina.
```bash
git clone https://github.com/Guiliff/Guessing_Game.git
cd Guessing_Game
```

3. **Compile o código** com o GCC no terminal:
```bash
gcc guessing_game.c -o guessing_game.out
./guessing_game.out
```

<div align="center">
  <img src="https://github.com/Guiliff/Guessing_Game/blob/main/assets/gccg.gif?raw=true" alt="Compilando o jogo" />
</div>

3. **Escolha o nível de dificuldade:**
- (1) Fácil -> 15 tentativas
- (2) Médio -> 10 tentativas
- (3) Difícil -> 5 tentativas
4. **Tente adivinhar o número secreto!**
Com base nas dicas dadas pelo jogo (muito alto, muito baixo ou correto), tente acertar o
número antes que suas tentativas se esgotem.

<div align="center">
  <img src="https://github.com/Guiliff/Guessing_Game/blob/main/assets/test.gif?raw=true" alt="Testando o jogo" />
</div>

## 🧠 Lógica do Jogo
- O número secreto é gerado aleatoriamente entre 0 e 50.
- Cada palpite gera uma resposta:
  - Se for correto, o jogo termina com uma mensagem de vitória.
  - Se for maior ou menor, o jogo indica isso.
  - Palpites negativos não são válidos e não contam como tentativa.
- O jogo termina quando:
  - O jogador acerta o número, ou
  - Todas as tentativas se esgotam.
## 🛠 Requisitos
- Compilador C (como o GCC) via terminal, ou
- IDE com suporte à linguagem C, como:
  - Visual Studio Code (com a extensão C/C++)
  - Code::Blocks
  - Dev-C++
---
Divirta-se e bons palpites!
