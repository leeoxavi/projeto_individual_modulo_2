**Banco de Dados para o Sistema RESILIADATA**

Este repositório contém a modelagem e implementação de um banco de dados para o sistema RESILIADATA, que visa auxiliar na avaliação das tecnologias utilizadas pelas empresas parceiras e seus colaboradores.

**Descrição do Projeto**

O sistema RESILIADATA requer um banco de dados robusto para armazenar informações essenciais sobre empresas parceiras, tecnologias utilizadas e colaboradores associados. A modelagem do banco de dados inclui três entidades principais: Empresa, Tecnologia e Colaborador, com seus respectivos campos e relacionamentos.

**Entidades e Campos**

**Empresa**

- ID: Identificador único da empresa.
- Nome: Nome da empresa.
- Setor: Setor de atuação da empresa.
- Localização: Localização da empresa.

**Tecnologia**

- ID: Identificador único da tecnologia.
- Nome: Nome da tecnologia.
- Área: Área de aplicação da tecnologia.

**Colaborador**

- ID: Identificador único do colaborador.
- Nome: Nome do colaborador.
- Cargo: Cargo do colaborador na empresa.
- Empresa_ID: Chave estrangeira referenciando a empresa à qual o colaborador pertence.

**Relacionamentos**

- **Empresa -> Tecnologia:** Relacionamento um para muitos, onde uma empresa pode utilizar várias tecnologias.
- **Empresa -> Colaborador:** Relacionamento um para muitos, onde uma empresa pode ter vários colaboradores.

**Como Usar**
O banco de dados pode ser implementado em um sistema de gerenciamento de banco de dados relacional (ex: MySQL, PostgreSQL). Os arquivos SQL para criação das tabelas e inserção dos dados simulados estão disponíveis neste repositório.
