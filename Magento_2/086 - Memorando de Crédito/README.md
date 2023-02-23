# Memorando de Crédito (devolver valor para cliente)

No Magento, quando  algo dá errado em um dos pedidos em nossa loja, pode ser necessário ressarcir nosso cliente reembolsando o valor pago. A plataforma oferece diferentes formas de se fazer isso e alguns conceitos são importantes de serem entendidos antes de criar o seu primeiro reembolso.

**1º - Reembolso Online**

O reembolso online é aquele onde uma comunicação de reembolso é realizada com o meio de pagamento (PagSeguro, PayPal, Cielo, etc) usado pelo cliente que realizou a compra.

Nesses cenários o valor da compra é devolvido ao cliente geralmente usando o mesmo meio de pagamento usado no processo de compra. Ou seja, se o pedido foi feito usando cartão de crédito, o valor tende a ser devolvido para o mesmo cartão usado na compra.

***Peculiaridades***

A forma como o reembolso online ocorre dependerá do meio de pagamento e do módulo de pagamento utilizado. O correto funcionamento deste tipo de reembolso também está diretamente ligado à esta integração.

Alguns meios de pagamento permitem que pagamentos feitos com Boleto bancário também sejam reembolsados. Nestes casos o meio de pagamento pode oferecer ao cliente que o valor seja devolvido em uma conta corrente especificado por ele, ou creditado em sua “carteira virtual” (quando disponível).

Por fim, o Magento permite que façamos reembolsos totais ou parciais de um pedido. Com isso, podemos especificar quantos itens serão reembolsados, se queremos reembolsar o valor do frete, ou mesmo cobrar alguma taxa de reembolso. No entanto, nem todos os serviços de pagamento permitem um reembolso parcial.

***Pré-requisitos***

Embora praticamente todos os gateways e facilitadores possuam recursos e APIs de reembolso, o módulo que faz esta integração também precisa suportar o reembolso.

**2º - Reembolso Offline**

O reembolso offline como você deve imaginar é exatamente o oposto. Ou seja, nele não há comunicação com o gateway de pagamento.

Este modelo é ideal para os casos onde uma outra forma de reembolso foi acordada com o cliente. Por exemplo o depósito do valor em conta corrente, ou mesmo com um cupom de desconto ou criação de um novo pedido.

***Pré-requisitos***

O reembolso offline pode ser aplicado em faturas cujo valor é maior que zero, ou a qualquer pedido como um todo.

### Mão na massa...

Estando ciente das duas formas, seguiremos com a instrução de como criar um **Reembolso Offline** no Magento.

1 -> Acesse o **PAINEL MAGENTO > VENDAS > PEDIDOS >** *selecionar o pedido*

2 -> Nesta tela, clique em **Faturas** no menu horizontal clique em **Memorando de Crédito** 

![filtrar cliente](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/086%20-%20Memorando%20de%20Cr%C3%A9dito/images/image-1.png)


Na tela de reembolso é possível especificar quantos produtos deseja reembolsar e se o *Magento* deve devolvê-los ao estoque. Também é possível especificar o valor do frete a ser reembolsado e fazer reajustes (como taxas de devolução - caso houver). 
    
Somente valores positivos são permitidos nestes campos, nunca superando o valor total pago na fatura.   


![filtrar cliente](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/086%20-%20Memorando%20de%20Cr%C3%A9dito/images/image-2.png)

3 -> Por fim podemos optar por enviar a cópia do reembolso (caso queira) junto com os comentários para o cliente e realizar um reembolso offline ou online, respectivamente.

4 -> **ATENÇÃO:** Reembolso serve para opções onde o método de pagamento oferece esta possibilidade.

![filtrar cliente](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/086%20-%20Memorando%20de%20Cr%C3%A9dito/images/image-3.png)


Na grid de pedidos você verá como **Fechado** a situação do pedido. (conforme tradução padrão)

5 -> Na visualização dos pedidos do cliente ele também irá ver o pedido como reembolso (a depender do layout do seu tema)

![filtrar cliente](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/086%20-%20Memorando%20de%20Cr%C3%A9dito/images/image-4.png)

**ATENÇÃO** Caso seu método de pagamento ofereça a opção de reembolso é sempre recomendável que utilize esta opção para que haja a correta comunicação entre cliente e método de pagamento.

### Dúvidas/Suporte:

Entre em contato com o nosso departamento de suporte.