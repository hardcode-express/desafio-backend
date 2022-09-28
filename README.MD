## Desafio Backend NodeJs

Nesse desafio iremos avaliar suas habilidades em:

* **Node**
* **Typescript**
* **Aplicação Restful**
* **Jest** (desejável mas não obrigatório)
* **Docker** (desejável mas não obrigatório)

Você irá desenvolver a API de uma aplicação para a criação de um quiz de perguntas e respostas!

**A aplicação deverá prover o registro e autenticação de dois tipos de usuários**:

* Admin
* Player

**Cada quiz é composto por**:

* 10 perguntas com 3 respostas onde apenas 1 é correta.
* Cada resposta correta acumula a 1 ponto.
* Cada resposta errada perde 1 ponto. A menor pontuação possível é 0.
* Possui uma categoria.

**Ao iniciar o jogo**:

* O player deve escolher uma categoria válida e receber um quiz com perguntas aleatórias referentes a categoria escolhida.

**Ao finalizar o jogo**:

* O player deve receber a contabilização dos seus pontos juntamente com a sua posição atual no ranking global. Não há limitação de quantos quizzes o player pode responder.

**O ranking**:

* É a contabilização dos pontos acumulados por cada player.
* Ranking geral considera todas as categorias.
* Ranking por categoria agrupa por categorias.
* Este requisito é desejável mas não obrigatório.

**Permissões**:

* Todos os endpoints devem estar protegidos por autenticação.
* Usuários do tipo **Admin** tem permissão para criar perguntas e respostas para os quizzes.
* Usuários do tipo **Player** tem permissão para jogar e consultar o ranking.

## Requisitos

* O projeto precisa estar configurado para rodar em um ambiente Linux (preferencialmente como container Docker).
* Deve anexar ao seu projeto uma coleção do postman com todos os endpoints criados e exemplos de utilização.

**Para executar seu código devemos executar apenas os seguintes comandos**:

* git clone $seu-fork
* cd $seu-fork
* comando para instalar dependências
* comando para executar a aplicação

## Critério de avaliação

* **Organização do código**: Separação de módulos, view e model
* **Clareza**: O README explica de forma resumida qual é o problema e como pode rodar a aplicação?
* **Assertividade**: A aplicação está fazendo o que é esperado? Se tem algo faltando, o README explica o porquê?
* **Legibilidade do código** (incluindo comentários)
* **Segurança**: Existe alguma vulnerabilidade clara?
* **Cobertura de testes** (Não esperamos cobertura completa mas é importante garantir o fluxo principal)
* **Histórico de commits** (estrutura e qualidade)
* **UX**: A API é intuitiva?
* **Escolhas técnicas**: A escolha das bibliotecas, banco de dados, arquitetura, etc, é a melhor escolha para a aplicação?

## Dúvidas

Qualquer duvida basta perguntar no discord!

Ao completar o desafio, submeta um pull-request a esse repositório com uma breve explicação das decisões tomadas e principalmente as instruções para execução do projeto.

**Boa sorte! ;)**
