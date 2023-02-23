# Regra de carrinho, compre X Ganhe Y.

A promoção "Compre X Ganhe Y" permite oferecer um produto grátis para o cliente que comprar uma quantidade determinada de um produto específico. Neste tutorial, vamos utilizar como exemplo "Compre 2 Ganhe 1". 




1 -> Primeiramente faça login no painel do Magento e acesse **MARKETING > REGRAS DE PREÇO DE CARRINHO > ADICIONAR NOVA REGRA**.

![criar regra](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/089%20-%20Compre%20X%20e%20ganhe%20Y%20-%20Regra/images/1-adicionar.png)

2 -> Na aba **Informações da Regra** você deve inserir as informações básicas, não esquecendo de selecionar o site e quais grupos de clientes podem utilizar a regra

**ATENÇÃO: ** você pode criar esta regra com ou sem cupom, fica a seu critério.

![informações da regra](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/089%20-%20Compre%20X%20e%20ganhe%20Y%20-%20Regra/images/2-informacoes.png)

3 -> Agora na aba condições, você deve buscar a listagem a opção **Combinação de atributos do produto** e deixá-lo da seguinte forma:

![condicoes](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/089%20-%20Compre%20X%20e%20ganhe%20Y%20-%20Regra/images/3-condicoes.png)

4 -> Nos itens da listagem, você deve selecionar o atributo SKU, você pode usar outro limitador, porém para ser mais assertivo utilizaremos o SKU.

**ATENÇÃO:** Caso o SKU não apareça como condição entre em contato com o desenvolvedor.

5 -> Posteriormente selecione/insira a SKU do produto que você deseja utilizar de parametro

![sku](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/089%20-%20Compre%20X%20e%20ganhe%20Y%20-%20Regra/images/4-sku.png)

6 -> No grupo **Ações** você deve informar os parametros, em nosso caso quando o cliente comprar 2 itens, 1 deles será bonificado.

![grupo de ações](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/089%20-%20Compre%20X%20e%20ganhe%20Y%20-%20Regra/images/5-qtdedesconto.png)

7 -> **Aplicar ao Valor da Entrega** e **Descartar as regras subsequentes** fica a seu critério

8 -> Logo abaixo, no campo Frete grátis, você deve selecionar se é aplicado ou não o frete grátis, em nosso exemplo deixaremos **Não**

![frete gratis](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/089%20-%20Compre%20X%20e%20ganhe%20Y%20-%20Regra/images/6-fretegratis.png)

9 -> Por questões de organização, recomenda-se que você insira uma etiqueta, conforme segue:

![etiqueta](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/089%20-%20Compre%20X%20e%20ganhe%20Y%20-%20Regra/images/7-etiqueta.png)

10 -> Feito isso, pressione GRAVAR, localizado no canto superior direito.

**ATENÇÃO:** Caso seu indice esteja configurado para executar por agenda, o resultado irá aparecer após a próxima execução, neste caso o aconselhável é aguardar.

11 -> O resultado esperado é:

![resultado 1](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/089%20-%20Compre%20X%20e%20ganhe%20Y%20-%20Regra/images/8-resultado.png)

A cada soma de 2 itens, 1 será gratuito, conforme exemplo:

![resultado 2](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/089%20-%20Compre%20X%20e%20ganhe%20Y%20-%20Regra/images/9-resultadomultiplos.png)

12 -> Caso você queira limitar o máximo de itens que recebe essa bonificação, você deve voltar na configuração da regra e no campo **Desconto Máximo Quantidade é Aplicado Para** e insira o limitador, veja abaixo no nosso exemplo:

![limitador](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/089%20-%20Compre%20X%20e%20ganhe%20Y%20-%20Regra/images/10-limitador.png)

13 -> Resultado esperado é:

![limitador sucesso](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/089%20-%20Compre%20X%20e%20ganhe%20Y%20-%20Regra/images/11-limitadorsucesso.png)

Note que o desconto foi aplicado, porem diferente da exibição acima, tendo 4 unidades era aplicado a bonificação e agora não mais.

<hr>

### Dúvidas/Suporte:

Entre em contato com o nosso departamento de suporte.