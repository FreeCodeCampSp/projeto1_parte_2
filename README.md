# Introduçao a processadores de HTML e CSS

Os navegadores modernos sabem ler **HTML**, **CSS** e **JavaScript**. Desenvolvedores modernos usam diversas outras ferramentas e linguagens para escrever esses códigos de maneira mais eficiente.
Nesta etapa do projeto vamos abordar o [Pug](https://github.com/pugjs/pug) para HTML e o [SASS](http://sass-lang.com/) para CSS.

Para usar essas ferramentas necessitamos da **linha de comando** na qual vamos usar o [Node](https://nodejs.org/en/) como forma de escrever programas em JavaScript e a ferramenta [NPM](https://www.npmjs.com/).

## Instalando o Node (E o NPM vem junto)

O Node tem um instalador para todos os sistemas praticamente simplesmente navegue até [o site oficial](https://nodejs.org/en/) e baixe a versão mais atual.

## A linha de comando

A linha de comando é uma ferramenta para escrever texto(Comandos) que são transmitidos para programas que executam ações. A maioria dos usuários de computador estão acostumados com interfaces gráficas, no entando desenvolvedores muitas vezes usam e até preferem ferramentas de linha de comando.

Para abrir a linha de comando

**No windows**: Procure o programa terminal ou cmd

**No linux/Mac**: Procure o programa terminal

Uma vez que nós temos o node e npm instalados podemos começar a nos familiarizar. Para conferir se ambos estão instalados execute os seguintes comandos:
```shell
node --version
```

```shell
npm -v
```

Você deve obter um comportamento similar ao mostrado abaixo:

[![Exemplos de linha de comando](./cliExample.gif)](./cliExample.gif)

Parabéns você acabou de dar seus primeiros comandos em uma linha de comando!

### Pastas e navegação

Você quer que a suas aplicações fiquem contidas todas na mesma pasta. Para isso é importante saber navegar por pastas usando a linha de comando, para isso vamos listar alguns comandos iniciais:

- **cd NOME_DE_UMA_PASTA** - Navega até a pasta
- **dir** - Lista as pastas no diretório atual
- **cd ..** - Navega até a pasta anterior
- **mkdir** - Cria uma pasta

Para começarmos crie (pela linha de comando ou de forma tradicional), uma pasta chama projeto2 e navegue até ela como no exemplo abaixo.

[![Navegação de pasta](./cliExample2.gif)](./cliExample2.gif)

Isso muda o **diretório atual** é a referência de onde os comandos vão ser executados.

> Pense no diretório atual como a palavra **aqui**. A palavra não muda mas o significado do que é **aqui** é totalmente diferente se você está em casa ou no trabalho.
