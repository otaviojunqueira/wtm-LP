# WTM Tênis de Mesa — Landing page

Site estático (HTML + CSS + JS puro, sem build). Basta abrir `index.html` no navegador.

## Estrutura

```
index.html        página única (SEO: meta tags, Open Graph, JSON-LD SportsClub)
css/style.css     estilos (tokens no topo, em :root)
js/main.js        menu mobile, header ao rolar, reveal, contadores
fonts/            Archivo (variável, peso + largura) e Inter — auto-hospedadas
assets/           logo vetorizada (SVG), favicon, apple-touch-icon, og-image
```

## Pendências antes de publicar

- [ ] Confirmar o ano de fundação (rodapé diz "desde 2000", deduzido dos "26 anos de história").
- [ ] Revisar os textos de "Quem somos" e das turmas com o professor.
- [ ] Confirmar se dá pra divulgar os dias e horários de cada CT (é o que mais converte).
- [ ] Trocar o link do WhatsApp (`wa.me/qr/...`) por `https://wa.me/55DDDNUMERO?text=...` com mensagem pronta.
- [ ] Adicionar fotos reais dos treinos (seção de galeria ou imagem no hero).
- [ ] Registrar o domínio e ajustar `<link rel="canonical">` e `og:image` para URLs absolutas.
- [ ] Criar/atualizar o Perfil da Empresa no Google (Google Business Profile) para os dois CTs.

## Deploy

Funciona em qualquer hospedagem estática: Vercel, Netlify, GitHub Pages ou Cloudflare Pages (todas grátis).
