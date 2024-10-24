# Bootcamp Analista de QA

<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\LOGO QA 10.png">

### Projeto 1
Introdução ao sprint 1
Introdução ao desenvolvimento e teste?
Neste capítulo, você vai conhecer o processo de desenvolvimento de aplicativos de ponta a ponta, entender em que estágio um testador entra em ação e aprender sobre as tarefas que essa função envolve.

Vamos conferir o que você vai aprender:

. Como o software é desenvolvido, da ideia à implementação
. O papel de um analista de QA em cada etapa do processo de desenvolvimento
. Como as equipes gerenciam as tarefas
. As etapas de uma tarefa de teste
. Como testar uma versão de lançamento do produto.

Aplicação: da ideia à remoção
Da ideia à descontinuação, cada aplicação (ou aplicativo) passa por uma série de etapas. Isso é chamado de Ciclo de Vida de Desenvolvimento de Software (SDLC, na sigla em inglês).

Vamos conferir essas etapas.<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (5).png">
Criação de ideias: nessa etapa, a equipe investiga o mercado e formula hipóteses sobre o produto. O resultado deve ser uma ideia ou conceito geral do aplicativo a ser criado.

Levantamento de requisitos: aqui são definidos os requisitos específicos do aplicativo, como o que deve ser implementado, as limitações do sistema em desenvolvimento e assim por diante.

Design: a arquitetura do futuro software é formulada. Isso pode ser na forma de documentação, especificações técnicas ou layouts, ou ainda pela compreensão de como exatamente o sistema será implementado.

Desenvolvimento e testes: nessa etapa, o aplicativo é criado. O código é escrito, os testes são realizados e correções são feitas conforme o feedback. O resultado (espera-se) é um software funcional.

Lançamento: aqui, todas as etapas necessárias foram concluídas e o software é disponibilizado para os usuários finais.

Manutenção: a equipe mantém a funcionalidade do aplicativo e corrige bugs continuamente.

Descontinuação: com o passar do tempo, o aplicativo fica desatualizado e, em algum momento, o suporte ao aplicativo é interrompido.
Objetivos do testador nas diferentes etapas do ciclo de vida de desenvolvimento de software.
Agora você conhece o ciclo de vida do desenvolvimento de software. Mas onde entra a análise de controle de qualidade? Bem, a equipe de controle de qualidade tem responsabilidades diferentes em cada etapa desse ciclo. Aqui estão algumas das responsabilidades que você pode ter como analista de QA:

Criação de ideias
Nesta etapa, um testador está envolvido no seguinte:

Compreender o conceito do produto: um testador deve se familiarizar com a ideia central do produto para projetar testes efetivos.
Analisar a lógica do produto: é essencial que os testadores compreendam como o produto deve funcionar para identificar quaisquer desvios dessa lógica durante o teste.
Identificar inconsistências lógicas: caso existam aspectos do produto que não pareçam lógicos ou coerentes, é responsabilidade dos testadores apontá-los.
Criar uma lista de cenários de usuário: os testadores devem começar a pensar nos diferentes cenários pelos quais os usuários podem passar ao usar o produto. Esses cenários serão usados no design de testes.
Levantamento de requisitos
Nesta etapa, a equipe de teste tem várias responsabilidades importantes:

Analisar os requisitos: os testadores analisam os requisitos para garantir que sejam completos, consistentes e que possam ser testados com eficácia.
Sugerir requisitos adicionais: quando os testadores identificam áreas onde requisitos adicionais poderiam ser adicionados para facilitar o processo de teste, eles devem sugerir ao restante da equipe que eles sejam adicionados.
Criar documentação de teste: os testadores começam a trabalhar na documentação de teste, que será essencial para orientar o processo nas etapas posteriores.
Design
Durante a fase de design, a equipe de teste trabalha para:

Testar a implementação: os testadores conferem se a implementação atende aos requisitos originais, como verificar se todos os elementos necessários da interface estão presentes nos designs.
Desenvolver a documentação de teste: os testadores continuam trabalhando na documentação de teste, fazendo adições e atualizações conforme necessário.
Projetar testes automatizados: os testadores começam a projetar testes automatizados para testar funcionalidades que já foram desenvolvidas.
Avaliar o volume de testes necessários: os testadores começam a avaliar quantos testes serão necessários para garantir a qualidade do produto.
Desenvolvimento e teste
Próximas ações do testador:

Concluir a documentação do teste: os testadores concluem a documentação do teste, certificando-se de que todos os aspectos do sistema foram abordados.
Testar o sistema: os testadores realizam testes do sistema em sua totalidade, procurando algum defeito ou problema que possa afetar o funcionamento ou usabilidade.
Criar testes automatizados: os testadores podem participar da criação de testes automatizados, o que pode ajudar a tornar o processo de teste mais eficiente e eficaz.
Lançamento do produto
Próximas ações do testador:

Realizar testes de regressão: os testadores realizam testes de regressão para garantir que alterações recentes não tenham incluído novos bugs no produto.
Verificar funcionalidades: os testadores verificam se todas as funcionalidades estão em desenvolvimento e funcionam conforme o esperado.
Comunicar-se com os primeiros usuários: os testadores interagem com os primeiros usuários apresentados ao produto, geralmente, através do suporte. Isso permite coletar feedback inicial e identificar quaisquer bugs perdidos nos estágios anteriores de teste.
Testes de correções de bugs: os testadores verificam as correções de bugs para garantir que foram resolvidas de forma eficaz.
Manutenção
Próximas ações do testador:

Gerenciar solicitações de usuários: os testadores gerenciam as solicitações de usuários fornecidas pela equipe de suporte, reproduzindo, verificando e corrigindo erros relatados.
Testar melhorias e novas funcionalidades: os testadores verificam todas as melhorias, correções de bugs e novas funcionalidades para garantir que tudo está operando corretamente e que novos problemas não foram inseridos no sistema.
Descontinuação
O testador confere se o restante das funcionalidades continua operando corretamente depois que outras funcionalidades foram descontinuadas.

Sua função e objetivos podem variar dependendo do projeto em que você está trabalhando.

Etapas de desenvolvimento: testar uma tarefa.
Os projetos nos quais uma equipe trabalha costumam ser divididos em tarefas. Por exemplo, criar novas funcionalidades, refinar as existentes, corrigir bugs ou até mesmo remover funcionalidades.

É mais prático acompanhar o andamento de uma tarefa em gerenciadores como o Jira. No gerenciador, elas são chamadas de tarefas ou tickets e podem ser criadas por um gerente de projeto, desenvolvedor ou outro testador.

Para acompanhar o andamento da tarefa, a equipe usa um quadro especial. Às vezes, é um painel (board) com adesivos (stickers). Cada adesivo é uma tarefa separada.

O quadro reflete claramente o período de trabalho atual, por exemplo, uma semana. Ele também pode ser usado para identificar áreas problemáticas no processo de resolução de tarefas. Por exemplo, se a tarefa permanecer em seu estado inicial durante toda a semana, algo claramente deu errado.

As tarefas são distribuídas por status, que refletem a etapa em que a tarefa se encontra no momento. O quadro pode ficar assim:

<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (6).png">
Nos cabeçalhos das colunas, você verá um conjunto de etapas possíveis pelos quais a tarefa passa durante seu ciclo de vida. Só pode haver três status na versão mais simples:
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (7).png">
O ciclo pode ser dividido em etapas condicionais:

Primeira etapa

A pessoa que define a tarefa — por exemplo, o gestor — a cria no rastreador, dá a ela o status "Aberta" e a atribui à pessoa responsável.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (8).png">
Segunda etapa

A pessoa começa a trabalhar na tarefa, e o status muda para "Em progresso".
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (9).png">
Terceira etapa

A tarefa é concluída, e o status muda para "Fechada".
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (10).png">
Em projetos reais, o processo é mais complicado. Confira:
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (11).png">
Este é um dos possíveis ciclos de vida de uma tarefa:

. O gestor cria uma tarefa, atribui a ela o status "Aberta" e atribui o desenvolvedor como responsável.
. O desenvolvedor prossegue com a tarefa e altera o status para "Em progresso."
. Quando o desenvolvimento é concluído, o desenvolvedor altera o status para "Pronta para testar." O testador recebe a tarefa.
. O testador começa a trabalhar e muda o status para "Em teste."
. Caso surjam novos problemas durante o teste, a tarefa é devolvida ao desenvolvedor para melhorias, e o status muda para "Em progresso."
. Quando o desenvolvedor corrige os bugs, e o testador verifica tudo novamente, o status muda para "Teste concluído."
. Após a conclusão da tarefa, o status muda para "Resolvida."
. Antes de fechar a tarefa, verifica-se como as funcionalidades atuam na produção. Se tudo estiver bem, o gestor confirma que a tarefa foi concluída e altera o status para "Fechada."

Teste de lançamento:
Quando dizemos que vamos lançar a próxima versão de um produto, isso é um lançamento.

A equipe de desenvolvimento cria uma nova versão de um aplicativo quando o tempo de lançamento agendado se aproxima ou quando tarefas suficientes são acumuladas no status "Teste concluído".

Criar uma nova versão do aplicativo
Primeiro, o aplicativo é desenvolvido em um ambiente local no computador do desenvolvedor.

Cada desenvolvedor escreve sua própria parte do aplicativo. Em seguida, as partes de código são combinadas. Isso acontece antes do teste ou no momento da criação de uma nova versão de lançamento do aplicativo. Essa é a compilação de lançamento, ou apenas compilação.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (12).png">
Quando a compilação fica pronta, ela é enviada para a estande de teste — um ambiente onde o testador pode testar o produto.

Nesse ponto, o testador já deve ter os scripts de teste necessários prontos para a compilação.

Tudo o que resta é verificar tudo na ordem correta:

realizar os testes de fumaça
testar as tarefas que chegaram ao lançamento
realizar os testes de regressão
Teste de fumaça

Um teste rápido que verifica se recursos críticos existentes não estão corrompidos. Se forem encontrados problemas neste ponto, testes adicionais não fazem sentido, porque as coisas mais importantes devem ser corrigidas primeiro.

Teste regressivo das tarefas que chegaram ao lançamento

Se o teste de fumaça for bem-sucedido, você pode passar a testar os recursos. Se eles não funcionarem, o lançamento não fará sentido.

Teste de regressão dos recursos restantes

Se as etapas anteriores correram bem e sem erros, será necessário realizar testes de regressão das funcionalidades restantes. O produto é testado em sua totalidade, e o conjunto de testes onde as novas funcionalidades podem ter afetado as antigas é ampliado.

A ordem dos testes pode variar dependendo da situação atual, mas quando o processo estiver estabelecido e houver tempo suficiente, pode ser assim.

O aplicativo é enviado para produção — o ambiente ou servidor com o qual os usuários finais trabalham.

Depois disso, resta apenas testar se o aplicativo foi enviado para produção com sucesso, e se os recursos novos e antigos funcionam.

Desenvolvimento e teste: conclusão
Neste capítulo, você aprendeu os fundamentos do processo de desenvolvimento e conseguiu realizar testes de regressão antes do lançamento.

Agora você sabe:

As etapas do ciclo de vida de um aplicativo
Quais tarefas um testador executa em cada etapa
Como a equipe pode organizar as tarefas
Quem muda o status das tarefas e como
Como um produto pronto para lançamento é testado
Um testador profissional está envolvido em cada etapa da vida de um software.


Introdução aos checklists
Nos capítulos anteriores, abordamos os conceitos básicos da profissão de QA. Neste capítulo, você vai começar a criar as primeiras partes da documentação de teste: os checklists.

Vamos discutir:

Como é um checklist de um teste
Como registrar os resultados do teste em um checklist
O que é um bug e como definir os resultados esperados e reais
Como criar um checklist eficaz e abrangente
Esse tópico consiste em três lições. Vamos lá!

Analistas de QA adoram um bom checklist! Um checklist é uma lista simples onde os itens são riscados conforme você conclui tarefas. Na verdade, você já deve usar checklists simples, como listas de afazeres ou de compras, para tarefas básicas em casa.

Em QA, quase todo fluxo de trabalho de teste começa com o aprendizado dos requisitos do produto ou funcionalidade. Um checklist é uma ótima maneira de registrar se os requisitos foram atendidos ou não.

Checklists de QA
No mundo de QA, um checklist é um tipo de documentação de teste com uma lista de elementos que precisamos testar. Cada afirmação (ou item) compreende duas partes: um elemento e uma descrição do comportamento esperado. Dê uma olhada:
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (13).png">
💡 Quando um analista de QA trabalha em um projeto por muito tempo, faz descrições mais curtas para economizar tempo. Por exemplo, "O teste onde clicar no botão de cadastro abre o formulário de cadastro" se torna "Clicar no botão de cadastro abre o formulário". Então, um checklist real pode ser menos detalhado.

-Vamos aprender o que é BUG:
Você sabia que "bug" significa "inseto" em inglês? Então pegue um pote de vidro e uma rede para borboletas, é hora de capturar alguns! Ok, não estamos falando sobre esse tipo de bug, mas há uma relação. De certa forma...

Bem, há uma história famosa que se repete em toda a internet. Em 9 de setembro de 1947, Grace Murray Hopper estava procurando erros em um dos primeiros computadores, chamado Mark II. O problema acabou sendo uma mariposa que ficou presa dentro dele.

Embora haja alguma verdade nessa história, o termo "bug" já vinha sendo usado há muitos anos antes disso. No entanto, esse foi o primeiro caso relatado de um bug no contexto da computação.

Um bug é uma divergência entre os resultados esperados e o resultado real de um aplicativo ou recurso. O resultado esperado descreve como o recurso deve funcionar, enquanto o resultado atual é como o serviço está funcionando.

Como criar um checklist de teste:
Um ponto, um teste
Um ponto deve incluir um requisito, item ou resultado esperado. Se você fizer isso, será mais fácil avaliar se o resultado esperado corresponde ao real.

Por exemplo, essa frase contém muitas verificações de uma vez:

A página de cadastro deve incluir o campo de e-mail, e uma mensagem de erro deve aparecer no campo e-mail se o usuário deixá-lo vazio.

Se o campo estiver realmente presente, mas uma mensagem de erro não aparecer, não ficará claro se esse teste deve ser marcado como "Aprovado" ou "Reprovado".

Você precisa decompor o teste em vários subtestes para tornar o processo de teste mais fácil:

Trabalhar com o campo e-mail

Há um campo de e-mail na página de cadastro.
Uma mensagem de erro aparece quando o usuário deixa o campo de e-mail vazio e clica no botão "Inscreva-se".
Comece as frases com um verbo no infinitivo
Fazer isso descreve a tarefa da melhor forma possível e facilita o entendimento do ponto.

Quando o checklist não tem um verbo no infinitivo, é mais difícil de entender sobre o que é o ponto:

Trabalhando com os dados do usuário durante o cadastro

E-mail e senha válidos
E-mail e senha inválidos
Usuário já cadastrado
Um verbo no infinitivo torna a tarefa mais clara: você pode ver a ação que precisa realizar ao seguir o checklist.

Verificar o cadastro

Fazer o cadastro com um e-mail e senha válidos
Fazer o cadastro com um e-mail e senha inválidos
Fazer o cadastro com um usuário já cadastrado
Nem sempre é possível seguir essa regra, porque nem todas as verificações podem ser descritas dessa forma. Por exemplo, você pode ver um ponto parecido com este: "O campo de e-mail é preenchido com o texto 'E-mail' por padrão." Não há com o que se preocupar. A dica é: se você pode começar com um verbo no infinitivo, faça isso.

Não duplique cenários de teste
Por exemplo, há uma verificação para o resultado esperado no checklist: "Há um campo de e-mail na página de cadastro". Garanta que isso não se repita em nenhum outro lugar do checklist.

Aqui estão as regras para escrever checklists eficazes que você aprendeu nesta lição:

Um assunto por verificação.
Comece com um verbo no infinitivo.
Não duplique.
Vamos ver como essas dicas podem ajudar ao escrever checklists em uma situação real de trabalho.

Por exemplo, você precisa verificar o campo "Pergunta" no Google Forms. Esse é um serviço que permite que você crie pesquisas e questionários.

O campo deve funcionar assim:

Não existem restrições de comprimento.
Qualquer caractere é permitido.
O campo contém o texto "Texto de resposta curta" por padrão.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (14).png">
O checklist pode ser assim:

Requisitos para o campo "Pergunta"

Verificar se o formulário é salvo se você inserir o texto de caractere único "B" no campo "Pergunta".
Verificar se o formulário é salvo se você inserir o texto de dois caracteres "Bo" no campo "Pergunta".
Verificar se o formulário é salvo se você inserir os símbolos !@#$;F&*()_=-'~ no campo "Pergunta".
Verificar se o campo "Pergunta" contém o valor "Texto de resposta curta" por padrão.
Neste checklist:

Cada ponto descreve um resultado esperado.
Todos os pontos começam com um verbo.
Todas as sentenças são positivas.
Verificações não estão duplicadas.
Vamos continuar falando sobre o processo de criação de checklists nos próximos sprints, então não se preocupe se algo não parecer claro por enquanto. Lembre-se que você sempre pode pedir esclarecimentos no Discord.

Onde eu posso escrever os checklists?
Em qualquer editor de texto:
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (15).png">
No Excel:
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (16).png">
Em aplicativos especiais, por exemplo, Notion:
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (17).png">

Relatórios de BUG :
Um relatório de bug deve conter alguns itens essenciais:

Um título com uma descrição exaustiva, mas breve do bug
As etapas para reproduzir o bug
Os resultados esperados e reais
A configuração do sistema onde o bug ocorreu
A prioridade de corrigir o bug
Quando seus colegas lerem o relatório sobre esse bug de logotipo, vão entender imediatamente o problema. Vejamos como um relatório de bug para esse problema pode ser:

📌ABUG-1 A página de login não abre ao clicar no logotipo "Around".

Etapas para reprodução:

Abra https://around-v1.nm.tripleten-services.com/signin?lng=pt
Clique no logotipo "Around" no canto superior direito da página
Resultado esperado: a página de login abre.

Resultado real: a página de login não abre, nada acontece.

Configuração do sistema: macOS/Windows, Google Chrome 114.0.5735.198

Prioridade: Moderada

Para entender relatórios de bug
Um relatório de bug tem diversas partes, chamadas de "campos". Alguns campos são obrigatórios, ou seja, devem ser preenchidos sempre que você criar um relatório de bug. Outros campos são opcionais. Vejamos os campos obrigatórios primeiro:

Nome do campo	Definição
ID	Um identificador exclusivo de relatório de bug
Título	Uma breve descrição do bug
Prioridade e Severidade	A criticidade do bug e a urgência de corrigi-lo
Configuração do sistema	Os sistemas operacionais, navegadores ou versões de aplicativos onde o bug aparece
Etapas para reprodução	Um caso de teste ou um guia sobre a reprodução do bug
Resultados reais e esperados	Uma descrição dos resultados reais e esperados
Vamos considerar os campos opcionais:

Nome do campo	Finalidade
Descrição	Criado se o título não tiver informações sobre o defeito
Materiais adicionais	Adicionado para ajudar a ilustrar um bug (exemplos: uma captura ou gravação da tela)
Pré-condição	Adicionado quando o sistema precisa de preparação antes do teste
Pós-condição	Adicionado se for necessário retornar o sistema ao seu estado original após o teste.
💡 Observação: o que é necessário pode variar conforme a empresa e/ou projeto. Sua futura empresa pode exigir alguns desses campos opcionais ou vice-versa.
Títulos de relatórios de bug: 
- O título de um relatório de bug descreve a essência do problema. O objetivo é economizar o tempo dos seus colegas, oferecendo uma visão geral do problema rapidamente. Por essa razão, o título do relatório de bug costuma ser chamado de resumo do bug.

Vamos falar sobre como reproduzir bugs: reproduzir um bug é encontrar o mesmo bug no software encontrado pelo analista de QA para corrigi-lo ou investigá-lo mais a fundo. Afinal, é muito difícil para um desenvolvedor corrigir um bug se não conseguir descobrir como ele acontece.
- Severidade e prioridade:
  

- Cada bug é diferente. Uma maneira pela qual eles podem ser categorizados é pelo seu nível de influência no sistema, o que costuma ser chamado de severidade:

- Bugs bloqueadores: com esses bugs, nenhum dos elementos do sistema funciona. Por exemplo, se você estiver testando um site e a página principal não carregar devido a um bug, você está lidando com um bug bloqueador.
- Bugs críticos: ocorrem quando uma parte importante do sistema não funciona de maneira adequada. O sistema é operável, mas a probabilidade de falha é grande. Por exemplo, podemos estar lidando com um bug crítico quando o botão "Comprar" não funciona depois que o usuário faz login em sua conta, mas a loja ainda funciona normalmente enquanto os usuários não fizerem login.
- Bugs graves: nesse caso, o sistema funciona, mas não como deveria. Basicamente, todos os recursos estão ativos, mas não funcionam conforme esperado. Por exemplo, em vez do desconto de 5% prometido, uma loja online oferece 3% de desconto sempre que um cliente clica no botão "Comprar". O desconto de 3% é bom, mas não é o que a equipe de marketing planejou.
- Bugs pequenos: nesse caso, o sistema funciona, mas é inconveniente usá-lo. Por exemplo, imagine que há um defeito no design da seção "Produtos" de uma loja online. Isso não impede os usuários de comprarem os produtos, mas é uma experiência desagradável.
- Bugs triviais: esses bugs não afetam a funcionalidade do programa. Seria como um erro de texto, onde a seção "Chaleiras" de uma loja online tem um erro no nome e o plural não é usado, exibindo "Chaleira", por exemplo. Esses bugs costumam ser fáceis de corrigir.
  - Prioridade : 
A segunda maneira de classificar os bugs é por prioridade. A prioridade de bugs é diferente da severidade, pois depende do impacto causado na empresa ou organização.

Em geral, quanto maior a prioridade, mais rápido você vai precisar corrigir o defeito:

- Prioridade alta: o bug está causando grandes interrupções e deve ser corrigido o mais rápido possível! Exemplo: se os usuários não conseguirem realizar compras em uma loja online.
- Prioridade média: o bug não é crítico, mas está causando problemas que causam algum impacto na empresa. Exemplo: se a classificação não funcionar na seção "Produtos".
- Prioridade baixa: esses bugs podem esperar. Eles precisam ser corrigidos, mas só após os bugs de prioridade alta e média serem resolvidos. Exemplo: a seção "Chaleiras" em uma loja online exibindo o nome "Chaleira."
- É importante observar que, embora muitas vezes exista uma ligação entre a severidade e prioridade, podem existir todas as combinações possíveis. Por exemplo, você pode ter um bug de severidade alta (crítico), mas de prioridade baixa.


Configuração do sistema:
Imagine que você comprou uma máquina de lavar roupas há alguns meses. De repente, ela para de funcionar e você a devolve à loja onde comprou. O gerente quer enviá-la para manutenção, mas concorda em trocá-la por uma nova.

Para você, a situação foi resolvida, mas para a loja e o fabricante, ainda há muito o que fazer. O fabricante pede à loja para fornecer o número do lote (por exemplo, a "versão" do produto), bem como uma descrição das condições em que a máquina era usada. Essas informações serão importantes no reparo do problema e para determinar se outras máquinas também terão o mesmo defeito.

De um modo parecido, no mundo de QA, um bug talvez só apareça sob certas condições específicas. Por exemplo, talvez ele só apareça para usuários de tablets ou em um determinado navegador. É por isso que, além do que já mencionamos, um relatório de bug também deve incluir a configuração do sistema.

A configuração do sistema descreve a configuração específica na qual o bug aparece. Isso pode variar de acordo com o projeto e aplicativo. Por exemplo, se você estiver testando um aplicativo web, deve incluir o seguinte:

Versão do aplicativo
- Tipo do navegador: Chrome, Firefox, Safari ou Microsoft Edge
- Versão do navegador: Por exemplo, Safari 16.4.1
- Sistema operacional (SO): Windows, macOS, Linux, Android ou iOS
Versão do SO: Por exemplo, Windows 11
- Se você estiver usando um PC ou notebook, geralmente não é necessário incluir os detalhes do dispositivo. Contudo, ao testar em um dispositivo móvel, será necessário considerar algumas coisas importantes:

- Tipo de dispositivo: smartphone, tablet ou smartwatch
Modelo do dispositivo: Por exemplo, Samsung S23.


Casos de teste:
Você está pegando o jeito! Criar relatórios de bug foi um passo importante, mas, agora, vamos aprimorar suas habilidades. É hora de aprender sobre os casos de teste. Como analista de QA, você vai criar casos de teste com frequência, então vamos lá:

Um caso de teste (às vezes chamado de cenário de teste) descreve o processo de verificação real de que um produto ou recurso está funcionando conforme esperado. Os casos de teste e relatórios de bug possuem uma estrutura parecida, mas existem diferenças importantes:

Um caso de teste ajuda o testador a entender se um aplicativo está funcionando adequadamente. Esses casos costumam ser reutilizados quando um aplicativo é atualizado para verificar se os recursos ainda funcionam conforme esperado.
Os casos de teste ajudam os testadores a encontrar os bugs. Os relatórios de bug, por sua vez, registram um bug que já foi encontrado.
Composição dos casos de teste
Os casos de teste geralmente devem incluir:

ID
Título
Etapas de teste
Resultado esperado
💡 Dica profissional: dependendo da complexidade do caso de teste e as etapas de teste necessárias, o resultado esperado pode ser especificado para cada etapa ou apenas para o resultado geral.

Testadores também indicam os seguintes elementos em um caso de teste:

Pré-condição: é qualquer coisa que deve ser feita ou condições que devem ser atendidas antes da execução de um teste.
Pós-condição: é o estado em que o sistema deve estar depois da execução do caso de teste.
Sistema operacional (SO): os bugs nem sempre ocorrem em todos os sistemas operacionais para os quais o software foi desenvolvido.
Tipo de dispositivo: é o dispositivo que deve ser usado para testar o produto de software (por exemplo, o tipo de smartphone).
Breve descrição do objetivo para mostrar quais requisitos o caso de teste abrange.
Link para os requisitos: é útil para se referir aos requisitos que usamos ao criar um caso de teste.
Tag: elas costumam ser dadas ao caso de teste dependendo do fatiamento, por exemplo, regressão e fumaça.
Outros componentes: versão do software, nomes dos elementos que precisam de testes e o perfil/permissões do usuário.
E agora? Estados dos casos de teste
Você concluiu um caso de teste e obteve um resultado real — e talvez tenha sido diferente do resultado esperado! De qualquer forma, você vai precisar atribuir um "estado" ao seu caso de teste. Esse status vai deixar claro se tudo está funcionando conforme o esperado ou se você identificou um bug que precisa ser corrigido. Esse processo é importante porque reflete a qualidade geral do produto.

Na dscricão abaixo, há três opções de estado, dependendo de como os resultados reais e esperados são comparados:

O resultado esperado correspondeu ao resultado real?	Estado	Comentário	O que fazer
Tudo correspondeu!	Aprovado	O teste foi aprovado.	Vá para o próximo caso de teste.
O resultado real não correspondeu ao resultado esperado.	Reprovado	O teste foi reprovado.	Crie um relatório de bug.
Não foi possível testar.	Ignorado	O resultado não pode ser obtido.	Discuta os detalhes do caso de teste com colegas ou crie um relatório de bug.
Vamos falar um pouco mais sobre o estado "Ignorado". Podemos atribuir esse estado quando:

Não é possível replicar a pré-condição.
Não há informações suficientes (por exemplo, sem o nome de usuário do administrador e/ou senha).
O serviço está indisponível, portanto, você não pode executar os casos de teste.

Erros comuns ao escrever casos de teste
Testadores iniciantes podem cometer erros quando escrevem casos de teste. Vejamos alguns erros comuns:

- O caso de teste não possui dados de teste.
- Os títulos dos casos de teste estão duplicados.
- Um caso de teste contém vários cenários de teste.
- O ID do caso de teste não foi especificado.

Relatório de resumo de testes
Você tem alguns casos de teste, ótimo! Mas, espere, o que você vai fazer com eles? Bem, você vai executar os testes e depois vai escrever um relatório de resumo dos testes.

Um relatório de resumo dos testes fornece uma visão geral das atividades realizadas durante os testes. Esse documento descreve os objetivos do teste, escopo, casos de teste executados, bugs encontrados e outras informações relevantes. Ele permite que a equipe do produto obtenha uma visão geral abrangente dos testes realizados, ajuda a identificar áreas de melhoria, garante que todos os requisitos do produto foram atendidos e fornece uma base para a tomada de decisões.

<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (18).png">
Um relatório detalhado, como o acima, vai ajudar você a comunicar facilmente os detalhes dos testes realizados.

No entanto, analistas de QA costumam criar relatórios menos detalhados. Nesses casos, o relatório de resumo de testes possui menos campos, contendo apenas elementos essenciais, como ID do caso de teste, um título conciso e seu status. Por exemplo:

Resumo do teste: Trabalhar com cartões (versão curta)

ID	           / Caso de teste	            /   Status
AROUND-1	/ Adicionar um novo cartão /	Aprovado
AROUND-2	/ Visualizar seu próprio cartão	/ Ignorado
AROUND-3	/ Excluir um cartão	/ Aprovado
Esse relatório mostra claramente o resultado de três casos de teste: nenhum bug foi detectado, mas um recurso (visualizar seu próprio cartão) não foi testado. Você pode passar essa informação aos seus colegas, e eles vão decidir como proceder.

💡 Se algum bug for encontrado, será necessário criar um relatório de bug. Para poupar tempo, é uma prática recomendada indicar o ID, o título e a criticidade do relatório de bug correspondente próximo ao ID do caso de teste no relatório de resumo.

Teste de fumaça
Realizar um teste de fumaça significa verificar se as principais partes de um aplicativo funcionam como escrito na documentação. O nome vem dos testes de eletrônicos antigos: se algo não pegar fogo na primeira vez que for ligado, passou no teste de fumaça.

Sprint 1: Noções Básicas de Teste


Capítulo 5/8
Casos de teste
Teste de fumaça



Clique para acessar a lição no formato de texto

Realizar um teste de fumaça significa verificar se as principais partes de um aplicativo funcionam como escrito na documentação. O nome vem dos testes de eletrônicos antigos: se algo não pegar fogo na primeira vez que for ligado, passou no teste de fumaça.



📸 Imagine que você esteja vendendo uma câmera. O comprador testa a câmera conferindo se ela liga, tira e salva fotos.

Realizamos testes de fumaça para garantir que as funcionalidades essenciais de um serviço estejam funcionando corretamente. Isso significa que você não precisa testar cada elemento a fundo. Imagine que os desenvolvedores da sua empresa adicionaram uma nova funcionalidade em um aplicativo de pedir táxi. Com ela, é possível salvar o endereço das rotas frequentes na seção "Meus endereços". Agora, o analista de QA deve fazer o teste de fumaça e garantir que o aplicativo esteja funcionando conforme esperado depois da atualização.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (19).png">

Testes de fumaça são necessários quando:

- O aplicativo foi pouco alterado: se apenas funcionalidades pequenas foram atualizadas (um novo plano de fundo para botões, uma nova etiqueta, etc.), serão necessários apenas alguns testes de fumaça.
- Não há tempo suficiente para testes mais abrangentes: às vezes, a falta de tempo exige que um projeto seja entregue em seu estado atual. Testes de fumaça ajudam a garantir que o aplicativo não está quebrado.

Teste de regressão
Os testes de regressão são usados para verificar se todos os elementos existentes de um aplicativo funcionam da mesma forma que funcionavam antes de uma atualização. Em outras palavras, o teste de regressão verifica se nada quebrou como resultado das novas alterações.

Você pode estar se perguntando por que isso é chamado de teste de regressão. O termo "regressão" refere-se a situações em que o software anteriormente funcional começa a mostrar erros ou defeitos após as alterações serem feitas – daí a necessidade de testes de regressão.

Testes de regressão geralmente envolvem um conjunto completo de testes. Na verdade, testes de fumaça também são parte do teste de regressão. Porém, é importante lembrar que o teste de regressão não é o teste "inicial" realizado (caso contrário, não haveria possibilidade de regressão). Durante o teste de regressão, os testadores primeiro executam testes de fumaça para verificar se os principais elementos de um aplicativo funcionam conforme esperado. Depois disso, eles podem executar o resto dos testes.
SPRINT 2 Alterando meu README

Projeto-2

- Introdução à análise de requisitos
Aqui, você vai começar a aprender tudo que precisa para realizar testes de forma independente do zero. A primeira etapa nesse processo é a análise de requisitos. Durante essa etapa, um analista de QA estuda os requisitos do aplicativo (ou aplicação) para entender o que se espera do produto testado.

💡 Os requisitos do aplicativo descrevem as principais características e funcionalidades dele. Eles são cruciais para os testes, pois ajudam a entender o resultado esperado – o que se espera que o aplicativo faça e como.
Para iniciar a análise de requisitos, você precisa obter os requisitos, é claro. Normalmente, um analista de QA recebe requisitos de um gerente; sem eles, você não pode começar a trabalhar em uma tarefa de teste.

Durante a análise de requisitos, você precisa decompor e visualizar os requisitos e então encontrar áreas cinzentas.
Para iniciar a análise de requisitos, você precisa obter os requisitos, é claro. Normalmente, um analista de QA recebe requisitos de um gerente; sem eles, você não pode começar a trabalhar em uma tarefa de teste.

Durante a análise de requisitos, você precisa decompor e visualizar os requisitos e então encontrar áreas cinzentas.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (20).png ">
Análise de requisitos: identificação de objetos de teste

