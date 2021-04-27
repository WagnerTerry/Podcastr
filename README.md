PODCASTR
SEMANA NLW #05
Usando React, Next

npx create-next-app podcastnext

para rodar o projeto
yarn dev

criar o arquivo \_document.tsx dentro de pages , para incluir as fontes e não recaregar a pagina toda hora

configurando o json server em package.json

"scripts": {
"server": "json-server server.json -w -d 750 -p 3333"
},

para rodar: yarn server // abrir uma aba pra ele junto com o yarn dev

dependências

- yarn add typescript @types/react @types/node -D
- yarn add sass
- yarn add date-fns // lidar com datas - format
- yarn add json-server -D
- yarn add axios
- yarn add rc-slider

usar se quiser o PWA ou electron
