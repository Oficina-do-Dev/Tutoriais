# Como exportar, importar e preencher a tabela da WebMatrix.

1 -> Primeiramente faça o Login no painel do Magento e vá para **LOJAS > CONFIGURAÇÕES > CONFIGURAÇÃO**.

![tutorial webmatrix](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/050%20-%20Como%20exportar%2C%20importar%20e%20preencher%20a%20tabela%20da%20WebMatrix/images/image1.png)

2 -> Depois acesse **VENDAS > MÉTODOS DE ENVIO**.

![tutorial webmatrix](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/050%20-%20Como%20exportar%2C%20importar%20e%20preencher%20a%20tabela%20da%20WebMatrix/images/image2.png)

3 -> Para conseguirmos importar e exportar a tabela do MatrixRate dentre outras configurações devemos primeiro alterar a visão da loja (seu escopo), no canto superior esquerdo da tela vc irá ver esta opção, clique nela e depois selecione **Main Website**, após ter alterado a visão da loja abra a seção de **WebShopApps Matrix Rate**.

![tutorial webmatrix](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/050%20-%20Como%20exportar%2C%20importar%20e%20preencher%20a%20tabela%20da%20WebMatrix/images/image3.png)

4 -> O WebMatrixRate nos oferece 3 condições diferentes de calculo de frete, sendo elas:

- Peso vs Destino;
- Order Subtotal vs Destination (Preço da compra vs Destino);
- Qtd de itens vs Destino

4.1 -> Desmarque a caixa **Usar Padrão** para desbloquear o campo de condição.

![tutorial webmatrix](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/050%20-%20Como%20exportar%2C%20importar%20e%20preencher%20a%20tabela%20da%20WebMatrix/images/image8.png)

4.2 -> Selecione a condição de sua prefência, o lógica para preencher a tebela com os dados necessários é o mesmo para as 3 opções.

![tutorial webmatrix](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/050%20-%20Como%20exportar%2C%20importar%20e%20preencher%20a%20tabela%20da%20WebMatrix/images/image4.png)

5 -> Clique em **EXPORTAR CSV** para baixar o modelo da tabela, o nome do arquivo é matrixrate.csv. Lembrando que clicando no botão de exportar, ele irá baixar um modelo com base na condição selecioanda acima.

6 -> Você consegue abrir esse arquivo em alguns programas diferentes, podendo ser:

- Qualquer Editor de código que tenha suporte.
- Microsoft Excel.
- LibreOffice Calc.
- Planilhas do Google.

6.1 -> A escolha do programa vai da sua preferência, sendo menos recomendado o Editor de código. Nesse tutorial iremos fazer uso do google planilhas, a condição **Peso vs Destino** com faixas de CEP de estados.

7 -> No programa de sua escolha abra o arquivo **CSV**, de mais espaço entre as células para melhor compreenção da planilha.

![tutorial webmatrix](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/050%20-%20Como%20exportar%2C%20importar%20e%20preencher%20a%20tabela%20da%20WebMatrix/images/image5.png)

8 -> Caso você não queira deixar especifico o País, Região/estado e Cidade, vocẽ pode colocar um asterisco nesses campos e fazer a regra por faixa de CEP, ou vice-versa.

9 -> O sistema da WebMatrixRate utliza de alguns dados da loja como tipo de peso e moeda, então no campo de **Peso** coloque a medida em **Kg** e **Preço de envio** em **Reais**, insira tambèm um nome do método, como no exemplo abaixo.

![tutorial webmatrix](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/050%20-%20Como%20exportar%2C%20importar%20e%20preencher%20a%20tabela%20da%20WebMatrix/images/image6.png)

10 -> As outras condições de frete segue a mesma lógica, então escolha uma condição com base na sua necessidade.

11 -> Ao terminar de preencher as regras, salve o arquivo e importe ele em seu Magento seguindo as etapas **1**, **2** e **3** deste tutorial, então clique em importar, selecione o arquivo e clique em **Abrir**.

![tutorial webmatrix](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/050%20-%20Como%20exportar%2C%20importar%20e%20preencher%20a%20tabela%20da%20WebMatrix/images/image7.png)

12 -> Terminado clique em **Gravar Configuração** no canto superior direito da tela.

13 -> Agora você precisar limpar o cache da loja para que a regras de frete comece a fazer efeito, prossiga para **SISTEMA > FERRAMENTAS > GERENCIAMENTO DE CACHE**.

![tutorial webmatrix](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/050%20-%20Como%20exportar%2C%20importar%20e%20preencher%20a%20tabela%20da%20WebMatrix/images/image9.png)

14 -> Selecione os cache de **Configuration** e **Page cache** e clique me **Enviar**.

![tutorial webmatrix](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/050%20-%20Como%20exportar%2C%20importar%20e%20preencher%20a%20tabela%20da%20WebMatrix/images/image10.png)

15 -> Pronto, agora a regras que você criou ja estão funcionando em sua loja

<hr>

### Dúvidas/Suporte:

Entre em contato com o nosso departamento de suporte.
