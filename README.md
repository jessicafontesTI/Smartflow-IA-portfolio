# 🚀 SmartFlow AI

### Sistema Web de Gestão de Solicitações Internas

O **SmartFlow AI** é uma aplicação web desenvolvida para centralizar, organizar e acompanhar solicitações entre departamentos de uma empresa.

O projeto nasceu da necessidade de substituir processos descentralizados por um ambiente único, permitindo maior **rastreabilidade, organização, segurança e acompanhamento das demandas internas**.

> 🔐 O código-fonte principal é mantido em repositório privado. Este repositório apresenta a documentação e demonstração do projeto para fins de portfólio.

---

## 🎯 Objetivo do Projeto

Centralizar solicitações internas de diferentes departamentos em uma única aplicação, permitindo acompanhar todo o ciclo de vida de uma demanda, desde sua abertura até a conclusão.

O sistema foi projetado inicialmente para departamentos como:

- 💻 TI
- 👥 Recursos Humanos
- 🛒 Compras
- 💰 Financeiro

---

## ✨ Principais Funcionalidades

- 🔐 Autenticação de usuários
- 👤 Controle de acesso por perfil
- 🏢 Gestão de departamentos
- 🗂️ Gestão de categorias
- 🎫 Abertura e acompanhamento de solicitações
- ⚡ Definição de prioridade
- 🔄 Controle de status
- 👨‍💻 Atribuição de responsáveis
- 📊 Dashboard com indicadores
- 🔎 Filtros e consultas
- 🗑️ Exclusão lógica (Soft Delete)
- ♻️ Restauração de registros
- 📜 Auditoria de alterações
- 📤 Exportação de dados
- 🔑 Troca obrigatória de senha no primeiro acesso
- ⏱️ Controle de sessão por inatividade

---

## 👥 Perfis de Acesso

### 👑 Administrador

Possui acesso administrativo ao sistema, incluindo gerenciamento de usuários, departamentos, categorias e acompanhamento das solicitações.

### 👤 Operador

É vinculado a um departamento e pode abrir solicitações para outros setores, acompanhar demandas e atuar nas solicitações relacionadas ao seu departamento conforme suas permissões.

---

## 🛠️ Tecnologias Utilizadas

### Backend

- PHP 8.2
- Arquitetura MVC
- PDO
- MySQL / MariaDB

### Frontend

- HTML5
- CSS3
- JavaScript
- Bootstrap 5

### Infraestrutura e Deploy

- Git
- GitHub
- GitHub Actions
- SSH
- Linux
- Hospedagem Web
- Deploy automatizado

---

## 🔄 Fluxo Simplificado

```text
Usuário
   ↓
Autenticação
   ↓
SmartFlow AI
   ↓
Controller
   ↓
Regras de Negócio
   ↓
Model
   ↓
MySQL / MariaDB
```

---

## 🔐 Segurança

Durante o desenvolvimento foram consideradas práticas como:

- senhas armazenadas utilizando hash;
- consultas preparadas com PDO;
- proteção CSRF;
- controle de acesso baseado em perfil;
- gerenciamento seguro de sessões;
- cookies de sessão protegidos;
- validação de dados no backend;
- escape de saída contra XSS;
- proteção de arquivos de configuração;
- credenciais fora do controle de versão;
- auditoria das principais alterações;
- exclusão lógica para preservação do histórico.

---

## 🗄️ Banco de Dados

O projeto utiliza **MySQL/MariaDB** e possui sistema próprio de migrations para criação e evolução da estrutura do banco de dados.

Entre as informações gerenciadas estão:

- usuários;
- departamentos;
- categorias;
- solicitações;
- configurações;
- registros de auditoria.

As migrations foram projetadas para serem executadas de forma controlada também no ambiente de produção.

---

## 🚀 CI/CD e Deploy

O projeto possui um fluxo de deploy utilizando **GitHub Actions + SSH**.

Fluxo:

```text
Desenvolvimento Local
        ↓
       Git
        ↓
      GitHub
        ↓
 GitHub Actions
        ↓
       SSH
        ↓
Servidor Linux
        ↓
 SmartFlow AI
```

O código da aplicação é mantido em um repositório privado e o processo de deploy envia somente os arquivos necessários para o ambiente de produção.

---

## 🌐 Aplicação em Produção

O SmartFlow AI possui uma versão funcional publicada na web.

🔗 **Aplicação:**  
https://jessicafontes.alwaysdata.net/

> Por se tratar de um sistema corporativo, o acesso às funcionalidades internas exige autenticação.

---

## 📸 Demonstração

Em breve esta seção contará com imagens das principais funcionalidades:

- Tela de Login
- Dashboard
- Fila de Solicitações
- Abertura de Solicitação
- Gestão de Usuários
- Gestão de Departamentos
- Auditoria

---

## 🧠 Evolução do Projeto

A arquitetura foi preparada pensando na evolução futura do sistema.

Entre as possibilidades estudadas estão:

- classificação inteligente de solicitações;
- triagem utilizando Inteligência Artificial;
- sugestões automáticas;
- análise dos dados das solicitações;
- integração com modelos de IA.

Essas funcionalidades não fazem parte da versão atual e representam possibilidades de evolução do projeto.

---

## 💡 Competências Aplicadas

Este projeto permitiu aplicar conhecimentos de:

`PHP` `MySQL` `MariaDB` `JavaScript` `HTML` `CSS` `Bootstrap` `MVC` `Git` `GitHub` `GitHub Actions` `Linux` `SSH` `Segurança Web` `Banco de Dados` `CI/CD`

---

## 👩‍💻 Desenvolvido por

**Jéssica Fontes**

Estudante de Análise e Desenvolvimento de Sistemas, com foco em Desenvolvimento de Software, Cloud Computing e Inteligência Artificial.
