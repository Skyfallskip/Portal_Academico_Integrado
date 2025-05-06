# Projeto Lírio – Portal Acadêmico Integrado

O Projeto Lírio é uma plataforma web desenvolvida para otimizar a interação entre alunos e professores no ambiente acadêmico. O sistema oferece funcionalidades para o gerenciamento de turmas, disciplinas, atividades, notas e comunicação de avisos, proporcionando uma gestão acadêmica eficiente e de fácil acesso.

## Funcionalidades

### Portal do Professor
- Cadastro e gerenciamento de turmas: O professor pode criar, editar e excluir turmas, além de associar alunos a elas.
- Gerenciamento de disciplinas: O professor pode criar e associar disciplinas às turmas.
- Upload de materiais didáticos: Disponibilização de PDFs, vídeos, links e outros tipos de conteúdo educacional.
- Criação e gestão de atividades: O professor pode criar atividades com prazo, descrição e anexo, além de visualizar as entregas dos alunos.
- Correção de atividades: O professor pode visualizar as atividades entregues, atribuir notas e fornecer feedback detalhado.
- Envio de avisos: O professor pode enviar comunicados, como prazos de atividades e outras informações importantes, diretamente para as turmas.

### Portal do Aluno
- Visualização de turmas e disciplinas: O aluno tem acesso a todas as suas turmas e disciplinas em um único lugar.
- Acesso aos materiais didáticos: O aluno pode visualizar e fazer o download dos materiais disponibilizados pelos professores.
- Envio de atividades: O aluno pode enviar suas atividades dentro do prazo estipulado pelos professores.
- Visualização de notas e feedbacks: O aluno pode acompanhar suas notas e os feedbacks fornecidos pelos professores.
- Recebimento de avisos: O aluno recebe avisos sobre atividades, prazos e comunicados de seus professores.

## Tecnologias Utilizadas

### Frontend
- React.js: Utilizado para a criação da interface interativa e dinâmica.
- HTML5 & CSS3: Estruturação e estilo das páginas, com foco em usabilidade.
- JavaScript (ES6+): Linguagem de programação para interatividade e manipulação do DOM.

### Backend
- Django (Python) ou Node.js (Express): Frameworks para construção da API e gerenciamento das requisições.
- JWT (JSON Web Tokens): Utilizado para autenticação segura de usuários.
- Django ORM ou Sequelize: Para manipulação de banco de dados relacional.

### Banco de Dados
- MySQL ou PostgreSQL: Banco de dados relacional utilizado para armazenar os dados das turmas, atividades, alunos, professores e notas.

### Outros
- Tailwind CSS: Framework para estilização rápida e eficiente das interfaces.
- Vercel ou Netlify: Plataformas para deploy do frontend.
- Railway ou Render: Plataformas para deploy do backend.

## Estrutura do Projeto

### Frontend
A aplicação frontend foi construída utilizando o framework React.js para garantir uma navegação rápida e dinâmica. Utilizamos componentes reutilizáveis para facilitar a manutenção e a escalabilidade do sistema.

### Backend
O backend foi desenvolvido com Django (ou Node.js/Express), sendo responsável pela API RESTful. A autenticação é feita via JWT, garantindo a segurança nas comunicações entre o cliente e o servidor.

### Banco de Dados
O banco de dados relacional armazena as informações críticas do sistema, como dados de usuários (alunos e professores), turmas, disciplinas, atividades, notas e comunicados.

## Como Contribuir

Contribuições são bem-vindas! Para contribuir com o projeto, siga as etapas abaixo:

1. Faça um fork deste repositório.
2. Crie uma branch para a sua feature:
