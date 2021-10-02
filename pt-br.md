# Como fazer perguntas de forma inteligente

## Traduções

Existem traduções deste texto para diversos idiomas listadas em http://www.catb.org/~esr/faqs/smart-questions.html . Caso você deseje copiar, hospedar, traduzir ou recortar esse documento, por favor veja a [política de direitos autoriais](http://www.catb.org/~esr/copying.html).

## Aviso

Muitos sites de projetos possuem links para este documento em suas seções sobre como obter ajuda. Tudo bem, é o uso pretendido - mas se você for um webmaster linkando este documento na página do seu projeto, exiba com destaque próximo ao link um alerta de que não somos um help desk para o seu projeto!

Aprendemos da maneira mais difícil que, sem esse aviso, seremos repetidamente incomodados por idiotas que acham que, por termos publicado este documento, é nosso trabalho resolver todos os problemas técnicos do mundo.

Se você está lendo este documento porque precisa de ajuda e fica com a impressão de que pode obtê-la diretamente dos autores deste documento, você é um dos idiotas de quem estamos falando. Não nos faça perguntas. Vamos apenas ignorar você. Estamos aqui para mostrar como obter ajuda de pessoas que realmente conhecem o software ou hardware com o qual você está lidando, e em 99,9% das vezes não seremos nós. A menos que você tenha certeza de que um dos autores é especialista no que você está lidando, deixe-nos em paz e todos ficarão mais felizes.

## Introdução

No mundo dos hackers, o tipo de resposta que você obtém para suas perguntas técnicas depende tanto da maneira como você faz as perguntas quanto da dificuldade de desenvolver a resposta. Este guia irá ensiná-lo a fazer perguntas de uma maneira mais provável de obter uma resposta satisfatória.

Agora que o uso do código aberto se popularizou, muitas vezes você pode obter respostas tão boas de outros usuários mais experientes quanto de hackers. Isto é uma coisa boa; os usuários tendem a ser um pouco mais tolerantes com o tipo de falhas que os iniciantes costumam ter. Ainda assim, tratar usuários experientes como hackers das maneiras que recomendamos aqui geralmente será a maneira mais eficaz de obter respostas úteis deles também.

A primeira coisa a entender é que os hackers realmente gostam de problemas difíceis e perguntas boas e instigantes sobre eles. Se não gostássemos, não estaríamos aqui. Se você nos der uma pergunta interessante para mastigar, seremos gratos a você; boas perguntas são um estímulo e um presente. Boas perguntas nos ajudam a desenvolver nosso entendimento e frequentemente revelam problemas que talvez não tenhamos percebido ou pensado de outra forma. Entre os hackers, “Boa pergunta!” é um elogio forte e sincero.

Apesar disso, os hackers têm a reputação de responder a perguntas simples com o que pode parecer hostilidade ou arrogância. Às vezes parece que somos deliberadamente rudes com os novatos e os ignorantes. Mas isso não é verdade.

O que somos, assumidamente, é hostis às pessoas que parecem não querer pensar ou fazer sua própria lição de casa antes de fazer perguntas. Pessoas assim são uma perda de tempo - levam sem retribuir e nos fazem perder tempo que poderíamos ter gasto com outra questão mais interessante ou outra pessoa mais digna de uma resposta. Chamamos pessoas assim de “otários” (e por razões históricas às vezes o soletramos “lusers”).[^NT1]

Percebemos que existem muitas pessoas que querem apenas usar o software que escrevemos e que não têm interesse em aprender detalhes técnicos. Para a maioria das pessoas, um computador é apenas uma ferramenta, um meio para um fim; elas têm coisas mais importantes para fazer e vidas para viver. Reconhecemos isso e não esperamos que todos se interessem pelas questões técnicas que nos fascinam. No entanto, nosso estilo de responder a perguntas é voltado para pessoas que se interessam e desejam ser participantes ativos na solução de problemas. Isso não vai mudar. Nem deveria; se assim fosse, nos tornaríamos menos eficazes nas coisas que fazemos melhor.

Somos (em grande parte) voluntários. Tiramos um tempo de nossas vidas ocupadas para responder a perguntas e, às vezes, ficamos sobrecarregados com elas. Então, filtramos implacavelmente. Em particular, jogamos fora as perguntas de pessoas que parecem ser otárias, a fim de gastar nosso tempo respondendo a perguntas de forma mais eficiente, com os campeões.

