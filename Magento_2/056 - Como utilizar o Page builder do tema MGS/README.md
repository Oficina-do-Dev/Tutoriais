# Como utilzar o page builder do tema MGS

**Avisos importantes:**
Para que você consiga utilizar o page builder, seu usuário do painel Magento deve estar habilitado no page builder.
Qualquer tipo de customização que for necessário ser realizado na home do site deve ser feito obrigatóriamente pelo Page Builder da MGS, caso contrário você corre o risco de corromper a home de seu site.

1 -> Após ter ativado seu usuário faça login com ele pelo site, como um cliente normal, após ter realizado o login você irá reparar em uma barra preta que apareceu no topo de sua tela, clique no switch com o título de **Active Builder** para ativar no page builder.

2 -> Com o page builder ativado você notará que todos os blocos e seções de seu site estão envoltos em caixas com borda tracejada, isto serve para delimitar os blocos.

3 -> Você pode adicionar quantos blocos e seções você desejar, mas tome cuidado com o desempenho de seu site. Para customizar as seções (demilitadas por caixas verdes) clique no simbolo de engrenagem localizadas no topo de cada seção.

![page builder MGS](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/056%20-%20Como%20utilizar%20o%20Page%20builder%20do%20tema%20MGS/images/image1.png)

4 -> Aqui você terá algumas opções referentes a esta seção como:

- **Fullwidth** - determina que a seção ocupará a largura total da tela.
- **Class name** - você pode inserir um nome específico neste campo, possibilitando a customização via CSS ou javascript em um arquivo externo.
- **Background color** - caso você deseja que o fundo desta seção tenha uma cor fixa, você pode inserir aqui o código hexadecimal da cor que deseja.
- **Background image** - aqui você pode fazer o upload de uma imagem que ficará de fundo na seção.
- **Background repeat** - isto serve para que caso a imagem inserida seja muito pequena, o pagebuild irá repetir ela até que ocupe o tamanho total da seção.
- **Parallax** - ativa o efeito parallax na imagem que estiver de fundo.
- **Background Cover** - faz com que a imagem, caso seja pequena, ocupe o espaço todo da seção (isso pode distorcer um pouco a imagem dependendo do tamanho dela).
- **Padding top** - acrescenta um espaço ao topo da seção com base no numero em pixel inserido no campo.
- **Padding bottom** - acrescenta um espaço abaixo da seção com base no numero em pixel inserido no campo.

4.1 -> Em **Column Config** você consegue configurar como que será dividido os blocos dentro desta seção.

![page builder MGS](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/056%20-%20Como%20utilizar%20o%20Page%20builder%20do%20tema%20MGS/images/image2.png)

5 -> Dentro da seção haverá blocos divididos conforme a configuração de seção. Clique em **Add New Block** para adicionar um novo bloco. Abrirá um janela com algun tipos diferentes de blocos que você pode utilizar, escolha um com base na sua necessidade, mais à frente iremos explicar alguns deles.

![page builder MGS](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/056%20-%20Como%20utilizar%20o%20Page%20builder%20do%20tema%20MGS/images/image3.png)

6 -> No topo de cada bloco haverá um pequeno menu contendo as opções de:

- **Mover** - esta opção serve para arrastar o bloco (mover ele de lugar), clique e segure sobre o ícone para realizar esta ação.
- **Editar** - esta opção é para abrir o menu de configuração e customização do bloco.
- **Proporção do bloco** - serve para ajustar o tamanho do bloco.
- **Excluir bloco** - excluir o bloco e seu conteúdo.

![page builder MGS](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/056%20-%20Como%20utilizar%20o%20Page%20builder%20do%20tema%20MGS/images/image4.png)

7 -> Vamos agora mostrar como que funciona a customização de um bloco, lembrando que como existem diversos tipos de blocos disponíveis, explicaremos apenas 3 mas a base é a mesma para os demais.

![page builder MGS](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/056%20-%20Como%20utilizar%20o%20Page%20builder%20do%20tema%20MGS/images/image5.png)

8 -> Começando pelo **Text content & Images**, ele é um bloco utilizado para inserir conteúdo de texto e imagem na home de seu site. 

8.1 -> Ao clicar para adicionar este bloco você verá algumas opções, sendo elas:

- **Block col** - isto é a proporção do bloco dentro da seção, sendo 12 a proporção máxima.
- **Custom Class** - você pode inserir um nome específico neste campo, possibilitando a customização via CSS ou javascript em um arquivo externo.
- **Block Animation** - aqui você pode escolher um efeito/animação para o bloco.
- **Animation Delay** - define o tempo de duração do efeito em milissegundos.

8.2 -> Na aba **Conteúdo** é onde os textos e imagens que você deseja inserir no bloco devem ficar, podendo tanto ser editado pelo próprio editor de texto do modulo ou com uma estrutura HTML e sendo personalizada por CSS externo.

8.3 -> Em **Imagens** haverá algumas imagens do tema com o código html para você utilizar.

![page builder MGS](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/056%20-%20Como%20utilizar%20o%20Page%20builder%20do%20tema%20MGS/images/image6.png)

