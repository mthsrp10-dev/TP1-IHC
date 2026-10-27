# Teste de Usabilidade

Este documento registra o Teste de Usabilidade da **versão web gratuita do Flightradar24**, realizado com participantes externos à equipe. Ele apresenta o planejamento, o teste piloto, a execução das sessões e a análise dos resultados, na mesma ordem em que o teste foi conduzido.

---

## 1. Planejamento

Antes de convidar os participantes, a equipe definiu o que pretendia observar, quais atividades seriam realizadas, quem participaria e quais instrumentos seriam usados. Esta seção reúne essas decisões.

### Objetivo do teste

O objetivo do teste é avaliar a usabilidade da versão web gratuita do Flightradar24 ([https://www.flightradar24.com](https://www.flightradar24.com)), observando se usuários externos à equipe conseguem realizar atividades típicas do sistema: acompanhar um voo, consultar seus detalhes, ver as chegadas de um aeroporto, usar filtros e guardar voos para acompanhar depois.

Durante as sessões, a equipe pretendia observar:

- **Eficácia:** se o participante consegue concluir cada atividade;
- **Eficiência:** quanto tempo leva e quantos erros comete;
- **Compreensão:** dificuldades com o vocabulário técnico da área, como siglas, unidades de altitude e velocidade e códigos de aeroporto;
- **Satisfação:** a percepção do participante sobre a experiência, coletada no questionário pós-teste.

### Participantes

O teste foi aplicado com **8 participantes**, todos externos à equipe, e com **2 participante no teste piloto**, que não integra os oficiais.

| Critério | Definição da equipe |
|---|---|
| Idade | Maiores de 16 anos |
| Relação com a equipe | Nenhum integrante da equipe participou como usuário |
| Experiência com tecnologia | Usam internet no celular ou no computador |
| Experiência com aviação | Com ou sem experiência de viagem de avião  |
| Local | Itacoatiara-AM |

*Os participantes foram convidados individualmente por meio do aplicativo WhatsApp. O recrutamento foi realizado com usuários externos à equipe, com idades entre 16 e 32 anos, residentes na região de Itacoatiara-AM. Para preservar a privacidade dos participantes, suas identidades foram mantidas em sigilo, sendo utilizados apenas códigos de identificação (P01, P02 e assim sucessivamente) na documentação dos resultados.*

### Tarefas

As atividades foram escritas como objetivos que um usuário comum teria, **sem indicar botão, menu ou caminho**. Cada uma traz no próprio cenário tudo de que precisa, para que o resultado de uma não dependa do resultado de outra. Todas as sessões seguiram a mesma ordem.

| Ordem | ID | Cenário apresentado ao participante | Funcionalidade | Critério de sucesso |
|---|---|---|---|---|
| 1 | T1 | Você ficou curioso para saber se tem algum avião voando sobre o Brasil agora. Encontre um e diga para onde ele está indo. | Mapa e detalhes do voo | Identifica um avião sobre o Brasil e informa o destino correto |
| 2 | T2 | Escolha um avião que esteja no ar e descubra a que altura e a que velocidade ele está voando. | Detalhes do voo | Informa altitude e velocidade exibidas |
| 3 | T3 | Você vai buscar um familiar no aeroporto de Manaus. Descubra quais voos estão previstos para chegar hoje. | Busca de aeroporto, chegadas | Encontra a lista de chegadas do aeroporto de Manaus |
| 4 | T4 | Um parente está viajando no voo [número informado pela equipe]. Descubra onde o avião está agora. | Busca de voo | Localiza o voo e indica a posição no mapa |
| 5 | T5 | Um parente está no voo [número informado pela equipe]. Descubra se ele está no horário ou atrasado. | Informações de horário e status | Informa corretamente o horário previsto e o status |
| 6 | T7 | Escolha um avião que esteja no ar e descubra por onde ele já passou desde que decolou. | Rota/trajetória | Visualiza o trajeto percorrido |
| 7 | T6 | Você quer ver apenas aviões de uma companhia aérea específica no mapa. | Filtros | Mostra no mapa só a companhia pedida |
| 8 | T8 | Escolha um voo que você queira acompanhar depois. Guarde-o e, em seguida, encontre-o de novo. | Marcadores (favoritos) | Salva o voo e o reencontra |

**Observações sobre a aplicação:**

- Os identificadores permanecem de T1 a T8. A ordem de aplicação coloca a T7 antes da T6, deixando filtros e marcadores, em geral mais difíceis, para o final.
- Nas tarefas T4 e T5, o número do voo foi escolhido pela equipe antes de cada sessão, entre voos que estivessem no ar, e informado ao participante. O voo usado em cada sessão ficou registrado.
- A tarefa T8 exige uma conta, então a equipe criou **uma conta gratuita de teste, sem dados pessoais**, usada em todas as sessões. O login foi feito como etapa de preparação, antes do início das tarefas, e **não entra nas métricas** de tempo e erros. Entre uma sessão e outra, o marcador do participante anterior foi apagado.
- As sessões foram marcadas em horário de movimento aéreo, porque os dados do sistema são em tempo real.


### Instrumentos utilizados

| Instrumento | Finalidade | Onde fica |
|---|---|---|
| **TCLE** | Consentimento do participante, assinado antes da sessão | Entregue ao professor pelo Classroom; **não é publicado neste repositório** |
| **Questionário de caracterização** | Perfil do participante antes das tarefas | Google Forms |
| **Sessão por videochamada** | Realização das tarefas, com compartilhamento e gravação da tela | Google Meet |
| **Questionário pós-teste** | UEQ e 5 perguntas abertas sobre a experiência | Google Forms |
| **Registro da sessão** | Tempo, resultado e erros por tarefa, anotados pela equipe | Planilha da equipe |
| **Evidências** | Fotos dos participantes, com rostos desfocados ou ocultos | Pasta `imagens/` |

Em vez do Maze, a equipe usou o Google Meet e o Google Forms, com autorização do professor.

**Questionário pós-teste, perguntas abertas:**
| # | Pergunta |
|---|---|
| 1 | Como foi a sua experiência geral ao usar o site? |
| 2 | O que você achou mais fácil ou agradável de fazer? |
| 3 | O que foi mais difícil ou confuso? Em qual atividade? |
| 4 | Algum termo, sigla ou informação do site você não entendeu? Qual? |
| 5 | O que você mudaria ou sugeriria para melhorar o site? |

*O planejamento do teste de usabilidade foi estruturado para avaliar a interação dos participantes com o Flightradar24, considerando suas diferentes experiências e familiaridade com plataformas de monitoramento de voos. As tarefas e os questionários foram definidos com o objetivo de identificar possíveis dificuldades de navegação, problemas de compreensão das informações apresentadas e aspectos positivos da interface. Por meio das perguntas abertas, a equipe buscou compreender a percepção dos usuários, identificar oportunidades de melhoria e complementar os resultados obtidos durante a execução das atividades. A adequação do planejamento seria verificada por meio do teste piloto, antes da aplicação oficial.*

---

## 2. Teste Piloto

O teste piloto foi realizado no dia 23/10/2026, com um participante externo à equipe, identificado pelo código PP, com o objetivo de verificar a adequação dos procedimentos planejados para a avaliação de usabilidade do Flightradar24.

Durante a sessão, foram previstos os mesmos procedimentos das avaliações oficiais, incluindo a apresentação do Termo de Consentimento Livre e Esclarecido (TCLE), o questionário de caracterização, a execução das tarefas e o questionário pós-teste.

### Ajustes realizados

Durante o teste piloto, foram verificadas a clareza das instruções, a compreensão das tarefas e o funcionamento dos recursos utilizados na avaliação. Não foram identificados problemas que exigissem alterações no planejamento inicial. Dessa forma, as tarefas e os instrumentos foram mantidos para as sessões oficiais.

![Participante do piloto realizando o teste](https://github.com/mthsrp10-dev/TP1-IHC/blob/main/01-avaliacao-usabilidade/imagens/teste-piloto2.png?raw=true)

*Figura 1 — Participante do piloto durante a realização do teste.*

**Considerações sobre o Teste Piloto**

A realização do teste piloto permitiu verificar a adequação dos procedimentos estabelecidos para a avaliação de usabilidade do Flightradar24. Como não foram identificadas dificuldades que exigissem alterações nas tarefas ou nos instrumentos utilizados, o planejamento inicial foi mantido. Dessa forma, o teste piloto contribuiu para a preparação da equipe e para a continuidade das avaliações com os participantes oficiais, garantindo maior organização e consistência na aplicação dos procedimentos.

---

## 3. Execução

As sessões do Teste de Usabilidade do Flightradar24 foram realizadas no dia 24/10/2026, no período das 00h às 15h, com participantes externos à equipe, residentes na região de Itacoatiara-AM, com idades variadas.

As avaliações foram realizadas utilizando computadores dos próprios participantes, com acesso à internet e diferentes navegadores. Durante as sessões, foram observadas algumas limitações técnicas relacionadas ao desempenho dos equipamentos e à estabilidade da conexão, fatores que podem ter influenciado o tempo de execução das tarefas.

### Perfil dos participantes

Respostas do questionário de caracterização, aplicado antes das tarefas.

| Participante | Faixa etária | Relação com a equipe | Experiência com tecnologia | Experiência com aviação | Cidade no momento do teste |
|---|---|---|---|---|---|
| P01 | 18–24 | Externo | Alta | Nenhuma | Itacoatiara |
| P02 | Menor de 18 | Externo | Alta | Nenhuma | Itacoatiara |
| P03 | 18–24 | Externo | Sim | Nenhuma | Itacoatiara |
| P04 | 18–24 | Amigo | Média | Nenhuma | Itacoatiara |
| P05 | 18–24 | Conhecido | Média | Nenhuma | Itacoatiara |
| P06 | 25–32 | Externo | Básica a média | Nenhuma | Itacoatiara |
| P07 | Menor de 18 | Externo | Básica | Nenhuma | Itacoatiara |
| P08 | 18–24 | Amigo | Básica | Nenhuma | Itacoatiara |

*Tabela 1 — Perfil dos participantes do teste.*

A análise do perfil dos participantes demonstra que a maioria possui idade entre 18 e 24 anos, sendo todos residentes em Itacoatiara-AM e externos à equipe responsável pela avaliação. Os participantes apresentaram diferentes níveis de familiaridade com a tecnologia, variando entre conhecimentos básicos e avançados. Entretanto, todos relataram não possuir experiência prévia com aviação. Essa diversidade de conhecimentos tecnológicos permitiu observar a interação de usuários com diferentes níveis de habilidade, contribuindo para a identificação de possíveis dificuldades de navegação e compreensão das funcionalidades do Flightradar24.

### Evidências

![Participante P01 realizando o teste](https://github.com/mthsrp10-dev/TP1-IHC/blob/main/01-avaliacao-usabilidade/imagens/teste-p01.png?raw=true)

*Figura 2 — Participante P01 durante a realização do teste.*

![Participante P02 realizando o teste](https://github.com/mthsrp10-dev/TP1-IHC/blob/main/01-avaliacao-usabilidade/imagens/teste-p02.png?raw=true)
*Figura 3 — Participante P02 durante a realização do teste.*

![Participante P03 realizando o teste](https://github.com/mthsrp10-dev/TP1-IHC/blob/main/01-avaliacao-usabilidade/imagens/teste-p03.png?raw=true)
*Figura 4 — Participante P03 durante a realização do teste.*

![Participante P04 realizando o teste](https://github.com/mthsrp10-dev/TP1-IHC/blob/main/01-avaliacao-usabilidade/imagens/teste-p04.png?raw=true)
*Figura 5 — Participante P04 durante a realização do teste.*

![Participante P05 realizando o teste](https://github.com/mthsrp10-dev/TP1-IHC/blob/main/01-avaliacao-usabilidade/imagens/teste-p05.png?raw=true)
*Figura 6 — Participante P05 durante a realização do teste.*

![Participante P06 realizando o teste](https://github.com/mthsrp10-dev/TP1-IHC/blob/main/01-avaliacao-usabilidade/imagens/teste-p06.png?raw=true)
*Figura 7 — Participante P06 durante a realização do teste.*

![Participante P07 realizando o teste](https://github.com/mthsrp10-dev/TP1-IHC/blob/main/01-avaliacao-usabilidade/imagens/teste-p07.png?raw=true)
*Figura 8 — Participante P07 durante a realização do teste.*

![Participante P08 realizando o teste](https://github.com/mthsrp10-dev/TP1-IHC/blob/main/01-avaliacao-usabilidade/imagens/teste-p08.png?raw=true)
*Figura 9 — Participante P08 durante a realização do teste.*




*As evidências registradas durante as sessões demonstram a realização das atividades propostas pelos participantes, permitindo documentar o processo de avaliação de usabilidade do Flightradar24. Os registros fotográficos complementam as informações coletadas durante os testes e contribuem para a transparência e a organização da documentação. Para preservar a privacidade dos participantes, suas identidades foram ocultadas nas imagens apresentadas.*

---

## 4. Análise dos Resultados



Todas as sessões seguiram o mesmo procedimento previamente estabelecido, incluindo a apresentação do Termo de Consentimento Livre e Esclarecido (TCLE), a aplicação do questionário de caracterização, a execução das tarefas propostas e, por fim, o preenchimento do questionário pós-teste. A equipe acompanhou as atividades sem interferir diretamente na interação dos participantes com o sistema, buscando preservar a autenticidade dos resultados obtidos.

### Resultados por participante

Uma tabela para cada participante, com os dados anotados na sessão.

**Participante P01**

| Tarefa | Tempo (s) | Resultado | Erros | Observações |
|---|---|---|---|---|
| T1 — Mapa e detalhes do voo | 11 segundos | ✓ | 0 | O participante concluiu a tarefa com êxito, sem demonstrar dificuldades. |
| T2 — Detalhes do voo | 17 segundos | ✓ | 0 | Concluiu devidamente, sem ter quaisquer problemas. |
| T3 — Chegadas de um aeroporto | 22 segundos | ✓ | 0 | Concluiu com êxito, sem dificuldades. |
| T4 — Localizar um voo | 36 segundos | ✓ | 0 | O participante entendeu a tarefa e a concluiu sem dificuldades. |
| T5 — Horário e status do voo | 36 | ✓ | 0 | O participante não encontrou dificuldades ao realizar a tarefa. |
| T6 — Rota percorrida | 38 | ✓ | 0 | O participante concluiu sem dificuldades. |
| T7 — Filtrar por companhia | 32 segundos | ✓ | 0 | O participante compreendeu e concluiu a tarefa com êxito |
| T8 — Marcar e reencontrar um voo | 71 segundos | ✗ | 3 | O participante não concluiu a tarefa devido a um impedimento do próprio sistema. |

*Legenda: ✓ sucesso · ! com dificuldade · ✗ insucesso.*


**Participante P02**

| Tarefa | Tempo (s) | Resultado | Erros | Observações |
|---|---|---|---|---|
| T1 — Mapa e detalhes do voo | 18 | ✓ | 0 | O participante concluiu sem dificuldades, procurando o detalhe do voo |
| T2 — Detalhes do voo | 57 |  !  | 1 | O participante não consegui-o encontrar a altitude do voo |
| T3 — Chegadas de um aeroporto | 54 | ✓  | 0 | O participante encontrou com facilidade a chegada do voo |
| T4 — Localizar um voo | 59 |  ! | 1 | O participante soube localizar o voo |
| T5 — Horário e status do voo | 30 | ✓ | 0 | O participante teve facilidade de encontrar  |
| T6 — Rota percorrida | 20 | ✓ | 0 | Não teve dificuldade de encontrar o voo |
| T7 — Filtrar por companhia | 50 | ✓ | 0 | Consegui-o colocar a companhia de sua preferência |
| T8 — Marcar e reencontrar um voo | 88 |  ✗ | 2 | Não teve sucesso na procura |

*Legenda: ✓ sucesso · ! com dificuldade · ✗ insucesso.*


**Participante P03**

| Tarefa | Tempo (s) | Resultado | Erros | Observações |
|---|---|---|---|---|
| T1 — Mapa e detalhes do voo | 55 segundos | ! | 1 | A participante concluiu a tarefa com dificuldades por causa do alto travamento do site. |
| T2 — Detalhes do voo | 63 segundos | ! | 2 | Concluiu com dificuldades, por conta do alto travamento do site e de anúncios aparecendo repentinamente na tela. |
| T3 — Chegadas de um aeroporto | 128 segundos | ✓ | 0 | Concluiu com êxito, sem dificuldades.  |
| T4 — Localizar um voo | 57 segundos | ! | 1 | A participante concluiu a tarefa com uma dificuldade, ao apertar em um espaço vazio e sair da tela que estava fazendo a tarefa. |
| T5 — Horário e status do voo | 57 segundos | ! | 1 | A participante concluiu a tarefa com dificuldades, tendo problemas para executar a tarefa por quanta da quantidade de espaços vazios. |
| T6 — Rota percorrida | 105 segundos | ✗ | 2 | A participante não conseguiu concluir a tarefa, não achando a opção de visualizar o trajeto do voo. |
| T7 — Filtrar por companhia | 85 segundos | ! | 1 | A participante não achou a opção de filtrar os voos no mapa, apenas em uma área específica, assim concluindo a tarefa do jeito que ela bem entendeu. |
| T8 — Marcar e reencontrar um voo | 120 segundos | ✗ | 3 | A participante não conseguiu concluir a tarefa, desistindo dela no meio do progresso. |


*Legenda: ✓ sucesso · ! com dificuldade · ✗ insucesso.*


**Participante P04**

| Tarefa | Tempo (s) | Resultado | Erros | Observações |
|---|---|---|---|---|
| T1 — Mapa e detalhes do voo | 45 |  !  | 1 | teve dificuldade para encontrar  |
| T2 — Detalhes do voo | 71 | ✓ | 0 | Teve duvida pois não compreendia o site mais teve êxito na sua procura |
| T3 — Chegadas de um aeroporto | 90 | !  | 1 | Teve dificuldade de acahar |
| T4 — Localizar um voo |  35 | ✓  | 0 | teve êxito |
| T5 — Horário e status do voo | 48 |  ! | 1 | Não consegui-o achar o voo |
| T6 — Rota percorrida | 45 | ✓  | 0 | Teve êxito na sua procura |
| T7 — Filtrar por companhia | 40 |  ✗ | 2 | Desistiu por duvida  |
| T8 — Marcar e reencontrar um voo | 77 |  ✗ | 2 | Não consegui-o guardar e procurar novamente] |

 
*Legenda: ✓ sucesso · ! com dificuldade · ✗ insucesso.*


**Participante P05**

| Tarefa | Tempo (s) | Resultado | Erros | Observações |
|---|---|---|---|---|
| T1 — Mapa e detalhes do voo | 30 segundos | ! | 2 | Concluiu com algumas dificuldades, principalmente por conta dos anúncios. |
| T2 — Detalhes do voo | 44 segundos | ! | 1 | Concluiu com dificuldades, principalmente ao ler os valores da velocidade e altitude |
| T3 — Chegadas de um aeroporto | 52 segundos | ✗ | 3 | Não concluiu a tarefa devidamente, a participante não conseguiu localizar voos indo para Manaus no dia de hoje |
| T4 — Localizar um voo | 48 segundos | ✓ | 0 | A participante concluiu sem dificuldades, procurando diretamente na barra de pesquisa e encontrando o avião |
| T5 — Horário e status do voo | 48 segundos | ✓ | 0 | A participante concluiu sem dificuldades,verificando os status gerais do voo. |
| T6 — Rota percorrida | 31 segundos | ✓ | 0 | A participante concluiu a tarefa com êxito |
| T7 — Filtrar por companhia | 52 segundos | ✗ | 2 | A participante não consegue encontrar a opção de filtrar apenas companhias aéreas específicas, e desiste da tarefa no meio do trajeto |
| T8 — Marcar e reencontrar um voo | 42 segundos | ! | 1 | A participante não encontrou a opção para guardar o avião, e concluiu a tarefa da maneira que achou melhor.|


*Legenda: ✓ sucesso · ! com dificuldade · ✗ insucesso.*


**Participante P06**

| Tarefa | Tempo (s) | Resultado | Erros | Observações |
|---|---|---|---|---|
| T1 — Mapa e detalhes do voo | 47  | ✓  | 0  | Teve êxito na procura |
| T2 — Detalhes do voo | 60 |  !  | 1 |Teve duvida pela informação fornecida  |
| T3 — Chegadas de um aeroporto | 67 |  ✗ |  1 | Não consegui achar a forma correta de procura de voo para Manaus  |
| T4 — Localizar um voo | 45 | ✓ |  0 | Teve facilidade |
| T5 — Horário e status do voo | 93 | ✓  | 0 | Demorou para Achar mais conseguio encontrar |
| T6 — Rota percorrida | 60 | ✓  |  0 | Consegui-o encontrar com facilidade |
| T7 — Filtrar por companhia | 80 |  !  |  1 | Não consegui-o filtra certo  |
| T8 — Marcar e reencontrar um voo | 47 |  ✗ | 2 | Não fez de forma correta  |

*Legenda: ✓ sucesso · ! com dificuldade · ✗ insucesso.*


**Participante P07**

| Tarefa | Tempo (s) | Resultado | Erros | Observações |
|---|---|---|---|---|
| T1 — Mapa e detalhes do voo | 14 |  ✗  | 1 | Não consegui-o dizer o detalhe do voo  |
| T2 — Detalhes do voo | 48 |  !  | 1 | Teve muita dificuldade para encontrar  |
| T3 — Chegadas de um aeroporto | 25 | ✗ | 2 | Não teve êxito na procura  |
| T4 — Localizar um voo | 21 | ✓  | 0 | Não teve muita dificuldade para encontrar |
| T5 — Horário e status do voo | 185 | ✓ | 0 | Demorou mais consegui-o achar  |
| T6 — Rota percorrida | 14 | ✓  |  0 | Não teve muita dificuldade para encontrar |
| T7 — Filtrar por companhia | 41 |  ✗ | 2 | Por não ter familiaridade com a plataforma ele desistiu|
| T8 — Marcar e reencontrar um voo | 16 | ✗ | 2 | Não consegui-o encontrar a forma de guardar e reencontrar o voo |

*Legenda: ✓ sucesso · ! com dificuldade · ✗ insucesso.*


**Participante P08**

| Tarefa | Tempo (s) | Resultado | Erros | Observações |
|---|---|---|---|---|
| T1 — Mapa e detalhes do voo | 44 segundos | ! | 1 | A participante concluiu a tarefa com dificuldades por causa de anúncios, e também por encontrar um voo sem destino. |
| T2 — Detalhes do voo | 134 segundos | ✗ | 3 | A participante não conseguiu concluir a tarefa, e desistiu no meio do progresso. |
| T3 — Chegadas de um aeroporto | 128 segundos | ✓ | 0 | Concluiu com êxito, sem dificuldades.  |
| T4 — Localizar um voo | 188 segundos | ! | 3 | A participante concluiu a tarefa com várias dificuldades, navegando por várias opções para descobrir o objetivo. |
| T5 — Horário e status do voo | 188 segundos | ! | 3 | A participante concluiu a tarefa com várias dificuldades, encontrando muitas opções e em dúvida de como alcançar o objetivo, mas conseguiu concluir. |
| T6 — Rota percorrida | 149 segundos | ✓ | 0 | A participante concluiu a tarefa com êxito, apesar da demora para achar o voo. |
| T7 — Filtrar por companhia | 251 segundos | ! | 2 | A participante navegou por várias opções, encontrando dificuldade ao realizar a tarefa, mas conseguiu a concluir com sucesso. |
| T8 — Marcar e reencontrar um voo | 134 segundos | ✗ | 3 | A participante não conseguiu concluir a tarefa, concluindo a tarefa do jeito que ela bem entendeu. |

*Legenda: ✓ sucesso · ! com dificuldade · ✗ insucesso.*

*[Repetir a tabela para P02 a P08 e explicar brevemente o que ela mostra.]*

### Resumo por participante

| Participante | Sucesso ✓ | Com dificuldade ! | Insucesso ✗ | Tempo total (s) | Total de erros |
|---|---|---|---|---|---|
| P01 | [ ] | [ ] | [ ] | [ ] | [ ] |
| P02 | [ ] | [ ] | [ ] | [ ] | [ ] |

*[Explicar o que a tabela mostra e quais participantes tiveram mais dificuldade.]*

### Consolidação por tarefa

| Tarefa | TSR — Taxa de sucesso (%) | TTR — Tempo médio da tarefa (s) |
|---|---|---|
| T1 — Mapa e detalhes do voo | [ ] | [ ] |
| T2 — Detalhes do voo | [ ] | [ ] |
| T3 — Chegadas de um aeroporto | [ ] | [ ] |
| T4 — Localizar um voo | [ ] | [ ] |
| T5 — Horário e status do voo | [ ] | [ ] |
| T7 — Rota percorrida | [ ] | [ ] |
| T6 — Filtrar por companhia | [ ] | [ ] |
| T8 — Marcar e reencontrar um voo | [ ] | [ ] |

*[Explicar como a TSR foi calculada (participantes com sucesso divididos pelo total, vezes 100) e se o resultado "com dificuldade" foi ou não contado como sucesso. Explicar também como o tempo médio foi calculado, e quais tarefas foram as mais difíceis.]*

### Respostas abertas e fatores de usabilidade

Esta seção reúne as respostas das cinco perguntas abertas do questionário pós-teste, no texto original, e liga cada uma a um fator de usabilidade. Como o enunciado não define os fatores, a equipe adotou os da ISO 9241-11 e de Nielsen (eficácia, eficiência, facilidade de aprendizado e satisfação) e acrescentou dois que apareceram com força nas respostas: **compreensão** (idioma e termos técnicos) e **organização da interface** (excesso de informações). Uma mesma resposta pode tratar de mais de um fator.

**Legenda das perguntas:** 1 — experiência geral · 2 — o que foi mais fácil ou agradável · 3 — o que foi mais difícil ou confuso · 4 — termo, sigla ou informação que não entendeu · 5 — o que mudaria ou sugeriria.

A tabela traz as respostas mais representativas. Trechos longos foram abreviados com [...], e a grafia original foi mantida.

| Participante | Pergunta | Resposta () || Fator de usabilidade |
|---|---|---|---|---|
| P01 | 1 | "Intermediária" | | Satisfação |
| P02 | 1 | "bem travadinho, achei cheio de informações também" || Eficiência (desempenho); organização da interface |
| P04 | 1 | "Muito difícil" | | Facilidade de aprendizado |
| P05 | 1 | "Confusa,site em inglês desafia o entendimento" || Compreensão (idioma) |
| P06 | 1 | "Daria nota 6, ele poderia ser mais intuitivo, ter uma janela que desse opções ao clicar em cada avião, mas de forma mais objetiva. Há a limitação de idioma que pode ser consertada usando o navegador, [...]" | | Satisfação; facilidade de aprendizado; compreensão (idioma) |
| P07 | 1 | "boa porém um pouco complicada" || Satisfação; facilidade de aprendizado |
| P08 | 1 | "O site é bem interessante, porém, devido a grande quantidade de informações, sua utilização acaba se tornando confusa" || Satisfação; organização da interface |
| P03 | 2 | "Pesquisar os vôos" || Facilidade de aprendizado |
| P04 | 2 | "Clicar nos aviões e ver de onde vieram e pra onde iam" || Facilidade de aprendizado |
| P06 | 2 | "O que pareceu mais fácil foi saber de onde o avião saiu" || Facilidade de aprendizado |
| P08 | 2 | "Buscar voos específicos através do seu número na barra de pesquisa" | | Facilidade de aprendizado |
| P01 | 3 | "Ver os avião que estão chegando em Manaus" | | Eficácia |
| P02 | 3 | "achar em qual altitude e velocidade o avião selecionado estava" | | Eficácia |
| P03 | 3 | "Saber em quais lugares o avião já passou" || Eficácia |
| P04 | 3 | "Em geral, tinha sempre uma dificuldade em cada atividade, visto que o site tinha muita coisa e estava em inglês" || Eficácia; organização da interface; compreensão (idioma) |
| P05 | 3 | "Pesquisar a companhia aérea" || Eficácia |
| P06 | 3 | "Saber quais aviões vem e vão de cada aeroporto" || Eficácia |
| P07 | 3 | "guardar o voo" | | Eficácia |
| P08 | 3 | "Buscar informações como altitude e velocidade, identificar uma companhia área em específico" || Eficácia |
| P05 | 4 | "Vários.ex : scheduled,barômetro alt,ground speed" || Compreensão (termos técnicos e idioma) |
| P06 | 4 | "Estar em inglês atrapalhou um pouco, no geral a parte de termos foi até mais tranquilo." || Compreensão (idioma) |
| P08 | 4 | "O site apresenta alguns termos técnicos relacionados à aviação que dificultam a compreensão. Nao lembro de um termo específico." || Compreensão (termos técnicos) |
| P01 | 5 | "Menos poluição com pop-ups" || Organização da interface |
| P04 | 5 | "[...] acho que tiraria o tanto de coisa que tem na interface do site, além de colocar melhor a distribuição de controles para o usuário poder ter uma melhor navegação nele [...]" | | Organização da interface |
| P05 | 5 | "Site em pt-br" || Compreensão (idioma) |
| P06 | 5 | "opção para outros idiomas, ter uma busca mais sensível, deixar opções mais buscadas de forma mais exposta." || Compreensão (idioma); eficiência |
| P07 | 5 | "um tutorial de como navegar pelo site sem dificuldades" || Facilidade de aprendizado |
| P08 | 5 | "[...] Sugiro tornar a organização mais simples, que permita ocultar informações que nao necessárias ou de interesse pessoal. Também sugiro que deixe uma linguagem mais simples e acessível para todos os públicos." || Organização da interface; compreensão |

*[Explicar o que a tabela apresenta e destacar os fatores que mais apareceram. A análise qualitativa completa, com os códigos e as redes do ATLAS.ti, está em [experiencia-de-uso.md](../02-avaliacao-ux/experiencia-de-uso.md).]*

### Considerações sobre o Teste de Usabilidade

*principais achados, tarefas mais problemáticas, o que isso indica sobre a usabilidade do Flightradar24 e limitações do teste, como a conta compartilhada de teste, as sessões por videochamada e os dados em tempo real.]*

---

**Navegação:** [Voltar ao README](../README.md) - [Inspeção](1-inspecao.md) 
