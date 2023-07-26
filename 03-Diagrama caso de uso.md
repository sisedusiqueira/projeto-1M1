# Diagrama caso de uso
**Apresentação: Sistema de Automação de Documentos do Registro Acadêmico - IFB Campus São Sebastião**

*Bom dia a todos!*
Hoje, tenho o prazer de apresentar a vocês o nosso projeto de Sistema de Automação de Documentos para o Registro Acadêmico do Instituto Federal de Brasília - Campus São Sebastião. Esse sistema tem como objetivo simplificar e otimizar o processo de emissão e gerenciamento de documentos acadêmicos para alunos e equipe administrativa.

**Contexto do Projeto:**
- Nosso sistema será desenvolvido para atender aos seguintes atores: Aluno, Funcionário da Secretaria e Administrador.
- Cada ator terá acesso a funcionalidades específicas de acordo com seu perfil de acesso no sistema.
- Os principais serviços disponibilizados pelo sistema são: Login, Cadastro no Sistema, Cadastro de Atestados Médicos, Renovação de Matrículas, Emissão de Diplomas, Assinatura de Contrato de Estágio, Solicitar Declarações ou Histórico, Trancamento, Analisar Solicitações, Gerenciar Matrículas e Emissão de Documentos.

**Diagrama de Casos de Uso:**
[Apresentar o diagrama de casos de uso no projetor ou tela.]

**Explicação do Diagrama de Casos de Uso:**
- Como podemos ver no diagrama, temos três perfis de usuários: Aluno, Funcionário da Secretaria e Administrador.
- Cada um desses perfis possui uma lista de funcionalidades disponíveis para eles.
- O caso de uso "Login" é a primeira etapa para acessar o sistema e permitir que os usuários autenticados utilizem as demais funcionalidades.
- O caso de uso "Cadastro no Sistema" é necessário tanto para os Alunos quanto para os Funcionários da Secretaria e o Administrador. É o processo de registro no sistema para obter um acesso seguro.
- A partir do "Login" e do "Cadastro no Sistema", os atores terão acesso aos demais serviços, como Cadastro de Atestados Médicos, Renovação de Matrículas, Emissão de Diplomas, entre outros.
- Funcionários da Secretaria e o Administrador podem realizar tarefas administrativas adicionais, como Analisar Solicitações, Gerenciar Matrículas e Emissão de Documentos.

**Benefícios do Sistema:**
- Para os alunos, o sistema oferece maior comodidade ao possibilitar a solicitação de documentos de forma ágil e online, reduzindo a necessidade de deslocamento físico.
- Para a equipe da Secretaria, a automação dos processos agiliza a análise e o gerenciamento das solicitações dos alunos, melhorando a eficiência administrativa.
- A plataforma também permite que os administradores tenham uma visão geral das atividades do sistema, facilitando o monitoramento e controle do processo.
  

Neste projeto foram definidos três perfis de acesso (atores): 

* Aluno, Funcionário da Secretaria e Administrador do Sistema.


Os serviços disponibilizados pelo sistema foram identificados como casos de uso e são os seguintes:

* 1. Login: Permite que os atores Aluno, Funcionário da Secretaria e Administrador acessem o sistema autenticando-se.
* 2. Cadastro no Sistema (Aluno): Permite que o Aluno realize o seu cadastro no sistema, fornecendo suas informações pessoais e acadêmicas.
* 3. Cadastro no Sistema (Funcionário da Secretaria): Permite que o Funcionário da Secretaria realize o seu cadastro no sistema, fornecendo suas informações de * funcionário.
* 4. Cadastro no Sistema (Administrador): Permite que o Administrador do Sistema realize o seu cadastro no sistema, fornecendo suas informações de administrador.
* 5. Cadastro de Atestados Médicos: Permite que o Aluno envie atestados médicos ao sistema, justificando ausências e solicitação de abono de faltas.
* 6. Renovação de Matrículas: Permite que o Aluno renove sua matrícula para o próximo período letivo.
* 7. Emissão de Diplomas: Permite que o Aluno solicite a emissão do diploma após conclusão do curso.
* 8. Assinatura - Contrato de Estágio: Permite que o Aluno assine o contrato de estágio, caso seja necessário para o curso.
* 9. Solicitar Declarações ou Histórico: Permite que o Aluno solicite declarações ou histórico acadêmico.
* 10. Trancamento: Permite que o Aluno solicite o trancamento temporário de sua matrícula.
* 11. Analisar Solicitações: Permite que o Funcionário da Secretaria analise as solicitações feitas pelos Alunos.
* 12. Gerenciar Matrículas: Permite que o Funcionário da Secretaria gerencie as matrículas dos Alunos, realizando matrículas, transferências, trancamentos, entre outras ações.
* 13. Emissão de Documentos: Permite que o Funcionário da Secretaria emita documentos acadêmicos, como declarações, históricos, diplomas, entre outros.

As associações entre atores e casos de uso definem quais atores têm permissão para executar cada caso de uso específico. Por exemplo, o ator Aluno tem permissão para executar casos de uso relacionados ao cadastro, solicitações de documentos e gerenciamento de matrículas. O ator Funcionário da Secretaria tem permissão para analisar solicitações e gerenciar matrículas. O ator Administrador tem acesso ao gerenciamento do sistema.

O diagrama de interação detalha como os atores interagem com os casos de uso do sistema. Cada ator tem sua própria interação com os casos de uso pertinentes ao seu perfil de acesso. O fluxo de interação pode envolver a entrada de informações, realização de ações específicas e visualização de resultados.

É importante ressaltar que o diagrama de interação é uma representação gráfica simplificada das interações, e a implementação real do sistema pode envolver mais detalhes e etapas específicas para cada caso de uso.

