- 1 PASSO - INSTALANDO TypeScript

Codigo : npm install typescript --save-dev
Codigo : npm install -g typescript (instalar no projeto todo)<br/>
    --Codigo para instalar o arquivo de configuração do typeScript
      --tsc --init

- 2 PASSO - INSTALANDO OS TIPOS DE CADA BIBLIOTECA PARA O TYPESCRIPT ENTENDER

Codigo : npm add --save-dev @types/node

obs:Por Que devo instalar essa dependencia? 
res:O TYPESCRIPT por padrao so entende codigo do javaScript puro
com isso estou passando os tipos da biblioteca (usada) para o typescript poder entender os codigos dessa biblioteca
