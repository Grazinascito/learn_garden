
## Porque esse tema importa?
> Como desenvolvedora web, é importante saber como acontece o processo de renderização de uma página web.

> Além disso, a renderização é o processo de transformar o código(html, css e javascript) em uma página visual

> Existem várias formas de fazer isso, por isso precisamos saber quais são essas formas para então aplica-las

### Single Page Application
==Toda SPA utiliza a estratégia de Client-Side Rendering(CSR)==
#### o papel do client depois desse processo:
* O client utiliza uma única página html ->  faz a solicitação pro servidor ->  o servidor devolve a solicitação 
* depois o client solicita um arquivo javascript ->  o servidor devolve o arquivo javascript
* E o client é responsável por renderizar tudo isso no lado do client(broswer)
* Ler o arquivo javascript recebido
* Executar o arquivo JS
* E a partir disso, o javascript monta a página na tela do usuario

> ou seja, o client(browser) faz todo o processo de renderização

![](Screenshot%202024-07-25%20at%2019.17.45.png)

#### prós e contras do SPA:
* ✅**pró:** a partir do momento em que a página é carregada totalmente, a experiencia do usuário é mais fluída 
* ❌**contra:** esse primeiro carregamento, pode ser pesado e demorado
-----

