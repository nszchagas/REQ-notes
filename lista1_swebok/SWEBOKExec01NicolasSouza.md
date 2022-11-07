---
title: "Engenharia de Requisitos - SWEBOK"
author: "Nicolas Chagas Souza (matrícula: 20/0042327)"
date: "04/11/2022"
geometry: left=2cm,right=2cm,top=1cm,bottom=2cm
output: pdf_document
---

## Questões

### O que significa SWEBOK? Por que ele foi escrito? Por quem ele foi escrito?

A sigla SWEBOK significa Software Engineering Body of Knowledge, e, como o nome sugere, trata-se de um guia para o conhecimento relativo à area da Engenharia de Software, que vem sendo desenvolvido há mais de quarenta anos. O guia documenta os conceitos teóricos que perpassam pelos processos da engenharia de um produto de software, e foi escrito pelo IEEE, o instituto de engenheiros elétricos e eletrônicos.

> Fonte: Seção Foreword do SWEBOK.

### Em que consiste a área de conhecimento de Requisitos de Software?

A área de Requisitos de Software é responsável pela elicitação, análise, especificação e validação de requisitos de software, e, também, pela gerência dos requisitos durante o ciclo de vida do produto de software.

> Fonte: Página 1-1 do capítulo 1 do SWEBOK.

### Com quais áreas do conhecimento a área de Requisitos de Software está relacionadas?

A área de Requisitos de Software está relacionada intimamente às áreas de: Design, Testes, Manutenção, Qualidade, Gerência, Processo, Modelos e Métodos de Software.

> Fonte: Página 1-1 do capítulo 1 do SWEBOK.

### O que é um requisito de software?

Os requisitos de software expressam as necessidades e restrições presentes em um produto de software. São propriedades que devem ser atendidas pelo produto, geralmente apresentam-se com o intuito de resolver algum problema do mundo real. Os requisitos de um software, geralmente, são uma combinação complexa proveniente das pessoas pertencentes ao ambiente no qual o software irá operar.

> Fonte: Páginas 1-1 e 1-2 do capítulo 1 do SWEBOK.

### Cite uma propriedade essencial de todos os requisitos de software

Uma propriedade essencial dos requisitos é que eles sejam verificáveis, como uma funcionalidade individual, no caso dos requisitos funcionais, ou a nível de sistema, no caso dos requisitos não funcionais. A equipe de requisitos, testes e qualidade deve assegurar que os requisitos atendidos dentro dos recursos disponíveis. Além disso, requisitos possuem outros atributos, como a priorização e a identificação única.

> Fonte: Página 1-2 do capítulo 1 do SWEBOK.

### O que são requisitos funcionais e não funcionais?

Requisitos funcionais estão relacionados às funções que o software deve executar, como por exemplo cadastrar um usuário, e também são conhecidos como funcionalidades. Um requisito funcional também pode ser descrito como aquele que pode ser validado por um conjunto finito de casos de teste. Já os requisitos não funcionais são aqueles que agem para restringir a solução às condições necessárias, como por exemplo estipular que o tempo de resposta de uma requisição ao backend seja inferior a 3 segundos. Estes também são conhecidos como requisitos de qualidade e podem ser classificados como, por exemplo, requisitos de performance, manutenção, segurança, confiabilidade ou interoperação.

> Fonte: Página 1-3 do capítulo 1 do SWEBOK.

### Sobre os requisitos quantificáveis, escreva como os requisitos de software devem ser

Requisitos de software devem ser determinados da maneira mais clara e não ambígua possível e, quando adequado, de forma quantitativa, tornando-o um requisito quantificável. Por exemplo, o requisito citado de exemplo na questão anterior: "o tempo de resposta de uma requisição ao backend deve ser inferior a 3 segundos" é um requisito quantificável, pois estipula uma meta de tempo de forma quantitativa.

> Fonte: Página 1-3 do capítulo 1 do SWEBOK.

### Sobre os atores de Processo, quem são muitas pessoas envolvidas no processo de requisitos?

Existem muitas pessoas envolvidas no processo, além do especialista em requisitos. Embora o conjunto de _stakeholders_ varie entre projetos, ele sempre incluirá usuários e clientes. Alguns exemplos típicos de _stakeholders_ são: usuários do sistema, clientes, analistas de mercado, reguladores e engenheiros de software.

> Fonte: Página 1-4 do capítulo 1 do SWEBOK.

### Escreva sobre elicitação de requisitos

