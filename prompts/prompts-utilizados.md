# Prompts Utilizados — Projeto NotebookLM

## 1. Sobre este arquivo

Este documento registra os principais prompts utilizados durante o desenvolvimento do projeto de estudo sobre **Educação Financeira para Iniciantes** no NotebookLM.

Os prompts foram utilizados em diferentes etapas do processo:

* exploração inicial do tema;
* organização dos conteúdos;
* verificação crítica das respostas;
* aprendizagem ativa por meio de quiz;
* validação do conhecimento construído.

O objetivo não foi apenas obter respostas da IA, mas utilizar o NotebookLM como uma ferramenta de apoio ao estudo, sempre relacionando as respostas às fontes selecionadas.

---

# 2. Prompt 1 — Exploração inicial

## Objetivo

Obter uma primeira visão geral sobre o conceito de educação financeira e identificar os principais assuntos que poderiam fazer parte do estudo.

## Prompt

> Explique o que é educação financeira para uma pessoa que está começando a estudar o assunto. Utilize as fontes deste caderno para construir a resposta e cite as fontes utilizadas.

## Resultado obtido

O NotebookLM apresentou uma explicação ampla sobre educação financeira e abordou temas como:

* comportamento financeiro;
* orçamento;
* necessidades e desejos;
* poupança;
* reserva de emergência;
* crédito;
* dívidas;
* investimentos.

A resposta foi útil para obter uma visão inicial do tema, mas apresentou muitos assuntos de uma só vez.

## Referências utilizadas

A resposta foi construída a partir das fontes adicionadas ao caderno do NotebookLM, incluindo materiais do:

* Banco Central do Brasil;
* Comissão de Valores Mobiliários;
* CVM / Planejar;
* SUSEP.

## Aprendizado

Um prompt mais aberto permite que a ferramenta escolha a estrutura da resposta.

Para estudar de maneira mais organizada, seria melhor definir previamente os conceitos que deveriam ser abordados e o formato esperado.

Essa observação levou à criação do segundo prompt.

---

# 3. Prompt 2 — Estruturação do conteúdo

## Objetivo

Criar uma explicação mais organizada, estabelecendo uma sequência lógica de aprendizagem para alguém que está começando a estudar educação financeira.

## Prompt

> Estou estudando educação financeira pela primeira vez e quero construir uma base sólida antes de aprender sobre investimentos.
>
> Utilizando exclusivamente as fontes deste caderno, explique os fundamentos da educação financeira para um iniciante.
>
> Organize a resposta nesta ordem:
>
> 1. O que é educação financeira
> 2. Necessidades e desejos
> 3. Receitas e despesas
> 4. Orçamento pessoal
> 5. Poupança
> 6. Reserva de emergência
> 7. Crédito e endividamento
>
> Para cada conceito:
>
> * apresente uma definição simples;
> * explique por que ele é importante;
> * dê um exemplo cotidiano;
> * cite as fontes utilizadas.
>
> Não aprofunde investimentos neste momento. Ao final, apresente 5 conceitos que eu deveria dominar antes de começar a estudar investimentos.

## Resultado obtido

A resposta ficou mais organizada e adequada para iniciantes.

Cada conceito passou a apresentar:

* definição;
* importância;
* exemplo;
* fontes relacionadas.

Também foi possível identificar conhecimentos que deveriam ser consolidados antes do estudo de investimentos.

Entre os conceitos destacados pelo NotebookLM estavam:

* pagar-se primeiro;
* reserva de emergência;
* Tripé dos Investimentos;
* juros compostos e efeito do tempo;
* inflação e rentabilidade real.

## Referências utilizadas

A resposta foi solicitada utilizando exclusivamente as fontes adicionadas ao caderno do NotebookLM.

As referências utilizadas estavam relacionadas principalmente aos materiais do Banco Central do Brasil, CVM e SUSEP.

## Aprendizado

Quanto mais claro o contexto, a estrutura e as restrições fornecidas no prompt, mais direcionada tende a ser a resposta.

