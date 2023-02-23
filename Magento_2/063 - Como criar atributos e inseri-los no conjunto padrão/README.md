# Criando Atributos e os inserindo no Conjunto de Atributos

1 -> Para criar um novo atributo, primeiramente abra o painel lateral de seu Magento e acesse **LOJAS > ATRIBUTOS > PRODUTO**.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/063%20-%20Como%20criar%20atributos%20e%20inseri-los%20no%20conjunto%20padrão/images/image1.png)

2 -> Tendo feito isso, nessa nova página clique em **Adicionar Novo Atributo** .

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/063%20-%20Como%20criar%20atributos%20e%20inseri-los%20no%20conjunto%20padrão/images/image2.png)

3 -> Agora, insira o nome do atributo em **Etiqueta Pré-definida**.

3.1-> Em **Tipo de entrada no catálogo para o dono da loja** adicione o tipo de atributo que será exibido na página do produto.

Temos as seguintes opções:

- **Text Field**: campo de texto comum.
- **Text Area** : campo de texto expansivel.
- **Text Editor**: campo de edição de texto, com barra de tarefas.
- **Date**: É um calendário.
- **Date and Time**: calendário com opções de tempo.
- **Yes/No**: interrupitor sim e não.
- **Multiple Select**: multiplas opções de seleção.
- **Dropdown**: É um menu que ao clicarmos tornará visivel mais opções de seleção de itens.
- **Preço**: Nada mais é que o atributo de preço do produto.
- **Midia de imagem:** adiciona a opção de upload de uma imagem.
- **Swatch Visual**: É parecido com dropdown, porém no Swatch Visual podemos ter, por exemplo, uma imagem de miniatura em cada opção ou selecionar uma cor.
- **Amostra de Texto**:  Também é parecido com um menu dropdown, porém nele guardamos frases(pequenos textos).
- **Imposto Fixo do Produto**: atributo de preço para o imposto sobre o produto.

**Importante:** dependendo do tipo de atributo que você escolher mais opções aparecerão logo abaixo, algumas precisam de opções com valores como por exemplo o swatch de imagem ou dropdown.

3.2 -> Em **Valores necessários**, podemos deixar como **Sim** caso o valor do atributo seja obrigatório ou como **Não** caso não seja obrigatório.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/063%20-%20Como%20criar%20atributos%20e%20inseri-los%20no%20conjunto%20padrão/images/image3.png)

4 -> Na seção **Propriedades de Atributo Avançado** temos as seguintes configurações:

- **Código do Atributo:** é o código interno de intendificação do atributo, será preenchido automáticamente com base na etiqueta do atributo ou, se preferir, você pode atribuir o nome que desejar no código do atributo.
- **Escopo:** defina o escopo como global para que o atributo seja visivel em todas as visões da loja.
- **Valor Padrão:** definimos o valor que aparecerá como padrão quando a página for carregada. 
- **Valor Único:** valores não compartilhados com outros produtos.
- **Adicionar a coluna de opções:** selecione "Sim" para adicionar esse atributo para a lista de opções de coluna na grade de produto.
- **Uso em opções de filtro:** selecione "Sim" para adicionar esse atributo para a lista de opções de filtro na grade de produto.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/063%20-%20Como%20criar%20atributos%20e%20inseri-los%20no%20conjunto%20padrão/images/image4.png)

5 -> No final deste página escontramos **Extra Options** com um único campo de **Custom Frontend style** que contem 4 estilos diferentes de visualização deste atributo no site, sendo eles:

- **Default Style:** é o estilo padrão de layout do atributo conforme selecionado em tipo de entrada no catálogo para o dono da loja.
- **Slider:** atribui o efeito de slider as opções/valores do atributo.
- **Menu Suspenso:** atribui o efeito de menu suspenso/dropdown as opções/valores do atributo.
- **Check Box:** faz com que as opções/valores do atributo sejam caixas de seleção para o cliente.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/063%20-%20Como%20criar%20atributos%20e%20inseri-los%20no%20conjunto%20padrão/images/image5.png)

5 -> No menu lateral esquerdo clique sobre **Gerenciar rótulos**, é onde você altera o rótulo que irá aparecer na sua loja, caso você não preencha, o rótulo que será utilizado é o do campo **Etiqueta Pré-definida**(nome do atributo).

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/063%20-%20Como%20criar%20atributos%20e%20inseri-los%20no%20conjunto%20padrão/images/image6.png)

6 -> Agora vamos em **Propriedades da loja**, clique sobre e você verá as seguintes opções.

- **Uso em Pesquisa:** é onde habilitamos o produto para ser pesquisável, marque essa opção como sim e mais duas opções aparecerão, que são **Peso da Pesquisa** e **Visível na pesquisa avançada**. 
- **Peso da Pesquisa:** quanto maior, mais fácil será de encontrar o produto.
- **Visível na pesquisa avançada:** a pesquisa avançada é uma pesquisa com mais detalhes que a pesquisa normal.
- **Comparável na Loja:** esta opção habilita o atributo para ser exibido nas compações de produtos.
- **Utilizar em Navegação por Camadas:** habilita o campo para ser exibido nos filtros laterais das listagens(Por exemplo: página de categoria).
- **Usar nos Resultados de Pesquisa na Navegação de Camadas:** o atributo é exibido nas páginas de busca.
- **Posição:** posição do atributo no bloco de navegação em camadas.
- **Uso para condições de regra de Promoções**, habilita o atributo para ser utilizado como opção de condição em regras de promoção.
- **Permitir Tags HTML na loja:** Para permitir que o texto seja formatado com HTML, defina Permitir tags HTML na vitrine como Sim.
- **Visível nas páginas do catálogo na loja:** Habilita o atributo para ser exibido nas páginas dos produtos.
- **Usado na listagem de produtos:** Os atributos apareçam na listagem, geralmente no topo ou na lateral esquerda(depende do design do tema).
- **Usado para ordenação na listagem de produtos:** habilita o atributo para ser exibido nas configurações de ordenação das listagens, caso esteja como **Sim**, o atributo será exibido no campo **Ordenar por** nas páginas de categorias.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/063%20-%20Como%20criar%20atributos%20e%20inseri-los%20no%20conjunto%20padrão/images/image7.png)

7 -> Após terminar de configurar clique no botão laranja **Salvar Atributo** que fica no canto superior direito.

8 -> Agora temos que adicionar o atributo no conjunto padrão do Magento e é muito facil, acesse **LOJAS > ATRIBUTOS > CONJUNTO DE ATRIBUTOS** e clique em **Padrão**.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/063%20-%20Como%20criar%20atributos%20e%20inseri-los%20no%20conjunto%20padrão/images/image8.png)

13 -> Agora é só clicar no atributo que você criou (ele estará na seção à direita da página) e arrastá-lo para a posição de sua preferência dentro do cojunto de grupos de atributos.

![criando os atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/063%20-%20Como%20criar%20atributos%20e%20inseri-los%20no%20conjunto%20padrão/images/image9.png)

14 -> Pronto agora o seu atributo faz parte do conjunto de atributos padrão do Magento.

<hr>

### Dúvidas/Suporte: 
Entre em contato com o nosso departamento de suporte. 