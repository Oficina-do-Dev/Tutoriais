# Como o CDN pode ajudar meu site ?

## Para entender melhor, o que é o CDN ? 

CDN ou **Content Delivery Network** que em uma tradução literal fica **Rede de Distribuição de Conteúdo** é um grupo de servidores que permitem que os conteúdos da internet estejam fácilmente disponíveis, com rapidez e segurança. Em outras palavras o objetivo do CDN é tornar a experiência do usuário e a navegabilidade mais otimizada.

Alguns serviços conhecidos de CDN são:

    CloudFlare
    Akamai
    Incapsula
    MaxCDN
    GoCache

## Como o conteúdo é entregue?

Antes de compreendermos melhor como ele funciona, precisamos saber como o conteúdo é entregue para o usuário. Em resumo, conteúdo é qualquer tipo de elemento textual, visual ou auditivo de um site. É um bloco de texto, uma imagem, arquivos de áudio, vídeos, entre outros...

Desta forma, existem dois tipos de conteúdos, sendo eles:

**ESTÁTICO**: É todo aquele conteúdo que em sua versão original (a de entrada) é o que as pessoas realmente veem na página publicada (resultado), em resumo, ele permanece o mesmo e não é modificado.

O servidor dá o mesmo tipo de dado a cada usuário, por conta disso, a entrega do conteúdo é bem mais rápida. O processo é simples: um usuário faz um pedido ao servidor de internet para acessar um arquivo e, na mesma hora, o servidor entrega o arquivo solicitado.

**DINÂMICO**: Este por sua vez se diferencia um pouco, pois diferente do estático ele se modifica baseado na sua versão original (a de entrada). Ele é personalizado para várias páginas, dependendo das solicitações de cada usuário.

Um exemplo de conteúdo dinámico é uma página de um produto: ela geralmente contém o nome do produto, uma descrição, um preço e inclui imagens.

## Como o CDN funciona?

Basicamente, o CDN reproduz o conteúdo que está armazenado no servidor central. A versão reproduzida do conteúdo vai, então, ser salva em locais de várias regiões do planeta, chamados de Pontos de Presença (PoP, do inglês). Esses *Pontos* são os locais em que mais de duas redes fazem a conexão consigo mesmas.

Sem o CDN, quando um usuário tenta acessar um site, o computador envia um pedido de acesso ao servidor central para o conteúdo. O servidor central, então, responde ao pedido e mostra o conteúdo ao usuário.

Esse processo leva algum tempo para ser concluído. A distância entre o usuário e o servidor é que determina a velocidade do processo. Com o CDN, o negócio é diferente. Em vez de levar o pedido até o servidor central, os visitantes de um site recebem uma cópia dos dados (conteúdos já armazenados) do servidor de internet mais próximo.

A entrega do conteúdo, neste caso, é bem mais rápida e usa um sistema de mapeamento que avalia a localização do usuário e do servidor. Se em alguma ocasião o servidor mais próximo não conseguir entregar o conteúdo ao usuário, ele vai procurar por outros servidores em um ambiente de CDN.

Caso os dados não existem ou não tiverem sido armazenados, o servidor vai contactar o servidor central para fornecer tal conteúdo. E, então, vai armazená-lo para atender aos pedidos futuros.


![Como funciona o CDN](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/099%20-%20Como%20o%20CDN%20pode%20ajudar%20meu%20site/images/image1.PNG)

## Benefícios de usar CDN

Por que você precisa de uma CDN? Existem 4 razões bem fundamentadas da importância de usar algum serviço de CDN. São elas: **Velocidade**, **Disponibilidade**, **Custo** e **Segurança**. 


**Velocidade**

Cada segundo conta. Se um usuário de internet tenta acessar seu site e levar mais de 3 segundos para ver o conteúdo dela, é provável que ele desista do seu site.

Normalmente, o servidor de hospedagem do seu site é que faz o trabalho de gerenciar os dados e o tráfego de uma página. .

Mas, quando a quantidade de acessos sobe muito e você tem apenas um servidor para administrar tudo, uma resposta bem lenta é inevitável.

É aqui onde o CDN entra. Ele ajuda a responder as solicitações de acesso a uma página com muito mais velocidade. Como isso? Driblando a latência (o atraso entre o momento do pedido e a resposta) de conexões.

Alguns fatores podem causar esse atraso, mas é mais influenciado pela distância entre os visitantes e o servidor de hospedagem de um site.

![Como funciona o CDN](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/099%20-%20Como%20o%20CDN%20pode%20ajudar%20meu%20site/images/image2.PNG)

**Disponibilidade**

A quantidade de usuários de internet está crescendo rapidamente. Se você já pensava que fornecer conteúdos de qualidade poderia fazer explodir suas conversões, você está absolutamente certo.

Mas, para isso, você precisa se certificar que esses mesmos conteúdos estejam disponíveis em todas as ocasiões. Nesse caso, usar o CDN é uma ótima opção.

Imagine se seu site não funcionar corretamente quando o tráfego aumentar. Isso não apenas vai diminuir a credibilidade dele. Mas, também, será uma grande perda de oportunidade para mais conversões. O CDN foi feito para lidar com essas situações.

**Custo-benefício**

Quem é que não quer ter mais resultados gastando menos? Com o CDN, você pode ter um projeto com um melhor custo-benefício. Quando menos dados são necessários de um servidor de origem, os custos de hospedagem podem ser ajustados de acordo com a demanda.

Isso significa que você não precisa pagar altas quantias de dinheiro para ter um serviço eficiente e que você mesmo pode otimizar. Outra coisa boa é que você não precisa criar uma infraestrutura. A empresa de CDN é que cuida disso para você.   

**Segurança**

A segurança do seu site e dos dados dele devem ser a sua prioridade número um. Tanto na sua perspectiva quanto na dos seus usuários.

Mas, na maioria das vezes, você não precisa realmente saber como se proteger de todos os ataques maliciosos. O fato é que um ataque hacker acontece a cada 39 segundos e 95% das brechas em segurança digital são causadas por falha humana.

Além disso, acredito que você saiba o quão destrutivo um ataque DDoS pode ser. É uma tentativa maliciosa de perturbar um servidor ou uma rede com uma avalanche de pedidos e tráfego desorientado.

Como resultado, seu site cai e não pode ser acessado por ninguém. Qualquer negócio que você tiver na internet corre risco se algo desse tipo acontecer. Seus consumidores podem, também não querer mais acessar seu site e procurarem opções mais seguras.

Ainda, se você já implementou algum serviço de CDN, é ele quem vai gerenciar todo o tráfego recebido pelo site, garantindo que este esteja sempre funcionando. A rede estará lá para ajudar você a bloquear um ataque malicioso antes que ele atinja seu data center ou servidor.  




Você pode ler mais sobre CDN  [Aqui](https://www.cloudflare.com/pt-br/learning/cdn/what-is-a-cdn/)

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.