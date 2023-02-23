# Como realizar o Update de preço em Massa

1 -> Primeiramente faça login no painel do Magento e vá para **SISTEMA > TRANSFERÊNCIA DE DADOS > EXPORTAR**.

![update preços produtos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/093%20-%20Como%20realizar%20o%20Update%20de%20preço%20em%20Massa/image/image1.png)

2 -> Em **Tipo de entidade** selecione a opção **Produtos** e em Formato do arquivo de exportação mantenha a opção CSV.

![update preços produtos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/093%20-%20Como%20realizar%20o%20Update%20de%20preço%20em%20Massa/image/image2.png)

3 -> Você pode utilizar o filtro com base nas categorias para que sejam exportados apenas os produtos que você deseja realizar o update de preço, caso queira exportar todos os produtos basta clicar em **PRÓXIMO** que está localizado um pouco abaixo da seção dos filtros.

**OBS:** em alguns casos o magento pode demorar um pouco para gerar o arquivo, basta aguardar alguns minutos caso isto aconteça.

4 -> Você poderá realizar o Download do arquivo na mesma página, lembrando que o arquivo mais recente estará em primeiro. Para baixar o arquivo basta clicar em **Selecione** e depois em **Fazer Download**.

![update preços produtos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/093%20-%20Como%20realizar%20o%20Update%20de%20preço%20em%20Massa/image/image3.png)

5 -> Para abrir o arquivo recomendamos fortemente que você utiliza o LibreOffice CALC (baixe <a href="https://www.libreoffice.org/download/download-libreoffice/" target="_blank">AQUI</a>)

6 -> Ao abrir o arquivo pelo LibreOffice Calc irá aparecer essa janela, você **deve** clicar no canto superior esquerdo da tabela (marcado de vermelho) para selecionar todas as celulas e em seguida alterar o tipo de coluna para **TEXTO**, após realizar esta alteração basta clicar em OK para abrir a planilha.

![update preços produtos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/093%20-%20Como%20realizar%20o%20Update%20de%20preço%20em%20Massa/image/image4.png)

7 -> Agora procure pela coluna **PRICE** para alterar os preços dos produtos.
**OBS:** use ponto para valores com casa decimal, caso o valor seja 10 você deve colocar desta maneira -> **10.00**

![update preços produtos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/093%20-%20Como%20realizar%20o%20Update%20de%20preço%20em%20Massa/image/image5.png)

8 -> Após você realizar o update salve o arquivo no formato **CSV**, agora devemos fazer a importação da planilha no magento. Para realizar a importação da planilha vá para **SISTEMA > TRANSFERÊNCIA DE DADOS > IMPORTAR**.

![update preços produtos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/093%20-%20Como%20realizar%20o%20Update%20de%20preço%20em%20Massa/image/image6.png)

9 -> Em **Tipo de entidade** selecione a opção **Produtos**, em **Comportamento de importação** selecione a opção **Adicionar/atualizar**, em **Estratégia de validação** selecione a opção **Pular entradas de erros**, agora basta fazer o upload da planilha clicando em **Escolher arquivo**.

![update preços produtos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/093%20-%20Como%20realizar%20o%20Update%20de%20preço%20em%20Massa/image/image7.png)

10 -> Agora clique em **Verificar dados** no canto superior direito para que o magento faça a validação da planilha.

**OBS:** em alguns casos é necessário alterar o idioma da conta para Inglês, alguns campos presentes na planilha são exportadas com os valores em Inglês assim ocasionando problemas na importação.

11 -> Caso todos os valores estejam corretos você receberá esta mensagem junto com o botão **Import**, basta clica-lo para que o Magento faça a importação da planilha.

![update preços produtos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/093%20-%20Como%20realizar%20o%20Update%20de%20preço%20em%20Massa/image/image8.png)

12 -> Agora aguarde o CRON realizar o reindex na loja (em média de 3 à 5 minutos) e logo após verifique os produtos para ter certeza que as alterações foram realizadas com sucesso.

<hr>

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.