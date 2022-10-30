---
title: Fundamentos de IHC - SWEBOK
author: "Nicolas Chagas Souza (matrícula: 20/0042327)"
date: 30/10/2022 
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

This topic introduces the roles of the people who
participate in the requirements process. This pro-
cess is fundamentally interdisciplinary, and the
requirements specialist needs to mediate between
the domain of the stakeholder and that of soft-
ware engineering. There are often many people
involved besides the requirements specialist, each
of whom has a stake in the software. The stake-
holders will vary across projects, but will always
include users/operators and customers (who need
not be the same).



Typical examples of software stakeholders
include (but are not restricted to) the following:
Users: This group comprises those who will
operate the software. It is often a heteroge-
neous group involving people with different
roles and requirements.
• Customers: This group comprises those who
have commissioned the software or who rep-
resent the software’s target market.
• Market analysts: A mass-market product
will not have a commissioning customer, so
marketing people are often needed to estab-
lish what the market needs and to act as
proxy customers.
• Regulators: Many application domains, such
as banking and public transport, are regu-
lated. Software in these domains must com-
ply with the requirements of the regulatory
authorities.
• Software engineers: These individuals have
a legitimate interest in profiting from devel-
oping the software by, for example, reusing
components in or from other products. If,
in this scenario, a customer of a particu-
lar product has specific requirements that
compromise the potential for component
reuse, the software engineers must carefully
weigh their own stake against those of the
customer. Specific requirements, particu-
larly constraints, may have major impact on
project cost or delivery because they either
fit well or poorly with the skill set of the
engineers. Important tradeoffs among such
requirements should be identified.
It will not be possible to perfectly satisfy the
requirements of every stakeholder, and it is the
software engineer’s job to negotiate tradeoffs that
are both acceptable to the principal stakeholders
and within budgetary, technical, regulatory, and
other constraints. A prerequisite for this is that all
the stakeholders be identified, the nature of their
“stake” analyzed, and their requirements elicited.

> Fonte: Página 1-4 do capítulo 1 do SWEBOK.

### Escreva sobre elicitação de requisitos

Requirements elicitation is concerned with the
origins of software requirements and how the
software engineer can collect them. It is the first
stage in building an understanding of the problem
the software is required to solve. It is fundamen-
tally a human activity and is where the stakehold-
ers are identified and relationships established
between the development team and the customer.
It is variously termed “requirements capture,”
“requirements discovery,” and “requirements
acquisition.”
One of the fundamental principles of a good
requirements elicitation process is that of effec-
tive communication between the various stake-
holders. This communication continues through
the entire Software Development Life Cycle
(SDLC) process with different stakeholders at
different points in time. Before development
begins, requirements specialists may form the
conduit for this communication. They must medi-
ate between the domain of the software users (and
other stakeholders) and the technical world of the
software engineer. A set of internally consistent
models at different levels of abstraction facilitate
communications between software users/stake-
holders and software engineers.
A critical element of requirements elicitation is
informing the project scope. This involves provid-
ing a description of the software being specified
and its purpose and prioritizing the deliverables
1-5
to ensure the customer’s most important business
needs are satisfied first. This minimizes the risk
of requirements specialists spending time elicit-
ing requirements that are of low importance, or
those that turn out to be no longer relevant when
the software is delivered. On the other hand, the
description must be scalable and extensible to
accept further requirements not expressed in the
first formal lists and compatible with the pre
previous
ones as contemplated in recursive methods.
> Fonte: Página 1-3 do capítulo 1 do SWEBOK.

### Quais são as fontes dos requisitos?

