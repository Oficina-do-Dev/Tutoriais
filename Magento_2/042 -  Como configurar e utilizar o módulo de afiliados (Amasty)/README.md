# Como configurar e utlizar o módulo de afiliados da Amasty

## Para que serve o módulo de Afilidados?

O módulo de afiliados para Magento 2 permite que os administradores de lojas executem programas de afiliados com todos os recursos para conduzir com eficácia vendas de canais adicionais. Devido ao módulo, os administradores serão capazes de fornecer materiais aos afiliados com promoções prontas para uso e relatórios de estatísticas detalhados. Configurações claras garantem afiliação fácil gerenciamento de contas, permite que os administradores da loja regulem as comissões e rastreiem as retiradas.

- Execute vários programas de afiliados ao mesmo tempo.
- Configure as comissões para cada programa específico.
- Configurar descontos e requisitos de pagamento.
- Faça upload de materiais promocionais com facilidade.
- Gerenciar contas e transações de afiliados.

## Como configurá-lo ?

1 -> Primeiramente abra **LOJAS > CONFIGURAÇÕES > AMASTY EXTENSIONS > AFILIADO**.

2 -> Configurando o Módulo - **Configurações Gerais**:

- **Adicionar link de afiliado ao rodapé:** habilite esta opção para adicionar um link para a página de destino do afiliado ao seu rodapé da loja.
- **Expiração do cookie (dias):** especifique um período de expiração do cookie personalizado. Por padrão, é definido como 365 dias. Isso significa que quando um cliente chega ao site de um editor usando um link de afiliado, a loja página cria um cookie. Se um visitante referido chega ao seu site usando um link de afiliado e preenche qualquer pedido dentro de 365 dias, ele (ela) receberá um desconto e o afiliado receberá uma comissão. Após neste período o afiliado não ganhará nenhuma comissão, um cliente indicado não terá desconto.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image1.png)

3 -> Configurando o Módulo - **Conta**:

- **Marcado “Notificações de e-mail” por padrão:** Se a opção estiver habilitada, o “Notificações de e-mail" a inscrição será verificada automaticamente na conta do afiliado.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image2.png)

4 -> Configurando o Módulo - **URL Afiliado**:

- **URL geral do afiliado:** especifique o texto personalizado que substituirá amasty_affiliate no URL do conta de cliente.

- **Parâmetro do cliente:**  especifique o código que será usado em URLs como:? C = 123

- **Comprimento do código de afiliado:** O código deve conter de 4 a 31 símbolos. '10' é definido por padrão.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image3.png)

5 -> Configurando o Módulo - **Fluxo de Trabalho de Comissão**:

- **Adicionar Comissão ao Status do Pedido Obitido:** escolha o status do pedido que irá acionar a adição para o afiliados.

- **Subtrair a comissão quando o pedido for obtido:** escolha o status do pedido que será acionado subtração de comissão.

- **Subtrair a comissão quando o Creditmemo for criado:** habilite esta opção para pagamento por venda programas somente quando um Creditmemo é criado.

- **Período de retenção da comissão (dias):** especifique o período de retenção da comissão após o qual será adicionada ao saldo do afiliado. Enquanto a comissão está em espera, ela não pode ser usada para pedidos de retirada.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image4.png)

6 -> Configurando o Módulo - **Configurações de retirada**:

- **Valor mínimo de retirada:** defina o valor mínimo que pode ser solicitado por um afiliado dentro de um pedido. Por exemplo. se o valor for igual a 50, os afiliados não podem solicitar saques inferiores a quantidade especificada.

- **O saldo mínimo “disponível” para solicitar saque:** se o saldo de um afiliado for inferior ao valor especificado, ele/ela não poderá solicitar nenhum saque.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image5.png)

7 -> Configurando o Módulo - **Notificações por email**:

Nesta seção, você pode ativar facilmente diferentes tipos de notificação por e-mail para afiliados e administradores. Se você deseja editar modelos prontos para uso ou criar um novo, vá para **MARKETING > COMUNICAÇÕES > MODELOS DE EMAIL**.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image6.png)

8 -> Configurando o Módulo - **Indique amigos**:

- **Adicionar este ID de conta:** o ra-5968d339b0751a2f é usado apenas para fins de teste, então clique no link da descrição para criar uma cheve própria

- **Conteúdo da página de referência de amigos:** especifique um texto personalizado que será exibido na  página de conta do afiliado na guia correspondente.

- **Conteúdo da página de fontes de tráfego:** especifique um texto personalizado que será exibido na página de conta do cliente para a guia 'Fontes de tráfego'.

- **Habilitar na página de lista de produtos / Habilitar na página de detalhes do produto / Habilitar em minha conta / Menu de afiliados:** todas essas configurações são usadas para exibir os botões sociais para afiliados registrados em páginas da loja.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image7.png)

9 -> Configurando o Módulo - **Termos e Condições**:

- **Caixa de Seleção de Texto:** a caixa de seleção dos Termos e Condições é exibida na página de registro na conta do afiliado. Aqui você pode especificar um texto personalizado que será colocado com a caixa de seleção.

- **A caixa de seleção está marcada por padrão:** escolha se a caixa de seleção dos Termos e Condições será marcada por padrão.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image8.png)

## Gerenciando os programas de afiliados.

1 -> Para editar ou criar programas de afiliados, vá para **MARKETING > AFILIADO > GERENCIAR PROGRAMAS**.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image9.png)

