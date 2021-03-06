# MetodologiaScrum
Scrum
Aplicação de Métricas de Software com Scrum
Alunos: Jeymmison Alves e Matheus Enriqui Lazario
Faculdades Integradas Camões  – Curitiba – PR – Brasil
 jeymmison.alves@biometrix.com.br, matheus.lazario@vetore.com
 
 
 
Abstract. This paper presents a summary of the article Software Metrics application with Scrum , with the techniques used , the case study , the application of metrics , analysis of the results the conclusion of the study and the interpretation of the staff in relation to Article studied.
Keywords: Software metrics, scrum, function point analysis, ideal day, planning poker.
Resumo. Este trabalho apresenta a um resumo do artigo Aplicação de Métricas de Software com Scrum, apresentando as técnicas utilizadas, o estudo de caso, a aplicação de métricas, as análises dos resultados a conclusão do estudo, bem como a interpretação da equipe em relação ao artigo estudado. 
Palavras Chaves: Métricas de software, scrum, pontos de função, ideal day, planning poker.
1. Introdução
O presente tem por objetivo apresentar um resumo do artigo Aplicação de Métricas de Software com Scrum, como trabalho da matéria de engenharia de software do curso de análise e desenvolvimento de sistemas oferecido pelas faculdades integradas camões.
O artigo (estudo de caso) foi redigido por Mateus Luiz Gamba e Ana Cláudia Garcia Barbosa para Unidade Acadêmica de Ciências, Engenharias e Tecnologias da Universidade do Extremo Sul Catarinense (UNESC).
2. Técnicas Utilizadas
O artigo, teor deste resumo, teve como objetivo uma análise da viabilidade da aplicação de algumas técnicas de métricas, ao fazer uso da metodologia ágil (Scrum) para gestão de planejamento de projetos de software.
Neste contexto foi efetuado um estudo de caso em uma empresa desenvolvedora de sistemas integrados de gestão empresarial. Os sistemas que esta empresa desenvolve, são baseados em plataforma web, utilizando-se de banco de dados pós-relacional Caché, com sua linguagem nativa e outras comuns como Hypertext Markup Language (HTML), Cascade Style Sheets (CSS) e Javascript.
As técnicas de métricas selecionadas para aplicar o estudo de caso foram três: Ideal Day, Planning Poker e Pontos de Função.
A técnica de Ideal Day consiste em calcular a quantidade de tempo necessário para concluir uma tarefa. Este cálculo é feito a partir do número de horas que a equipe estima despender para implementar e concluir uma tarefa ou parte dela em um dia de trabalho.
Possuindo o número de horas estimado o mesmo é divido pelo numeral 1 (um) menos o percentual presumido de tempo que será dedicado a este dia nas tarefas escolhidas. O resultado é prazo de tempo estimado para o término da tarefa. Caso haja necessidade e o trabalho exceda um dia, é possível decompor esta tarefa em tarefas menores para que as somas destas tarefas menores ocupem o tempo de somente um dia.  A fórmula do cálculo esta ilustrada abaixo.
 
