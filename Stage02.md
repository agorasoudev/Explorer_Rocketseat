>> Navegador e editor de código

>> Introdução ao HTML

Nessa aula demos introdução ao HTML (Hyper Text Markup Language), aprendemos sobre a estrutura inicial do HTML e suas tags.

# O que é HTML?

HTML é uma *liguagem de marcação* baseada em hipertexto - textos com hiperlinks ou links que levam de um conteúdo para outro.

Com HTML, podemos escrever documentos que serão acessados pelo navegador ou browser - é a linguagem da web.

## O que são tags HTML?

São elementos que identificam e organizam um conteúdo dentro de um arquivo HTML através de uma marcação (tag) entre os sinais de < e >.

Alguns exemplos conhecidos:

`<HTML> ... </HTML>` - indica que o conteúdo deve ser lido como HTML

`<p> ... </p>` - Indica que o conteúdo é um parágrafo de texto.

## Elementos *inline* e elementos *block*

Alguns elementos HTML são exibidos no formato inline - ficam um ao lado do outro na janela do navegador. Outros, são exibidos como blocos, e automaticamente ‘empurram’ tudo o que vem depois para baixo.

**Como saber se o conteúdo é inline ou block?**

No geral, todos os conteúdos HTML são do tipo block, exceto conteúdos no formato texto que não representam um bloco de texto completo - um parágrafo ou título, por exemplo.

<p>, <h1>, <h2> são elementos de texto, porém tem visibilidade em bloco.

Elementos de estilização e ênfase, links e imagens são elementos em linha:

<img>, <span>, <strong>, <a> são exemplos de elementos em linha.

> Glossário de tags HTML
    Utilize este glossário sempre que você tiver uma dúvida sobre qual é a melhor estrutura HTML para o seu projeto. Não se preocupe em decorar os conteúdos, mas utilize como guia para explorar o comportamento das tags e suas funções semânticas.
    Importante: esse guia usou como base a documentação do MDN, aproveite para explorar os links e descobrir outras várias tags diferentes!
> Principais tags HTML
<html> O elemento **HTML <html> **(ou HTML root element) representa a raiz de um HTML ou XHTML documento. Todos os outros elementos devem ser descendentes desse elemento.

> Metadados do documento
    Os metadados são onde se guardam várias informações sobre a página, incluindo informações sobre estilos, scripts e etc.
<base>
    especifica o endereço (URL) utilizada por todos os endereços relativos contidos dentro de um documento. Há um número máximo de 1 (um) elemento Base <base> do documento.
<head>
    providencia informações gerais (metadados) sobre o documento, incluindo seu título e links para scripts e folhas de estilos.
<link>
    specifica as relações entre o documento atual e um recurso externo. Possíveis usos para este elemento incluem a definição de uma estrutura relacional para navegação. Este elemento é mais usado para vincular as folhas de estilo.
<meta>
    O elemento **HTML <meta> **define qualquer informação de metadados que não podem ser definidos por outros elementos HTML. (base, link, script, style ou title).
<style>
    contém informações de estilo para um documento ou uma parte do documento. As informações de estilo específico estão contidas dentro deste elemento, geralmente no CSS.
<title>
    define o título do documento, mostrado na barra de título de um navegador ou na aba da página. Pode conter somente texto e quaisquer marcações contidas no texto não são interpretadas.

> Separação de conteúdo
    Elementos de separação de conteúdo permitem organizar o conteúdo do documento em partes lógicas.
<address>
    fornece informações de contato para seu ancestral article ou body mais próximo; no segundo caso, ele se aplica ao documento inteiro.
<article>
    representa uma composição independente em um documento, página, aplicação, ou site, ou que é destinado a ser distribuido de forma independente ou reutilizável, por exemplo, em sindicação. Este poderia ser o post de um fórum, um artigo de revista ou jornal, um post de um blog, um comentário enviado por um usuário, um gadget ou widget interativos, ou qualquer outra forma de conteúdo independente.
<aside>
    representa uma seção de uma página que consiste de conteúdo que é tangencialmente relacionado ao conteúdo do seu entorno, que poderia ser considerado separado do conteúdo. Essas seções são, muitas vezes, representadas como barras laterais. Elas muitas vezes contem explicações laterais, como a definição de um glossário; conteúdo vagamente relacionado, como avisos; a biografia do autor; ou, em aplicações web, informações de perfil ou links de blogs relacionados.