Requirements have many sources in typical soft-
ware, and it is essential that all potential sources
be identified and evaluated. This topic is designed
to promote awareness of the various sources of
software requirements and of the frameworks for
managing them. The main points covered are as
follows:
• Goals. The term “goal” (sometimes called
“business concern” or “critical success fac-
tor”) refers to the overall, high-level objec-
tives of the software. Goals provide the moti-
vation for the software but are often vaguely
formulated. Software engineers need to pay
particular attention to assessing the value
(relative to priority) and cost of goals. A fea-
sibility study is a relatively low-cost way of
doing this.
• Domain knowledge. The software engineer
needs to acquire or have available knowl-
edge about the application domain. Domain
knowledge provides the background against
which all elicited requirements knowledge
must be set in order to understand it. It’s
a good practice to emulate an ontological
approach in the knowledge domain. Rela-
tions between relevant concepts within the
application domain should be identified.
• Stakeholders (see section 2.2, Process
Actors). Much software has proved unsat-
isfactory because it has stressed the require-
ments of one group of stakeholders at the
expense of others. Hence, the delivered
software is difficult to use, or subverts the
cultural or political structures of the cus-
tomer organization. The software engineer
needs to identify, represent, and manage1-6
SWEBOK® Guide V3.0
the “viewpoints” of many different types of
stakeholders.
• Business rules. These are statements that
define or constrain some aspect of the struc-
ture or the behavior of the business itself. “A
student cannot register in next semester’s
courses if there remain some unpaid tuition
fees” would be an example of a business rule
that would be a requirement source for a uni-
versity’s course-registration software.
• The operational environment. Requirements
will be derived from the environment in
which the software will be executed. These
may be, for example, timing constraints
in real-time software or performance con-
straints in a business environment. These
must be sought out actively because they can
greatly affect software feasibility and cost as
well as restrict design choices.
• The organizational environment. Software
is often required to support a business pro-
cess, the selection of which may be condi-
tioned by the structure, culture, and internal
politics of the organization. The software
engineer needs to be sensitive to these since,
in general, new software should not force
unplanned change on the business process.

1-5 e 1-6
> Fonte: Página 1-3 do capítulo 1 do SWEBOK.

### Escreva sobre as técnicas para a elicitação de requisitos

nce the requirements sources have been iden-
tified, the software engineer can start eliciting
requirements information from them. Note that
requirements are seldom elicited ready-made.
Rather, the software engineer elicits information
from which he or she formulates requirements.
This topic concentrates on techniques for getting
human stakeholders to articulate requirements-
relevant information. It is a very difficult task and
the software engineer needs to be sensitized to the
fact that (for example) users may have difficulty
describing their tasks, may leave important infor-
mation unstated, or may be unwilling or unable to
cooperate. It is particularly important to understand
that elicitation is not a passive activity and that,
even if cooperative and articulate stakeholders are
available, the software engineer has to work hard
to elicit the right information. Many business or
technical requirements are tacit or in feedback that
has yet to be obtained from end users. The impor-
tance of planning, verification, and validation in
requirements elicitation cannot be overstated. A
number of techniques exist for requirements elici-
tation; the principal ones are these:
• Interviews. Interviewing stakeholders is a
“traditional” means of eliciting requirements.
It is important to understand the advantages
and limitations of interviews and how they
should be conducted.
• Scenarios. Scenarios provide a valuable
means for providing context to the elicita-
tion of user requirements. They allow the
software engineer to provide a framework
for questions about user tasks by permitting
“what if” and “how is this done” questions
to be asked. The most common type of sce-
nario is the use case description. There is a
link here to topic 4.2 (Conceptual Modeling)
because scenario notations such as use case
diagrams are common in modeling software.
• Prototypes. This technique is a valuable tool
for clarifying ambiguous requirements. They
can act in a similar way to scenarios by pro-
viding users with a context within which they
can better understand what information they
need to provide. There is a wide range of
prototyping techniques—from paper mock-
ups of screen designs to beta-test versions of
software products—and a strong overlap of
their separate uses for requirements elicita-
tion and for requirements validation (see
section 6.2, Prototyping). Low fidelity proto-
types are often preferred to avoid stakeholder
“anchoring” on minor, incidental character-
istics of a higher quality prototype that can
limit design flexibility in unintended ways.
• Facilitated meetings. The purpose of these
meetings is to try to achieve a summative
effect, whereby a group of people can bring
more insight into their software require-
ments than by working individually. They
can brainstorm and refine ideas that may be
difficult to bring to the surface using inter-
views. Another advantage is that conflicting
requirements surface early on in a way that
lets the stakeholders recognize where these
occur. When it works well, this techniqueSoftware Requirements
may result in a richer and more consistent
set of requirements than might otherwise
be achievable. However, meetings need to
be handled carefully (hence the need for a
facilitator) to prevent a situation in which
the critical abilities of the team are eroded
by group loyalty, or in which requirements
reflecting the concerns of a few outspoken
(and perhaps senior) people that are favored
to the detriment of others.
• Observation. The importance of software
context within the organizational environ-
ment has led to the adaptation of observa-
tional techniques such as ethnography for
requirements elicitation. Software engineers
learn about user tasks by immersing them-
selves in the environment and observing how
users perform their tasks by interacting with
each other and with software tools and other
resources. These techniques are relatively
expensive but also instructive because they
illustrate that many user tasks and business
processes are too subtle and complex for
their actors to describe easily.
• User stories. This technique is commonly
used in adaptive methods (see Agile Meth-
ods in the Software Engineering Models
and Methods KA) and refers to short, high-
level descriptions of required functionality
expressed in customer terms. A typical user
story has the form: “As a <role>, I want
<goal/desire> so that <benefit>.” A user
story is intended to contain just enough infor-
mation so that the developers can produce a
reasonable estimate of the effort to imple-
ment it. The aim is to avoid some of the waste
that often happens in projects where detailed
requirements are gathered early but become
invalid before the work begins. Before a user
story is implemented, an appropriate accep-
tance procedure must be written by the cus-
tomer to determine whether the goals of the
user story have been fulfilled.
• Other techniques. A range of other techniques
for supporting the elicitation of requirements
information exist and range from analyzing
competitors’ products to applying data min-
ing techniques to using sources of domain
knowledge or customer request databases.

