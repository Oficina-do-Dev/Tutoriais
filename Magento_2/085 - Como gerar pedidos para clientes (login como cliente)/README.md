# Como gerar pedidos para clientes (via painel/login como cliente)

No Magento você pode gerar o pedido para o painel através de duas formas, sendo elas:

1º - PAINEL MAGENTO > VENDAS > PEDIDOS > CRIAR NOVO PEDIDO > *filtrar cliente*

2º - PAINEL MAGENTO > CLIENTES > GERENCIAR CLIENTES > *filtrar cliente* > LOGIN COMO CLIENTE

Geralmente nem todos os métodos de pagamento e/ou módulos de cotação de envio são compativeis com a primeira opção, pois são voltados a usabilidade do cliente e não ao painel administrativo, neste tutorial iremos abordar a segunda opção.


1 -> Acesse o **PAINEL MAGENTO > CLIENTES > GERENCIAR CLIENTES**

2 -> Filtre o cliente


![filtrar cliente](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/085%20-%20Como%20gerar%20pedidos%20para%20clientes%20(login%20como%20cliente)/images/image-1.png)


3 -> Clique em **EDITAR**, na coluna horizontal clique em **LOGIN AS CUSTOMER**


![Login como cliente](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/085%20-%20Como%20gerar%20pedidos%20para%20clientes%20(login%20como%20cliente)/images/image-2.png)


**ATENÇÃO:** Se o cliente não tiver habilitado a funcionalidade *PERMITIR ASSISTÊNCIA DE COMPRA REMOTA* você precisa habilitar ou solicitar ao mesmo que habilite (recurso existente nas versões mais recentes do Magento para se adequar ao LGPD)

3.1 -> Para habilitar, clique em *Informações de Conta* e mude para **SIM** a Opção *PERMITIR ASSISTÊNCIA DE COMPRA REMOTA* e posteriormente clique em **SALVAR E CONTINUAR A EDITAR**


![permitir assistencia](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/085%20-%20Como%20gerar%20pedidos%20para%20clientes%20(login%20como%20cliente)/images/image-3.png)


3.2 -> Após liberado a *Assistência Remota* você pode dar continuidade ao processo.

4 -> Estando logado como cliente você consegue gerar pedidos e efetuar cotações de frete normalmente.

**ATENÇÃO:** Como você está logado como *cliente* você poderá realizar todas as operações que ele pode realizar pelo frontend.


![painel cliente](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/085%20-%20Como%20gerar%20pedidos%20para%20clientes%20(login%20como%20cliente)/images/image-4.png)


**OBSERVAÇÕES:** Algumas lojas não possuem validação para o cliente permitir ou bloquear o administrador gerar pedidos (assistência remota), pois em alguns casos é utilizado módulos que permitem o *Login como cliente*, para saber se sua loja usa módulo nativo ou de terceiro entre em contato com o dept. de suporte.

### Dúvidas/Suporte:

Entre em contato com o nosso departamento de suporte.