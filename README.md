# Sistema Open Source para Controle de Equipamentos e Inventário de Laboratórios

## 📘 Sobre o Projeto

Este projeto é uma iniciativa **Open Source** com foco em uso
**acadêmico**, voltado para o gerenciamento de equipamentos, reagentes,
consumíveis e inventário em **laboratórios de química e biologia**. O
sistema busca oferecer uma solução completa e acessível para
instituições de ensino e pesquisa que precisam organizar recursos,
controlar empréstimos e registrar movimentações.

## 🎯 Objetivos

-   Facilitar o controle de equipamentos e materiais de laboratório.
-   Registrar entradas, saídas, empréstimos e devoluções.
-   Fornecer um ambiente seguro com diferentes níveis de acesso.
-   Possibilitar auditoria e rastreabilidade de todos os itens.
-   Criar uma base robusta e extensível para pesquisas e desenvolvimento
    acadêmico.

## 👥 Perfis de Usuário

O sistema inclui quatro perfis principais, cada um com permissões
específicas:

### **Aluno**

-   Solicitação de empréstimo de equipamentos.
-   Consulta ao inventário.
-   Visualização das próprias solicitações e histórico.

### **Moderador**

-   Aprovamento ou rejeição de solicitações.
-   Controle básico de registros de inventário.
-   Auxílio na mediação entre alunos e professores.

### **Professor**

-   Gerenciamento de aulas e práticas que utilizam os equipamentos.
-   Supervisão de solicitações e movimentações.
-   Acesso a relatórios avançados.

### **Administrador**

-   Controle total do sistema.
-   Cadastro e remoção de usuários.
-   Ajuste de permissões.
-   Configurações gerais e manutenção do servidor.

## 🖥️ Arquitetura do Sistema

O projeto foi idealizado com a seguinte estrutura:

### **Servidor Principal**

-   Aplicação centralizada responsável pelo backend.
-   Banco de dados de toda a instituição.
-   Autenticação e autorização.
-   Registro de logs e auditorias.

### **Computadores Clientes**

-   Interface para usuários finais.
-   Comunicação direta com o servidor.
-   Operações de consulta, cadastro (dependendo do nível) e atualizações
    em tempo real.

## 🛠️ Tecnologias (Sugestões)

O projeto permite flexibilidade tecnológica, mas seguem algumas
recomendações: - **Backend**: Node.js, Python (Django/Flask/FastAPI), ou
Java (Spring). - **Frontend**: React, Vue ou Angular. - **Banco de
Dados**: PostgreSQL, MariaDB ou MongoDB. - **Comunicação**: API REST ou
GraphQL. - **Autenticação**: JWT, OAuth2 ou sistema próprio.

## 🌱 Status do Projeto

Este repositório é apenas a estrutura inicial para iniciar o
desenvolvimento. O sistema ainda está em sua fase de concepção.

## 🤝 Contribuições

Por ser um projeto aberto, contribuições são bem-vindas! Você pode
ajudar com: - Correções - Sugestões - Documentação - Desenvolvimento de
novas features

## 📬 Contato

Email: matheus.soares7648@gmail.com
Linkedin: https://www.linkedin.com/in/matheus-soares-809458307/

Caso queira discutir ideias, contribuir ou tirar dúvidas sobre o
projeto, fique à vontade para abrir uma issue ou pull request.
