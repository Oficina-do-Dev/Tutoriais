# O que é cache e para que serve?

## Cache do Navegador

### Para que serve?

O cache nada mais é que informações que ficam salvas no seu navegador (do seu dispositivo) por um curto periodo de tempo, eles podem tornar a navegação mais rápida e eficiente uma vez que evita que o seu dispositivo efetue o download de todas as informações do site a qual você quer acessar naquele momento, já que é mais rápido ler arquivos no seu computador do que requisitá-los do servidor a qual está hospedado o site.

Vale lembrar que o cachê ocupa espaço de armazenamento e a depender da configuração do navegador de seu dispositivos ele pode manter esta memória por mais ou menos tempo.

### Como limpar o cache do navegador?

Primeiramente você precisa saber que efetuar este processo pode causar uma lentidão temporária para você acessar este site novamente, pois exigirá que seu navegador faça a requisição de todas as informações novamente. Usando o Firefox como exemplo, basta abrir as opções do navegador e, na aba de “Privacidade e Segurança”, encontrar o botão “Limpar dados” no campo “Cookies e dados de sites”. Uma caixa de diálogo será exibida e então, basta marcar apenas o cache para a exclusão. Embora o processo possa variar um pouco de navegador a navegador, a dinâmica é parecida: basta procurar nas opções de privacidade e segurança as ferramentas de limpeza para eliminar o cache.

## Cache do Magento

O Magento possui diferentes caches que servem para otimizar a navegação e usabilidade por parte do usuário, similar ao cache do navegador o Magento também armazena as informações que são mais utilizadas ou facilita que sua leitura seja realizada para otimizar a velocidade de navegação. É interessante entender o que cada um executa para que você otimize a navegação de seu site.

![cache](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_1/08%20-%20O%20que%20é%20cache%20e%20para%20que%20serve/images/image1.png)

```

1 -> Configuration: O Magento coleta a configuração de todos os módulos, mescla e salva o resultado mesclado no cache. Esse cache também contém configurações específicas da loja armazenadas no sistema de arquivos e no banco de dados. Limpe ou libere este tipo de cache após modificar os arquivos de configuração.

2 -> Layouts de página compilados (ou seja, os componentes de layout de todos os componentes). Limpe ou libere este tipo de cache após modificar os arquivos de layout.

3 -> Blocks: Fragmentos de página HTML por bloco. Limpe ou libere este tipo de cache após modificar a camada de visualização.

4 -> Translation: Após mesclar as traduções de todos os módulos, o cache de fusão será limpo.

5 -> Collections Data: Resultados de consultas de banco de dados. Se necessário, o Magento limpa esse cache automaticamente, mas os desenvolvedores de terceiros podem colocar todos os dados em qualquer segmento do cache. Limpe ou libere este tipo de cache se seu módulo personalizado usa lógica que resulta em entradas de cache que o Magento não pode limpar.

6 -> EAV types and attributes: Metadados relacionados a atributos EAV (por exemplo, rótulos de loja, links para código PHP relacionado, renderização de atributo, configurações de pesquisa e assim por diante). Normalmente, você não precisa limpar ou liberar esse tipo de cache.

7 -> Web Services Configuration: Armazenamento em cache da estrutura da API da Web.

```

É importante manter o cache do Magento sempre habilitado para otimizar a navegação do usuário e reduzir esforço por parte do servidor.

## Como ele pode ajudar meu site?

Como explicado anteriormente o cache faz uma "memória" do site em seu navegador, somado este recurso com o cache do Magento torna a navegação de certa forma mais rápida, causando com isso uma melhor experiência para seu cliente.

Existem outros recursos como REDIS, VARNISH, OpCache e serviços como CDN (CloudFlare, GoCache, Akamai, etc.) que também auxiliam na otimização de navegação e podem ser inseridos no escopo do seu site a depender de alguns fatores compatibilidade da hospedagem e versão instalada de seu Magento.

<hr>

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.