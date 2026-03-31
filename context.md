# PROMPT DE CONTEXTO PARA DESENVOLVIMENTO DO TCC

## CONTEXTO DO PROJETO

Este projeto de TCC está sendo desenvolvido na área de Sistemas de Informação, com foco em sistemas educacionais e gestão de processos acadêmicos.

O trabalho tem como base um sistema real chamado **Educa EMES**, desenvolvido durante estágio na Escola da Magistratura do Espírito Santo (EMES), instituição vinculada ao Poder Judiciário. O sistema foi construído de forma colaborativa entre o autor do TCC e seu supervisor técnico, estando atualmente em ambiente de produção e sendo utilizado pelos servidores da instituição.

O Educa EMES pode ser caracterizado como um sistema integrado de gestão educacional (semelhante a um ERP), abrangendo múltiplos módulos, incluindo:

* Gestão acadêmica/pedagógica
* Administração institucional
* Contratação
* Orçamento
* Documentação
* Mensageria e comunicação
* Portal externo para alunos (acompanhamento de cursos, frequência e certificados)
* Área interna para servidores

O sistema já contempla parte do fluxo acadêmico da instituição, incluindo:

* Inscrição em cursos
* Controle de frequência
* Aprovação
* Emissão de certificados

Importante destacar que a EMES não possui um sistema próprio de avaliação por notas, utilizando a frequência como critério principal para certificação. No entanto, existe integração com o Moodle, permitindo a realização de atividades avaliativas complementares.

---

## PROBLEMA A SER ABORDADO

Antes da implementação do sistema atual:

* A EMES utilizava processos manuais, incluindo registros físicos de frequência;
* Havia baixa eficiência operacional e dificuldade de controle;
* Em 2023, foi adotado o sistema Emeron Web, que apresentava:

  * Baixa usabilidade
  * Arquitetura inadequada
  * Escopo limitado apenas ao fluxo pedagógico básico;
* Diversas atividades continuavam sendo feitas manualmente:

  * Comunicação com alunos
  * Envio de e-mails
  * Divulgação de cursos
  * Aplicação de formulários

A implementação do Educa EMES representou um avanço significativo na digitalização e integração desses processos. No entanto, observa-se que o fluxo pedagógico ainda apresenta pontos de intervenção manual, ausência de padronização em determinadas etapas e limitações na automação completa do ciclo acadêmico.

Assim, o problema central deste trabalho não se restringe à inexistência de um sistema, mas à **necessidade de ampliar e consolidar a automação do fluxo pedagógico dentro de um sistema integrado já existente**, garantindo maior eficiência, padronização e redução de dependência de operações manuais.

---

## PROPOSTA DO TCC

O TCC deve apresentar o **desenvolvimento, modelagem e análise de uma solução de automação do fluxo pedagógico no sistema Educa EMES**, caracterizando-se como uma pesquisa aplicada com estudo de caso.

O sistema Educa EMES será tratado como:

* Uma solução já implementada
* O ambiente base para a aplicação da proposta
* Um estudo de caso real em instituição pública

A contribuição principal do trabalho consiste na **proposição e implementação de mecanismos que permitam a automação completa do fluxo pedagógico**, abrangendo desde a inscrição até a conclusão do curso e emissão de certificados.

O foco do trabalho NÃO é apenas descrever funcionalidades existentes, mas:

* Identificar lacunas no fluxo atual
* Propor melhorias baseadas em automação
* Modelar a solução proposta
* Implementar os mecanismos necessários
* Analisar os impactos qualitativos da solução

---

## DIRETRIZES PARA ESCRITA

* Utilizar linguagem acadêmica formal
* Evitar linguagem coloquial
* Escrever sempre no passado ou presente acadêmico (ex: "foi desenvolvido", "este trabalho apresenta")
* Não utilizar primeira pessoa
* Manter clareza e objetividade
* Evitar redundância
* Estruturar bem os parágrafos

---

## ESCOPO DO TRABALHO

