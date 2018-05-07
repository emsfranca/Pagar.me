![logotipo-pagar-me_1](https://user-images.githubusercontent.com/29931138/39649003-a45a8320-4fba-11e8-9239-006475f2d238.png)

O Link Pagar.me, que está atualmente na fase Beta de testes, é uma maneira facilitada de receber o pagamento do seu cliente. Com ele você cria um link, envia para o cliente e ele pode efetuar o pagamento em qualquer lugar. Essa ferramenta é apenas a forma de finalizar uma compra; isto é, é preciso saber quais produtos e em qual quantidade você deseja colocar nele antes de criar um novo link.

No link é possível colocar quantos e quais produtos o seu cliente quer comprar ou você quer oferecer em uma promoção, mas não é possível editar esses itens posteriormente. Os links criados podem ser pagos por Cartão de crédito e Boleto bancário, e é possível oferecer a possibilidade de parcelar a compra em até 12x, com ou sem juros.

As transações que são geradas através do Link Pagar.me se comportam como uma transação normal: isto é, apenas a forma de **receber** o pagamento é diferente, mas todo o resto depois disso funciona como você já está acostumado.

- [Como criar um link de pagamento com opção de parcelamento e pagamento múltiplo](https://github.com/pagarme/link-de-pagamento/blob/master/README.md#criando-um-link-de-pagamento);  
- [Como realizar a consulta dos links criados e ver o status das transações geradas](https://github.com/pagarme/link-de-pagamento/blob/master/README.md#consultando-os-links-de-pagamento-criados); 
- [Como colocar o seu logo e as cores da sua empresa na tela do link de pagamento](https://github.com/pagarme/link-de-pagamento/blob/master/README.md#personalizando-o-logo-e-a-cor-da-tela-do-link-de-pagamento);  
- [Como pagar uma compra através de um link de pagamento (cliente final)](https://github.com/pagarme/link-de-pagamento/blob/master/README.md#pagando-um-pedido-usando-o-link-de-pagamento).  
- Perguntas frequentes

## Criando um link de pagamento

Para começar, acesse a Dashboard do Pagar.me. Clique no menu no canto superior esquerdo da tela e então será possível ver a opção Link de Pagamento:

![Menu link](https://user-images.githubusercontent.com/29931138/39650158-7ab6d250-4fbd-11e8-9044-3199c846ea92.jpg)

Já na janela de links de pagamento, clique no botão "Criar Novo Link", localizado no canto superior da tela, conforme mostra a imagem abaixo:

![Criar Novo Link](https://user-images.githubusercontent.com/29931138/39650160-7d8184d0-4fbd-11e8-8972-e02abf9bd25f.png)

Quando você clica nesse botão, um modal é aberto e nele você pode colocar os itens e quantidades que estarão disponíveis naquele link, além de poder configurar alguns detalhes de formas de pagamento.  

### 1) Indique os itens da compra

Você pode colocar dentro desse link quantos produtos quiser, mas **não é possível editar esses itens depois**. Se for necessário acrescentar ou retirar produtos, ou mesmo dar um desconto no valor de um deles, é preciso criar um novo link de pagamento. O primeiro passo, então, é adicionar os itens:  

![Itens da compra](https://user-images.githubusercontent.com/29931138/39650166-7f36d168-4fbd-11e8-8fac-78bc892af187.png)

Nessa etapa, você deve indicar o nome do produto, o preço da unidade e a quantidade. Um subtotal é mostrado para cada produto que você adicionar, e o valor total da compra é indicado logo abaixo. Clique em "Adicionar item" para colocar outros produtos nesse mesmo link de pagamento, ou passe para a próxima etapa de criação.

### 2) Configure os limites de pedidos e tempo

Os links de pagamento criados podem ser pagos mais de uma vez, por mais de uma pessoa diferente, mas é possível limitar isso de duas formas: por quantidade máxima de pedidos e por tempo. Por exemplo, imagine que você tem 10 itens de um produto para oferecer em uma promoção, e quer mandar o link para que os 10 primeiros compradores consigam o valor promocional.  

![Configurações](https://user-images.githubusercontent.com/29931138/39650172-8275d50e-4fbd-11e8-9aeb-6badbbe0d060.png)

Dessa forma, em "Quantidade máxima de pedidos" você pode colocar o valor 10. Depois disso, se outros clientes tentarem comprar, o link aparece como expirado. É possível também limitar por tempo, para que um link funcione por um número limitado de minutos, horas, dias ou meses. Esses dois fatores podem ser usados em conjunto, e assim que um deles é atingido, o link perde a validade.  

### 3) Escolha as formas de pagamento

O terceiro passo da criação de um link de pagamento é a escolha das opções de meio de pagamento e parcelamento. Você pode configurar o link para ser pago por Cartão de crédito, Boleto bancário ou os dois. Além disso, é possível permitir o parcelamento da compra em até 12x.  

![Formas de pagamento](https://user-images.githubusercontent.com/29931138/39650174-846a1780-4fbd-11e8-8977-6435406daa76.png)

Quando a opção de juros é ativada, existe uma configuração extra: você pode indicar em até quantas parcelas a compra **não terá** juros. Por exemplo, se você configurar o campo com o valor 3, caso o cliente opte por comprar em 1x, 2x ou 3x, não será cobrado juros no pedido. No entanto, caso ele escolha 4x, todas as parcelas terão juros aplicados.  

Para pagamento por Boleto bancário, indique a quantidade de dias para o vencimento, valendo a partir da data na qual o pedido for gerado pelo Checkout Pagar.me. Se nenhum valor for colocado neste campo, o padrão neste caso é de 30 dias a partir da data na qual o pedido for gerado.  

Por fim, clique em "Criar Novo Link" para concluir o processo. Pronto, a partir de agora, ele aparece na lista de links que foram criados! Assim que você termina de criar um link, a tela mostrada na imagem a seguir aparece. Clique em "Copiar" para que o endereço do link de pagamento seja copiado e você possa então enviá-lo para o seu cliente.  

![Copiar link](https://user-images.githubusercontent.com/29931138/39650175-86ee4fee-4fbd-11e8-9040-7b2cdc90b1ed.jpg)

## Consultando os links de pagamento criados

Quando você segue o caminho "Menu > Link de Pagamento", é mostrada uma lista de todos os links que já foram criados. Ali são mostrados: link (que pode ser copiado para envio), status, data de criação e valor total.  

O status indica se aquele link está ativo (isto é, ainda pode gerar pedidos), se está expirado (isto é, atingiu a quantidade máxima de pedidos ou de tempo) ou se ele foi cancelado. Você pode cancelar um link quando não quiser mais aceitar compras a partir dele, mesmo que nenhuma limitação de tempo ou quantidade tiver sido atingida ainda.

![Lista de links](https://user-images.githubusercontent.com/29931138/39650181-89e26712-4fbd-11e8-9896-f6f921597710.png)

Ao passar o mouse por um link da lista, o botão de copiar a URL dele é mostrado. Se você clicar em um item da lista, uma tela com detalhes é aberta, como a que é mostrada seguir:

![Detalhes do link](https://user-images.githubusercontent.com/29931138/39650185-8d034b3c-4fbd-11e8-9bb2-de84dff480ab.png)

Nessa tela você pode ver todas as informações sobre o link, como o endereço dele, as limitações de quantidade de pedidos e de tempo, as formas de pagamento e as descrições dos produtos. No último campo, na parte de baixo, é possível ver todos os pedidos que já foram gerados usando aquele link.  

É importante notar que um pedido **gerado** não necessariamente é um pedido **pago**. Isto é, assim que um comprador clicar no botão "Continuar pagamento", na tela do link, um pedido é imediatamente gerado e o cliente é então direcionado ao Checkout Pagar.me para efetuar a compra. Um pedido gerado é mostrado da seguinte forma:

![Pedidos gerados](https://user-images.githubusercontent.com/29931138/39650187-8f671d4a-4fbd-11e8-842f-0c56c00843de.png)

São mostrados os dados do cliente, a forma de pagamento e o status, para que você possa ver rapidamente quais pedidos já foram pagos. Para saber mais, você pode clicar em "Ver transação" para acessar os detalhes da transação que está atrelada a este pedido.  

## Personalizando o logo e a cor da tela do link de pagamento

Habilitar a personalização da tela do link de pagamento que é mostrada para os seus clientes é muito simples. Na sua Dashboard, siga o caminho *Ver minha conta > Configurações > Branding* para configurar a identidade visual que o Pagar.me utiliza nos e-mails que são enviados para os seus clientes.  

Nesse menu, você pode enviar uma imagem para ser usada como logo e configurar a cor principal da sua loja, em RGBA. Se você quiser usar essa identidade visual também nas telas do link de pagamento, basta escolher a opção "Sim" no botão "Deseja utilizar essas informações no Link de Pagamento também?", como mostra a imagem abaixo:  

![Branding](https://user-images.githubusercontent.com/29931138/39650189-913ee8d2-4fbd-11e8-9237-6fc09663ecc4.png)

Para uma melhor visualização do logo na tela do link, recomendamos que você utilize um arquivo em formato PNG com o fundo transparente, com tamanho máximo de 300 x 55 pixels. Quando você salva essas alterações, a identidade visual da sua loja é mostrada na tela que é aberta quando o seu cliente acessa o link de pagamento, fazendo com que ele reconheça a sua loja e tenha mais confiança para continuar com a finalização da compra. 

## Pagando um pedido usando o link de pagamento

Veja a seguir como um pedido pode ser pago usando o Link Pagar.me. Quando você envia o link para o cliente, a seguinte tela é mostrada: 

![Tela do link](https://user-images.githubusercontent.com/29931138/39650193-9380ea5a-4fbd-11e8-98cf-5ab7c813b00f.png)

Ali, o comprador consegue visualizar os itens, a quantidade e o valor de cada um, além do valor total da compra. Ao clicar em "Continuar Pagamento", um modal com o Checkout Pagar.me é aberto e o seu cliente então procede de forma segura, para inserir os dados do cartão e finalizar a compra, ou gerar um boleto para pagamento.

## Perguntas frequentes

#### É possível enviar um link de pagamento para clientes de outros países?

Sim. O link é apenas a forma de começar a venda, porém todo o pagamento é realizado no Checkout Pagar.me, que suporta clientes internacionais.

#### Os valores pagos através de um link de pagamento podem ser antecipados?

Sim, a transação criada através do link é uma transação normal, então o valor estará disponível para saque em D+29+2 dias úteis. Dessa forma, é possível antecipar e receber esse valor antes.

#### As transações criadas pelo link de pagamento passam pelo antifraude?

Sim, todas as transações que forem pagas usando um Cartão de crédito passam por um serviço de antifraude.

#### É possível cancelar um link de pagamento antes de expirar o tempo e a quantidade de pedidos?

Sim, é possível cancelar um link a qualquer momento, para isso basta abrir os detalhes dele e clicar no botão "Cancelar link", no canto superior direito. Se um cliente tentar realizar o pagamento posteriormente, uma mensagem de erro indica que aquele link está expirado.

#### É possível limitar a quantidade máxima de parcelas para cada link?

Sim, isso é definido no momento da criação de cada link. Você também pode indicar o valor a ser cobrado de juros, e até quantas parcelas não terão juros.

#### É possível colocar uma limitação para aceitar apenas Cartão de crédito ou apenas Boleto bancário?

Sim, durante a configuração do link você escolhe quais formas de pagamento deseja aceitar. É possível escolher uma delas ou as duas.

![logotipo-pagar-me_1](https://user-images.githubusercontent.com/29931138/39649003-a45a8320-4fba-11e8-9239-006475f2d238.png)
