# 🧩 Product Backlog

Documentação dos **Requisitos Funcionais (RF)** e **Requisitos Não Funcionais (RNF)** do sistema de atendimento técnico com Inteligência Artificial.

---

## 📘 Requisitos Funcionais (RF)

| Código | Título | Definição |
|:-------|:--------|:-----------|
| **RF001** | Autenticar Usuário | Devido à hierarquia de acesso, todos os usuários devem fazer login antes de operar o sistema. |
| **RF002** | Abrir Chamado | Usuário, após fazer login, pode abrir nova requisição de atendimento clicando em “Abrir Chamado”. |
| **RF003** | Preencher Formulário | Após selecionar “Abrir Chamado”, o usuário descreve seu problema com o máximo de detalhes possível e o formulário será analisado pela IA. |
| **RF004** | Avaliar Solução | Se o problema for resolvido, as informações vão para o banco de dados; caso contrário, a IA encaminhará ao técnico responsável. |
| **RF005** | Verificar Chamado | Após login, o usuário pode consultar o status do chamado atual ou o histórico de chamados antigos. |
| **RF006** | Cancelar Chamado | O usuário pode cancelar sua solicitação de atendimento, devendo justificar o motivo do cancelamento. |
| **RF007** | Categorizar Chamado | A IA categoriza o chamado conforme a descrição do problema, associando-o ao setor adequado (software, hardware, infraestrutura, etc). |
| **RF008** | Sugerir Solução | A IA busca soluções possíveis no banco de dados a partir das palavras-chave da descrição do problema. |
| **RF009** | Priorizar Chamado | Antes do encaminhamento, a IA define o nível de prioridade com base em informações do banco de dados. |
| **RF010** | Encaminhar Chamado | Se a IA não encontrar solução, o chamado é encaminhado ao técnico do setor correspondente. Caso o cliente informe que a solução sugerida não funcionou, o chamado também é encaminhado. |
| **RF011** | Diagnosticar Chamado | O técnico visualiza chamados encaminhados, entra em contato com o cliente, analisa o problema e registra o diagnóstico. |
| **RF012** | Confirmar Solução | O técnico deve informar ao sistema a conclusão do chamado para atualizar seu status. |
| **RF013** | Excluir Chamado | O administrador pode excluir chamados em situações excepcionais. |
| **RF014** | Gerar Relatório Mensal | O administrador pode gerar relatório de 30 dias com informações como volume de chamados, por técnico, cliente, setor e prioridade. |
| **RF015** | Gerar Relatório Semestral | Gera relatório cobrindo o período de 180 dias. |
| **RF016** | Gerar Relatório Anual | Gera relatório cobrindo o período de 365 dias. |
| **RF017** | Exportar Relatório | Relatórios gerados devem ser exportáveis em formato Excel. |
| **RF018** | Editar Usuário | O administrador pode editar dados de usuários (empresa, cargo, contato, nome). |
| **RF019** | Adicionar Usuário | O administrador pode cadastrar novos usuários com diferentes níveis de acesso. |
| **RF020** | Excluir Usuário | O administrador pode excluir usuários em casos de desligamento ou fim de contrato. |

---

## ⚙️ Requisitos Não Funcionais (RNF)

| Código | Título | Definição |
|:-------|:--------|:-----------|
| **RNF0001** | Reconhecimento e Prevenção de Erros | Confirmações antes de ações críticas, avisos sobre formulários incompletos e opções de cancelamento para evitar erros do usuário. |
| **RNF0002** | Ajuda e Documentação | O sistema deve disponibilizar manual do usuário com instruções de uso corretas e recomendadas. |
| **RNF0003** | Manutenibilidade e Rastreabilidade | O código deve possuir arquitetura modular e rastreável, facilitando manutenção e auditoria. |
| **RNF0004** | Usabilidade | O produto deve ser intuitivo, fácil de aprender e operar, sem depender completamente do manual. |
| **RNF0005** | Hierarquia de Acesso | Diferenciação dos níveis de acesso conforme o papel do usuário na empresa. |
| **RNF0006** | Implementação de Testes | O sistema deve possuir testes unitários e de usabilidade para garantir qualidade e desempenho. |