<footer>
    representa um rodapé para o seu sectioning content (conteúdo de seção) mais próximo ou sectioning root elemento (ou seja, seu parente mais próximo article, aside, nav, section, blockquote, body, details, fieldset, figure, td). Normalmente um rodapé contém informações sobre o autor da seção de dados, direitos autorais ou links para documentos relacionados.
<header>
    representa um grupo de suporte introdutório ou navegacional. Pode conter alguns elementos de cabeçalho mas também outros elementos como um logo, seções de cabeçalho, formulário de pesquisa, e outros.
<h1>, <h2>, <h3>, <h4>, <h5>, <h6>
    representam seis níveis de título de seção. <h1> é o nível de seção mais alto e <h6> é o mais baixo.
<main>
    define o conteúdo principal dentro do body em seu documento ou aplicação. Entende-se como conteúdo principal aquele relacionado diretamente com o tópico central da página ou com a funcionalidade central da aplicação. O mesmo deverá ser único na página, ou seja, dentro do elemento <main> não deverão ser incluidas seções da página que sejam comuns a todo o site ou aplicação, tais como mecanismos de navegação, informações de copyright, logotipo e campos de busca (a não ser, é claro, caso a função principal do documento seja fazer algum tipo de busca).
<nav>
    representa uma seção de uma página que aponta para outras páginas ou para outras áreas da página, ou seja, uma seção com links de navegação.
<section>
    representa uma seção genérica contida em um documento HTML, geralmente com um título, quando não existir um elemento semântico mais específico para representá-lo.

> Conteúdo textual
    Usam-se elementos HTML de conteúdo textual para se organizar blocos ou seções de conteúdo. Importantes para accessibilidade e SEO, esses elementos identificam o propósito ou estrutura do conteúdo.
<blockquote>
    indica que o texto incluído é uma longa citação. Normalmente, este é processado visualmente pelo recuo (ver Notas (en-US) sobre como mudá-lo). A URL para a fonte da citação pode ser dada usando o atributo cite, enquanto uma representação de texto da fonte pode ser dada usando o cite elemento.
<dd>
    fornece detalhes ou uma definição mais completa do termo precedente (definido por dt) numa lista de descrições (dl).
<div>
    é um container genérico para conteúdo de fluxo, que de certa forma não representa nada. Ele pode ser utilizado para agrupar elementos para fins de estilos (usando class ou id), ou porque eles compartilham valores de atributos, como lang. Ele deve ser utilizado somente quando não tiver outro elemento de semântica (tal como article ou nav).
<dl>
    engloba uma lista de pares de termos e descrições. Um uso comum para este elemento é para implementar um glossário ou exibir metadados(uma lista de pares chave e valor).
<dt>
    identifica um termo na lista de definição. Este elemento pode ocorrer somente em um elemento filho de dl. Geralmente seguido por um elemento dd; ou multiplos <dt> na mesma linha indicam vários termos sendo definidos pelo próximo element dd.
<figcaption>
    representa uma legenda ou uma legenda associada com uma figura ou ilustração descrita pelo resto dos dados do elemento figure que seu elemento pai.pages/tabbed/figcaption.html
<figure>
    representa conteúdo autocontido, potencialmente com uma legenda opcional, que é especificada usando o figcaption elemento. A figura, sua legenda e seu conteúdo são referenciados como uma única unidade.
<hr>
    representa uma quebra temática entre elementos de nível de parágrafo (por exemplo , uma mudança da cena de uma história, ou uma mudança de tema com uma seção). Nas versões anteriores do HTML, representava uma linha horizontal. Pode continuar sendo exibida como uma linha horizontal nos navegadores, mas agora está definida em termos semânticos, em vez de termos de apresentação.
<ol>
    representa uma lista de itens ordenados. De forma característica esses itens ordenados em uma lista são mostrados com uma contagem que os precede, que pode ser de qualquer tipo, como numerais, letras, algarismos romanos, ou simples símbolos. Esse modelo numerado não é definido na descrição html da página, mas na folha de estilos CSS associada, pela propriedade list-style-type.
