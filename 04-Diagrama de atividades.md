# Diagrama de Atividades
**Apresentação: Sistema de Automação de Documentos do Registro Acadêmico - IFB Campus São Sebastião**

[Diagrama de Atividades](#)

Diagrama de Caso de Uso - Sistema de Automação de Documentos do Registro Acadêmico do IFB - Campus São Sebastião

**Atores (Perfis de Acesso):**
1. Aluno
2. Funcionário da Secretaria

**Casos de Uso (Serviços Disponibilizados):**
1. Login
2. Cadastro no Sistema (Aluno)
3. Gerenciar Matrículas
4. Solicitar Declaração
5. Renovação
6. Trancamento
7. Emissão de Diploma
8. Resetar Senha

**Descrição dos Casos de Uso:**

1. **Login:**
   - Descrição: Permite que os atores (Aluno e Funcionário da Secretaria) façam login no sistema para acessar suas funcionalidades específicas.
   - Fluxo Principal: O ator informa seu nome de usuário e senha para autenticação no sistema.
   - Fluxo Alternativo: Se as credenciais forem inválidas, uma mensagem de erro é exibida.

2. **Cadastro no Sistema (Aluno):**
   - Descrição: Permite que o Aluno faça o seu cadastro no sistema para obter acesso às funcionalidades disponíveis.
   - Fluxo Principal: O Aluno preenche os campos obrigatórios (nome, matrícula, curso, etc.) para criar sua conta no sistema.

3. **Gerenciar Matrículas:**
   - Descrição: Permite que o Funcionário da Secretaria gerencie as matrículas dos alunos, incluindo inscrições, alterações e exclusões de disciplinas.
   - Fluxo Principal: O Funcionário da Secretaria acessa a área de gerenciamento de matrículas e realiza as ações necessárias.

4. **Solicitar Declaração:**
   - Descrição: Permite que o Aluno solicite uma declaração ao sistema, que pode ser de conclusão de curso, de matrícula, de histórico acadêmico, entre outras.
   - Fluxo Principal: O Aluno seleciona o tipo de declaração desejada e a solicita ao sistema.

5. **Renovação:**
   - Descrição: Permite que o Aluno solicite a renovação de sua matrícula para o próximo período letivo.
   - Fluxo Principal: O Aluno acessa a opção de renovação de matrícula e segue as etapas necessárias para concluir o processo.

6. **Trancamento:**
   - Descrição: Permite que o Aluno solicite o trancamento de sua matrícula, interrompendo temporariamente seus estudos.
   - Fluxo Principal: O Aluno acessa a opção de trancamento e segue as etapas necessárias para concluir o processo.

7. **Emissão de Diploma:**
   - Descrição: Permite que o Aluno solicite a emissão de seu diploma após a conclusão do curso.
   - Fluxo Principal: O Aluno acessa a opção de emissão de diploma e segue as etapas necessárias para solicitar o documento.

8. **Resetar Senha:**
   - Descrição: Permite que o Aluno redefina sua senha em caso de esquecimento ou necessidade de alteração.
   - Fluxo Principal: O Aluno solicita a redefinição de senha, informa seu e-mail cadastrado e recebe um link para criar uma nova senha.

O diagrama de caso de uso representa a interação entre os atores e as funcionalidades do sistema. Ele fornece uma visão geral dos serviços disponibilizados e das ações que cada ator pode realizar. Essa ferramenta auxilia no entendimento das principais funcionalidades do sistema de automação de documentos do Registro Acadêmico do IFB - Campus São Sebastião, permitindo uma visualização clara das interações entre os usuários e o software.

Diagrama de Atividades: Automação de Documentos do Registro Acadêmico

+-----------------------------------+
| Início                            |
+-----------------------------------+
| 1. Solicitar Login                |
| 2. Realizar Login                 |
| 3. Verificar Perfil de Acesso     |
+-----------------------------------+
       |
       v
+-----------------------------------+
| Verificar Permissões             |
+-----------------------------------+
| Se Aluno:                         |
|   - Mostrar Opções do Aluno       |
|   - Escolher Ação                |
|   - Realizar Ação                |
|   - Voltar ao Menu do Aluno       |
| Senão se Funcionário da Secretaria: |
|   - Mostrar Opções do Funcionário |
|   - Escolher Ação                |
|   - Realizar Ação                |
|   - Voltar ao Menu do Funcionário |
+-----------------------------------+
       |
       v
+-----------------------------------+
| Fim                               |
+-----------------------------------+