A principal evolução em relação ao primeiro prompt foi deixar de apenas perguntar **“o que é?”** e passar a definir **como o conteúdo deveria ser apresentado**.

---

# 4. Prompt 3 — Auditoria e verificação crítica

## Objetivo

Verificar se as respostas produzidas pelo NotebookLM estavam realmente sustentadas pelas fontes ou se algumas afirmações haviam sido simplificadas ou interpretadas além do conteúdo original.

## Prompt

> Analise criticamente a resposta anterior.
>
> Identifique todas as afirmações que envolvem números, percentuais, recomendações ou regras práticas, especialmente:
>
> * reserva de emergência de 3 a 12 meses;
> * limite de 30% da renda para dívidas;
> * uso de Tesouro Selic ou CDB com liquidez diária para reserva;
> * relação entre liquidez, risco e rentabilidade;
> * efeitos dos juros compostos e do tempo;
> * impacto da inflação sobre a rentabilidade.
>
> Para cada afirmação:
>
> 1. Apresente a afirmação.
> 2. Indique exatamente qual fonte sustenta a afirmação.
> 3. Explique se a fonte apresenta isso como uma regra, recomendação, exemplo ou apenas uma possibilidade.
> 4. Informe se a afirmação foi simplificada ou interpretada além do que a fonte diz.
> 5. Se houver alguma ressalva importante, apresente-a.
>
> Utilize exclusivamente as fontes deste caderno e não utilize conhecimento externo.

## Resultado obtido

A análise mostrou que algumas afirmações precisavam de contexto.

Entre os principais pontos identificados:

### Reserva de emergência

Diferentes fontes apresentam diferentes períodos de referência, dependendo da situação da pessoa.

Portanto, não deve ser tratada como uma regra universal de **“3 a 12 meses”**.

### Endividamento

O percentual de comprometimento da renda depende da definição utilizada pela fonte e deve considerar a **renda mensal líquida**.

### Reserva de emergência e investimentos

Características como baixo risco e liquidez são importantes para uma reserva de emergência, mas os produtos utilizados como exemplo possuem características e riscos próprios.

### Terminologia

A expressão correta encontrada nas fontes é **“Tripé dos Investimentos”**, e não “Triângulo dos Investimentos”.

### Juros compostos

Os efeitos dependem das taxas, do período e das condições consideradas na simulação.

### Inflação

Uma rentabilidade nominal não representa necessariamente ganho real de poder de compra.

## Referências utilizadas

A auditoria foi solicitada para confrontar as afirmações diretamente com as fontes disponíveis no caderno, especialmente:

* Banco Central do Brasil — Caderno de Educação Financeira;
* CVM — Guia de Planejamento Financeiro;
* CVM / Planejar — Livro TOP: Planejamento Financeiro Pessoal;
* SUSEP — Orçamento.

## Cicatriz identificada

> **A IA pode transformar recomendações, exemplos ou informações contextuais das fontes em regras gerais se a resposta não for auditada.**

## Aprendizado

A etapa de auditoria mostrou que utilizar IA para estudar não significa aceitar automaticamente tudo o que ela apresenta.

As respostas precisam ser comparadas com as fontes, principalmente quando envolvem:

* números;
* percentuais;
* recomendações;
* regras práticas;
* conceitos financeiros.

Essa foi uma das principais aprendizagens do projeto.

---

# 5. Prompt 4 — Aprendizagem ativa com quiz

## Objetivo

Verificar se os conceitos estudados realmente haviam sido compreendidos, em vez de apenas lidos.

## Prompt

