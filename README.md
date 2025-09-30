## Configuração do ambiente

Crie um arquivo `.env` na raiz do projeto com as seguintes variáveis:

DATABASE_NAME=seu_banco
DATABASE_USER=seu_usuario
DATABASE_PASSWORD=sua_senha
DATABASE_HOST=localhost
DATABASE_PORT=3306

Crie um `venv` utilizando `python -m venv venv`

Ative-o:

Windows - `.\venv\Scripts\activate` ou `.\venv\Scripts\Activate.ps1`
Linux - `source venv/bin/activate`

Utilize `pip install -r requirements.txt`

Caso deseje verificar o processo de criação do código -> [Tutorial - Django](https://docs.djangoproject.com/en/5.2/intro/)
