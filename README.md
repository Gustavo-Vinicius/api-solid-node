# App

Gympass style app.

## RFs (Requsitos funcionais)

-   [ ] DEVE SER POSSÍVEL SE CADASTRAR ;
-   [ ] DEVE SER POSSÍVEL SE AUTENTICAR ;
-   [ ] DEVE SER POSSÍVEL OBTER O PERFIL DE UM USUÁRIO LOGADO ;
-   [ ] DEVE SER POSSÍVEL OBTER O NÚMERO DE CHECK-INS REALIZADOS PELO USUÁRIO LOGADO ;
-   [ ] DEVE SER POSSÍVEL O USUÁRIO OBTER SEU HISTÓRICO DE CHECK-INS ;
-   [ ] DEVE SER POSSÍVEL O USUÁRIO BUSCAR ACADEMIAS PRÓXIMAS ;
-   [ ] DEVE SER POSSÍVEL O USUÁRIO BUSCAR ACADEMIAS PELO NOME ;
-   [ ] DEVE SER POSSÍVEL O USUÁRIO REALIZAR CHECK-IN EM UMA ACADEMIA ;
-   [ ] DEVE SER POSSÍVEL VALIDAR O CHECK-IN DE UM USUÁRIO ;
-   [ ] DEVE SER POSSÍVEL VALIDAR O CHECK-IN DE UM USUÁRIO ;
-   [ ] DEVE SER POSSÍVEL CADASTRAR UMA ACADEMIA ;

## RNs (Regras de negócio)

-   [ ] O USUÁRIO NÃO DEVE PODER SE CADASTRAR COM UM E-MAIL DUPLICADO ;
-   [ ] O USUÁRIO NÃO PODE FAZER 2 CHECK-INS NO MESMO DIA ;
-   [ ] O USUÁRIO NÃO PODE FAZER CHECK-IN SE NÃO ESTIVER PERTO (100M) DA ACADEMIA ;
-   [ ] O CHECK-IN SÓ PODE SER VALIDADO ATÉ 20 MINUTOS APÓS CRIADO ;
-   [ ] O CHECK-IN SÓ PODE SER VALIDADO POR ADMISTRADORES ;
-   [ ] A ACADEMIA SÓ PODE SER CADASTRADA POR ADMINISTRADORES ;

## RNFs (Requisitos não-funcionais)

-   [ ] A SENHA DO USUARIO PRECISA ESTÁ CRIPTOGRAFADA ;
-   [ ] OS DADOS DA APLICAÇÃO PRECISAM ESTAR PERSISTIDOS EM UM BANCO POSTGRESQL ;
-   [ ] TODAS LISTAS DE DADOS PRECISAM ESTAR PAGINADAS COM 20 ITENS POR PÁGINA ;
-   [ ] USUÁRIO DEVE SER IDENTIFICADOS POR UM JWT (JSON WEB TOKEN) ;