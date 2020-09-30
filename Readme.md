# Classes e Mixins
Alô, alô terrestre! Esse respositório foi feito para contribuir com o pessoal novato que não tem muita ideia de como fazer mixins para mobile first. Lembrando que a maior parte dos frameworks já fazem uso do mobile first e que melhores práticas, atualmente, incuem usar flexbox. Dito isso...
## Conteúdo do arquivo
No arquivo único nós temos partes com:
* **Breakpoints:** que são os tamanhos de cada tela de cada dispositivo
* **Media Queries dentro de mixins:** que usam as váriaveis de breakpoints
* **Classes CSS:** que também usam media queries menos exatas que as últimas para dizer se um dispositivo é "grande ou pequeno"

## Linguagem do Arquivo
O arquivo está em SASS e pode ser modificado para ser usado em SCSS, basta colocar adicionar {} e ; a onde eles estariam em um arquivo SCSS.

Não recomendo modificar esse projeto para usar CSS.

## Como usar
1. Insira o arquivo no local de preferência do seu projeto (pode ser usado com qualquer framework desde que devidamente configurado de acordo com a framework)
2. Para incluir em um arquivo use: ``` @import  classes_and_mixins.sass ``` 
3. Para incluir os mixins use: ``` @include nome_do_mixin ``` e dentro de { } insira os estilos desejados.