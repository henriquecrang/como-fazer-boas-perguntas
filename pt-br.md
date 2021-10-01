# Como fazer perguntas de forma inteligente

## Traduções

Existem traduções para diversos idiomas listadas em http://www.catb.org/~esr/faqs/smart-questions.html#code . Caso você deseje copiar, hospedar, traduzir ou recortar esse documento, por favor veja a [política de direitos autoriais](http://www.catb.org/~esr/copying.html).

## Aviso

Muitos sites de projetos possuem links para este documento em suas seções sobre como obter ajuda. Tudo bem, é o uso pretendido - mas se você for um webmaster linkando este documento na página do seu projeto, exiba com destaque próximo ao link um alerta de que não somos um help desk para o seu projeto!

Aprendemos da maneira mais difícil que, sem esse aviso, seremos repetidamente incomodados por idiotas que acham que, por termos publicado este documento, é nosso trabalho resolver todos os problemas técnicos do mundo.

Se você está lendo este documento porque precisa de ajuda e fica com a impressão de que pode obtê-la diretamente dos autores deste documento, você é um dos idiotas de quem estamos falando. Não nos faça perguntas. Vamos apenas ignorar você. Estamos aqui para mostrar como obter ajuda de pessoas que realmente conhecem o software ou hardware com o qual você está lidando, e em 99,9% das vezes não seremos nós. A menos que você tenha certeza de que um dos autores é especialista no que você está lidando, deixe-nos em paz e todos ficarão mais felizes.

## Introdução

No mundo dos hackers, o tipo de resposta que você obtém para suas perguntas técnicas depende tanto da maneira como você faz as perguntas quanto da dificuldade de desenvolver a resposta. Este guia irá ensiná-lo a fazer perguntas de uma maneira mais provável de obter uma resposta satisfatória.

Agora que o uso do código aberto se popularizou, muitas vezes você pode obter respostas tão boas de outros usuários mais experientes quanto de hackers. Isto é uma coisa boa; os usuários tendem a ser um pouco mais tolerantes com o tipo de falhas que os iniciantes costumam ter. Ainda assim, tratar usuários experientes como hackers das maneiras que recomendamos aqui geralmente será a maneira mais eficaz de obter respostas úteis deles também.

A primeira coisa a entender é que os hackers realmente gostam de problemas difíceis e perguntas boas e instigantes sobre eles. Se não gostássemos, não estaríamos aqui. Se você nos der uma pergunta interessante para mastigar, seremos gratos a você; boas perguntas são um estímulo e um presente. Boas perguntas nos ajudam a desenvolver nosso entendimento e frequentemente revelam problemas que talvez não tenhamos percebido ou pensado de outra forma. Entre os hackers, “Boa pergunta!” é um elogio forte e sincero.

Apesar disso, os hackers têm a reputação de responder a perguntas simples com o que pode parecer hostilidade ou arrogância. Às vezes parece que somos deliberadamente rudes com os novatos e os ignorantes. Mas isso não é verdade.

O que somos, assumidamente, é hostis às pessoas que parecem não querer pensar ou fazer sua própria lição de casa antes de fazer perguntas. Pessoas assim são uma perda de tempo - levam sem retribuir e nos fazem perder tempo que poderíamos ter gasto com outra questão mais interessante ou outra pessoa mais digna de uma resposta. Chamamos pessoas assim de “otários” (e por razões históricas às vezes o soletramos “lusers”).[^1]

Percebemos que existem muitas pessoas que querem apenas usar o software que escrevemos e que não têm interesse em aprender detalhes técnicos. Para a maioria das pessoas, um computador é apenas uma ferramenta, um meio para um fim; elas têm coisas mais importantes para fazer e vidas para viver. Reconhecemos isso e não esperamos que todos se interessem pelas questões técnicas que nos fascinam. No entanto, nosso estilo de responder a perguntas é voltado para pessoas que se interessam e desejam ser participantes ativos na solução de problemas. Isso não vai mudar. Nem deveria; se assim fosse, nos tornaríamos menos eficazes nas coisas que fazemos melhor.

Somos (em grande parte) voluntários. Tiramos um tempo de nossas vidas ocupadas para responder a perguntas e, às vezes, ficamos sobrecarregados com elas. Então, filtramos implacavelmente. Em particular, jogamos fora as perguntas de pessoas que parecem ser otárias, a fim de gastar nosso tempo respondendo a perguntas de forma mais eficiente, com os campeões.

Se você achar essa atitude desagradável, condescendente ou arrogante, verifique suas suposições. Não estamos pedindo que você se ajoelhe diante de nós - na verdade, a maioria de nós adoraria nada mais do que tratá-lo como um igual e recebê-lo em nossa cultura, se você fizer o esforço necessário para tornar isso possível. Mas simplesmente não é eficiente para nós tentar ajudar pessoas que não estão dispostas a ajudar a si mesmas. É OK ser desinformado; não é OK ser estúpido.

Assim, embora não seja necessário já ser tecnicamente competente para chamar a nossa atenção, é necessário demonstrar o tipo de atitude que leva à competência - estar alerta, atento, observador, disposto a ser um parceiro ativo no desenvolvimento de uma solução. Se você não consegue conviver com esse tipo de discriminação, sugerimos que você pague alguém por um contrato de suporte comercial, em vez de pedir aos hackers que doem ajuda pessoalmente a você.

