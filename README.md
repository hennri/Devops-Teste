# Devops-Teste

1 – O que são testes em DevOps?

é a investigação do software a fim de fornecer informações sobre sua qualidade em relação ao contexto em que ele deve operar, se relaciona com o conceito de verificação e validação. Isso inclui o processo de utilizar o produto para encontrar seus defeitos.

O teste é um processo realizado pelo testador de software, que permeia outros processos da engenharia de software, e que envolve ações que vão do levantamento de requisitos até a execução do teste propriamente dito.

-----------------------------------------------------------------------------------------------------------------------------


2 – O que eles validam?

Por meio do teste de software, podemos avaliar a funcionalidade, usabilidade, portabilidade, velocidade de processamento, precisão das operações e da integração de processos, confiabilidade, integridade e eficiência do novo aplicativo.

------------------------------------------------------------------------------------------------------------------------------


3 – Qual a diferença entre Verificação e Validação?

A verificação é uma atividade que envolve a análise de um sistema para verificar se o mesmo atende aos requisitos funcionais
e não funcionais. Já a validação é a certificação de que o sistema atende as necessidades e expectativas do cliente,
validação e verificação não são processos independetes.


-------------------------------------------------------------------------------------------------------------------

4 – Quais os objetivos do teste?

Teste de Caixa-Branca

Idealmente, o teste de caixa-branca testa todas as partes do código do aplicativo. Trata-se de um procedimento estrutural que avalia os componentes internos de um programa para encontrar falhas que serão solucionadas pelos desenvolvedores do aplicativo.

Teste de Caixa-Preta

Analisa todas as entradas e saídas desejadas para o aplicativo e mapeia todos os erros percebidos. Entre outras funções, serve para simular os possíveis equívocos operacionais, que podem ser cometidos pelos futuros usuários, para saber como o software responderá.


--------------------------------------------------------------------------------------------------------------------


5 – O que é um Test Case?

Um test case é um conjunto de condições ou variáveis
sob as quais um testador determinará se um sistema em teste satisfaz os requisitos ou funciona corretamente.

---------------------------------------------------------------------------------------------------------------

6 – O que é um Test Suite?

O test suite é um contêiner que possui um conjunto de testes que ajuda os testadores a executar e reportar o status de execução do teste.
Pode levar qualquer um dos três estados, ou seja, ativo, em progresso e concluído.
Um caso de teste pode ser adicionado a vários conjuntos de testes e planos de teste. Depois de criar um plano de teste,
são criados conjuntos de testes que, por sua vez, podem ter qualquer número de testes.

Os conjuntos de testes são criados com base no ciclo ou no escopo. Ele pode conter qualquer tipo de teste,
viz - funcional ou não funcional.

------------------------------------------------------------------------------------------------------------------


7 – Quais são os tipos de teste?

Teste de Aceitação pelo Usuário

Verifica se o aplicativo será considerado amigável pelo usuário. Procura perceber se haverá qualquer elemento da interface que possa causar rejeição por parte do usuário do software. O teste de aceitação é uma validação que o usuário faz antes de colocar em produção. Basicamente, ele verifica se o sistema faz o que ele solicitou e atende requisitos específicos (cores da empresa do cliente, tempo de resposta baixo, etc). O cliente decide o que ele irá validar nesse teste – que também pode ser realizado nos processos que irão avaliar a usabilidade.

Teste de Carga

Avalia como o software se comporta quando há um grande número de usuários simultâneos.

Teste de Configuração

Testa o funcionamento do aplicativo em diferentes ambientes de hardware e software — valida sua portabilidade.

Teste de Funcionalidade

É feito para validar os requerimentos e regras de negócio associadas às funcionalidades do software, que podem estar divergentes das determinações existentes em sua documentação. Identifica também se a aplicação cumpre com a função.

Teste de Instalação

Verifica se todos os componentes do software foram instalados corretamente em diferentes situações de configuração de hardware/software e em situações adversas, como queda de energia elétrica e espaço insuficiente de memória do hardware.