A primeira etapa será identificar objetos de teste nesses requisitos. Isso significa definir o que você vai precisar testar, o que vai ajudar em todas as próximas etapas da análise de requisitos.

O que são objetos de teste
Objetos de teste são partes do aplicativo que precisam ser testadas. Eles são identificados durante a análise de teste.

Digamos que uma empresa desenvolveu um servidor de e-mail — um aplicativo para trocar e-mails. Com a última atualização, o aplicativo ganhou um novo recurso: agora ele pode identificar mensagens de spam e armazená-las em uma pasta separada.

Primeiro, um analista de QA não vai testar o aplicativo inteiro, mas vai se concentrar em uma função específica. Nesse caso, lidar com spam — esse se torna o objeto de teste.

Vamos identificar os objetos de teste nos requisitos do aplicativo Urban Routes.

Requisitos funcionais
A seção requisitos funcionais descreve como o aplicativo deve funcionar. Com base nesses requisitos e designs, um desenvolvedor escrever o código e um analista de QA projeta os testes.

Tente analisar os requisitos funcionais do Urban Routes e identificar vários objetos de teste.

💡 Os objetos de teste representam a funcionalidade descrita nos requisitos.

Por exemplo, os requisitos declaram: "Existem os seguintes botões de seleção do modo de rota: "Optimal," "Flash" e "Personal", e também botões de seleção do tipo de transporte: carro pessoal, compartilhamento de carro, táxi, scooter, bicicleta e a pé.”

Como testador, você precisa verificar o seguinte:

A seção do modo de rota possui os botões necessários.
Cada botão desempenha sua função (por exemplo, o botão "Optimal" atribui automaticamente o tipo de transporte, cria uma rota e exibe o tempo e o custo da viagem).
Os objetos de teste para essa parte dos requisitos serão a seleção do modo de rota e os botões do tipo de transporte.

Agora vamos dar uma olhada em outro requisito: "Se o campo 'De' for preenchido incorretamente, o ponto A não será exibido."

Você precisa verificar se ele realmente não é exibido. O objeto de teste aqui é o campo "De".

Restrições para os campos de entrada de endereços
A próxima seção dos requisitos do Urban Routes descreve o formato dos dados dos campos de entrada de endereço, "De" e "Para":

Apenas letras latinas, números, espaços, traços, pontos e vírgulas
Pode ter de 1 a 50 caracteres
Você precisa verificar se o campo aceita apenas dados nesse formato. Por exemplo, deve ser possível digitar "1300 1st St", mas não "1300 / 1st St" (pois a barra / não é aceitável).

Layouts
Os requisitos descrevem determinados aspectos da aparência de um aplicativo. Layouts costumam acompanhar os requisitos, já que uma representação visual de uma interface é mais intuitiva para a maioria das pessoas.

Decomposição de requisitos
Agora que você conheceu os requisitos, pode passar para a primeira etapa da análise de requisitos: a decomposição.

A decomposição é uma etapa importante que torna o design de testes mais fácil. Antes de prosseguir, vamos ver onde a decomposição se encaixa no quadro geral.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (21).png">
Para analisar os requisitos corretamente, você deve realizar as seguintes etapas:

Decompor: dividir cada requisito em blocos atômicos. Você vai aprender o que isso significa mais adiante na lição.
Visualizar: criar gráficos ou diagramas simples (mapas mentais e fluxogramas) para entender como os blocos atômicos se encaixam.
Pesquisar áreas cinzentas: procurar cenários que talvez os requisitos não mencionem explicitamente.
Por que decompor?
Os requisitos não são escritos perfeitamente. Trabalhar em uma tarefa grande e complexa é como resolver um quebra-cabeça gigante. Se você já tentou montar um desses, sabe que é muito difícil apenas olhar as peças no chão e saber exatamente como tudo se encaixa.

Então, como você começa? Uma abordagem é olhar a imagem na caixa e começar a dividir as peças em seções para descobrir com quais partes trabalhar. Por exemplo, você pode fazer uma divisão mental em formas, cores ou regiões distintas e começar daí.

Nos testes, seguimos um processo semelhante: ao pegar um objeto ou requisito de teste e o decompor logicamente, podemos testar partes individuais.

Como decompor requisitos
Você pode seguir estas três regras simples ao decompor requisitos:

Os requisitos muitas vezes podem ser decompostos em várias partes.
Os requisitos devem ser decompostos em blocos atômicos.
Os requisitos não devem ser decompostos além da descrição.
Vejamos cada uma delas com mais detalhes.

1. Você geralmente pode dividir um requisito em diversas partes.
Digamos que você estudou os requisitos do Urban Routes e identificou um objeto de teste: o formulário de seleção de endereço. O formulário contém dois campos de entrada: "De" e "Para". Essas são as partes menores nas quais você pode dividir um único requisito de formulário de seleção de endereço.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (22).png">
2. Os requisitos são decompostos até o nível atômico, o que significa que não podem ser reduzidos mais que isso.
Por exemplo, você pode decompor as restrições de entrada do campo "De" da seguinte forma:

Entrada — letras latinas
Entrada — números
Entrada — espaços
Entrada — traços
Entrada — pontos
Entrada — vírgulas
Entrada — de 1 a 50 caracteres
Entrada — mais de 50 caracteres
Esse é o nível atômico: você não pode detalhar esse requisito além disso.

<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (23).png">
3. Os requisitos não devem ser decompostos além da descrição.
Por exemplo, se os requisitos para o campo "De" não disserem nada sobre letras maiúsculas e minúsculas, será suficiente verificar as letras do alfabeto latino. Você não precisa criar uma decomposição para letras maiúsculas e minúsculas.


- Visualização de requisitos
A visualização é a próxima etapa depois da decomposição. Um gráfico ilustrativo vai ajudar você a estruturar e compreender as informações dos requisitos de maneira mais fácil.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (24).png">
Mapa mental
Imagine que você esteja testando uma página de login e recebe os seguintes requisitos:

◻️ Há um título "Esta é a página de login" no meio da página e um subtítulo com o texto "Insira seus dados para acessar a plataforma". Abaixo do título estão os campos de entrada "Nome de usuário" e "Senha". O nome de usuário deve conter entre 8 e 10 caracteres e apenas letras latinas. A senha deve conter 8 dígitos, mas não pode ter mais de 3 dígitos repetidos. No campo "Senha", há um link azul que diz "Esqueceu sua senha?" e leva à página de redefinição de senha. Depois disso, existem dois botões: à direita, o botão "Login", que redireciona para a página inicial se todos os dados estiverem corretos, e à esquerda, o botão "Cadastre-se", que possui um rótulo acima com o texto "Ainda não tem uma conta?"

São muitas informações! Com um texto tão longo, pode ser um pouco difícil entender os requisitos. Sem mencionar que você pode encontrar requisitos ainda maiores e mais complexos.

Para entender melhor esses requisitos, você pode dividi-los em seções — por exemplo, funcionalidade e interface — e visualizá-los como um mapa mental:

Um mapa mental é um método de visualização de relacionamentos associativos. É uma maneira prática para um analista de QA visualizar os requisitos. Você pode desenhar um mapa mental após a decomposição ou em paralelo com ela.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (25).png">
Após desenhar um mapa mental como esse, você vai entender melhor os requisitos e vai poder retornar ao mapa mental caso precise atualizar algo necessário no aplicativo.

Fluxograma
Enquanto um mapa mental mostra o que está no aplicativo, um fluxograma descreve como o aplicativo funciona.

Um fluxograma mostra a ordem das etapas que devem ser seguidas para resolver uma tarefa específica em um aplicativo.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (26).png">
Digamos que você queira cadastrar uma conta da Netflix e pagar por uma assinatura. Essas são duas funcionalidades diferentes, o que significa que deve haver um fluxograma para cada uma.

Um fluxograma também descreve o comportamento de um aplicativo se algo for feito de maneira incorreta. Por exemplo, colocar um endereço de e-mail inexistente ou esquecer de vincular um cartão bancário.

Como desenhar um mapa mental
Para criar um mapa mental, é preciso dividir os requisitos em elementos que melhor descrevem as funções.

Por exemplo, você pode usar os requisitos decompostos da lição anterior:
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (27).png">
Aqui está um mapa mental que você pode obter ao criar uma visualização desses requisitos:
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (28).png">
💡 O principal objetivo de um mapa mental é agilizar o processo de teste: você não vai precisar consultar os requisitos o tempo todo se o seu mapa mental for detalhado o suficiente. Ele serve como um guia completo, permitindo que você entenda os requisitos e faça o design dos testes de maneira mais eficaz.
Como desenhar um fluxograma
Veja o fluxograma que descreve a interação entre um pedestre e os semáforos:
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (29).png">
Cada elemento no fluxograma representa uma etapa. Os elementos são conectados por linhas com setas que mostram a direção.

Aqui estão as formas geométricas mais comuns em fluxogramas:

Um retângulo arredondado representa o começo e o fim de um fluxograma.
Um retângulo comum representa uma ação. Por exemplo: "Pare".
Um paralelogramo representa entrada e saída. Por exemplo, inserir um nome de usuário.
Um diamante representa uma condição. O processo vai continuar em uma ramificação que corresponda ao resultado. Por exemplo: O sinal de pedestre está sendo mostrado? A condição foi atendida? O valor está correto?
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (30).png">
Você pode criar a visualização dos requisitos em um pedaço de papel ou usar estas ferramentas online:

draw.io
Miro
XMind
lucidchart
A diferença entre mapas mentais e fluxogramas
Tente se lembrar da diferença entre um mapa mental e um fluxograma:

Um mapa mental mostra os elementos constituintes de um aplicativo de maneira estruturada.
Um fluxograma ilustra a maneira como uma função funciona do início ao fim. Desenhar fluxograma vai ajudar a entender melhor como um aplicativo é construído, além de desenvolver seu pensamento analítico.
Ambos vão ser úteis durante os testes.

💡 Visualizar requisitos é uma tarefa criativa que pode ser abordada de diferentes maneiras. Isso significa que você pode desenhar diferentes mapas mentais para o mesmo conjunto de requisitos. No entanto, no geral, você não vai ter muitas opções diferentes para desenhar fluxogramas, pois eles representam regras consistentes de como um aplicativo deve funcionar.

- Áreas cinzentas e pesquisa de requisitos
As pessoas costumam escrever coisas com base em sua compreensão ou expectativas. No entanto, muitas vezes, elas sem querer presumem que os outros têm o mesmo conhecimento ou expectativas que elas. Quando as informações nos requisitos não são suficientes para entender por completo alguma funcionalidade, isso significa que encontramos áreas cinzentas. Nesta lição, você vai aprender como identificá-las.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (31).png">
Sprint 2: Design de Teste

- Análise de requisitos
- Áreas cinzentas e pesquisa de requisitos


As pessoas costumam escrever coisas com base em sua compreensão ou expectativas. No entanto, muitas vezes, elas sem querer presumem que os outros têm o mesmo conhecimento ou expectativas que elas. Quando as informações nos requisitos não são suficientes para entender por completo alguma funcionalidade, isso significa que encontramos áreas cinzentas. Nesta lição, você vai aprender como identificá-las.
Um exemplo, você pode usar o aplicativo do Urban Routes , parra fazer está verificação.



Estude os requisitos do Urban Routes e identifique quais desafios você pode encontrar:

Requisitos não especificados e incompletos. Muitas vezes, você só vai notar isso após reler os requisitos algumas vezes. Por exemplo, como o sistema deveria reagir se colocarmos o mesmo endereço nos campos "De" e "Para"? Deve haver uma mensagem de erro? Ou a rota deve ser criada?
Requisitos implícitos. Os autores da documentação costumam excluir os requisitos que acreditam serem óbvios. Por exemplo, o logotipo do Urban Routes no canto superior esquerdo deve ser clicável: ao clicar nele, a página principal do aplicativo Routes deve ser aberta.
Os designs e requisitos não correspondem. Por exemplo, os designs do Routes possuem a seguinte ordem de tipo de transporte: carro particular, a pé, táxi, bicicleta, scooter e compartilhamento de carro. Já nos requisitos é especificada a seguinte ordem: carro particular, compartilhamento de carro, táxi, scooter, bicicleta e a pé.
Faltam requisitos. Isso também acontece. Por exemplo, os requisitos para o Routes não descrevem as funcionalidades de alguns elementos no mapa. Por exemplo, os botões do Mapa/Satélite estão presentes nos designs, mas não está descrito como eles devem funcionar.
O que fazer ao encontrar áreas cinzentas
Continue tentando: digamos que você clique em um botão na interface do Urban Routes e não tenha certeza sobre o que vai acontecer, pois os requisitos não estão claros. Você pode tentar diferentes cenários, como atualizar a página. Não hesite em tentar métodos aleatórios!
Verifique cenários de teste semelhantes: examine casos de teste semelhantes para ver se há pistas. Não se esqueça de revisar tudo isso para dominar sua tarefa! Uma solução que você encontrou anteriormente para uma área cinzenta pode ser útil de novo mais tarde.
Esclareça os requisitos: após identificar as áreas cinzentas, é essencial pedir às pessoas certas que as esclareçam. Lembre-se, a comunicação é fundamental! Isso pode variar entre projetos e empresas, mas o ideal é perguntar a um gerente de produto ou analista. Pergunte sobre o conceito do aplicativo e as expectativas do usuário e informe sobre as áreas cinzentas que você encontrou. Essas pessoas vão ter uma resposta ou você pode conferir com o cliente. Elas podem até atualizar os requisitos.
Dicas:

Tente imaginar como o aplicativo deveria funcionar. Coloque-se no lugar do usuário: tudo está claro e é conveniente?
Faça perguntas: qual a finalidade de um objeto de teste específico, como ele funciona e a quais outros elementos ele está conectado?
Elabore um plano de teste e descubra quais tipos de testes são necessários para a funcionalidade. Isso vai tornar os requisitos necessários mais transparentes.
As áreas cinzentas são como um quebra-cabeça a ser resolvido. Para resolvê-las, prepare-se para fazer perguntas e explorar!

A quem perguntar sobre as diferentes áreas cinzentas
A comunicação é fundamental quando se trata de esclarecer os requisitos. Caso encontre áreas cinzentas, você pode perguntar às seguintes pessoas:

Desenvolvedor: pergunte sobre a implementação dos requisitos no código.
Gerente de produto ou analista: pergunte sobre o conceito de um aplicativo, as expectativas do usuário e as inconsistências entre os requisitos e os designs.
Designer: pergunte sobre os cenários de caso de teste de um aplicativo e seus designs.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (32).png">
A comunicação interna é muito importante: sem ela, a equipe pode ter informações incompletas sobre uma tarefa ou dúvida.

É essencial que você sempre faça as perguntas necessárias para resolver uma tarefa. Testadores iniciantes costumam fazer suposições em vez de fazer perguntas, o que pode tornar o trabalho em uma tarefa mais longo ou até mesmo causar erros. Portanto, nunca hesite em pedir esclarecimentos quando necessário.

- Testes funcionais e não funcionais
Os requisitos (e, portanto, os testes) podem ser funcionais ou não funcionais.
Requisitos e testes funcionais
Testes funcionais visam verificar a funcionalidade de um produto de software. Essencialmente, o analista de QA deve garantir que tudo funciona conforme descrito nos requisitos.

O teste funcional pode analisar o seguinte:

A lógica de um sistema: por exemplo, testa a lógica que determina como o custo de uma viagem é calculado.
Interação do usuário com um serviço: por exemplo, como a escala de um mapa muda quando você clica nele.
Exibição de dados: por exemplo, como as informações sobre uma viagem são exibidas para o usuário.
Um requisito funcional pode ser mais ou menos assim: "Ao preencher o campo 'Para' e clicar no botão 'Enviar', o aplicativo deve enviar um e-mail para o endereço indicado." Ele descreve o que o aplicativo pode executar. Em outras palavras, descreve sua funcionalidade.

Para verificar se um aplicativo atende aos requisitos funcionais, são realizados testes funcionais.

Vejamos um exemplo de teste funcional. Imagine que você esteja testando o site do Google para confirmar se, ao clicar no logotipo no canto superior esquerdo da página de busca, a página inicial do Google é aberta.
Requisitos e testes funcionais
Testes funcionais visam verificar a funcionalidade de um produto de software. Essencialmente, o analista de QA deve garantir que tudo funciona conforme descrito nos requisitos.

O teste funcional pode analisar o seguinte:

A lógica de um sistema: por exemplo, testa a lógica que determina como o custo de uma viagem é calculado.
Interação do usuário com um serviço: por exemplo, como a escala de um mapa muda quando você clica nele.
Exibição de dados: por exemplo, como as informações sobre uma viagem são exibidas para o usuário.
Um requisito funcional pode ser mais ou menos assim: "Ao preencher o campo 'Para' e clicar no botão 'Enviar', o aplicativo deve enviar um e-mail para o endereço indicado." Ele descreve o que o aplicativo pode executar. Em outras palavras, descreve sua funcionalidade.

