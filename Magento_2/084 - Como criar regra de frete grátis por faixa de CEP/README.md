# Como criar regra de frete grátis por faixa de CEP

1 -> Para criar a regra de frete grátis você deve primeiro acessar **MARKETING > PROMOÇÕES > REGRAS DE PREÇO DE CARRINHO** e clicar no botão **Adicionar Nova Regra**

![criando regra](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/084%20-%20Como%20criar%20regra%20de%20frete%20grátis%20por%20faixa%20de%20CEP/images/image1.png)

2 -> Agora adicione as informações obrigatórias:
- Nome da regra;
- Sites (selecione **Main Website**);
- Grupos de clientes (selecione quais grupos de clientes terão acesso ao frete grátis);
- Cupom (deixe a regra de forma automática com a opção **Sem cupom**);

![criando regra](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/084%20-%20Como%20criar%20regra%20de%20frete%20grátis%20por%20faixa%20de%20CEP/images/image2.png)

3 -> Após isto iremos criar a regra de CEP, abra a seção de **CONDIÇÕES** e copie esta estrutura de condições.

 ```
 
- Combinações de condições ( Se QUALQUER  destas condições forem VERDADEIRO )

-- Combinações de condições ( Se TODOS  destas condições forem VERDADEIRO )
--- Código de Postal de Entrega  é igual ou maior que
--- Código de Postal de Entrega  é igual ou menor que

-- Combinações de condições ( Se TODOS  destas condições forem VERDADEIRO )
--- Código de Postal de Entrega  é igual ou maior que
--- Código de Postal de Entrega  é igual ou menor que

```

![criando regra](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/084%20-%20Como%20criar%20regra%20de%20frete%20grátis%20por%20faixa%20de%20CEP/images/image3.png)

Você deverá repetir as condições que estão marcadas pelo retangulo vermelho para cada range de CEP.

**Atenção:** no laço de condição principal altere "Se **TODOS**" para "Se **Qualquer**", os demais permanecem como "Se **TODOS**".

4 -> Para ajuda-lo, abaixo está o range de CEP de todos os estados do Brasil:
- **Acre(AC)** - 69900-000 a 69999-999
- **Alagoas(AL)** - 57000-000 a 57999-999
- **Amazonas(AM) 1** - 69000-000 a 69299-999
- **Amazonas(AM) 2** - 69400-000 a 69899-999
- **Amapá(AP)** - 68900-000 a 68999-999
- **Bahia(BA)** - 40000-000 a 48999-999
- **Ceará(CE)** - 60000-000 a 63999-999
- **Distrito Federal(DF) 1** - 70000-000 a 72799-999
- **Distrito Federal(DF) 2** - 73000-000 a 73699-999
- **Espírito Santo(ES)** - 	29000-000 a 29999-999
- **Goiás(GO) 1** -	72800-000 a 72999-999
- **Goiás(GO) 2** -	73700-000 a	76799-999
- **Maranhão(MA)** - 65000-000 a 65999-999
- **Minas Gerais(MG)** - 30000-000 a 39999-999
- **Mato Grosso do Sul(MS)** - 79000-000 a 79999-999
- **Mato Grosso(MT)** - 78000-000 a 78899-999
- **Pará(PA)** - 66000-000 a 68899-999
- **Paraíba(PB)** - 58000-000 a 58999-999
- **Pernambuco(PE)** - 50000-000 a 56999-999
- **Piauí(PI)** - 64000-000 a 64999-999
- **Paraná(PR)** - 80000-000 a 87999-999
- **Rio de Janeiro(RJ)** - 20000-000 a 28999-999
- **Rio Grande do Norte(RN)** - 59000-000 a 59999-999
- **Rondônia(RO)** - 76800-000 a 76999-999
- **Roraima(RR)** - 69300-000 a 69399-999
- **Rio Grande do Sul(RS)** - 90000-000	a 99999-999
- **Santa Catarina(SC)** - 88000-000 a 89999-999
- **Sergipe(SE)** - 49000-000 a 49999-999
- **São Paulo(SP)** - 01000-000	a 19999-999
- **Tocantins(TO)** - 77000-000	a 77999-999

5 -> Agora na seção **Ações** em **Frete grátis** escolha a opção "Para envio com os itens correspondentes" e pronto a sua regra de frete grátis já estará funcionando.

![criando regra](https://github.com/Oficina-do-Dev/Tutoriais/blob/main/Magento_2/084%20-%20Como%20criar%20regra%20de%20frete%20grátis%20por%20faixa%20de%20CEP/images/image4.png)

**Observação:** você também definir regras para o frete grátis ser aplicado (Ex: valor minimo do carrinho, quantidade de itens ou valor de um atributo especifico) basta apenas adicionar as condições nesta seção e depois altere o **Frete grátis** para "Apenas para os itens correnpondentes"

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.