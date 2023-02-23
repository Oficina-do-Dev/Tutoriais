# Alterando Banners 

1 -> Primeiramente, através do painel, acesse **CMS -> Blocos Estáticos** .

![alterando_banners](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/20-%20Alterando%20Banners/images/image1.png)

2 -> Acesse Pagina inicial - BUZZ

![alterando_banners](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/20-%20Alterando%20Banners/images/image2.png)

3 -> Você será redirecionado para a página onde é exibido o código fonte da Home-Buzz, nessa página você pode inserir imagens através do botão **Insert Image**(detalhe: as imagens upadas são traduzidas em código fonte também).
**ATENÇÃO!** É recomendado que antes de inserir uma imagem ao código, role até a última linha do código e clique em uma linha vazia.

![alterando_banners](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/20-%20Alterando%20Banners/images/image3.png)

Obs: Também é recomendado que as imagens de banners sejam colocadas no caminho **Armazenamento/porto/homepage/slider/09**, caso não houver na pasta a imagem desejada, você pode adicionar uma nova imagem clicando em **Procurar Arquivos**, procure a imagem em seu computador e depois de selecionada clique em **Enviar Arquivos**.

![alterando_banners](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/20-%20Alterando%20Banners/images/image4.png)

4 -> Após escolhida a imagem, clique em **Inserir Arquivo**.

![alterando_banners](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/20-%20Alterando%20Banners/images/image5.png)

Feito isso, o código então será inserido de fomar automática para o lugar onde foi selecionado no bloco de código.

![alterando_banners](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/20-%20Alterando%20Banners/images/image6.png)

Na última linha onde o trecho de código da imagem se encontra, copie todo o conteúdo entre chaves e depois apague a linha toda.

5 -> Tendo o conteúdo entre chaves copiado, retorne para o topo do bloco de código e então substitua a imagem antiga pela nova imagem colando o conteúdo entre as chaves dessa linha.

![alterando_banners](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/20-%20Alterando%20Banners/images/image7.png)

A imagem em questão está sendo substítuida no Slide 1, sempre procure a linha de código entre:

```
 <!-- SLIDER (numero) > **  

```

e

```
<!-- FIM SLIDER (numero) >

```
Um pouco mais abaixo  em **href=”{{store url=’produtos-ate-9-99.html’}}”** , insira entre as aspas um link referente ao banner de sua loja.

6 -> Caso deseje inserir mais banners na home, copie todo o bloco de código abaixo e cole-o antes de  

```

 <!-- FIM AREA SLIDER > 

```

**O seguinte código deve ser copiado**

```

<div id='banner-slider-demo-9' class "owl-carousel owl-theme owl-middle-narrow owl-banner-caroulsel >
<!-- AREA DO SLIDER -->

<!-- SLIDER 1 -->
    <div class="item" style="background:url({{media url="wysiwyg/porto/homepage/slider/09/slider_9e90.jpg"}}) 30% no-repeat; background-size:cover;">
<!-- FIM SLIDER 1 -->
<div class="container" style="position:relative">
<a href="{{store url='produtos-ate-9-99.html'}}"><img src="{{media url="wysiwyg/porto/homepage/slider/05/02.png"}}" width="1140" height="500" alt=""/>
<div class="content" style="position:absolute;top:30%;right:9%;text-align:left;">
<div class="clearer"></div>
</a>
</div>
</div>
</div>

```
Em seguida, clique em  **Salvar** no canto superior direito da tela, finalizando a alteração.

<hr>

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.

