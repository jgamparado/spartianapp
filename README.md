# Spartiate App

App web (PWA) entregável do Protocolo Vitalité — em francês.

- **Recette** — calculadora (idade, altura, peso) que gera o Tonique Spartiate au concombre com quantidades personalizadas
- **Bonus** — 6 receitas (sel bleu, pastèque, carotte, anti-inflammatoire, betterave, fruit violet)
- **Techniques** — 6 módulos (7 mouvements, erreur silencieuse, toucher magique, oral, 5 secrets, murmure)
- **21 jours** — plano diário com checklist e timer de exercício pélvico

Arquivo único (`index.html`) sem build. Progresso fica salvo no navegador do cliente (localStorage).
Pode ser instalado na tela inicial (manifest + service worker) e funciona offline após o primeiro acesso.

## Publicar
GitHub Pages: Settings → Pages → Deploy from branch `main` / root. Ou suba a pasta em qualquer hospedagem estática (Netlify, Vercel, Hostinger).
