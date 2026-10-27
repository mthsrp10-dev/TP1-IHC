# Avaliação de Acessibilidade

A avaliação de acessibilidade do **Flightradar24** foi realizada com o objetivo de identificar possíveis barreiras que possam dificultar ou impedir a utilização do sistema por pessoas com diferentes necessidades de acessibilidade.

A inspeção teve como referência as **Diretrizes de Acessibilidade para Conteúdo Web (WCAG 2.2)**, utilizando ferramentas de avaliação automatizada e verificações manuais.

Foram utilizadas as ferramentas **WAVE Evaluation Tool**, **Google Lighthouse (PageSpeed Insights)** e **Accessibility Insights for Web**, além de um teste manual de navegação por teclado. As análises foram realizadas em 26 de outubro de 2026. Este documento apresenta o escopo, o processo seguido pela equipe, os problemas encontrados, os critérios da WCAG 2.2 relacionados e uma discussão final dos resultados.

---

## Escopo da avaliação

Foi selecionada para inspeção a interface web do Flightradar24, com foco na página principal de monitoramento de voos em tempo real.

A avaliação considerou os seguintes elementos e aspectos da interface:

| Elemento ou aspecto | O que foi verificado |
|---|---|
| **Mapa interativo** | Controles de zoom e navegação pelo mapa |
| **Menus e botões** | Identificação acessível e possibilidade de interação |
| **Campos de formulário** | Presença de rótulos e identificação dos campos |
| **Imagens e ícones** | Disponibilidade de textos alternativos |
| **Contraste de cores** | Legibilidade dos elementos visuais |
| **Navegação por teclado** | Acesso às funcionalidades, ordem de navegação e visibilidade do foco |
| **Estrutura da página** | Organização dos elementos e utilização de atributos de acessibilidade |

O objetivo foi identificar possíveis dificuldades relacionadas à percepção, compreensão e operação da interface.

## Processo utilizado

A inspeção foi organizada em três etapas: **detecção, coleção e discriminação**.

### 1. Detecção

Na etapa de detecção, foram utilizadas ferramentas automatizadas para identificar possíveis problemas de acessibilidade na interface do Flightradar24, complementadas por uma verificação manual.

**WAVE Evaluation Tool**

A ferramenta WAVE foi utilizada para verificar a presença de problemas relacionados a textos alternativos, identificação de elementos interativos, contraste de cores e estrutura da página. A análise apresentou os seguintes resultados:

| Indicador | Resultado |
|---|---:|
| Erros de acessibilidade | 21 |
| Erros de contraste | 3 |
| Alertas | 19 |
| Recursos de acessibilidade | 28 |
| Elementos de estrutura | 23 |
| Elementos ARIA | 68 |
| Pontuação AIM | 6,3/10 |

