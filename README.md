
    Python 3.9.6
    Django 3.2.*

Como rodar o projeto?

    Clone esse repositório.
    Crie um virtualenv com Python 3.
    Ative o virtualenv.
    Instale as dependências.
    Rode as migrações.

git clone https://github.com/rg3915/dicas-de-django.git
cd dicas-de-django
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
