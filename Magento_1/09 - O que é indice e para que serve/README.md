# O que é índice e para que serve?

## O que é índice do Magento?

Em resumo índice é onde armazena as informaçoes como preço, posição no catálogo, vinculo de categoria, quantidade disponível em estoque, entre outras informações que tem como foco a otimização da navegação e versatilidade do Magento.

![indice](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/09%20-%20O%20que%20é%20indice%20e%20para%20que%20serve/images/image1.png)

## Para que serve?

Para melhorar o desempenho de sua vitrine . Conforme os dados mudam, os dados transformados devem ser atualizados ou reindexados. Magento tem uma arquitetura muito sofisticada que armazena muitos dados do comerciante (incluindo dados de catálogo , preços, usuários e lojas) em muitas tabelas de banco de dados. Para otimizar o desempenho da vitrine, o Magento acumula dados em tabelas especiais usando indexadores.

Por exemplo, se você alterar o preço de um item de R$ 4,99 para R$ 3,99. O Magento deve reindexar a mudança de preço para exibi-la em sua vitrine.

Sem a indexação, o Magento teria que calcular o preço de cada produto na hora, levando em consideração as regras de preços do carrinho de compras , preços de pacotes, descontos, preços de camadas, etc. Carregar o preço de um produto levaria muito tempo, possivelmente resultando em abandono de carrinho.

## Como realizar a indexação (reindex)?

A reindexação pode ser realizada em dois modos:

**Atualizar ao salvar** - as tabelas de índice são atualizadas imediatamente após a alteração dos dados.

**Atualizar por agenda** - este nativamente não oferece suporte ao administrador do painel. Para fazê-lo você deve acessar o terminal SSH da sua loja.

## Preciso de conhecimento especifico para reindexar via terminal?

Não, a reindexação do Magento 1 é feita pelo painel, abra **SISTEMAS > GERENCIAR ÍNDICES**, selecione todos os índices e clicar em enviar no canto direito.

![indice](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/09%20-%20O%20que%20é%20indice%20e%20para%20que%20serve/images/image2.png)

<hr>

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.