<ul>
    representa uma lista de itens sem ordem rígida, isto é, uma coleção de itens que não trazem uma ordenação numérica e as suas posições, nessa lista, são irrelevantes. Caracteristicamente, os itens em uma lista desordenada são exibidos com um marcador que pode ter várias formas, como um ponto, um círculo, ou um quadrado. O tipo de marcador não é definido na descrição HTML da página, mas na CSS associada, utilizando a propriedade list-style-type.
<li>
    é usado para representar um item que faz parte de uma lista. Este item deve estar contido em um elemento pai: uma lista ordenada (ol), uma lista desordenada (ul) , ou um menu (menu) e representa uma única entidade dessa lista. Em menus e listas desordenadas a relação de itens é exibida, normalmente, usando pontos de marcação (as bolinhas). Em listas ordenadas eles são, comumente, mostrados com algum contador ascendente - como um número, ou letra - à sua esquerda.
<p>
    representa um parágrafo. Em mídias visuais, parágrafos são representados como blocos indentados de texto com a primeira letra avançada e separados por linhas em branco. Já em HTML, parágrafos são usados para agrupar conteúdos relacionados de qualquer tipo, como imagens e campos de um formulário.
<pre>
    é a tag utilizada para representar texto pré-formatado. Um texto dentro desse elemento é tipicamente exibido em uma fonte não proporcional da mesma maneira em que o texto original foi disposto no arquivo. Espaços em branco são mantidos no texto da mesma forma em que este foi digitado.

> Semânticas textuais inline
    Usa-se a semântica textual inline para definir o significado, estrutura, ou estilo de uma palavra, linha, ou de qualquer outro tipo de texto.
<a>
    O elemento **<a> **em HTML (ou elemento âncora), com o atributo href cria-se um hiperligação nas páginas web, arquivos, endereços de emails, ligações na mesma página ou endereços na URL. O conteúdo dentro de cada <a> precisará indicar o destino do link.
<abbr>
    representa uma abreviação e opcionalmente fornece uma descrição completa para ela. Se presente, o atributo title deve conter a descrição completa e apenas ela.
<b>
    representa um intervalo de texto estilísticamente diferente do texto normal, sem transmitir qualquer importância ou relevância. Ele é geralmente usado para destacar palavras-chaves em um resumo, nomes de produtos em um comentário ou outros vãos de texto cuja a apresentação típica seria negrito. Outro exemplo de seu uso é como marcação da frase principal de cada paragrafo de um artigo.
<br>
    produz uma quebra de linha em um texto (carriage-return).É útil para escrever poemas ou um endereço, onde a divisão de linha é significante.
<cite>
    representa uma referência a um trabalho artístico. Deve incluir o título do trabalho ou uma URL de referência, que pode ser em uma forma abreviada de acordo com as convenções usadas para a adição dos metadados de citação.
<code>
    apresenta seu conteúdo estilizado de maneira a indicar que o texto é um pequeno fragmento de código. Por padrão, o conteúdo é exibido utilizando a fonte monoespaçada padrão do user agent.
<em>
    marca o texto que tem ênfase. O elemento <em> pode ser aninhado, com cada nível de aninhamento indicando um grau maior de ênfase.
<i>
    representa uma parte do texto que é destacada do restante por algum motivo, por exemplo, termos técnicos, expressões de outros idiomas ou pensamentos de personagens fictícios. Normalmente, é apresentado com o uso do tipo "itálico".
<mark>
    representa um trecho de destaque em um texto, por exemplo, uma sequência de texto marcado como referência, devido à sua relevância em um contexto particular. Por Exemplo, pode ser utilizado em uma página que mostra os resultados de uma busca onde todas as instâncias da palavra pesquisadas receberam destaque.
<q>
    indica que o texto dentro da tag é uma pequena citação. Este elemento destina-se a citações curtas que não requerem marcações de parágrafo; para citações maiores use o elemento blockquote.
<s>
    renderiza um texto tachado ou uma linha cortando o texto. Use o elemento <s> para representar texto que não sejam relevante ou que não estam corretos. Não é apropriado o uso do <s> indicar edições no texto; para indicar edições no texto utilize del e ins, que são elementos mais apropriados.
