# BarrelGen

Este script tem como objetivo facilitar a criação de um arquivo `index.js` que realiza o "barrel" de módulos em um diretório de componentes. O "barrel" consiste em criar um arquivo de índice que exporta todos os componentes contidos em um diretório, facilitando sua importação em outros arquivos.

![Demonstração](/barrel-gen.gif)

Para determinar no script o path do diretório que necessita o barrel, substitua o valor da variavel na linha 3 directory_folder (python) ou directoryFolder (javasript) com uma string com o path

Exemplo (javascript):
```
const directoryFolder = '/home/fischer/Desktop/test/Components';
```

#

