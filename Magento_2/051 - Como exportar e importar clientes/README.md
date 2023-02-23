# Como exportar e importar clientes.

## Exportando
1 -> Primeiramente faça login no painel do Magento e prossiga para **SISTEMA > TRANSFERÊNCIA DE DADOS** você verá algumas opções:

- Importar;
- Exportar;
- Importação/Exportação Taxas;
- importar Histórico;

1.1 -> Iremos trabalhar apenas com a primeira e segunda opção, mas vamos aprender primeiro como exportar o arquivo, então clique em **Exportar**.

![importando e exportando clientes](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/051%20-%20Como%20exportar%20e%20importar%20clientes/images/image1.png)

2 -> Selecione o Tipo de entidade, sendo elas:

- Precificação Avançada;
- Produtos;
- Customers Main File;
- Customer Adresses;
- Stock Sources;

2.1 -> Nesse tutorial iremos utilizar apenas as opções **Customers Main File** e **Customer Adresses**.

![importando e exportando clientes](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/051%20-%20Como%20exportar%20e%20importar%20clientes/images/image2.png)

3 -> Após você selecionar um tipo de entidade, logo abaixo irá aparecer para você diversos campos, selecione os atributos aos quais você deseja que sejam baixados e clique em **Proximo** logo abaixo dos atributos no canto esquerdo.

4 -> Após isto, aguarde enquanto o Cron executar a tarefa e assim que ele terminar, o download estará disponivel na seção logo abaixo.

**Atenção:** é importante verificar se o CRON do seu servidor está ativo, pois é ele quem irá executar a rotina de exportação.

5 -> Após alguns minutos o arquivo estará disponivel para download na mesma página, clique em **Selecione** e depois a opção de **Fazer Download** para baixar o arquivo.

![importando e exportando clientes](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/051%20-%20Como%20exportar%20e%20importar%20clientes/images/image7.png)

6 -> Pronto exportação finalizada.

## Importando

1 -> Primeiramente faça login no painel do Magento e prossiga para **SISTEMA > TRANSFERÊNCIA DE DADOS** você irá ver algumas opções:

- Importar;
- Exportar;
- Importação/Exportação Taxas;
- importar Histórico;

1.1 -> Vamos aprender agora como importar o arquivo, então clique em **importar**.

![importando e exportando clientes](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/051%20-%20Como%20exportar%20e%20importar%20clientes/images/image1.png)

2 -> Selecione o Tipo de entidade, sendo elas:

- Precificação Avançada;
- Produtos;
- Customers and Adresses (single file);
- Customers Main File;
- Customer Adresses;
- Stock Sources;

![importando e exportando clientes](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/051%20-%20Como%20exportar%20e%20importar%20clientes/images/image3.png)

2.1 -> Após selecionar um tipo de entidade você irá notar que diversos campos surgiram logo abaixo, iremos explicar cada um deles, mas primeiro, caso você não saiba como deve ser a estrutura que o arquivo de importação deve ter para que o Magento reconheça, para isso clique em **Baixar arquivo de amostra** ao lado do campo de entidade, será iniciado o download de um aquivo contento um exemplo de como deve ser estruturado os dados.

![importando e exportando clientes](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/051%20-%20Como%20exportar%20e%20importar%20clientes/images/image4.png)

2.2 -> Você consegue abrir esse arquivo em alguns programas diferentes, podendo ser:

- Qualquer Editor de código que tenha suporte.
- Microsoft Excel.
- LibreOffice Calc.
- Planilhas do Google.

Escolha o que você tenha mais familiaridade.

3 -> Após ter entendido como os dados são estruturados e com o arquivo pronto pra importar, vamos dar continuidade.

4 -> Os campos grifados são os que você deve alterar, os demais não são aconselhados, pois alterando seus valores poderá ocorrer erros na importação.

![importando e exportando clientes](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/051%20-%20Como%20exportar%20e%20importar%20clientes/images/image5.png)

5 -> Explicando **Comportamento de importação**.

Aqui você deve escolher uma entre as 3 opções, sendo elas:

- **Adicionar/Atualizar:** adiciona os novos clientes e caso ja tenha o mesmo cliente cadastrado na loja ele atualiza seus dados;
- **Substituir:** essa opção fará com que o magento exclua todos os clientes que tenha em sua loja e substituindo pelos clientes no arquivo de importação;
- **Excluir:** os clientes que tiverem seu dados no arquivo serão excluidos da loja, caso os dados sejam correpondentes.

6 -> Explicando **Estratégia de validação**.

Há duas opções:

- Parar no erro;
- Pular entradas de erro;

**Parar no erro** fará com que a importação pare quando encontrar algum erro ou quando o numero de erros passar do permitido no campo de **Número de Erros permitidos**.

**Pular entradas de erro** permite que a importação continue mesmo quando encontrar um ou mais erros, esta opção é a mais recomendada, e no campo de **Número de Erros permitidos** insira um valor alto para garantir que a importação de clientes não irá parar.

7 -> Agora em **Selecione o arquivo de importação** clique no botão de Choose file, irá abrir uma janela onde você deve procurar e selecionar o arquivo ao qual você irá importar.

![importando e exportando clientes](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/051%20-%20Como%20exportar%20e%20importar%20clientes/images/image5.png)

8 -> Em seguida clique em **Verificar dados** no canto superior direito da página, o Magento então irá começar efetuar a importação e após finalizar você deve limpar o cache da loja em **SISTEMA > FERRAMENTAS > GERENCIAMENTO DE CACHE** e depois pode checar os clientes em **CLIENTES > TODOS OS CLIENTES**, pronto importação finalizada.

**Importante:** em alguns casos é necessário reindexar a loja, podendo aguardar para que o **CRON** execute esta rotina, você pode também realizar manualmente (caso tiver conhecimento) ou via painel (caso houver modulo de gerenciamento de indice via painel instalado)

<hr>

### Dùvidas/Suporte: 
Entre em contato com nosso departamento de suporte.