> Quero testar meu conhecimento sobre educação financeira.
>
> Utilizando exclusivamente as fontes deste caderno, crie um quiz com 10 questões sobre os fundamentos estudados.
>
> Regras:
>
> * Não apresente as respostas agora.
> * Faça perguntas de múltipla escolha com 4 alternativas (A, B, C e D).
> * Misture questões conceituais e situações práticas do cotidiano.
> * Distribua as questões entre:
>
>   1. Educação financeira
>   2. Necessidades e desejos
>   3. Receitas e despesas
>   4. Orçamento
>   5. Poupança
>   6. Reserva de emergência
>   7. Crédito e endividamento
> * Evite questões que dependam de informações que não estejam nas fontes.
> * Indique a fonte relacionada a cada questão, mas não revele a resposta correta.
> * Não dê dicas sobre qual alternativa é correta.
>
> Depois que eu responder às 10 questões, faça a correção, explique meus erros e indique quais conceitos devo revisar.

## Resultado obtido

Foi gerado um quiz com 10 questões de múltipla escolha.

As questões envolveram conceitos e situações práticas relacionadas ao conteúdo estudado.

O resultado obtido foi:

> **10/10 — 100% de acerto.**

Todas as questões foram respondidas com segurança antes da correção.

## Referências utilizadas

As questões foram elaboradas utilizando exclusivamente o conteúdo das fontes adicionadas ao NotebookLM, com indicação da fonte relacionada a cada questão.

## Aprendizado

O quiz funcionou como uma etapa de **aprendizagem ativa**, pois exigiu recuperar os conhecimentos estudados e aplicá-los em situações práticas.

Isso ajudou a verificar se o conteúdo havia sido compreendido e não apenas consultado.

---

# 6. Prompt 5 — Validação da minha própria definição

## Objetivo

Comparar uma definição criada durante o estudo com as informações presentes nas fontes, verificando quais partes estavam alinhadas e quais poderiam ser aprimoradas.

## Prompt

> Analise a definição abaixo sobre educação financeira:
>
> “Educação financeira é a capacidade de entender como o dinheiro funciona para tomar decisões inteligentes sobre como ganhar, gastar, poupar e investir. Ela não serve para fazer você parar de gastar, mas sim para ensinar você a dominar o seu dinheiro em vez de se tornar escravo dele.”
>
> Utilizando exclusivamente as fontes deste caderno:
>
> 1. indique quais partes da definição estão de acordo com as fontes;
> 2. indique quais partes são simplificações ou interpretações;
> 3. sugira uma versão mais tecnicamente precisa, mantendo uma linguagem adequada para iniciantes;
> 4. cite as fontes que sustentam cada ponto.
>
> Não descarte a definição original; quero compará-la com a definição baseada nas fontes.

## Resultado obtido

A análise mostrou que a definição criada estava alinhada com as fontes ao relacionar educação financeira com decisões conscientes sobre dinheiro, consumo, poupança e investimentos.

Também foram identificadas algumas simplificações.

Por exemplo, a expressão **“entender como o dinheiro funciona”** representa apenas parte do conceito, pois as fontes também destacam conhecimentos, atitudes e comportamentos.

A expressão **“ganhar dinheiro”** também não representa diretamente um dos principais pilares apresentados pelas fontes utilizadas.

Já a expressão **“dominar o seu dinheiro”** foi identificada como uma metáfora útil para comunicação com iniciantes, mas não como uma definição técnica utilizada pelas fontes.

## Referências utilizadas

A definição foi comparada exclusivamente com as fontes adicionadas ao caderno do NotebookLM, especialmente os materiais institucionais utilizados para fundamentar o estudo.

## Aprendizado

A comparação entre uma explicação própria e as fontes foi importante para perceber que compreender um assunto não significa necessariamente conseguir defini-lo de maneira tecnicamente completa.

A IA foi utilizada nesse momento como uma ferramenta de **validação e refinamento**, e não como substituta da construção do conhecimento.

---

# 7. Evolução dos prompts

O processo apresentou uma evolução gradual:

| Etapa | Abordagem    | Objetivo                                |
| ----- | ------------ | --------------------------------------- |
| 1     | Exploração   | Entender o tema de forma geral          |
| 2     | Estruturação | Organizar o conteúdo para estudo        |
| 3     | Auditoria    | Verificar afirmações e fontes           |
| 4     | Quiz         | Testar a compreensão                    |
| 5     | Validação    | Comparar meu entendimento com as fontes |

