<h1 align="center">
<img src="https://nodejs.org/static/images/logo.svg" width="122" height="75">
 <br>
</h1>

[Configurações do ambiente](https://www.notion.so/Configura-es-do-ambiente-d0fcddac0de642fb99fca7d8dbd28cc3)

# Introdução

Fala Dev! Seja muito bem vindo à **Next Level Week 05**, trilha **Node.js**🚀 

Para começar a preparar você para essa semana incrível de muito conteúdo e aprendizado, vamos começar configurando nosso ambiente de desenvolvimento, com algumas ferramentas fundamentais para chegarmos no fim desse evento com nosso backend finalizado.

<h1 align="center">
<img src="https://media.giphy.com/media/cPfjwUZtwArxyHVqjz/giphy.gif" style="display: block; object-fit: cover; border-radius: 1px; width: 100%; pointer-events: auto;">
</h1>

#### Dias
- Dia 1: Liftoff - :heavy_check_mark:
>We're go for launch. É hora de decolar e partir rumo ao próximo nível. Esse é o começo da nossa missão.

- Dia 2:

- Dia 3: 

- Dia 4: 

- Dia 5: 

# Guias

[Instalação das ferramentas](https://www.notion.so/Instala-o-das-ferramentas-405f3e8b014649cbb422dee6b5bd0535)

[Atualização (versões diferentes)](https://www.notion.so/Atualiza-o-vers-es-diferentes-09abff4d88d44c459a7c7a925ad15bfa)

[Tive problemas, e agora?](https://www.notion.so/Tive-problemas-e-agora-c67378e1319d4723a3211aad8eb987c6)

Opcional - Configurações adicionais do VS Code
Se você já configurou todo o ambiente seguido os passos anteriores e quer deixar o Visual Studio Code com as mesmas configurações usadas pela Daniele nessa trilha, aqui vão algumas dicas:

## Extensões

Você pode instalar as seguintes extensões a partir do menu de extensões do próprio VS Code:

- **[Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)**: Essa extensão faz a correção ortográfica no nosso código, funcionando melhor com camelcase (por padrão, corrige apenas o inglês). Essa extensão é bastante útil mas é totalmente opcional;
- **[Portuguese - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-portuguese)**: É um dicionário de português para que a extensão **Code Spell Checker** consiga fazer também a correção ortográfica em Português;
- **[Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)**: Essa extensão reconhece cores CSS escritas em qualquer lugar do nosso código. Por padrão reconhece apenas cores em hexadecimal mas você pode configurar para reconhecer cores no formato de palavras como `"red"` ou `"yellow"`. É uma extensão bastante útil, já que reconhece as cores diretamente no código;

## Configurações do VS Code

As seguintes configurações podem ser acessadas no VS Code apertando `Ctrl + Shift + P` (ou `cmd +` , digitando `Preferences: Open Settings (JSON)` e entrando na opção encontrada:

<h1 align="center">
<img src="https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F79aca06f-8252-4865-a00f-d557469bb025%2FUntitled.png?table=block&id=eb94d5b2-06be-4a11-b884-eb383837381d&width=1730&userId=c0530cfd-b499-49b5-9557-57b445ee0294&cache=v2" width="864" height="462.7">
</h1>

No arquivo JSON que abriu, adicione as seguintes configurações (certifique-se de adicionar dentro das chaves {}):

```json
"terminal.integrated.fontSize": 14,

"editor.tabSize": 2,
"editor.fontSize": 16,
"editor.lineHeight": 26,
"editor.semanticHighlighting.enabled": false,

"editor.rulers": [80, 120],

"editor.codeActionsOnSave": {
  "source.fixAll.eslint": true
},

"files.associations": {
  ".sequelizerc": "javascript",
  ".stylelintrc": "json",
  ".prettierrc": "json",
  "*.tsx": "typescriptreact"
},

"typescript.tsserver.log": "verbose",
"material-icon-theme.activeIconPack": "nest",

"material-icon-theme.folders.associations": {
  "infra": "app",
  "entities": "class",
  "domain": "class",
  "schemas": "class",
  "typeorm": "database",
  "repositories": "mappings",
  "http": "container",
  "migrations": "tools",
  "modules": "components",
  "implementations": "core",
  "dtos": "typescript",
  "fakes": "mock",
  "websockets": "pipe",
  "protos": "pipe",
  "grpc": "pipe",
  "providers": "include",
  "subscribers": "messages",
  "useCases": "controller",
  "kafka": "scripts",
  "mappers": "meta",
  "_shared": "shared",
  "eslint-config": "tools",
  "kube": "kubernetes"
},

"material-icon-theme.files.associations": {
  "ormconfig.json": "database",
  "tsconfig.json": "tune",
  "*.proto": "3d",
  "*.webpack.js": "webpack"
},
"window.menuBarVisibility": "toggle",
"cSpell.enableFiletypes": [
  "!asciidoc",
  "!c",
  "!cpp",
  "!csharp",
  "!go",
  "!handlebars",
  "!haskell",
  "!jade",
  "!java",
  "!latex",
  "!php",
  "!pug",
  "!python",
  "!restructuredtext",
  "!rust",
  "!scala",
  "!scss"
],
"cSpell.language": "en,pt",
"editor.suggestSelection": "first",
"cSpell.userWords": [
  "chakra",
  "middlewares",
  "prefetch",
  "rocketseat"
],
"workbench.productIconTheme": "fluent-icons",
"terminal.integrated.showExitAlert": false,

"splitHTMLAttributes.closingBracketOnNewLine": true,
"window.zoomLevel": 1
```

