# Como criar cupom desconto para frete grátis no Magento 1

## Requitos:

* Acesso ao painel Magento;

## Como criar:

No exemplo abaixo iremos criar uma regra que concede frete grátis para os produtos da loja, acima de R$ 199,00, excluindo uma categoria em questão sem a utilização de código de cupom e pode ser usado diversas vezes pelo mesmo cliente.

1 -> Acesse o painel Magento;

![Tela de criação](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/15%20-%20Cupom%20desconto%20para%20frete%20gr%C3%A1tis/images/1-regraspromocao.png)	

2 -> Nesta tela clique em **Criar Regra** localizado no canto superior direito;

![Criar regra](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/15%20-%20Cupom%20desconto%20para%20frete%20gr%C3%A1tis/images/2-criarregra.png)	 

3 -> Na tela que se abrir, aba **Informações da Regra** insira as informações nos campos:

```

 Nome da regra
 Status (selecionar ativo para que a regra funcione)
 Grupo de clientes (selecione quais grupos vão poder usufruir da regra)
 Cupom (neste você pode selecionar cupom especifico ou deixar sua regra sem cupom)
 Usos por Cupom (quantas vezes ele será utilizado, deixe em branco para ilimitado)
 Usos por Cliente (quantas vezes o mesmo cliente poderá utilizar o cupom)
 Da Data (data inicial para o cupom tornar-se válido)
 Para Data (data final para o cupom funcionar)
 Prioridade (sendo 0 de maior prioridade)
 Publicar no Feed RSS (Caso você utilize alguma plataforma de RSS, deixe marcado como SIM)

```


![Campos necessários](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/15%20-%20Cupom%20desconto%20para%20frete%20gr%C3%A1tis/images/3-camposinfo.png)

4 -> Navegue até a opção **Condições**

Crie a condição a qual a regra deve ser aplicada, para a regra ser aplicada ela precisa obedecer as condições determinadas nesta área


![Campos necessários](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/15%20-%20Cupom%20desconto%20para%20frete%20gr%C3%A1tis/images/4-condicoes.png)

5 -> Navegue até a aba **Ações**

 E preencha as seguintes informaçoes:

```

Aplicar (Valor percentual do desconto % - O desconto será calculado em %)
Valor do Desconto (quantos % será)
Aplicar ao Valor da Entrega (Caso selecionado SIM o valor do frete também será usado no calculo)
Frete Grátis (Caso selecionado SIM concederá FRETE GRATIS para o cliente que utilizar este cupom)
Aplicar Somente esta Regra (Caso selecionado SIM o cliente que aplicar este cupom não mais poderá utilizar outras regras)

```
![Ações](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/15%20-%20Cupom%20desconto%20para%20frete%20gr%C3%A1tis/images/4-acoes.png)

5 -> Feito isso clique em **SALVAR** localizado no canto superior direito;

## Preparar o Magento (Método de Envio):

Para que a regra funcione corretamente você deve habilitar e editar um método de envio nativo do Magento, siga as etapas abaixo:

6 -> Acesse a tela de configuração do Magento: **SISTEMA > CONFIGURAÇÃO**

![Painel de configurações](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/15%20-%20Cupom%20desconto%20para%20frete%20gr%C3%A1tis/images/6-metodoenvio.png)

7 -> Navegue até a opção: **VENDAS > FORMAS DE ENTREGA**

![Painel de envio](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/15%20-%20Cupom%20desconto%20para%20frete%20gr%C3%A1tis/images/7-vendasenvio.png)

8 -> Localize a opção **ENTREGA GRÁTIS** e altere as informações para:

```

Habilitado SIM (para que a regra utilize este método)
Titulo (defina o titulo método)
Nome do método (defina o nome que será apresentado)
Valor Minimo do Pedido (insira o valor 999999 para que ignore este campo)
Mensagem de Erro Apresentada (Neste caso a regra não seja funcional é a mensagem que irá aparecer para o cliente)
Entrega Permitida para Países (Quais países podem utilizar esta regra)

```

![Entrega grátis](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/15%20-%20Cupom%20desconto%20para%20frete%20gr%C3%A1tis/images/8-entregagrais.png)

9 -> Clique no botão **Salvar** localizado no canto superior direito;

10 -> Recomenda-se a atualização do cache:

```

FPC
Layout
Config

```

## Teste da regra:

11 -> Feito as etapas acima, acesse o frontend da loja, sendo o total do carrinho igual ou acima da regra definida, o resultado será similar a este:

![Teste com valor correto](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/15%20-%20Cupom%20desconto%20para%20frete%20gr%C3%A1tis/images/9-testecomvalor.png)

Caso o total do carrinho seja menor que o definido na regra o resultado será similar a este:

![Teste cliente erro](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/15%20-%20Cupom%20desconto%20para%20frete%20gr%C3%A1tis/images/10-testesemvalor.png)

Não irá exibir o método de envio previamente configurado (Etapa 8)

12 -> Pronto, regra criada e testada !


### Dúvidas/Suporte:
Entre em contato com o departamento de suporte.