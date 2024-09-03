# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

| Persona | Sexo | Gênero | Idade | Estado cívil | Tem filhos? | Profissão | Renda | Escolaridade | Residente | Hobbies |
|---------|------|--------|-------|--------------|-------------|-----------|-------|--------------|-----------|---------|
|Gabriel|Masculino|Cisgênero|35 anos|Casado|Sim|Policial militar|<= 3 mil|Graduação|Vitória da Conquista - BA|Jogar boliche, tocar violão e assistir filmes de CSI|
|Julia|Feminino|Cisgênero|17 anos|Solteira|Não|Estudante|n/a|Ensino médio incompleto|São Caetano do Sul - SP|Assistir videos curtos de maquiagem, sair com os amigos e andar de bicicleta|
|Ivo|Masculino|Não binário|45 anos|Divorciado|Não|Gerente de Marketing|<= 10 mil|Pós graduação|Cuiaba - MT|Viajar, cozinhar e ler livros de negócios|
|Lucas|Masculino|Transgênero|26 anos|Casado|Sim|Professor de história|<= 3 mil|Mestrado|Belo Horizonte - MG|Jogar jogos de tabuleiro, estar em família e assistir corridas de carro|
|Miguel|Masculino|Cisgênero|14 anos|Solteiro|Não|Estudante|n/a|Ensino fundamental incompleto|Rio Branco - AC|Andar de skate, tocar guitarra e fazer doces|
|Luara|Feminino|Transgênero|28 anos|Solteira|Sim|Analista de Sistemas|<= 6 mil|Graduação|Fortaleza - CE|Pintura, Corrida e Tocar piano|


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Modelagem do Processo de Negócio 

### Análise da Situação Atual

Apresente aqui os problemas existentes que viabilizam sua proposta. Apresente o modelo do sistema como ele funciona hoje. Caso sua proposta seja inovadora e não existam processos claramente definidos, apresente como as tarefas que o seu sistema pretende implementar são executadas atualmente, mesmo que não se utilize tecnologia computacional. 

### Descrição Geral da Proposta

Apresente aqui uma descrição da sua proposta abordando seus limites e suas ligações com as estratégias e objetivos do negócio. Apresente aqui as oportunidades de melhorias.

### Processo 1 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 1. Em seguida, apresente o modelo do processo 1, descrito no padrão BPMN. 

![Processo 1](img/02-bpmn-proc1.png)

### Processo 2 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 2. Em seguida, apresente o modelo do processo 2, descrito no padrão BPMN.

![Processo 2](img/02-bpmn-proc2.png)

## Indicadores de Desempenho

Apresente aqui os principais indicadores de desempenho e algumas metas para o processo. Atenção: as informações necessárias para gerar os indicadores devem estar contempladas no diagrama de classe. Colocar no mínimo 5 indicadores. 

Usar o seguinte modelo: 

![Indicadores de Desempenho](img/02-indic-desemp.png)
Obs.: todas as informações para gerar os indicadores devem estar no diagrama de classe a ser apresentado a posteriori. 

## Requisitos

### Requisitos Funcionais

| ID    | Descrição do Requisito                                                                  | Prioridade |
|-------|-----------------------------------------------------------------------------------------|------------|
| RF-001| Permitir que os usuários se cadastrem na plataforma com informações pessoais e áreas de conhecimento | ALTA       |
| RF-002| Permitir que os usuários criem e editem seus perfis, incluindo descrição e histórico de atividades | ALTA       |
| RF-003| Permitir que usuários não cadastrados busquem por temas ou áreas de conhecimento na interface principal | ALTA       |
| RF-004| Exibir uma lista de conhecimentos disponíveis com detalhes sobre o provedor e formas de contato | ALTA       |
| RF-005| Permitir contato direto entre usuários interessados e provedores de conhecimento via e-mail ou telefone | ALTA       |
| RF-006| Permitir filtragem de resultados de busca por área de conhecimento e disponibilidade | MÉDIA      |
| RF-007| Permitir que os usuários avaliem e comentem sobre as experiências de aprendizado ou compartilhamento | MÉDIA      |
| RF-008| Enviar notificações por e-mail ou push sobre novos pedidos de conhecimento ou contatos recebidos | MÉDIA      |

### Requisitos Não Funcionais

