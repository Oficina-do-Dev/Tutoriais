# Como criar atributo de cor e tamanho e utiizá-los no produto configurável

1 -> Primeiro precisamos criar os atributos, para isso acesse **LOJAS > ATRIBUTOS > PRODUTO**.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/062%20-%20Como%20criar%20atributo%20de%20cor%20e%20tamanho%20e%20utilizá-los%20no%20produto%20configurável/images/image1.png)

2 -> Nesta página está localizado todos os atributos de sua loja, mas nós iremos criar um novo atributo, então clique em **Adicionar Novo Atributo**.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/062%20-%20Como%20criar%20atributo%20de%20cor%20e%20tamanho%20e%20utilizá-los%20no%20produto%20configurável/images/image2.png)

3 -> Vamos mostrar aqui apenas o processo para criar o atributo de Cor, mas o processo para criar o atributo de tamanho segue a mesma lógica. Ao entrar na página de criação do atributo:

- **Etiqueta Pré-definida:** insira o nome de seu atributo aqui. Exemplos: Cores.
- **Tipo de entrada no catálogo para o dono da loja:** aqui temos diferentes tipos de atributo para selecionarmos, para o atributo de cores selecione a opção **Swatch Visual** e para o atributo de tamanho escolha a opção de Dropdown.
- **Valores necessários:** define como obrigatório o preenchimento do atributo.
- **Atualizar a imagem de pré-visualização do produto:** utilizar o filtro por este atributo irá atualizar a imagem do produto na página de catálogo
- **Usar a imagem do produto para o Swatch se possivel:** permite o uso de lógica de fallback para substituir a imagem de amostra de acordo com a imagem de amostra ou padrão do produto

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/062%20-%20Como%20criar%20atributo%20de%20cor%20e%20tamanho%20e%20utilizá-los%20no%20produto%20configurável/images/image3.png)

4 -> Mais abaixo na área de **Gerir Amostra (valores do seu atributo)** iremos alimentar o atributo com seus valores, para adionar um novo valor basta clicar em **Adicionar Amostra**, no campo ```Admin``` você deve inserir o nome do valor que será visto por você e no campo ```Default Store View``` é o nome do valor apresentado no frontend da loja.
(No caso do atributo de tamnaho, não havera o campo ```Amostra```, apenas os dois campos de texto ao qual você deverá inserir a sigla do tamanho. Exemplo: GG, G, M).

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/062%20-%20Como%20criar%20atributo%20de%20cor%20e%20tamanho%20e%20utilizá-los%20no%20produto%20configurável/images/image4.png)

5 -> Em ```Amostra``` você irá selecionar acCor do swatch, você pode utilizar uma imagem miniatura ou utilizar o seletor de cor do magento para definir a cor, segue o exemplo abaixo:

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/062%20-%20Como%20criar%20atributo%20de%20cor%20e%20tamanho%20e%20utilizá-los%20no%20produto%20configurável/images/image5.png)

6 -> Um pouco mais abaixo encontramos as **Propriedades de Atributo Avançado** com as opções:

- **Código do Atributo:** é o código interno de intendificação do atributo, será preenchido automáticamente com base na etiqueta do atributo ou, se preferir, você pode atribuir o nome que desejar no código do atributo.
- **Escopo:** defina o escopo como global para que o atributo seja visivel em todas as visões da loja.
- **Valor único:** valores não compartilhados com outros produtos.
- **Adicionar a coluna de opções:** selecione "Sim" para adicionar esse atributo para a lista de opções de coluna na grade de produto.
- **Uso em opções de filtro:** selecione "Sim" para adicionar esse atributo para a lista de opções de filtro na grade de produto.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/062%20-%20Como%20criar%20atributo%20de%20cor%20e%20tamanho%20e%20utilizá-los%20no%20produto%20configurável/images/image6.png)

7 -> No final deste página escontramos **Extra Options** com um único campo de **Custom Frontend style** que contem 4 estilos diferentes de visualização deste atributo no site, sendo eles:

- **Default Style:** é o estilo padrão de layout do atributo conforme selecionado em tipo de entrada no catálogo para o dono da loja.
- **Slider:** atribui o efeito de slider as opções/valores do atributo.
- **Menu Suspenso:** atribui o efeito de menu suspenso/dropdown as opções/valores do atributo.
- **Check Box:** faz com que as opções/valores do atributo sejam caixas de seleção para o cliente.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/062%20-%20Como%20criar%20atributo%20de%20cor%20e%20tamanho%20e%20utilizá-los%20no%20produto%20configurável/images/image7.png)