O escopo deve ser delimitado da seguinte forma:

* Considerar a versão do sistema existente até o momento da escrita
* Focar principalmente nos módulos pedagógicos:

  * Inscrição
  * Frequência
  * Certificação
* Considerar a evolução desses módulos com foco na automação do fluxo
* Módulos administrativos podem ser mencionados, mas não aprofundados
* O sistema deve ser tratado como estudo de caso ou pesquisa aplicada

---

## ESTRUTURA DO CAPÍTULO 1

Desenvolver o Capítulo 1 com base na seguinte estrutura:

### 1. INTRODUÇÃO

Contextualização do tema, importância da transformação digital na educação e apresentação do sistema Educa EMES como contexto do estudo.

### 1.1 DESCRIÇÃO DO PROBLEMA

Apresentar:

* O cenário anterior da EMES (processos manuais e sistema anterior)
* A melhoria proporcionada pelo Educa EMES
* A lacuna atual: ausência de automação completa do fluxo pedagógico

### 1.2 FORMULAÇÃO DO PROBLEMA

Uma única frase clara e objetiva relacionada à automação do fluxo pedagógico.

### 1.3 PROPOSTA DE SOLUÇÃO

Apresentar a proposta de evolução do sistema Educa EMES com foco na automação do fluxo pedagógico.

### 1.4 OBJETIVOS

#### Objetivo Geral

Desenvolver e analisar uma solução de automação do fluxo pedagógico no sistema Educa EMES.

#### Objetivos Específicos

* Analisar o fluxo pedagógico atual
* Identificar pontos de intervenção manual
* Modelar a solução de automação
* Implementar os mecanismos propostos
* Avaliar qualitativamente os impactos da solução

---

## INÍCIO DO TEXTO (BASE PARA EXPANSÃO)

A transformação digital no setor público tem impulsionado a modernização de processos administrativos e educacionais, especialmente em instituições responsáveis pela formação profissional. Nesse contexto, escolas da magistratura desempenham papel essencial na capacitação de servidores e membros do judiciário, demandando soluções tecnológicas eficientes para gestão acadêmica e administrativa.

A Escola da Magistratura do Espírito Santo (EMES) insere-se nesse cenário, apresentando a necessidade de sistemas capazes de integrar e automatizar seus processos internos. Nesse contexto, foi desenvolvido o sistema Educa EMES, concebido com o objetivo de centralizar e otimizar o fluxo acadêmico e administrativo da instituição.

Embora o sistema represente um avanço significativo na digitalização dos processos institucionais, ainda se observa a necessidade de ampliar o nível de automação do fluxo pedagógico, de forma a reduzir intervenções manuais e aumentar a eficiência operacional. Dessa forma, este trabalho propõe a evolução do sistema Educa EMES por meio da implementação de mecanismos que permitam a automação completa do ciclo acadêmico.

---



# CONTEXTO PARA DESENVOLVIMENTO DO CAPÍTULO 2 – REFERENCIAL TEÓRICO

Este capítulo corresponde à revisão bibliográfica do TCC e deve demonstrar, de forma clara e fundamentada, o estado atual do conhecimento necessário para sustentar o desenvolvimento do trabalho.

O TCC está inserido na área de Sistemas de Informação e trata da proposição e implementação de uma solução de automação do fluxo pedagógico no sistema Educa EMES, utilizado pela Escola da Magistratura do Espírito Santo (EMES).

O objetivo deste capítulo NÃO é apenas apresentar definições isoladas, nem construir um glossário técnico. O capítulo deve mostrar que o autor compreende os fundamentos teóricos e conceituais que sustentam o problema abordado e a solução proposta.

A revisão bibliográfica deve partir de conceitos mais amplos e avançar progressivamente até os conceitos mais diretamente relacionados ao trabalho. Ao longo do texto, deve ficar evidente a conexão entre a literatura revisada e o problema do TCC, que envolve a automação do fluxo pedagógico em um sistema integrado de gestão educacional.

