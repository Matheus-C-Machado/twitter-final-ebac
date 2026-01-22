# Clone do Twitter - Projeto Final Django

Este é um clone funcional e moderno do Twitter (X), desenvolvido como projeto final utilizando o framework **Django**. A aplicação conta com um sistema completo de interações sociais, suporte a mídias e uma interface premium otimizada para Dark Mode.

##  Funcionalidades Concluídas

###  Sistema de Autenticação
- **Cadastro e Login:** Sistema seguro de criação de conta e autenticação de usuários.
- **Alteração de Senha:** Funcionalidade integrada para alteração de senha segura dentro do perfil.
- **Proteção de Rotas:** Apenas usuários autenticados podem interagir com o feed e perfis.

###  Perfil e Customização
- **Edição de Perfil:** Alteração opcional de nome de usuário, biografia, foto de perfil e imagem de capa.
- **Estatísticas:** Contador em tempo real de seguidores e usuários seguidos.

###  Feed e Social
- **Feed Inteligente:** Exibe apenas postagens do próprio usuário e das pessoas que ele segue.
- **Sistema de Seguir:** Possibilidade de seguir/deixar de seguir qualquer usuário.
- **Listas Sociais:** Visualização detalhada de quem o usuário segue e quem são seus seguidores.

###  Interações  (AJAX)
- **Likes:** Curtir e descurtir postagens instantaneamente sem recarregar a página.
- **Retweets (Repost):** Sistema de retweet único (toggle) com atualização em tempo real.
- **Comentários:** Sistema de respostas em cada postagem com área de comentários expansível.

###  Mídia e Notificações
- **Suporte a Mídia:** Postagens com suporte para upload de Imagens e Vídeos.
- **Central de Notificações:** Alertas visuais para novas curtidas, comentários, retweets e novos seguidores.
- **Badge de Notificações:** Contador de mensagens não lidas no menu lateral.

---

##  Tecnologias Utilizadas

- **Back-end:** Python 3.x e Django 6.x (Arquitetura Monolítica com lógica RESTful via AJAX).
- **Banco de Dados:** SQLite (Desenvolvimento).
- **Front-end:** HTML5, Tailwind CSS (Design Responsivo), JavaScript (Fetch API para interações assíncronas).
- **Processamento de Imagem:** Pillow.
- **Deploy:** WhiteNoise (Arquivos estáticos) e Gunicorn.

---

##  Como rodar o projeto localmente

Siga os passos abaixo para configurar o ambiente em sua máquina:

Crie e ative um ambiente virtual (venv):
code
Bash
python -m venv venv
# No Windows:
.\venv\Scripts\activate
Instale as dependências:
code
Bash
pip install -r requirements.txt
Realize as migrações do Banco de Dados:
code
Bash
python manage.py makemigrations
python manage.py migrate
Crie um usuário administrador (Superuser):
code
Bash
python manage.py createsuperuser
Inicie o servidor de desenvolvimento:
code
Bash
python manage.py runserver
Acesse a aplicação em: http://127.0.0.1:8000/
Deploy
A aplicação está hospedada e pode ser acessada através do link abaixo:
👉 (https://twitter-final-ebac.onrender.com)
