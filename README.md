# Glossário Gamer & Retromodding — GG–001

Glossário interativo do universo gamer e retromodding: **74 verbetes** sobre hardware, emulação, jogabilidade e cultura dos jogos. Uma página estática, sem frameworks, com cara de manual de fliperama impresso em papel creme.

## Acesso online

| Projeto | Link |
|---|---|
| 📖 **Glossário** | https://kaioviniciusp.github.io/glossario-gamer-retromodding/ |
| 📊 **Apresentação** | https://kaioviniciusp.github.io/apresentacao-glossario-gg-001/ |

> A apresentação tem repositório e site Pages próprios — o link dela também está no rodapé do glossário.

## O que tem aqui

- `index.html` — o glossário completo (HTML + CSS + JavaScript em um único arquivo).
- `DOCUMENTACAO.md` / `DOCUMENTACAO.txt` — documentação técnica do projeto.

## Funcionalidades

- Busca em tempo real tolerante a acentos, com destaque dos termos encontrados
- Filtros por categoria e por favoritos, ordenação Padrão/A–Z e termo aleatório
- Favoritos persistidos em `localStorage`
- Ficha completa em modal `<dialog>` nativo, com links profundos via hash (ex.: `#retrobright`)
- Cópia da definição para a área de transferência
- Atalho `/` para focar a busca
- Acessibilidade: skip link, estados ARIA, foco visível e respeito a `prefers-reduced-motion`

## Categorias

| Categoria | Código | Cor | Termos |
|---|---|---|---:|
| Hardware/Mod | `HW` | azul `#0032A8` | 17 |
| Emulação | `EM` | verde `#018D3E` | 17 |
| Jogabilidade | `JB` | rosa `#C21B5A` | 21 |
| Cultura & Mercado | `CT` | vermelho `#E71506` | 19 |

## Rodando localmente

Abra o `index.html` no navegador — não precisa instalar nada.

## Créditos

Criado por kaio. Ícones em SVG inline, sem dependências externas além das fontes do Google Fonts.
