### Espaço BK app
Repositório do trabalho de conclusão de curso para a loja Espaço BK.

## Índice
- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Instalação e Execução](#instalação-e-execução)
- [Documentação](#documentação)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Instalação](#Instalação)

## Sobre o Projeto
Este projeto foi desenvolvido como o projeto final para a matéria de "Trabalho de conclusão do curso" de Ciência da computação pelos alunos Caetano Casagrande Castro e Miguel Serea com orientações da doutora Lidiane Visintin.
O sistema foi criado como um facilitador para a gestão de atividade, contato com o cliente e gerenciamento de colaboradores por meio da loja "Espaço BK". 

## Funcionalidades
- [Gestão de Tarefas](#gestão-de-tarefas)
- [Gestão de Usuários](#gestão-de-usuários)
- [Gestão de Metas Mensais](#gestão-de-metas-mensais)
- [Gestão de Clientes](#gestão-de-clientes)
- [Gestão de Vínculos Cliente-Funcionário](#gestão-de-vínculos-cliente-funcionário)
- [Gestão de Histórico de Compras](#gestão-de-histórico-de-compras)
- [Gestão de Campanhas](#gestão-de-campanhas)
- [Eventos do Sistema](#eventos-do-sistema)
- [Importações](#importações)
- [Login e Autenticação](#login-e-autenticação)
- [Requisitos Não Funcionais](#requisitos-não-funcionais)

# 1. Gestão de Tarefas
- Cadastrar, editar, excluir e visualizar tarefas.
- Perfis de acesso:
  - **Administrador:** todas as tarefas de todos os colaboradores.
  - **Gerente:** tarefas de todos os funcionários.
  - **Funcionário:** apenas suas próprias tarefas.

# 2. Gestão de Usuários
- Cadastro, edição, exclusão e visualização de usuários.
- Troca de senha.
- Perfis de acesso diferenciados: Administrador, Gerente e Funcionário.

# 3. Gestão de Metas Mensais
- Cadastro, edição, exclusão e acompanhamento de metas.
- Visualização de metas individuais (Funcionário) ou de toda equipe (Administrador/Gerente).
- Gráficos de desempenho.

# 4. Gestão de Clientes
- Importação de clientes via planilhas.
- Prevenção de duplicidade (CPF e nome).
- Associação de clientes a colaboradores.
- Visualização de clientes vinculados.

# 5. Gestão de Vínculos Cliente-Funcionário
- Associação, edição, exclusão e visualização de vínculos.
- Permite que colaboradores vejam apenas seus clientes vinculados.

# 6. Gestão de Histórico de Compras
- Importação de histórico de compras.
- Prevenção de duplicidade.
- Visualização de histórico por colaboradores.

# 7. Gestão de Campanhas
- Cadastro, edição, exclusão e visualização de campanhas.
- Upload de imagens (JPG, PNG) para campanhas.
- Definição de data de validade.
- Envio de campanhas para colaboradores.

# 8. Eventos do Sistema
- Notificação de aniversários de clientes.
- Avisos de cashback (nos dias 5, 15 e 3 dias antes do final do mês).

# 9. Importações
- Importação de clientes e histórico de compras.
- Atualização de dados evitando duplicidade.

# 10. Login e Autenticação
- Acesso via usuário e senha.
- Perfis com permissões diferenciadas.

# 11. Requisitos Não Funcionais
- Sistema responsivo (desktop e mobile).
- Segurança via autenticação.
- Armazenamento de imagens compatíveis (JPG/PNG).

## Estrutura do Projeto
- Front-end: React, TailwindCSS, CSS, HTML, JavaScript, TypeScript, NodeJS.
- Back-end: Python, Django, Mongosh. 

## Instalação, execução e pré-requisitos
- Pré-requisitos:
  Node >= 24.0.2
  React >= 18.3.1
  React-dom >= 18.3.1
  TailwindCSS >= 3.4.10

- Execução:

- Instalação:

## Documentação 
Todos os dados do projeto incluindo tecnologias empregadas, arquitetura do projeto, requisitos do sistema, diagramas de caso de uso, modelagem deo banco de dados e entre outros estão disponíveis em: https://drive.google.com/file/d/1qqaGu4F0fKq2nuB2I6pK9z8-Ox0EC_m0/view?usp=drive_link