---

## OBJETIVO DO CAPÍTULO

Este capítulo deve:

- apresentar os conceitos centrais que fundamentam o trabalho;
- demonstrar o estado do conhecimento sobre sistemas de informação, sistemas integrados, sistemas educacionais, automação de processos e integração de sistemas;
- relacionar esses conceitos com o problema e com a proposta do TCC;
- fornecer base teórica suficiente para justificar as decisões que serão apresentadas nos capítulos seguintes.

---

## DIRETRIZES GERAIS DE ESCRITA

- utilizar linguagem acadêmica formal;
- evitar linguagem coloquial;
- não utilizar primeira pessoa;
- evitar definições excessivamente básicas ou triviais;
- evitar transformar o capítulo em tutorial técnico;
- evitar listar conceitos sem conexão entre si;
- construir uma narrativa lógica, conectando cada seção ao tema central do trabalho;
- incluir citações bibliográficas ao longo de todo o capítulo;
- sempre que possível, relacionar os conceitos discutidos ao contexto institucional e ao problema investigado;
- não detalhar a stack tecnológica do sistema neste capítulo;
- manter o foco em fundamentos teóricos, abordagens, características, benefícios, limitações e aplicações dos conceitos revisados.

---

## ESTRUTURA OBRIGATÓRIA DO CAPÍTULO

O capítulo deve seguir exatamente a seguinte estrutura em LaTeX:

```latex
\chapter{Referencial Teórico}

\section{Sistemas de Informação}

\section{Sistemas Integrados de Gestão}

\section{Sistemas de Gestão Educacional}

\section{Automação de Processos}

\section{Integração de Sistemas}

\section{Síntese da Revisão}
```

## ORIENTAÇÕES POR SEÇÃO
1. Sistemas de Informação

Nesta seção, apresentar o conceito de sistemas de informação, destacando seu papel no suporte à gestão organizacional, ao controle de processos, ao armazenamento e circulação de dados e à tomada de decisão.

A abordagem deve ir além de uma definição simples. É importante discutir a relevância dos sistemas de informação em contextos organizacionais, especialmente em instituições públicas, onde a organização dos processos e a confiabilidade das informações são aspectos críticos.

A seção deve ajudar a estabelecer a base conceitual do trabalho, mostrando que sistemas de informação são instrumentos centrais para integração, controle e eficiência institucional.

Pontos esperados:

conceito e finalidade dos sistemas de informação;
apoio à gestão e à tomada de decisão;
papel na organização de processos;
relevância para instituições públicas e educacionais.
2. Sistemas Integrados de Gestão

Nesta seção, discutir os sistemas integrados de gestão, com ênfase na ideia de integração de módulos, centralização de dados e unificação de processos.

A seção deve explorar o conceito de ERP e sua aplicação em ambientes organizacionais complexos, destacando benefícios como redução de redundância, maior consistência das informações, padronização de rotinas e melhoria da eficiência operacional.

Também é importante apresentar desafios ou limitações associados à adoção de sistemas integrados, como complexidade de implementação, necessidade de aderência aos processos institucionais e dependência de boa modelagem.

## A seção deve preparar o terreno para enquadrar o Educa EMES como um sistema integrado de gestão educacional.

Pontos esperados:

definição de sistemas integrados de gestão;
conceito de ERP;
integração entre módulos;
centralização e consistência de dados;
benefícios e desafios;
relação com o contexto do TCC.
3. Sistemas de Gestão Educacional

Nesta seção, apresentar os sistemas de gestão educacional, discutindo sua função no apoio às atividades acadêmicas e administrativas de instituições de ensino.

É importante abordar funcionalidades típicas desse tipo de sistema, como gestão de cursos, inscrições, acompanhamento de alunos, frequência, certificação, comunicação institucional e apoio à execução do fluxo acadêmico.

