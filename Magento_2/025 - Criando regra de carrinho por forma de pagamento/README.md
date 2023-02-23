# Como criar regra de carrinho por forma de pagamento

1 -> Faça login no painel Magento usando seus dados de acesso, então abra **MARKETING > PROMOÇÕES > REGRAS DE PREÇO DE CARRINHO**;

![regra_de_preço](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/025%20-%20Criando%20regra%20de%20carrinho%20por%20forma%20de%20pagamento/images/image1.png)

2 -> Clique em **Adicionar Nova Regra** no canto superior direito;

![regra_de_preço](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/025%20-%20Criando%20regra%20de%20carrinho%20por%20forma%20de%20pagamento/images/image2.png)

3 -> Insira um nome à regra e se preferir adicione uma descrição para explicar a função, selecione o **Main Website** para habilidar esta regra na visão principal do site, agora com o **CTRL** apertado selecione os grupos de clientes que poderão usar a regra, em **Cupom** deixe como **Sem cupom** (a menos que você queira atribuir um desconto por uso cupom);

![regra_de_preço](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/025%20-%20Criando%20regra%20de%20carrinho%20por%20forma%20de%20pagamento/images/image3.png)

4 -> Desça um pouco a tela até encontrar a aba **Condições** e clique nela para abrir;

![regra_de_preço](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/025%20-%20Criando%20regra%20de%20carrinho%20por%20forma%20de%20pagamento/images/image4.png)

5 -> Agora clique no sinal de **+** para adicionar uma condição; 

![regra_de_preço](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/025%20-%20Criando%20regra%20de%20carrinho%20por%20forma%20de%20pagamento/images/image5.png)

5.1 -> Abrirá um campo para que você selecione uma opção, procure por **Forma de pagamento/Método de pagamento**;

![regra_de_preço](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/025%20-%20Criando%20regra%20de%20carrinho%20por%20forma%20de%20pagamento/images/image6.png)

5.2 -> Clique onde está os três pontos e abrirá um menu com todas as formas de pagamento disponiveis em sua loja, selecione a que você deseja atribuir o desconto;

![regra_de_preço](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/025%20-%20Criando%20regra%20de%20carrinho%20por%20forma%20de%20pagamento/images/image7.png)

**Atenção:** se você precisa que o desconto seja aplicável para mais de um método de pagamento, siga o procedimento abaixo.

6 -> Agora clique no sinal de **+** para adicionar uma condição e selecione a opção **Combinação de condições**, faça isso duas vezes; 

![regra_de_preço](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/025%20-%20Criando%20regra%20de%20carrinho%20por%20forma%20de%20pagamento/images/image5.png)

6.1 -> As condições devem ficar desta maneira, não esqueça de alterar a validação da primeira condição para **QUALQUER**.

![regra_de_preço](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/025%20-%20Criando%20regra%20de%20carrinho%20por%20forma%20de%20pagamento/images/image13.png)

6.2 -> Agora adicione cada opção de pagamento dentro de uma condição, desta forma:

![regra_de_preço](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/025%20-%20Criando%20regra%20de%20carrinho%20por%20forma%20de%20pagamento/images/image14.png)

**OBS:** reproduza a mesma estrutura circulada para cada método de pagamento que você deseje adicionar à regra.

7 -> Desça um pouco a tela e abra a opção **Ações**;

![regra_de_preço](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/025%20-%20Criando%20regra%20de%20carrinho%20por%20forma%20de%20pagamento/images/image8.png)

8 -> Em **Quantidade de Desconto** insira o desconto que será aplicado a função (apenas número e caso seja número quebrado separe com ponto);

![regra_de_preço](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/025%20-%20Criando%20regra%20de%20carrinho%20por%20forma%20de%20pagamento/images/image9.png)

9 -> Caso queira que o valor de desconto também seja aplicado ao frete, então marque a opção **Aplicar ao Valor de Entrega** como sim, caso queira que o valor do frete seja um valor a parte, então basta deixar esta opção como não.

![regra_de_preço](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/025%20-%20Criando%20regra%20de%20carrinho%20por%20forma%20de%20pagamento/images/image10.png)

10 -> Abaixo de **Aplicar ao Valor de Entrega** você encontrará **Descartar as regras subseqüentes**, por padrão é deixado como **Não**, porém, caso queira que as próximas regras após a regra do **Frete** sejam descartadas, deixe como **Sim** .

![regra_de_preço](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/025%20-%20Criando%20regra%20de%20carrinho%20por%20forma%20de%20pagamento/images/image11.png)

11 -> Pronto, agora clique em **Salvar** no canto superior direito e basta ir no checkout do site para fazer a verificação e validação

![regra_de_preço](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/025%20-%20Criando%20regra%20de%20carrinho%20por%20forma%20de%20pagamento/images/image12.png)

<hr>

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.