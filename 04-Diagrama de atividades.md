# Diagrama de Atividades
**Apresentação: Sistema de Automação de Documentos do Registro Acadêmico - IFB Campus São Sebastião**

[Diagrama de Atividades](#)

Aqui está o diagrama de atividades com base nas informações fornecidas:

```
Diagrama de Atividades: Automação de Documentos do Registro Acadêmico

Atividades:
1. Iniciar
2. Realizar Login
3. Verificar Perfil do Usuário
4. Aluno: Cadastro no Sistema
5. Aluno: Resetar Senha
6. Aluno: Gerenciar Solicitações
7. Aluno: Solicitar Declaração
8. Aluno: Renovação de Matrícula
9. Aluno: Trancamento
10. Aluno: Emissão de Diploma
11. Funcionário da Secretaria: Login
12. Funcionário da Secretaria: Gerenciar Matrículas
13. Administrador: Login
14. Administrador: Gerenciar Permissões
15. Encerrar

Decisões:
- Aluno, Funcionário da Secretaria ou Administrador?

Fluxo de Atividades:
Iniciar -> Realizar Login -> Verificar Perfil do Usuário
            |
            v
     Aluno, Funcionário da Secretaria ou Administrador?
            |
            v
        Aluno -> Cadastro no Sistema -> Encerrar
        Aluno -> Resetar Senha -> Encerrar
        Aluno -> Gerenciar Solicitações -> Solicitar Declaração -> Encerrar
                                 |--> Renovação de Matrícula -> Encerrar
                                 |--> Trancamento -> Encerrar
                                 |--> Emissão de Diploma -> Encerrar
        Funcionário da Secretaria -> Gerenciar Matrículas -> Encerrar
        Administrador -> Gerenciar Permissões -> Encerrar
```

Neste diagrama de atividades, representamos o fluxo geral das atividades do sistema de automação de documentos do Registro Acadêmico. A atividade "Iniciar" dá início ao processo, seguido pela atividade "Realizar Login", onde o usuário deve fornecer suas credenciais para acessar o sistema. Em seguida, a atividade "Verificar Perfil do Usuário" determina se o usuário é um Aluno, Funcionário da Secretaria ou Administrador.

Dependendo do perfil do usuário, o fluxo seguirá para as atividades específicas para cada perfil. O Aluno pode realizar atividades como cadastrar-se no sistema, resetar senha, gerenciar solicitações, solicitar declarações, renovar matrícula, trancar matrícula e emitir diploma. O Funcionário da Secretaria pode realizar a atividade de gerenciar matrículas, e o Administrador pode gerenciar permissões no sistema.

Após a conclusão das atividades específicas de cada perfil, o fluxo segue para a atividade "Encerrar", que finaliza o processo.
