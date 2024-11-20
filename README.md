Sistema de Monitoramento de Repositórios
Este é um sistema desenvolvido para monitorar repositórios Git, auxiliando desenvolvedores e equipes a manterem suas aplicações sempre atualizadas com a versão mais recente do Node.js. Além disso, o sistema oferece funcionalidades para gerenciamento e visualização de repositórios cadastrados.

📋 Funcionalidades
Cadastro de repositórios Git, com periodicidade personalizada para notificações.
Verificação automática da compatibilidade com a versão atual do Node.js.
Notificações via e-mail sobre o status de atualização do repositório.
Histórico de consultas realizadas.
Interface intuitiva e responsiva.

Como rodar o sistema:
Siga os passos abaixo para configurar e executar o sistema localmente:

1. Clone o repositório

git clone https://github.com/matheus-hc/tcc.git
cd TCC

2. Crie e ative o ambiente virtual

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate  # Windows

3. Instale as dependências

pip install -r requirements.txt

4. Configure o banco de dados
Execute os seguintes comandos para configurar o banco de dados:

flask db init
flask db migrate -m "Inicializando o banco de dados"
flask db upgrade

5. Execute o servidor
Inicie a aplicação:

flask run
Acesse o sistema no navegador em: http://localhost:5000.

📚 Tecnologias utilizadas
Backend: Flask (Python)
Frontend: Bootstrap e HTML
Banco de Dados: SQLite
Outros: SQLAlchemy, Flask-Migrate

🌟 Objetivo principal
Este sistema foi desenvolvido com o intuito de facilitar o monitoramento de atualizações em repositórios Git, promovendo maior segurança e eficiência no ciclo de desenvolvimento de software. 
Ele é ideal para equipes que desejam manter suas dependências atualizadas de maneira automatizada e organizada.
