# pond_m6_s8

### Traceability Matrix

| **ID**  | **Requisito**                        | **Requisito de Negócio**                      | **Módulos/Componentes**                                 | **Testes de Integração**                                                              | **Testes de Sistema**                                                                 |
|---------|--------------------------------------|-----------------------------------------------|--------------------------------------------------------|--------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| RF-001  | Visualização de Informações de um Projeto  | Melhorar a transparência e o acompanhamento de projetos pelos usuários  | UI: Serviço de Projeto, Componente de Detalhes do Projeto  | Testar a integração entre a interface de seleção de projeto e o componente de detalhes do projeto  | Validar que a interface mostra corretamente as informações do projeto selecionado  |
| RF-002  | Visualização dos Projetos Específicos do Usuário  | Melhorar a transparência e o acompanhamento de projetos pelos usuários  | UI: Serviço de Projetos,   | Verificar a interação entre a interface de listagem de projetos e o banco de dados dos projetos do usuário  | Garantir que os projetos são listados corretamente em ordem cronológica  |
| RNF-001 | Manutenibilidade                     | Garantir a continuidade e a facilidade de manutenção do sistema  | Back-end: Gerenciador de Dependências, Sistema de Controle de Versão  | Testar a inclusão de novas bibliotecas sem afetar o funcionamento atual do sistema  | Validar a consistência e padronização do código conforme as diretrizes estabelecidas  |

### Detalhes dos Requisitos e Ligações

#### Requisito Funcional 1 (RF-001): Visualização de Informações de um Projeto
- **Descrição:** O sistema deve permitir que os usuários visualizem as informações de um determinado projeto.
- **Critérios de Aceitação:**
  1. Deve haver uma interface para que o usuário consiga selecionar um projeto específico.
  2. Após selecionar um projeto em específico, deve haver uma interface para demonstrar informações de um projeto, como o seu nome, a descrição e o responsável por ele.
- **Ligação com Requisito de Negócio:** Melhorar a transparência e o acompanhamento de projetos pelos usuários.
- **Módulos/Componentes:**
  - UI: Componente de Seleção de Projeto
  - UI: Componente de Detalhes do Projeto
- **Testes:**
  - **Integração:** Verificar a integração entre a interface de seleção de projeto e o componente de detalhes do projeto.
  - **Sistema:** Validar que a interface mostra corretamente as informações do projeto selecionado.

#### Requisito Funcional 2 (RF-002): Visualização dos Projetos Específicos do Usuário
- **Descrição:** O sistema deve permitir que o usuário consiga visualizar os seus próprios projetos.
- **Critérios de Aceitação:**
  1. O sistema deve apresentar uma interface específica onde os projetos do usuário são listados.
  2. Os projetos devem ser apresentados em ordem cronológica, dos mais recentes aos mais antigos.
- **Ligação com Requisito de Negócio:** Melhorar a transparência e o acompanhamento de projetos pelos usuários.
- **Módulos/Componentes:**
  - UI: Componente de Listagem de Projetos
- **Testes:**
  - **Integração:** Verificar a interação entre a interface de listagem de projetos e o banco de dados dos projetos do usuário.
  - **Sistema:** Garantir que os projetos são listados corretamente em ordem cronológica.

#### Requisito Não Funcional (RNF-001): Manutenibilidade
- **Descrição:** O sistema deve ser fácil de manter, permitindo atualizações, correções de erros e melhorias sem interrupções significativas do serviço.
- **Critérios de Aceitação:**
  1. O código-fonte do sistema deve conter uma padronização e consistência interna, de acordo com o que foi decidido pela equipe.
  2. O sistema deve permitir a inclusão de novas bibliotecas ou ferramentas de desenvolvimento sem afetar o seu funcionamento como um todo.
- **Ligação com Requisito de Negócio:** Garantir a continuidade e a facilidade de manutenção do sistema.
- **Módulos/Componentes:**
  - Back-end: Gerenciador de Dependências
  - Back-end: Sistema de Controle de Versão
- **Testes:**
  - **Integração:** Testar a inclusão de novas bibliotecas sem afetar o funcionamento atual do sistema.
  - **Sistema:** Validar a consistência e padronização do código conforme as diretrizes estabelecidas.

