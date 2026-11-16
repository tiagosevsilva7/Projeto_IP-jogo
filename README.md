# 🗡️ Chumbo & Sangue (Estilo Bullet Hell) - 

> Jogo no estilo bullet hell ambientado em um apocalipse zumbi, desenvolvido para a disciplina de Introdução a Programação da UFPE

---

## 📋 Sobre o Jogo:
Este projeto consiste em um jogo 2D de ação e sobrevivência, desenvolvido 100% em Python aplicando conceitos de Programação Orientada a Objetos (POO) e Lógica de Programação Introdutória aprendidos nas aulas da disciplina de Introdução a Programação. 

O jogador controla um personagem em uma arena 2D com o objetivo de sobreviver a hordas de inimigos enquanto coleta diferentes tipos de itens espalhados pelo mapa, com registro e exibição em tempo real na interface.

---

## 🪙 Tipos de Coletáveis Principais:
  1. 🛡️ **Escudo Temporário:** Concede um escudo que bloqueia ataques por 5 segundos.
  2. 🏹 **Aumento do Arsenal:** Aumenta o número de projéteis do personagem.
  3. ❤️ **Poção / Item de Cura:** Restaura os pontos de vida do personagem.
Registro em Tela: Contabilização e exibição simultânea da quantidade coletada de cada item principal.

---

## 💻 Linguagem e Bibliotecas Utilizadas: (por enquanto)

**[Python]** – Linguagem utilizada em todo projeto.
**[Pygame]** - Biblioteca principal para gerenciamento de janela, loop, renderização de sprites, áudio e detecção de colisões etc.
**[Random]** – Spawnar aleatoriamente os zumbis, atribuição de diferentes atributos e tamanho, lógica de drop para itens, caso o zumbi morra. 
**[Math]** – Para calcular ângulos e distâncias, garantir que o projétil viaje em linha reta na posição onde o zumbi estava no momento do disparo.

---

## 🏗️ Organização geral do Projeto: (por enquanto)

Estrutura geral visando melhor organização e aproveitamento:

```text
projeto-jogo-ip/
├── assets/            # Imagens, fontes, efeitos sonoros
│   ├── images/        # Para imagens gerais do jogo
│   ├── sounds/        # Para efeitos sonoros
│   └── musica/        # Para músicas
├── classes/           # Guarda os arquivos dos principais objetos do jogo
├── utils/             # Funções auxiliares do projeto
├── constantes.py      # Valores fixos usados para qualquer partes do projeto
├── main.py            # Parte principal
├── requirements.txt   # # Bibliotecas usadas
├── .gitignore         # Arquivos/Pastas que não devem ser enviadas para o repositório
└── README.md          # Documentação e apresentação geral do projeto