Para verificar se um aplicativo atende aos requisitos funcionais, são realizados testes funcionais.

Vejamos um exemplo de teste funcional. Imagine que você esteja testando o site do Google para confirmar se, ao clicar no logotipo no canto superior esquerdo da página de busca, a página inicial do Google é aberta.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (33).png">
Os requisitos indicam: "Clicar no logotipo, no canto superior esquerdo, redireciona o usuário para a página inicial".

Os testes para esse requisito são funcionais, pois avaliam uma funcionalidade específica do aplicativo: a capacidade do logotipo do Google, quando clicado, de redirecionar o usuário para a página inicial.

Os testes funcionais visam verificar se o aplicativo se comporta conforme esperado do ponto de vista do usuário; neste caso, garantir que a navegação até a página inicial funcione corretamente.

Requisitos e testes não funcionais
Testes não funcionais verificam as características de um sistema. A documentação do produto geralmente também contém requisitos não funcionais. Eles referem-se às características do produto que não afetam diretamente a funcionalidade.

Por exemplo, um requisito não funcional para o site do Google poderia ser: "O redirecionamento da página de pesquisa para a página inicial é concluído em 0,5 segundo".
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (34).png">
Nesse caso, nosso foco não é apenas verificar a funcionalidade do botão, mas testar a rapidez do redirecionamento.

Vejamos outro exemplo. A equipe decidiu atualizar o aplicativo Urban Routes com um novo recurso — um botão para alternar idiomas para que o aplicativo possa ser facilmente usado em diferentes países. Veja os requisitos para este novo recurso:

"O botão para trocar o idioma deve ser adicionado no canto superior direito do Urban Routes. Ele deve ser um menu suspenso com os seguintes idiomas: inglês, espanhol e português. Inglês é selecionado por padrão. Depois que o usuário seleciona um idioma no menu suspenso, a interface do aplicativo é traduzida para o idioma selecionado.”

Para verificar o aplicativo de acordo com esses requisitos, precisamos verificar o seguinte: 

Se o aplicativo é alterado para o idioma selecionado (teste funcional)
Se todos os elementos foram traduzidos corretamente para o idioma selecionado (testes não funcionais)
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (35).png">
Os testes não funcionais ajudam a testar um aplicativo de acordo com critérios que não estão relacionados à sua operação real.

Os principais tipos de testes não funcionais são testes de segurança e testes de desempenho.

Alguns projetos também exigem testes de usabilidade e testes de localização. Respectivamente, esses testes verificam se o software é fácil de interagir e se o texto foi traduzido corretamente.

- Introdução ao design de teste
Durante a fase de design de teste, os analistas de QA criam casos de teste usados posteriormente para realizar os testes. No entanto, a criação de casos de teste exige muita preparação – não podemos simplesmente sair criando casos.

- Design de casos de teste
O design de teste envolve a criação dos casos de teste. Ao realizar a análise de requisitos, você perguntava: "O que estou testando?" Quando criamos casos de teste, perguntamos: "Como vou fazer o teste?" É como descrever as etapas que você precisa dar para preparar um novo prato gostoso.

Por que precisamos de casos de teste? Queremos ter certeza de que o software será testado por completo. Sem casos de teste, o teste seria aleatório, e arriscaríamos perder etapas e cenários críticos. Usar casos de teste garante que todos os aspectos do software sejam examinados e que o teste seja realizado de forma sistemática.

Uma vez que os casos de teste sejam criados, um analista de QA vai trabalhar neles e fará seu melhor para seguir cada caso de teste conforme escrito. As equipes de controle de qualidade dividem o trabalho entre seus membros, então o testador pode não ser a mesma pessoa que escreveu os casos de teste e também pode não estar familiarizado com os requisitos para as funcionalidades testadas. É por isso que é tão importante criar os casos de teste o mais detalhadamente possível.

Regras do design de teste
Existem cinco regras importantes no design de testes.

Você talvez precise de vários casos de teste para verificar um requisito. Por exemplo, um requisito diz: "O mapa do Urban Routes é escalável." Você pode testar essa funcionalidade de diferentes maneiras:
Usando os botões "+" e "-" na interface
Usando o botão de rolagem do mouse ou um touchpad
Usando gestos com dispositivos móveis
Um caso de teste é igual a um teste. Para testar a escalabilidade do mapa do Urban Routes, vale a pena criar dois casos de teste: um para o botão "+" e outro para o botão "-". Se você combinar ambos os testes em um caso e um dos botões tiver um bug, você não vai conseguir identificar qual deles tem esse bug.
As funcionalidades testadas não devem ser duplicadas nos testes. Digamos que você testou o botão "+" no caso de teste "Escalabilidade do mapa do Urban Routes". Isso significa que você não precisa criar um caso de teste para a "Exibição do botão '+' na interface." Obviamente, o botão é exibido.
O design dos testes precisa ser feito conforme os requisitos. Se os requisitos não descreverem como um smartphone funcionaria a -120 °C, não escreva um caso de teste em que você precise afundar um smartphone em nitrogênio líquido.
Os testes devem abranger todos os requisitos. Você precisa se certificar de que seus casos de teste verificam todas as funcionalidades.

- Testes positivos e negativos
O design de teste envolve a criação de casos de teste positivos e negativos.

- Casos de teste positivos
Um caso de teste positivo verifica se um aplicativo funciona corretamente, de acordo com um determinado requisito e usando dados válidos.
- Casos de teste negativos
Os casos de teste negativos verificam se o aplicativo responde corretamente quando os dados são utilizados incorretamente ou são inválidos. O aplicativo deve implementar a manipulação de erros adequada para lidar com um comportamento inesperado do usuário.

Particionamento em classes de equivalência
Uma das técnicas fundamentais do design de teste é o particionamento em classes de equivalência. Essa técnica permite agrupar (ou particionar) os dados de teste, reduzindo o número de testes que precisamos executar sem reduzir a eficácia dos testes. Vamos ver isso em mais detalhe.

O que é equivalência?
Equivalência é a igualdade dos objetos. Durante a testagem, os valores equivalentes são aqueles que são processados da mesma maneira por um aplicativo.

Por exemplo, os requisitos para os campos de endereço no Urban Routes indicam: "O comprimento aceitável é de 1 até 50 caracteres."

Isso significa que o aplicativo processa os valores do comprimento de 1 a 50 caracteres da mesma maneira. Os valores com comprimentos maiores do que 50 caracteres são processados de forma diferente, por exemplo, exibindo uma mensagem de erro.

Os testadores combinam esses valores em classes de equivalência.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (35).png">
Há três classes de equivalência para cada um dos campos de endereço, "De" e "Para":

Valores	                 /                       Reação aplicativo
campo vazio (0 caractere)	                       Erro
entre 1 e 50	                                  Sem erro
entre 51 e ∞	                                      Erro
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (37).png">
Então, como isso fica quando executamos testes? Em vez de executar vários testes para cada grupo, você pode escolher um valor de cada grupo para testar. O aplicativo vai reagir para qualquer um deles da mesma maneira. Você pode escolher os seguintes valores:

0 caractere (deixar o campo vazio deve ser inválido)
20 caracteres (20 é mais do que 1 e menos do que 50, então deve ser válido)
52 caracteres (52 é mais do que 50, então deve ser inválido)
Essa técnica não apenas economiza o tempo gasto para criar e executar casos de teste, mas também abrange todos os cenários possíveis, o que permite realizar um teste exaustivo.

- Como identificar classes de equivalência
Uma classe de equivalência é um intervalo de números ou um conjunto de valores que faz com que um aplicativo reaja da mesma maneira.

Use o seguinte algoritmo para identificar classes de equivalência:

Divida o requisito em blocos atômicos.
Para cada bloco, identifique o tipo das classes: um intervalo de números ou um conjunto de valores.
Identifique os valores corretos. Você pode encontrá-los nos requisitos.
Identifique valores incorretos. Eles incluem tudo que não foi identificado na terceira etapa.
Descubra o que acontece se você inserir valores incorretos.

- Como escolher valores de teste:
Nesta lição, você vai aprender como escolher um valor de teste dentro de cada classe. Esses são os valores que você vai usar em testes.

Uma hipótese comum durante o teste é que, se um aplicativo tiver processado corretamente um valor de uma classe, ele vai fazer o mesmo com o restante dos valores. Da mesma forma, se algum dos valores de uma classe causar um erro, o mesmo vai acontecer com todos os valores dessa classe.

Portanto, para escolher um valor de teste, basta pegar qualquer valor dentro da classe.

No entanto, os valores-limite não devem ser usados. Esses são valores nos limites de um intervalo. Por exemplo, 1 e 50 são os valores-limite da classe "O comprimento do texto é de 1 a 50 caracteres.” Eles serão usados para uma finalidade diferente, portanto, não vão aparecer nesse grupo de teste. Vamos falar sobre os valores-limite na próxima lição.
- Valores-limite:
Agora, você vai aprender como identificar valores-limite de classes.

Um valor-limite é um valor igual ao mínimo ou máximo permitido.

⚠️ Apenas um intervalo pode ter valores-limite. Conjuntos não têm.

Por exemplo, os requisitos para o campo de telefone no formulário para chamar um táxi no Urban Routes dizem que você pode inserir de 10 a 12 caracteres.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (38).png">
Isso significa que 10 e 12 são limites da classe "número de telefone válido".
Cerifique-se de sempre verificar os valores-limite, porque bugs costumam aparecer nos limites. Veja estes exemplos:

Indicador de bateria. Celulares geralmente mostram a porcentagem da carga restante da bateria. Se o seu celular mostrasse 0%, mas ainda estivesse ligado e funcionando, seria estranho, certo? Sendo assim, saber o limite pode ajudar a revelar bugs durante o teste.
Cálculo de idade. Pode parecer muito simples descobrir a idade de uma pessoa sabendo sua data de nascimento. No entanto, algumas datas se destacam. Por exemplo, anos bissextos. E se a data de nascimento de uma pessoa for 29 de fevereiro, que ocorre uma vez a cada quatro anos? Se você apenas contar o número de aniversários que a pessoa teve, vai obter a idade errada: por exemplo, 6 em vez de 24. Esse é o tipo de erro que os programas de computador cometem, e você deve tomar cuidado com eles.
Tipos de limites
Às vezes, os limites vão ser fáceis de identificar, como no exemplo anterior, sobre o comprimento do número de telefone. Em outros casos, eles podem ser difíceis de identificar. Vamos ver quais tipos de dados podem ser encontrados nos requisitos:

🔢 Números inteiros, ou integers, são bastante usados em cenários da vida real ao contar itens que não podem ser divididos em partes menores. Por exemplo, se você tem 30 livros em uma estante e 45 em outra, está lidando com números inteiros. Da mesma forma, um professor pode escrever que 25 alunos estão presentes na aula. Esses cenários implicam na contagem de quantidades de itens inteiros, e números inteiros costumam ser usados com esse propósito.

💲 Decimais, ou fracionários, representam quantidades não inteiras. Por exemplo, você frequentemente encontra preços como $ 1,99 ou instruções culinárias como "adicionar 1,5 colher de chá de açúcar". Os decimais garantem precisão em questões financeiras e medidas.

🕒 Intervalos de tempo são outro tipo de dados comum usado para medidas ou estimativa de tempo. Pense em um aplicativo que rastreia o número de horas trabalhadas por dia. O aplicativo calcula o pagamento de horas extras com base no número de horas trabalhadas após as 8 horas do dia de trabalho padrão. Se testarmos esse aplicativo usando valores-limite em intervalos de tempo, podemos encontrar algumas discrepâncias. Por exemplo, se o turno começar no dia 31 de março (final do mês) e terminar no dia 1º de abril, às 00h, poderá ser contabilizado no salário de abril, o que não é justo!

💡 Observe que, às vezes, os requisitos possuem descrições vagas dos intervalos. Por exemplo, "números positivos" ou "maioridade". O trabalho de um analista de QA é encontrar o significado dessas discrepâncias.

Valores-limite no design de teste
Vamos pensar em um exemplo da vida real: imagine que você esteja testando um aplicativo de banco em que você pode descobrir suas oportunidades de empréstimo.

Cada banco tem os próprios requisitos para fornecer empréstimos aos clientes. Por exemplo: "Apenas adultos podem pegar um empréstimo".

Primeiro, precisamos descobrir com que tipo de dados estamos lidando e como os limites são definidos. Nesse exemplo, estamos lidando com idade em números inteiros. Contudo, ainda precisamos esclarecer quais são os limites que definem um "adulto". Digamos que você conversou com um gerente e descobriu que, para o seu banco, um adulto é uma pessoa com idade entre 18 e 65 anos.

Para verificar o funcionamento de um aplicativo com esses valores-limite, é preciso seguir estas etapas:

Identificar o intervalo dos valores, ou seja, dos 18 aos 65 anos. Nesse intervalo, uma pessoa pode pegar um empréstimo.
Verificar se o aplicativo funciona com valores-limite, ou seja, 18 e 65 anos, conforme solicitado.
Verificar se o aplicativo funciona com base em uma lógica diferente quando estiver fora dos limites do intervalo, ou seja, com valores de 17 e 66.
Verificar se o aplicativo funciona conforme solicitado dentro dos limites do intervalo, ou seja, com valores de 19 e 64.
Assim, para testar o campo idade nesse aplicativo bancário, você vai precisar incluir seis verificações: 18 e 65; 17 e 66; 19 e 64.

Você pode usar o mesmo algoritmo para outros intervalos.

Digamos que você precisa verificar um campo no qual o usuário insere o número de minutos. Um usuário pode inserir de 15 a 45 minutos. O tipo de dados é um intervalo de tempo. A etapa é de 1 minuto.

Aqui está a ordem em que você precisa testar os valores-limite:

Identifique o tipo de dados e a etapa: um intervalo de tempo e 1 minuto.
Verifique se o aplicativo funciona bem com valores-limite do intervalo: 15 e 45.
Passe para uma etapa fora do intervalo e verifique os seguintes valores: 14 e 46.
Passe para uma etapa dentro do intervalo e verifique os seguintes valores: 16 e 44.
A seguinte lista pode ajudar a recordar como definir seus dados de teste nos limites:

LI: limite inferior
LS: limite superior
LI - 1: limite inferior - uma etapa
LS + 1: limite superior + uma etapa
LI + 1: limite inferior + uma etapa
LS - 1: limite superior - uma etapa

- Como usar classes de equivalência e valores-limite juntos
imite. Nesta lição, você vai aprender a usar ambas as técnicas juntas.

Digamos que você possa recarregar o saldo do seu celular com um valor de $ 1 a $ 49,99. Você não pode escolher uma quantia menor ou maior.

Tipo de dados: um decimal com duas casas decimais, em que a parte inteira é para reais, e a parte decimal é para centavos. A etapa é 0,01.

Classes de equivalência:

0.00 — 00.99
1.00 — 49.99
50.00 ou mais
Como você testa a recarga usando as técnicas de classes de equivalência e valores-limite da melhor maneira possível? Primeiro, você precisa testar os valores dentro da classe e então seguir o algoritmo de teste com base em valores-limite:

Teste os valores dentro das classes: 00,50, 2,50 e 55,00. Se os testes forem bem-sucedidos, vá para a próxima etapa. Se não, não existe razão para continuar testando o aplicativo. Ele não funciona.
Para cada classe, teste os valores-limite e os valores uma etapa dentro e uma fora dos limites. Você não pode definir um valor de fora dos limites na primeira classe — não é possível recarregar seu saldo com uma soma negativa. Se os testes forem bem-sucedidos, você confirmou que os limites estão corretos.
💡 Os valores-limite da classe "50 ou mais" também podem ser escritos como "50,00 —+∞". Mas como testar o infinito? Na verdade, isso é possível: é uma prática recomendada testar como um aplicativo reage a um número muito grande. Escolha um valor pelo menos 1.000 vezes maior que o maior valor-limite, e isso vai ser suficiente para verificar se valores grandes são aceitos. Nesse caso, você pode testar valores de 50.000 ou 5.000.000.

- Otimização de teste
💡 O princípio mais importante da otimização é reduzir o número de duplicatas antes da testagem.


- Projeto-3
Introdução ao Teste de Aplicativos Web
Os princípios de funcionamento de um aplicativo web: você vai aprender como um aplicativo web é organizado e como usar ferramentas de desenvolvimento.
Testes de interface em aplicativos web: nesta seção, você vai aprender a testar os elementos de uma interface, compará-los com designs e usar o editor Figma.
Testes entre plataformas e navegadores: esse tópico vai ensinar sobre como testar aplicativos web em vários dispositivos e navegadores.
Testes de adaptabilidade do layout: nesse tópico, você vai estudar várias abordagens de design de layouts, bem como os recursos usados para testar o layout da versão móvel de um aplicativo web.
Design de testes: ao concluir esse tópico, você vai saber como criar testes para aplicativos web.
  - 