Se você decidir nos pedir ajuda, você não quer ser um dos otários. Você também não quer parecer um. A melhor maneira de obter uma resposta rápida e responsiva é perguntar como uma pessoa inteligente, confiante e com informações, que por acaso precisa de ajuda para resolver um problema específico.

(Melhorias neste guia são bem-vindas. Você pode enviar sugestões para [esr@thyrsus.com](mailto:esr@thyrsus.com) ou [respond-auto@linuxmafia.com](mailto:respond-auto@linuxmafia.com). Observe, entretanto, que este documento não pretende ser um guia geral para [netiqueta](http://www.ietf.org/rfc/rfc1855.txt) e geralmente rejeitaremos sugestões que não estão especificamente relacionadas com a obtenção de respostas úteis em um fórum técnico.)

## Antes de perguntar

Antes de fazer uma pergunta técnica por e-mail, em um grupo ou em um fórum online, faça o seguinte:

...1. Tente encontrar uma resposta pesquisando os históricos do fórum ou lista de e-mails onde você planeja postar.
...1. Tente encontrar uma resposta pesquisando na web.
...1. Tente encontrar uma resposta lendo o manual.
...1. Tente encontrar uma resposta lendo um FAQ.
...1. Tente encontrar uma resposta investigando e testando.
...1. Tente encontrar uma resposta perguntando a um amigo habilidoso.
...1. Se você é um programador, tente encontrar uma resposta lendo o código-fonte.

Ao fazer sua pergunta, mostre o fato de que você fez essas coisas primeiro; isso ajudará a estabelecer que você não está sendo uma esponja preguiçosa e desperdiçando o tempo das pessoas. Melhor ainda, mostre o que você aprendeu ao fazer essas coisas. Gostamos de responder a perguntas para pessoas que demonstraram que podem aprender com as respostas.

Use táticas como fazer uma pesquisa no Google com o texto de qualquer mensagem de erro que você receber (pesquisar tanto nos grupos de email do Google como em páginas da Web). Isso pode levá-lo diretamente a documentação ou a mensagens passadas que respondam à sua pergunta. Mesmo que isso não aconteça, dizer "Pesquisei a seguinte frase no Google, mas não encontrei nada que parecesse promissor" é uma boa coisa a fazer em uma mensagem solicitando ajuda, pelo menos porque já indica o que as pesquisas não resolveram. Isso também ajudará a direcionar futuramente outras pessoas com problemas semelhantes para o seu tópico, fazendo os termos de pesquisa apontarem para o que esperamos será a resolução do problema levantado.

Não tenha pressa. Não espere ser capaz de resolver um problema complicado com alguns segundos de busca no Google. Leia e entenda as perguntas frequentes, sente-se, relaxe e reflita sobre o problema antes de entrar em contato com especialistas. Confie em nós, eles saberão, a partir de suas perguntas, o quanto você leu e refletiu, e estarão mais dispostos a ajudar se você vier preparado. Não dispare instantaneamente todo o seu arsenal de perguntas só porque sua primeira pesquisa não apresentou nenhuma resposta (ou muitas).

Prepare sua pergunta. Pense sobre isso. Perguntas que parecem precipitadas obtêm respostas precipitadas ou nenhuma resposta. Quanto mais você fizer para demonstrar que pensou e se esforçou para resolver seu problema antes de buscar ajuda, maior será a probabilidade de realmente obter ajuda.

Cuidado para não fazer a pergunta errada. Se você fizer uma pergunta baseada em suposições errôneas, é bem provável que um hacker aleatório responda com uma resposta literalmente inútil enquanto pensa "Pergunta estúpida ...", e espera que a experiência de obter como resposta o que você merece, em vez do que você precisava, vá te ensinar uma lição.

Nunca presuma que você tem direito a uma resposta. Você não tem; afinal, você não está pagando pelo serviço. Você obterá uma resposta, se conquistá-la, fazendo uma pergunta substancial, interessante e instigante - que contribua implicitamente para a experiência da comunidade, em vez de apenas exigir passivamente o conhecimento de outras pessoas.

Por outro lado, deixar claro que você pode e deseja ajudar no processo de desenvolvimento da solução é um bom começo. “Alguém pode me dar uma direção?”, “O que está faltando em meu exemplo?” e “Qual site eu deveria ter pesquisado?” são perguntas mais propensas a obter respostas do que “Por favor me diga exatamente o que eu devo fazer”, pois aqui você está deixando claro que está realmente disposto a concluir o processo sozinho se alguém puder simplesmente apontar a direção certa.


## Quando estiver perguntando
### Escolha o local cuidadosamente
### Stack Overflow
### Web e canais no IRC
### Como segundo passo, use listas de e-mail do projeto
### Use títulos específicos e significativos
### Torne fácil ser respondido
### Escreva em linguagem clara, respeitando a gramática e com grafias corretas
### Envie perguntas em formatos acessíveis e padronizados
### Seja preciso e informativo sobre o seu problema
### Volume não é precisão
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


[^1]: Trocadilho em inglês com as palavras "user" (usuário) e "loser" (otário).
