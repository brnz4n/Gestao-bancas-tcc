# 🎓 AvaliaTCC - Frontend

> **Sistema Web para Gerenciamento de Bancas Avaliadoras de Trabalho de Conclusão de Curso.**

Este repositório contém o **protótipo de Alta Fidelidade (Frontend)** do sistema AvaliaTCC. O projeto visa modernizar e automatizar o controle de bancas de defesa, substituindo planilhas manuais por uma interface web responsiva, intuitiva e moderna.

---

## 📖 Sobre o Projeto

Baseado em pesquisa acadêmica sobre engenharia de software aplicada à gestão educacional, este projeto propõe uma interface para resolver problemas como:

* Conflitos de horários e salas nas defesas.
* Dificuldade na comunicação e agendamento entre coordenadores, professores e alunos.
* Organização e divulgação do cronograma para ouvintes.

**Nota:** Este projeto foca na camada de **apresentação (HTML/CSS/JS)**. A lógica de autenticação e persistência de dados é simulada via JavaScript para demonstração.

---

## 📂 Estrutura do Projeto

Abaixo, a descrição de cada arquivo presente no repositório e sua responsabilidade no sistema:

```
Gestao-bancas-tcc/
│
├── 📁 imagens/                 # Logotipos, ícones e assets gráficos
│
├── 🔐 Autenticação & Acesso
│   ├── index.html              # Landing Page / Página Inicial Pública
│   ├── login.html              # Tela de Login (Lógica JS para Aluno/Prof/Admin)
│   ├── cadastro.html           # Cadastro de novos usuários
│   ├── recuperaçao.html        # Tela de recuperação de senha
│   ├── sobre.html              # Informações institucionais sobre o sistema
│   └── recursos.html           # Página de ajuda ou recursos do sistema
│
├── 🎓 Área do Aluno & Ouvintes
│   ├── dashboard_aluno.html    # Painel do Aluno (Minha banca, certificados)
│   ├── ver_resumo.html         # Visualização de detalhes/resumo do TCC
│   ├── ouvinte.html            # Área específica para usuários ouvintes
│   ├── cadastro_ouvinte.html   # Formulário para registro de horas complementares
│   ├── bancas_disponiveis.html # Listagem de bancas abertas para inscrição
│   └── cronograma.html         # Visualização pública de datas e horários
│
├── 👨‍🏫 Área do Professor
│   └── dashboard_professor.html # Painel do Professor (Orientações e Avaliações)
│
├── 👔 Área Administrativa (Coordenador)
│   ├── dashboard_admin.html    # Dashboard com KPIs e gráficos gerais
│   ├── principal.html          # Gerenciamento (CRUD) de Bancas e Agendamentos
│   ├── Relatorios.html         # Gráficos estatísticos (Chart.js) e exportação
│   └── plataforma.html         # Configurações gerais da plataforma
│
└── 🎨 Estilos
    └── style.css               # Folha de estilos global e customizações Bootstrap

```

---

## ✨ Funcionalidades Visuais

### 1. Sistema de Login Simulado

O arquivo `login.html` possui um script que direciona o usuário para a dashboard correta baseada nas credenciais inseridas, simulando um backend real.

### 2. Gestão de Bancas (`principal.html`)

Interface para o coordenador visualizar, editar e excluir bancas, com verificação visual de conflitos de horário.

### 3. Relatórios Gráficos (`Relatorios.html`)

Integração com **Chart.js** para exibir métricas como:

* Bancas por curso.
* Taxa de aprovação/reprovação.
* Total de ouvintes inscritos.

### 4. Cronograma Público (`cronograma.html`)

Design limpo e acessível para que alunos e comunidade externa consultem as datas das defesas.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5** - Estrutura semântica.
* **CSS3** - Estilização customizada com conceito de **Glassmorphism** (`.card-glass`).
* **Bootstrap 5.3** - Grid system, componentes responsivos e modais.
* **JavaScript** - Manipulação do DOM, simulação de rotas e gráficos.
* **Chart.js** - Biblioteca para visualização de dados.
* **Boxicons** - Ícones vetoriais.

---

## 🚀 Como Executar

1. **Clone o repositório:**
```bash
https://github.com/brnz4n/Gestao-bancas-tcc

```


2. **Acesse a pasta:**
```bash
cd Gestao-bancas-tcc

```


3. **Abra o projeto:**
* Basta abrir o arquivo `login.html` ou `index.html` em qualquer navegador moderno (Chrome, Edge, Firefox).



---

## 🔑 Credenciais de Teste (Simulação)

Utilize os dados abaixo na tela de `login.html` para navegar entre os diferentes perfis:

| Perfil | E-mail | Senha | Arquivo de Destino |
| --- | --- | --- | --- |
| **Aluno** | `aluno@gmail.com` | `aluno123` | `dashboard_aluno.html` |
| **Professor** | `prof@gmail.com` | `prof123` | `dashboard_professor.html` |
| **Coordenador** | `coord@gmail.com` | `admin123` | `dashboard_admin.html` |

---

## 📚 Referência Acadêmica

Este projeto utiliza como base teórica os requisitos levantados no artigo:

* **Obra:** Desenvolvimento de Sistema Web para Gerenciamento de Bancas Avaliadoras de Trabalho de Conclusão de Curso.


* **Autores:** Denis Macias Veiga, Felipe José Dellê.

---

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar para fins de estudo.

---

Feito por KAIQUE DAMASCENO SOUSA e ANTONIO BRENO OLIVEIRA MAGALHAES
