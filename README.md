# BraSil

Jogo pra aprender (ou reaprender) os 27 estados do Brasil: bandeiras, capitais, lugar no mapa, gentílicos e regiões.

**Jogar:** abra o link do GitHub Pages deste repositório.

## O que tem
- **Jogar:** Misturado, Bandeiras, Capitais, Mapa e Gentílicos. Em "Mais opções" dá pra filtrar por região, escolher quantas perguntas ou jogar contra o relógio (60 segundos).
- **Desafio do dia:** 10 perguntas que mudam todo dia, com contagem de dias seguidos.
- **Regiões:** Arrasta pras regiões, Completa a região (de cabeça) e Qual é a região?
- **Campanha:** uma região por vez, até o Brasil todo.
- **Álbum:** ficha de estudo de cada estado.

O que você erra volta na mesma partida e aparece mais nas próximas. O progresso fica salvo no navegador de quem joga.

## Rodar localmente
É um site estático: `index.html` + `data.json`. Como o jogo carrega `data.json` com `fetch`, sirva a pasta por HTTP (por exemplo `python3 -m http.server`) em vez de abrir o arquivo direto.

## Créditos
- Bandeiras dos estados: Wikimedia Commons, domínio público (via pacote npm `flags-brasil`).
- Mapa do Brasil: [svg-maps](https://github.com/VictorCazanave/svg-maps) por Victor Cazanave, licença [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- Fontes: Unbounded, Bricolage Grotesque e Space Mono (Google Fonts).
