[Configurações do ambiente](https://www.notion.so/Configura-es-do-ambiente-d0fcddac0de642fb99fca7d8dbd28cc3)

# Introdução

Fala Dev! Seja muito bem vindo à **Next Level Week 05**, trilha **Node.js**🚀 

Para começar a preparar você para essa semana incrível de muito conteúdo e aprendizado, vamos começar configurando nosso ambiente de desenvolvimento, com algumas ferramentas fundamentais para chegarmos no fim desse evento com nosso backend finalizado.

<img src="https://media.giphy.com/media/cPfjwUZtwArxyHVqjz/giphy.gif" style="display: block; object-fit: cover; border-radius: 1px; width: 100%; pointer-events: auto;">

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

<img src="https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F79aca06f-8252-4865-a00f-d557469bb025%2FUntitled.png?table=block&id=eb94d5b2-06be-4a11-b884-eb383837381d&width=1730&userId=c0530cfd-b499-49b5-9557-57b445ee0294&cache=v2" width="864" height="462.7">

No arquivo JSON que abriu, adicione as seguintes configurações (certifique-se de adicionar dentro das chaves {}):

<div contenteditable="false" spellcheck="false" autocorrect="off" autocapitalize="off" placeholder=" " data-root="true" class="" style="flex-grow: 1; flex-shrink: 1; text-align: left; font-family: SFMono-Regular, Consolas, &quot;Liberation Mono&quot;, Menlo, Courier, monospace; font-size: 85%; tab-size: 2; padding: 34px 16px 32px 32px; min-height: 1em; color: rgba(255, 255, 255, 0.9); white-space: pre;"><span class="token property" data-token-index="0">"terminal.integrated.fontSize"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token number" data-token-index="0">14</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">

</span><span class="token property" data-token-index="0">"editor.tabSize"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token number" data-token-index="0">2</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
</span><span class="token property" data-token-index="0">"editor.fontSize"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token number" data-token-index="0">16</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
</span><span class="token property" data-token-index="0">"editor.lineHeight"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token number" data-token-index="0">26</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
</span><span class="token property" data-token-index="0">"editor.semanticHighlighting.enabled"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token boolean" data-token-index="0">false</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">

</span><span class="token property" data-token-index="0">"editor.rulers"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token punctuation" data-token-index="0">[</span><span class="token number" data-token-index="0">80</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0"> </span><span class="token number" data-token-index="0">120</span><span class="token punctuation" data-token-index="0">]</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">

</span><span class="token property" data-token-index="0">"editor.codeActionsOnSave"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token punctuation" data-token-index="0">{</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"source.fixAll.eslint"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token boolean" data-token-index="0">true</span><span data-token-index="0">
</span><span class="token punctuation" data-token-index="0">}</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">

</span><span class="token property" data-token-index="0">"files.associations"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token punctuation" data-token-index="0">{</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">".sequelizerc"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"javascript"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">".stylelintrc"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"json"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">".prettierrc"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"json"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"*.tsx"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"typescriptreact"</span><span data-token-index="0">
</span><span class="token punctuation" data-token-index="0">}</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">

</span><span class="token property" data-token-index="0">"typescript.tsserver.log"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"verbose"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
</span><span class="token property" data-token-index="0">"material-icon-theme.activeIconPack"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"nest"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">

</span><span class="token property" data-token-index="0">"material-icon-theme.folders.associations"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token punctuation" data-token-index="0">{</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"infra"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"app"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"entities"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"class"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"domain"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"class"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"schemas"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"class"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"typeorm"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"database"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"repositories"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"mappings"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"http"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"container"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"migrations"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"tools"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"modules"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"components"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"implementations"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"core"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"dtos"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"typescript"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"fakes"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"mock"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"websockets"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"pipe"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"protos"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"pipe"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"grpc"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"pipe"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"providers"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"include"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"subscribers"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"messages"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"useCases"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"controller"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"kafka"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"scripts"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"mappers"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"meta"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"_shared"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"shared"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"eslint-config"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"tools"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"kube"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"kubernetes"</span><span data-token-index="0">
</span><span class="token punctuation" data-token-index="0">}</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">

</span><span class="token property" data-token-index="0">"material-icon-theme.files.associations"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token punctuation" data-token-index="0">{</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"ormconfig.json"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"database"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"tsconfig.json"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"tune"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"*.proto"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"3d"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token property" data-token-index="0">"*.webpack.js"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"webpack"</span><span data-token-index="0">
</span><span class="token punctuation" data-token-index="0">}</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
</span><span class="token property" data-token-index="0">"window.menuBarVisibility"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"toggle"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
</span><span class="token property" data-token-index="0">"cSpell.enableFiletypes"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token punctuation" data-token-index="0">[</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"!asciidoc"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"!c"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"!cpp"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"!csharp"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"!go"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"!handlebars"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"!haskell"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"!jade"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"!java"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"!latex"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"!php"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"!pug"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"!python"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"!restructuredtext"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"!rust"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"!scala"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"!scss"</span><span data-token-index="0">
</span><span class="token punctuation" data-token-index="0">]</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
</span><span class="token property" data-token-index="0">"cSpell.language"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"en,pt"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
</span><span class="token property" data-token-index="0">"editor.suggestSelection"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"first"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
</span><span class="token property" data-token-index="0">"cSpell.userWords"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token punctuation" data-token-index="0">[</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"chakra"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"middlewares"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"prefetch"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
  </span><span class="token string" data-token-index="0">"rocketseat"</span><span data-token-index="0">
</span><span class="token punctuation" data-token-index="0">]</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
</span><span class="token property" data-token-index="0">"workbench.productIconTheme"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token string" data-token-index="0">"fluent-icons"</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
</span><span class="token property" data-token-index="0">"terminal.integrated.showExitAlert"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token boolean" data-token-index="0">false</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">

</span><span class="token property" data-token-index="0">"splitHTMLAttributes.closingBracketOnNewLine"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token boolean" data-token-index="0">true</span><span class="token punctuation" data-token-index="0">,</span><span data-token-index="0">
</span><span class="token property" data-token-index="0">"window.zoomLevel"</span><span class="token operator" data-token-index="0">:</span><span data-token-index="0"> </span><span class="token number" data-token-index="0">1</span><span>
</span></div>


