# Relatório de SEO — Patinhas do Cerrado

## Palavras-chave escolhidas
1. **adoção de animais Uberaba**
2. **adotar cachorro e gato**
3. **ONG adoção responsável**

## Otimizações aplicadas
- **Metadados e indexação (`index.html` e `sobre.html`):** inclusão de `<title>` descritivo, `<meta name="description">`, `<link rel="canonical">` próprio por página, tags Open Graph (`og:title`, `og:description`, `og:image` apontando para `img/og-capa.png`, `og:url`, `og:locale`) e `favicon`.
- **Dados estruturados (`index.html`):** adição de bloco JSON-LD com `@type: "Organization"` (`Patinhas do Cerrado`, URL e localização em Uberaba, MG).
- **Arquitetura de links internos:** navegação e links contextuais entre `index.html` e `sobre.html` com textos âncora descritivos.
- **Rastreamento e mapa do site:** criação do `robots.txt` com diretiva `Sitemap` e do `sitemap.xml` com as URLs públicas do projeto.
- **Imagens e desempenho:** dimensões (`width` e `height`) e textos alternativos (`alt`) nas imagens, `loading="lazy"` nas imagens fora da primeira tela e criação da capa `img/og-capa.png`.

## Comparativo Lighthouse (Mobile — Antes × Depois)

| Categoria | Antes | Depois | Diferença |
| :--- | :---: | :---: | :---: |
| Performance | 79 | 81 | +2 |
| Accessibility | 96 | 96 | 0 |
| Best Practices | 96 | 100 | +4 |
| SEO | 91 | 100 | +9 |