# Django de A a Z - Medic Search
Aplicação web para consulta de médicos

## Instalação

1. Crie uma maquina virtual

```bash
  python -m venv venv
```

2. Instalar dependências

```bash
  pip install -r requirements.txt
```

3. Sincronize a base de dados

```bash
  python manage.py makemigrations
  python manage.py migrate
```

4. Crie um usuário (Administrador do sistema)

```bash
  python manage.py createsuperuser
```

5. Teste a instalação carregando o servidor de desenvolvimento (http://localhost:8000 no navegador):

```bash
  python manage.py runserver
```