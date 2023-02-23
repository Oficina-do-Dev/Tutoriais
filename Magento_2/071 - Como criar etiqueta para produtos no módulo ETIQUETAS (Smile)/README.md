# Como criar etiqueta para produto usando o módulo ETIQUETAS (SMILE)

## Requisitos

É importante que você saiba como criar um atributo e também inserir as opções para o atributo, caso contrário siga o tutorial abaixo:

- <a href="https://github.com/Oficina-do-Dev/Tutoriais/tree/main/Magento_2/063%20-%20Como%20criar%20atributos%20e%20inseri-los%20no%20conjunto%20padr%C3%A3o">Tutorial de como criar um atributo</a>

Para que você possa selecionar mais de uma opção é recomendável que seu atributo seja do tipo *Multipla Seleção* ou *Multiple Select* a depender da tradução do seu Magento, as propriedades do atributo podem seguir o padrão abaixo:


![padrão do atributo](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/071%20-%20Como%20criar%20etiqueta%20para%20produtos%20no%20m%C3%B3dulo%20ETIQUETAS%20(Smile)/images/1-padraodoatributo.png)


No exemplo abaixo iremos ilustrar o atributo já criado (código: label) e com algumas opções já inseridas, iremos abordar desde a etapa de inserção de demais opções até a seleção no produto e a visualização na grid e visão individual do produto.

## Criando opções do atributo

1 -> Primeiramente faça login no painel do Magento.

2 -> Acesse a listagem de atributos em *LOJAS > ATRIBUTOS > PRODUTO*.

![atributos](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/071%20-%20Como%20criar%20etiqueta%20para%20produtos%20no%20m%C3%B3dulo%20ETIQUETAS%20(Smile)/images/2-atributoproduto.png)

3 -> Na listagem filtre o código *label*.

![label](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/071%20-%20Como%20criar%20etiqueta%20para%20produtos%20no%20m%C3%B3dulo%20ETIQUETAS%20(Smile)/images/3-label.png) 

4 -> Acesse o atributo e na *Propriedades* localize a opção *Gerenciar opções*, clique em *Adicionar opção* localizado no canto inferior esquerdo.

![adicionar opção](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/071%20-%20Como%20criar%20etiqueta%20para%20produtos%20no%20m%C3%B3dulo%20ETIQUETAS%20(Smile)/images/4-adicionaropcao.png)

5 -> Insira a opção desejada preenchendo as colunas Administrador e Frente de Loja Padrão, caso precisar inserir mais de uma opção repita o processo. Finalizando a inserção clique no botão *Salvar Atributo* localizado no canto superior direito.

![adicionar opção](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/071%20-%20Como%20criar%20etiqueta%20para%20produtos%20no%20m%C3%B3dulo%20ETIQUETAS%20(Smile)/images/5-salvaratributo.png)


## Criando a etiqueta

6 -> No menu lateral do Magento, clique em *MARKETING > ETIQUETAS (SMILE) > ATRIBUTOS*.

![etiquetas](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/071%20-%20Como%20criar%20etiqueta%20para%20produtos%20no%20m%C3%B3dulo%20ETIQUETAS%20(Smile)/images/6-etiquetas.png)

7 -> Nesta tela clique em *Adicionar nova etiqueta* localizado no canto superior direito.

![adicionar etiqueta](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/071%20-%20Como%20criar%20etiqueta%20para%20produtos%20no%20m%C3%B3dulo%20ETIQUETAS%20(Smile)/images/7-adicionaretiqueta.png)

8 -> Na tela que se abrir vão aparecer todas as opções e locais que você deve inserir as informações, conforme pode ver abaixo,

![opcoes de etiqueta](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/071%20-%20Como%20criar%20etiqueta%20para%20produtos%20no%20m%C3%B3dulo%20ETIQUETAS%20(Smile)/images/8-opcoes.png)

9 -> Segue explicação de cada etapa:

- *Habilitar etiqueta* > Caso SIM a etiqueta estará disponível para utilização,
- *Nome* > Nome dado para esta etiqueta em especifico,
- *Atributo* > Qual atributo você irá utilizar para esta seleção,
- *Opção* > Será a opção do atributo vinculado para que exiba a etiqueta,
- *Visão de Loja* > Em qual ou quais visões de loja deve aparecer a etiqueta,
- *Imagem da etiqueta* > A etiqueta a qual você irá utilizar, é interessante seguir um padrão (Exemplo: 40x40px),
- *Localização da imagem no modo de listagem* > Posição que a etiqueta ficará na visualização de grid,
- *Localização da imagem na visualização do produto* > Posição que a etiqueta ficará na visão individual do produto,
- *Exibir em* > Neste você deve selecionar em quais visualizações a etiqueta deve aparecer
- *Texto alternativo para a etiqueta* > Quando posicionar o mouse sobre o icone é o texto que irá aparecer para o cliente.

