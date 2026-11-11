# liveplus-stories

Artes de stories da Live Plus (1080x1920) para publicação automatizada no Instagram.

## Registro de peças

| Arte | Data de uso | Publicada em | URL de hospedagem (LinkedIn CDN, expira 03/12/2026) |
|---|---|---|---|
| countdown_11-11_B.png (v2) | 11/11/2026 12h | IG story (expectativa podcast) | https://media.licdn.com/dms/image/v2/D4D22AQG75TA-EIkF3g/feedshare-shrink_1280/B4DaHKpGUTKIAI-/0/1794401134131?e=1796256000&v=beta&t=c59STnEWiTGiivJPw4kuTv0ocNM7ALdfKgnb1dv8yQ0 |
| story_ergonomia_12-11.png (v2) | 12/11/2026 19h10 | IG story (chamada do post de ergonomia) | https://media.licdn.com/dms/image/v2/D4D22AQHatWsEj_k8ug/feedshare-shrink_1280/B4DaHKpO8QK0AI-/0/1794401169463?e=1796256000&v=beta&t=1ZSFbTlxdGTV7cOLoN_PlXI_0z9ScmM6ttU_1qkRP4o |
| story_diabetes_14-11.png | 14/11/2026 19h10 (previsto) | IG story (chamada do post do diabetes) | a hospedar após aprovação |

## Padrão de stories (fixado pelo usuário em 11/11/2026)

- Zonas seguras do IG: conteúdo dentro de x 90–990, y ~290–1660 em 1080×1920
- Site em selo/chip próprio com contorno, separado do CTA por divisor fino, link grande
- CTA do post com seta apontando para a imagem do post
- Linguagem humanizada, sem travessão, sem construção "não é X, é Y"
- Sem palavras órfãs: quebra de texto balanceada, linhas com larguras parecidas (regra de 11/11/2026)

## Fluxo de hospedagem

Os binários não sobem pela API do GitHub disponível. O arquivo é hospedado via
upload de imagem do LinkedIn (recipe `feedshare-image`, sem publicar post) e a
URL resultante alimenta o container do IG. Originais ficam em `artifacts/stories/`.