9 -> Vamos agora mostar o **OWL Carousel Slider** e suas opções de customização.

9.1 -> Na aba Geral você encontra as seguntes opções:

- **Block col** - isso é a proporção do bloco dentro da seção, sendo 12 a proporção máxima.
- **Custom Class** - você pode inserir um nome específico neste campo, possibilitando a customização via CSS ou javascript em um arquivo externo.
- **Block Animation** - aqui você pode escolher um efeito de apresentação para o bloco.
- **Animation Delay** - define o tempo de duração do efeito em milissegundos.

**Importante** o efeito descrito na aba geral se aplica ao bloco todo, efeito de transição das imagens é definido na aba Slider Config.

![page builder MGS](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/056%20-%20Como%20utilizar%20o%20Page%20builder%20do%20tema%20MGS/images/image7.1.png)

9.2 -> Em **Manage Imagens** você deve fazer o upload das imagens que irá utilizar no slide, clicando em **+ Upload new Image**.

![page builder MGS](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/056%20-%20Como%20utilizar%20o%20Page%20builder%20do%20tema%20MGS/images/image7.2.png)

9.3 -> Agora iremos adicionar a imagem ao slide, na aba **Manage Slide** clique em **Add new Slide**. Agora selecione uma imagem (esse processo de adicionar a imagem ao slide tem que ser feito individualmente), logo abaixo haverá opções de:

- **Link** - caso você deseje que o banner redirecione para alguma página ou categoria de sua loja, adicione o link aqui.
- **Alt Image** - é o título da imagem.
- **Text (html)** - neste campo caso você deseje inserir algum texto no slide, ele deve ser inserido por meio de código html.
- **Text Position** - aqui você deve selecionar a posição que o texto irá ficar com relação ao slide.
- **Text Animation** - você pode selecionar uma opção de animação para o texto aqui.

![page builder MGS](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/056%20-%20Como%20utilizar%20o%20Page%20builder%20do%20tema%20MGS/images/image7.3.png)

9.4 -> Agora em **Slide Config** que vamos editar as opções de efeitos e customizações gerais do slide:

- **Full Width** - determina que o slide ocupará a largura total da tela.
- **Full height** - determina que o slide ocupará o comprimento total da tela.
- **Effect** - animação/efeito da transição de imagem do slider.
- **Auto play** - possibilita que o slide inicialize sozinho a transição entre as imagens.
- **Auto play speed** - velocidade da transição das imagens.
- **Stop autoplay on mouse hover** - esta função significa que o auto play será interrompido assim que o mouse estiver em cima dele.
- **Display nav** - habilita as setas de navegação para que o usuário consiga passar os slider sozinho.
- **Display dots** - habilita bolinhas de navegação dos slides.
- **Nav e Dots Template** - escolha diferentes tipos de layout para as setas e pontos de navegação aqui, caso os tenha ativado.
- **Loop** - toda vez que as imagens acabar, ele voltará para o inicio assim fazendo um loop infinito.

9.5 -> Pronto agora basta clicar em **Enviar**.

10 -> Vamos ver agora o **Promotion Banner**, na Aba geral temos as opções:

- **Block col** - isso é a proporção do bloco dentro da seção, sendo 12 a proporção máxima.
- **Custom Class** - você pode inserir um nome específico neste campo, possibilitando a customização via CSS ou javascript em um arquivo externo.
- **Block Animation** - aqui você pode escolher um efeito de apresentação para o bloco.
- **Animation Delay** - define o tempo de duração do efeito em milissegundos.

![page builder MGS](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/056%20-%20Como%20utilizar%20o%20Page%20builder%20do%20tema%20MGS/images/image8.png)

10.1 -> Na aba de **Banner Config** temos as opções de:

- **Banner Title** - é o título do banner.
- **Banner Image alt** - é o título da imagem do banner.
- **Imagem** - clique no botão choose file para fazer o upload de uma imagem que será usada no banner.
- **Conteúdo** - caso você queira adicionar algum texto ao banner você deve inseri-lo aqui.
- **Texto do botão** - como o nome já fiz, você deve inserir aqui um texto que aparecerá no botão de redirecionamento do banner.
- **URL** - neste campo você deve inserir o link da categoria ou página referente ao banner.
- **Text Align** - tipo de alinhamento do botão.
- **Effect** - efeito ao passar a mouse pele banner.

![page builder MGS](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/056%20-%20Como%20utilizar%20o%20Page%20builder%20do%20tema%20MGS/images/image8.1.png)

10.2 -> Nas outras abas de Promotion banner não é necessário realizar nenhuma alteração.

11 -> A customização dos outros tipos de blocos seguem a mesma lógica destes que eu apresentei pra você. Após terminar de customizar o layout você deve recarregar a página apertando CTRL + F5 para que você consiga visualizar as alterações que foram feitas, para efetivar estas alterações no site, você deve voltar ao topo da página e clicar em **Confirmar**, presente no canto superior esquerdo da tela e pronto.

<hr>

### Dúvidas/Suporte: 
Entre em contato com o nosso departamento de suporte.
