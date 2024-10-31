<h1>Orm NodeJs</h1>

<h2>🔖 Sobre</h2>
<p>Api sobre uma plataforma de cursos com Sequelize e SQLite, criada durante a formação de APIs com Node.js e Express  📚

O projeto consiste em uma API completa que simula uma plataforma de cursos, utilizando a Orm Sequelize
</p>

<h2> 🚀 Tecnologias </h2>
<div>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white">
  <img src= "https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white">
  <img src= "https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white">
</div>

<h2> 🧭Rotas </h2>

<h3> Categorias 🗂️</h3>

- Buscar Categorias: `/categorias` (GET)
- Buscar Categoria por Id: `/categorias/:id` (GET)
- Cadastrar Categoria: `/categorias` (POST)
- Atualizar Categoria: `/categorias/:id` (PUT)
- Excluir Categoria: `/categorias/:id` (DELETE)

<h3> Cursos 📚</h3>

- Buscar Cursos: `/cursos` (GET)
- Buscar Curso por Id: `/cursos/:id` (GET)
- Cadastrar Curso: `/cursos` (POST)
- Atualizar Curso: `/cursos/:id` (PUT)
- Excluir Curso: `/cursos/:id` (DELETE)

<h3> Pessoas 👥</h3>

- Buscar Pessoas: `/pessoas` (GET)
- Buscar Todas as Pessoas: `/pessoas/todos` (GET)
- Buscar Pessoa por Id: `/pessoas/:id` (GET)
- Cadastrar Pessoa: `/pessoas` (POST)
- Atualizar Pessoa: `/pessoas/:id` (PUT)
- Cancelar Registro de Estudante: `/pessoas/:estudante_id/cancela` (PUT)
- Excluir Pessoa: `/pessoas/:id` (DELETE)

<h3> Matrículas 🎓</h3>

- Buscar Matrículas Ativas de Estudante: `/pessoas/:estudante_id/matriculas` (GET)
- Buscar Todas as Matrículas de Estudante: `/pessoas/:estudante_id/matriculas/todos` (GET)
- Buscar Matrículas Confirmadas de Estudante: `/pessoas/:estudante_id/matriculas/confirmadas` (GET)
- Buscar Cursos Lotados: `/pessoas/matriculas/lotadas` (GET)
- Buscar Matrícula por Id: `/pessoas/:estudante_id/matriculas/:id` (GET)
- Cadastrar Matrícula: `/pessoas/:estudante_id/matriculas` (POST)
- Atualizar Matrícula: `/pessoas/:estudante_id/matriculas/:id` (PUT)
- Excluir Matrícula: `/pessoas/:estudante_id/matriculas/:id` (DELETE)