8 -> No menu lateral esquerdo em **Gerenciar rótulos** haverá um campo e nele você deve inserir novamente o nome do atributo.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/062%20-%20Como%20criar%20atributo%20de%20cor%20e%20tamanho%20e%20utilizá-los%20no%20produto%20configurável/images/image8.png)

9 -> Em **Propriedades da Loja:** encontramos outras configurações do atributo, vamos entender cada uma delas:

- Para disponibilizar o atributo para pesquisa, defina **Usar na pesquisa** como ```Sim```.
- Para incluir o atributo na comparação de produtos, defina **Comparável na Loja** como ```Sim```.
- Para incluir atributos de lista suspensa, seleção múltipla ou preço na navegação em camadas, defina **Usar na Navegação em camadas dos resultados da pesquisa** como um dos seguintes:
    - Filtrável (com resultados).
    - Filtrável (sem resultados).
- Para usar a navegação em camadas nas páginas de resultados da pesquisa, defina **Usar na Navegação dos resultados da pesquisa** como ```Sim``` e insira um número no campo Posição.
- Para usar o atributo em regras de preço, defina **Usar para condições de regra promocional** como ```Sim```.
- Para incluir o atributo na página do produto, defina **Visível nas páginas do catálogo na loja** como ```Sim```.
- Para incluir o atributo nas listas de produtos, defina **Usado na lista de produtos** como ```Sim```.
- o Use o atributo como um parâmetro de classificação para listas de produtos, defina **Usado para classificação na lista de produtos** como ```Sim```.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/062%20-%20Como%20criar%20atributo%20de%20cor%20e%20tamanho%20e%20utilizá-los%20no%20produto%20configurável/images/image9.png)

10 -> Ao terminar clique em **Salvar Atributo**.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/062%20-%20Como%20criar%20atributo%20de%20cor%20e%20tamanho%20e%20utilizá-los%20no%20produto%20configurável/images/image10.png)

**Atenção:** Para que o atributo apareça no cadastro do produto, podemos adicionar ele no grupo padrão de atributos ou você pode adicionar este atributo diretamente no produto que você esta criando. Se você deseja utilizar a segunda opção, pule para a etapa 15.

12 -> Para adicionar um atributo ao grupo padrão de atributos do magento é muito facil, acesse **LOJAS > ATRIBUTOS > CONJUNTO DE ATRIBUTOS** e clique em **Padrão**.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/062%20-%20Como%20criar%20atributo%20de%20cor%20e%20tamanho%20e%20utilizá-los%20no%20produto%20configurável/images/image13.png)

13 -> Agora é só clicar no atributo que você criou (ele estará na seção à direita da página) e arrastá-lo para a posição de sua preferência dentro do cojunto de grupos de atributos.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/062%20-%20Como%20criar%20atributo%20de%20cor%20e%20tamanho%20e%20utilizá-los%20no%20produto%20configurável/images/image14.png)

14 -> Após isto, basta clicar em **Salvar** e ir para o produto.

15 -> Acesse **CATÁLOGO > iNVENTÁRIO > PRODUTOS**.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/062%20-%20Como%20criar%20atributo%20de%20cor%20e%20tamanho%20e%20utilizá-los%20no%20produto%20configurável/images/image11.png)

16 -> Na página dos produtos clique no ícone ao lado do botão de **Adicionar produto**, um dropdown aparecerá com diferentes opções de produtos, a opção que vamos utilizar é a de **Configurable Product**.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/062%20-%20Como%20criar%20atributo%20de%20cor%20e%20tamanho%20e%20utilizá-los%20no%20produto%20configurável/images/image12.png)

17 -> Agora siga o processo comum do cadastro de produto configurável, caso você não saiba como criar um produto configurável, veja este <a href="https://github.com/Oficina-do-Dev/Tutoriais/tree/main/Magento_2/005%20-%20Como%20cadastrar%20produto%20configurável">Tutorial de cadastro de produto configurável</a>, os atributos que criamos já estão disponíveis para serem usados no cadastro dos produtos.

<hr>

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.