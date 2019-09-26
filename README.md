# Django 

<nav>
  <h1>Academia - Mastertech - Estação Hack  <img src="https://proxy.duckduckgo.com/iu/?u=https%3A%2F%2Fd1ywbwqv5var5z.cloudfront.net%2Fcourses%2Fimages%2F000%2F000%2F082%2Foriginal%2Fpython_django.png%3F1464950119&f=1&nofb=1"  width="40" /></h1>
</nav>

23/09/2019 - Facebook 🚀

- **Site da documentação do Python - Pypi:** ![Pypi](https://pypi.org/)
- **Fazer startup no Django:** `django-admin startproject projeto .`
- **Runserver:** `python manage.py runserver` 
- **Parar servidor de rodar:** `CTRL + C` 
- **Usar python3 para iniciar o venv:** `python3 -m venv .venv`
- **Source:** `source .venv/bin/activate` 
- **Ver os arquivos contidos na pasta:** `ls -la`
- **Criar requirements.txt no VS Code e colocar django depois usar pip install:** `pip install -r requirements.txt` 
- **Colocar style.css para o Django procurar:** `"{% static 'css/style.css' %}"` 
- **Carregar Static antes se não da erro:** `{% load static %}` 
- **Chamar variavel no html:** `{{ minha var }}` 
- **Abrir programas do windows no linux:** ![Wine](https://www.winehq.org/)

# Passo a passo Django

``` 
1: mkdir nome_da_pasta
2: python -m venv  .venv
3: source/Scripts/activate 
4: touch  requirements.txt 
5: colocar django  manualmente no requirements 
6: pip install requirements.txt 
7: django-admin startproject nome_do_projeto(conferir se o manage.py foi criado na raiz do projeto.
8:em settings  do projeto, colocar em installed app o nome projeto
9: py  manage.py  runserver 
10: se rodou tá ok 
11: py manage.py startapp  nome_da_aplicação
12: mkdir imagens, static e java
13: criar cada arquivo em sua pasta
```


## Colocar joguinho da velha no Django 

- [ ] Rodar joguinho no localhost:8000
  

![](https://media0.giphy.com/media/11ZSwQNWba4YF2/giphy.gif?cid=790b7611fd9572113b6460faae8cd1d65114850ebdf4ef55&rid=giphy.gif)
