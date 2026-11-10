# Guia Prático do Aluno: Projeto Integrador de Desenvolvimento de Sistemas

O Projeto Integrador (UC14) é a unidade curricular onde você irá articular todas as competências desenvolvidas ao longo do curso (UC1 a UC13). O principal objetivo é vivenciar situações reais do mercado, integrando trabalho em equipe, resolução de problemas, tomada de decisão e a aplicação prática da tecnologia no desenvolvimento de uma solução completa. Lembre-se que, para a aprovação e avaliação final no Projeto Integrador, o sistema será avaliado de forma global, considerando o conjunto de competências desenvolvidas em todas as unidades curriculares do curso.

## 1. O Desafio: Tema Livre
Para este projeto, **o tema é totalmente livre!** Vocês deverão identificar um problema real (seja de uma empresa local, uma necessidade da comunidade ou um nicho de mercado inexplorado) ou um cenário simulado que demande uma solução tecnológica. 

A única regra é: o sistema deve englobar as competências construídas durante o curso, passando por planejamento (UC1, UC2), algoritmos e POO (UC3, UC4), modelagem de banco de dados (UC5), interfaces UI/UX e Web/Mobile/Desktop (UC6 a UC10) e, fundamentalmente, testes de qualidade e manutenção (UC11, UC12, UC13). Escolham algo que os motive, que exija criatividade e que sirva como um excelente portfólio profissional para o mercado de trabalho.

## 2. Metodologia de Trabalho
* **Organização e Agilidade:** O projeto simula o ambiente corporativo real. A equipe deve se auto-organizar, definir papéis, tomar decisões técnicas conjuntas e gerenciar o tempo de forma ágil (recomendamos fortemente o uso de quadros Kanban, metodologias ágeis ou práticas do Scrum, conforme visto na UC2).
* **Ciclo de Testes Colaborativos:** No mercado de tecnologia, o desenvolvimento e a garantia de qualidade (QA) andam juntos. O trabalho incluirá uma rotina colaborativa de testes cruzados, utilizando Bugtrackers e metodologias da UC11: sua equipe testará os sistemas de outras equipes, identificando falhas e gerando relatórios técnicos rigorosos que deverão ser corrigidos por eles (e vice-versa). Como QA, a inteligência emocional para relatar falhas e o respeito à equipe avaliada são essenciais.

## 3. Roteiro e Checklist Detalhado de Entregas
Para garantir que vocês se sintam guiados do início ao fim e não pulem etapas cruciais, dividimos o projeto em 5 fases principais. Utilizem este checklist para orientar as atividades e validar as subentregas da equipe:

### Fase 1: Ideação, Escopo e Planejamento (UC1 e UC2)
Nesta fase inicial, a equipe define "o que" será feito, para quem, os limites técnicos e "quando".
- [ ] **Documento de Visão e Escopo:** Descrição detalhada do problema escolhido, o público-alvo, a solução tecnológica proposta (o que é e o que fará de principal) e os objetivos do sistema. **(UC1 - Modelar sistemas de informação)**
- [ ] **Levantamento de Requisitos e Regras de Negócio:** **(UC1 - Modelar sistemas de informação)**
    - [ ] Lista de Requisitos Funcionais (o que o sistema faz: ex. cadastrar cliente, calcular frete).
    - [ ] Lista de Requisitos Não Funcionais (desempenho, segurança, plataformas, usabilidade).
    - [ ] Regras de Negócio claras (restrições e condições que o sistema deve obedecer).
- [ ] **Plano de Ação e Cronograma Ágil:** Organização das tarefas (Kanban/Scrum), distribuição de papéis (Product Owner, Scrum Master, Devs, QAs) e definição de prazos para os Sprints. **(UC2 - Planejar o desenvolvimento de sistemas)**

### Fase 2: Arquitetura, Modelagem de Dados e UX/UI (UC5 e UC6)
A hora de desenhar a estrutura lógica e a interface antes de codificar.
- [ ] **Modelagem do Banco de Dados:** **(UC5 - Manipular banco de dados)**
    - [ ] Modelo Conceitual e Diagrama Entidade-Relacionamento (DER).
    - [ ] Modelo Lógico (tabelas, chaves primárias e estrangeiras, relacionamentos e tipos de dados) e normalização.
- [ ] **Modelagem da Aplicação em UML:** **(UC1 - Modelar sistemas de informação)**
    - [ ] Elaboração do Diagrama de Casos de Uso.
    - [ ] Elaboração do Diagrama de Classes e Arquitetura do Sistema.
- [ ] **Design de Interação e Interface - UX/UI:** **(UC6 - Desenvolver elementos de interface visual para sistemas de informação)**
    - [ ] Pesquisa com o Usuário e Personas.
    - [ ] Criação de Wireframes de baixa fidelidade para mapeamento da jornada.
    - [ ] Protótipos navegáveis de alta fidelidade (cores, tipografia, fluxo de navegação e responsividade).

### Fase 3: Desenvolvimento de Software (Front-end, Back-end e Banco de Dados - UC3, UC4, UC7 a UC10)
A fase de codificação propriamente dita, onde o protótipo ganha vida funcional (via Web, Desktop ou Mobile).
- [ ] **Implementação e Persistência do Banco de Dados:** **(UC5 - Manipular banco de dados)**
    - [ ] Script de criação de tabelas, constraints e relacionamentos.
    - [ ] Carga inicial de dados de teste (DDL/DML via SGBD).