A elicitação de requisitos diz respeito à da etapa de concepção dos requisitos de um software e à forma como o engenheiro de software pode coletá-los. Essa atividade envolve a identificação dos _stakeholders_ e a criação de relacionamentos entre a equipe de desenvolvimento e o cliente. Uma boa elicitação de requisitos é pautada em uma comunicação efetiva entre os vários _stakeholders_ do projeto, que deve ser mantida ao longo de todo o processo de desenvolvimento do software. O analista de requisitos deve conduzir essa comunicação, mediando o contato entre o domínio dos usuários e outros stakeholders e o mundo técnico do engenheiro de software. Uma parte crítica da elicitação de requisitos é a definição do escopo do projeto, que envolve a descrição de do software que está sendo especificado, seu objetivo e a priorização das entregas para garantir ao cliente que as necessidades negociais mais importantes sejam atendidas primeiros. Essa abordagem minimiza a possibilidade do analista de requisitos gastar tempo elicitando requisitos de baixa importância naquele instante, por exemplo. Por outro lado, a descrição do software deve ser escalável e propícia para inclusão de requisitos que possam ser identificados ao longo do processo

> Fonte: Página 1-5 do capítulo 1 do SWEBOK.

### Quais são as fontes dos requisitos?

Os requisitos podem vir de diversas fontes de requisitos de softwares e de _frameworks_ para gerência-los. Algumas das fontes são as seguintes:

- Objetivos do software: a partir dos principais objetivos, em maior nível, do software, é possível extrair um conjunto de requisitos.
- Domínio de conhecimento: background de conhecimentos necessários para o entendimento dos requisitos elicitados.
- Stakeholders: o engenheiro de software precisa identificar, representar e gerenciar os pontos de vista dos diversos tipos de stakeholders.
- Regras de negócio: fornecem algumas restrições que podem ser transformadas em requisitos, por exemplo, um aluno só pode se matricular em uma matéria após ter sido aprovado nas matérias que são seus pré-requisitos.
- O sistema operacional do ambiente: o ambiente em que o sistema será executado fornece requisitos, como por exemplo alguns requisitos não funcionais como consumo máximo de memória.
- O ambiente: a cultura, estrutura e política dos clientes do software devem ser levados em consideração durante a elicitação de requisitos.

> Fonte: Páginas 1-5 e 1-6 do capítulo 1 do SWEBOK.

### Escreva sobre as técnicas para a elicitação de requisitos

O engenheiro de software geralmente irá elicitar informações que servirão de base para a formulação dos requisitos. A elicitação de requisitos com apoio em recursos humanos pode ser feita por algumas técnicas, como: entrevistas, cenários, protótipos, reuniões, observação e histórias de usuário.

> Fonte: Páginas 1-6 e 1-7 do capítulo 1 do SWEBOK.

### Escreva sobre análise de requisitos

A análise de requisitos tem como objetivos principais identificar e resolver conflitos entre requisitos, determinar as fronteiras do software e como deve ser a interação com o sistema organizacional e operacional em que funcionará e elaborar requisitos de sistema, que serão transformados em requisitos de software. Análise de requisitos contempla a classificação de requisitos, para facilitar os _tradeoffs_ necessários e o processo de estabelecer a negociação de requisitos. Os requisitos devem ser descritos de forma precisa para que possam ser validados, sua implementação seja verificável e o custo, estimável.

> Fonte: Página 1-7 do capítulo 1 do SWEBOK.

### Escreve sobre a especificação de requisitos de software na engenharia de software

A especificação de requisitos, geralmente, diz respeito à etapa de produção de um documento que possa ser sistematicamente revisado, avaliado e aprovado. Dentre os documentos que podem ser produzidos nessa etapa, encontram-se a definição do sistema, os requisitos do sistema e os requisitos de software, para sistemas mais complexos, e os requisitos de software, para sistemas mais simples.

> Fonte: Página 1-10 do capítulo 1 do SWEBOK.

### Escreva sobre a validação dos requisitos

A etapa de validação de requisitos contempla o processo de análise do documento de requisitos para garantir que ele defina o software esperado pelos usuários. Os documentos elaborados na etapa de especificação passam por uma etapa de verificação e validação, para garantir que o engenheiro de software tenha entendido os requisitos. Além disso, é importante verificar se o documento elaborado está de acordo com os padrões exigidos pelos _stakeholders_, como por exemplo uma padronização de documentos em uma empresa, é consistente, completo e de fácil entendimento.

> Fonte: Página 1-11 do capítulo 1 do SWEBOK.

### Como os requisitos podem ser validados?

Diferentes tipos de _stakeholders_, como representantes do cliente e da equipe de desenvolvimento, devem revisar os documentos. Os documentos de requisitos estão sujeitos às mesmas práticas de gerência de configuração que os mais artefatos do ciclo de vida de um software. Quando práticos, os requisitos também estão sujeitos a uma verificação da gerência de configuração, utilizando-se ferramentas de gerenciamento de requisitos. É comum que os requisitos sejam validados em um ou mais pontos do processo de requisitos, para que os problemas sejam identificados e resolvidos antes do comprometimento de recursos.

## Referências Bibliográficas

Bourque and R.E. Fairley, eds., Guide to the Software Engineering Body of Knowledge, Version 3.0, IEEE Computer Society, 2014; www.swebok.org.