A evolução pode ser resumida como:

> **Perguntar → Estruturar → Questionar → Testar → Validar**

---

# 8. Principais “cicatrizes” do processo

As “cicatrizes” registram problemas, simplificações ou aprendizados encontrados durante a utilização do NotebookLM.

## Cicatriz 1 — Prompt muito aberto

O primeiro prompt gerou uma resposta útil, mas bastante ampla.

**Problema:** a IA decidiu a estrutura e a prioridade dos conteúdos.

**Aprendizado:** especificar contexto, ordem dos assuntos e formato esperado.

---

## Cicatriz 2 — Simplificação de informações

Algumas recomendações financeiras apresentadas pelo NotebookLM poderiam ser interpretadas como regras universais.

**Problema:** uma informação retirada de uma fonte pode perder contexto quando resumida.

**Aprendizado:** solicitar uma auditoria específica para números, percentuais, recomendações e regras práticas.

---

## Cicatriz 3 — Terminologia

Foi identificado o uso de **“Triângulo dos Investimentos”** em vez de **“Tripé dos Investimentos”**.

**Problema:** uma pequena alteração de terminologia pode mudar a precisão do conteúdo.

**Aprendizado:** conferir conceitos e nomenclaturas diretamente nas fontes.

---

## Cicatriz 4 — Aprender não é apenas ler

Mesmo com respostas bem estruturadas, ainda era necessário verificar se o conteúdo havia sido compreendido.

**Aprendizado:** utilizar perguntas, situações práticas e quizzes para testar a recuperação do conhecimento.

---

## Cicatriz 5 — CET

Ao analisar uma situação de parcelamento, foi percebido que dizer que todo valor adicional ao preço à vista corresponde necessariamente a **“juros”** pode ser uma simplificação.

O custo total de uma operação pode envolver outros encargos.

**Aprendizado:** é necessário diferenciar custo adicional, juros e **Custo Efetivo Total (CET)**.

---

# 9. Modelo de prompt reutilizável

A partir da experiência com o NotebookLM, foi possível identificar uma estrutura de prompt que pode ser reutilizada em outros estudos.

## Estrutura

### CONTEXTO

Explique qual é o tema e para quem o conteúdo será apresentado.

### FONTES

Utilize exclusivamente as fontes disponíveis no caderno.

### TAREFA

Defina exatamente o que precisa ser analisado ou explicado.

### RESTRIÇÕES

Informe o que deve ou não ser abordado.

### FORMATO

Defina como a resposta deve ser organizada.

### VERIFICAÇÃO

Peça referências, ressalvas ou comparação com as fontes quando necessário.

## Exemplo

> Estou estudando [TEMA] pela primeira vez.
>
> Utilize exclusivamente as fontes deste caderno.
>
> Explique [ASSUNTO] para um iniciante.
>
> Organize a resposta em:
>
> 1. Definição
> 2. Importância
> 3. Exemplo
> 4. Cuidados ou limitações
>
> Cite as fontes utilizadas e destaque qualquer informação que seja uma recomendação, exemplo ou regra específica da fonte.

---

# 10. Conclusão

A utilização do NotebookLM mostrou que a qualidade do estudo não depende apenas da ferramenta, mas também da forma como as perguntas são construídas e das verificações realizadas.

O processo evoluiu de uma consulta inicial para uma metodologia de estudo que envolveu:

* pesquisa baseada em fontes;
* elaboração de prompts;
* organização do conhecimento;
* auditoria das respostas;
* aprendizagem ativa;
* validação do conhecimento;
* produção de um material final de estudo.

Dessa forma, o NotebookLM foi utilizado não apenas para gerar respostas, mas como uma ferramenta de apoio ao processo de aprendizagem.

O principal aprendizado foi perceber que **uma boa utilização de IA envolve saber perguntar, verificar, questionar e aplicar o conhecimento obtido**.
