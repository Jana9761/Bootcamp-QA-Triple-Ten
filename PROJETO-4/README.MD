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

Projeto-4


PROJETO FINAL










