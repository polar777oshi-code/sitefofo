# Para a Milk ❤️

Uma pequena página secreta, feita com carinho. Next.js (App Router) + TypeScript + Tailwind CSS 4 + Framer Motion.

## Rodar localmente

```bash
npm install
npm run dev
```

Abra http://localhost:3000. Para testar a versão de produção: `npm run build && npm run start`.

## Publicar na Vercel

**Pela interface:** suba a pasta para um repositório no GitHub → vercel.com/new → importe o repositório → **Deploy** (nenhuma configuração extra; o framework Next.js é detectado sozinho).

**Pela CLI:**

```bash
npm i -g vercel
vercel        # primeira vez: responda as perguntas
vercel --prod
```

## Personalizar

- **Todos os textos** estão em `lib/content.ts` (carta, cartões, frases, assinatura).
- **Cores e fontes**: bloco `@theme` em `app/globals.css`.
- **Tempo da revelação**: `STEP_TIMES` em `components/Reveal.tsx`.

A página usa `noindex`, então não aparece em buscadores. Requer Node 20.9+.