Onde:
DE: quantidade de dias estimados para concluir a tarefa;
IED: prazo necessário para implementar o item, esse prazo é definido pela equipe;
IED_REAL%: percentual que indica a estimativa de quanto tempo do dia o desenvolvedor ficara dedicado a implantação do item.
A técnica de Planning Poker é composta por uma pontuação inspirada na sequência de Fibonacci. Sendo assim, cada integrante da equipe possui cartas com esta pontuação e as atribui para os requisitos considerados na sprint. As atribuições destes pontos devem estar de acordo com o que o indivíduo da equipe acredita ser a dificuldade deste requisito, considerando tudo o que possa impactar nesta tarefa.
Todos os membros da equipe, após terem escolhido sua pontuação para a tarefa em questão, atribuem os pontos e os discutem até que se alcance uma pontuação comum. Uma ou mais rodadas podem ser necessárias até que a equipe chegue em um acordo em conjunto. Isto é feito para todos os requisitos deste sprint.
A técnica de Pontos de Função, diferentemente das supracitadas, tem como principal objetivo não só estimar um requisito em si, mas o tamanho funcional do software, fundamentando-se em vários aspectos sob o ponto de vista do usuário. Além de oferecer o tamanho funcional do software, traz alguns benefícios como melhor acompanhamento da produtividade da equipe, maior influência na qualidade e custos de desenvolvimento, bem como maior previsibilidade do projeto nas fases iniciais.
3. O Estudo de Caso
O estudo de caso foi aplicado utilizando as métricas citadas em uma equipe que iniciava a utilização da metodologia Scrum. Como diretrizes para aplicação desta metodologia foi definido que esta equipe seria composta de quatro integrantes com especialidades em desenvolvimento de sistemas de análise de testes e engenharia de software. A duração de uma sprint seria de dez dias, em que, nesse período, seguiriam-se as regras ditadas pelo scrum e a aplicação das métricas escolhidas.
Como auxilio no entendimento dos requisitos e para se obter uma maior acurácia no desenvolvimento, além do scrum master, o product owner e os stakeholders estiveram diretamente envolvidos na sprint.
O projeto teve início com a elaboração do product backlog, de trinta e quatro requisitos, sendo que destes foram selecionados para sprint somente os de maior prioridade e relevância. Sendo assim o product owner selecionou estes requisitos, detalhando-os a equipe até que esses fossem assimilados pela mesma, portanto, ela poderia aplicar as métricas de forma satisfatória.
Então, as métricas foram aplicadas nos requisitos escolhidos pelo product owner, somando um total de vinte e três requisitos para a sprint em questão. A aplicação se deu em duas partes, em primeiro foi aplicado o Ideal Day e o Planning Poker, que auxiliou nas escolhas de todo trabalho que seria executado no sprint. Em segundo a aplicação das métricas de Ponto de Função.
4. Aplicação das Métricas
Para a técnica do Ideal Day foi definido a seguinte escala de porcentagem dia, 0,25, 0,5, 0,75, 1, 1,25, 1,5 e assim por diante. Para aplicar à métrica a equipe discutiu cada item até chegar um consenso, definindo que todos empregariam 90% do dia no desenvolvimento de seu trabalho. Por fim a equipe calculou que seriam necessários 13,5 dias para a conclusão de toda a tarefa orçada.
Aplicando a fórmula do Ideal Day, chegou-se à conclusão de 14,64 dias para conclusão das tarefas, baseando-se num dia com 8 horas de trabalho. Portanto, a métrica resultou numa sprint de 117,3 horas.
No Planning Poker os membros da equipe empregaram a pontuação inspirada em fibonacci, assim anunciando a dificuldade de cada requisito e, então, estimando o tempo total de cada tarefa da sprint. Foi definida a iniciação pelas tarefas consideradas mais fáceis e progredindo para as consideradas mais difíceis. Após diversas rodadas de pontuações chegou-se ao resultado de 117 pontos e, portanto, um total de 117,5 horas.
Com o trabalho do sprint definido, ou seja, do total de 34 requisitos foram escolhidos 23 destes para serem desenvolvidos, foi feito uma descrição resumida deles para que se encaixassem nos moldes do scrum e, portanto, implementados de forma ágil.
Ao se começar a implementação, se deu início ao processo de contagem de pontos de função. Para tanto, foi respeitado os processos de tipo de contagem, escopo de contagem e fronteira da aplicação, contagem das funções de dados, contagem das funções transacionais e determinação dos pontos de funções não ajustados. Por serem três novos módulos foi classificado como projeto de desenvolvimento, pois esta definição tem impacto na utilização da métrica.
Segundo o artigo, outras questões levadas em conta sobre a aplicação da técnica de pontos por função é que não foi explorado o fator de ajuste, bem como o cálculo dos pontos de funções ajustados, pois os módulos foram desenvolvidos como continuidade de um software existente, por ser orientado a objetos, plataforma web, pelo fato do scrum ser uma metodologia ágil e pontos de função não ser considerada uma métrica de estimativa de prazo ágil.
Para cada ponto foi representado um prazo de horas, semelhantes às outras técnicas e chegou-se ao resultado de 211 pontos de função e, portanto, 40,30 horas.
Apesar da grande discrepância com as outras métricas, a equipe decidiu por não efetuar recálculos com o intuito de averiguar se algum dos valores resultava a algo semelhante do encontrado ao final do estudo.
5. Análise dos Resultados
Após a coleta de todas as informações e definições sobre o sprint, demos continuidade ao trabalho, implementando os requisitos especificados, alcançando o final do desenvolvimento da sprint. Então foi feita a coleta das informações acerca do tempo real do projeto para confrontar com as estimativas obtidas através das técnicas de métricas implantadas.
O tempo total de trabalho foi de 107,2 horas, ou seja, a quantidade de horas calculada por nós durante o sprint ficou similar ao avaliado pelas métricas Ideal Day e Planning Poker, ficando apenas 8,66% abaixo do tempo.
Acerca da métrica de Pontos de Função, segundo os autores do artigo, não foi possível definir a complexidade do projeto e, sim, o tamanho. Contudo foi aplicando-se algumas simulações de cálculo para esta sprint, caso fosse executado novamente e chegou-se ao resultado de 211 pontos alcançando um total de 106 horas. Ressalta-se a dificuldade na elaboração e coleta dos dados por se tratar de uma metodologia ágil, que se contrapõe a métrica de pontos por função.