1-6 e 1-7
> Fonte: Página 1-3 do capítulo 1 do SWEBOK.

### Escreva sobre análise de requisitos

This topic is concerned with the process of ana-
lyzing requirements to
• detect and resolve conflicts between
requirements;
• discover the bounds of the software and how
it must interact with its organizational and
operational environment;
• elaborate system requirements to derive soft-
ware requirements.
The traditional view of requirements analysis
has been that it be reduced to conceptual model-
ing using one of a number of analysis methods,
such as the structured analysis method. While
conceptual modeling is important, we include the
classification of requirements to help inform trad-
eoffs between requirements (requirements clas-
sification) and the process of establishing these
tradeoffs (requirements negotiation).
Care must be taken to describe requirements
precisely enough to enable the requirements to
be validated, their implementation to be verified,
and their costs to be estimated.

1-7
> Fonte: Página 1-3 do capítulo 1 do SWEBOK.

### Escreve sobre a especificação de requisitos de software na engenharia de software

For most engineering professions, the term “spec-
ification” refers to the assignment of numerical
values or limits to a product’s design goals. In
software engineering, “software requirements
specification” typically refers to the production of
a document that can be systematically reviewed,
evaluated, and approved. For complex systems,
particularly those involving substantial nonsoft-
ware components, as many as three different
types of documents are produced: system defini-
tion, system requirements, and software require-
ments. For simple software products, only the
third of these is required. All three documents are
described here, with the understanding that they
may be combined as appropriate. A description of
systems engineering can be found in the Related
Disciplines of Software Engineering chapter of
this Guide.

1-10
> Fonte: Página 1-3 do capítulo 1 do SWEBOK.

### Escreva sobre a validação dos requisitos

The requirements documents may be subject to val-
idation and verification procedures. The require-
ments may be validated to ensure that the software
engineer has understood the requirements; it is
also important to verify that a requirements docu-
ment conforms to company standards and that it
is understandable, consistent, and complete. In
cases where documented company standards or
terminology are inconsistent with widely accepted
standards, a mapping between the two should be
agreed on and appended to the document.
Formal notations offer the important advantage
of permitting the last two properties to be proven
(in a restricted sense, at least). Different stake-
holders, including representatives of the customer
and developer, should review the document(s).
Requirements documents are subject to the same
configuration management practices as the other
deliverables of the software life cycle processes.
When practical, the individual requirements are
also subject to configuration management, gener-
ally using a requirements management tool (see
topic 8, Software Requirements Tools).
It is normal to explicitly schedule one or more
points in the requirements process where the
requirements are validated. The aim is to pick up
any problems before resources are committed to
addressing the requirements. Requirements vali-
dation is concerned with the process of examin-
ing the requirements document to ensure that it
defines the right software (that is, the software
that the users expect).
1-11
> Fonte: Página 1-3 do capítulo 1 do SWEBOK.

### Como os requisitos podem ser validados?

## Referências Bibliográficas

Bourque and R.E. Fairley, eds., Guide to the Software Engineering Body of Knowledge, Version 3.0, IEEE Computer Society, 2014; www.swebok.org.