Se você achar essa atitude desagradável, condescendente ou arrogante, verifique suas suposições. Não estamos pedindo que você se ajoelhe diante de nós - na verdade, a maioria de nós adoraria nada mais do que tratá-lo como um igual e recebê-lo em nossa cultura, se você fizer o esforço necessário para tornar isso possível. Mas simplesmente não é eficiente para nós tentar ajudar pessoas que não estão dispostas a ajudar a si mesmas. É OK ser desinformado; não é OK ser estúpido.

Assim, embora não seja necessário já ser tecnicamente competente para chamar a nossa atenção, é necessário demonstrar o tipo de atitude que leva à competência - estar alerta, atento, observador, disposto a ser um parceiro ativo no desenvolvimento de uma solução. Se você não consegue conviver com esse tipo de discriminação, sugerimos que você pague alguém por um contrato de suporte comercial, em vez de pedir aos hackers que doem ajuda pessoalmente a você.

Se você decidir nos pedir ajuda, você não quer ser um dos otários. Você também não quer parecer um. A melhor maneira de obter uma resposta rápida e responsiva é perguntar como uma pessoa inteligente, confiante e com informações, que por acaso precisa de ajuda para resolver um problema específico.

(Melhorias neste guia são bem-vindas. Você pode enviar sugestões para [esr@thyrsus.com](mailto:esr@thyrsus.com) ou [respond-auto@linuxmafia.com](mailto:respond-auto@linuxmafia.com). Observe, entretanto, que este documento não pretende ser um guia geral para [netiqueta](http://www.ietf.org/rfc/rfc1855.txt) e geralmente rejeitaremos sugestões que não estão especificamente relacionadas com a obtenção de respostas úteis em um fórum técnico.)

## Antes de perguntar

Antes de fazer uma pergunta técnica por e-mail, em um grupo ou em um fórum online, faça o seguinte:

1. Tente encontrar uma resposta pesquisando os históricos do fórum ou lista de e-mails onde você planeja postar.
1. Tente encontrar uma resposta pesquisando na web.
1. Tente encontrar uma resposta lendo o manual.
1. Tente encontrar uma resposta lendo um FAQ.
1. Tente encontrar uma resposta investigando e testando.
1. Tente encontrar uma resposta perguntando a um amigo habilidoso.
1. Se você é um programador, tente encontrar uma resposta lendo o código-fonte.

Ao fazer sua pergunta, mostre o fato de que você fez essas coisas primeiro; isso ajudará a estabelecer que você não está sendo uma esponja preguiçosa e desperdiçando o tempo das pessoas. Melhor ainda, mostre o que você aprendeu ao fazer essas coisas. Gostamos de responder a perguntas para pessoas que demonstraram que podem aprender com as respostas.

Use táticas como fazer uma pesquisa no Google com o texto de qualquer mensagem de erro que você receber (pesquisar tanto nos grupos de email do Google como em páginas da Web). Isso pode levá-lo diretamente a documentação ou a mensagens passadas que respondam à sua pergunta. Mesmo que isso não aconteça, dizer "Pesquisei a seguinte frase no Google, mas não encontrei nada que parecesse promissor" é uma boa coisa a fazer em uma mensagem solicitando ajuda, pelo menos porque já indica o que as pesquisas não resolveram. Isso também ajudará a direcionar futuramente outras pessoas com problemas semelhantes para o seu tópico, fazendo os termos de pesquisa apontarem para o que esperamos será a resolução do problema levantado.

Não tenha pressa. Não espere ser capaz de resolver um problema complicado com alguns segundos de busca no Google. Leia e entenda as perguntas frequentes, sente-se, relaxe e reflita sobre o problema antes de entrar em contato com especialistas. Confie em nós, eles saberão, a partir de suas perguntas, o quanto você leu e refletiu, e estarão mais dispostos a ajudar se você vier preparado. Não dispare instantaneamente todo o seu arsenal de perguntas só porque sua primeira pesquisa não apresentou nenhuma resposta (ou muitas).

Prepare sua pergunta. Pense sobre isso. Perguntas que parecem precipitadas obtêm respostas precipitadas ou nenhuma resposta. Quanto mais você fizer para demonstrar que pensou e se esforçou para resolver seu problema antes de buscar ajuda, maior será a probabilidade de realmente obter ajuda.

Cuidado para não fazer a pergunta errada. Se você fizer uma pergunta baseada em suposições errôneas, é bem provável que um hacker aleatório responda com uma resposta literalmente inútil enquanto pensa "Pergunta estúpida ...", e espera que a experiência de obter como resposta o que você merece, em vez do que você precisava, vá te ensinar uma lição.

Nunca presuma que você tem direito a uma resposta. Você não tem; afinal, você não está pagando pelo serviço. Você obterá uma resposta, se conquistá-la, fazendo uma pergunta substancial, interessante e instigante - que contribua implicitamente para a experiência da comunidade, em vez de apenas exigir passivamente o conhecimento de outras pessoas.

Por outro lado, deixar claro que você pode e deseja ajudar no processo de desenvolvimento da solução é um bom começo. “Alguém pode me dar uma direção?”, “O que está faltando em meu exemplo?” e “Qual site eu deveria ter pesquisado?” são perguntas mais propensas a obter respostas do que “Por favor me diga exatamente o que eu devo fazer”, pois aqui você está deixando claro que está realmente disposto a concluir o processo sozinho se alguém puder simplesmente apontar a direção certa.


## Quando estiver perguntando
### Escolha o local cuidadosamente

Seja sensível ao escolher onde fazer sua pergunta. Você provavelmente será ignorado ou considerado um otário se:
* enviar sua pergunta em um fórum fora do assunto
* enviar uma questão muito elementar em um fórum onde questões técnicas avançadas são esperadas, ou vice-versa
* enviar de forma cruzada para muitos grupos diferentes
* enviar mensagem direta para alguém que não é seu conhecido nem pessoalmente responsável por resolver o seu problema

Os hackers ignoram perguntas que são direcionadas inadequadamente para tentar proteger seus canais de comunicação de serem afogados em irrelevância. Você não quer que isso aconteça com você.

O primeiro passo, portanto, é encontrar o fórum certo. Novamente, o Google e outros métodos de pesquisa na Web são seus amigos. Use-os para encontrar a página do projeto mais associada ao hardware ou software que está lhe causando dificuldades. Normalmente, ela terá links para uma lista de FAQ (Perguntas Freqüentes) e para listas de discussão de projetos e seus históricos. Essas listas de discussão são os lugares finais para ir em busca de ajuda, se seus próprios esforços (incluindo a leitura dos FAQs que você encontrou) não apresentarem uma solução. A página do projeto também pode descrever um procedimento para relatar um bug ou ter um link para fazê-lo; em caso afirmativo, clique nele.

Enviar um e-mail para uma pessoa ou fórum com o qual você não está familiarizado é, na melhor das hipóteses, arriscado. Por exemplo, não presuma que o autor de uma página informativa deseja ser seu consultor gratuito. Não faça suposições otimistas sobre se sua pergunta será bem-vinda - se você não tiver certeza, envie-a para outro lugar ou evite enviá-la.

Ao selecionar um fórum online, grupo ou lista de discussão, não confie muito no nome; procure um FAQ ou regulamento para verificar se sua pergunta está no tópico. Leia um pouco do histórico antes de postar para ter uma ideia de como as coisas são feitas lá. Na verdade, é uma boa ideia fazer uma pesquisa por palavra-chave por palavras relacionadas ao seu problema no grupo ou nos históricos da lista de discussão antes de postar. A busca pode encontrar uma resposta e, caso contrário, o ajudará a formular uma pergunta melhor.

Não atire em todos os canais de ajuda disponíveis de uma vez, isso é como gritar e irrita as pessoas. Navegue pelos diferentes espaços suavemente.

Saiba qual é o seu assunto! Um dos erros clássicos é fazer perguntas sobre a interface de programação Unix ou Windows em um fórum dedicado a uma linguagem ou biblioteca ou ferramenta portável para ambas as plataformas. Se você não entende por que isso é um erro crasso, é melhor não fazer nenhuma pergunta até entender.

Em geral, as perguntas para um fórum público bem selecionado têm mais probabilidade de obter respostas úteis do que perguntas equivalentes em um espaço privado. Há múltiplas razões para isto. Uma delas é simplesmente o tamanho do grupo de respondentes em potencial. Outra é o tamanho do audiência; os hackers preferem responder a perguntas que educam muitas pessoas do que a perguntas que sirvam para poucos.

Compreensivelmente, hackers habilidosos e autores de softwares populares já estão recebendo mais do que seu quinhão de mensagens mal direcionadas. Ao aumentar a enchente, você pode, em casos extremos, ser até a gota d'água que faz transbordar - algumas vezes, contribuintes de projetos populares deixam de o apoiar devido ao dano colateral insuportável na forma de tráfego de mensagens inúteis para suas contas pessoais.

### Stack Overflow

Pesquise e pergunte no Stack Exchange.[^NT2]

Nos últimos anos, a comunidade de sites Stack Exchange surgiu como um recurso importante para responder a questões técnicas (e de outros assuntos também), e é até mesmo o fórum preferido para muitos projetos de código aberto.

Comece com uma pesquisa no Google antes de olhar para o Stack Exchange; O Google indexa em tempo real. Há uma grande chance de alguém já ter feito uma pergunta semelhante, e os sites do Stack Exchange geralmente estão próximos ao topo dos resultados da pesquisa. Se você não encontrou nada no Google, pesquise novamente no site específico mais relevante para sua pergunta (veja abaixo). Pesquisar com tags pode ajudar a refinar os resultados.

Se você ainda não encontrou nada, poste sua pergunta no site onde ela é mais relevante. Use as ferramentas de formatação, especialmente para código, e adicione tags relacionadas ao conteúdo de sua pergunta (principalmente o nome da linguagem de programação, sistema operacional ou biblioteca com a qual você está tendo problemas). Se um usuário solicitar mais informações, edite sua postagem inicial para incluí-las. Se alguma resposta for útil, clique na seta para cima para votar; se uma resposta fornecer uma solução para o seu problema, clique na opção sob as setas de votação para aceitá-la como correta.

O Stack Exchange cresceu para mais de 100 sites, mas aqui estão os locais mais prováveis para sua pergunta técnica:

* Super User é para perguntas sobre computação de uso geral. Se sua pergunta não for sobre código ou sobre programas com os quais você interage apenas por meio de uma conexão de rede, provavelmente ela vai aqui.
* Stack Overflow é para perguntas sobre programação.
* Server Fault é para perguntas sobre administração de servidores e redes.

Vários projetos têm seus próprios sites específicos, incluindo Android, Ubuntu, TeX / LaTeX e SharePoint. Verifique o site do Stack Exchange para obter uma lista atualizada.

### Web e canais no IRC

Seu grupo de usuários local, ou sua distribuição Linux, pode divulgar um fórum online ou canal IRC onde novatos podem obter ajuda. (Em países que não falam inglês, os fóruns de novatos têm mais probabilidade de serem listas de discussão.) Esses são bons primeiros lugares para perguntar, especialmente se você acha que pode ter tropeçado em um problema relativamente simples ou comum. Um canal de IRC divulgado é um convite aberto para fazer perguntas e frequentemente obter respostas em tempo real.

Na verdade, se você obteve o programa que está causando problemas em uma distribuição Linux (como é comum hoje), pode ser melhor perguntar no fórum / lista da distro antes de tentar o fórum / lista de projetos do programa. Os hackers do projeto podem apenas dizer, “use nosso build”.

Antes de postar em qualquer fórum online, verifique se ele possui um recurso de pesquisa. Em caso afirmativo, tente algumas pesquisas por palavra-chave para algo parecido com o seu problema; isso só irá te ajudar. Se você já fez uma pesquisa geral na Web antes (como deveria), pesquise no fórum mesmo assim; seu mecanismo de busca em toda a web pode não ter todo este fórum indexado recentemente.

Há uma tendência crescente para que os projetos façam suporte ao usuário por meio de um fórum online ou canal de IRC, com listas de e-mail reservadas mais ao trabalho de desenvolvimento. Portanto, procure esses canais primeiro ao buscar ajuda específica para um projeto.

No IRC, é provavelmente melhor não despejar uma longa descrição do problema no canal primeiro; algumas pessoas interpretam isso como inundação do canal. Melhor fazer uma descrição do problema em uma linha de forma inclinada para iniciar uma conversa no canal.

### Como segundo passo, use listas de e-mail do projeto

Quando um projeto tem uma lista de discussão de desenvolvimento, escreva para a lista de discussão, não para desenvolvedores individuais, mesmo se você achar que sabe quem pode responder melhor à sua pergunta. Verifique a documentação do projeto e sua página inicial para o endereço de uma lista de discussão do projeto e use-a. Existem vários bons motivos para esta política:
* Qualquer pergunta boa o suficiente para ser feita a um desenvolvedor também será valiosa para todo o grupo. Ao contrário, se você suspeitar que sua pergunta é muito idiota para uma lista de e-mails, não é uma desculpa para atormentar desenvolvedores individuais.
* Fazer perguntas na lista distribui a carga entre os desenvolvedores. O desenvolvedor individual (especialmente se ele for o líder do projeto) pode estar muito ocupado para responder às suas perguntas.
* A maioria das listas de discussão são arquivadas e os históricos são indexados pelos motores de busca. Se você fizer sua pergunta na lista e ela for respondida, um futuro leitor poderá encontrar sua pergunta e a resposta na Web, em vez de perguntar novamente.
* Se certas perguntas são feitas com frequência, os desenvolvedores podem usar essas informações para melhorar a documentação ou o próprio software para torná-lo menos confuso. Mas se essas perguntas forem feitas em particular, ninguém terá uma visão completa de quais perguntas são feitas com mais frequência.

Se um projeto tiver tanto uma lista de discussão ou fórum online de “usuários” e outro de “desenvolvedores” (ou “hackeres”), e você não está hackeando o código, pergunte na lista / fórum de “usuário”. Não presuma que você será bem-vindo na lista de desenvolvedores, onde eles provavelmente verão sua pergunta como um ruído interrompendo o trabalho dos desenvolvedores.

No entanto, se você tiver certeza de que sua pergunta não é trivial e não obtiver resposta na lista / fórum de "usuários" por vários dias, tente os "desenvolvedores". Seria bom ficar em silêncio lá por alguns dias ou pelo menos revisar as mensagens históricas dos últimos dias, para aprender os costumes locais antes de postar (na verdade, esse é um bom conselho em qualquer lista privada ou semiprivada).

Se você não consegue encontrar o endereço da lista de discussão de um projeto, mas vê apenas o endereço do mantenedor do projeto, vá em frente e escreva para o mantenedor. Mas mesmo nesse caso, não presuma que a lista de discussão não existe. Mencione em seu e-mail que você tentou e não conseguiu encontrar a lista de e-mails apropriada. Mencione também que você não se opõe a que sua mensagem seja encaminhada a outras pessoas. (Muitas pessoas acreditam que o e-mail privado deve permanecer privado, mesmo que não haja nenhum segredo nele. Ao permitir que sua mensagem seja encaminhada, você dá ao seu correspondente a escolha de como lidar com seu e-mail.)

### Use títulos específicos e significativos

Use cabeçalhos de assuntos específicos e significativos

Em listas de discussão, grupos ou fóruns online, o cabeçalho do assunto é sua oportunidade de ouro para atrair a atenção de especialistas qualificados em cerca de 50 caracteres ou menos. Não o desperdice com balbucios como “Por favor, me ajude” (muito menos “POR FAVOR AJUDE-ME !!!!”; mensagens com assuntos como esse são descartadas por reflexo). Não tente nos impressionar com a profundidade de sua angústia; use o espaço para uma descrição superconsciente do problema.

Uma boa convenção para cabeçalhos de assunto, usada por muitas organizações de suporte técnico, é “objeto - desvio”. A parte “objeto” especifica qual coisa ou grupo de coisas está tendo um problema, e a parte “desvio” descreve o desvio do comportamento esperado.

**Estúpido:**
    AJUDA! O vídeo não funciona corretamente no meu laptop!
    
**Esperto:**
    Cursor do mouse deformado X.org 6.8.1, Fooware MV1005 vid. chipset

**Mais esperto:**
    Cursor do mouse do X.org 6.8.1 no Fooware MV1005 vid. chipset - está deformado

O processo de escrever uma descrição de “desvio do objeto” o ajudará a organizar seu pensamento sobre o problema com mais detalhes. O que é afetado? Apenas o cursor do mouse ou outros gráficos também? Isso é específico para a versão X.org do X? Para a versão 6.8.1? Isso é específico para os chipsets de vídeo Fooware? Para o modelo MV1005? Um hacker que lê pode entender imediatamente com o que você está tendo problemas e o problema que está tendo, em um piscar de olhos.

De forma mais geral, imagine olhar para o índice de um arquivo de perguntas, com apenas as linhas de assunto aparecendo. Faça com que a linha de assunto reflita sua pergunta bem o suficiente para que a próxima pessoa que pesquisar o arquivo com uma pergunta semelhante à sua consiga seguir o tópico para uma resposta em vez de postar a pergunta novamente.

Se você fizer uma nova pergunta em uma resposta, certifique-se de alterar o assunto para indicar que você está fazendo uma nova pergunta. Um assunto que se pareça com “Re: teste” ou “Re: novo bug” tem menos probabilidade de atrair quantidades úteis de atenção. Além disso, cite mensagens anteriores o mínimo suficientepara que leitores entendam sua mensagem.

Não basta clicar em responder a uma mensagem da lista para iniciar um tópico totalmente novo. Isso limitará o seu público. Alguns leitores de e-mail, como o mutt[^NT3], permitem que o usuário agrupe os emails por thread e, em seguida, esconda as mensagens de uma mesma thread. As pessoas que fazem isso nunca verão sua mensagem.

Mudar de assunto não é suficiente. O Mutt, e provavelmente outros leitores de e-mail, procuram outras informações nos cabeçalhos do e-mail para atribuí-lo a um tópico, não apenas o assunto. Em vez disso, inicie um e-mail totalmente novo.

Em fóruns online, as regras de boas práticas são ligeiramente diferentes, porque as mensagens geralmente são muito mais estreitamente vinculadas a tópicos de discussão específicos e frequentemente invisíveis fora desses tópicos. Mudar o assunto ao fazer uma pergunta em uma resposta não é essencial. Nem todos os fóruns permitem linhas de assunto separadas nas respostas e quase ninguém as lê quando o fazem. No entanto, fazer uma pergunta em uma resposta é uma prática duvidosa em si, porque só será vista por aqueles que estão acompanhando a este tópico. Portanto, a menos que você tenha certeza de que deseja perguntar apenas às pessoas atualmente ativas no tópico, inicie um novo.

### Torne fácil ser respondido

Terminar sua pergunta com “Envie sua resposta para ...” torna bastante improvável que você obtenha uma resposta. Se você não se dá ao trabalho de levar nem mesmo os poucos segundos necessários para configurar um cabeçalho Reply-To correto em seu agente de e-mail, não nos incomodamos em levar nem mesmo alguns segundos para pensar sobre o seu problema. Se o seu programa de e-mail não permitir isso, utilize um programa de e-mail melhor. Se o seu sistema operacional não oferece suporte a nenhum programa de e-mail que permita isso, utilize um sistema operacional melhor.

Em fóruns online, pedir uma resposta por e-mail é totalmente rude, a menos que você acredite que as informações possam ser confidenciais (e que alguém irá, por alguma razão desconhecida, avisar isso a você mas não a todo o fórum). Se você quiser uma cópia do e-mail quando alguém responder no tópico, peça que o fórum online a envie; este recurso é suportado em quase todos os lugares com opções como “monitorar este tópico”, “enviar e-mail com as respostas”, etc.

### Escreva em linguagem clara, respeitando a gramática e com grafias corretas

Descobrimos na prática que pessoas que são descuidados e desleixadas ao escrever geralmente também são descuidados e desleixados no pensamento e na codificação (acontece tanto que até valeria a pena fazer apostas). Responder a perguntas para pensadores descuidados e desleixados não é gratificante; preferimos gastar nosso tempo em outro lugar.

Portanto, expressar sua pergunta de maneira clara e adequada é importante. Se você não se dá ao trabalho de fazer isso, não podemos nos dar ao trabalho de prestar atenção. Faça um esforço extra para polir seu idioma. Não precisa ser rígido ou formal - na verdade, a cultura hacker valoriza a linguagem informal, gíria e bom-humor usados com precisão. Mas tem que ser preciso; deve haver alguma indicação de que você está pensando e prestando atenção.

Soletre, pontue e use maiúsculas corretamente. Não digite errado palavras parecidas. NÃO DIGITE EM MAIÚSCULAS; isso é lido como gritaria e considerado rude. (Usar apenas minúsclas é apenas um pouco menos irritante, mas é difícil de ler. Alan Cox pode se safar com isso, mas você não.)[^NT4]

De modo mais geral, se você escrever como um idiota semianalfabeto, provavelmente será ignorado. Portanto, não use atalhos de mensagens instantâneas. Soletrar "você" como "vc" faz com que você pareça um idiota semianalfabeto para salvar duas teclas inteiras. Pior: escrever como um  "l33t script kiddie hax0r" é o beijo da morte e garante que você não receberá nada além de um silêncio sepulcral como resposta (ou, na melhor das hipóteses, uma porção de desprezo e sarcasmo).

Se estiver fazendo perguntas em um fórum que não usa seu idioma nativo, você terá uma pequena margem para erros de ortografia e gramática - mas nenhuma margem extra para preguiça (e sim, geralmente podemos identificar essa diferença). Além disso, a menos que você saiba quais são os idiomas do seu respondente, escreva em inglês. Hackers ocupados tendem a simplesmente ignorar perguntas em idiomas que eles não entendem, e o inglês é o idioma de trabalho da Internet. Ao escrever em inglês, você minimiza suas chances de que sua pergunta seja descartada sem ser lida.

Se você está escrevendo em inglês, mas esse é um segundo idioma para você, é uma boa prática alertar os possíveis leitores sobre suas possíveis dificuldades com o idioma e as opções para contorná-las. Exemplos:
* Inglês não é minha língua nativa; desculpe os erros de digitação.
* Se você fala $LANGUAGE, envie um e-mail / DM para mim; Posso precisar de ajuda para traduzir minha pergunta.
* Estou familiarizado com os termos técnicos, mas algumas expressões de gíria e expressões idiomáticas são difíceis para mim.
* Publiquei minha pergunta em $LANGUAGE e em inglês. Ficarei feliz em traduzir as respostas, se você falar apenas uma ou outra.

### Envie perguntas em formatos acessíveis e padronizados

Se você tornar sua pergunta artificialmente difícil de ler, é mais provável que ela seja ignorada em favor de outra que não seja. Então:

* Envie mensagens em texto simples, não em HTML. (Não é difícil desativar o HTML em emails.)
* Anexos MIME são geralmente OK, mas apenas se forem de conteúdo real (como um arquivo de origem anexado ou patch), e não meramente clichê gerado por seu cliente de e-mail (como outra cópia de sua mensagem).
* Não envie e-mail em que parágrafos inteiros sem quebras de linha. (Isso torna muito difícil responder apenas a parte da mensagem.) Suponha que seus respondentes lerão e-mails em telas de texto de 80 caracteres e defina a quebra de linha de acordo, para algo menos que 80.
* No entanto, não agrupe dados (como despejos de arquivo de log ou transcrições de sessão) em qualquer largura de coluna fixa. Os dados devem ser incluídos no estado em que se encontram, para que os leitores possam ter certeza de que estão vendo o que você viu.
* Não use a codificação MIME Quoted-Printable em um fórum em inglês. Essa codificação pode ser necessária quando você está postando em um idioma que o ASCII não cobre, mas muitos agentes de e-mail não a suportam. Quando eles quebram, todos aqueles "=20" espalhados pelo texto são feios e perturbam - ou podem sabotar ativamente a semântica do seu texto.
* Nunca, jamais espere que os hackers sejam capazes de ler formatos de documentos proprietários fechados, como Microsoft Word ou Excel. A maioria dos hackers reage a isso tão bem quanto você faria se uma pilha fervente de merda de porco fosse despejada na sua porta. Mesmo quando podem lidar com isso, eles se ressentem de ter que fazer isso.
* Se você estiver enviando e-mail de uma máquina Windows, desative o problemático recurso “Smart Quotes” da Microsoft (em Ferramentas> Opções de autocorreção, desmarque a caixa de seleção entre aspas em AutoFormatação ao digitar). Assim, você evitará espalhar caracteres ilegíveis em seu e-mail.
* Em fóruns online, não abuse dos recursos “smiley” e “HTML” (quando eles estiverem presentes). Um ou dois emoticons geralmente são aceitáveis, mas um texto colorido e extravagante tende a fazer as pessoas pensarem que você é um idiota. O uso excessivo de smileys, cores e fontes fará com que você pareça uma adolescente risonha, o que geralmente não é uma boa ideia, a menos que você esteja mais interessado em sexo do que em respostas.

Se você estiver usando um cliente de e-mail de interface gráfica para usuários, como Netscape Messenger, MS Outlook ou algo semelhante, tome cuidado, pois ele pode violar essas regras quando usado com suas configurações padrão. A maioria desses clientes tem um comando “Exibir código-fonte” em seu menu. Use isso em alguma mensagem de sua caixa de saída, verificando o envio de texto simples sem lixo desnecessário.

### Seja preciso e informativo sobre o seu problema

* Descreva os sintomas do seu problema ou bug com cuidado e clareza.
* Descreva o ambiente em que ocorre (máquina, sistema operacional, aplicativo, qualquer que seja). Forneça a distribuição e a versão do seu fornecedor (por exemplo: “Fedora Core 7”, “Slackware 9.1”, etc.).
* Descreva a pesquisa que você fez para tentar entender o problema antes de fazer a pergunta.
* Descreva as etapas de diagnóstico que você executou para tentar identificar o problema sozinho antes de fazer a pergunta.
* Descreva quaisquer alterações recentes possivelmente relevantes na configuração do seu computador ou software.
* Se possível, forneça uma maneira de reproduzir o problema em um ambiente controlado.

Faça o melhor que puder para antecipar as perguntas que um hacker fará e responda com antecedência em seu pedido de ajuda.

Dar aos hackers a capacidade de reproduzir o problema em um ambiente controlado é especialmente importante se você estiver relatando algo que acredita ser um bug no código. Quando você faz isso, suas chances de obter uma resposta útil e a velocidade com que você provavelmente obterá essa resposta aumentam tremendamente.

Simon Tatham escreveu um excelente ensaio intitulado [How to Report Bugs Effectively](http://www.chiark.greenend.org.uk/~sgtatham/bugs.html). Eu recomendo fortemente que você o leia.

### Volume não é precisão

Você precisa ser preciso e informativo. Esse fim não é alcançado simplesmente despejando enormes volumes de código ou dados em um pedido de ajuda. Se você tiver um caso de teste grande e complicado que está quebrando um programa, tente fatiá-lo e torná-lo o menor possível.

Isso é útil por pelo menos três motivos. Um: ser visto investindo esforços para simplificar a pergunta torna mais provável que você obtenha uma resposta. Dois: simplificar a pergunta torna mais provável que você obtenha uma resposta útil. Três: No processo de refinar seu relato de bug, você mesmo pode desenvolver uma correção ou solução alternativa.

### Não se apresse em dizer que encontrou um bug
### Se diminuir não substitui fazer seu dever de casa
### Descreva os sintomas do problema, não suas suposições
### Descreva os sintomas do problema em ordem cronológica
### Descreva o objetivo, não um único passo
### Não peça para as pessoas responderem por e-mail privado
### Seja explícito sobre sua questão
### Ao perguntar sobre código
### Não mande seu dever de casa
### Elimine perguntas inúteis
### Não sinalize sua questão como “Urgente”, mesmo que realmente seja para você
### Cortesia nunca é demais e às vezes ajuda
### Envie posteriormente uma breve nota sobre a solução

## Como interpretar respostas
### RTFM e STFW: Como saber se você fez besteira
### Se você não entender...
### Lidando com grosseria

## Sobre não reagir como um otário
## Perguntas que não devem ser feitas
## Boas e más perguntas
## Se você não obtiver uma resposta
## Como responder perguntas de forma útil
## Fontes relacionadas
## Reconhecimentos


[^NT1]: Trocadilho em inglês com as palavras "user" (usuário) e "loser" (otário).
[^NT2]: Stack Exchange é um grupo de sites de perguntas e respostas do qual o Stack Overflow faz parte.
[^NT3]: É assim inclusive a visualização padrão do GMail, ferramenta atualmente (2021) mais utilizada para leitura de e-mails.
[^NT4]: Alan Cox é um desenvolvedores mantenedores do Kernel do Linux.