Teste de Integração

Permite verificar se unidades ou os componentes combinados do aplicativo funcionam.

Teste de Interface

Averigua se as telas do software são de fácil navegabilidade e se são intuitivas, para que atendam o usuário da melhor maneira.

Teste de Integridade

Verifica se os componentes do aplicativo permanecem íntegros mesmo quando comportam grandes volumes de dados, e testa sua resistência a falhas — avaliando sua robustez.

Teste Operacional ou de Estabilidade

Avalia se o software pode rodar por muito tempo sem apresentar falhas.

Teste de Performance

Mensura se o tempo de resposta de cada rotina do aplicativo está adequado e identifica o ponto de exaustão do software.

Teste de Manutenção

Verifica se a manutenção do ambiente de software e hardware causou algum efeito indesejado no aplicativo.

Teste Positivo-Negativo

Pretende garantir que o software irá funcionar corretamente em seu fluxo normal, assim como no seu fluxo de exceção.

Teste de Regressão

Trata-se da testagem completa do aplicativo a cada mudança ou atualização realizada, para verificar se houve alteração do comportamento dos componentes já analisados, em função da introdução de um novo componente.

Teste de Segurança

Experimenta a navegação no software utilizando os diversos papéis, perfis, permissões, a fim de validar os critérios de segurança estabelecidos. Sua intenção é garantir que os dados estejam disponíveis somente às pessoas autorizadas e que o aplicativo não esteja vulnerável a invasões de hackers/crackers.

Teste de Stress

Testa a navegação no software seguindo trilhas não especificadas em sua documentação para ver como o aplicativo se comporta em situações inesperadas. Este teste visa identificar o momento crítico em que o programa deixa de salvar dados ou estes são corrompidos, ocorrem travamentos ou alguns comandos não são atendidos.

Teste de Unidade

Valida o funcionamento de cada componente individual do aplicativo, unidade a unidade ou de cada classe do aplicativo, testando se ocorre o retorno esperado quando se fornece dados válidos e dados inválidos.

Teste de Usabilidade

Teste voltado para a experiência do usuário, como irá acessar as funcionalidades, se as interfaces facilitam as operações, têm padrão visual e seu layout está adequado ao uso pretendido, assim como validam os materiais de treinamento (manual do usuário, tutoriais, help online).

-------------------------------------------------------------------------------------------------------------------------




8 – O que são testes do tipo Caixa Branca e Caixa Preta?

Teste de Caixa-Branca

Idealmente, o teste de caixa-branca testa todas as partes do código do aplicativo. Trata-se de um procedimento estrutural que avalia os componentes internos de um programa para encontrar falhas que serão solucionadas pelos desenvolvedores do aplicativo.

Teste de Caixa-Preta

Analisa todas as entradas e saídas desejadas para o aplicativo e mapeia todos os erros percebidos. Entre outras funções, serve para simular os possíveis equívocos operacionais, que podem ser cometidos pelos futuros usuários, para saber como o software responderá.

--------------------------------------------------------------------------------------------------------------------------


9 – Procure o que é o diagrama da pirâmide de teste, e a sua relação com o
custo. Reproduza o diagrama com comentário.

O diagrama da pirâmide de teste é descrito por uma representação gráfica onde encontramos testes unitários, seguidos pelos testes de integração, para testar as chamadas de serviços e APIs e, por fim, os testes end-to-end, focando os fluxos principais do sistema e os feedbacks de interface.
Segue Link com exemplo do diagrama: https://github.com/angrenost/Imagem_Piramide/blob/master/ImagemLeo-1-1024x628.png

Sergio Ferraz Almeida RA 1800709

--------------------------------------------------------------------------------------------------------------------------

10 – Percentualmente, qual é a distribuição dos tipos de testes na pirâmide
de testes?

Percentualmente, a distribuição dos tipos de testes na pirâmide de testes é de 70% testes small ou unitários, 20% testes medium ou integrados e 10% de testes large ou end-to-end.


Sergio Ferraz Almeida RA 1800709
