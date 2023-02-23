# Como gerenciar pedidos via painel Magento com status personalizado.

No cenário de possuir status (situação do pedido) personalizados você consegue alterar isso via painel Magento e enviar (caso quiser) a atualização para seu cliente.

1 -> Após o Cliente ter efetuado o pedido você consegue vê-lo em **VENDAS > PEDIDOS**.

![pedidos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/047%20-%20Como%20gerenciar%20pedidos%20via%20painel%20com%20status%20personalizado/images/image1-painel.png)

2 -> Aqui nesta tela você consegue ver todos os pedidos que foram efetuados em sua loja, os pedidos que ainda não foram pagos o status ou não foram confirmados devem ficar com o status de *Pendente* ou *Aguardando Pagamento*.

![pedidos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/047%20-%20Como%20gerenciar%20pedidos%20via%20painel%20com%20status%20personalizado/images/imagem2-pedidos.png)

3 -> Os pedidos que estão pagos e aguardam sua atualização vão estar com o status *Processando* ou *Em processamento*.

*ATENÇÃO:* As etapas abaixo devem ser utilizadas para pedidos que já se encontram com o status *Processando* ou *Em processamento*, caso você altere de um pedido com o status *Pendente* ou *Aguardando Pagamento* pode gerar transtorno com os pedidos e/ou com seus clientes.

4 -> Para efetuar uma atualização do status do pedido, você deve realizar o faturamento do mesmo, para isso, acesse o pedido clicando sobre a opção Visualizar localizado no canto direito da grid de pedidos.

![visualizar](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/047%20-%20Como%20gerenciar%20pedidos%20via%20painel%20com%20status%20personalizado/images/imagem3-visualizar.png) 

5 -> Na tela do pedido, desça o curso do mouse para a àrea inferior da tela você perceberá que para a situação do pedido atual só dispõe da opção, isto ocorre pois seu pedido ainda não foi faturado.

![status](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/047%20-%20Como%20gerenciar%20pedidos%20via%20painel%20com%20status%20personalizado/images/imagem3-status.png) 

6 -> Para faturar o pedido, na guia superior existe a opção Fatura, clique sobre a mesma,

![fatura](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/047%20-%20Como%20gerenciar%20pedidos%20via%20painel%20com%20status%20personalizado/images/imagem4-fatura.png) 


7 -> Você será direcionado para a tela de fatura de pedido, confira as informações do pedido e produtos, pois após esta etapa o processo de cancelamento ficará complexo.

![fatura](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/047%20-%20Como%20gerenciar%20pedidos%20via%20painel%20com%20status%20personalizado/images/imagem5-dadosfatura.png) 

8 -> Após a conferência, desça para a parte inferior da página e clique na opção *Enviar fatura*, 

![e-mail fatura](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/047%20-%20Como%20gerenciar%20pedidos%20via%20painel%20com%20status%20personalizado/images/imagem6-emailfatura.png) 


*ATENÇÃO:* Caso achar conveniente você pode enviar a cópia do e-mail de fatura para o cliente, caso deseje enviar a cópia do e-mail para o cliente marque a checkbox *Cópia do e-mail de fatura* antes de clicar em *Enviar fatura*


9 -> Você receberá o retorno que a fatura foi criada no topo da página

![fatura criada](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/047%20-%20Como%20gerenciar%20pedidos%20via%20painel%20com%20status%20personalizado/images/imagem7-faturacriada.png) 

10 -> Agora se você descer novamente para a região que exibe sobre a situação, você notará que possui outros status para serem utilizados. 

![novos status](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/047%20-%20Como%20gerenciar%20pedidos%20via%20painel%20com%20status%20personalizado/images/imagem8-novosstatus.png) 

11 -> Seguindo com a documentação, iremos alterar para o status *Pagamento Confirmado* na região exibida no tópico anterior, selecione o status *Pagamento Confirmado*, selecione a checkbox *Notificar o cliente por e-mail* e a checkbox *Visível na loja*

![pagamento confirmado - pedido](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/047%20-%20Como%20gerenciar%20pedidos%20via%20painel%20com%20status%20personalizado/images/imagem9-pagamentoconfirmado.png) 

12 -> Caso você visualizar a grid de pedidos, notará que o pedido em questão consta com o status *Pagamento Confirmado*, conforme efetuado no tópico anterior.

![pagamento confirmado](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/047%20-%20Como%20gerenciar%20pedidos%20via%20painel%20com%20status%20personalizado/images/imagem10-pagamentoconfirmadogrid.png) 

13 -> Você pode efetuar as alterações dos status como achar conveniente, notificando ou não o cliente via e-mail.


14 -> Foi finalizado o processo de preparo da encomenda e resta enviar. Você precisa realizar o envio através do Magento para que o cliente receba a informação do rastreio, para isso, na tela do pedido, no canto superior direito clique na opção *Enviar*.

![enviar](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/047%20-%20Como%20gerenciar%20pedidos%20via%20painel%20com%20status%20personalizado/images/imagem11-enviar.png) 

15 -> Você será redirecionado para a tela de envio, desça a tela até a região de Dados de Entrega, clique sobre a opção *Adicionar o número de rastreamento*

![rastreamento](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/047%20-%20Como%20gerenciar%20pedidos%20via%20painel%20com%20status%20personalizado/images/imagem12-rastreamento.png) 

16 -> Na coluna transportadora selecione a transportadora no seletor, caso não possuir mantenha como *Valor personalizado*, mantendo como Valor personalizado você deve inserir o nome da transportadora na coluna *Título*, na coluna *Número* informe o número de rastreio.

*Atenção:* Cada transportadora possui um padrão para rastreio, geralmente utilizam o número da NF-e, por segurança confira o exemplo de cada transportadora que você possui contrato.


![dados rastreio](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/047%20-%20Como%20gerenciar%20pedidos%20via%20painel%20com%20status%20personalizado/images/imagem12-rastreamento.png) 

17 -> Caso possua mais de um rastreio para o mesmo pedido, você pode repetir o processo informado acima.

18 -> Após ter inserido a informação de transportadora e rastreio, desça para o final da página, selecione a checkbox *Enviar por e-mail cópia do envio* e clique em *Enviar comentário*.

![enviar rastreio](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/047%20-%20Como%20gerenciar%20pedidos%20via%20painel%20com%20status%20personalizado/images/imagem13-inforastreamento.png) 

19 -> Caso deseje incluir alguma informação sobre o pedido, que não possua anteriormente, você pode informar no campo *Texto do comentário* antes de clicar em *Enviar comentário*, porém para que a informação seja enviado junto ao rastreio deve-se preencher a checkbox *Acrescentar comentários*

![enviar rastreio](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/047%20-%20Como%20gerenciar%20pedidos%20via%20painel%20com%20status%20personalizado/images/imagem14-comentariorastreamento.png) 

20 -> Note que o status do pedido em questão irá mudar para *Completo* ou *Enviado*, você poderá ver esta informação na grid de pedidos.

![enviar rastreio](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/047%20-%20Como%20gerenciar%20pedidos%20via%20painel%20com%20status%20personalizado/images/imagem15-griddepedidosenviados.png) 


21 -> Seguindo estas etapas o processo estará finalizado e seu pedido encerrado.

<hr>

### Dúvidas/Suporte
Entre em contato com o nosso departamento de suporte.