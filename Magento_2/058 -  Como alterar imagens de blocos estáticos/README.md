# Como alterar imagens de blocos estáticos

1 -> Primeiramente faça login no painel do Magento e acesse **CONTEÚDO > ELEMENTOS > BLOCOS**.

![alterando imagens](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/058%20-%20%20Como%20alterar%20imagens%20de%20blocos%20estáticos/images/image1.png)

2 -> Aqui nesta página fica localizado todos os blocos estáticos de sua loja, procure pelo bloco em que você deseja realizar a troca de imagem e clique nele para abri-lo. Aqui vamos utilizar o BANNER (home page - institucional).

3 -> Existem duas maneiras de alterar as imagens do bloco estático, por editor de texto e por editor de código, vamos ensinar as duas alternativas para você.

## Via editor de texto

1 -> Desça a página até a área de conteúdo do bloco, aqui você consegue visualizar o conteúdo do bloco junto com as imagens que nela estão. Clique na imagem que você deseja substituir.

![alterando imagens](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/058%20-%20%20Como%20alterar%20imagens%20de%20blocos%20estáticos/images/image8.png)

2 -> Depois clique em **Insert > Image**.

![alterando imagens](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/058%20-%20%20Como%20alterar%20imagens%20de%20blocos%20estáticos/images/image9.png)

3 -> Uma janela se abrirá, para alterar a imagem você deve, em **Source**, clique no botão com o **simbolo de pasta e uma lupa** para que você consiga procurar a imagem entre os diretórios do servidor.

![alterando imagens](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/058%20-%20%20Como%20alterar%20imagens%20de%20blocos%20estáticos/images/image10.png)

4 -> Na aba que se abriu, utilize a navegação entre diretórios à esquerda para encontrar o arquivo entre as pastas ou caso você ainda não tenha feito o upload da imagem para o servidor, acesse a pasta **home** e clique em **Carregar imagens** para fazer o upload da imagem a partir de sua máquina. Selecione a imagem e clique em **Add Selected** (botão laranja no canto superior direito).

![alterando imagens](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/058%20-%20%20Como%20alterar%20imagens%20de%20blocos%20estáticos/images/image4.png)

5 -> Após ter realizado esse processo você voltará para a mesma janela do tópico 3, agora clique em **OK** e pronto a imagem ja foi substituida. 

6 -> Agora para adicionar um link de redirecionamento você deve alterar o link tanto no botão,quanto na imagem, clique em cima do texto presente no botão (em nosso caso é Comprar) e depois no icone de link e depois faça o mesmo processo para a imagem.

![alterando imagens](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/058%20-%20%20Como%20alterar%20imagens%20de%20blocos%20estáticos/images/image11.png)

7 -> Na janela que se abrirá você deve inserir o link no campo **URL** e depois clique em **OK**.

8 -> Agora clique em **Salvar** no canto superior direito e siga para a próxima etapa.

9 -> Agora você deve limpar o cache da loja para as alterações sejam aplicadas, acesse **SISTEMA > FERRAMENTAS > GERENCIAMENTO DE CACHE**

![alterando imagens](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/058%20-%20%20Como%20alterar%20imagens%20de%20blocos%20estáticos/images/image6.png)

10 -> Marque as chackbox dos seguintes tipos de cache:

- **Configuration**
- **Layouts**
- **Blocks HTML output**
- **Page Cache**

10.1 -> Selecione a opção de **Atualizar** e clique em **Enviar**, pronto as alterações do slider já foram aplicadas na home de seu site.

![alterando imagens](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/058%20-%20%20Como%20alterar%20imagens%20de%20blocos%20estáticos/images/image7.png)

11 -> Na home de seu site aperte **CTRL + F5** para recarregar a página.

## Via editor de código

1 -> Após entrar no bloco estático, desça um pouco até a área de conteúdo do bloco, clique no botão **Show / Hide Editor** para transformar o conteúdo do bloco em código html.

![alterando imagens](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/058%20-%20%20Como%20alterar%20imagens%20de%20blocos%20estáticos/images/image2.png)

2 -> Por segurança copie o código e cole ele em um editor de código ou editor de texto. Após ter copiado o código desça até a última linha do bloco a aperte **Enter** 3 vezes para que fique um espaço e assim melhorar a identificação. Agora clique em **Insert Image** para iniciarmos a alteração das imagens.

![alterando imagens](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/058%20-%20%20Como%20alterar%20imagens%20de%20blocos%20estáticos/images/image3.png)

3 -> Na aba que se abriu, utilize a navegação entre diretórios à esquerda para encontrar o arquivo entre as pastas ou caso você ainda não tenha feito o upload da imagem para o servidor, acesse a pasta **home** e clique em **Carregar imagens** para fazer o upload da imagem a partir de sua máquina. Selecione a imagem e clique em **Add Selected** (botão laranja no canto superior direito).

![alterando imagens](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/058%20-%20%20Como%20alterar%20imagens%20de%20blocos%20estáticos/images/image4.png)

4 -> Note que foi adicionado um código html no final do bloco (onde você tinha deixado o mouse). Na linguagem HTML as imagens são representadas pela tag **img**, sendo assim ondem estiver a tag haverá uma imagem, dentro dessa tag existe um atributo chamado de **src** que contém o link de referência da imagem dentro do servidor. Substitua a **src** da imagem antiga pela **src** da imagem nova, após isso apague o código da imagem que criamos no final do bloco.

![alterando imagens](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/058%20-%20%20Como%20alterar%20imagens%20de%20blocos%20estáticos/images/image5.png)

5 -> Agora altere a visão do conteúdo para editor de texto clicando em **Show / Hide Editor** verifique se a imagem foi carregada, se sim pule pra próxima etapa, caso contrário provávelmente algum processo não foi executado corretamente, revise as etapas anteriores e tente novamente.

6 -> Caso você deseje alterar o link de redirecionamento, procure pelos elementos com a tag **a** e dentro desta tag procure pelo atributo **href**, você deve inserir o link entre as aspas, caso seja um link de redirecionamento interno do site, insira o link dentro do **store url**, caso contrário, exclua ele e coloque seu link inteiro dentro do href.

![alterando imagens](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/058%20-%20%20Como%20alterar%20imagens%20de%20blocos%20estáticos/images/image12.png)

7 -> Terminado clique em **Salvar** e siga para a próxima etapa.

6 -> Você deve agora limpar o cache da loja para as alterações sejam aplicadas, acesse **SISTEMA > FERRAMENTAS > GERENCIAMENTO DE CACHE**

![alterando imagens](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/058%20-%20%20Como%20alterar%20imagens%20de%20blocos%20estáticos/images/image6.png)

7 -> Marque as chackbox dos seguintes tipos de cache:

- **Configuration**
- **Layouts**
- **Blocks HTML output**
- **Page Cache**

7.1 -> Selecione a opção de **Atualizar** e clique em **Enviar**, pronto as alterações do slider já foram aplicadas na home de seu site.

![alterando imagens](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/058%20-%20%20Como%20alterar%20imagens%20de%20blocos%20estáticos/images/image7.png)

8 -> Na home de seu site aperte **CTRL + F5** para recarregar a página.

<hr>

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.