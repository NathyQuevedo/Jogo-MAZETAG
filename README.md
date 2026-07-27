# MazeTag

> Dois jogadores. Um labirinto. Nenhum lugar para se esconder.

MazeTag é um jogo 2D de perseguição local para dois jogadores desenvolvido em **Unity**. Um jogador é o Pegador, o outro é o Fugitivo — e o labirinto é o único árbitro.

---

## Como jogar

| | Jogador 1 — Pegador | Jogador 2 — Fugitivo |
|---|---|---|
| **Controles** | `W` `A` `S` `D` | `↑` `↓` `←` `→` |
| **Objetivo** | Encurralar e pegar o Fugitivo | Sobreviver pelo maior tempo possível |

---

## Funcionalidades

- Seleção de personagem individual para cada jogador
- Power-ups no labirinto: boost de velocidade e lama lentificante
- Tela de resultados com nome dos jogadores e estrelas coletadas
- Sistema de funções fixas: P1 sempre começa como Pegador

---

## Tecnologias

- **Unity 6** (6000.3.7f1)
- **C#**
- **TextMesh Pro**
- Fisica 2D com `Rigidbody2D`
- Persistência de dados entre cenas via `PlayerPrefs` e `DontDestroyOnLoad`

---

## Estrutura do projeto

```
Assets/
├── Scenes/          # Menu, Selecao de Personagem, Labirinto, Resultados
├── Scripts/         # GameManager, CharacterSelectManager, PlayerMovimento, PlayerTag...
├── Sprites/         # Personagens e elementos do labirinto
└── TextMesh Pro/    # Fontes e configuracoes de UI
```

---

## Desenvolvido por

**Nathaly** — Projeto desenvolvido como trabalho de conclusão do curso Técnico de Informática na EEEPE.

---

## Licença

Este projeto é de uso educacional.
