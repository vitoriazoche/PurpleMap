# Purple Map

Um tabuleiro jogável inspirado na comunidade [He4rt Developers](https://heartdevs.com/). Role os dados, aprenda techs, ganhe XP e complete trilhas para virar referência na comunidade.

Tudo roda em um único `index.html`, sem build e sem dependências.

## Como jogar

- Você começa no **Hello World** com 500 XP e anda no sentido da seta.
- **Casas de tech:** pague o custo em XP para aprender. Ao cair de novo numa tech que já aprendeu, ganha 25% do custo; com a trilha completa, 50%.
- **Canais** (Discord, Twitch, GitHub, DEV) e **serviços** (Café, Wi-Fi) rendem XP quando você cai neles de novo.
- **Comunidade** e **Issue** sorteiam um card: ajuda da comunidade, sorte ou revés.
- **Deploy na sexta**, o card errado ou três duplas seguidas mandam você para o **Code Review**. Saia tirando uma dupla ou pagando 50 XP.
- Passar pelo Hello World rende 100 XP.
- **Vitória:** complete 3 das 6 trilhas. **Fim de jogo:** XP negativo.

O progresso e o tema escolhido ficam salvos no navegador (`localStorage`).

## Trilhas

| Trilha      | Techs                     |
| ----------- | ------------------------- |
| Fundamentos | Lógica, Git, Terminal     |
| Front-end   | HTML e CSS, JavaScript, TypeScript |
| Interfaces  | React, Vue, Tailwind      |
| Back-end    | PHP, Python, Go           |
| Infra       | Docker, Kubernetes, Cloud |
| He4rt Stack | Filament, Livewire, Laravel |

## Rodando localmente

Abra o `index.html` no navegador, ou sirva a pasta:

```bash
python -m http.server 8000
```

E acesse `http://localhost:8000`.

Para publicar no GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / root**.

## Acessibilidade

- Contraste WCAG 2.2 AA nos temas claro e escuro, com botão para alternar o tema.
- Jogável só com teclado, com foco visível e link para pular direto ao jogo.
- Cada jogada é anunciada para leitores de tela; cada casa tem uma descrição completa.
- Trilhas identificadas por nome e sigla, não só pela cor.
- No celular, o tabuleiro vira uma lista na ordem do jogo, com barra fixa de ações.
- Respeita `prefers-reduced-motion`.

## Créditos

- Fonte [Satoshi](https://www.fontshare.com/fonts/satoshi), da Indian Type Foundry, carregada pelo Fontshare.
- Fonte [Fira Code](https://github.com/tonsky/FiraCode), licença SIL Open Font License 1.1, carregada pelo Google Fonts.
- Ícones de interface baseados no [Heroicons](https://heroicons.com/) (MIT).
- Ícones de marca do Discord, GitHub e Twitch do [Font Awesome Free](https://fontawesome.com/license/free) (CC BY 4.0).
