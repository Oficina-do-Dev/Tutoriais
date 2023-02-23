# O que é Salable Quantity ou Quantidade vendável?

**Importante:** para entender melhor o que é o salable quantity (quantidade vendável) é necessário que você entenda o processo de <a href="https://github.com/Oficina-do-Dev/Tutoriais/tree/main/Magento_2/003%20-%20Como%20cadastrar%20produto%20simples">cadastro do produto</a> e de <a href="https://github.com/Oficina-do-Dev/Tutoriais/tree/main/Magento_2/007%20-%20Como%20gerenciar%20pedidos%20via%20painel">gerenciamento de pedidos</a>, caso não conheça nenhum deles basta clicar nos links referentes.

A quantidade vendável surge no lançamento do Magento 2.3 junto com o sistema de inventário de múltiplas fontes. Ele permite que você gerencie todos os seus depósitos em um só lugar e evite estoques mortos e situações de falta de estoque.

**Quantidade vendável é a soma de todos os itens disponíveis deste produto agrupados em estoques.**

Ao contrário das versões anteriores do Magento 2, a quantidade de um produto não diminui quando o cliente faz um pedido. Em vez disso, a quantidade vendável é reduzida. Enquanto. a quantidade do produto diminui somente após o envio do produto, ou seja, finalizando o processo do pedido.

## Explicando detalhadamente:

Quando você cria um novo produto e insere a quantidade do estoque que você tem dele, dois tipos de quantidade será criada, a quantidade de estoque padrão e a quantidade vendável (salable quantity). Você irá reparar que os dois terão o mesmo valor mas os dois tem propósitos diferentes.

A quantidade vendável é quantidade do estoque que está disponível para venda, quando um cliente adiciona o produto no carrinho e faz o pedido, a quantidade do produto solicitada por ele será subtraida da quantidade vendável, desse modo evitando que clientes comprem produtos aos quais o estoque já acabou.

Quando você realizar a fatura e envio do produto, a quantidade que o cliente comprou então será subtraida do estoque real da loja.

## Entendendo na prática:

Criamos um produto com o nome de **Produto teste** e colocamos seu stock como 100, note que a **Quantidade** e o **Salable Quanity** tem o mesmo valor, pois como acabamos criar este produto a quantidade disponível para venda é igual a quantidade total do estoque.

![salable quantity](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/067%20-%20%20O%20que%20é%20Salable%20Quantity/images/image1.png)

**Atenção:** mais uma vez reforçamos que é necessário que você saiba o processo de cadastro de produtos, caso você não saiba ou não se lembre basta clicar <a href="https://github.com/Oficina-do-Dev/Tutoriais/tree/main/Magento_2/003%20-%20Como%20cadastrar%20produto%20simples">aqui</a>.

Agora que o produto ja foi cadastrado e esta disponivel para venda, o cliente da loja irá comprá-lo executando um processo normal de compra.

![salable quantity](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/067%20-%20%20O%20que%20é%20Salable%20Quantity/images/image2.png)

Quando o cliente finalizar o pedido da compra a quantidade de produto que ele comprou será subtraida do Salable Quantity (Quantidade vendável) primeiro para que quando você realizar a fatura e envio do produto a quantidade comprada pelo cliente seja subtraida do estoque real da loja.

![salable quantity](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/067%20-%20%20O%20que%20é%20Salable%20Quantity/images/image3.png)

Na imagem abaixo o pedido que o cliente fez já foi faturado e enviado e a quantidade comprada pelo cliente ja foi subtraida do estoque real da loja.

![salable quantity](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/067%20-%20%20O%20que%20é%20Salable%20Quantity/images/image4.png)

**Qual a vantagem disso?**

Um exemplo bem básico, imagine que você tenha apenas 10 unidades de um produto em seu estoque, o salable quantity evita que, nesse caso, mais de 10 pessoas comprem o produto assim evitando problemas de falta de estoque e dores de cabeça com ressarcimento. A cada pedido enviado por você (processo de <a href="https://github.com/Oficina-do-Dev/Tutoriais/tree/main/Magento_2/007%20-%20Como%20gerenciar%20pedidos%20via%20painel">gerenciamento de pedidos</a>) a quantidade do estoque será subtraida e sendo equalizada com a quantidade do salable quantity.

**Importante:** se acaso você ou o cliente cancelar o pedido, a quantidade do produto comprada por ele retornará ao estoque, assim possibilitando que outra pessoa compre o produto.

### Dúvidas/Suporte: 
Entre em contato com o nosso departamento de suporte.