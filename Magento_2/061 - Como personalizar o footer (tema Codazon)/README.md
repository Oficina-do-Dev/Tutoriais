# Como personalizar o footer do tema Codazon

1 -> Primeiramente faça login no painel Magento e acesse **CONTEÚDO > ELEMENTOS > BLOCOS**.

![personalizando o footer](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/061%20-%20Como%20personalizar%20o%20footer%20(tema%20Codazon)/images/image1.png)

2 -> Agora procure pelo bloco estático do footer de seu tema e clique **Selecione** e depois em **Editar**.

3 -> Depois de entrar no bloco, desça a página até a área de conteúdo do bloco estático, por segurança faça backup do conteúdo do bloco, clique em **Show / Hide Editor** trocando a visão para código e copie o conteúdo e cole em algum arquivo como backup.

4 -> Há duas maneiras de personalizar o footer, pelo editor de texto e pelo editor de código, vamos agora aprender os dois métodos. 

![personalizando o footer](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/061%20-%20Como%20personalizar%20o%20footer%20(tema%20Codazon)/images/image2.png)

## Via editor de texto

1 -> Para inserir um Link ou texto no footer é bem simples, basta saber em qual coluna você deseja inserir o texto, coloque o mouse no ultimo item daquela coluna e aperte **Enter** para descer uma linha, por padrão a formatação será puxada. Se for um texto comum basta escrever normalmente, se for um texto com link basta escreve-lo e depois selecioná-lo, depois clique no ícone mostrado abaixo.

![personalizando o footer](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/061%20-%20Como%20personalizar%20o%20footer%20(tema%20Codazon)/images/image3.png)

2 -> Ao clicar no ícone esta janela se abrirá, insira o link em **URL**, caso você deseje que o link seja aberto em uma nova guia no navegador do cliente basta ir em **Target** e mudar a opção para **New Window**

![personalizando o footer](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/061%20-%20Como%20personalizar%20o%20footer%20(tema%20Codazon)/images/image4.png)

3 -> Depois que terminar clique em **Salvar** e pronto.

## Via editor de código

1 -> Recomendamos quue você utilize um editor de códigos externo para realizar quaisquer alterações no conteúdo do bloco estático, poís caso algum problema aconteça basta retornar as alterações utilizando o CTRL + Z e tudo certo.

2 -> Após ter copiado o código do conteúdo e colado em um editor de código externo, identifique os elementos e colunas aos quais você deseja inserir alguma informação.

3 -> Para inserir apenas uma informação em texto simples utilize este código ```<p class="hidden-xs">SEU TEXTO AQUI</p>```, a tag **p** significa paragrafo, sendo a tag utilizada para textos simples.

4 -> Para inserir um texto com link você deve primeiro identificar se o lugar em que você vai inserir esta informação faz parte de uma lista desordenada ```<ul></ul>```, se sim basta adicionar a tag ``` <a href="SEU LINK AQUI">SEU TEXTO AQUI</a>``` dentro da tag ```<li></li>```, caso contrário insira apenas a tag **a**.

5 -> Caso você vá utlizar um link interno de redirecionamento, insira o código identificador da página ou da categoria dentro de ```{{store url='SEU LINK AQUI'}}``` e depois coloque este conjunto todo dentro do atributo **href=""** da tag **a**.

6 -> Se você desejar que o link seja aberto em outra guia do navegador, inclua este código dentro da tag **a** ```target="_blank"``` e pronto.

7 -> Clique em **Salvar** e vá até uma página e aperte CTRL + F5 para visualizar a alteração.

<hr>

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.