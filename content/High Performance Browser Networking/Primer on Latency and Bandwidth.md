- throughput => Taxa de transferencia
- buffer space => É um armazenamento temporario usado para carregar os dados enquanto isso ta sendo transferido. _O mecanismo que o youtube usa_
  - In video streaming, a buffer stores a portion of the video data ahead of what is currently being played. This helps to mitigate interruptions caused by network fluctuations and provides smooth playback.

https://hpbn.co/primer-on-web-performance/#anatomy-of-a-modern-web-application
https://www.iamtk.co/web-performance-roadmap

## Por que performance na web é importante?

- Um site rápido retem melhor o usário
- Um site rápido aumenta o engajamento do usuário
- Um site rápido resulta em conversão

### Latencia

> É o tempo em que leva para a fonte enviar um pacote para o destino que está recebendo isso

### Largura de banda(bandwidth)

> Tamanho da taxa de transferencia da comunicação

![](Screenshot%202024-07-31%20at%2023.11.11.png)

#### funfact

> Um CDN é responsavel por salvar copias de informações em vários servidores,. O objetivo de um CDN é melhorar performance

> O TCP é feito para lidar com a segurança e garantia de que o dado é transmitido corretamente

### Three-way handshake

É uma das comunicações que acontece entre o client e o server ANTES do pacote ser enviado.

### Flow Control

Existe um mecanismo para evitar que o client sobrecarregue as capacidades de quem ta recebendo os dados. _Mas isso não evita que outras partes do role sobrecarregue outras coisas_

#### funfact

> O TCP é feito para usar a perda de pacote como um mecanismo de feedback para escancarar que pode ocorrer uma congestão de pacotes em algum momento

> Ponto importante: É imprescindível melhorar o "congestion control" para evitar o congestionamento de pacotes.