2 -> Nesta página você consegue visualizar todos os programas de afiliados, sendo possível também visualizar os detalhes de cada programa específico. Para adicionar um novo programa clique no botão **Adicionar novo programa**.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image10.png)

3 -> Criando um programa de afiliado - **Informações gerais**:

- **Nome do programa:** especifique um nome de programa que será usado no painel de administração, bem como mostrado em uma conta de afiliado.

- **Situação:** habilita/desabilita o programa.

- **Regra de preço do carrinho de compras:** o módulo usa as regras de preço padrão do carrinho de compras Magento para permitir você define descontos para clientes de referência. É possível usar uma regra diferente para cada novo programa de afiliados. Você pode usar e editar a regra padrão ou criar uma nova. Preste atenção que apenas essas regras estarão disponíveis, onde a opção **Cupom** é definida para **Cupom Específico** e o **Gerar automáticamente** está habilitada.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image11.png)

4 -> Criando um programa de afiliado - **Configuração de Comissão**:

- **Comissão de Pagamento:** o módulo oferece duas variantes de comissão
  - **Pagar por venda** - um afiliado receberá uma comissão por cada pedido feito por sua indicação.
  - **Pagar por Lucro** - um afiliado receberá uma comissão sobre o valor do pedido específico. Sendo assim, você precisa especificar a configuração da Comissão de pagamento do valor. Por exemplo. Se uma quantia de comissão paga é igual a R$ 500, o afiliado receberá a comissão apenas quando o total do valor dos pedidos torna-se igual ou superior a R$ 500.

- **Tipo de comissão:** use o tipo de comissão Porcentagem ou Fixo.

- **Valor da comissão:** especifique o valor da comissão.

- **Use uma comissão diferente de 2ª ordem de um cliente:** o módulo permite especificar uma comissão diferente a partir da 2ª encomenda efetuada por referência. Esta opção está disponível para apenas para o tipo Pagar por venda.

- **Continue pagando comissões ao primeiro afiliado:** se a opção estiver ativada, quando um cliente for comprar o primeiro produto usando o link do afiliado A, mas depois faz compras usando os links do afiliado B, a transação ainda será contada para o afiliado A.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image12.png)

5 -> Criando um programa de afiliado - **Clientes e grupos de clientes**

- **Grupo de clientes:** escolha o grupo de clientes principal, ao qual o programa afiliado recém-criado vai ser aplicada.

- **IDs de cliente:** insira os IDs de clientes específicos que você deseja permitir que usem este programa. Nesso campo, você precisa inserir os IDs manualmente uu usar o botão **Adicionar clientes** para abrir uma janela pop-up com uma lista de todos os clientes.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image13.png)

## Gerenciando contas de afiliados

Todos os clientes existentes têm a oportunidade de criar contas de afiliados. Em primeiro lugar, um cliente em sua conta de cliente deve ir para a guia Configurações do afiliado e concordar com Termos e Condições.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image15.png)

Lembre-se de que você pode criar contas de afiliados na grade somente após o cliente concordar com termos e condições em sua conta de cliente. 

1 -> Para criar uma nova conta de afiliado a partir do painel de administração ou para gerenciar as já existentes, vá para **MARKETING > AFILIADO > GERENCIAR CONTAS**.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image14.png)

2 -> Para adicionar uma nova conta, clique no botão **Adicionar conta** no canto superior direito e para ver os detalhes de um afiliado específico, clique no link **Editar** do afiliado correspondente na grade.

3 -> Aqui o processo de criação de afiliado é o mesmo de criação de cliente comum, preencha os campos com as dados do cliente e clique em **Salvar** no canto superior direito.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image16.png)

## Gerenciando Banners

1 -> Para gerenciar banners de afiliados ou criar um novo, vá para **MARKETING > AFILIADO > GERENCIAR BANNERS**.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image17.png)

2 -> Na página Gerenciar Banners, você pode editar os banners já criados ou clicar no botão **Adicionar Banner** para fazer upload de um novo.

3 -> Na página Configurações de banner, você pode fazer upload de uma imagem de banner (para o tipo de imagem) ou especificar um texto promocional (para o tipo de texto).

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image18.png)

4 -> Clique no botão **Salvar** no canto superior direito quando terminar.

## Gerenciando Transações

1 -> Para gerenciar transações de afiliados, vá para **MARKETING > AFILIADO > GERENCIAR TRANSAÇÕES**.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image19.png)

2 -> Na página de Gerenciar transações, você pode ver todas as transações afiliadas. Para ver os detalhes de qualquer transação específica, basta clicar no link **Visualizar**.

## Gerenciando Retiradas

1 -> Para gerenciar retiradas, vá para **MARKETING > AFILIADO > GERENCIAR RETIRADAS**.

![modulo de afiliado Amasty](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/042%20-%20%20Como%20configurar%20e%20utilizar%20o%20módulo%20de%20afiliados%20(Amasty)/images/image20.png)

2 -> O módulo não possui nenhum sistema de pagamento embutido, ele apenas rastreia e exibe detalhes de saque. Portanto, as comissões de afiliados são pagas com a ajuda de quaisquer métodos ou serviços 3-d escolhidos pelos administradores da loja.

3 -> Para pagar a comissão do afiliado clique no link **Editar** no canto direito e depois no botão **Pagar** no canto superior direito da tela.

<hr>

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.