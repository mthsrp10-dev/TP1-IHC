# Avaliação de Acessibilidade

> **Rascunho.** Os trechos entre `[colchetes]` precisam ser preenchidos ou confirmados pela equipe. Apague esta observação antes da entrega.

Este documento apresenta a inspeção de acessibilidade da versão web gratuita do **Flightradar24**, realizada com base nas diretrizes **WCAG 2.2** (Web Content Accessibility Guidelines), combinando verificações manuais e automatizadas. Ele informa o escopo da avaliação, o processo seguido pela equipe, os problemas encontrados com os critérios violados e uma discussão final dos resultados.

---

## Escopo da avaliação

Foram selecionadas as seguintes telas e funcionalidades para inspeção, as mesmas do escopo geral do trabalho, e para cada uma foram definidos os aspectos de acessibilidade verificados.

| # | Tela / Funcionalidade | Aspectos verificados |
|---|---|---|
| 1 | [Mapa principal com as aeronaves] | [Leitor de tela, teclado, contraste, alternativas ao mapa] |
| 2 | [Busca de voos e de aeroportos] | [Rótulos, teclado, leitor de tela] |
| 3 | [Painel de detalhes de um voo] | [Leitor de tela, contraste, fonte e espaçamento] |
| 4 | [Chegadas e partidas de um aeroporto] | [Estrutura da tabela, leitor de tela, contraste] |
| 5 | [Filtros] | [Teclado, foco visível, leitor de tela] |
| 6 | [Marcadores (com a conta de teste da equipe)] | [Teclado, leitor de tela] |

*[Ajustar a lista às telas realmente avaliadas e informar o navegador e o sistema operacional usados.]*

## Processo utilizado

A inspeção seguiu as etapas de **detecção**, **coleção** e **discriminação**, com os testes descritos a seguir.

### Testes realizados

| Teste | Como foi feito | Ferramenta utilizada |
|---|---|---|
| **Leitor de tela** | Navegação pelas telas do escopo ouvindo o conteúdo lido, para verificar se as informações são apresentadas e interpretadas corretamente | [NVDA, Orca, VoiceOver ou outro] |
| **Navegação pelo teclado** | Uso do sistema apenas com o teclado, verificando se todos os elementos e funcionalidades podem ser acessados sem o mouse | Teclado e navegador |
| **Diretrizes WCAG 2.2** | Verificação automática e conferência manual dos critérios: estrutura do conteúdo, textos alternativos, elementos interativos e marcação | [WAVE, axe DevTools, Accessibility Insights ou outra] |
| **Fonte e espaçamento** | Ampliação do texto e do zoom e aplicação dos espaçamentos previstos na WCAG, para identificar cortes, sobreposições e perda de conteúdo | [Ferramenta ou extensão utilizada] |
| **Contraste** | Medição das combinações de cor de texto, ícones e controles contra o fundo | [WebAIM Contrast Checker, Colour Contrast Analyser ou outra] |

### Etapas

| Etapa | O que foi feito |
|---|---|
| **1. Detecção** | [Cada integrante (ou dupla) executou os testes que lhe cabiam e registrou cada problema, com a tela, o teste que o revelou e o critério WCAG violado] |
| **2. Coleção** | [Os registros foram reunidos em uma única lista, eliminando os repetidos e contando quantas vezes cada problema apareceu] |
| **3. Discriminação** | [A equipe revisou os problemas, descartou os que não eram reais e classificou os demais por **gravidade** e **impacto** para o usuário] |

**Classificação adotada:** [Descrever a escala usada, por exemplo: *bloqueia* o uso (o usuário não consegue concluir a ação), *dificulta* o uso ou *incomoda*.]

![Evidência da inspeção de acessibilidade](imagens/acessibilidade-evidencia.png)

*Figura 1 — [Descrever a evidência, por exemplo: resultado da verificação automática, teste de contraste ou captura do leitor de tela.]*

## Resultados da inspeção

[Texto de abertura: quantos problemas foram detectados no total, quantos restaram depois da coleção e da discriminação, e em quais telas se concentraram.]

### Síntese dos problemas encontrados

A tabela apresenta cada problema encontrado, o critério da WCAG 2.2 que ele viola, a tela onde ocorreu e a frequência, isto é, quantas vezes foi encontrado nos testes.

| Problema | Critério WCAG | Tela/Página | Frequência |
|---|---|---|---|
| [Descrição do problema] | [Número e nome do critério] | [Tela] | [ ] |
| [ ] | [ ] | [ ] | [ ] |

*[Explicar o que a tabela apresenta e discutir os resultados observados: quais problemas se repetem, em quais telas e qual o impacto para quem usa leitor de tela, teclado ou tem baixa visão.]*

### Critérios WCAG violados

A tabela organiza os critérios violados pelos quatro princípios da WCAG (Perceptível, Operável, Compreensível e Robusto), com a diretriz correspondente e o nível de conformidade (A, AA ou AAA).

| Princípio | Diretriz | Critério violado | Nível |
|---|---|---|---|
| [Perceptível] | [ ] | [ ] | [A / AA] |
| [Operável] | [ ] | [ ] | [A / AA] |
| [Compreensível] | [ ] | [ ] | [A / AA] |
| [Robusto] | [ ] | [ ] | [A / AA] |

*[Explicar o que a tabela apresenta e discutir os resultados observados: quais princípios concentram mais violações e se os critérios são de nível A ou AA.]*

## Considerações sobre os resultados

[Texto de encerramento: principais resultados da avaliação, quais barreiras seriam mais graves para usuários de tecnologias assistivas, como o caráter visual do mapa afeta a acessibilidade, limitações da inspeção (ferramentas usadas, telas avaliadas, uso do sistema por pessoas com deficiência não testado) e relação com os achados da inspeção heurística e do teste de usabilidade.]

---

**Navegação:** [Voltar ao README](../README.md) · [Comunicabilidade](../04-avaliacao-comunicabilidade/mac.md) · [Apresentação do sistema](../00-flightradar24/apresentacao-do-sistema.md)