Aplicativo web
Você provavelmente visualiza toneladas de páginas da web todos os dias: para procurar algo no Google ou abrir o bootcamp de Analista de QA, por exemplo. Você visualiza essas páginas no seu dispositivo usando um navegador, como Safari, Chrome ou Firefox.

Um navegador é um software que envia solicitações para um servidor, recebe respostas, processa informação e exibe os resultados na página de um aplicativo (ou aplicação) web.

No entanto, há muito mais em um aplicativo web do que apenas a interface que você vê.

Quero saber mais
Front-end e back-end
Um aplicativo web consiste em duas partes:

Um conjunto de páginas que o usuário vê em um navegador. Por exemplo, a página de busca do Google ou a página de destino do bootcamp de Analista de QA.
Um conjunto de operações lógicas e cálculos que processam as solicitações de um usuário. Por exemplo, quando você clica no botão "Escolher bootcamp", o navegador envia sua solicitação para um servidor, obtém uma resposta e exibe uma lista de todos os bootcamps na página.
A parte visual de uma página é desenvolvida por um desenvolvedor front-end.

O código das operações e dos cálculos que processam essas solicitações e geram respostas são escritos por desenvolvedores back-end.

O front-end e o back-end são duas partes de um aplicativo web.
O front-end é a parte visível de um aplicativo. Um usuário interage com ele, por exemplo, clicando em botões ou digitando algum texto.

O back-end é a parte oculta de um aplicativo. Ele lida com cálculos, lógica e armazenamento de dados.
A maioria dos aplicativos web são projetados usando a arquitetura cliente-servidor.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (39).png">
Os elementos da arquitetura cliente-servidor funcionam conforme os seguintes princípios:

O cliente se conecta a um servidor e transforma as ações do usuário em solicitações, que são enviadas ao servidor. Por exemplo, quando você clica em um vídeo do YouTube, está interagindo com o cliente.
O servidor processa as solicitações de um cliente e gera uma resposta. Por exemplo, após ter clicado em um vídeo, o servidor envia informações sobre o vídeo: curtidas, comentários e visualizações. Um servidor costuma ser um computador potente que fica separado de um cliente. Por exemplo, os servidores do Google ficam em centro de dados especiais.
A internet, ou uma rede, conecta o cliente e o servidor. Sem ela, eles não conseguiriam entrar em contato um com o outro.
O front-end é o código processado no lado do cliente, enquanto o back-end funciona em um servidor que costuma ser remoto.
Como o front-end e o back-end interagem entre si
Imagine que você está comprando livros de uma loja online. Veja como o front-end e o back-end vão interagir:

Você faz um pedido, ou seja, preenche todos os campos necessários e clica no botão "Comprar".
O front-end transforma sua ação em uma solicitação, e o navegador envia essa solicitação para o servidor, ou seja, o back-end.
O back-end realiza operações e cálculos lógicos, ou seja, processa a solicitação e retorna uma resposta. Por exemplo, ele verifica se o produto está em estoque e calcula o custo do pedido.
O navegador recebe a resposta, o front-end a processa e exibe a mensagem "O pedido foi realizado. Obrigado pela sua compra!" na página.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (40).png">

- URL
Quando quer abrir um aplicativo web, você provavelmente insere a URL na barra de endereço do navegador. Por exemplo, https://www.google.com/ or https://tripleten.com/.

Uma URL (Uniform Resource Locator, ou Localizador Uniforme de Recursos) é o endereço de um recurso da web. Ela mostra onde um aplicativo web (ou uma página da web) ou seu fragmento está localizado, e como acessá-lo.

Durante os testes, a URL pode ser usada para entender como o front-end e o back-end interagem. Seu navegador envia diversas solicitações para recursos diferentes o tempo todo. Com a ajuda da URL, você pode encontrar apenas as solicitações responsáveis pelo funcionamento do seu aplicativo.
Quero saber mais sobre URLs
A estrutura de uma URL
Veja a estrutura completa de uma URL:
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (41).png">
Em resumo, as URLs que você costuma usar consistem apenas em esquema e nome do host: por exemplo, https://google.com. Os caminhos e os parâmetros de solicitação também são muito usados, pois a maioria dos aplicativos web consistem em múltiplas páginas (por isso precisamos de caminhos), e os usuários querem enviar informações específicas ao aplicativo (através dos parâmetros de solicitação).Entendi
Sistema de Nomes de Domínio
O nome de host também é chamado de nome de domínio. Trata-se do endereço de um aplicativo web usado para registrar o aplicativo na internet. Um nome de domínio consiste em caracteres atribuídos a um aplicativo pelo Sistema de Nomes de Domínio (DNS, na sigla em inglês). Por exemplo, google.com e tripleten.com são os nomes de domínio dos aplicativos web do Google e da TripleTen.

Quando você digita uma URL na barra de endereço, o navegador inicia uma solicitação para um servidor DNS (Domain Name System em inglês). O servidor DNS traduz o nome do domínio em um endereço IP, que é o identificador exclusivo do servidor com as informações solicitadas.

Um endereço IP é um identificador exclusivo de um servidor que armazena as informações necessárias.

Uma pessoa não consegue memorizar todos os endereços IP que existem, e é por isso que o DNS foi criado. Ele transforma um nome de domínio em um endereço IP. Isso é parecido com as antigas listas telefônicas, nas quais cada nome de uma pessoa correspondia a um número de telefone.

- Solicitações HTTP
Como você já sabe, o cliente e o servidor se comunicam usando uma rede. Para ter uma comunicação fácil, o cliente e o servidor precisam usar a mesma linguagem, ou seja, um protocolo de transmissão de dados.

Um protocolo de transmissão de dados é um conjunto de regras para transferir dados na internet.

HTTP e HTTPS
Um desses protocolos é o HTTP (HyperText Transfer Protocol, ou Protocolo de Transferência de Hipertexto). Hoje, você pode usar HTTP para transferir todo tipo de dados, como texto, imagens, áudio e vídeo.

Entretanto, há um problema: o HTTP transfere dados de forma insegura. As pessoas podem interceptar e roubar dados privados em sites que transferem informações por HTTP. Por exemplo, é melhor não transferir dados bancários usando esse método.

Para garantir a segurança, os sites usam um HTTP com mais proteção chamado de HTTPS (HyperText Transfer Protocol Secure, ou Protocolo de Transferência de Hipertexto Seguro). Ele criptografa uma conexão usando protocolos criptográficos. Assim, um cliente e um servidor podem trocar mensagens de forma segura.

- Solicitações HTTP
Solicitações HTTP são a maneira do front-end solicitar ao back-end que execute determinadas operações nos dados, como mostrar uma página da web. O back-end então retorna uma resposta.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (42).png">
Uma solicitação é estruturada conforme as regras de transmissão de dados HTTP. Ela consiste em quatro partes:

Uma linha inicial
Cabeçalhos
Uma linha divisória vazia
Corpo de mensagem
No exemplo abaixo, o usuário inseriu "TripleTen" na barra de pesquisa do Bing, e o front-end solicitou os dados necessários do back-end em uma solicitação HTTP:
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (43).png">
Confira isso em mais detalhes abaixo.

Linha inicial
A linha inicial consiste em três elementos: um método, um caminho e uma versão do protocolo.

Por exemplo: POST / search / HTTP/1.1 ou GET / HTTP/1.1.

O método indica uma ação: o back-end processa essa ação. Os métodos mais comuns são GET, POST, PUT e DELETE.
Se você não especificar o método, o back-end não vai entender o que fazer com os dados, então esse é um elemento obrigatório.

O caminho para um recurso é um endereço usado pelo front-end para enviar uma solicitação para o back-end. Por exemplo, /profile/settings.
A versão do protocolo é o número de uma versão do HTTP. Atualmente, é HTTP/1.1.
Cabeçalhos de solicitação
Cabeçalhos de solicitação representam informações adicionais que o front-end envia para o back-end.
Se você não especificar o método, o back-end não vai entender o que fazer com os dados, então esse é um elemento obrigatório.

O caminho para um recurso é um endereço usado pelo front-end para enviar uma solicitação para o back-end. Por exemplo, /profile/settings.
A versão do protocolo é o número de uma versão do HTTP. Atualmente, é HTTP/1.1.
Cabeçalhos de solicitação
Cabeçalhos de solicitação representam informações adicionais que o front-end envia para o back-end.

Existem:

Cabeçalhos genéricos
Cabeçalhos de solicitação
Cabeçalhos de entidade

Mais um exemplo
Uma solicitação HTTP completa pode ser assim:

POST /subscribe/ HTTP/1.1
Host: сinemart.com
User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/91.0.4472.106 Safari/537.36
Accept-Language: en
Connection: keep-alive
Content-type: application/json

{
"surname": "Williams",
"name": "Sam",
"age": 28,
"email": "samw@tripleten.com"
}
Aqui está o que cada parte significa:

POST /subscribe/ HTTP/1.1: POST — escrever dados com o método POST; /subscribe — a solicitação aborda um recurso que lida com inscrições; HTTP/1.1 é a versão 1.1 do protocolo HTTP.
Host: сinemart.com: cinemart.com — é o host para o qual o front-end envia uma solicitação.
User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/91.0.4472.106 Safari/537.36: essa parte contém informações sobre os navegadores, o sistema operacional e as versões de software do cliente.
Accept-Language: en: en — são os idiomas aceitos na resposta. Nesse caso, inglês.
Connection: keep-alive: keep-alive — significa que a conexão com o servidor é permanente.
Content-type: application/json: os dados estão no formato JSON.
{"surname": "Williams", "name": "Sam", "age": 28, "email": "samw@tripleten.com"} — é o corpo da mensagem.
O que mais?
Uma solicitação GET não tem um corpo, enquanto uma solicitação POST geralmente tem um.

- Respostas HTTP
Na lição anterior, você aprendeu que uma solicitação HTTP consiste em três partes: uma linha de status, cabeçalhos e o corpo da mensagem. Uma resposta HTTP tem uma estrutura semelhante:

<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (44).png">
Linha de status
A linha de status inclui uma versão do protocolo, um código de status e um texto de status.

Por exemplo: HTTP/1.1 200 OK.

A versão do protocolo é o número de uma versão HTTP para a qual uma resposta é gerada. Exemplo: HTTP/1.1.
O código de status é um número de três dígitos que indica se o servidor processou a solicitação com sucesso. Exemplo: 200.
O texto de status é o texto que acompanha o código de status. Exemplo: "OK."
Os desenvolvedores usam uma lista padronizada de códigos de status e descrições.

Os códigos de status são divididos em cinco grupos:

Códigos    /	Descrição	/    Exemplo
1xx       	Informativo	       102 —a solicitação foi recebida mas o processo ainda está em progresso.
2xx	            /Sucesso /    200 — OK, a solicitação foi processada com sucesso.
3xx	/      Redirecionamento	/ 302 — o recurso solicitado está temporariamente disponível em outro endereço.
4xx/     	Erro de cliente /  	404 — não foi possível encontrar a página solicitada pelo usuário no servidor.
5xx	  / Erros no servidor /  	500 — erro interno de servidor.
-  Imagine que você quer abrir a página SUPERTESTER no site da TripleTen: https://tripleten.com/supertester.

Se você clicar no link, verá um erro. O back-end enviou uma resposta para o front-end: 404 Not found. É assim que ele indicou que não foi possível encontrar a página.

Os erros mais comuns, representados por códigos de status e uma descrição, são:

403 Forbidden — um cliente não tem permissão para acessar o recurso.
404 Not Found — não foi possível encontrar a página com o seguinte URL.
500 Internal Server Error — erro interno de servidor.
503 Service Unavailable — o serviço está temporariamente indisponível. O servidor não pode processar solicitações.
504 Gateway Timeout — o tempo de resposta do servidor expirou.
E quanto aos cabeçalhos?
Cabeçalhos de resposta
Os cabeçalhos de resposta contêm informações adicionais sobre o back-end e os tipos de dados para o front-end.

A estrutura dos cabeçalhos é semelhante a de uma solicitação HTTP.

Cabeçalhos genéricos (para uma solicitação HTTP)
Cabeçalhos de resposta
Cabeçalhos de entidade (para uma solicitação HTTP)
Os cabeçalhos genéricos contêm parâmetros que são transmitidos tanto em uma solicitação quanto em uma resposta. Exemplo: “Connection” é o status da conexão entre um cliente e um servidor, e “Date” é a data em que a resposta do servidor foi criada.

Cabeçalhos de resposta permitem que um servidor transmita informações adicionais que não cabem em uma linha de status. Exemplo: "Server" é o software que um servidor usa para lidar com a solicitação e gerar a resposta, e "Location" indica a localização exata de um recurso.

Cabeçalhos de entidade definem as características do conteúdo dentro do corpo da mensagem. Exemplo: "Content-Type" é o tipo de dados da resposta.
Corpo da mensagem
O corpo da mensagem é usado pelo back-end para informar sobre o resultado obtido do processamento de uma solicitação.

Por exemplo, o front-end solicitou a página principal do Google, google.com, ao back-end.
O back-end processou a solicitação com sucesso: ele enviou a página necessária dentro do corpo da mensagem para o front-end.


O navegador processou a resposta do back-end e exibiu uma página com a barra de pesquisa:

<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (45).png">

- Como visualizar solicitações do front-end e respostas do back-end
Às vezes, quando o front-end e back-end trocam dados, alguma coisa pode sair errada. Por exemplo, o front-end enviou uma solicitação para adicionar produtos a um carrinho de compras, mas nenhum produto foi adicionado. O back-end não conseguiu lidar com a solicitação e respondeu com um erro.

Para resolver isso, você precisa ser capaz de visualizar solicitações e respostas.

Geralmente, você visualiza as solicitações e respostas no DevTools (Ferramentas para Desenvolvedores de Web).

Para ver como o DevTools funciona, você vai testar o recurso de pedido de táxi no Urban Routes. Tente executar alguns testes por conta própria, depois encontre as solicitações do front-end e respostas do back-end no DevTools. Você pode estudar a funcionalidade de chamar um táxi nos requisitos.
Alterando meu README.

- Cookies
Os aplicativos web armazenam dados de maneira diferente. Nesta lição, você vai aprender sobre uma destas tecnologias: o cookie.

Um cookie refere-se aos dados armazenados no dispositivo do usuário. O servidor gera dados, que ficam armazenados no computador ou smartphone do usuário. Quando o usuário abre o aplicativo novamente, o servidor recebe os dados de volta.

Imagine que você vai sair de férias e decidiu escolher um hotel em um aplicativo da web, uma plataforma de pesquisa de hotéis:

Você abre a página principal da plataforma.
O navegador procura cookies em seu dispositivo e então envia uma solicitação ao servidor.
Se essa não for a primeira vez que você está usando a plataforma de pesquisa, o navegador vai enviar os cookies salvos ao servidor. Por exemplo, os cookies podem ter informações de que o usuário tem uma conta na plataforma.
O servidor vai processar a solicitação e gerar uma resposta com base nesses dados. Por exemplo, vai adicionar uma lista de suas reservas à resposta. Sem cookies, o servidor não vai enviar os dados, pois identifica você como um novo usuário.

<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (45).png">
Os cookies podem armazenar diferentes dados:

Dados para autenticação. Por exemplo, você faz login em um aplicativo web, fecha a aba e, depois de um tempo, abre o aplicativo novamente. Você não vai precisar inserir seu login e senha de novo, pois os dados do status de autorização estão armazenados nos cookies.
Dados do usuário. Por exemplo, as informações sobre os hotéis, geolocalização, idioma e moeda que o usuário visualizou.
Dados para colecionar estatísticas. Por exemplo, as estatísticas sobre o dispositivo do usuário ou páginas visualizadas. Com base nas estatísticas, a equipe do aplicativo tira conclusões e toma decisões sobre como uma funcionalidade está operando.
Como eu posso visualizar os cookies?
Os cookies são pequenos arquivos de texto que você pode ver diretamente no navegador.

Armazenamento local
Armazenamento local são dados armazenados no navegador. Isso é diferente dos cookies, pois os dados do armazenamento local não são transferidos para o servidor, apenas o lado do cliente do aplicativo os utiliza.

Por exemplo, você preenche um formulário de reserva de hotel e insere seu nome completo, e-mail e número de telefone. Se o aplicativo front-end armazenar dados no armazenamento local, eles não serão perdidos mesmo depois de uma página ser atualizada. Se você decidir reservar outro hotel e retornar ao formulário de reserva, seu nome, sobrenome, e-mail e número de telefone serão retirados do armazenamento local. Você não vai precisar digitar tudo de novo.
Como eu posso ver esses dados?
Como visualizar dados do armazenamento local
Os dados do armazenamento local podem ser visualizados no DevTools.

- Cache em testes
Cache (ou armazenamento cache) são os dados de uma página. Quando você abre imagens, áudio, vídeo ou páginas, tudo isso é armazenado em seu dispositivo.

