# By Jove! — Design System

> **Feita de encontros.**
> Sistema de design da By Jove!, marca brasileira de activewear feminino nascida no beach tennis.

Versão 1.0 · Julho de 2026 · base estratégica para produto, comunicação, experiência e comunidade.

---

## Essência

Encontro · Afinidade · Pertencimento · Elegância · Movimento.
O **ponto dourado** é o símbolo proprietário da marca — um ponto de encontro, uma conexão, um começo. Aparece sempre como **acento**, nunca como excesso.

## Paleta oficial

| Cor | Hex | Função |
|-----|-----|--------|
| Off-white | `#F6F2EC` | Base clara e silenciosa |
| Areia | `#E7DFD2` | Acolhimento e naturalidade |
| Taupe | `#D1C6B7` | Neutro quente intermediário |
| Pedra | `#B2A89B` | Neutralidade e equilíbrio |
| Carvão | `#22272F` | Cor principal da marca |
| Ouro acetinado | `#C9A66A` | Ponto de encontro — acento |

Extensões: Marinho `#162230` · Dourado fosco `#B69A67` · Mineral `#6E6A65` · Verde discreto `#6F786B`.

## Tipografia

- **Display / wordmark / títulos:** Bodoni Moda — *fashion serif* de alto contraste, substituto digital mais fiel ao logotipo proprietário By Jove!.
- **Texto serifado (citações):** Cormorant Garamond.
- **Interface / corpo:** Jost (geométrica leve) com *tracking* amplo para eyebrows e a tagline.

> **Ponto proprietário:** o pingo dourado (`#C9A66A`) é sempre o **ponto do "j"** — nunca o "!". O ponto de exclamação permanece em carvão. Para uso pixel-perfect, substitua o wordmark tipográfico pelo **vetor oficial** (SVG/PDF) da marca.

## Estrutura

```
index.html                      Galeria do design system
design-system/
├── tokens.css                  Design tokens (cores, tipografia, espaçamento)
├── foundations/
│   ├── colors.html
│   ├── typography.html
│   └── logo.html
└── components/
    ├── buttons.html
    ├── forms.html
    ├── cards.html
    ├── badges.html
    ├── navigation.html
    └── hero.html
```

## Uso

Abra `index.html` no navegador para navegar por todos os componentes, ou importe `design-system/tokens.css` no seu projeto e consuma as variáveis `--bj-*`.

Cada arquivo de preview traz um marcador `<!-- @dsCard -->` na primeira linha, usado para gerar os cards no projeto **Claude Design** correspondente.

---

*by jove! · feita de encontros.*
