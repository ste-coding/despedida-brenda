# Despedida de solteira da Brenda — convite digital

Site de página única, baseado na estrutura do convite de aniversário da Adriana.
Só HTML + Tailwind via CDN: é só publicar a pasta (GitHub Pages, Netlify, Vercel).

## O que precisa ser trocado antes de publicar

| Onde | O quê |
|---|---|
| `index.html` → `WHATSAPP_GROUP_URL` | Link do grupo do WhatsApp (hoje está `COLE-SEU-LINK-AQUI`) |
| `index.html` → meta tags `og:*` e `canonical` | URL final do site (preview no WhatsApp) |
| `assets/brenda.jpg` | Foto de rosto da noiva (quadrada) — hoje é o recorte da foto de infância |
| `assets/brenda-taca.jpg` | Mesma foto, enquadramento mais aberto, usada no modal "Talvez" |
| `assets/musica.mp3` | Música de fundo (hoje é a mesma do projeto anterior) |
| `assets/video.MOV` (opcional) | Vídeo de fundo, aplicado sobre o vinho em `mix-blend-luminosity`. Sem o arquivo, fica só o fundo vinho com as taças |

## Paleta

Os nomes dos tokens do Tailwind foram mantidos — só os valores mudaram, então
todas as classes antigas continuam funcionando.

| Token | Cor |
|---|---|
| `primary` | `#80011f` — vinho do fundo do convite |
| `secondary` | `#c1112e` — vermelho dos traços e do "vai casar" |
| `surface` | `#fff7f6` — branco quente |
| `surface-container-low` | `#feecec` — rosa clarinho da mancha do convite |
| fundo da página | `#6d0119` com padrão de taças em traço fino (`#bgRedField`) |
| `on-surface` | `#3a1017` |

## Estrutura da página

1. Loader vinho com barra de progresso
2. Header fixo "Brenda vai casar · 15/08"
3. Hero — letras recortadas "brenda" (uma linha só) + "vai casar" em script + data/hora
4. Introdução
5. Dress code vermelho + Presente coletivo (com botão de copiar o Pix)
6. Local (Salão de festas — Direcional Praia)
7. Bilhete "Não esqueça" pregado, igual ao papel do convite
8. Confirmação de presença (grupo do WhatsApp) e modal "Talvez"
9. Convite original em imagem
10. Área final que revela o fundo

## Fontes

- **Epilogue** — títulos
- **Caveat Brush** — "vai casar" e "Lembretes" (o pincel do convite)
- **Cormorant Garamond** — texto do bilhete e do local (o serif do convite)
- **Plus Jakarta Sans** — corpo
