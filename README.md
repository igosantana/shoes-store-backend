# Loja de Tênis API

Este é o projeto de uma api para a [loja de tênis](https://shoes-store-frontend.vercel.app/). Neste projeto foram criadas as rotas de produtos, categorias e pedidos.

## Ferramentas
 - Api criada com o CMS Strapi e typescript.
 - Banco de dados Postgres criado no [render](https://render.com/).
 - Cloudinary para o storage das imagens.
 - Strepi para a realização do pagamento do produto.

### `develop`

Após fazer as instalações das dependências

```
npm run develop
# or
yarn develop
```

## Deploy

O deploy da api foi realizado pelo [render](https://render.com/)


## Rotas

[api](https://shoe-store-pmx8.onrender.com)

### Produtos
 - GET (Retorna todos os produtos com suas imagens)
    - /api/products?populate=*
 
### Categorias
  - GET (Retorna todas as categorias com os produtos)
     - /api/categories?populate=*
 
### Pedidos
  - POST(Utilizado para realizar o pagamento dos produtos)
      - /api/order