- [ ] **Desenvolvimento Front-end / Interface Visual:** **(UC7 - Desenvolver código de front-end para web, UC8 - Desenvolver sistemas web, UC9 - Desenvolver sistemas desktop, UC10 - Desenvolver aplicações para dispositivos móveis)**
    - [ ] Telas responsivas construídas conforme o protótipo UX/UI.
    - [ ] Validações iniciais de interface (ex: campos obrigatórios, formatação).
- [ ] **Desenvolvimento Back-end e Integração (POO):** **(UC3 - Construir algoritmos, UC4 - Desenvolver código de orientação a objetos, UC8 - Desenvolver sistemas web, UC9 - Desenvolver sistemas desktop, UC10 - Desenvolver aplicações para dispositivos móveis)**
    - [ ] Implementação de lógica de negócios utilizando o paradigma de Orientação a Objetos.
    - [ ] Integração completa do front-end com o banco de dados (operações de CRUD completas e regras de negócio ativas).
    - [ ] Código modularizado, organizado e devidamente versionado no Git/GitHub.

### Fase 4: Qualidade, Testes Colaborativos e Manutenção (QA - UC11, UC12 e UC13)
A aplicação das técnicas de Qualidade (QA) para garantir que o sistema não possua falhas críticas antes da entrega.
- [ ] **Documentação de Testes (Plano e Casos de Teste):** **(UC11 - Testar sistemas de informação)**
    - [ ] Elaboração do Plano de Testes (escopo e ferramentas).
    - [ ] Criação dos Casos de Teste baseados nos Critérios de Aceitação (com foco em Testes Limite e Tratamento de Erros, abrangendo Testes Estáticos e Dinâmicos).
- [ ] **Execução de Auditoria e Testes Cruzados (Como Tester):** **(UC11 - Testar sistemas de informação, UC12 - Manter sistemas de informação)**
    - [ ] Execução da bateria de Testes Funcionais, Aceitação e Smoke Tests na aplicação de uma equipe colega.
    - [ ] Emprego, quando aplicável e sob supervisão, de Inteligência Artificial para auxílio na análise técnica e criação de prompts de auditoria.
- [ ] **Bug Reports e Gestão de Defeitos:** **(UC11 - Testar sistemas de informação, UC12 - Manter sistemas de informação)**
    - [ ] Registro técnico formal das falhas encontradas no sistema alheio (ID, passos de reprodução, erro obtido vs esperado e severidade) utilizando ferramentas (Bugtrackers/Kanban).
- [ ] **Correção, Reteste e Suporte (Manutenção):** **(UC12 - Manter sistemas de informação, UC13 - Documentar sistemas de informação)**
    - [ ] Recebimento dos Bug Reports de outras equipes, identificação do defeito no código (Testes de Caixa Branca e Depuração), e implementação da correção com versionamento documentado.
    - [ ] Simulação de suporte técnico respondendo e guiando o usuário em dificuldades.

### Fase 5: Entrega Final e Apresentação Institucional
O empacotamento do ciclo de desenvolvimento e a defesa do projeto.
- [ ] **Entrega do Software Funcional:** O sistema em sua versão final, funcional, versionado, corrigido e capaz de realizar suas tarefas centrais de ponta a ponta (End-to-End). **(UC1 a UC13)**
- [ ] **Relatório Técnico Final:** Documento (ou portfólio digital) compilando todas as fases: arquitetura escolhida, desafios enfrentados, soluções aplicadas e propostas de manutenção/evolução para o futuro. **(UC13 - Documentar sistemas de informação)**
- [ ] **Apresentação Final (Pitch):** Defesa oral para a banca avaliadora, demonstrando o sistema rodando na prática, simulando situações reais e mostrando como os requisitos de negócio foram atendidos. **(Integração UC1 a UC13)**

## Sugestões de como organizar o projeto no GitHub
Para manter a organização do código, documentação e tarefas durante o desenvolvimento do projeto, recomendamos seguir as boas práticas descritas abaixo:

* **Estrutura de Pastas Recomendada:**
    * `/docs/`: Armazene toda a documentação produzida (Documento de Visão, Diagramas UML/DER, wireframes e artefatos das Fases 1 e 2).
    * `/src/` ou `/app/`: Organize o código-fonte da aplicação (separando front-end, back-end ou pacotes conforme a arquitetura adotada).
    * `/database/`: Guarde os scripts DDL/DML de criação do banco de dados, relacionamentos e carga inicial de dados de teste.
* **Documentação no README.md:** Utilize as informações deste Guia Prático para construir um README.md completo na raiz do repositório, detalhando o problema, a proposta da solução, instruções de execução e os integrantes da equipe.
* **Gerenciamento com GitHub Projects (Kanban Ágil):** Crie um projeto no GitHub Projects e estruture as tarefas relativas às Fases 1 a 5 em cartões (Backlog, A Fazer, Em Andamento, Em Revisão e Concluído) para controlar o fluxo de trabalho da equipe.
* **Uso de Milestones e Issues (Gestão de Defeitos na Fase 4):** Utilize Milestones para representar a entrega de cada uma das 5 fases. Na Fase 4 (Testes Cruzados), utilize as Issues para registrar os Bug Reports detalhados encontrados pelas equipes parceiras, permitindo atribuir responsáveis, definir severidade e acompanhar a correção e reteste de falhas.