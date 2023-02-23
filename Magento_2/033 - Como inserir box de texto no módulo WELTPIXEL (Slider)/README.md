# Como inserir box de texto no slider WELTPIXEL

1 -> Acesse o painel magento usando seus dados de acesso, na sidebar procure pela opção **WELTPIXEL** e clique nela;

![weltpixel](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/033%20-%20Como%20inserir%20box%20de%20texto%20no%20módulo%20WELTPIXEL%20(Slider)/images/image1.png)

2 -> No menu do weltpixel clique em **Banners for Sliders**;

![weltpixel](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/033%20-%20Como%20inserir%20box%20de%20texto%20no%20módulo%20WELTPIXEL%20(Slider)/images/image2.png)

3 -> Aqui é onde ficam todos os banners da loja, escolha qual deseja customizar e clique em **Editar**;

![weltpixel](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/033%20-%20Como%20inserir%20box%20de%20texto%20no%20módulo%20WELTPIXEL%20(Slider)/images/image3.png)

4 -> Na tela de customização do banner desça a tela até encontrar a opção **Custom HTML Content**;

![weltpixel](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/033%20-%20Como%20inserir%20box%20de%20texto%20no%20módulo%20WELTPIXEL%20(Slider)/images/image4.png)

Neste bloco você pode inserir o HTML personalizado para que a box seja exibida, segue exemplo de texto:
**DICA:** utilize algum software de edição de código para visualizar como a imagem abaixo (visual code, sublime, etc.), lembrando de alterar para o formato .html no tipo de leitura do texto.

```
<div class="slide3-1-new-content content" style="position: absolute; left: 4.5%; top: 27%; font-family: Oswald; background-color: #000; width: auto; height: auto; padding: 35px;"><em style="font-size: 15px;">Coleções elegantes</em>
<div class="clearer"></div>
<h2>PARA ELE &amp; ELA</h2>
<div class="clearer"></div>
<a class="btn btn-default" style="background-color: #333B52;" href="{{store url='produtos-sahari.html'}}"><span style="color: #fff;">SHOP NOW</span></a></div>
<style>
	@media screen and (max-width: 780px) {
		.slide3-1-new-content {
			display:none;
		}
	}
</style>

```
### Explicando o bloco acima:

- entre a tag **h2** PARA ELE & ELA você deve informar o titulo do bloco;
- caso queira alterar a cor da box, alterar o background-color: #000; sendo #000 o código da cor, para encontrar o código da cor, acesse o site: https://htmlcolors.com/
- caso queira alterar a cor do botão, alterar o background-color:  #333B52; substituindo pelo código da cor desejada, para encontrar o código da cor, acesse o site: https://htmlcolors.com/
- caso quiser alterar a família da fonte da box, alterar font-family: Oswald para a família pretendida;
- entre a tag **span** SHOP NOW possui o titulo do botão;
- caso queira alterar o destino do botão, alterar  store url='produtos-sahari.html' substituindo 'produtos-sahari.html' pelo link desejado;

Na forma atual está ocultando o box para resoluções abaixo de 780px de largura, caso queira remover (não recomendado) apagar todo conteudo presente no intervalo: 

```
@media screen and (max-width: 780px) {
 		.slide3-1-new-content {
 			display:none;
 		}
 	}

```

5 -> O resultado desde persolalização será:

![weltpixel](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/033%20-%20Como%20inserir%20box%20de%20texto%20no%20módulo%20WELTPIXEL%20(Slider)/images/image5.png)

6 -> Caso seja necessário você precisará limpar o cache da loja dos seguintes itens:

```

LAYOUT
BLOCK
FPC

```

<hr>

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.