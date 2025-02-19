# 109 - Como criar uma regra de cupom com geração automática

Esse tutorial vai lhe instruir em etapas como criar uma regra de carrinho com cupom de geração automática que concede desconto em %.

1 -> No painel navegue até o menu: **MARKETING > PROMOÇÕES > Regras de preço do carrinho** 

![Localização](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/109%20-%20Como%20criar%20uma%20regra%20de%20cupom%20com%20geracao%20automatica/images/image1.png)   

2 -> Nesta tela clique na opção **Adicionar Nova Regra** localizado no canto superior direito

![Adicionar](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/109%20-%20Como%20criar%20uma%20regra%20de%20cupom%20com%20geracao%20automatica/images/image2.png)   

3 -> Na tela que você será direcionado inicialmente você precisa inserir as seguintes informações:

    Nome da regra   -> Para facilitar sua organização
    Descrição       -> Para servir de apoio na interpretação da regra
    Ativo           -> Caso SIM a regra poderá ser utilizada, caso NÃO a regra não poderá ser utilizada
    Sites           -> Neste você deve selecionar em quais sites a regra deve selecionar *
    Grupos de Cli.  -> Neste você pode selecionar quais grupos de cliente a sua regra deve atender, caso você não faça distinção de cliente por grupo, selecione todos. * 
    
    
    * (mantenha pressionado a tecla CTRL caso seja mais de um)

![Opcoes](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/109%20-%20Como%20criar%20uma%20regra%20de%20cupom%20com%20geracao%20automatica/images/image3.png) 

4 -> Veja abaixo como ficou em nosso exemplo:

![Configuração](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/109%20-%20Como%20criar%20uma%20regra%20de%20cupom%20com%20geracao%20automatica/images/image4.png)    

5 -> Dando continuidade, mais abaixo existe uma opção importante, sendo ela a **Cupom**, selecione a opção **Cupom específico** e marque a opçào **Usar Geração Automática**

![Cupom Especifico + Geração](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/109%20-%20Como%20criar%20uma%20regra%20de%20cupom%20com%20geracao%20automatica/images/image6.png)

6 -> Você vai notar que o campo Código do cupom vai ficar cinza, pois você precisará gerar o cupom em cada uso.

![Cupom Especifico + Geração](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/109%20-%20Como%20criar%20uma%20regra%20de%20cupom%20com%20geracao%20automatica/images/image7.png)

7 -> Abaixo você deve informar os valores dos campos **Usos por Cupom** e **Usos por cliente** o primeiro tem relação de quantas vezes aquele cupom pode ser usado, ignore caso não houver um limite, o segundo tem relação em quantas vezes cada cliente pode utilizar aquele cupom especifico.

![Usos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/109%20-%20Como%20criar%20uma%20regra%20de%20cupom%20com%20geracao%20automatica/images/image8.png)

**OBS:** em nosso exemplo cada cupom poderá ser utilizado uma única vez.

8 -> Mais abaixo existe o periodo a qual o cupom será válido e o campo **Prioridade** o qual 0 é mais alto, a prioridade serve para caso houver mais de um cupom ele vai priorizar sempre o mais alto

![Periodo e Prioridade](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/109%20-%20Como%20criar%20uma%20regra%20de%20cupom%20com%20geracao%20automatica/images/image9.png)

9 -> Abaixo começamos na sessão de **Condições** o qual você pode determinar qual será a condição para que aquele cupom seja válido por exemplo:

- Forma de pagamento
- Sub-total
- Método de entrega
- Código Postal (CEP)
- Região de Entrega
entre outros...

![Condicao](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/109%20-%20Como%20criar%20uma%20regra%20de%20cupom%20com%20geracao%20automatica/images/image10.png)

Você pode fazer uma combinação de condições, ou seja, se duas condições forem verdadeiras permitir utilizar o cupom ou qualquer de uma das condições forem verdadeiras. Lembre-se condição é opcional.

10 -> Abaixo das condições, temos as **Ações** que servem para indicar o que aquele cupom irá fazer, basicamente você deve expor para que aquela regra serve, como gerar um desconto especifico em % ou valor fixo por exemplo.

![Acao](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/109%20-%20Como%20criar%20uma%20regra%20de%20cupom%20com%20geracao%20automatica/images/image11.png)

11 -> Em nosso exemplo vamos conceder 5% de desconto (sem condição), conforme print abaixo:

![Acao - Exemplo](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/109%20-%20Como%20criar%20uma%20regra%20de%20cupom%20com%20geracao%20automatica/images/image12.png)

12 -> Abaixo temos a sessão **Etiquetas** que serve basicamente para identificar qual cupom o cliente inseriu em seu pedido, você pode ter uma etiqueta especifica para cada visão de loja ou se preferir utilizar a mesma, em nosso exemplo vamos usar a mesma, conforme print abaixo:

![Acao - Exemplo](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/109%20-%20Como%20criar%20uma%20regra%20de%20cupom%20com%20geracao%20automatica/images/image13.png)

13 -> Feito isso você deve clicar na opção **Salvar e Continuar Editando** localizada no canto superior direito, isso antes de darmos continuidade na criação de ao menos um código.

![Acao - Exemplo](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/109%20-%20Como%20criar%20uma%20regra%20de%20cupom%20com%20geracao%20automatica/images/image5.png)


## GERAR O CUPOM


14 -> Agora na parte inferior existe a opção **Gerenciar Códigos de Cupom**, esta área é responsável por gerar os códigos de Cupom vinculado a esta regra, podendo alterar o tamanho do código caso necessário, conforme print abaixo:

![Gerenciar cupom](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/109%20-%20Como%20criar%20uma%20regra%20de%20cupom%20com%20geracao%20automatica/images/image14.png)

15 -> Em nosso exemplo, vamos gerar apenas um código, clicando no botão **Gerar**

![Gerar cupom](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/109%20-%20Como%20criar%20uma%20regra%20de%20cupom%20com%20geracao%20automatica/images/image15.png)

16 -> A criação do código será processada pelo CRON, em seguida será disponibilizada nesta mesma area, caso não apareça logo que você criar, atualize a página.

17 -> Após gerar o código será criado algo como o print abaixo:

![Cupom gerado](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/109%20-%20Como%20criar%20uma%20regra%20de%20cupom%20com%20geracao%20automatica/images/image16.png)

**OBS:** Você deve informar este código para o cliente que recebeu o desconto e sempre que necessário você pode acessar a página desta regra e gerar novos cupons.

18 -> Conforme você for gerando os cupons eles vão constar como utilizados, conforme print abaixo:

![Cupom gerado](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/109%20-%20Como%20criar%20uma%20regra%20de%20cupom%20com%20geracao%20automatica/images/image17.png)


19 -> Feito isso você deve clicar na opção **SALVAR** localizada no canto superior direito e/ou **Salvar e Continuar Editando** caso você queira fazer outras customizações na regra ou criar novos códigos (exemplo).


**ATENÇÃO:** Tenha cuidado ao criar as regras para evitar problemas de lucratividade, atente-se as condições e quantidades de uso do cupom.

<hr>

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.