# Como vincular vídeos do Youtube nos Produtos.

1 -> Primeiramente você deve acessar o <a href="https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbmRFazlWNzVGLUlzRV9XM0o5ZWhUUENXQnExd3xBQ3Jtc0trXy1oOGVtcUhUWHNfRWktdE5EZ1R4MExQN3labHVnOHZWR0Z0ZjRSTHJ2R3NQT2g2UXZoaG91cEphdTVoc05famxpTUtJYmI5VERkd1Mtd01GODhYakFtdHJsUkx0eGpkZWtaV0xOY1VodW1RajJ2SQ&q=https%3A%2F%2Fconsole.developers.google.com%2Fapis%2Fdashboard&v=YNK6xteVvek" target="_blank">Google Developer</a> e criar um novo projeto caso você não tenha um.

![api do google YT](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/094%20-%20Como%20vincular%20videos%20do%20Youtube%20aos%20produtos/images/image1.png)

2 -> Criado o projeto da loja clique em **Credenciais**.

![api do google YT](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/094%20-%20Como%20vincular%20videos%20do%20Youtube%20aos%20produtos/images/image2.png)

3 -> Agora clique em **CRIAR CREDENCIAIS** e depois em **Chave de API**.

![api do google YT](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/094%20-%20Como%20vincular%20videos%20do%20Youtube%20aos%20produtos/images/image3.png)

4 -> O Google então irá criar para você a sua chave de integração de API, no popup que aparecerá copie e salve sua chave API, caso você feche sem querer a janela basta clicar em **EXIBIR CHAVE** para poder ter acesso a chave novamente.

![api do google YT](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/094%20-%20Como%20vincular%20videos%20do%20Youtube%20aos%20produtos/images/image4.png)

5 -> Agora no menu lateral esquerdo clique em **Biblioteca** e procure pela seção do YouTube e clique na opção **YouTube Data API v3**.

![api do google YT](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/094%20-%20Como%20vincular%20videos%20do%20Youtube%20aos%20produtos/images/image5.png)

6 -> Clique em **Ativar** e agora vamos para o Magento.

![api do google YT](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/094%20-%20Como%20vincular%20videos%20do%20Youtube%20aos%20produtos/images/image6.png)

7 -> No painel do Magento vá para **LOJAS > CONFIGURAÇÃO**.

![api do google YT](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/094%20-%20Como%20vincular%20videos%20do%20Youtube%20aos%20produtos/images/image7.png)

8 -> Abra agora **Catálogo > Catálogo** e clique para abrir a aba **Vídeo do Produto**, no campo **Chave de API do YouTube** insira a chave que criamos no Google.

![api do google YT](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/094%20-%20Como%20vincular%20videos%20do%20Youtube%20aos%20produtos/images/image8.png)

9 -> Pronto agora você já consegue vincular videos do YouTube em seu produto, para isso acesse **CATALOGO > PRODUTOS** e escolha o produto em que você deseje adicionar o video.

10 -> Na seção Imagens e Vídeos clique em **Adicionar video**.

![api do google YT](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/094%20-%20Como%20vincular%20videos%20do%20Youtube%20aos%20produtos/images/image9.png)

11 -> Agora insira no campo **URL** o link do video e o Magento irá puxar automáticamente o restante das informações, você pode alterar estas informações se necessário.

![api do google YT](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/094%20-%20Como%20vincular%20videos%20do%20Youtube%20aos%20produtos/images/image10.png)

12 -> Clique em Salvar no canto superior direito para salvar o video no produto e depois salve a alteração do produto, espere alguns minitos para que o CRON execute o reindex das informações e limpeza do cache e você já conseguirá visualizar o video na página do produto.

![api do google YT](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/094%20-%20Como%20vincular%20videos%20do%20Youtube%20aos%20produtos/images/image11.png)

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.