6. Conclusão do Estudo
Nós concluímos que apesar de terem alcançado resultados semelhantes nas técnicas Ideal Day e Planning Poker, que o Ideal Day se apresentou de melhor forma no início do projeto, pela sua facilidade em estimar o prazo em dias que se pretendia terminar o requisito.
A métrica de Planning Poker se torna interessante para medir o tamanho dos requisitos futuros, pois ao decorrer do projeto o prazo de dias do Ideal Day pode alterar pela troca de membros da equipe ou qualquer outra adversidade não prevista, algo que em contrapartida o Planning Poker facilmente contorna, alterando os pontos atribuídos para cada requisito.
A técnica de Pontos de Função obteve resultado distante das outras métricas, por não analisar a complexidade de iteração do usuário com o sistema em desenvolvimento e por ser um sistema web. Portanto chegou-se à conclusão que mais estudos seriam necessários para aplicação desta técnica.
A aplicação do estudo de caso foi considerada satisfatória, apesar de ser usufruída em apenas um sprint. Ajudando em um entendimento mais profundo das técnicas bem como do projeto em um todo.
7. Interpretação do Estudo pela Dupla e Conclusão
As atividades ficam mais evidentes, visto que todos podem participar ativamente da definição das atividades e cronogramas, chegando a um consenso para definições de prazo. 
Como as atividades são definidas em conjunto, as funcionalidades que agregam valor são colocadas em primeiro plano, porém as prioridades podem ser alteradas, desde que já se tenha os requisitos da funcionalidade prontos.
Contudo as alterações trazem também modificação nos prazos, o que pode ser considerado ruim, já que mudanças podem atrasar o já definido em cronograma.	
Com o estudo realizado foi possível perceber que as duas métricas consideradas ágeis obtiveram um melhor resultado, ao contrário da Pontos de Função que ficou bem distante do prazo estipulado.
A dupla concluiu que para se ter certeza de qual métrica é a melhor, é necessário aplicar em mais alguns sprints. Mais testes são necessários para confirmar se realmente Ideal Day é melhor que a Planning Poker, e dar novas oportunidades para a métrica de Pontos de Função.