Também pode ser discutida a relação entre sistemas de gestão educacional e ambientes virtuais de aprendizagem, como LMS, incluindo o Moodle, sempre em nível conceitual e bibliográfico, sem detalhar implementação técnica.

O foco desta seção deve ser mostrar que a gestão educacional possui particularidades próprias e demanda soluções integradas e aderentes ao contexto institucional.

Pontos esperados:

conceito de sistemas de gestão educacional;
apoio ao fluxo acadêmico e administrativo;
gestão de cursos, alunos, frequência e certificação;
relação entre sistemas institucionais e LMS;
importância da aderência às necessidades da instituição.
4. Automação de Processos

Nesta seção, discutir a automação de processos organizacionais, especialmente em contextos onde há repetição de tarefas, dependência de rotinas manuais e necessidade de padronização.

A seção deve mostrar como a automação contribui para redução de falhas, maior rastreabilidade, ganho de eficiência e melhoria da execução de fluxos operacionais.

Se fizer sentido, pode-se abordar conceitos relacionados a BPM (Business Process Management), desde que isso seja feito de forma objetiva e conectado ao tema do TCC.

A seção é central para o trabalho e deve ter relação direta com a proposta do TCC, que consiste justamente na ampliação da automação do fluxo pedagógico no sistema Educa EMES.

Pontos esperados:

conceito de automação de processos;
redução de tarefas manuais;
padronização e controle;
rastreabilidade;
eficiência operacional;
possível relação com BPM;
conexão explícita com a proposta do TCC.
5. Integração de Sistemas

Nesta seção, abordar a importância da integração entre sistemas em ambientes organizacionais, destacando a troca de dados, interoperabilidade, consistência das informações e comunicação entre diferentes plataformas.

É relevante discutir por que sistemas isolados ou fragmentados dificultam a gestão institucional e como a integração entre sistemas pode melhorar a fluidez dos processos e reduzir retrabalho.

A seção também deve abrir espaço para tratar, em nível conceitual, da integração entre sistemas institucionais e plataformas externas, como ambientes virtuais de aprendizagem.

Pontos esperados:

conceito de integração de sistemas;
interoperabilidade;
troca de dados entre plataformas;
benefícios da integração;
impacto na consistência e eficiência dos processos;
relação com sistemas educacionais e com o contexto da EMES.
6. Síntese da Revisão

## Esta seção deve encerrar o capítulo articulando os conceitos apresentados ao longo da revisão bibliográfica.

Não deve ser uma repetição simples das seções anteriores. O objetivo aqui é construir uma síntese interpretativa, deixando claro como os conceitos estudados fundamentam o problema do trabalho e justificam a proposta de automação do fluxo pedagógico em um sistema integrado de gestão educacional.

A síntese deve mostrar que:

sistemas de informação sustentam o controle e a organização institucional;
sistemas integrados favorecem centralização e padronização;
sistemas de gestão educacional atendem às particularidades do domínio acadêmico;
a automação de processos é relevante para reduzir intervenções manuais;
a integração entre sistemas é fundamental para consistência e continuidade dos fluxos.

Ao final, a seção deve fazer uma transição natural para o capítulo de metodologia ou para o capítulo seguinte do trabalho.

## INSTRUÇÕES SOBRE CITAÇÕES E REFERÊNCIAS
inserir citações ao longo de todo o capítulo;
utilizar referências bibliográficas reais e academicamente adequadas;
priorizar livros, artigos científicos, dissertações, teses e documentação institucional confiável quando pertinente;
evitar afirmações sem fonte;
utilizar comandos LaTeX de citação, como \cite{}, de modo compatível com o arquivo .bib do projeto;
quando possível, sugerir também entradas BibTeX correspondentes às referências utilizadas.


# CONTEXTO PARA DESENVOLVIMENTO DO CAPÍTULO 3 – METODOLOGIA

Este capítulo deve descrever, de forma clara e detalhada, a metodologia adotada no TCC. O objetivo é explicar a natureza da pesquisa, a abordagem metodológica, o procedimento técnico utilizado, o contexto do estudo, as etapas executadas no desenvolvimento do trabalho e a forma de análise dos resultados.

