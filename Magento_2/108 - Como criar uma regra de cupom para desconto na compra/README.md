# 108 - Como criar uma regra de cupom para desconto na compra

Esse tutorial vai lhe instruir em etapas como criar uma regra de carrinho e possuir um cupom especifico para enviar ao seu cliente durante a finalização da compra e garantir com isso um desconto (podendo ser em % ou em valor fixo).

1 -> No painel navegue até o menu: **MARKETING > PROMOÇÕES > Regras de preço do carrinho** 

![Localização](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image1.png)   

2 -> Nesta tela clique na opção **Adicionar Nova Regra** localizado no canto superior direito

![Adicionar](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image2.png)   

3 -> Na tela que você será direcionado inicialmente você precisa inserir as seguintes informações:

    Nome da regra   -> Para facilitar sua organização
    Descrição       -> Para servir de apoio na interpretação da regra
    Ativo           -> Caso SIM a regra poderá ser utilizada, caso NÃO a regra não poderá ser utilizada
    Sites           -> Neste você deve selecionar em quais sites a regra deve selecionar *
    Grupos de Cli.  -> Neste você pode selecionar quais grupos de cliente a sua regra deve atender, caso você não faça distinção de cliente por grupo, selecione todos. * 
    
    
    * (mantenha pressionado a tecla CTRL caso seja mais de um)

![Opcoes](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image3.png) 

4 -> Veja abaixo como ficou em nosso exemplo:

![Configuração](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image4.png)    

5 -> Dando continuidade, mais abaixo existe uma opção importante, sendo ela a **Cupom**, abaixo a explicação das possibilidades:

- Sem cupom         -> o cliente mediante a condições especificas (exemplo) irá adquirir o desconto automaticamente

![Sem Cupom](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image5.png)  

- Cupom específico  -> o cliente precisará informar um cupom especifico durante a finalização da compra

![Cupom Especifico](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image6.png)

- Cupom especifico com geração automática -> similar ao anterior, porém neste você pode gerar diversos códigos, por exemplo cada um será enviado a um cliente especifico.

![Cupom Especifico + Geração](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image7.png)

6 -> Caso você selecione **Cupom específico** irá aparecer uma opção logo abaixo, sendo ela a **Usos por Cupom** e **Usos por cliente** o primeiro tem relação de quantas vezes aquele cupom pode ser usado, ignore caso não houver um limite, o segundo tem relação em quantas vezes cada cliente pode utilizar aquele cupom especifico.

![Usos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image8.png)

7 -> Mais abaixo existe o periodo a qual o cupom será válido e o campo **Prioridade** o qual 0 é mais alto, a prioridade serve para caso houver mais de um cupom ele vai priorizar sempre o mais alto

![Periodo e Prioridade](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image9.png)

8 -> Abaixo começamos na sessão de **Condições** o qual você pode determinar qual será a condição para que aquele cupom seja válido por exemplo:

- Forma de pagamento
- Sub-total
- Método de entrega
- Código Postal (CEP)
- Região de Entrega
entre outros...

![Condicao](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image10.png)

Você pode fazer uma combinação de condições, ou seja, se duas condições forem verdadeiras permitir utilizar o cupom ou qualquer de uma das condições forem verdadeiras. Lembre-se condição é opcional.

9 -> Abaixo das condições, temos as **Ações** que servem para indicar o que aquele cupom irá fazer, basicamente você deve expor para que aquela regra serve, como gerar um desconto especifico em % ou valor fixo por exemplo.

![Acao](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image11.png)

10 -> Em nosso exemplo vamos conceder 5% de desconto (sem condição) porém na ação também temos um segundo validador que em nosso exemplo vamos condicionar que o cliente só irá possuir o desconto se o valor do carrinho dele for maior ou igual a 100 e também não iremos conceder frete grátis, conforme print abaixo:

![Acao - Exemplo](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image12.png)

11 - Abaixo temos a sessão **Etiquetas** que serve basicamente para identificar qual cupom o cliente inseriu em seu pedido, você pode ter uma etiqueta especifica para cada visão de loja ou se preferir utilizar a mesma, em nosso exemplo vamos usar a mesma, conforme print abaixo:

![Acao - Exemplo](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image13.png)

12 - Feito isso você deve clicar na opção **SALVAR** localizada no canto superior direito e/ou **Salvar e Continuar Editando** caso você queira fazer outras customizações na regra.

**OBS:** Após salvar a regra ela se torna disponível para ser usada imediatamente, tenha cuidado em criar regras sem cupom pois você pode afetar sua lucratividade e/ou a usabilidade para todos os clientes a depender da condição a ser determinada na configuração da regra.

<hr>

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.