<span>
    um conteiner genérico em linha para conteúdo fraseado , que não representa nada por natureza. Ele pode ser usado para agrupar elementos para fins de estilo (usando os atributos class ou id ), ou para compartilhar valores de atributos como lang. Ele deve ser usado somente quando nenhum outro elemento semântico for apropriado. <span> é muito parecido com o elemento div , entretando div é um elemento de nível de bloco enquanto <span> é um elemento em linha.
<strong>
    elemento para negrito.
<time>
    O elemento HTML time (<time>) representa o tempo tanto no formato de 24 horas ou como uma data precisa no calendário Gregoriano (com informações opcionais de tempo e fuso horário)
<var>
    O elemento HTML Variable (<var>) representa uma variável em uma expressão matemática ou um contexto de programação.

> Imagem e multimídia
    HTML suporta vários recursos multimídia como imagens, áudio, e video.
<area>
    O HTML <area> elemento define uma região hot-spot em uma imagem, e, opcionalmente, associa-lo com um Hyperlink. Este elemento é usado somente dentro de um map elemento.
<audio>
    utilizado para embutir conteúdo de som em um documento HTML ou XHTML.O elemento audio foi adicionado como parte do HTML5.
<img>
    O elemento **HTML <img> **(or HTML Image Element) representa a inserção de imagem no documento, sendo implementado também pelo HTML5 para uma melhor experiência com o elemento figure e figcaption.
<map>
    O elemento HTML <map> é usado com os elementos area para definir um mapa de imagem (a área clicável do link).
<track>
    usado como filho dos elementos de mídiaaudio e video. Ele permite que você especifique faixas de texto temporizadas (ou dados baseados em tempo), por exemplo, para lidar automaticamente com legendas. As faixas são formatadas em WebVTT format (en-US) (arquivos .vtt) — Web Video Text Tracks ou Timed Text Markup Language (TTML).
<video>
    O elemento HTML <video> é utilizado para incorporar conteúdo de vídeo em um documento HTML ou XHTML.

> Conteúdo integrado
    Além do conteúdo normal de multimídia, HTML pode incluir uma variedade de outros conteúdos, apesar de nem todos serem possuírem fácilidade de interação.
<embed>
    O **elemento HTML <embed> **incorpora conteúdo externo no ponto especificado no documento. Este conteúdo é fornecido por um aplicativo externo ou outra fonte de conteúdo interativo, como um plug-in de navegador.
<iframe>
    O elemento HTML <iframe> (ou elemento HTML inline frame) representa um contexto de navegação aninhado, efetivamente incorporando outra página HTML para a página atual. Em HTML 4.01, um documento pode conter uma cabeça e um corpo ou uma cabeça e um conjunto de quadros, mas não tanto um corpo e um conjunto de quadros. No entanto, um <iframe> pode ser usado dentro de um corpo de documento normal. Cada contexto de navegação tem sua própria história de sessão e o documento ativo. O contexto de navegação que contém o conteúdo incorporado é chamado o pai de contexto de navegação. O contexto de navegação de nível superior (que não tem um pai) normalmente é a janela do navegador.
<picture>
    O elemento HTML <picture> é um container usado para especificar múltiplos elementos source para um elemento específico img contido nele. O navegador irá escolher a imagem mais adequada de acordo com o layout atual da página, caracteristicas do dispositivo em que será exibido (p.e. um dispositivo normal ou um hiDPI), e a habilidade do navegador de renderizar um certo tipo de imagem (p.e., envie uma imagem WebP para os navegadores baseados no Chromium ou PNG para navegadores não-Chromium); se não houver correspondência entre os elementos source, o arquivo especificado pelo elemento <img> será selecionado. A imagem selecionada é então exibida no espaço ocupado pelo elemento <img>.
<source>
    O elemento source é utilizado para especificar múltiplos recursos de mídia de elementos picture, audio ou video em HTML5. É um elemento vazio. É normalmente usado para disponibilizar múltiplos formatos suportados por diferentes navegadores..