| ID     | Descrição do Requisito                                                                 | Prioridade |
|--------|----------------------------------------------------------------------------------------|------------|
| RNF-001| O sistema deve ser intuitivo e fácil de navegar, proporcionando uma boa experiência do usuário| ALTA       |
| RNF-002| O sistema deve responder a solicitações de busca e filtro em menos de 5 segundos | ALTA       |
| RNF-003| O sistema deve ser escalável para suportar aumento de usuários e acessos simultâneos | ALTA       |
| RNF-004| O sistema deve implementar criptografia de dados, garantindo segurança e privacidade dos usuários| ALTA       |
| RNF-005| O sistema deve ser desenvolvido de forma modular, permitindo fácil manutenção e atualização | MÉDIA      |
| RNF-006| 	A aplicação deve ser compatível com os principais sistemas operacionais do mercado. | ALTA      |

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

| ID     | Descrição da Restrição                                                                 |
|--------|----------------------------------------------------------------------------------------|
| RE-01  | O projeto deve ser entregue até o final do semestre letivo, com data limite em 23/06/2024. |
| RE-02  | O desenvolvimento do aplicativo deve utilizar exclusivamente as tecnologias disponíveis no framework selecionado. |
| RE-03  | A equipe de desenvolvimento não pode subcontratar terceiros para a realização do trabalho. |
| RE-04  | A aplicação deve ser desenvolvida exclusivamente para dispositivos móveis. |

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)

# Matriz de Rastreabilidade

A matriz de rastreabilidade é uma ferramenta usada para facilitar a visualização dos relacionamento entre requisitos e outros artefatos ou objetos, permitindo a rastreabilidade entre os requisitos e os objetivos de negócio. 

A matriz deve contemplar todos os elementos relevantes que fazem parte do sistema, conforme a figura meramente ilustrativa apresentada a seguir.

![Exemplo de matriz de rastreabilidade](img/02-matriz-rastreabilidade.png)

> **Links Úteis**:
> - [Artigo Engenharia de Software 13 - Rastreabilidade](https://www.devmedia.com.br/artigo-engenharia-de-software-13-rastreabilidade/12822/)
> - [Verificação da rastreabilidade de requisitos usando a integração do IBM Rational RequisitePro e do IBM ClearQuest Test Manager](https://developer.ibm.com/br/tutorials/requirementstraceabilityverificationusingrrpandcctm/)
> - [IBM Engineering Lifecycle Optimization – Publishing](https://www.ibm.com/br-pt/products/engineering-lifecycle-optimization/publishing/)


# Gerenciamento de Projeto

De acordo com o PMBoK v6 as dez áreas que constituem os pilares para gerenciar projetos, e que caracterizam a multidisciplinaridade envolvida, são: Integração, Escopo, Cronograma (Tempo), Custos, Qualidade, Recursos, Comunicações, Riscos, Aquisições, Partes Interessadas. Para desenvolver projetos um profissional deve se preocupar em gerenciar todas essas dez áreas. Elas se complementam e se relacionam, de tal forma que não se deve apenas examinar uma área de forma estanque. É preciso considerar, por exemplo, que as áreas de Escopo, Cronograma e Custos estão muito relacionadas. Assim, se eu amplio o escopo de um projeto eu posso afetar seu cronograma e seus custos.

## Gerenciamento de Tempo

Com diagramas bem organizados que permitem gerenciar o tempo nos projetos, o gerente de projetos agenda e coordena tarefas dentro de um projeto para estimar o tempo necessário de conclusão.

![Diagrama de rede simplificado notação francesa (método francês)](img/02-diagrama-rede-simplificado.png)

O gráfico de Gantt ou diagrama de Gantt também é uma ferramenta visual utilizada para controlar e gerenciar o cronograma de atividades de um projeto. Com ele, é possível listar tudo que precisa ser feito para colocar o projeto em prática, dividir em atividades e estimar o tempo necessário para executá-las.

![Gráfico de Gantt](img/02-grafico-gantt.png)

## Gerenciamento de Equipe

O gerenciamento adequado de tarefas contribuirá para que o projeto alcance altos níveis de produtividade. Por isso, é fundamental que ocorra a gestão de tarefas e de pessoas, de modo que os times envolvidos no projeto possam ser facilmente gerenciados. 

![Simple Project Timeline](img/02-project-timeline.png)

## Gestão de Orçamento

O processo de determinar o orçamento do projeto é uma tarefa que depende, além dos produtos (saídas) dos processos anteriores do gerenciamento de custos, também de produtos oferecidos por outros processos de gerenciamento, como o escopo e o tempo.

![Orçamento](img/02-orcamento.png)
