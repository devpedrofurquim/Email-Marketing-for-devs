# Responsive Email-Marketing templates with HTML and CSS

- Existem mais de 4 bilhões de pessoas que usam email em todo o mundo, então se você busca uma maneira eficiente de alcançar seus clientes, o email marketing é a maneira mais eficaz.

- 79% dos marketeiros colocam a estratégia do email marketing em seu top 3 de estratégias mais efetivas.

# Email Marketing começa pelo B2B

- 31% dos markereteiros B2B afirmam que a newsletter é a melhor maneira de converter um visitante em um cliente.

- 37% dos marketeiros B2C enviam emails baseado em compras passadas.

- 85.7% dos marketeiros de e-commerce dizem que o objetivo primário de suas estratégias com o email marketing é aumentar o reconhecimento da marca.

# Guia para Desenvolvedores Web

No desenvolvimento de email marketing com Html e Css mantem-se o seguinte código base:

// DOCUMENT TYPE HTML 1.0 TRANSITIONAL é o mais compátivel com o email clients.

<!--!>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "Http://www.w3.org/TR/xhtml1-transitional.dtd">
<html xmls="http://www.wr3.or/1999/xhtml">
<head>

- Meta Tags para Emails Marketing

Detector de Formato:

Essas tags simples impedem o IOS de transformar seus números de telefone e datas em links. Pessoalmente, acredito que esses links podem ajudar se a intenção for de que o leads entrem em contato ou salvem a informação. Por outro lado, o text-decoration padrão da Apple pode não ir bem com o esquema de cores do seu email, e essas meta tags impedem essa tranformação.

<meta name="format-detection" content="date=no">
<meta name="format-detection" content="telephone=no">

Viewport:

Essas meta tags podem ser usadas para controlar o tamanho em que o browser mostra o seu email. No entanto, uma pesquisa apontou que esses vários meta tags não causam efeito no display inicial e no comportamento responsivo do email. O atributo max-scale impede que os usuários dêem zoom in no corpo do email, e isso não é de grande ajuda para quem tem problemas de visão.

<meta name="viewport" content="width=device-width; initial-scale=1.0; maximum-scale=1.0; user-scalable=no;">
<meta name="viewport" content="width=600,initial-scale = 2.3,user-scalable=no">
<meta name="viewport" content="width=device-width">

Charset:

Essa tag é extremamente importante para preservar as letras e números de seu email através de vários clientes de email.

<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />

Compatibilidade:

O IE=Edge ativa a compatibilidade do comportamento responsivo com os celulares windows, e isso é ótimo. Porém, essa tag também vai todas as suas imagens no Live Mail. A solução é simples, basta colocar seu IE=Edge meta tag entre uma condicional para o esconder do Live Mail, assim:


  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
<!--<![endif]-->

Já as meta tags de compatibilidade seguintes se mantém do seguinte modo:

<meta http-equiv="X-UA-Compatible" content="IE=7" />
<meta http-equiv="X-UA-Compatible" content="IE=8" />
<meta http-equiv="X-UA-Compatible" content="IE=9" />

É importante manter a meta tag de compatibilidade com Internet Explore e Microsoft Edge.

<meta name="viewport" content="width=device-width, initial-scale=1.0">

Portanto, o ínicio do documento HTML se dará assim:

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "Http://www.w3.org/TR/xhtml1-transitional.dtd">
<html xmls="http://www.wr3.or/1999/xhtml">
<head>

<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />

<meta name="format-detection" content="date=no">
<meta name="format-detection" content="telephone=no">

<meta name="viewport" content="width=device-width; initial-scale=1.0; maximum-scale=1.0; user-scalable=no;">
<meta name="viewport" content="width=600,initial-scale = 2.3,user-scalable=no">
<meta name="viewport" content="width=device-width">

<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="IE=7" />
<meta http-equiv="X-UA-Compatible" content="IE=8" />
<meta http-equiv="X-UA-Compatible" content="IE=9" />
<!--[if !mso]><!-- -->
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
<!--<![endif]-->

- Title tag para email marketing

Não é necessário, mas gosto de usar.

<title><title>

- Folha Style interna

É importante manter a folha da Style interna acima do body e dentro da tag <head>, mas é mais importante ainda manter os atributos de style no modo Inline.

<style type="text/css">

    body {
        maring: 0;
        background-color: #cccccc;
    }

    table {
        border-spacing: 0;
    }

    td {
        padding: 0;
    }

    img {
        border: 0;
    }
</style>
</head>
<body>

// Classe para centralizar todo o conteúdo dentro do HTML.

<center class="wrapper">

CÓDIGO HTML INTEIRO COM INLINE STYLES

// Fechamento de classes.

</center>
</body>
</html>

# Exemplos efetivos de campanhas de email marketing

- ModCloth

Grandes empresas estão sempre evoluindo, e consequentemente os seus clientes experam essas mudanças. O que eles não experam é serem avisados sobre essas mudanças.

Dito isso, o email ModCloth serve como uma antecipação para uma mudança que pode ser brusca para o cliente. Se você vai mudar o modo que se comunica com o cliente, dê a ele um aviso claro de que tais mudanças vão acontecer.

Por que funciona?

Porque essa campanha cria uma expectativa de comunicação no cliente.

- Tory Burch

A campanha de email marketing Tory Burch se diferencia dos outros emails por um único fator, a animação, algo que chama a atenção de todos, principalmente os clientes. Essa estratégia também é ótima por conta de passar um sentido de venda privada para o cliente. Na maioria das vezes, o Tory Burch faz o cliente se sentir especial, e isso o encoraja a aproveitar a sua vantagem "única".

Por que funciona?

Email's podem ser incrivelmente chatos e impessoais. Esse email tory burch surpreende as expectativas do cliente.

- Run Keeper

A campanha Run Keeper se esforça para reengajar clientes perdidos, que já não visitam ou compram no e-commerce há algum tempo. O Run Keeper é email informativo, que comunica ao cliente as últimas atualizações de produtos ou até mesmo as novidades em seu site ou redes sociais. É uma estratégia que abertamente pede mais uma chance ao cliente perdido. Também podem ser discutidos beneficios do produto que o cliente pode não saber.

Por que funciona?

Por ser um estratégia puramente informativa, se passa o sentimento de um marketing menos agressivo e confortante. Pequenas inclusões como "Olá amigo" no ínicio do email e "Você Arrasa" no final do email fazem o cliente se sentir mais próxima da marca.

- Loft

A campanha de email marketing Loft tem o objetivo principal de demonstrar compreensão sobre sua louca caixa de emails. Com um esforço para que o cliente receba da empresa apenas o que o interessa. Essa campanha de marketing focada na relação do cliente com os emails do e-commerce é super efetiva e faz o cliente sentir que seus gostos e opniões importam.

- Uncommon Goods

Você deve criar um senso de urgência com os seus CTA (Call to Actions ou Chamada Para Ação, em pt-br). É isso que faz o cliente agir. Bom, essa campanha de email tem o objetivo principal de causar esse senso de urgência no cliente, focando no valor de agir agora, no exato momento que se recebe o email.

Por que funciona?

Ao invés de dizer "Faça sua encomenda do Dia das Mães antes que nossos produtos acabem!", essa campanha pergunta, "Você Não Acha Que Sua Mãe Gostaria de Receber Seus Presentes Mais Rápido?".

- Harpoon Brewery

É a época da automação de emails, portanto é comum que as campanhas de email marketing transmitam um sentimento de algo robótico para o cliente, o que consequentemente gera um afastamento da marca com o cliente. E assim como um antídoto para essa situação, a campanha de email marketing Harppon Brewery funciona como algo extremamente pessoal e único, apesar de ser automatizado do mesmo modo.

Se você procura fortalecer o seu relacionamento com o cliente, considere deixá-los saber que você está pensando neles.

Por que funciona?

Por conta de uma simples palavra que significa muito: Personalização; É como se esse email fosse enviado para a pessoa certa no tempo certo.

Exemplos de situações onde o Harpoon Brerewy pode ser usado: No aniversário do cliente.

- Rip Curl

"JUNTE-SE A REVOLUÇÃO!"

Essa frase é muito forte, certo? Rip Curl é uma campanha de Surfing Australiana que combina urgência com a nossa parte psicológica que sempre deseja fazer parte de algo grande, importate. Essa headline é desenhada para fazer com que os clientes acreditem que existe realmente uma revolução e que é hora de tomar uma posição sobre essa situação tão importante.

