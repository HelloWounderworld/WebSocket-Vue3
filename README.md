# vuejs-websocket-tutorial

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### Fonte em que me baseei para realizar o teste de websocket:
https://fjolt.com/article/vue-how-to-set-up-a-websocket-server

### Forma para testar:
Após dar o npm i no repositório, pois já deixei nas dependências os módulos necessários para instalar automaticamente nas sua máquina, bastaria abrir um terminal e trabalhar em duas janelas da seguinte forma:

Primeira Janela: Vc roda node index.mjs ou, vc poderia instalar o noemon usando o comando "npm install -g nodemon" no repositório para rodar, nodemon index.mjs. Assim, vc irá abrir uma aba no navegador com o endereço "localhost:8080".

Segunda Janela: Visto que foi executado a primeira janela, nela vc irá rodar o comando "npm run serve". Isso, provavelmente, irá abrir uma outra porta diferente da porta, 8080, que foi aberto na primeira janela. Assim, abrindo a respectiva aba, na qual é indicada, após rodado o "npm run serve", irá aparecer um template onde será exibido uma mensagem de boas vindas e em "You are:" e "Your message is:" irá mostrar, respectivamente, se vc está ou não conectado e se a mensagem foi ou não enviado. 
