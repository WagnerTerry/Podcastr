PODCASTR
SEMANA NLW #05
Usando React, Next

create-next-app podcastnext

para rodar o projeto
yarn dev

criar o arquivo \_document.tsx dentro de pages , para incluir as fontes e não recaregar a pagina toda hora

configurando o json server em package.json

"scripts": {
"server": "json-server server.json -w -d 750 -p 3333"
},

para rodar: yarn server

dependências

- yarn add typescript @types/react @types/node -D
- yarn add sass
- yarn add date-fns // lidar com datas - format
- yarn add json-server -D