10 -> Vamos a um exemplo prático para posterior utilização, veja abaixo,

![exemplo](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/071%20-%20Como%20criar%20etiqueta%20para%20produtos%20no%20m%C3%B3dulo%20ETIQUETAS%20(Smile)/images/10-exemplo.png)

11 -> Finalizado as inserções e seleções clique no botão *Salvar Etiqueta* localizado no canto superior direito,

![salvar etiqueta](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/071%20-%20Como%20criar%20etiqueta%20para%20produtos%20no%20m%C3%B3dulo%20ETIQUETAS%20(Smile)/images/11-salvar.png)

12 -> Pronto, sua etiqueta já foi criada, agora resta apenas a seleção no produto.

## Vinculando o produto na etiqueta

13 -> No painel Magento, navegue até *CATALOGO > PRODUTOS*,

![catalogo](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/071%20-%20Como%20criar%20etiqueta%20para%20produtos%20no%20m%C3%B3dulo%20ETIQUETAS%20(Smile)/images/13-catalogoprodutos.png)

14 -> No filtro busque o produto ao qual você deseja vincular a etiqueta, em nosso exemplo usaremos a RAQUETE P/ MOSQUITO RECARRE. HARM9901,

![raquete](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/071%20-%20Como%20criar%20etiqueta%20para%20produtos%20no%20m%C3%B3dulo%20ETIQUETAS%20(Smile)/images/14-filtroproduto.png)

15 -> Acesse o produto, e localize o atributo *Etiqueta* (usado neste tutorial),

![atributo etiqueta](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/071%20-%20Como%20criar%20etiqueta%20para%20produtos%20no%20m%C3%B3dulo%20ETIQUETAS%20(Smile)/images/1-padraodoatributo.png)
15-atributoselecao.png

16 -> Selecione a opção desejada, 

Em nosso exemplo será a opção USB, porém como o atributo é do tipo Multipla Seleção você pode selecionar varias opções.

![selecionar opcao](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/071%20-%20Como%20criar%20etiqueta%20para%20produtos%20no%20m%C3%B3dulo%20ETIQUETAS%20(Smile)/images/16-salvaropcao.png)

17 -> Em seguida clique em SALVAR, localizado no canto superior direito.

![botao salvar](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/071%20-%20Como%20criar%20etiqueta%20para%20produtos%20no%20m%C3%B3dulo%20ETIQUETAS%20(Smile)/images/17-botaosalvar.png)

18 -> Antes x Resultado esperado:

![visualizacao grid antes](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/071%20-%20Como%20criar%20etiqueta%20para%20produtos%20no%20m%C3%B3dulo%20ETIQUETAS%20(Smile)/images/18-antes.png)

![visualizacao grid depois](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/071%20-%20Como%20criar%20etiqueta%20para%20produtos%20no%20m%C3%B3dulo%20ETIQUETAS%20(Smile)/images/18-depois.png)

## Dicas e possíveis problemas

- Siga o padrão no tamanho dos ícones e de preferencia sem fundo (.PNG),
- Limite a no máximo 4 ícones por produto para que não fique uma visualização poluída,
- O texto de apoio ao ícone deve auxiliar o usuário a entender o produto,
- Você pode editar a qualquer momento a imagem e qualquer informação da etiqueta,

Selecionei a etiqueta no produto mais não aparece na visão cliente:

- Cache ou indice ainda não renovado, aguardar.
- Cache externo (CloudFlare e/ou Varnish) ainda não renovado, aguardar.
- Configuração da etiqueta incorreta, convém verificar seguindo o tutorial acima.

A imagem da etiqueta só aparece se acessado a visão individual do produto:

- Provavelmente a configuração da etiqueta está incorreta, convém verififcar
- Possui cache para o catálogo ou página inicial da loja, aguardar atualização.

Selecionei a etiqueta errada no produto:

- Você pode acessar o produto e editar a seleção e/ou removendo a seleção da etiqueta.

Posso criar mais opções de etiqueta ?

- Sim, não existe limite quanto a criação, porém conforme dito acima recomenda-se prudência ao selecionar no produto para não criar uma poluição visual na visão cliente.

<hr>

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.