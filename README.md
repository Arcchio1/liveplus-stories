# liveplus-stories

Artes de stories da Live Plus (1080x1920) para publicação automatizada no Instagram.

## Registro de peças

| Arte | Data de uso | Publicada em | URL de hospedagem (LinkedIn CDN, expira 03/12/2026) |
|---|---|---|---|
| countdown_11-11_B.png | 11/11/2026 12h | IG story (expectativa podcast) | https://media.licdn.com/dms/image/v2/D4D22AQG5WBmzTjlTpw/feedshare-shrink_1280/B4DaHKmpLIJIAM-/0/1794400491033?e=1796256000&v=beta&t=4l4nMVEh-SSbWTTwC_IF2Pmkvhv5rEqiYSxjqtlO1X4 |
| story_ergonomia_12-11.png | 12/11/2026 19h10 | IG story (chamada do post de ergonomia) | https://media.licdn.com/dms/image/v2/D4D22AQG14z6yc-_qpQ/feedshare-shrink_1280/B4DaHKmP0nJcAI-/0/1794400386808?e=1796256000&v=beta&t=Nujy5kdTSGMMEErZItziGfR-_JjoRMVypgGj5i--Sno |

## Padrão de stories (fixado pelo usuário em 11/11/2026)

- Zonas seguras do IG: conteúdo dentro de x 90–990, y ~290–1660 em 1080×1920
- Site em selo/chip próprio com contorno, separado do CTA por divisor fino, link grande
- CTA do post com seta apontando para a imagem do post
- Linguagem humanizada, sem travessão, sem construção "não é X, é Y"

## Fluxo de hospedagem

Os binários não sobem pela API do GitHub disponível. O arquivo é hospedado via
upload de imagem do LinkedIn (recipe `feedshare-image`, sem publicar post) e a
URL resultante alimenta o container do IG. Originais ficam em `artifacts/stories/`.
