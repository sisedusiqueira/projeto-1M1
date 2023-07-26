# Diagrama caso de uso
**Apresentação: Sistema de Automação de Documentos do Registro Acadêmico - IFB Campus São Sebastião**

Diagrama de Caso de Uso - Sistema de Automação de Documentos do Registro Acadêmico do IFB - Campus São Sebastião

[Diagrama de caso de uso](https://app.diagrams.net/?libs=general;uml&src=about#G1Dn_0xKC-Fd_6IFnM6_AO9LEbQxmbTNWJ)

![image](https://github.com/sisedusiqueira/projeto-1M1/assets/138258723/ff626f28-faa7-4e21-8c93-020db1399358)

Aqui está o diagrama de caso de uso para o sistema de automação de documentos do Registro Acadêmico do IFB - Campus São Sebastião, com os perfis de aluno, administrador e secretaria:

Diagrama de Caso de Uso: Automação de Documentos do Registro Acadêmico

Perfis de Acesso:
- Aluno
- Funcionário da Secretaria
- Administrador

Casos de Uso:
1. Login
2. Cadastro no Sistema (Aluno)
3. Resetar Senha (Aluno)
4. Gerenciar Solicitações (Aluno)
5. Solicitar Declaração (Aluno)
6. Renovação de Matrícula (Aluno)
7. Trancamento (Aluno)
8. Emissão de Diploma (Aluno)
9. Login (Funcionário da Secretaria)
10. Gerenciar Matrículas (Funcionário da Secretaria)
11. Login (Administrador)
12. Gerenciar Permissões (Administrador)

Associações:
- Aluno:
   - Realiza os casos de uso: Login, Cadastro no Sistema (Aluno), Resetar Senha (Aluno), Gerenciar Solicitações (Aluno), Solicitar Declaração (Aluno), Renovação de Matrícula (Aluno), Trancamento (Aluno), Emissão de Diploma (Aluno)

- Funcionário da Secretaria:
   - Realiza os casos de uso: Login (Funcionário da Secretaria), Gerenciar Matrículas (Funcionário da Secretaria)

- Administrador:
   - Realiza os casos de uso: Login (Administrador), Gerenciar Permissões (Administrador)

Diagrama:
        +--------------------+
        |    Aluno           |
        +--------------------+
           |   |   |   |   |   |   |   |   |   |
           |   |   |   |   |   |   |   |   |   +-------------------------+
           |   |   |   |   |   |   |   |   +---------------------------+ |
           |   |   |   |   |   |   |   +-----------------------------+ | |
           |   |   |   |   |   |   +-------------------------------+ | | |
           |   |   |   |   |   +---------------------------------+ | | |
           |   |   |   |   +-----------------------------------+ | | |
           |   |   |   +-------------------------------------+ | | |
           |   |   +---------------------------------------+ | | |
           |   +-----------------------------------------+ | | |
           +-------------------------------------------+ | | |
                                                         | | |
        +--------------------+                           | | |
        | Funcionário da     |                           | | |
        |    Secretaria      |                           | | |
        +--------------------+                           | | |
                                                         | | |
        +--------------------+                           | | |
        |   Administrador    | -------------------------+ | |
        +--------------------+                           | |
                                                         | |
        +--------------------+                           | |
        |       Aluno        | -------------------------+ |
        +--------------------+                             |
                                                           |
                                                           |
                                                           |
                                                 +-----------------------+
                                                 |     Sistema          |
                                                 +-----------------------+
