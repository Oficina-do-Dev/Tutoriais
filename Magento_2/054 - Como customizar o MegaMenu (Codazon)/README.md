# Como customizar o MegaMenu do tema Codazon Fastest

1 -> Primeiramente faça login no painel do Magento e acesse **CODAZON > MANAGE MEGAMENU**.

![megamenu codazon](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/054%20-%20Como%20customizar%20o%20MegaMenu%20(Codazon)/images/image1.png)

2 -> Nesta página esão localizados todos os menus do tema Fastest Codazon, procure pelo menu referente ao seu tema e clique nele para abri-lo, em nosso caso temos 2 menus sendo utilizados ao mesmo tempo sendo um vertical e o outro horizontal respectivamente Sidebar - BUZZ e MEGAMENU (HEADER) - BUZZ.

![megamenu codazon](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/054%20-%20Como%20customizar%20o%20MegaMenu%20(Codazon)/images/image2.png)

3 -> Primeiro você encontrará as configurações gerais deste menu, altere apenas o **Título** do menu se desejar, mas em hipótese alguma modifique o **indentificador**.

![megamenu codazon](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/054%20-%20Como%20customizar%20o%20MegaMenu%20(Codazon)/images/image3.png)

4 -> Descendo a página chegamos a área de edição e customização do megamenu.

4.1 -> Na área delimitada pela **cor vermelha** temos os itens que irão incorporar o menu, você pode clicar e segurar neles arrastando para a área do menu, delimitada pela **cor amarela**. 

4.2 -> No canto inferior esquerdo você encontra um link direto para uma playlist de tutoriais do megamenu, produzida pela desenvolvedora do tema. 

4.3 -> No botão **verde** você tem uma visualização rápida de como o menu está ficando.

![megamenu codazon](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/054%20-%20Como%20customizar%20o%20MegaMenu%20(Codazon)/images/image4.png)

5 -> Explicando os itens do megamenu:

- **Item link:** adiciona um único link ao menu.
- **Dropdown Content:** possibilita adicionar um conteúdo html personalizado. Se usar este tipo, você pode adicionar seu html com as customizações que você deseja.
- **Tabs Container e Tab item:** são utilizados como dropdown customizados para os demais itens.
- **Categories list:** aqui você seleciona uma categoria de sua loja e apartir dela o menu irá puxar o restante das subcategorias.
- **Bootstrap Row e Bootstrap Column:** Se você tem conhecimento sobre Boostrap CSS, pode usar este tipo para criar seu menu. O módulo suporta Boostrap 12-Columns. Este tipo o ajudará a construir um layout complexo para o menu suspenso. Se o layout suspenso não for muito complexo, você deve usar o Dropdown Content.

![megamenu codazon](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/054%20-%20Como%20customizar%20o%20MegaMenu%20(Codazon)/images/image5.png)

6 -> Para criar o menu você deve pegar o item a esquerda, arrastar e soltar na área especificada no tópico 4.1. Para criar menus com dropdown você deve primeiro inserir um item e o próximo um pouco a direita.

![megamenu codazon](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/054%20-%20Como%20customizar%20o%20MegaMenu%20(Codazon)/images/image6.png)

7 -> Clique no Lápis no canto direito de cada item para abrir as opções de customização dele. A seta ao lado serve para que caso haja subitens deste, você consiga vê-los.

![megamenu codazon](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/054%20-%20Como%20customizar%20o%20MegaMenu%20(Codazon)/images/image7.png)

8 -> Atribua um titulo ao item, caso o link de referência seja para uma página interna da loja ou uma página de categoria, o link deve estar dentro de ```{{store direct_url='LINK AQUI'}}``` para que funcione, caso seja uma página de categoria deve-se inserir **.html** no final do link.

8.1 -> Caso você queira realizar uma customização nesse item você também consegue atribuir uma classe css no item.

8.2 -> Tambem é possivel adicionar um icone da biblioteca de icones do tema clicando em **ICON FONT LIBRARY** ou uma imagem ou icone de qualquer outro lugar desde que obedeça o tamanho 32 x 32 pixels, em **Icon item use** troque para **Get icon from image library or other URL** e insira o link da imagem no campo especificado.

![megamenu codazon](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/054%20-%20Como%20customizar%20o%20MegaMenu%20(Codazon)/images/image8.png)

9 -> Terminado de customizar, clique em **Save Menu** no canto superior direito e pronto o menu ja estará funcionando no header do site.

<hr>

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.