Os cookies e o armazenamento local facilitam o uso do aplicativo. O usuário não precisa inserir os mesmos dados várias vezes, por exemplo, login, senha e número de telefone.

Um cache de navegador tem outra finalidade. Quando você abre uma página de novo, ela vai carregar mais rápido porque o navegador pega os arquivos do armazenamento em cache, não do servidor.

<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (47).png">
Por que um testador precisa saber isso?
Às vezes, a causa dos bugs está escondida no cache. Imagine que você encontra um bug e cria um cartão no rastreador de bugs. O desenvolvedor corrige o bug e retorna o problema para testes. Agora, você precisa ter certeza de que tudo está funcionando. Você testa o aplicativo de novo, mas nada muda. O bug ainda ocorre, mas o desenvolvedor afirma ter corrigido o problema.

É possível que os dados tenham sido simplesmente armazenados em cache em seu navegador. É por isso que você vê a versão antiga da página no seu computador e não a nova versão do servidor. Para corrigir o problema, você precisa limpar o cache. Siga estas etapas para praticar:

Abra o Google Chrome.
No canto superior direito, abra o menu do navegador e selecione "Histórico".
Clique em "Limpar dados de navegação".
Marque apenas uma caixa: "Imagens e arquivos em cache".
Defina o intervalo de tempo, "Todo o período".
Clique em "Limpar dados".
Você pode encontrar guias para outros navegadores na internet.

Após atualizar o aplicativo, uma parte dos arquivos pode ser baixada do servidor e outra do armazenamento em cache. Isso pode causar alguns problemas, como com o layout do aplicativo.

Se você notar esse bug em produção, não se apresse em limpar o cache. Os usuários podem encontrar o mesmo problema. Informe aos desenvolvedores e eles vão ajudar a entender o problema.
Teste de interface do usuário de um aplicativo web: introdução
Olá, este é o capítulo "Teste de interface do usuário de um aplicativo web"! Aqui, você vai aprender sobre diferentes elementos da interface, bem como sobre testar o layout de um aplicativo.

Os usuários interagem com um aplicativo web por meio de uma interface de usuário, ou IU. Em inglês, a sigla é UI. Ela é composta de diferentes elementos da interface. O elemento básico de uma interface é o menu principal, que deixa você se mover entre as páginas web.

Confira os diferentes elementos na página de "Analista de QA" da TripleTen:
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (48).png">
Todo elemento de interface é testado de duas maneiras: visual e funcionalmente.

Teste visual
Testes visuais também são chamados de testes de layout.

Um layout tem tudo a ver com a combinação e colocação dos elementos da interface de maneira que correspondam com o design.

Um testador então verifica, em um navegador, se a página web tem o aspecto desejado. Se você encontrar inconsistências, como a cor ou o tamanho de um botão que não corresponde ao design, será necessário criar um relatório de bug.

Teste funcional
Um testador precisa garantir que os elementos da interface funcionam corretamente. Por exemplo, isso inclui verificar que é possível clicar nos botões e que os links levam para as páginas corretas.

Se vários elementos formam uma única funcionalidade, eles são unidos em grupos, ou formulários. Por exemplo, os campos "De" e "Para" são necessários para criar uma rota e compõem um formulário.

- Uma ferramenta para trabalhar com designs: Figma
Nas lições anteriores, você aprendeu quais são os elementos da interface mais comuns. Nesta lição, você vai aprender sobre o Figma, uma ferramenta usada para testar o layout da interface.

Design
Quando uma interface é criada ou alterada, um testador compara o layout resultante com os requisitos e designs.

Um design é uma representação visual de como a interface da página deve ser. O design da interface inclui a organização de elementos visuais, como botões, imagens e texto, bem como a criação de uma experiência esteticamente agradável e funcional para os usuários.

Os designers criam um projeto individual para cada página de um aplicativo web. 
Sprint 3: Teste de Aplicativos Web


Capítulo 3/8
Teste de interface do usuário de um aplicativo web
Uma ferramenta para trabalhar com designs: Figma
Nas lições anteriores, você aprendeu quais são os elementos da interface mais comuns. Nesta lição, você vai aprender sobre o Figma, uma ferramenta usada para testar o layout da interface.

Design
Quando uma interface é criada ou alterada, um testador compara o layout resultante com os requisitos e designs.

Um design é uma representação visual de como a interface da página deve ser. O design da interface inclui a organização de elementos visuais, como botões, imagens e texto, bem como a criação de uma experiência esteticamente agradável e funcional para os usuários.

Os designers criam um projeto individual para cada página de um aplicativo web. Por exemplo, os designs do Urban Routes são assim:



Janaina
Como isso é relevante para realizar testes?
Tanto desenvolvedores quanto testadores usam esses designs.

Um desenvolvedor front-end utiliza designs para escrever códigos. Nesse caso, primeiro o designer deve criar uma interface simples e conveniente. Essa propriedade é chamada de usabilidade (ou facilidade de uso).
Um testador compara uma interface pronta com os designs, procurando inconsistências na localização dos elementos ou esquema de cores.
Às vezes, os designs não correspondem aos requisitos. Pode ser que os requisitos tenham sido atualizados e os designs não. Nesse caso, você precisa começar com os requisitos.

Normalmente, um design vem com uma tarefa, ou requisitos, na forma de um link ou mensagem. Por exemplo, o designer do Urban Routes pode criar o design da interface em um editor gráfico especial e depois anexar um link à tarefa no rastreador.
O que é esse editor gráfico?
Figma
Um dos instrumentos mais comuns para trabalhar com designs é o Figma. Ele é um editor gráfico disponível em um navegador ou em um aplicativo para o computador ou celular. No Figma, você pode trabalhar simultaneamente com colegas em um projeto online e deixar comentários, assim como no Google Docs.

É uma boa ideia entender o básico de como o Figma funciona. Neste sprint, você vai usar esse editor para revisar os designs e testar a interface do Urban Routes.

Primeiro, tente descobrir como trabalhar no Figma para abrir arquivos e se mover entre os designs. Para fazer isso, conclua uma pequena tarefa:

Link para as instruções e a tarefa no Figma se você estiver usando Windows.
Link para as instruções e a tarefa no Figma se você estiver usando MacOS.
Formulários e teste de validação
A ideia de um formulário de aplicativo web surgiu a partir das versões físicas deles na vida real. Por exemplo, se você quiser conectar sua casa à internet, precisa preencher um contrato ou formulário em papel. De forma semelhante, um desenvolvedor cria formulários em aplicativos web conforme os requisitos, e um usuário precisa preenchê-los.

Um formulário é um componente de uma página para obter informações do usuário. Um formulário de registro, uma área de pedidos em uma loja online e uma janela para escrever uma postagem no Facebook são exemplos de formulários.
Os formulários possuem três características especiais:

Para um usuário ser capaz de inserir e mandar dados, um formulário precisa ter elementos de interface: botões, botões de rádio, caixas de seleção, campos com listas de opção e campos de entrada de texto. Por exemplo, um formulário de registro é composto de seis campos de entrada e do botão "Fazer registro".
O objetivo do formulário é fazer o usuário realizar uma ação específica em um aplicativo web. Por exemplo, se registrar.
O usuário precisa perceber quando o objetivo for alcançado. Por exemplo, depois do registro, o usuário vai ver a seguinte mensagem na tela: "Sua conta está pronta!"
Testes de formulários
Formulários são testados como um único elemento. Por exemplo, um usuário precisa inserir um nome, um sobrenome, um login, uma senha e um número de telefone no formulário de registro.

Todos os dados no formulário são preenchidos com um propósito em mente: o front-end não vai enviar a solicitação até você preencher todos os campos obrigatórios. É por isso que você precisa testar os elementos juntos.

Lembre-se de que, se o formulário conter pedaços de dados que dependem um do outro e mudam o cenário do preenchimento no formulário, você precisa testar isso. Por exemplo, se um usuário preencher um pedido de empréstimo e escrever "Desempregado" como situação profissional, não há necessidade de inserir dados sobre salário e local de trabalho.

Primeiro, você executa os testes positivos e depois os negativos.
Para começar, o testador deve inserir dados válidos que constam nos requisitos. Você precisa garantir que, nesse caso, o aplicativo realize suas funções principais.

Por exemplo, os campos "Nome de usuário" e "Senha" do formulário de cadastro devem aceitar apenas caracteres latinos, números, hifens e pontos.

O cadastro deve ser bem-sucedido se você inserir um nome de usuário válido, como anna-desenvolvedora-qa, e a senha, anna.senha123, bem como se preencher corretamente outros campos.
Quando você executar testes negativos, certifique-se de que o aplicativo não vai travar. De forma ideal, ele deve retornar uma mensagem de erro.

Se você inserir dados inválidos, como caracteres proibidos, dentro de qualquer campo do formulário, uma mensagem de erro vai aparecer. Isso significa que os dados no formulário não foram aprovados na validação.
Validação
A validação é um mecanismo que verifica se os dados inseridos pelo usuário estão corretos.

Se a validação for bem-sucedida, o aplicativo vai funcionar corretamente. Se não, o usuário vai ver uma mensagem de que os dados no campo são inválidos.
As regras de validação são escritas pelos desenvolvedores no código. Isso é feito no front-end e também no back-end.

No primeiro caso, o front-end verifica os dados imediatamente. Por exemplo, o formulário emite a mensagem "A senha contém caracteres inválidos" assim que o usuário preenche o campo "Senha".
No segundo caso, o back-end verifica todos os dados apenas após obter a solicitação. Por exemplo, o Google Forms executa a validação dos campos depois que o usuário preenche todo um formulário e clica no botão "Enviar".

- Testes em textos para detectar erros
Os textos desempenham um papel importante na interface web.
Os textos guiam o usuário pelos elementos da interface e ajudam a interagir com o aplicativo:

O texto do logotipo se refere à empresa e ao nome do aplicativo: Urban Routes.
Os textos acima dos campos do formulário dão dicas sobre os dados que você precisa inserir nos campos "De" e "Para".
A parte com a informação sobre as tarifas contém botões com os nomes e custo das tarifas e uma janela pop-up com informações detalhadas sobre elas.
Os campos de entrada contêm placeholders, ou seja, textos auxiliares que você precisa inserir no campo, por exemplo, "Enviar mensagem ao motorista".
Os botões são rotulados com textos que dizem o que acontece quando você clica neles. Por exemplo, o texto no botão "Pedir" declara que clicar nesse botão vai pedir um táxi.
Quem cria os textos?
Os textos costumam ser escritos com base no seguinte cenário:

O gerente de projetos atribui a tarefa ao editor. Por exemplo: "O texto para chamar táxi deve conter um cabeçalho e informações adicionais sobre a distância e duração da rota."
O editor prepara o texto. Por exemplo: "Pedido: A rota será de [3] quilômetros e levará [3] minutos."
Quando os textos ficam prontos, o designer encaixa tudo nos designs.
Ao escrever o código, o desenvolvedor adiciona esses textos aos elementos necessários da interface. Nesse exemplo acima, é o botão para pedir um táxi.
A cada etapa, algo errado pode acontecer com o texto:

O usuário não entende o texto.
Por exemplo, o editor escreveu "Pronto" para o botão de chamar um táxi. Não fica claro o que acontece quando o usuário clica nesse botão: se um táxi é pedido ou se outro campo de entrada aparece.

O designer confundiu os textos no design, e o desenvolvedor transferiu isso para o código.
Por exemplo, o texto no botão de chamar um táxi se tornou o seguinte: "Pedido:" A rota será de [3] minutos e levará [4] quilômetros." A variação correta é "Pedido: A rota será de [3] quilômetros e levará [3] minutos."

O desenvolvedor cometeu um erro de digitação e transferiu o texto com um erro para o código.
Por exemplo, o desenvolvedor trocou duas letras na palavra "Rota", e agora se lê "Rato".

O desenvolvedor não transferiu a variação final do texto para o código.
Por exemplo, o editor ainda tem que preparar o texto, mas o desenvolvedor já transferiu a variação temporária para código e esqueceu de mudá-la. Como resultado, a dica "O texto do botão vai estar aqui" fica na interface.

Esse é o motivo pelo qual um testador precisa prestar atenção não apenas nos elementos do layout, mas também nos textos na interface. Afinal, eles afetam a usabilidade de um aplicativo e a reputação da empresa.
Como eu testo os textos?
Quando testar, tente responder duas perguntas:

Você pode, como usuário do aplicativo, entender o que o texto diz?
Existe qualquer erro de gramática, escrita ou pontuação no texto?
Para testar os textos em busca de erros, você pode usar instrumentos especiais:

Por exemplo, o Language Tool: https://languagetool.org.
- Testes multiplataforma
Os usuários podem acessar aplicações de diferentes dispositivos e navegadores, e essa aplicação pode se comportar de maneira diferente, por exemplo, em um notebook Windows com Google Chrome e em um iPhone com Safari. Para testar todas essas combinações, você vai precisar realizar testes entre plataformas (ou multiplataforma) e entre navegadores. Nesta lição, você vai começar a aprender sobre testes multiplataforma.

Primeiro, você precisa entender qual é a diferença entre plataformas e sistemas operacionais.
Plataformas
Um usuário pode acessar aplicativos em um notebook, smartphone ou tablet. Há plataformas, ou seja, dispositivos que os usuários precisam para usar aplicativos.

Há dois tipos de plataformas:

Desktop: PCs e notebooks.
Móvel: smartphones e tablets.Os desenvolvedores adaptam um mesmo aplicativo para diversas plataformas criando versões desktop e móvel, tornando conveniente usar o serviço em telas pequenas e grandes.
As versões móveis e desktop são testadas separadamente. Pode ser que a versão para desktop corresponda aos designs e requisitos, mas a versão móvel, não — botões, dicas e outros elementos aparecem em lugares errados.
Sistemas operacionais
Um usuário se comunica com um dispositivo mediante um conjunto de programas. Alguns programas manipulam os sinais do teclado e mouse, outros deixam o usuário criar e excluir arquivos.

Um conjunto de programas para comunicação entre um usuário e um dispositivo é chamado de sistema operacional, abreviado como SO. Exemplos de sistemas operacionais são Windows, Android e macOS.

Você precisa testar os aplicativos executados em diferentes sistemas operacionais separadamente. Mesmo que a versão para iOS de um aplicativo atenda aos requisitos e designs, a versão do Android talvez ainda tenha problemas. Por exemplo, o layout, os botões e o posicionamento dos elementos talvez estejam errados.
Combinar plataformas e sistemas operacionais
Alguns sistemas operacionais são apenas para plataformas desktop, enquanto outros são apenas para versões móveis. 
Você precisa testar diferentes combinações de plataformas e sistemas operacionais. É possível que um aplicativo funcione sem bugs em um caso, mas, em outro, pode apresentar bugs.

Por exemplo, um testador confirmou que, em um notebook com Windows, o aplicativo estava funcionando conforme os requisitos e designs. Depois, o testador abriu o mesmo aplicativo em um telefone com Windows e viu que o layout não corresponde aos designs, e é bem complicado usar os botões.

Para garantir que um aplicativo atenda aos requisitos e designs em qualquer plataforma e SO, os testadores executam testes multiplataforma. Eles testam se:

A interface do usuário corresponde ao design.
A funcionalidade está conforme indicado nos requisitos.
Como selecionar sistemas operacionais para testar um aplicativo
1- Conferir os requisitos
Os requisitos para um aplicativo geralmente indicam um conjunto de sistemas operacionais para dispositivos móveis e desktop. Nesse caso, você só precisa testá-los.
2- Perguntar ao gerente de projetos
Às vezes, não há descrição dos SOs nos requisitos. Nesse caso, você pode perguntar ao gerente do projeto quais são compatíveis com o aplicativo e testá-los.
3- . Conferir as estatísticas locais
Se os requisitos não dizem nada sobre os sistemas operacionais compatíveis e seu gerente de projetos também não tiver uma resposta, confira as estatísticas locais do aplicativo.

A maioria das empresas coleta dados sobre como os usuários usam o aplicativo. Por exemplo, quantas pessoas o abrem, quais botões recebem mais cliques e quais funções são mais usadas.

Um desenvolvedor adiciona o código no aplicativo, que envia dados a instrumentos especiais, por exemplo, ao Google Analytics. Esses instrumentos coletam análises e as apresentam em forma visual.

Com base nesses dados, os analistas e gerentes de projetos entendem como devem desenvolver o aplicativo, e um testador entende quais navegadores e sistemas operacionais precisam ser verificados.
- Pergunte ao gerente de projetos ou analista onde você pode obter as estatísticas do aplicativo.
- Verifique com o gerente de projetos quais versões a equipe concordou em considerar as mais populares. Por exemplo, em alguns projetos, a equipe concordou em oferecer suporte a um SO se mais de 2% dos usuários o usarem. Em outra empresa, a equipe pode concordar em testar os dois SOs mais populares para desktop e móvel.
4- Conferir estatísticas gerais para um SO
Às vezes, não há estatísticas locais para um aplicativo, como quando um serviço está apenas iniciando. Nesse caso, você pode consultar as estatísticas gerais dos sistemas operacionais no país para o qual o aplicativo foi desenvolvido.