> Scripts
<canvas>
    O elemento HTML Canvas (<canvas>) pode ser utilizado para desenhar gráficos utilizando scripts (geralmente JavaScript). Por exemplo, além de desenhar gráficos, ele pode ser usado para fazer composições de fotos e também para animações. Você poderá colocar conteúdos alternativos dentro do bloco <canvas>. Este conteúdo será renderizado também em navegadores antigos e em navegadores com JavaScript desabilitado.
<noscript>
    O Elemento HTML <noscript> define uma seção de html a ser inserida se um tipo de script não é suportado pela página ou se o script está desativado no navegador.
<script>
    O elemento HTML <script> é usado para incluir ou referenciar um script executável.

> Tabelas
<caption>
    O Elemento **HTML <caption> (**ou Elemento HTML Subtitulo de Tabela) representa o título de uma tabela. Embora ele seja sempre o primeiro filho de um table, seu estilo, usando CSS pode colocar ele em qualquer lugar relativo a tabela.
<col>
    O elemento **HTML <col> **define uma tabela contendo colunas e sendo utilizada para definições semanticas em todas as colunas comuns. É normalmente encontrada dentro do elemento("colgroup")}} .Este elemento permite a estilização de colunas utilizando-se do CSS, porém apenas um numero pequeno de atributos que terão efeito dentro das colunas (veja as especificações do CSS 2.1 a partir dessa lista).
<colgroup>
    representa um grupo de colunas.
<table>
    O elemento HTML Table (<table>) representa dados em duas dimensões ou mais.
<tbody>
    representa o grupo das célulcas de uma tabelas que contém os dados em uma tabela com títulos e dados.
<td>
    table data ou uma célula de dados na tabela (não-títulos)
<tfoot>
    O **<tfoot> **é um elemento HTML que define um conjunto de linhas as quais farão parte do rodapé de uma tabela HTML
<th>
    O elemento **HTML <th> **define uma célula cabeçalho do grupo de células de sua tabela. A exatidão natural deste grupo é definida pelos atributos scope e headers.
<thead>
    representa o grupo das células de uma tabela referentes aos títulos dos dados ali apresentados
<tr>
    uma table row ou linha da tabela.

> Formulários
<button>
    representa um botão clicável.
<datalist>
    contém um conjunto de elementos option que representam as opções possíveis para o valor de outros controles.
<fieldset>
    é usado para agrupar elementos, assim como labels (label), dentro de um formulário web.
<form>
    representa uma seção de um documento que contém controles interativos que permitem ao usuário submeter informação a um determinado servidor web.
<input>
    é usado para criar controles interativos para formulários baseados na web para receber dados do usuário. A semântica de um <input> varia consideravelmente dependendo do valor de seu atributo type.
<label>
    representa uma legenda para um item em uma interface de usuário. Ele pode estar associado com um elemento de controle, colocando este dentro do elemento label, ou usando o atributo for. Tal controle é chamado o controle etiquetado do elemento etiqueta. Um input pode ser associado a diversas etiquetas (<label>s).
<legend>
    representa um rótulo para o conteúdo do seu ancestral fieldset.
<meter>
    pode representar um valor escalar dentro de um intervalo conhecido ou um valor fracionário.
<optgroup>
    Em um Formulário Web, o elemento HTML <optgroup> cria um agrupamento de opções dentro do elemento select.
<option>
    Em um formulário Web, o elemento HTML <option> é usado para criar um controle que representa um item dentro de um elemento HTML5 select, optgroup ou datalist.
<output>
    O elemento de saída (<output>) é um elemento no qual um site ou aplicativo pode injetar os resultados de um cálculo ou o resultado de uma ação do usuário.
<progress>
    usado para visualizar o progresso de uma tarefa. Embora as especifidades de como é mostrado ficam a cargo do desenvolvedor, tipicamente, é mostrado como uma barra de progresso.
<select>
    representa um controle que apresenta um menu de opções. As opções dentro do menu são representadas pelo elemento option, que podem ser agrupados por elementos optgroup. As opções podem ser pré-selecionadas para o usuário.
<textarea>
    <textarea> representa um controle de edição para uma caixa de texto, útil quando você quer permitir ao usuário informar um texto extenso em formato livre, como um comentário ou formulário de retorno.