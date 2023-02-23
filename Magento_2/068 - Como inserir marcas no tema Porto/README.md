# Como inserir marcas no tema Porto

**Importante:** para inserir ou alterar qualquer marca é recomendado que você utilize um editor de código (Visual Studio Code, Sublime, notepad++ e etc) para realizar as alterações no código do bloco com mais segurança e agilidade. As imagens das marcas devem ser na **resolução de 150 x 150 pixels**.

1 -> Abra o painel Magento e acesse **CONTEÚDO > BLOCOS**.

![como inserir marcas](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/068%20-%20Como%20inserir%20marcas%20no%20tema%20Porto/images/image1.png)

2 -> Procure pelo bloco estático referente à área de marcas e clique em **Selecionar** e depois em **Editar**, aqui o bloco se chama Marcas - Footer Top - BUZZ.

![como inserir marcas](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/068%20-%20Como%20inserir%20marcas%20no%20tema%20Porto/images/image2.png)

3 -> Desça até a área de conteúdo do bloco onde estará o código do slider, copie o código e cole em um editor de código e a partir dele que iremos começar.

**Atenção:** antes de salvar a alteração feita no bloco **NÃO** troque a visão do conteúdo para editor de texto, poís isto fará com que o código pare de funcionar. Se acaso você salvar o bloco e o slider parar de funcionar entre em contato com o nosso suporte.

4 -> Para adicionar uma nova marca acrescente esta linha de código logo abaixo da ultima marca.

```

<div class="item"><img class="owl-lazy" data-src="(LINK DA IMAGEM AQUI)" alt="" style="display: inline-block;width: 150px; height: 150px; border-radius: 50px;" /></div>

```

![como inserir marcas](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/068%20-%20Como%20inserir%20marcas%20no%20tema%20Porto/images/image3.png)

5 -> No Magento agora, no conteúdo do bloco estático clique na ultima linha e aperte **Enter** algumas vezes para adicionar mais linhas, então você deve clicar em **Insert Image**.

![como inserir marcas](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/068%20-%20Como%20inserir%20marcas%20no%20tema%20Porto/images/image4.png)

6 -> Agora navegue pelas pastas até a encontrar a pasta **marcas**, clicando nela você encontrará imagens das outras marcas que ja estão sendo exibidas em sua loja, para realizar o upload de uma nova imagem clique em **Choose Files** e procure a imagem em seu computador.

![como inserir marcas](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/068%20-%20Como%20inserir%20marcas%20no%20tema%20Porto/images/image5.png)

7 -> Após fazer o upload da imagem no loja, selecione ela e clique em **Add Selected**.

![como inserir marcas](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/068%20-%20Como%20inserir%20marcas%20no%20tema%20Porto/images/image6.png)

8 -> Note que na ultima linha foi adicionado o código da imagem, agora copie todo o conteúdo entre aspas do atributo src.

![como inserir marcas](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/068%20-%20Como%20inserir%20marcas%20no%20tema%20Porto/images/image7.png)

9 -> Agora no editor de código, na linha que você adicionou substitua o **(LINK DA IMAGEM AQUI)** pelo conteúdo que você copiou na etapa anterior.

10 -> Após ter terminado aperte **CTRL + A** para selecionar todo o código e depois **CTRL + C** para copiar, agora no bloco estático em conteúdo aperte **CTRL + A** para selecionar tudo e depois aperte **CTRL + V** para substituir todo o conteúdo do bloco estático, terminado clique em **Salvar**.

11 -> Nesse momento a imagem da marca já foi inserida com sucesso, basta você ir até a home de sua loja e conferir.

### Dúvidas/Suporte:
Entre em contato com nosso departamento de suporte.