O trabalho está inserido na área de Sistemas de Informação e tem como foco a proposição e implementação de uma solução de automação do fluxo pedagógico no sistema Educa EMES, utilizado pela Escola da Magistratura do Espírito Santo (EMES).

O sistema Educa EMES já existe e está em produção. No entanto, o TCC não tem como objetivo apenas descrever esse sistema, mas propor e desenvolver uma evolução específica dentro dele: a ampliação e consolidação da automação do fluxo pedagógico.

A metodologia deve refletir essa característica. Portanto, o capítulo deve enquadrar o trabalho como:

* pesquisa aplicada, pois busca resolver um problema real em contexto institucional;
* abordagem qualitativa, pois a análise dos resultados será baseada na compreensão dos impactos da solução sobre os processos institucionais, sem depender de mensuração estatística formal;
* estudo de caso, pois o trabalho se desenvolve a partir de uma situação real observada na EMES e de um sistema efetivamente utilizado pela instituição.

## Estrutura desejada para o capítulo

### 3.1 Natureza da pesquisa

Explicar que o trabalho é uma pesquisa aplicada, voltada à solução de um problema concreto relacionado à gestão educacional e à automação de processos institucionais.

### 3.2 Abordagem metodológica

Explicar que a abordagem é qualitativa, pois o interesse do trabalho está na análise da contribuição da solução proposta para a melhoria dos processos pedagógicos, observando aspectos como integração, padronização, redução de atividades manuais e eficiência operacional.

### 3.3 Procedimento técnico

Caracterizar o trabalho como estudo de caso, uma vez que a pesquisa se desenvolve em um ambiente real, com base em um sistema em produção e em necessidades institucionais concretas da EMES.

### 3.4 Contexto e objeto do estudo

Apresentar a EMES como instituição de formação vinculada ao Poder Judiciário, descrever de forma sintética o sistema Educa EMES e delimitar o objeto do estudo como a automação do fluxo pedagógico dentro desse sistema.

### 3.5 Etapas do desenvolvimento do trabalho

Descrever, em sequência lógica, as etapas realizadas no TCC, como por exemplo:

1. levantamento do contexto institucional e dos processos pedagógicos;
2. análise do sistema existente e identificação da lacuna de automação;
3. definição dos requisitos da solução proposta;
4. modelagem da solução;
5. implementação da automação no sistema;
6. análise qualitativa dos impactos da solução.

### 3.6 Estratégia de análise dos resultados

Explicar que a avaliação será qualitativa, observando a contribuição da solução para:

* redução da dependência de tarefas manuais;
* melhoria da integração entre etapas do fluxo pedagógico;
* padronização de rotinas;
* maior rastreabilidade das informações;
* apoio à eficiência operacional da instituição.

## Diretrizes de escrita

* utilizar linguagem acadêmica formal;
* evitar primeira pessoa;
* não transformar o capítulo em tutorial técnico;
* manter o foco metodológico, explicando o que foi feito e como foi feito;
* preservar coerência com o Capítulo 1, especialmente com a definição do problema e da proposta de solução;
* deixar claro que o sistema existente é a base do estudo, mas que a contribuição do TCC está na proposta e implementação da automação do fluxo pedagógico.

## Observação importante

A stack tecnológica do sistema pode ser mencionada apenas quando necessária para contextualizar a implementação, mas o detalhamento técnico das tecnologias deve ficar para capítulo posterior de arquitetura e desenvolvimento.



## INSTRUÇÃO FINAL PARA O MODELO

A partir deste contexto:

* Expandir cada seção de forma coerente e acadêmica
* Manter consistência entre problema, solução e objetivos
* Garantir que a contribuição do TCC seja clara (automação do fluxo pedagógico)
* Evitar tratar o sistema como solução final
* Produzir conteúdo adequado para TCC de graduação em Sistemas de Informação

---
