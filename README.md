Plataforma de Cursos Web - Sistema de Onboarding
Este projeto é uma plataforma de cursos online voltada para a área de emissões da MaxMilhas, onde os usuários podem acessar cursos divididos em aulas com videoaulas e conteúdo de texto. Com autenticação via Google Sign-In para emails corporativos e um sistema de pontuação gamificado, o projeto visa engajar os usuários na conclusão de cursos. A aplicação está hospedada no Render e possui uma estrutura completa de frontend e backend.

Funcionalidades
Autenticação Segura: Login via Google Sign-In, restrito a emails corporativos.
Cursos e Aulas: Organização em aulas com conteúdo de vídeo e texto para cada curso.
Sistema de Pontuação: Usuários ganham 50 pontos por aula completada e entre 1600 a 2000 pontos por desempenho acima de 50% nos quizzes.
Quizzes Desbloqueáveis: Disponíveis apenas após a conclusão de todas as aulas de um curso.
Páginas de Suporte: Inclui FAQ e Links Úteis para ajudar o usuário.
Perfil Personalizável: Permite ao usuário editar seu nome e foto.
Responsividade: Design adaptado para dispositivos móveis e desktops.
Screenshots
Tela de Login
Adicione aqui uma screenshot da tela de login, onde o usuário pode entrar com autenticação via Google Sign-In.

Tela Inicial
Adicione aqui uma screenshot da tela inicial, mostrando o dashboard com informações gerais e acesso rápido aos cursos.

Tela de Cursos
Adicione aqui uma screenshot da tela de cursos, onde os usuários visualizam os cursos disponíveis e seu progresso em cada um.

Ranking de Pontuação
Adicione aqui uma screenshot da tela de ranking, onde os usuários podem visualizar sua posição e comparar seu progresso com outros usuários.

Página de Edição de Perfil
Adicione aqui uma screenshot da página de edição de perfil, onde o usuário pode atualizar seu nome e foto.

Tecnologias Utilizadas
Frontend
React: Biblioteca JavaScript para criação de interfaces de usuário (versão 18.3.1).
@mui/material: Biblioteca de componentes com Material Design (versão 6.1.1).
Bootstrap: Framework de CSS para layout e responsividade (versão 5.3.3).
Axios: Biblioteca para chamadas HTTP (versão 1.7.7).
@react-oauth/google: Integração para login com Google OAuth (versão 0.12.1).
@auth0/auth0-react: SDK da Auth0 para autenticação (versão 2.2.4).
Font Awesome: Ícones para interface (versão 6.6.0).
Backend
Node.js: Plataforma para execução de JavaScript no servidor.
Express: Framework para APIs RESTful (versão 4.21.0).
Mongoose: ODM para MongoDB (versão 8.6.3).
Multer: Middleware para upload de arquivos (versão 1.4.5-lts.1).
Cloudinary: API para armazenamento de imagens na nuvem.
jsonwebtoken e express-jwt: Gerenciamento de autenticação com JSON Web Tokens (JWT) para segurança das requisições.
Outras Bibliotecas
@emotion/react e @emotion/styled: Para estilos CSS (versões 11.13.3 e 11.13.0).
dotenv: Gerenciamento de variáveis de ambiente (versão 16.4.5).
emailjs-com: Envio de emails diretamente do cliente (versão 3.2.0).
bcrypt e bcryptjs: Hashing de senhas para segurança (versões 5.1.1 e 2.4.3).
react-icons: Biblioteca de ícones para React (versão 5.3.0).
react-router-dom: Roteamento para navegação dinâmica (versão 6.26.2).
Scripts de Execução
json
Copy code
"start": "react-scripts start",
"build": "react-scripts build",
"test": "react-scripts test",
"serve": "serve -s build"
Esse sistema de onboarding foi desenvolvido para oferecer uma experiência de aprendizado contínua e engajante. Com um design intuitivo e responsivo, ele incentiva os usuários a progredirem em seus estudos e acompanharem suas conquistas.






