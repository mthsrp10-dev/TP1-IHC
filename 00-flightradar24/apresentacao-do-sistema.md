# Apresentação do Sistema — Flightradar24

> 

Antes de iniciar as avaliações de usabilidade, experiência de uso, acessibilidade e comunicabilidade, esta seção apresenta o sistema escolhido pela equipe: o que é, para que serve, quem o utiliza e quais partes dele foram avaliadas. A intenção é dar o contexto necessário para entender as decisões tomadas nas etapas seguintes.

![Tela principal do Flightradar24](https://passageirodeprimeira.com/wp-content/uploads/2019/01/flightradarcover.png)

*Figura 1 — Tela principal do Flightradar24 na versão web, com o mapa de aeronaves em tempo real.*

---

## 1. Qual sistema será avaliado?

O sistema avaliado é o **Flightradar24**, um serviço de rastreamento de voos em tempo real. Ele mostra, sobre um mapa, a posição das aeronaves em voo e permite consultar informações de cada voo, como origem, destino, altitude, velocidade e tipo de aeronave. Também oferece informações de aeroportos, como chegadas e partidas.

| Item | Informação |
|---|---|
| **Nome** | Flightradar24 |
| **Desenvolvedor** | Flightradar24 AB |
| **Plataformas existentes** | Web, Android e iOS |
| **Plataforma avaliada** | **Versão web**, no navegador do computador |
| **Versão do sistema** | Gratuita |
| **Idioma da interface** | Originalmente em inglês, com possibilidade de tradução automática para o português, dependendo do navegador e de suas configurações. |
| **Link** | [https://www.flightradar24.com](https://www.flightradar24.com) |
| **Período de avaliação** | 24/10/2026 |
| **Navegador utilizado** | Diferentes navegadores web, conforme a preferência e disponibilidade de cada participante. |

## 2. Qual é o domínio do sistema?

O sistema pertence ao domínio de **transporte aéreo e informação em tempo real**. Também tem uso em **entretenimento e curiosidade** (observar o tráfego aéreo) e no **acompanhamento de viagens** (saber onde está o voo de um parente ou conhecido).

## 3. Qual é a finalidade do sistema?

O Flightradar24 permite que qualquer pessoa **acompanhe voos ao vivo** em um mapa mundial e consulte informações sobre aeronaves, rotas e aeroportos. Na prática, o sistema permite ao usuário:

- ver onde um avião está agora e para onde está indo;
- consultar dados de um voo específico, como altitude, velocidade, aeronave e horários;
- acompanhar chegadas e partidas de um aeroporto;
- filtrar as aeronaves exibidas no mapa;
- guardar voos de interesse para acompanhar depois.

## 4. Quem são os principais usuários do sistema?

O sistema é voltado a um público amplo e diverso. O uso básico não exige conhecimento técnico prévio de aviação, embora o conteúdo traga vocabulário específico da área, como siglas de aeroportos e unidades de altitude e velocidade.

| Perfil | Como usa o sistema |
|---|---|
| **Passageiros e familiares** | Acompanham o voo de alguém que está viajando ou que vão buscar no aeroporto |
| **Entusiastas de aviação** | Observam o tráfego aéreo, tipos de aeronave e rotas |
| **Curiosos** | Identificam o avião que viram passar no céu |
| **Profissionais da área** | Consultam informações de voos e aeroportos [confirmar se pertinente] |

> Participantes das avaliações: Os participantes são usuários externos à equipe, com idades variadas, residentes na região de Itacoatiara-AM. Todos possuem acesso à internet por meio de computadores e dispositivos móveis, apresentando pouca ou nenhuma experiência com viagens aéreas. Para preservar a identidade dos participantes, foram utilizados códigos de identificação (P01, P02 e assim sucessivamente) durante o registro e a análise dos resultados.

## 5. Quais são as principais funcionalidades do sistema?

| Funcionalidade | Descrição |
|---|---|
| **Mapa em tempo real** | Exibe as aeronaves em voo, com movimentação ao vivo |
| **Busca** | Localiza voos, aeronaves e aeroportos |
| **Detalhes do voo** | Mostra rota, altitude, velocidade, aeronave e horários |
| **Trajetória** | Mostra por onde o avião já passou desde que decolou |
| **Informações de aeroporto** | Lista chegadas e partidas |
| **Filtros** | Restringe as aeronaves exibidas no mapa, por exemplo por companhia aérea |
| **Marcadores (favoritos)** | Permite guardar voos para acompanhar depois, mediante uma conta gratuita |
| **Configurações de visualização** | Permitem alterar, por exemplo, o estilo do mapa e as unidades de medida  |
| **Planos pagos** | Oferecem recursos adicionais, como mais histórico de voos e camadas de clima |

## 6. Qual será o escopo da avaliação?

O Flightradar24 possui muitas funcionalidades, e nem todas foram avaliadas. Para que as quatro avaliações (usabilidade, experiência de uso, acessibilidade e comunicabilidade) tratem das mesmas partes do sistema, a equipe definiu o recorte abaixo.

| Dentro do escopo | Fora do escopo |
|---|---|
| **Versão web gratuita** do Flightradar24 | Aplicativos para celular (Android e iOS) |
| Mapa de aeronaves em tempo real | Planos pagos (assinaturas) |
| Busca de voos e de aeroportos | Modo de realidade aumentada (câmera do celular) |
| Detalhes do voo (rota, altitude, velocidade, aeronave, horários) | Alertas e notificações |
| Chegadas e partidas de um aeroporto | Clima, histórico de voos e recursos avançados |
| Filtros e trajetória do voo | Criação de conta pelos participantes |
| Marcadores, com uma **conta gratuita criada pela equipe** apenas para as sessões | Anúncios (apenas observados, sem tarefas sobre eles) |
| Configurações de visualização, quando acessíveis sem conta | |

**Justificativa do recorte:**

- A **versão web** foi escolhida para que todas as avaliações usem a mesma plataforma e porque ela permite aplicar com mais precisão os testes de acessibilidade (leitor de tela, navegação pelo teclado e verificação de contraste).
- A **versão gratuita** garante que todos os participantes tenham a mesma experiência.
- O **modo de realidade aumentada** existe apenas no celular e depende dos sensores do aparelho e da presença de aeronaves acima do usuário, o que impede padronizar as sessões.
- Os marcadores exigem **uma conta**, então a equipe criou uma conta de teste, sem dados pessoais, para que os participantes não precisassem se cadastrar. O login foi tratado como etapa de preparação e **não entra nas métricas** de tempo e erros.
- Os dados do sistema mudam a todo momento. Por isso, as tarefas foram escritas de forma genérica, sem depender de um voo específico estar no ar.

**Como o escopo se aplica a cada avaliação:**

| Avaliação | Arquivo | Como o escopo é usado |
|---|---|---|
| Inspeção de usabilidade | [1-inspecao.md](../01-avaliacao-usabilidade/1-inspecao.md) | Exploração livre das telas e funcionalidades dentro do escopo |
| Teste de usabilidade | [2-teste.md](../01-avaliacao-usabilidade/2-teste.md) | Oito tarefas baseadas nas funcionalidades do escopo |
| Experiência de uso | [experiencia-de-uso.md](../02-avaliacao-ux/experiencia-de-uso.md) | UEQ e perguntas abertas aplicadas aos participantes do teste |
| Acessibilidade | [inspecao-de-acessibilidade.md](../03-avaliacao-acessibilidade/inspecao-de-acessibilidade.md) | Telas selecionadas dentro do escopo, avaliadas com a WCAG 2.2 |
| Comunicabilidade | [mac.md](../04-avaliacao-comunicabilidade/mac.md) | Dez tarefas de interpretação de mensagens e informações do sistema |

**Limitações conhecidas:**

- Os participantes realizaram as sessões em **Itacoatiara-AM**, e algumas tarefas usam o aeroporto de Manaus como cenário, por ser um contexto regional conhecido. (Todos os participantes conhecem o mesmo).
- Variação das informações em tempo real: Considerando que o Flightradar24 apresenta informações atualizadas em tempo real, os resultados podem variar entre as sessões. As avaliações foram realizadas no dia 24 de novembro de 2026, no período das 00h às 15h, estando sujeitas às alterações naturais dos dados apresentados pelo sistema.
- Limitações técnicas: Durante as sessões, foram identificadas limitações relacionadas principalmente ao desempenho dos equipamentos utilizados pelos participantes e à qualidade da conexão com a internet. Esses fatores podem ter influenciado o tempo de resposta do sistema e a fluidez da interação, afetando potencialmente o desempenho dos usuários durante a execução das tarefas.

---

## Considerações

O Flightradar24 foi escolhido porque o sistema é interessante para as quatro avaliações, por que pode ser considerado um sistema não convencional, porque é viável para o teste com usuários e para a inspeção de acessibilidade. Com o sistema e o escopo apresentados, as próximas seções documentam as avaliações realizadas: inspeção e teste de usabilidade, avaliação de experiência de uso, inspeção de acessibilidade e avaliação de comunicabilidade.

**Navegação:** [Voltar ao README](../README.md) · [Avaliação de usabilidade](../01-avaliacao-usabilidade/1-inspecao.md)
