# Senhas no Magento 2 - Detalhes

Primeiramente precisamos deixar explicito que segurança nunca é de mais, certo?

Partindo deste principio, quando você instala o Magento ele já vem configurado com a configuração que exige a maior quantidade de caracteres e/ou combinações possíveis para que com isso melhore a segurança do seu cliente e principalmente de seu ecommerce.

Em relação a isso a LGPD (Lei Geral de Proteção de Dados) estabelece que o usuário (cliente) utilize senhas fortes e evite o compartilhamento da mesma para outros sites/lojas e/ou aplicativos, bem como evitar o compartilhamento da senha para outras pessoas.

Se mesmo assim você considera que é necessário reduzir a complexidade da senha exigida para seus clientes, saiba que no Magento 2 ficou fácil alterar.


## Como alterar a complexidade da senha:

Lembrando que não é uma boa ideia fazer isso! Quanto mais complexa a senha menor a chance de alguém conseguir "quebrar" e ter acesso aos dados do seu usuário/cliente. 

Estando logado no painel Administrador (Painel Magento):

	LOJAS > CONFIGURAÇÃO > CLIENTES > CONFIGURAÇÕES DE CLIENTE > OPÇÕES DE SENHA

### Entendendo como funciona e alterando:

A regra é bem simples: a quantidade de dígitos corresponde a quantidade de classes de caracteres são eles: letras em caixa baixa, letras em caixa alta, números e caracteres especiais. 

Quanto maior a quantidade de caracteres maior a complexidade da senha. Por exemplo:

1 – Será aceito senhas unicamente com números, letras caixa baixa, letras caixa alta e caracteres especiais:

	09151987
	senhasenha
	SENHASENHA
	!@#$@!#$%

2 – Serão aceitos senhas com duas classes de caracteres:

	05151987senha
	senhaSENHA
	senha@!$

3 – Serão aceitas senhas com três classes de caracteres: (**recomendável**)

	09051987SEnha
	senhaPASS$#!
	#$@TEE1234

4 – Serão aceitas senhas com quatro classes de caracteres, deixando a senha complexa.

	09051987SEnha!@#$
	senhaPASS$#!9013
	#$@TEE1234vamos

Após selecionar o padrão que melhor se adequa a sua necessidade, você deve alterar, posteriormente clique em GRAVAR localizado no canto superior direito.

### Alterei e agora?

Recomenda-se a limpeza do CACHE da loja e se possível a reindexação da mesma. Não existe retorno visual para o cliente, apenas a mensagem de sucesso ao administrador da troca.

## Mudei de idéia e agora?

Você pode voltar na mesma tela e definir o novo padrão de configuração de senha e para os clientes que tiverem criado a conta depois da alteração anterior será recomendado a eles alterar a senha no próximo login.

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.