# LFGAMidias — Landing page

Site de apresentação da LFGAMidias, com notebook 3D que "monta" um site conforme a página rola.

## Estrutura

- `index.html` — o site completo em um único arquivo (React e Three.js carregados por CDN). É o que vai para o Vercel.
- `vercel.json` — configuração opcional do Vercel (cabeçalhos de segurança).
- `framer/LFGAMidiasLanding-Framer.tsx` — versão em Code Component para colar no Framer.

## Antes de publicar

Abra o `index.html`, procure por `SEU_NUMERO_AQUI` e troque pelo número do WhatsApp (somente dígitos, com DDI e DDD, ex.: `5571999999999`).

## Publicar no Vercel

1. No Vercel: **Add New > Project** e importe este repositório.
2. **Framework Preset:** Other. Deixe comando de build e pasta de saída em branco.
3. **Deploy**.

## Testar localmente

Abra o `index.html` no navegador (precisa de internet para carregar React, Three.js e as fontes).