- Como selecionar navegadores para testes de sofware
Você precisa executar testes entre navegadores se o layout tiver sido alterado, pois é melhor testar essas alterações em todos os navegadores. No entanto, geralmente, os testadores não têm tempo para fazer uma testagem minuciosa entre todos os navegadores existentes.

Para economizar recursos, um testador pode executar testes apenas em navegadores compatíveis ou nos mais populares.
Como posso saber quais são esses navegadores?
Você pode escolher navegadores para testar da mesma forma que os sistemas operacionais:

Procure nos requisitos do aplicativo.
Pergunte ao gerente de projetos.
Verifique as estatísticas locais para ver quais navegadores os usuários preferem para acessar o aplicativo.
Verifique as estatísticas gerais para ver quais navegadores são populares na região.

- Abordagem para layouts de aplicativos web
Um aplicativo web geralmente vem em duas formas:

Aplicativo desktop
Aplicativo móvel
Sprint 3: Teste de Aplicativos Web

Capítulo 5/8
Teste de design web responsivo
Abordagem para layouts de aplicativos web
Um aplicativo web geralmente vem em duas formas:

Aplicativo desktop
Aplicativo móvel
Nesta lição, você vai aprender quais práticas de layout de aplicativo facilitam a interação com o aplicativo.
Quero saber mais
Há apenas dois tipos de aplicativos web, mas há muitos tipos de dispositivos:

PCs
Notebooks
Smartphones
Tablets
Os usuários devem se sentir confortáveis ao interagir com o aplicativo em qualquer dispositivo. Assim, o aplicativo deve ser adaptável.

Aplicativos adaptáveis são aplicativos capazes de alternar entre diferentes tamanhos de tela.

Resolução da tela é o tamanho de uma imagem em uma tela em pixels.

O aplicativo web se adapta à resolução da tela para que todos os elementos caibam na tela e a funcionalidade disponível permaneça.
Avançar
Há duas abordagens para garantir que o layout se ajuste a diferentes tamanhos de telas: design adaptável e design responsivo. Ambas as opções são frequentemente chamadas de "adaptáveis."
Mais sobre o design adaptável
Design adaptável
O aplicativo usa pontos de interrupção específicos (que significa "ponto de destruição", "momento da inflexão") para se ajustar ao tamanho da tela:

O designer define os pontos de interrupção no design.
O desenvolvedor os adiciona ao código.
Quando a largura da tela atinge estes "pontos," o layout "quebra" (transforma-se para se ajustar à nova largura).
Por exemplo, o designer definiu os seguintes pontos de interrupção: 

320 pixels - para smartphones

960 pixels - para tablets

1200 pixels - para navegadores desktop

Se a janela do navegador for reduzida para 960 pixels, o design altera para tablet, e se for de 320 pixels, para dispositivo móvel.

Quando um usuário visita um site adaptável, o servidor determina qual dispositivo o usuário tem e responde com o design necessário: para desktop, tablet ou smartphone.

Design responsivo
Design responsivo
Se o design responsivo tiver pontos de interrupção, o design responsivo se adapta à largura da tela em qualquer ponto. Este layout, chamado como um layout fluido, estende-se em todas as direções sem saltos bruscos na imagem.

As proporções e tamanhos dos elementos em um design responsivo são dados em porcentagem, e não em pixels. Como resultado, todos os componentes "estendem" suavemente com base na resolução da tela. É por isso que este design é chamado de fluido.

Ferramentas para testar a versão móvel de um site
Há duas maneiras de testar um aplicativo móvel:

Em um dispositivo móvel real: as empresas costumam ter dispositivos de teste.
Em um desktop: no botão Alternar barra de ferramentas do dispositivo, integrado ao DevTools.
Cada método é adequado para casos específicos. 
Teste em dispositivos móveis reais
Em dispositivos reais você testa:

Compatibilidade multiplataforma e entre navegadores: o aplicativo web deve funcionar e ser exibido corretamente em todos os sistemas operacionais e navegadores móveis compatíveis.
O teclado na tela: você precisa garantir que o layout não muda quando o teclado aparece.
Alguns gestos que não podem ser executados em um computador: por exemplo, como pinçar com dois dedos para diminuir o zoom.
Teste com DevTools
No DevTools, você pode verificar apenas alguns recursos do aplicativo móvel:

Como o layout de um aplicativo web se ajusta em diferentes tamanhos de tela.
Como o layout se comporta quando a orientação da tela é alterada.
Alguns gestos. Por exemplo, o gesto de deslizar o dedo.
Os testadores costumam combinar ambos os métodos:

Primeiro, realizam testes em um dispositivo real.
No DevTools, testam o layout naquelas resoluções que não podem ser verificadas em dispositivos.
Como selecionar resoluções de tela para teste de web design responsivo.
O que afeta a escolha?
Um algoritmo especial vai ajudar você a escolher quais resoluções são melhores para testar o layout. Você já viu como elas funcionam nas lições sobre teste entre navegadores e multiplataforma.

Aprenda como escolher a resolução da tela:

Observe os requisitos e designs: se as resoluções suportadas pelo aplicativo estiverem listadas, teste apenas elas.
Se as resoluções não estiverem listadas, consulte seu administrador de projeto. A equipe geralmente concorda com antecedência sobre quais resoluções usar para testes para cobrir telas grandes e pequenas.
Se não houver acordo, tente consultar as estatísticas locais. Elas falarão quais resoluções de dispositivo recebem muito tráfego entre os usuários de seus aplicativos.
Se você não tiver estatísticas de aplicativos, consulte as estatísticas gerais sobre resoluções para entender quais resoluções são as mais populares. Siga o link para ver um exemplo destas estatísticas: https://gs.statcounter.com/screen-resolution-stats

Como escolher um ambiente de teste
Os testadores testam o aplicativo em diversos ambientes, como:

Diferentes dispositivos: desktop e móvel
Diferentes sistemas operacionais
Diferentes navegadores
Diferentes resoluções.

Projeto-4
- Introdução à API 
O que você vai aprender:
O que é uma API
Qual é a função de uma API em um aplicativo
Como as APIs REST são criadas
Como trabalhar com o formato de dados JSON.
Arquitetura do aplicativo
 Há três componentes na arquitetura cliente-servidor:

O cliente (client): o aplicativo com o qual o usuário está trabalhando.
O servidor (server): o sistema que os clientes acessam para obter os dados.
A rede (network): um sistema de múltiplos dispositivos que ajuda o cliente e o servidor a trocarem dados.
Nos aplicativos web, o cliente é o front-end, a parte visível do aplicativo. O back-end é o lado do servidor do aplicativo, responsável pela lógica e pelos dados.

O cliente e o servidor trocam mensagens via protocolos HTTP e HTTPS. O cliente envia uma solicitação; o servidor retorna uma resposta.
Arquitetura de aplicativo é como os componentes de um aplicativo são organizados. Em um aplicativo web, a arquitetura pode incluir front-end, back-end, API e um banco de dados.

API (sigla em inglês para "Application Programming Interface", que significa Interface de Programação do Aplicativo) é a interface que ajuda os aplicativos a interagirem uns com os outros. Usando a API, eles trocam dados via solicitações e respostas.

Por exemplo, se o front-end do aplicativo Urban.Routes precisar obter as coordenadas de uma rota, ele se volta para a API do Google Maps.

O cliente precisa traçar a rota no mapa, mas primeiro precisa obter o mapa e as coordenadas da rota. Para fazer isso, o cliente envia uma ou mais solicitações à API do Google Maps e recebe as informações necessárias na resposta.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (49).png">
Depois disso, o cliente pode traçar o mapa e a rota na própria página.
Um banco de dados é um conjunto de dados acessado pelo usuário via um computador. Por exemplo, o banco de dados de uma loja online pode armazenar informações sobre produtos e clientes registrados.
O que é uma API:
Um aplicativo pode ter uma interface de usuário — IU (ou UI, em inglês). Isso pode ser:

Uma interface gráfica de usuário — GUI
Uma interface de linha de comando — CLI
Por meio delas, o usuário interage com aplicativos, computadores e outros dispositivos.

Em contraste, a API (sigla em inglês para "Application Programming Interface", que significa Interface de Programação de Aplicativos) é a interface através da qual os aplicativos se comunicam entre si. Quando dois aplicativos se comunicam, um envia comandos e o outro executa esses comandos.
Na arquitetura cliente-servidor, o front-end se comunica com o back-end enviando solicitações e recebendo respostas. Para criar uma solicitação ao back-end, o front-end aciona à API do back-end.

No Urban.Routes, a API do back-end é um conjunto fixo de URLs. Elas podem ser usadas para transmitir dados em um determinado formato.
- Soluções de arquitetura — REST
A arquitetura de um aplicativo pode ser criada de diferentes maneiras. Os métodos mais comuns são SOAP e REST. Nesta lição, você vai aprender sobre a API REST.
Características da REST
REST (sigla do inglês para "Representational State Transfer", que significa Transferência Representacional de Estado) é uma das maneiras de projetar uma API. Sua principal característica é a facilidade de exibir dados. Em outros estilos de arquitetura, os dados são "embalados" em uma camada adicional de marcação. Não há camada adicional na REST, então fica imediatamente claro a partir das solicitações e respostas o que acontece com os dados.

Por exemplo, o método POST cria dados, e o método DELETE os exclui.
Uma solicitação ao servidor contém apenas as informações que o servidor precisa para responder. No modelo cliente-servidor, muitos clientes podem acessar o servidor ao mesmo tempo. O servidor sabe apenas as informações que vieram na solicitação do cliente e não as armazena após o processamento da solicitação.
Estrutura multicamadas: essa arquitetura tem componentes que trocam dados, o cliente e o servidor. Além deles, também há componentes que distribuem fluxos de dados.
Componentes uniformes: cada componente da arquitetura REST é criado conforme regras claras.
Qualquer componente pode ser solicitado com uma URL específica. A solicitação vai conter todas as informações para que o componente possa processá-las corretamente.

Armazenamento em cache: quando o servidor envia uma resposta, ele ainda possui informações sobre quais dados devem ser armazenados em cache e quais não devem.
O estilo de arquitetura da API determina como os componentes da arquitetura trocam mensagens: em qual protocolo e formato. Ele determina a abordagem e as ferramentas que você vai usar para testar um aplicativo.

Por exemplo, você precisa testar uma API. Você sabe que ela é baseada em REST, o que significa que ela aceita solicitações HTTP no formato JSON. Essas informações ajudam a decidir sobre as ferramentas necessárias. Nesse caso, talvez seja melhor fazer testes usando o Postman, que é uma ferramenta para enviar solicitações HTTP à API e receber respostas.
HTTP: Estrutura de solicitação e resposta
HTTP é um protocolo que permite que o cliente e o servidor troquem mensagens.

O cliente envia uma solicitação HTTP ao servidor, que retorna uma resposta HTTP.
Uma solicitação HTTP consiste em três blocos:

A linha inicial contém o método de solicitação, URL e versão do protocolo.
Os cabeçalhos transmitem informações adicionais sobre o serviço. Por exemplo, o nome do domínio de um recurso ou o tamanho do conteúdo em bytes.
O corpo da mensagem contém os dados enviados pelo cliente. Por exemplo, o texto que um usuário inseriu no formulário de registro.
Nas próximas lições, você vai encontrar muita coisa sobre método e URL.

O método informa ao servidor qual ação executar. Os métodos mais comuns:

GET - solicita dados
POST - cria dados
DELETE - exclui dados
PUT - atualiza dados.
- A URL é o endereço que o cliente usa para solicitar os dados. O servidor aceita a solicitação de URL, a processa e envia uma resposta.
Nas próximas lições, você verá código de status, texto de status e corpo da mensagem.

Do que uma resposta HTTP consiste:

A linha de status contém a versão do protocolo, código de status e texto do status.
Os cabeçalhos transmitem informações adicionais, como a data e a hora em que a resposta foi criada.
O corpo da mensagem contém um conjunto de dados que o cliente recebe na resposta para as solicitações. Por exemplo, informações sobre todos os usuários registrados no aplicativo.
O código de status informa se o servidor processou a solicitação com sucesso. Por exemplo, o código 200 significa que tudo ocorreu bem, e o código 500 indica um erro interno de servidor.

O texto de status é uma descrição textual do código de status. Por exemplo, o erro 500 é um "erro interno de servidor".
JSON
Agora você sabe que precisa de uma API para comunicar e transferir informações entre aplicativos. Essas informações devem vir em um determinado formato para que os aplicativos possam se entender, e o formato JSON costuma ser usado pela arquitetura REST.

O JSON (sigla em inglês para "Javascript Object Notation", que significa Notação para Objeto em JavaScript) é um formato "leve" que é geralmente usado ao trocar dados entre aplicativos, e sua principal vantagem é que ele é fácil de ler e escrever.

Com o JSON, você pode descrever quase qualquer objeto do mundo real estruturalmente para uso no sistema.
Por exemplo, você quer descrever informações sobre uma pessoa, como nome e sobrenome. No formato JSON, isso pode ser assim:

{
  "first_name": "John",
  "last_name": "Johnson"
}
Você está olhando para pares do tipo key:value (chave:valor).

Se você pensar em uma pessoa como um objeto, ela vai ter várias propriedades: idade, local de nascimento, formação, livro favorito e assim por diante. Duas dessas propriedades estão descritas abaixo: nome e sobrenome.

"key" é o nome da propriedade, por exemplo, nome e sobrenome. "value" vem depois de um sinal de dois pontos.

Key	Value
first_name	"John"
last_name	"Johnson"
Os parâmetros são listados separados por vírgulas e descritos em um determinado formato. Por exemplo, key sempre é usado entre aspas duplas, enquanto value depende do tipo de dados. Os dados de texto ficam entre aspas.

Observação: um conjunto de pares é colocado entre chaves, o que permite indicar que se referem ao mesmo objeto.

Você precisa adicionar a idade de uma pessoa à estrutura:

{
  "first_name": "John",
  "last_name": "Johnson",
  "age": 35
}
A chave age aparece, mas seu valor é um número. Os números geralmente não são incluídos entre aspas, mas às vezes você precisa transmitir um "número" (por significado), como uma "string" (usando a entrada JSON) — por exemplo, "age": "100".

Aqui 100 é uma string no contexto do formato JSON (e será tratado pelo aplicativo como uma string), mas é essencialmente um número (o usuário sabe que 100 é um número).

A próxima etapa é adicionar informações sobre estado civil e se a pessoa tem filhos:

{
  "first_name": "John",
  "last_name": "Johnson",
  "age": 35, 
  "is_married": true,
  "has_kids": false
}
Uma lógica binária condicional opera no "Estado civil":

true
false
Esses valores são chamados de booleanos. Eles também não são colocados entre aspas. A chave é descrita como uma condição: "Se a pessoa for casada", "Se tiver filhos". O valor responde a essas perguntas: sim ou não.

E se um parâmetro puder conter diversos valores? Por exemplo, endereços de e-mail disponíveis são especificados da seguinte forma:

{
  "first_name": "John",
  "last_name": "Johnson",
  "age": 35, 
  "is_married": true,
  "has_kids": false,
  "emails": ["johnson.j@tripleten.com", "john@tripleten-students.com"]
}
Ok
Escrever um valor entre colchetes indica uma lista, ou, em outras palavras, um vetor. A lista pode conter um valor — "type": ["dog"], diversos valores — "type": ["dog", "cat"] ou ser deixada em branco. Por exemplo, se uma pessoa não tiver endereço de e-mail, esses dados ainda serão transmitidos, e vai ficar assim: "emails": [].

Os valores em um vetor podem ser representados não apenas por texto, como também por números e outros objetos. Por exemplo, agora temos alguns dados sobre animais de estimação:

{
  "first_name": "John",
  "last_name": "Johnson",
  "age": 35, 
  "is_married": true,
  "has_kids": false,
  "emails": ["johnson.j@tripleten.com", "john@tripleten-students.com"],
  "favorite_numbers": [0, 7, 42],
  "pets": [{"type": "dog", "name": "Buddy"}, {"type": "cat", "name": "Watson"}]
}
Legal
Em um vetor, os dados são separados por vírgulas em uma lista, e a ordem é importante. Por outro lado, em objetos, onde os parâmetros são definidos por pares key:value, a ordem não é importante.

Assim como um vetor, um objeto pode estar vazio. Nesse caso, o valor será escrito entre chaves, sem conteúdo entre elas: {}.
Se você quiser especificar que nenhum valor foi atribuído a um parâmetro, use a notação "pets": null — a palavra null indica que o valor do parâmetro não foi definido.

A estrutura de dados no formato JSON pode ser muito diversa e depende das informações que você quer descrever. Pode ser uma lista simples, como os artigos de produtos que o usuário comprou [10429, 23294, 12357] ou até um longo conjunto de parâmetros, onde cada um é um objeto separado com sua própria estrutura. Aqui estão alguns exemplos:

