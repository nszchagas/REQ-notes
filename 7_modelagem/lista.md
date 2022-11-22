---
title: Lista - Modelagem de Requisitos - Cenários e Léxicos
author: "Nicolas Chagas Souza (matrícula: 20/0042327)"
date: 18/11/2022
geometry: left=2cm,right=2cm,top=1cm,bottom=2cm
output: pdf_document
---




### 1) Estude sobre modelagem e apresente as suas anotações de estudo

Modelagem é a atividade de elaborar modelos capazes de representar características ou comportamentos de um software. A modelagem pode ser feita em diversas notações, de acordo com o modelo escolhido, e em diferentes níveis de abstração. São exemplos de modelagem mapas mentais, rich pictures e modelos de argumentação. A modelagem é essencial para representar de maneira visual aspectos importantes ao processo de desenvolvimento que possuam certa dificuldade em ser representados de forma textual.

### 2) Estude sobre cenários e apresente as suas anotações de estudo

A estratégia de cenários visa fornecer uma maior compreensão das interações entre ambientes e sistemas, por meio da qual é possível elicitar a parte comportamental do software, como sua dinâmica de funcionamento ou fluxo de dados. Um cenário deve ser composto por título, objetivos, contexto, atores, recursos, exceções e episódios.

### 3) Apresente um exemplo de cenários de um dos projetos da disciplina do semestre passado