Por que funciona?

No fim do dia, todos querem fazer parte de algo que é maior do que elas mesmas, e esse email tem a função de motivá-las a comprar um ticket (produto) para essa revolução.

Obs: Essa estratégia só funciona se houver apenas um único produto anunciado, pois esse produto representará o ticket único para tal revolução.

- Water

Normalmente, quando se fala em email marketing se esquece dos emails transacionais. Esses são emails automatizados que chegam em nossas inbox depois de tomarmos certas ações no website do e-commerce, como por exemplo quando preenchemos um formulário, compramos um produto ou até mesmo um update do progresso de nossas encomenda. Quase sempre, os marketeiros automatizam emails sem graça e esquecem disso para sempre.

Então, a campanha de email marketing Water toma uma diferente rota. Um exemplo disso foi utilizado por uma ong de caridade, onde, uma vez que alguém faz uma doação de dinheiro para eles, esse mesmo doador recebe um email que os atualiza onde exatamente o seu dinheiro está sendo utilizado. Com a timeline do email, o cliente não precisa nem ler totalmente o email, apenas acompanhar onde está o dinheiro.

Por que funciona?

Essa estratégia mantém a audiência engajada com a empresa e os atualiza em relação ao rastreamento de seu pedido.

- Birchbox

O estilo de assunto com a frase "Ops, nós esquecemos de te enviar algo em fevereiro" é curiosa e já se provou efetiva para muitas empresas. É claro, nada foi realmente esquecido, mas é uma estratégia interessante para captar a atenção do cliente. A intenção desse email é realmente enviar um cupom de desconto para o cliente.

Por que funciona?

Conquista a atenção do cliente e agregra para empresa um ponto com o cliente, por ser uma estratégia única.

- Postmates

GIFs são fáceis de serem consumidos e na maioria das vezes são extremamente cativantes. Pode-se usar GIFs em sua estratégia de email marketing e também aproveitar de uma headline divertida e engraçada, ou até mesmo pode-se usar o GIF para demonstrar o produto de um modo diferente e mais cativante.

Por que funciona?

Centraliza o produto de uma maneira divertida e diferenciada.

- Dropbox

Receber o email de um produto que você não usa há algum tempo realmente pode ser chato, e muitas vezes nem esperamos por tal estratégia, no entanto, cliente perdidos são o foco dessa campanha. O uso de uma headline que vai direto ao ponto, como um "Volte para nós" e um design amigável e emocional é a junção perfeita para atrair a atenção desse cliente perdido.

Além do mais, a intenção é manter um email curto e simples, com o objetivo de enfatizar que a intenção da empresa não é ser intruza, mas sim lembrá-los que a empresa existe e sente falta de seus clientes. Quando enviar email's como esse, você pode querer incluir uma promoção única, como um cupom limitado que inclua a palavra VOLTA ou RETORNO.

- Cook Smarts

A estratégia de email marketing Cook Smart é a da Newsletter. A compania envia para os seus clientes receitas semanais em três seções distintas, uma para o menu, outra para o modo de preparação e a última para as dicas de como consumir a receita, e isso significa que você não precisa acessar o site ou blog da empresa para ler o seu conteúdo por inteiro. Você vai saber exatemente qual seção procurar depois de alguns poucos emails recebidos.

- Hirevue

"Dizer adeus sempre é dificíl... Então decidimos te dar a opção de repensar nosso relacionamento." Esse o assunto da estratégia de email marketing Hirevue, um email automatizado que dá ao cliente a chance de se desassociar da lista de emails da empresa. É aconselhável a utilização de um email marketing simples, apenas focado na opção de se desassociar da lista de emails da empresa.

Esse modelo de email marketing é super inteligente, pois uma baixa taxa de abertura pode se tornar um grande prejuízo para a sua campanha.

Por que funciona?

Essa estratégia faz com que o cliente pause e pense se realmente quer se desassociar da lista de emails da empresa ou não.

-

fonts:

https://blog.hubspot.com/marketing/email-marketing-guide

https://blog.hubspot.com/marketing/email-marketing-examples-list