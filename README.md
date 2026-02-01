# Meu Projeto Teste

Tema para Shopify inspirado em uma loja de pets com paleta azul claro e laranja. O layout usa gradiente de azul claro (#ADD8E6) para laranja (#FFA500) e inclui página 404 estilizada.

## Estrutura
```
assets/
  theme.css
config/
  settings_schema.json
layout/
  theme.liquid
sections/
  promo-bar.liquid
  header.liquid
  category-menu.liquid
  slideshow.liquid
  benefits-strip.liquid
  collection-list.liquid
  brands-slider.liquid
  newsletter.liquid
  footer.liquid
templates/
  index.json
  product.liquid
  collection.liquid
  404.liquid
```

Para gerar o arquivo `.zip` do tema:
1. Compacte a pasta do projeto: `zip -r pet-theme.zip .`
2. Faça o upload do `pet-theme.zip` no painel do Shopify em **Online Store > Themes > Upload zip**.
