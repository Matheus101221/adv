# Soares, Sanches e Albuquerque Advogados Associados

Site institucional estático (HTML/CSS/JS), sem build.

## Estrutura
- `index.html` - página única com todas as seções
- `assets/` - logo, monograma, fotos da equipe (WebP) e ícones do site

## Editar
- Equipe (nomes e fotos): array `TEAM` no `<script>` do `index.html`. Fotos: `equipe-rafaela.webp`, `equipe-1.webp`, `equipe-3.webp`, `equipe-4.webp`. OAB e minibio (6º e 7º itens de cada linha) só aparecem quando preenchidos
- Artigos: array `ARTS`
- Formulário: preencher `FORM_ENDPOINT` (Formspree, Apps Script etc.). Sem endpoint, abre o WhatsApp.

## Publicar no GitHub Pages
Settings, Pages, Deploy from a branch, `main` / root.