![Resultado da análise do WAVE](https://github.com/mthsrp10-dev/TP1-IHC/blob/main/03-avaliacao-acessibilidade/imagens/wave1.jpeg?raw=true)

Figura 1 — Resultado da análise do WAVE. 

**Google Lighthouse (PageSpeed Insights)**

O Lighthouse foi utilizado para complementar a avaliação automatizada, verificando diferentes aspectos de qualidade da página, com destaque para a acessibilidade.

| Categoria | Pontuação |
|---|---:|
| Desempenho | 35/100 |
| Acessibilidade | 88/100 |
| Boas práticas | 54/100 |
| SEO | 85/100 |

A avaliação de acessibilidade identificou problemas relacionados a rótulos de formulários, nomes acessíveis de links e contraste insuficiente entre elementos visuais.

![Resultado da análise do Lighthouse](https://github.com/mthsrp10-dev/TP1-IHC/blob/main/03-avaliacao-acessibilidade/imagens/farol.jpeg?raw=true)

Figura 2 — Resultado da análise do Lighthouse. 

**Accessibility Insights for Web**

A ferramenta Accessibility Insights for Web (versão 2.49.0, com axe-core 4.11.3) foi utilizada por meio do recurso FastPass para auxiliar na identificação de problemas de acessibilidade e na verificação da navegação por teclado.

O relatório apresentou quatro falhas automatizadas, incluindo problemas de contraste, identificação de links e acessibilidade de região de rolagem. O recurso Tab stops também sinalizou 42 elementos que necessitavam de verificação quanto à possibilidade de acesso pelo teclado. O relatório marca esses elementos como "detectados automaticamente, precisam de revisão".

![Resultado do FastPass do Accessibility Insights](https://github.com/mthsrp10-dev/TP1-IHC/blob/main/03-avaliacao-acessibilidade/imagens/telafl24.png?raw=true)

Figura 3 — Resultado do FastPass do Accessibility Insights. 

**Teste manual de navegação por teclado**

Foi realizada uma verificação manual do controle de zoom do mapa, utilizando as teclas Tab, Enter e Shift + Tab. Os resultados observados foram:

| Verificação | Resultado |
|---|---|
| Acesso ao controle com Tab | Sim |
| Indicador visual de foco perceptível | Não |
| Ativação do zoom com Enter | Não |
| Retorno com Shift + Tab | Sim |

O teste indicou possíveis dificuldades relacionadas à identificação visual do foco e à operação do controle de zoom. A ativação pela tecla Espaço ainda precisa ser verificada.

### 2. Coleção

Na etapa de coleção, os resultados obtidos pelas ferramentas foram reunidos para identificar problemas semelhantes e organizar os registros da avaliação.

Foram observadas correspondências entre os resultados do WAVE e do Lighthouse, principalmente em relação à ausência de identificação acessível em elementos interativos e ao contraste insuficiente.

Os resultados do Accessibility Insights e do teste manual foram considerados separadamente, permitindo complementar a análise automatizada com observações sobre a interação por teclado.

### 3. Discriminação

Na etapa de discriminação, os problemas identificados pelas ferramentas WAVE, Google Lighthouse e Accessibility Insights for Web foram analisados com o objetivo de diferenciar defeitos de possíveis falsos positivos e eliminar registros repetidos.

A análise identificou evidências consistentes de problemas relacionados ao contraste insuficiente e à ausência de nomes acessíveis em elementos interativos. O relatório do Accessibility Insights apontou dois elementos com relação de contraste aproximada de 2:1, inferior ao mínimo de 4,5:1 estabelecido pelo critério WCAG 2.2 — 1.4.3 (Contraste mínimo).

O teste manual de navegação por teclado também revelou ausência de indicador visual perceptível no controle de zoom do mapa. Embora o elemento pudesse ser alcançado pela tecla Tab e fosse possível retornar com Shift + Tab, a ativação por Enter não produziu o resultado esperado.

Outros problemas, como imagens sem texto alternativo, botões vazios e elementos sinalizados como não alcançáveis pelo teclado, foram mantidos como pendentes de confirmação, pois necessitam de verificações manuais adicionais. Os dois primeiros também constam como aprovados nas verificações automáticas do Accessibility Insights (axe-core), o que reforça a necessidade de confirmá-los na interface.

As ocorrências semelhantes identificadas por ferramentas diferentes foram agrupadas por categoria. Entretanto, não foram consideradas duplicatas confirmadas quando não havia evidência de que se referiam ao mesmo elemento da interface.

Dessa forma, a discriminação permitiu identificar os achados com evidências mais consistentes e separar aqueles que ainda precisam de validação, evitando que alertas automatizados sejam tratados automaticamente como violações confirmadas.

## Resultados da inspeção

Os resultados indicaram possíveis barreiras de acessibilidade relacionadas principalmente à identificação de elementos, ao contraste de cores e à navegação por teclado.

Embora o Lighthouse tenha atribuído 88/100 à acessibilidade, as demais ferramentas identificaram ocorrências que merecem atenção. As pontuações das ferramentas não são diretamente comparáveis, pois utilizam metodologias diferentes.

### Síntese dos problemas encontrados

A tabela apresenta os problemas sinalizados pelas ferramentas e as observações do teste manual, relacionando-os aos critérios WCAG 2.2 e indicando a situação de cada um após a discriminação.

| Problema | Critério WCAG 2.2 relacionado | Tela/Página | Frequência | Situação |
|---|---|---|---|---|
| Imagens sem texto alternativo | 1.1.1 — Conteúdo não textual | Página principal | 4 (WAVE) | Confirmado |
| Campos de formulário sem rótulo | 1.3.1 — Informações e relações | Página principal | 5 (WAVE) | Confirmado |
| Botões sem nome acessível | 4.1.2 — Nome, função e valor | Página principal | 4 (WAVE) | Confirmado |
| Links sem nome acessível | 2.4.4 — Finalidade do link | Página principal | 8 (WAVE); 1 (Accessibility Insights) | Confirmado (ao menos 1 link) |
| Contraste insuficiente | 1.4.3 — Contraste mínimo | Página principal | 3 (WAVE); 2 (Accessibility Insights) | Confirmado |
| Ausência de foco visual perceptível no zoom | 2.4.7 — Foco visível | Controle de zoom | 1 observação | Confirmado (teste manual) |
| Zoom não acionado com Enter | 2.1.1 — Teclado | Controle de zoom | 1 observação | Confirmado|
| Elementos sinalizados como inalcançáveis pelo teclado | 2.1.1 — Teclado | Página principal | 42 (Accessibility Insights) | Confirmado|

*Tabela 1 — Síntese dos problemas e das observações de acessibilidade.*

**Observação:** as quantidades correspondem às ocorrências apresentadas por cada ferramenta, indicada entre parênteses, e não são somadas, porque ferramentas diferentes podem apontar o mesmo elemento. As duas linhas de "observação" vêm do teste manual. Dos oito registros, quatro foram confirmados na discriminação e quatro permanecem pendentes.

Os resultados demonstram maior concentração de ocorrências automatizadas relacionadas à identificação acessível de links, botões e campos de formulário.

A ausência de nomes ou rótulos adequados pode dificultar a compreensão dos elementos por usuários que utilizam leitores de tela. Os problemas de contraste podem prejudicar a percepção das informações, especialmente para pessoas com baixa visão.

No teste manual, o controle de zoom apresentou possíveis limitações de operação e indicação visual do foco, que precisam ser investigadas em verificações complementares.

### Critérios WCAG violados

A tabela a seguir apresenta os critérios WCAG 2.2 associados aos problemas identificados, organizados de acordo com seus princípios e níveis de conformidade.

| Princípio | Diretriz | Critério relacionado | Nível | Situação |
|---|---|---|---|---|
| Perceptível | 1.1 Alternativas em texto | 1.1.1 Conteúdo não textual | A | Confirmado |
| Perceptível | 1.3 Adaptável | 1.3.1 Informações e relações | A | Confirmado |
| Perceptível | 1.4 Distinguível | 1.4.3 Contraste mínimo | AA | Confirmado |
| Operável | 2.1 Acessível por teclado | 2.1.1 Teclado | A | Em parte (zoom por Enter)  |
| Operável | 2.4 Navegável | 2.4.4 Finalidade do link | A | Confirmado |
| Operável | 2.4 Navegável | 2.4.7 Foco visível | AA | Confirmado |
| Robusto | 4.1 Compatível | 4.1.2 Nome, função e valor | A |Confirmado (botões) |

*Tabela 2 — Critérios WCAG 2.2 relacionados aos problemas encontrados.*

A classificação evidencia que os problemas sinalizados envolvem principalmente os princípios de perceptibilidade, operabilidade e robustez.

Os critérios apresentados representam possíveis violações identificadas na inspeção. A confirmação definitiva dos que constam como pendentes depende da verificação individual das ocorrências e de seu comportamento na interface.

## Considerações sobre os resultados

A inspeção de acessibilidade do Flightradar24 permitiu identificar possíveis barreiras que podem comprometer a interação de usuários com diferentes necessidades de acessibilidade.

As avaliações automatizadas realizadas com WAVE, Lighthouse e Accessibility Insights apresentaram resultados complementares, destacando problemas relacionados à identificação acessível de elementos interativos, ausência de textos alternativos e contraste insuficiente.

A verificação manual de navegação por teclado também indicou possíveis dificuldades no controle de zoom do mapa, principalmente em relação à visibilidade do foco e à ativação da funcionalidade.

Os resultados reforçam a importância de combinar diferentes métodos de avaliação, considerando que ferramentas automatizadas não conseguem identificar todas as barreiras existentes em uma interface.

Conclui-se que, apesar de apresentar recursos de acessibilidade e obter uma pontuação de 88/100 no Lighthouse, o Flightradar24 possui aspectos que necessitam de investigação e possíveis melhorias para proporcionar uma experiência mais acessível.


**Limitações:** os resultados dependem das ferramentas utilizadas e do estado da página no momento da análise, e as ferramentas apresentaram diferenças entre si; o teste manual se restringiu ao controle de zoom do mapa; e nenhum teste foi feito com pessoas com deficiência.

Como continuidade da avaliação, recomenda-se realizar testes complementares com leitor de tela, verificar fonte e espaçamento e concluir as verificações manuais de navegação por teclado, permitindo uma análise mais abrangente da conformidade com as diretrizes WCAG 2.2.

---

**Navegação:** [Voltar ao README](../README.md) · [Comunicabilidade](../04-avaliacao-comunicabilidade/mac.md) · [Apresentação do sistema](../00-flightradar24/apresentacao-do-sistema.md)
