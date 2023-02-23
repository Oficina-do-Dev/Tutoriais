# Como criar cupom desconto no Magento 1

## Requitos:

* Acesso ao painel Magento;

## Como criar:

No exemplo abaixo iremos criar uma regra que concede 10% de desconto usando código de cupom específico para ser usado apenas uma vez por cliente (primeiracompra).

1 -> Acesse o painel Magento;

![Tela de criação](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/14%20-%20Como%20criar%20cupom%20desconto/images/1-regraspromocao.png)	

2 -> Nesta tela clique em **Criar Regra** localizado no canto superior direito;

![Criar regra](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/14%20-%20Como%20criar%20cupom%20desconto/images/2-criarregra.png)	 

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

![Campos necessários](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/14%20-%20Como%20criar%20cupom%20desconto/images/3-camposinfo.png)

4 -> Navegue até a aba **Ações**

 E preencha as seguintes informaçoes:

```

Aplicar (Valor percentual do desconto % - O desconto será calculado em %)
Valor do Desconto (quantos % será)
Aplicar ao Valor da Entrega (Caso selecionado SIM o valor do frete também será usado no calculo)
Frete Grátis (Caso selecionado SIM concederá FRETE GRATIS para o cliente que utilizar este cupom)
Aplicar Somente esta Regra (Caso selecionado SIM o cliente que aplicar este cupom não mais poderá utilizar outras regras)

```
![Ações](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/14%20-%20Como%20criar%20cupom%20desconto/images/4-acoes.png)

5 -> Feito isso clique em **SALVAR** localizado no canto superior direito;

6 -> Recomenda-se a atualização do cache

```

FPC
Layout
Config

```

## Teste do cupom:

7 -> Feito as etapas acima, acesse o frontend da loja, insira o cupom no campo definido para este, caso haja sucesso o resultado será similar a este:

![Teste cliente](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/14%20-%20Como%20criar%20cupom%20desconto/images/5-primeiracompra.png)

Finalizando a compra com a utilização do cupom, caso tenha informado **Usos por Cliente = 1** e você tentar realizar outro pedido com o mesmo cupom, o resultado será similar a este:

![Teste cliente erro](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/14%20-%20Como%20criar%20cupom%20desconto/images/5-primeiracompraerro.png)

8 -> Pronto, cupom criado e testado !


### Dúvidas/Suporte:
Entre em contato com o departamento de suporte.