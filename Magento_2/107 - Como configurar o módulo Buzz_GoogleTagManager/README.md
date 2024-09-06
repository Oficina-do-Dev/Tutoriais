# 107 - Como configurar o módulo Buzz_GoogleTagManager

1 -> Primeiramente, você precisa ter o acesso ao GTM (Google Tag Manager) e sua conta já precisa ter sido previamente criada e configurada, feito esta etapa pode avançar, caso contrário contate o suporte.

2 -> Após avançar com a etapa 1, acesse o painel do Magento e acesse **LOJAS > CONFIGURAÇÕES > BUZZ > GTM - Google Tag Manager**.

3 -> Selecione a opção:

    HABILITADO >> SIM

![Habilitado](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image2.png)    

4 -> Você irá notar que vai aparecer dois campos de texto, sendo eles: **Código Javascript do Google Tag Manager** e **Código Non-JS do Google Tag Manager** 

![Configuração](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image3.png)    

5 -> Você precisa inserir nestes respectivos campos o código fornecido durante a criação da sua conta do GTM, segue abaixo o exemplo:

**Código Javascript do Google Tag Manager:**

    <script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
    new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
    j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
    'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
    })(window,document,'script','dataLayer','GTM-T6HX97XJ');</script>

**Código Non-JS do Google Tag Manager**

    <noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-T6HX97XJ"
    height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>

6 -> Agora você deve selecionar as demais opções conforme sua necessidade, os textos são auto-explicativos e existem dicas abaixo de cada opção para facilitar na compreensão.

**OBS:** Você pode selecionar atributos personalizados para que sejam mapeados, todos ficam na mesma sessão de configuração.

7 -> Posteriormente você deve navegar até a sessão **Configuração da API do GTM**, nele você deve inserir:

**ID da conta:** Você pode capturar acessando a sua página inicial do GTM (print abaixo é explicativo),
**ID do container:** Você pode capturar acessando a sua página inicial do GTM (print abaixo é explicativo),
**ID de Medição:** É sua TAG do GTM,

![Como localizar informacoes](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image1.png)

8 -> Você pode preencher as informações da sessão **Rastreamento de Conversão do Google Ads** caso queira, tal sessão é dedicada especialmente ao Google Ads,

9 -> **Remarketing do Google Ads** como o nome diz é uma sessão dedicada especificamente ao remarketing,

10 -> Depois de preencher todas as informações necessárias, clique em **GRAVAR CONFIGURAÇÃO/SALVAR**, como é uma ferramenta para mensurar o tráfego e auxiliar em campanhas não existe resultado visual, porém ela habilitada você pode validar o funcionamento acessando o console do navegador e digitando:

    datalayer

Irá exibir alguns resultados que podem auxiliar no traqueamento/acompanhamento das compras, navegabilidade e acesso dos seus produtos.

**Sem efetuar login:**

![datalayer sem login](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image4.png)

**Quando efetuar login:**

![datalayer com login](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/107%20-%20Como%20configurar%20o%20m%C3%B3dulo%20Buzz_GoogleTagManager/images/image5.png)

**OBS:** caso quiser, você pode clicar em **Opções de Exportação Json** e depois em **Gerar Json para Variáveis, Gatilhos e Tags** para exportar o Json e enviar a sua equipe de marketing digital.

<hr>

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.