|**Cenário001**|
|--------------|
|**Titulo**    |
|Cadastro de um novo usuário no Duolingo|
|**Objetivo**  |
|Cadastrar um novo usuário|
|**Contexto**  |
| Local: Tela inicial ao entrar na aplicação pela primeira vez<br/> Tempo: Indeterminado<br/> Pré-condição: Acesso a internet |
|**Atores**    |
|[Usuário](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Lexicos/#lexico01) não cadastrado|
|**Recursos**  |
| Internet<br/> Smartphone ou Computador<br/> Duolingo previamente instalado |
|**Episódios** |
| Usuário novo<br/> Usuário que deseja criar uma outra conta na plataforma<br/> Usuário clica em 'Começar Agora'<br/> Escolhe o idioma no qual deseja aprender<br/> Escolhe uma Meta<br/> Escolhe motivação<br/> Idade<br/> Nome<br/> E-mail<br/> Senha<br/> Usuário tem progresso salvo |
|**Restrição** |
|Internet indisponível|
|**Exceção**   |
| Sem acesso ao Smartphone ou Computador<br/> Email inválido<br/> Internet indisponível |

<div style="text-align:center">
<p> Tabela 1: Exemplo de Cenário. Fonte: <a href="https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Cenarios/">Projeto Duolingo</a> </p>
</div>

### 4) Estude sobre léxico e apresente as suas anotações de estudo

O léxico é uma técnica de modelagem de requisitos que tem como objetivo descrever os símbolos de uma linguagem. O objetivo é identificar palavras ou frases peculiares ao domínio da aplicação sendo estudada. A descrição dos símbolos deve conter noção (significado) e impacto (uso) do símbolo. Cada símbolo tem zero ou mais sinônimos, uma ou mais noções e um ou mais impactos. Um léxico pode ser do tipo verbo, objetivo ou estado.

### 5) Apresente um exemplo de léxico do tipo verbo, outro do objeto e outro do estado de um dos projetos da disciplina do semestre passado

| Léxico | Noção | Impacto | Sinônimo         | Classificação |
| ------ | ----- | ------- | --------         | ------------- |
|Acessar |O usuário acessa a plataforma da Disney+.|O usuário pode acessar a Disney+ pelo navegador.</br> O usuário pode acessar a Disney+ pelo aplicativo mobile.</br>O usuário pode acessar a Disney+ pela Android TV.</br>O usuário pode acessar a Disney+ pela Apple TV.</br>O usuário pode acessar a Disney+ pelo PlayStation 4.</br>O usuário pode acessar a Disney+ pelo Xbox One.</br>O usuário pode acessar a Disney+ por uma smartTV.</br>O usuário pode acessar a Disney+ pelo Amazon Fire TV.</br>O usuário pode acessar a Disney+ pelo Roku.</br>|Conectar, entrar  | Verbo         |

<div style="text-align:center">
<p> Tabela 2: Exemplo de Léxico do tipo Verbo. Fonte: <a href="https://requisitos-de-software.github.io/2021.1-DisneyPlus/modelagem/lexicos/">Projeto Disney+</a> </p>
</div>

|L01|Usuário|
|:---|:---|
|**Autor**|Francisco Heronildo|
|**Classificação**|Objeto|
|**Sinônimos**|Utilizador, utente, cliente, usador, usufruidor, desfrutador, usufrutuário, usufrutueiro.|
|**Noção**|> Indivíduo que utiliza o aplicatívo|
|**Impacto**|> O usuário instala o Duolingo|
||> O usuário faz cursos de idiomas|
||> O usuário tem funcionalidades que o ajudam no aprendizado de novos idiomas|
|**Rastro**| Não possui |

<div style="text-align:center">
<p> Tabela 3: Exemplo de Léxico do tipo Objeto. Fonte: <a href="https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Lexicos/">Projeto Duolingo</a> </p>
</div>

|L10|XP|
|:---|:---|
|**Autor**|Brian Lui|
|**Classificação**|Estado|
|**Sinônimos**|Experiência, pontos.|
|**Noção**|> O usuário ganha XP sempre que completa uma tarefa que melhora seu domínio no idioma. Essas tarefas incluem concluir uma lição e praticar uma unidade|
|**Impacto**|> Inventiva o usuário a jogar mais para passar ao próximo nível.|
||> Faz o usuário ficar melhor no idioma.|
|**Rastro**| Não possui |

<div style="text-align:center">
<p> Tabela 4: Exemplo de Léxico do tipo Estado. Fonte: <a href="https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Lexicos/">Projeto Duolingo</a> </p>
</div>

### 6) Utilizando a ferramenta C & L (<http://pes.inf.puc-rio.br/cel/aplicacao/>), defina e apresente um cenário para o seu projeto da disciplina

|**Cenário**|
|--------------|
|**Titulo**    |
|Início de uma nova partida de xadrez contra o computador|
|**Objetivo**  |
|Iniciar uma partida de xadrez contra o computador|
|**Contexto**  |
|Local: Tela inicial ao entrar na aplicação pela primeira vez <br/> Tempo: Indeterminado |
|**Atores**    |
| Usuário      |
|**Recursos**  |
| Smartphone ou Computador<br/> Lichess previamente instalado |
|**Episódios** |
| - Usuário abre o aplicativo <br/> - Usuário seleciona a opção "Jogar com o Computador" <br/> - Usuário escolhe: cor das peças, variante de xadrez, nível, temporizador, tempo e incremento. <br/> - Usuário seleciona opção "jogar com o computador" <br/> - A partida é iniciada |
|**Exceção**   |
| Sem acesso ao Smartphone ou Computador |

<div style="text-align:center">
<p> Tabela 5: Cenário para o início de uma partida no Lichess </p>
</div>

### 7) Utilizando a ferramenta C & L, defina e apresente um léxico do tipo verbo, outro do objeto e outro do estado do seu projeto da disciplina

| Léxico | Noção | Impacto | Sinônimo         | Classificação |
| ------ | ----- | ------- | --------         | ------------- |
|    Assistir    |    Assistir uma partida de xadrez   |    Ao utilizar o aplicativo, o usuário pode assistir a partida de outros jogadores em tempo real.      |       Ver           |  Verbo        |

<div style="text-align:center">
<p> Tabela 6: Léxico do tipo verbo </p>
</div>

| Léxico | Noção | Impacto | Sinônimo         | Classificação |
| ------ | ----- | ------- | --------         | ------------- |
|   Variante  |   - Estilo de jogo de xadrez. <br/> - Conjunto de regras aplicadas em uma partida.    |  - O usuário pode jogar uma partida na variante crazyhouse; <br/> - O usuário pode jogar na variante racing kings.  | Modalidade, alternativa, opção.                          |   Objeto      |

<div style="text-align:center">
<p> Tabela 7: Léxico do tipo objeto </p>
</div>

| Léxico | Noção | Impacto | Sinônimo         | Classificação |
| ------ | ----- | ------- | --------         | ------------- |
|   Amistosa     |   Partida amistosa    |    O usuário pode iniciar uma partida contra outro jogador no modo amistoso.    |      Não ranqueada.            |   Estado      |

<div style="text-align:center">
<p> Tabela 8: Léxico do tipo estado </p>
</div>
