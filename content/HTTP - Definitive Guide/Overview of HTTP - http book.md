### URL
> As urls comunica onde um conteúdo está e como acessar.

### Transactions
* HTTP transaction consiste em um comando request(enviar do client pro server) e a resposta que o server mandar


> [!NOTE] Fact
 ==Web Pages Can Consist of Multiple Objects==

### HTTP Messages
* o que precisamos saber sobre http messages é como é estruturado o corpo:
![](Screenshot%202024-07-30%20at%2016.37.32.png)

### Connections - TCP
> a Transmission Control Protocol é o responsável por transportar a HTTP Messages de um local para o outro


[Draw notes]([[obsidian://open?vault=Obsidian%20Vault&file=Excalidraw%2FHTTP%20book%2016.24.01.excalidraw]])


### HTTP Layers(camadas)
![](Screenshot%202024-07-30%20at%2017.15.48.png)

### Connections, IP Addresses, and Port Numbers

> Antes do HTTP Client enviar uma mensagem para o servidor, ele estabelece uma conexão TCP/IP entre client e servidor utilizando o endereço Internet protocol(IP) e o numero da porta

### Como pegamos o endereço ip e o numero da porta?
> através da URL. ex: http://207.200.83.29:80/index.html

hostname -> uma forma mais legivel desses numeros

> [!NOTE] Fact
 ==When the port number is missing from an HTTP URL, you can assume the default value of port 80==


### Resumo:
![](Screenshot%202024-07-30%20at%2018.04.04.png)
ps: http é na porta 80. https é na porta 443
