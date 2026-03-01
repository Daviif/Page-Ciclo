# Page-Ciclo

Site estático simples com foco em jornada de check-in da academia.

## Páginas

- `index.html` (home com seleção de fluxo)
- `primeiro-acesso.html`
- `renovacao-plano.html`
- `gympass-totalpass.html`
- `faq.html`
- `404.html`
- `politica-de-privacidade.html`
- `robots.txt`
- `sitemap.xml`
- `netlify.toml`

## Como rodar local

Abra o arquivo `index.html` no navegador.

## Deploy no Netlify

1. Suba estes arquivos no repositório.
2. No Netlify, conecte o repositório.
3. Configure:
	- Build command: *(vazio)*
	- Publish directory: `.`
4. Publique o site.

## Checklist profissional mínimo

- SEO básico aplicado em todas as páginas (`meta description`, `canonical`, Open Graph e favicon).
- Página `404.html` para rotas não encontradas.
- Arquivos `robots.txt` e `sitemap.xml` para indexação.
- Headers de segurança e redirects versionados em `netlify.toml`.
- Página de privacidade com informações LGPD básicas.

## Ajuste obrigatório antes de produção

As URLs canônicas e do sitemap estão com placeholder:

- `https://eclectic-sundae-32af14.netlify.app/`

Antes de entregar ao cliente, troque pelo domínio final em:

- arquivos `.html` (tags `canonical`, `og:url`, `og:image`)
- `robots.txt`
- `sitemap.xml`