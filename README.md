# Projeto base frontend (lite)

## Copiar o projeto

Para iniciar o projeto basta fazer o git clone do repositório com o comando: 

``` 
git clone https://github.com/tzadoque/base-project-frontend-lite
```

## Instalar módulos


Logo após você irá instalar os módulos necessários com um dos comandos:
```
yarn install 
```
ou 
```
npm install
```

## Iniciar servidor local

O servidor que vem instalado é o live-server, para iniciá-lo basta utilizar o comando:
```
npx live-server
```
Fique a vontade para usar outro servidor da sua preferência.

## Scripts

Apenas dois scripts estão criados por padrão, o do ```webpack``` e do ```sass```. Quando algum dos dois são rodados eles geram automaticamente a pasta dist, por isso ela não vem no repositório.

```
"scripts": {
  "scss": "sass --watch src/scss/style.scss:dist/css/style.css --style compressed",
  "webpack": "webpack -w"
},
```

## Lite?

Então... Tentei criar um projeto base bem elaborado, com automação com gulp, babel, otimização de imagens, porém ficou bem pesado para rodar no meu pc, então resolvi criar esse projeto que não utiliza gulp e seus scripts são rodados individualmente.
