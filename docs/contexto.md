# Introdução

O avanço tecnológico tem impactado profundamente a maneira como gerenciamos nossas atividades diárias, tanto no ambiente profissional quanto no pessoal. A necessidade de organizar tarefas, definir prioridades e acompanhar o progresso é fundamental para manter a produtividade e cumprir prazos. No entanto, muitas pessoas e equipes enfrentam desafios com ferramentas dispersas e métodos ineficientes, resultando em perda de tempo e falhas na execução de projetos.

Este projeto tem como objetivo desenvolver um sistema web de gerenciamento de tarefas que facilite a organização e priorização de atividades. O sistema oferecerá uma plataforma centralizada para que os usuários possam registrar, acompanhar e colaborar em suas tarefas, otimizando o fluxo de trabalho e garantindo o cumprimento de metas. O público-alvo deste sistema inclui profissionais de diversas áreas, equipes de projetos e indivíduos que buscam uma maneira eficiente de gerenciar suas responsabilidades diárias.

## Problema
Em muitos ambientes de trabalho, a falta de uma ferramenta eficiente para gerenciar tarefas resulta em desorganização, perda de prazos e baixa produtividade. As pessoas frequentemente recorrem a métodos improvisados, como anotações em papel ou aplicativos que não se integram com outras ferramentas que utilizam, levando à sobrecarga cognitiva e frustração.

Além disso, as equipes enfrentam dificuldades para manter a transparência sobre o andamento das atividades e para colaborar de maneira eficaz, o que pode comprometer a execução de projetos. A ausência de uma plataforma unificada e acessível agrava esses problemas, tornando desafiador o gerenciamento de tarefas em um contexto de trabalho dinâmico e colaborativo.

Esse sistema será usado tanto por indivíduos que desejam organizar suas tarefas pessoais quanto por equipes que necessitam de uma solução integrada para gerenciar projetos e atividades coletivas. A aplicação será baseada em tecnologias web modernas, com foco em uma interface intuitiva e em recursos de integração com calendários e outras ferramentas digitais já utilizadas pelos usuários.

## Objetivos

Objetivo Geral: Desenvolver um sistema web de gerenciamento de tarefas que permita aos usuários organizar, priorizar e acompanhar suas atividades de forma centralizada, melhorando a eficiência e a produtividade.

Objetivos Específicos:

1. Criar uma plataforma intuitiva que permita o registro, categorização e priorização de tarefas de maneira simples e acessível.
2. Desenvolver funcionalidades de integração com ferramentas existentes, como calendários digitais, para facilitar a sincronização e o acompanhamento de prazos.
3. Implementar recursos de colaboração, permitindo que equipes possam compartilhar tarefas, acompanhar o progresso de projetos e manter a comunicação efetiva dentro da plataforma.

## Justificativa

Descreva a importância ou a motivação para trabalhar com esta aplicação que você escolheu. Indique as razões pelas quais você escolheu seus objetivos específicos ou as razões para aprofundar em certos aspectos do software.

O grupo de trabalho pode fazer uso de questionários, entrevistas e dados estatísticos, que podem ser apresentados, com o objetivo de esclarecer detalhes do problema que será abordado pelo grupo.

> **Links Úteis**:
> - [Como montar a justificativa](https://guiadamonografia.com.br/como-montar-justificativa-do-tcc/)

## Público-Alvo

Descreva quem serão as pessoas que usarão a sua aplicação indicando os diferentes perfis. O objetivo aqui não é definir quem serão os clientes ou quais serão os papéis dos usuários na aplicação. A ideia é, dentro do possível, conhecer um pouco mais sobre o perfil dos usuários: conhecimentos prévios, relação com a tecnologia, relações
hierárquicas, etc.

Adicione informações sobre o público-alvo por meio de uma descrição textual, diagramas de personas e mapa de stakeholders.

> **Links Úteis**:
> - [Público-alvo](https://blog.hotmart.com/pt-br/publico-alvo/)
> - [Como definir o público alvo](https://exame.com/pme/5-dicas-essenciais-para-definir-o-publico-alvo-do-seu-negocio/)
> - [Público-alvo: o que é, tipos, como definir seu público e exemplos](https://klickpages.com.br/blog/publico-alvo-o-que-e/)
> - [Qual a diferença entre público-alvo e persona?](https://rockcontent.com/blog/diferenca-publico-alvo-e-persona/)

# Especificações do Projeto

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |

Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

# Catálogo de Serviços

Descreva aqui todos os serviços que serão disponibilizados pelo seu projeto, detalhando suas características e funcionalidades.

# Arquitetura da Solução

Definição de como o software é estruturado em termos dos componentes que fazem parte da solução e do ambiente de hospedagem da aplicação.

![arq](https://github.com/user-attachments/assets/b9402e05-8445-47c3-9d47-f11696e38a3d)


## Tecnologias Utilizadas

Descreva aqui qual(is) tecnologias você vai usar para resolver o seu problema, ou seja, implementar a sua solução. Liste todas as tecnologias envolvidas, linguagens a serem utilizadas, serviços web, frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.

Apresente também uma figura explicando como as tecnologias estão relacionadas ou como uma interação do usuário com o sistema vai ser conduzida, por onde ela passa até retornar uma resposta ao usuário.

## Hospedagem

Explique como a hospedagem e o lançamento da plataforma foi feita.

> **Links Úteis**:
>
> - [Website com GitHub Pages](https://pages.github.com/)
> - [Programação colaborativa com Repl.it](https://repl.it/)
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Publicando Seu Site No Heroku](http://pythonclub.com.br/publicando-seu-hello-world-no-heroku.html)
