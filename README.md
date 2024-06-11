### Métodos Ágeis, Desenvolvimento Incremental e Desenvolvimento Guiado por Testes

#### **Métodos Ágeis**
Os métodos ágeis surgiram devido à insatisfação com os elevados custos e overheads envolvidos nos métodos tradicionais de design de software. Estes métodos ágeis:

- **Foco no código**: Prioridade ao código em vez do design.
- **Abordagem iterativa**: Desenvolvimento de software baseado em iterações curtas e contínuas.
- **Entrega rápida de software funcional**: Objetivo de entregar software funcional rapidamente e evoluir rapidamente para atender aos requisitos em mudança.

**Adequação**: Estes métodos são mais adequados para sistemas empresariais de pequena a média dimensão ou produtos de PC, onde a flexibilidade e a capacidade de responder rapidamente às mudanças são cruciais.

#### **Vantagens do Desenvolvimento Incremental**
- **Entrega de valor ao cliente com cada incremento**: A funcionalidade do sistema está disponível mais cedo, proporcionando valor contínuo.
- **Incrementos iniciais atuam como protótipos**: Ajudam a elucidar requisitos para incrementos posteriores.
- **Risco reduzido de falha do projeto**: A entrega contínua e a validação constante reduzem o risco de falha total do projeto.
- **Serviços prioritários recebem mais testes**: As funcionalidades de maior prioridade tendem a ser mais testadas, aumentando a sua fiabilidade.

#### **Problemas com o Desenvolvimento Incremental**
- **Problemas de gestão**: Dificuldade em julgar o progresso e encontrar problemas devido à falta de documentação.
- **Problemas contratuais**: Contratos tradicionais podem exigir especificações; sem especificações, são necessários diferentes tipos de contratos.
- **Problemas de validação**: Sem especificações, é difícil testar o sistema.
- **Problemas de manutenção**: Mudanças contínuas tendem a corromper a estrutura do software, tornando-o mais caro de modificar e evoluir para atender a novos requisitos.

#### **Desenvolvimento Guiado por Testes (TDD)**
- **Escrever testes antes do código**: Clarifica os requisitos a serem implementados.
- **Testes como programas**: Testes são escritos como programas e executados automaticamente para verificar a execução correta.
- **Execução automática de testes**: Todos os testes anteriores e novos são executados automaticamente quando novas funcionalidades são adicionadas, garantindo que novas funcionalidades não introduzam erros.

### Revisão e Comparação dos Conceitos

#### **Modelos de Processos de Desenvolvimento de Software**

1. **Modelo em Cascata**
   - **Características**: Fases distintas e sequenciais (Requisitos, Design, Implementação, Testes, Manutenção).
   - **Vantagens**: Clareza na definição das fases e entregas; fácil gestão de grandes projetos com requisitos bem definidos.
   - **Desvantagens**: Inflexível; difícil de acomodar mudanças após o início do processo; não adequado para projetos com requisitos voláteis.
   - **Objetivo**: Completar cada fase antes de iniciar a próxima, garantindo um desenvolvimento estruturado e ordenado.

2. **Desenvolvimento Incremental**
   - **Características**: Especificação, design, desenvolvimento e validação são intercalados; entregas em incrementos funcionais.
   - **Vantagens**: Flexível; permite feedback contínuo e adaptação rápida; entrega de valor contínua ao cliente.
   - **Desvantagens**: Pode ser difícil de gerir sem documentação clara; problemas de contrato e validação.
   - **Objetivo**: Entregar um sistema funcional aos utilizadores finais com incrementos que incorporam os requisitos mais importantes primeiro.

3. **Engenharia de Software Baseada em Componentes**
   - **Características**: Montagem do sistema a partir de componentes existentes (bibliotecas, frameworks, módulos).
   - **Vantagens**: Reutilização de componentes testados e comprovados; redução de custos e tempo de desenvolvimento.
   - **Desvantagens**: Pode haver problemas de compatibilidade e integração; dependência de componentes externos.
   - **Objetivo**: Desenvolver sistemas robustos e escaláveis através da reutilização de componentes existentes.

#### **Estratégias para Lidar com Mudanças**

1. **Entrega Incremental**
   - **Descrição**: Entregas incrementais são feitas ao cliente para experimentação, permitindo mudanças em incrementos posteriores a baixo custo.
   - **Objetivo**: Adaptar-se às mudanças rapidamente e entregar valor contínuo aos utilizadores finais.

2. **Prototipagem Descartável**
   - **Descrição**: Desenvolvimento de uma versão parcial para verificar e ajustar os requisitos antes da implementação final.
   - **Objetivo**: Validar ou derivar requisitos do sistema, especialmente quando os requisitos são mal compreendidos ou incertos.

### Conclusão

Cada modelo de processo de desenvolvimento de software tem suas vantagens e desvantagens, e a escolha do modelo adequado depende das características do projeto, dos requisitos do cliente e da necessidade de flexibilidade para acomodar mudanças. O **Modelo em Cascata** é mais adequado para projetos com requisitos bem definidos e estáveis, enquanto o **Desenvolvimento Incremental** e a **Engenharia de Software Baseada em Componentes** são mais indicados para ambientes dinâmicos onde a adaptação contínua é necessária. As estratégias de **Entrega Incremental** e **Prototipagem Descartável** oferecem formas eficazes de lidar com a incerteza e as mudanças, garantindo que o produto final atenda às necessidades dos utilizadores e possa evoluir rapidamente conforme necessário.

Além disso, os **Métodos Ágeis** e o **Desenvolvimento Guiado por Testes (TDD)** complementam estas abordagens ao enfatizar a entrega rápida de software funcional, a adaptação contínua às mudanças e a garantia de qualidade através de testes automatizados.
