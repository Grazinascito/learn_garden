### Static Site Generation - SSG
![](Screenshot%202024-07-28%20at%2020.34.16.png)


##### O SSG acontece em 4 fases:
>obs: renderiza a página no build da aplicação, e não com alguma interação do usuário na página

1. Se cria arquivos html estáticos na aplicação
2. Ao gerar uma build, enviamos esses html para o servidor
3. O client(browser) solicita um dos arquivos html
4. O servidor devolve o arquivo html

##### A primeira página do MLD poderia ser estática?
* o catálogo precisa do dinamismo para mudar as páginas
	* o usuário clica na seta -> o site re-renderiza com a informação da outra página do catálogo


#### Funfact:
 > É possível fazer páginas estáticas com o Next.js
 
 
 **Sem dados no primeiro render da página estática:**
	 ![](Pasted%20image%2020240728211600.png)
 **Com dados no primeiro render da página estática** 
 ![](Pasted%20image%2020240728211720.png)