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