{
     "user": {
         "name": "John",
         "lastVisited": "2022-02-11",
         "previous_order_ids": [10032, 12158, 77923]
     },
     "last_order": {
         "article": 76240,
         "prepaid": true,
         "price": 999.99,
         "need_delivery": false,
         "comments": null
     },
     "additional_info": {}
 }

Introdução: Testes de API com Postman

O que você vai aprender:
Como enviar solicitações HTTP via Postman
Como configurar a variável URL e cURL
Como testar interações com bancos de dados
O que você precisa incluir em um relatório de bug para API
O que são logs e como lê-los
Onde encontrar e como usar a documentação da API.
Postman: recursos básicos
O Postman é uma ferramenta para testar API que ajuda a enviar as solicitações HTTP e HTTPS à API e receber as respostas.
URL dinâmica no Postman
Imagine que, ao verificar a API, você conseguiu criar e salvar três solicitações no Postman, mas houve um erro no servidor ou você se distraiu e teve de encerrá-lo.

Para continuar a verificação, você deve reiniciar o servidor, mas a URL será alterada, e seria necessário alterá-la em todas as solicitações para que sejam enviadas ao novo endereço.

Alterar a URL em três casos não é difícil, mas, às vezes, há muitas solicitações e leva muito tempo alterá-las manualmente.
O Postman tem um recurso de "Ambiente" (Environment) que permite definir uma variável e colocá-la em diferentes solicitações.

Se você alterar o valor de uma variável em um lugar, ela será alterada em todos os lugares.

Com isso, não é necessário alterar URLs de maneira manual. Você coloca uma variável em vez de um endereço, e alterar esse valor o altera em todas as outras solicitações automaticamente.
- 
cURL e geração de solicitação do Postman para cURL
Há mais um recurso que você pode usar no Postman: trabalhar com cURL.

O que é cURL :
cURL é um aplicativo para manipular solicitações HTTP(S). Se você usa MacOS ou Windows 10, já tem ele no seu computador. Se você usa uma versão antiga do Windows ou Linux, vai precisar instalar o cURL. Por enquanto, você não vai precisar do aplicativo, já que vai fazer tudo com o Postman.

O cURL trabalha com as solicitações HTTP(S) via console.
Normalmente, você manipula seu computador por meio de uma interface gráfica ao clicar nos ícones e ao abrir as janelas dos programas. O console, ou linha de comando, deixa você manipular seu computador via texto. Você escreve um comando e o computador o executa.

cURL é um aplicativo que permite "interagir" com os servidores diretamente do console. Você escreve um comando de texto e uma solicitação é enviada à API.

Por exemplo, esta é uma solicitação na API do Urban.Grocers se você precisar procurar por kits de produtos com ids 1 e 22:

curl --location --request POST '<https://2d716e9e-f01f-459a-ba2d-79921085b3f3.containerhub.tripleten-services.com/api/v1/products/kits>' \ 
--header 'Content-Type: application/json' \ 
--data-raw '{"ids": [1, 22]}'

Se você escrever esse comando no console, uma solicitação vai ser enviada à API e uma resposta será retornada. Você vai vê-la lá também.
Aqui está a composição da solicitação:

curl — é o comando que inicia o cURL.
--request POST — é o parâmetro que especifica o método e a URL. É o método POST e URL no exemplo: https://2d716e9e-f01f-459a-ba2d-79921085b3f3.containerhub.tripleten-services.com/api/v1/products/kits.
--header — é o parâmetro que contém os cabeçalhos da solicitação. No exemplo, o cabeçalho informa que o corpo da solicitação está no formato JSON: Content-Type: application/json.
--data-raw — é o parâmetro que contém o corpo da solicitação. No exemplo, os ids dos produtos 1 e 22 são enviados no corpo.
<img src="C:\Users\janai\Documents\Botcamp QA\Imagens\Image (50).png">
Um comando cURL é fácil de copiar e enviar a seus colegas em qualquer aplicativo de mensagens. Você também pode adicioná-lo a requisitos, checklists, casos de teste e relatórios de bug por conveniência.

Imagine que você está testando uma API e encontra um bug. Você vai precisar escrever um relatório de bug para que o desenvolvedor ou outro testador possa executar a solicitação e recriar o problema. Se você adicionar o comando cURL, seu colega poderá fazer isso bem rápido usando o console.

Como converter uma solicitação do Postman para um comando cURL?
Abra o Postman. Encontre uma solicitação para a API do Urban.Grocers que você criou nas lições anteriores, por exemplo, "Criar um kit vazio."

Encontre a área para trabalhar com a solicitação. Clique no ícone </>.
Banco de dados e API
Outro elemento de uma arquitetura de aplicativo é o banco de dados, que armazena informações no aplicativo.

O back-end interage com o banco de dados enviando solicitações e recebendo dados na resposta.
Entendido!
Os bancos de dados podem ser organizados de diferentes maneiras. A mais comum é a relacional, onde as informações são armazenadas em tabelas.
Como isso está relacionado a testes de API?
Ao testar a API, é importante verificar se as alterações — adições, modificações ou exclusão de dados — foram registradas corretamente no banco de dados.

Relatório de bugs para API
Um relatório de bug é um relatório específico que descreve informações sobre o que está errado e precisa ser corrigido. Ele tem campos opcionais e obrigatórios. 

Logs na API
Os logs são registros de eventos que acontecem em um aplicativo.

Os eventos em uma API também são registrados. Veja o que está incluído nos logs de uma API:

Uma solicitação HTTP com uma descrição de parâmetros, cabeçalhos e o corpo
Os bugs que ocorreram durante o processamento da solicitação
Às vezes, uma resposta HTTP com uma descrição do código da resposta é adicionada à estrutura do log. Os desenvolvedores precisam disso para depurar o aplicativo; por exemplo, se quiserem entender se o serviço retorna uma resposta.

Por que um testador precisa de logs?
Imagine que você está testando recursos e enviando uma solicitação à API. Se um erro for retornado, você pode encontrá-lo nos logs e entender o que aconteceu no aplicativo. Os logs podem ser copiados e anexados a um relatório de bug.
- Documentação da API
Quando você compra um dispositivo, como uma impressora, sempre há instruções ou documentação.

Ao trabalhar com uma API, você também precisa de documentação.
A documentação ajuda a entender como a API de um determinado componente ou aplicativo funciona. Aqui está o que ela descreve:

Ações que podem ser feitas com o sistema; os dados que podem ser solicitados.
Limitações em dados transmitidos. Por exemplo, alguns parâmetros podem ter restrições sobre o tipo de dados (número ou string) e de tamanho (2-50 caracteres).
A estrutura das solicitações, respostas e endereços para os quais as solicitações podem ser enviadas.

A documentação descreve o que a API pode fazer — quais solicitações ela aceita e quais respostas pode enviar. Isso é uma documentação separada, diferente da documentação para o back-end.
Quem escreve a documentação?
O desenvolvedor ou arquiteto responsável pela criação da API de um componente ou aplicativo. Essas pessoas são as melhores para descrever o que é a API.
Escritores técnicos ou analistas que trabalham com o aplicativo.
Onde posso encontrar a documentação?
A documentação pode estar disponível abertamente se o produto for público. Alguns exemplos:

API Facebook
API Slack
Ela pode estar indisponível se for um serviço interno de um produto ou empresa. Se você for testar algum serviço, peça a documentação ao gerente do projeto ou aos desenvolvedores.
- Swagger

Onde a documentação é armazenada?
Você pode armazenar a documentação no formato de texto se a API e sua documentação forem simples e pequenas.

Se o sistema for complexo, a documentação cresce, dificultando a manutenção e navegação.

Para simplificar o trabalho com a documentação, são utilizadas ferramentas que a geram automaticamente. Um exemplo disso é o Swagger
O desenvolvedor prepara um arquivo especial com uma descrição de solicitação para a API, e a ferramenta o transfere automaticamente para a estrutura.
Cada linha especifica o caminho que deve ser adicionado à URL para executar a solicitação.

Por exemplo, o aplicativo Urban.Grocers está localizado em https://{id}.containerhub.tripleten-services.com. Você precisa criar uma solicitação que vai ajudar a obter todos os cartões no aplicativo. A solicitação para a estrutura URL + caminho vai ser assim: https://{id}.containerhub.tripleten-services.com/api/v1/cards.
A solicitação chama a função correspondente na API, o que significa que o cliente entra em contato com o servidor.

A parte do serviço para a qual o cliente envia a solicitação é chamada de endpoint. Um endpoint também é chamado de "método API" ou "URL de recurso.”

Quando ele é acessado pela URL, o endpoint realiza a ação necessária.
Na documentação, você pode clicar na linha com o método API para ver as informações detalhadas sobre a solicitação.

Apidoc
Agora você sabe como estudar a documentação de API no Swagger. Equipes diferentes usam diferentes ferramentas para armazenar a documentação, dependendo do que for mais conveniente para cada caso. Há outra ferramenta para trabalhar com a documentação, o Apidoc, que você vai usar nesta lição.

O Swagger e o Apidoc têm mecanismos semelhantes: a documentação de API é gerada automaticamente a partir de um arquivo. Eles diferem no design da interface e nas características técnicas dos geradores, que não são visíveis para o usuário.

- Introdução: Design de testes para teste de API

O que você vai aprender:
Como projetar testes positivos e negativos para API
Como identificar classes de equivalência e valores de limite para uma API
Como testar a validação de API
Testes positivos
O teste de API usa as mesmas abordagens que outros tipos de teste:

- Testes positivos e negativos
Técnicas de design de teste: classes de equivalência e valores-limite, tabelas de decisão, teste de pares
Vamos começar com os testes positivos e negativos para uma API.
Quais são as características dos testes positivos para uma API?
Ao testar aplicativos móveis e web, você interage com eles mediante uma interface gráfica como se fosse um usuário. Para testar uma API, você "interage" com o aplicativo da mesma forma que outro aplicativo faria: com as solicitações HTTP.

- Os casos de testes positivos verificam se o aplicativo funciona sem erros em dois casos:

se você usá-lo como pretendido e não tentar quebrá-lo.
se você inserir dados válidos conforme os requisitos.
Um exemplo de API
Imagine que você precisa testar a API do aplicativo Urban.Grocers. Aqui estão os requisitos.

Um deles diz: "Deve haver uma URL que permite criar um kit: POST /api/v1/kits"

Você precisa testar se a URL realmente permite que o usuário crie um kit. Isso é o que você vai precisar fazer:

Enviar uma solicitação à URL especificada para criar um kit
Verificar se o kit realmente foi criado
É um teste positivo: você garante que os recursos funcionam conforme o esperado.
Um teste passo a passo
Primeiro, você deve criar uma solicitação. Aqui está o que você precisa saber para isso:
Quais dados enviar e em qual formato criar a solicitação (parâmetros da solicitação)
Se há limitações na entrada; como o número de caracteres
Para qual URL enviar a solicitação e qual método usar.
Para saber quais dados devem ser enviados na solicitação, confira a documentação da API. Ela menciona os parâmetros. 
- Testes negativos
Os casos de testes negativos verificam como um aplicativo se comporta nos seguintes casos:

Você usa o aplicativo de forma diferente da pretendida pelos desenvolvedores.
Você insere dados inválidos.
Um exemplo de API
Por exemplo, você continua projetando testes para criar um kit no Urban.Grocers.

Você já sabe o que precisa para enviar o cardid existente no cartão. Usar os recursos de maneira não intencional, enviando um cardId inexistente. Isso é um teste negativo.

Se o comportamento do aplicativo nesse caso não estiver descrito nos requisitos, é importante verificar que ele não vai travar ou ter falhas.
E se o comportamento estiver descrito nos requisitos?
Se o comportamento estiver descrito, o aplicativo deve responder conforme necessário. Por exemplo, os requisitos informam: "Se o cardId especificado não estiver no banco de dados, uma resposta 404 Not found deve retornar, e a mensagem deve informar "O cartão especificado não foi encontrado."

Então, se você enviar uma solicitação à API com um cardId inexistente, já sabe como o aplicativo vai reagir: neste caso um erro 404 é o comportamento normal para o aplicativo, e não será preciso criar um relatório de bug.
Como executo o teste?
Você precisa fazer o mesmo que na última lição: criar uma solicitação, enviar à API e ver o que acontece. Os dados, porém, serão diferentes.

Por exemplo, você pode usar um id inexistente: 100500. Não existe tal valor na tabela card_model.

Você vai obter uma solicitação com o corpo {"cardId":100500, "name": "Salada fresca"}.

Qual será o resultado esperado?
O resultado esperado costuma estar escrito nos requisitos, como no exemplo acima. Se não estiver lá, verifique se o aplicativo não trava. O ideal é que um código de erro seja retornado. 

Se o aplicativo parar de funcionar, você precisa relatar um bug.
Classes de equivalência
Lembre-se de como funciona a técnica de classe de equivalência. Você precisa observar os requisitos e identificar os grupos de valores para os quais os aplicativos vão reagir da mesma maneira.

Por exemplo, se o requisito for "Comprimento do nome de 2 a 15 caracteres", você terá três classes: 0 a 1 caractere, 2 a 15 caracteres, e 16 a ∞ caracteres. Para testar uma classe, você precisa testar apenas um valor de classe.

Um exemplo de API
O Urban.Grocers tem um recurso "Criar usuário". Descubra como testá-lo usando as classes de equivalência.

Confira os requisitos aqui. Eles dizem: "Um usuário pode se registrar." A URL que cria o usuário é POST /api/v1/users.

Para projetar um teste com classes de equivalência, você precisa:

Criar uma solicitação que verifica se o usuário pode ser criado.
Verificar se a solicitação funciona.
Identificar as classes de equivalência.
Usar a solicitação como modelo e inserir nela diversas variantes de dados baseadas nas classes de equivalência.
Vamos passo a passo
Primeiro, você precisa criar uma solicitação com quaisquer dados e verificar se ela funciona.

Consulte a documentação da API. Descubra o seguinte:

Qual endpoint é responsável pela criação de um usuário
Quais parâmetros enviar na solicitação para criar um usuário.
- Valores-limite
Os valores-limite são o primeiro e último ponto no intervalo. Por exemplo, se o nome puder ter de 0 a 15 caracteres, os valores-limite são 0 e 15.

Validação de API
Validação é um mecanismo que testa se a solicitação à API foi feita corretamente. Ela verifica se você especificou os dados no formato correto e se há erros na estrutura.

As regras de validação são escritas pelos desenvolvedores no código, tanto do lado do cliente quanto do servidor. É melhor escrever a validação no back-end, pois um intruso pode contorná-la no lado do cliente, mas conseguir acesso ao servidor não é comum.

A validação pode alertar sobre o seguinte:

A estrutura da solicitação está incorreta. Por exemplo, alguns parâmetros obrigatórios ou tags estão faltando.
Os dados não estão registrados corretamente: há muitos caracteres ou o formato está errado.
Por que um testador precisa disso?
Quando você testa a API, precisa testar a validação.

A validação da estrutura da solicitação
Aqui está o que pode dar errado com a estrutura da solicitação:

Tipo de dados incorreto no corpo (como um número em vez de uma string ou vice-versa)
Estrutura incorreta do corpo da solicitação (por exemplo, o formato JSON não foi usado)

Alterando meu README.
PROJETO FINAL:
Está  na hora de colocar seus conhecimentos em práticas e realizar um projeto que irá abordar, todo conteúdo estudado no decorrer deste conteúdo que estudo.
Neste sprint, você vai concluir o projeto final deste programa: três tarefas grandes. 
A primeira tarefa é teórica e vai verificar seu conhecimento sobre os principais aspectos de teste. Você vai responder a perguntas semelhantes em entrevistas de emprego, então leve essa tarefa a sério.

As tarefas 2 e 3 são práticas e vão verificar se você sabe analisar e fazer o design de testes; ou seja, se você sabe como testar aplicativos da web e APIs.

Você vai testar o aplicativo Urban.Scooter: um serviço que permite alugar uma scooter elétrica por alguns dias.

O que precisa ser feito
Observe que você não precisa testar todo o aplicativo. Examine o que exatamente você precisa testar.
Estude a documentação do aplicativo em cada tarefa. Ela está armazenada como uma lista de requisitos e designs, bem como requisitos para as URLs para as quais o aplicativo envia dados.
Crie um mapa mental para visualizar os requisitos onde for necessário.
Divida os recursos em blocos atômicos e defina objetos de teste.
Faça o design de testes para lidar com todos os requisitos.
Aplique classes de equivalência, valores-limite e uma tabela de decisão quando apropriado.
Otimize o número de testes nos testes de interface de usuário e testes lógicos dos recursos.
Execute testes e faça relatórios de bugs, se necessário.
Use o DevTools ou Postman para verificar solicitações para determinadas URLs.
- Alterando meu README.