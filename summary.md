# Engenharia de software

* Trata da criação, desenvolvimento e manutenção de software;
* Aplicação sistemática de princípios, métodos e práticas para o
desenvolvimento, manutenção e evolução de software de qualidade.

## Fases de um projeto de software

* Levantamento de requisitos __(Eng. de software/PO)__;
* Design do software __(UX/UI)__;
* Implementação __(devs/root)__;
* Testes __(QA)__;
* Implantação e manutenção __(Todo o time envolvido)__.
  
## Levantamento de requisitos

* Coleta de informações sobre as funcionalidades e características do sistema;
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

* Os requisitos coletados são analisados, refinados e organizados para
criar uma compreensão clara do que o sistema deve fazer;
* Objetivo: garantir que os requisitos sejam completos, consistentes, precisos e compreensíveis antes de prosseguir para as fases de design e implementação.

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
* __Importância do Projeto de Software__: Economiza tempo
e recursos. Reduz riscos de erros e retrabalho. Facilita a
comunicação entre a equipe de desenvolvimento.

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