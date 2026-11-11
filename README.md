# liveplus-stories

Artes de stories e carrosséis da Live Plus para publicação automatizada no Instagram.

## Estrutura

- `posts/<tema>/<data>/slideN.png` — slides de carrosséis (1080x1350)
- `stories/<nome>.png` — artes de story (1080x1920)

## Peças publicadas / agendadas

| Arte | Uso | Publicação |
|---|---|---|
| posts/ergonomia/2026-11-12/ (5 slides) | Carrossel de ergonomia (home office) | 12/11/2026 19h |
| stories/story_ergonomia_12-11.png | Story de chamada do post | 12/11/2026 19h10 |
| posts/diabetes/2026-11-14/ (5 slides) | Carrossel Dia Mundial do Diabetes | 14/11/2026 19h |
| stories/story_diabetes_14-11.png | Story de chamada do post | 14/11/2026 19h10 |
| posts/prostata/2026-11-17/ (6 slides) | Carrossel Dia Mundial de Combate ao Câncer de Próstata | 17/11/2026 19h |
| stories/story_prostata_17-11.png | Story de chamada do post | 17/11/2026 19h10 |
| stories/countdown_11-11.png | Story de expectativa do podcast | 11/11/2026 12h |

## Padrão de stories (fixado pelo usuário em 11/11/2026)

- Zonas seguras do IG: conteúdo dentro de x 90–990, y ~290–1660 em 1080×1920
- Site em selo/chip próprio com contorno, separado do CTA por divisor fino, link grande
- CTA do post com seta apontando para a imagem do post
- Linguagem humanizada, sem travessão, sem construção "não é X, é Y"
- Sem palavras órfãs: quebra de texto balanceada, linhas com larguras parecidas

## Fluxo de hospedagem (a partir de 11/11/2026)

As artes são enviadas como binário real via Git Data API (blobs + tree + commit)
usando um PAT do usuário. As URLs permanentes (raw.githubusercontent.com) alimentam
os containers do IG. O LinkedIn deixa de ser usado como CDN.
