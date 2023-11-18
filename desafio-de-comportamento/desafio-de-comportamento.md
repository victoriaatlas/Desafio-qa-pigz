

##Descrição do Bug:
Ao cadastrar um entregador, o sistema permite a inserção de um CPF inválido, finalizando o cadastro sem exibir mensagens de erro.


### Passos para Reproduzir o Bug:


 - Acesse a página de cadastro de entregadores.
 - Preencha o formulário com informações de um entregador, incluindo um CPF inválido.
 - Clique no botão "Enviar" para finalizar o cadastro.
 - Verifique que o sistema aceita o CPF inválido e conclui o cadastro sem exibir mensagens de erro.

### Prioridade do Bug:
__Alta__


### Possíveis Impactos no Sistema:


 - Segurança e Confidencialidade: A possibilidade de cadastrar entregadores sem CPF válido compromete a segurança do serviço, permitindo a entrada de informações falsas ou inconsistentes.
 - Integridade dos Dados: CPFs inválidos podem impactar negativamente a integridade dos dados cadastrados no sistema.
 - Integração com Ferramentas Externas: O bug pode afetar a integração com outras ferramentas, como o sistema de emissão de notas fiscais, ao permitir o cadastro de entregadores com informações inconsistentes.





## Após a criação do card no JIRA relatando o bug no cadastro de entregadores, eu seguiria os seguintes passos:


1. Notificaria o desenvolvedor responsável(Bruno):
   - Enviaria uma mensagem direta para Bruno, informando a existencia do bug, caso necessario,explicaria sobre o bug;
   - Atribuiria o card ao desenvolvedor;
   - Solicitaria ao Bruno uma avaliação do bug, e uma estimativa de tempo para solução do problema.


2. Acompanharia o desenvolvimento:
   - Materia um contato regular com Bruno para acompanhar o progresso;
   - Certificaria se Bruno, tem todas as informações necessarias para a correção do bug de maneira eficaz.


3.Comunicaria a Gerente de Projeto(Carol):
   - Enviaria uma notificação informando sobre o bug encontrado, incluido detalhes sobre o impacto do bug;
   - Explicaria a prioridade da correção do bug e a ação planejada para a correção.
   - Discutiria (caso necessario) um ajuste no cronograma do projeto.


4.Participaria de Reuniões de Acompanhamento:
   - Participaria de reuniões regulares da equipe para discutir o progresso da correção do bug para manter a gerencia informada em caso de possiveis atrasos ou imprevistos.


5.Comunicaria a equipe de teste(caso exista):
   - Caso haja uma equipe de testes, compartilharia informações sobre o bug para que possamos incluir testes específicos durante e após a correção


6.Atualizaria o Status no JIRA:
   - Manter o status do card atualizado no JIRA conforme as etapas são concluídas.


7.Fecharia o card(em caso de conclusão):
   - Após a correção do bug, verificar se o problema foi resolvido.
   - Testar a funcionalidade para garantir que a correção não introduziu novos problemas.
   - Fechar o card no JIRA, indicando a conclusão do trabalho.
