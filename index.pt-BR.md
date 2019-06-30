---
# Translation instructions are after the "#" character in this first section. (They are comments that do not show up in the web page.)
title: Introdução à acessibilidade na Web   # Do not translate "title:". Do translate the text after "title:".
lang: pt-BR   # Change "en" to the translated language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2019-06-30   # Put the date of this translation YYYY-MM-DD (with month in the middle)
translators:
- name: "VictorBSI"   # Replace @@ with translator name

# contributors: #Add one -name: line for every contributor
# - name: "Contributor Name Here"
permalink: /fundamentals/accessibility-intro/pt-BR   # Add the language shortcode to the end; for example /fundamentals/accessibility-intro/fr
ref: /fundamentals/accessibility-intro/   # Do not change this
layout: default
github:
  repository: w3c/wai-intro-accessibility
  branch: gh-pages
  path: index.pt-BR.md   # Add the language shortcode to the middle of the filename, for example index.fr.md
footer: >   # Translate all the words below, including "Date:" and "Editor:". Do not change these dates.
  <p><strong>Data:</strong> Actualizado a 5 June 2019. Primera publicación en Febrero 2005.</p>
  <p><strong>Editor:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
  <p>Desenvolvido pelo Grupo de Trabalho de Educação e Disseminação (<a href="http://www.w3.org/WAI/EO/">EOWG</a>).</p>
# Read Translations Notes at https://github.com/w3c/wai-intro-accessibility/blob/gh-pages/README.md
# end of translation instructions
---


{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

Quando os sites e as ferramentas da Web são bem projetados e codificados, as pessoas com deficiências podem usá-los. No entanto, atualmente muitos sites e ferramentas são desenvolvidos, incluindo barreiras de acessibilidade que tornam difícil ou impossível para algumas pessoas usá-lo.

Tornar o site acessível beneficia tanto pessoas, empresas como a sociedade em geral. Os padrões internacionais da web definem quais necessidades de acessibilidade.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include_cached toc.html type="start" title="Conteúdo da página" class="full" %}
{:/}

<ul>
<li><a href="#context">Acessibilidade no Contexto</a></li>
<li><a href="#what">O Que é Acessibilidade na Web</a></li>
<li><a href="#important">A Acessibilidade é Importante Para as Empresas, Pessoas e Sociedade</a></li>
<li><a href="#making">Torne a Web Acessível</a></li>
<li><a href="#evaluate">Avaliar Acessibilidade</a></li>
<li><a href="#examples">Exemploss</a></li>
<li><a href="#more-info">Mais Informações</a></li>
</ul>

<span class="box-h box-h-simple box-h-full">Recursos relacionados</span><br>
{% include video-link.html title="Vídeo de Introdução à Acessibilidade à Web e Padrões W3C <em>(4 minutos)</em>" href="https://www.w3.org/WAI/videos/standards-and-benefits.html" src="/content-images/wai-intro-accessibility/video-still-accessibility-intro-16-9.jpg" %}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Acessibilidade no contexto {#context}

<blockquote class="pull">
  <p>O poder da Web reside na sua universalidade.<br />
    O acesso para qualquer pessoa, independentemente da deficiência, é um aspecto essencial.</p>
  <footer><cite>Tim Berners-Lee, diretor do diretor do W3C e inventor da World Wide Web</cite></footer>
</blockquote>

A Web é fundamentalmente projetada para funcionar para todos, independentemente de hardware, software, idioma, localização ou capacidade. Quando a Web atinge esse objetivo, ela é acessível a pessoas com uma gama diversificada de habilidades auditivas, de movimento, visão e cognitivas.

Portanto, o impacto da deficiência muda radicalmente na Web porque elimina as barreiras de comunicação e interação que muitas pessoas enfrentam no mundo físico. No entanto, quando sites, aplicativos, tecnologias ou ferramentas são mal projetados, eles podem criar barreiras que excluem as pessoas de usar a Web.

**A acessibilidade é essencial para desenvolvedores e organizações que desejam criar sites e ferramentas de qualidade e não excluir as pessoas do uso de seus produtos e serviços.**


## O Que é Acessibilidade da Web {#what}

Acessibilidade na Web significa que sites, ferramentas e tecnologias são projetados e desenvolvidos de tal forma que pessoas com deficiências possam usá-los. Mais especificamente, as pessoas podem:

-   perceber, entender, navegar e interagir com a web
-   Contribuir com a web

A acessibilidade da Web abrange todas as deficiências que afetam o acesso à Web, incluindo:

-   auditivas
-   cognitivas
-   neurológicas
-   físicas
-   de fala
-   visuais

A acessibilidade na Web também beneficia pessoas com * sem * deficiências, como:

- pessoas que usam telefones celulares, relógios inteligentes, TVs inteligentes e outros dispositivos com telas pequenas, diferentes modos de entrada, etc.
- pessoas idosas cujas habilidades mudam com a idade
- pessoas com "incapacidade temporária", como um braço quebrado ou a perda de óculos
- pessoas com "limitações devido à sua localização", como sob a luz do sol ou em um ambiente onde você não pode ouvir o áudio
- pessoas com conexão lenta à Internet ou com largura de banda limitada ou cara

Você pode assistir a um vídeo de 7 minutos com exemplos de como a acessibilidade é essencial para pessoas com deficiências e útil para qualquer pessoa em uma ampla variedade de situações:<br>
{% include video-link.html title="Perspectivas da Acessibilidade na Web <em>(YouTube)</em>" href="https://www.youtube.com/watch?v=3f31oufqFSM" src="/content-images/wai-intro-accessibility/video-still-accessibility-perspectives-16-9.jpg" %}

{::nomarkdown}
{% include box.html type="start" h="3" title="Mais Informações Sobre o Que é Acessibilidade" class="simple aside" %}
{:/}

- Se você quiser saber mais sobre como diferentes deficiências afetam o uso da Web e ler sobre cenários de pessoas com deficiências usando a Web, acesse [[Como pessoas com deficiências usam a Web]](/people-use-web/).
- Se você quiser mais exemplos de benefícios para outras pessoas, com o WCAG como ajuda, acesse [[Experiências da Web compartilhada: barreiras comuns para usuários de dispositivos móveis e pessoas com deficiências]](/standards-guidelines/shared-experiences/) y a [Accesibilidad Web Beneficia a Personas con y sin Discapacidades](https://www.w3.org/WAI/business-case/archive/soc#groups).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Acessibilidade é importante para pessoas, empresas e sociedade {#important}

A Web é um recurso importante em muitos aspectos da vida: educação, trabalho, governo, saúde, entretenimento e muito mais. É essencial que a Web seja acessível para facilitar a igualdade de acesso e oportunidades para pessoas com diferentes habilidades. O acesso às tecnologias de informação e comunicação, incluindo a Web, é definido como um direito humano básico na Convenção das Nações Unidas sobre os Direitos das Pessoas com Deficiência (UN [CRPD](https://www.un.org/development/desa/disabilities/convention-on-the-rights-of-persons-with-disabilities.html)).

A Web oferece a possibilidade sem precedentes de acesso à informação e interação para muitas pessoas com deficiências. Isso significa que barreiras de acessibilidade ao material impresso, áudio e mídia visual podem ser mais facilmente superadas através de tecnologias da web.

A acessibilidade suporta a inclusão social de pessoas com deficiências, além de outras, como:

- pessoas maiores
- pessoas em áreas rurais
- pessoas em países em desenvolvimento

**Há também um forte argumento comercial a favor da acessibilidade.** Como mostrado na seção anterior, o design acessível melhora a experiência e satisfação dos usuários, em uma variedade de situações, através de diferentes dispositivos e para pessoas maiores. Além disso, a acessibilidade pode melhorar sua marca, impulsionar a inovação e expandir seu alcance no mercado.

A acessibilidade da Web é **requisito legal** em muitas ocasiões.

{::nomarkdown}
{% include box.html type="start" h="3" title="Mais Informações Sobre a Importância da Acessibilidade" class="simple aside" %}
{:/}

-   Informações gerais sobre os benefícios no nível comercial no [[The Digital Accessibility Business Case]](/business-case/).
-   O guia para calcular os requisitos legais pode ser encontrado no arquivo [Legal and Political Factors](https://www.w3.org/WAI/business-case/archive/pol).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Torne o Web Acessível {#making}

A acessibilidade da Web depende de muitos componentes trabalhando juntos, incluindo tecnologias da Web, navegadores e outros \"agentes do usuário\", ferramentas de criação e sites.

A Iniciativa de Acessibilidade na Web do W3C ([WAI](/get-involved/)) desenvolve especificações técnicas, diretrizes, técnicas e recursos que descrevem soluções de acessibilidade. Estes são considerados padrões internacionais para acessibilidade na web; por exemplo, <abbr title="Diretrizes de acessibilidade para conteúdo da Web (WCAG)">WCAG</abbr> 2.0 também é padrão <abbr title="Organização Internacional para Padronização">ISO</abbr>: ISO/<abbr title="Organização Internacional para Padronização">IEC</abbr> 40500.

{::nomarkdown}
{% include box.html type="start" h="3" title="Mais informações sobre como tornar a Web acessível" class="simple aside" %}
{:/}

-   Mais sobre os componentes de acessibilidade trabalhando juntos: [[Componentes essenciais da acessibilidade da Web]](/fundamentals/components/).
-   Diretrizes de Acessibilidade ao Conteúdo da Web (WCAG), Diretrizes de Acessibilidade para Ferramentas de Criação (ATAG), ARIA para Aplicativos de Internet Rica Acessíveis e outros recursos importantes: [[Resumo dos Padrões de Acessibilidade do W3C]](/standards-guidelines/).
-   Para saber mais sobre como o WAI do W3C desenvolve material através da participação de múltiplos atores, participação internacional e como você pode contribuir: [[Sobre WAI]](/about/) y [[Participação no WAI]](/get-involved/).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

### Torne Seu Site Scessível {#website}

Vários aspectos da acessibilidade são simples de entender e implementar, enquanto outras soluções são muito mais complexas e exigem mais conhecimento.

É mais eficiente e eficaz incorporar a acessibilidade desde o início dos projetos. Desta forma, não será necessário voltar atrás e refazer o trabalho mais tarde.

{::nomarkdown}
{% include box.html type="start" h="3" title="Mais informações sobre como tornar seu site acessível" class="simple aside" %}
{:/}

-   Para ter uma introdução aos requisitos de acessibilidade e padrões internacionais, acesse [[Princípios de acessibilidade]](/fundamentals/accessibility-principles/).
-   Para entender algumas das barreiras comuns à acessibilidade a partir da perspectiva da avaliação, acesse [[Testes Simples - Uma primeira revisão]](/test-evaluate/preliminary/).
-   Para aprender sobre algumas das considerações básicas de design, edição e desenvolvimento para acessibilidade, acesse [[Dicas para Começar]](/tips/).
-   Quando você estiver pronto para aprender mais sobre desenvolvimento e design, recursos como:
    -   [Como cumprir as WCAG (Referência Rápida)](http://www.w3.org/WAI/WCAG21/quickref/)
    -   [Tutoriais de Acessibilidade na Web](https://www.w3.org/WAI/tutorials/)
-   Para o gerenciamento de projetos e considerações organizacionais, acesse o [[Planificação e Gestão da Acessibilidade na Web]](/planning-and-managing/).<br>
-   Se você precisar fazer correções rápidas, acesse [[Estratégias para Reparações Profissionais]](/planning/interim-repairs/).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

## Avaliar acessibilidade {#evaluate}

Ao desenvolver ou redesenhar um site, avalie a acessibilidade desde o início e durante todo o processo de desenvolvimento para identificar problemas de acessibilidade desde o início, quando é mais fácil resolvê-los. Etapas simples, como alterar as configurações do navegador, podem ajudá-lo a avaliar alguns aspectos da acessibilidade. Uma avaliação completa para determinar se um site atende a todas as diretrizes de acessibilidade exige mais esforço.

Existem ferramentas que ajudam na avaliação. No entanto, nenhuma ferramenta sozinha pode determinar se um site atende às diretrizes de acessibilidade. Uma avaliação humana bem experiente é necessária para determinar se um site é acessível.


{::nomarkdown}
{% include box.html type="start" h="3" title="Mais informações sobre como avaliar acessibilidade" class="simple aside" %}
{:/}

-   Recursos para auxiliar na avaliação da acessibilidade estão descritos em [[Assess Website Acessibility]](/test-evaluate/).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% include excol.html type="start" id="examples" %}

## Exemplos

{% include excol.html type="middle" %}

### Alternativas textuais para imagens

![image of logo; HTML markup img alt='Iniciativa de Acessibilidade na Web'](https://www.w3.org/WAI/intro/alt-logo.png){:.right}

As imagens devem incluir uma *[alternativa de texto equivalente](http://www.w3.org/TR/UNDERSTANDING-WCAG20/text-equiv.html)* (texto alternativo) no marcado/código.

Se não for fornecido texto alternativo para as imagens, suas informações ficam inacessíveis, por exemplo, para pessoas que não podem ver e usar um leitor de tela que lê as informações na página, incluindo o texto alternativo da imagem.

Quando o equivalente textual é fornecido, a informação está disponível para pessoas cegas, bem como para pessoas que desativam as imagens (por exemplo, em áreas com largura de banda limitada ou alto custo). Também está disponível para tecnologias que não podem ver imagens, como mecanismos de pesquisa.

### Entrada com teclado

![mouse crossed out](https://www.w3.org/WAI/intro/no-mouse.png){:.left width="67" height="45"}

Algumas pessoas não podem usar um mouse, incluindo muitas pessoas mais velhas com controle motor limitado. Um site acessível não depende do mouse; faz [todas as funcionalidades disponíveis para o teclado](http://www.w3.org/TR/UNDERSTANDING-WCAG20/keyboard-operation.html). Então, pessoas com discoapacity podem usar [tecnologias de suporte](/planning/involving-users/#at) que simulam o teclado, como entrada de voz.

### Transcrições para áudio

[![exemplo transcrito](https://www.w3.org/WAI/intro/transcript.png){:.right width="251" height="254"}](http://www.w3.org/WAI/highlights/200606wcag2interview.html)

Del mismo modo que as imagens não estão disponíveis para as pessoas que não podem ver, os arquivos de áudio não estão disponíveis para as pessoas que não pueden oír. Proporcionar uma transcrição de texto com acesso à informação de áudio do mar acessível para pessoas com problemas de audição, assim como para os motores de busca e outras tecnologias que não possuem.

Facilitar a transcrição é fácil e relativamente barata para os websites. Existem também [serviços de transcrição](http://www.uiaccess.com/transcripts/transcript_services.html) que criam transcrições textuais em formato HTMLL.

{::nomarkdown}
{% include box.html type="start" h="3" title="More Examples" class="simple aside" %}
{:/} 

-   [[Dicas para começar]](/tips/)
-   [[Testes simples - uma primeira revisão]](/test-evaluate/preliminary/)
-   {% include video-link.html class="small inline" title="Perspectivas sobre acessibilidade na Web & mdash; vídeos e descrições" href="/perspective-videos/" src="/content-images/wai-intro-accessibility/video-still-accessibility-perspectives-16-9.jpg" %}

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% include excol.html type="end" %}

## Para Mais Informações {#more-info}

W3C WAI facilita uma ampla gama de recursos em diferentes aspectos dos [padrões](/standards-guidelines/) de acessibilidade na web à acessibilidade na web, [formação](https://www.w3.org/WAI/train), [testing/evaluación](/test-evaluate/), [gestão de projetos e políticas](https://www.w3.org/WAI/managing). Nós encorajamos você a explorar este site ou verificar a lista de [recursos WAI](http://www.w3.org/WAI/Resources/).
