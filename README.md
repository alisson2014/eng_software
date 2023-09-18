# Engenharia de software

* __Definição__: Trata da criação, desenvolvimento e manutenção de software;
* __Importância__: Aplicação sistemática de princípios, métodos e práticas para o desenvolvimento, manutenção e evolução de software de qualidade.

## Fases de um projeto de software

* Levantamento de requisitos __(Eng. de software/PO)__;
* Design do software __(UX/UI)__;
* Implementação __(devs/root)__;
* Testes __(QA)__;
* Implantação e manutenção __(Todo o time envolvido)__.
  
## Levantamento de requisitos

* __Definição__: Coleta de informações sobre as funcionalidades e características do sistema;
* Necessário para construção do projeto como um todo.
* Envolve a identificação, documentação e análise das necessidades do usuário;

### Passos para realizar o levantamento de requisitos

1. Identificar as partes interessadas (stakeholders) envolvidas no projeto.
2. Realizar entrevistas e reuniões com os stakeholders para coletar informações sobre as necessidades, objetivos e restrições do sistema.
3. Se houver documentação prévia, como manuais ou especificações anteriores, analise-a para entender as características e requisitos já definidos.
4. Realizar a documentação dos requisitos de maneira clara e organizada.
5. Classificar os requisitos com base em sua importância e impacto no sistema. 
6. Apresentar os requisitos aos stakeholders para validação e feedback. 
7. Revisitar e ajustar os requisitos ao longo do processo, à medida que novas informações e insights surgirem.
 
### Técnicas para o levantamento de Requisitos

* Entrevistas;
* Questionários;
* Workshops;
* Observação;
* Prototipagem;
* Análise de Documentos.

## Análise de requisitos

* Os requisitos coletados são analisados, refinados e organizados para criar uma compreensão clara do que o sistema deve fazer;
* __Objetivo__: garantir que os requisitos sejam completos, consistentes, precisos e compreensíveis antes de prosseguir para as fases de design e implementação.

### Passos da análise de requisitos

1. Revisão Inicial dos requisitos.
2. Classificação e organização dos requisitos.
3. Verificação da completude.
4. Identificação de requisitos redundantes ou conflitantes.
5. Análise de prioridades.
6. Refinamento dos requisitos.
7. Detecção de requisitos incompletos ou inadequados.
8. Validação com as partes interessadas.
9. Documentação dos requisitos.
10. Revisão final e aprovação.

## Projeto de Software

* __Definição__: Processo de planejamento e design de um software antes de sua implementação.
* __Importância__: Economiza tempo e recursos. Reduz riscos de erros e retrabalho. Facilita a comunicação entre a equipe de desenvolvimento.

### Modelo Cascata

* Fases sequencias, onde só se passa para proxima fase após ter todas as informações e/ou requisitos necessários.

### Modelo Ágil (Scrum)

Desenvolvimento dividido em sprints curtos e bem definidos.
São suas fases: 

* __Product Backlog__: listar todas as tarefas desejadas;
* __Sprint Planning__: Planejamento das tarefas da sprint, definindo metas claras para a mesma;
* __Desenvolvimento da Sprint__: Implementação das funcionalidades selecionadas;
* __Revisão da Sprint__: Reunião para obter feedback da equipe e stackholders, visando analisar o que foi feito.
* __Retrospectiva da Sprint__:  Refletir sobre o que funcionou bem e o que pode ser melhorado. 

## Arquitetura de Software

* __Definição__: Organização fundamental de um sistema, composta por componentes, relacionamentos e propriedades.
* __Importância__: Define a estrutura geral do sistema. Orienta o desenvolvimento de módulos e componentes. Influencia a manutenção, escalabilidade e desempenho.

### Padrões de Arquitetura

* __Layered Architecture__: Divide o sistema em camadas distintas, com responsabilidades específicas
* __Client-Server Model__: Separação entre clientes(interfaces de usuário) e servidores (lógica de negócios e dados).
* __Microservices Architecture__: Divide o sistema em serviços independentes e interconectados. Escalabilidade e manutenção simplificada.
* __Monolithic Architecture__ Todo o sistema é desenvolvido e implantado como uma única unidade.

