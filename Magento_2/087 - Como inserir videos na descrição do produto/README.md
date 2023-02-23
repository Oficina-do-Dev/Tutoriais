# Como inserir videos na descrição do produto

No Magento, você pode adicionar vídeos de algumas formas na apresentação do produto, neste tutorial iremos abordar o método do iframe que trata de utilizar os recursos do youtube para processar seu vídeo e com isso evitar consumo de hardware de seu servidor. Por se tratar de um tutorial especifico não iremos abordar o processo de criação do produto, para isso acesse o tutorial especifico [aqui](https://github.com/Oficina-do-Dev/Tutoriais/tree/main/Magento_2/002%20-%20Tipos%20de%20produto)

1 -> Acesse o painel Magento da sua loja;

2 -> Na grid de produtos selecione o produto que você deseja editar;

![selecione o produto](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/087%20-%20Como%20inserir%20videos%20na%20descri%C3%A7%C3%A3o%20do%20produto/images/imagem_1.png)

3 -> Clique em EDITAR, no produto prossiga até a seção **DESCRIÇÃO LONGA**

![descrição longa](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/087%20-%20Como%20inserir%20videos%20na%20descri%C3%A7%C3%A3o%20do%20produto/images/imagem_2.png)

4 -> Agora você deve acessar o **YouTube** e selecionar o vídeo que você deseja inserir ao produto;

5 -> Acesse o vídeo, nele clique com o botão direito do mouse e selecione a opção **Copiar código de incorporação**;

![Youtube](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/087%20-%20Como%20inserir%20videos%20na%20descri%C3%A7%C3%A3o%20do%20produto/images/imagem_3.png)

6 -> Por segurança, cole o conteudo copiado em um editor de texto, no exemplo abaixo estamos utilizando o [Visual Studio Code](https://code.visualstudio.com/download);

	Texto copiado (exemplo): 
	<iframe width="790" height="444" src="https://www.youtube.com/embed/KcRmXWMUhpg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

7 -> Note que no conteúdo copiado possui algumas informações importantes, como width (largura) e height (altura), para melhor visualização em diferentes dispositivos vamos alterar estes dados antes de inserir no produto;

**ATENÇÃO:** Você não é obrigado alterar estas informações pode apenas colar no campo **DESCRIÇÃO LONGA**, caso queira pular esta etapa, vá para o **Tópico 11** deste tutorial;

8 -> Caso você não fizer a personalização ficará da seguinte forma:

![visão desktop](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/087%20-%20Como%20inserir%20videos%20na%20descri%C3%A7%C3%A3o%20do%20produto/images/imagem_4.png)

![visão mobile](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/087%20-%20Como%20inserir%20videos%20na%20descri%C3%A7%C3%A3o%20do%20produto/images/imagem_5.png)

9 -> Para corrigir esta questão altere as informações para:

	<iframe width="100%" height="400" src="https://www.youtube.com/embed/KcRmXWMUhpg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

10 -> O resultado esperado é:


![visão desktop](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/087%20-%20Como%20inserir%20videos%20na%20descri%C3%A7%C3%A3o%20do%20produto/images/imagem_6.png)

![visão mobile](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/087%20-%20Como%20inserir%20videos%20na%20descri%C3%A7%C3%A3o%20do%20produto/images/imagem_7.png)

11 -> Para inserir no produto, copie este conteúdo e cole no campo **DESCRIÇÃO LONGA**;

![descrição longa](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/087%20-%20Como%20inserir%20videos%20na%20descri%C3%A7%C3%A3o%20do%20produto/images/imagem_8.png)

**ATENÇÃO:** Caso seu Magento esteja habilitado o editor (similar ao World) você precisa voltar ao modo código, para isso clique em **Show / Hide Editor**. O editor modo código possui o layout similar a este:

![editor](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/087%20-%20Como%20inserir%20videos%20na%20descri%C3%A7%C3%A3o%20do%20produto/images/imagem_9.png)

12 -> Feito isso, clique em SALVAR, localizado no canto superior direito e verifique no frontend o resultado;

**ATENÇÃO:** Caso seu indice esteja configurado para executar por agenda, o resultado irá aparecer após a próxima execução, neste caso o aconselhável é aguardar.

13 -> Pronto, você inseriu o vídeo no cadastro do seu produto.

### Dúvidas/Suporte:

Entre em contato com o nosso departamento de suporte.