# Página para a Minha Namorada

Este projeto é uma página estática em HTML/CSS para publicação no GitHub Pages.

## Estrutura

- `index.html` — página principal
- `*.jpeg` — imagens usadas na galeria
- `.nojekyll` — evita processamento Jekyll pelo GitHub Pages

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Faça upload destes ficheiros para o repositório.
3. No GitHub, vá a `Settings` → `Pages`.
4. Em `Source`, escolha `Deploy from a branch`.
5. Selecione a branch principal e a pasta `/root`.
6. Guarde.
7. O GitHub Pages irá gerar um link público como:
   `https://seu-usuario.github.io/nome-do-repositorio/`

## Observações

- A página usa apenas HTML estático.
- Não necessita de build nem de Node.js.
- Todas as imagens devem permanecer na raiz do projeto para que o GitHub Pages as carregue corretamente.