### Design Patterns (Padrões de Projeto)

* __Definição__: Definição: Soluções para problemas recorrentes no design de software.
* Exemplos de padrões de projeto: Padrão de Projeto Singleton, Padrão de Projeto Observer, Padrão de Projeto MVC, entre outros.

## Implementação e Programação de Software

* __Planejamento__: Definir os requisitos do software, criar diagramas de fluxo, esboçar a arquitetura geral e identificar os recursos necessários.
* __Requisitos do Software__: Compreender claramente o
que o software deve fazer e quais são suas funcionalidades. Isso pode ser feito por meio de interações com os stakeholders e a criação de documentos de requisitos detalhados.
* __Diagramas de Fluxo__: Visam ilustrar como os diferentes componentes do sistema se comunicam. Podem ser usados para modelar processos de negócios e fluxos de trabalho do sistema.
* __Arquitetura do Software__: O seu objetivo é dividir o sistema em módulos, definir suas responsabilidades e as interações entre eles.
* __Escolha de Linguagem e Tecnologias__: Nessa etapa são considerados pontos importantes: a finalidade do software, a expertise da equipe e a escalabilidade do mesmo.
* __Práticas de Codificação__: Seguir padrões de codificação, aplicar boas práticas de programação, comentar e documentar o projeto são fatores importantes nesta etapa.
* __Controle de Versão__: O controle de versão é crucial para
acompanhar as mudanças no código ao longo do tempo e colaborar com outros desenvolvedores.
* __Testes__:  São essenciais para garantir que o software funcione conforme o esperado, os mais importantes são: _Testes unitários_, _Testes de integração_ e _Testes de aceitação_.
* __Refatoração__: Visa melhorar o código existente sem alterar seu comportamento externo. Isso ajuda a melhorar a legibilidade, a eficiência e a manutenibilidade do código
* __Automação e Implantação__: Automatize processos como compilação, testes e implantação para garantir eficiência e consistência. Ferramentas como _Jenkins_ e _Docker_ são úteis nesse contexto.
* __Segurança__: Garanta que o software seja seguro contra
_ameaças cibernéticas_. Isso envolve proteger os dados,
validar entradas do usuário, evitar vulnerabilidades
conhecidas e adotar práticas de codificação seguras.

## Diagrama de fluxos

* Visualizam os processos, as decisões e as interações dentro de um sistema ou aplicativo.
* Ajudam a comunicar de forma clara e visual como o software irá funcionar.

### Passo a passo para desenvolver os diagrama de fluxos

* __Identificar o Processo__: Pode ser um processo de negócios, uma função específica do software ou qualquer outra ação relevante.
* __Definir Símbolos__: Os diagramas de fluxo usam símbolos
para representar diferentes elementos, como ações, decisões, entradas/saídas e conexões.
* __Mapear os Elementos__: Desenhe os símbolos correspondentes aos processos, decisões e outras etapas do fluxo. Use linhas para conectar esses elementos e indicar a ordem em que eles ocorrem.
* __Adicionar Detalhes__: Para cada símbolo, adicione detalhes relevantes. Por exemplo, dentro de um retângulo de processo, descreva a _ação_ que ocorre. Em um losango de decisão, descreva a _condição_ que determina o caminho a ser seguido.
* __Definir Fluxos Alternativos__: Muitas vezes, um processo
possui fluxos alternativos, dependendo das decisõestomadas. Desenhe diferentes caminhos no diagrama para representar essas alternativas.
* __Validar o Diagrama__: Certifique-se de que o diagrama de
fluxo representa com precisão o processo ou o fluxo que você está tentando visualizar.
* __Utilizar Ferramentas de Diagramação__: Para criar diagramas de fluxo, você pode usar ferramentas de diagramação como o Microsoft Visio, Lucidchart, draw.io (online) ou até mesmo softwares de desenho vetorial como o Adobe Illustrator.
