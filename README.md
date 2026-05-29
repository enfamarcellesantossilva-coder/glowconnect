# glowconnect
Plataforma que conecta influencers e marcas para realização de parcerias, campanhas e divulgação de produtos. Plataforma de Influenciadores e Marcas

Plataforma desenvolvida em JavaEE com o objetivo de conectar influenciadores digitais, criadores de conteúdo e marcas, permitindo a gestão de campanhas, propostas de colaboração, comunicação entre utilizadores e acompanhamento de parcerias.

Objetivo do Projeto

O sistema foi concebido para criar um ambiente centralizado, seguro e organizado onde marcas possam divulgar campanhas e influenciadores possam encontrar oportunidades de colaboração de forma simples e eficiente.

Funcionalidades Principais Registo e autenticação de utilizadores Gestão de perfis de influenciadores e marcas Publicação e gestão de campanhas Sistema de candidaturas Aprovação e rejeição de propostas Comunicação entre utilizadores Dashboard com métricas e informações relevantes Histórico de campanhas e interações Tecnologias Utilizadas JavaEE JSP Servlet Bootstrap MySQL HTML5 CSS3 JavaScript Git Maven Arquitetura do Sistema

O projeto segue arquitetura em camadas:

Camada de Apresentação (JSP + Bootstrap) Camada de Negócio (JavaEE) Camada de Persistência (DAO + MySQL) Estrutura do Projeto src/ │ ├── controller/ ├── model/ ├── dao/ ├── service/ ├── utils/ │ webapp/ ├── views/ ├── css/ ├── js/ └── WEB-INF/ Requisitos Funcionais Registo de utilizadores Login e logout Criação e edição de perfis Publicação de campanhas Candidaturas a campanhas Sistema de mensagens Dashboard administrativo Gestão de campanhas Requisitos Não Funcionais Segurança de dados Interface intuitiva Escalabilidade Boa performance Compatibilidade web e desktop Fácil manutenção Base de Dados

Principais entidades:

Utilizador Perfil Campanha Proposta Mensagem Sessão Fluxo do Sistema Utilizador realiza login Sistema valida credenciais Dashboard é carregado Utilizador interage com campanhas e mensagens Dados são persistidos em MySQL Metodologia

O projeto segue a metodologia Cascata, com organização sequencial das etapas de desenvolvimento.

Ferramentas Utilizadas Git GitHub Excel MS Teams OpenAI ChatGPT Google Gemini Autor

Marcelle Silva

Instituição

IEFP

Licença

Este projeto foi desenvolvido para fins académicos e educacionais.
