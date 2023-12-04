# Curso de Django com Python 3
Código das aulas que vi durante o curso de Python, do Professor Jefferson Lobato, no Youtube, em 2023.

O Django é um framework web full stack open source (código aberto) baseado em Python, gratuito e de alto nível. Este framework foi criado com o objetivo de resolver todos os problemas mais comuns do processo de desenvolvimento de aplicações web, como por exemplo autenticação, rotas, object relational mapper (ORM) e até migrations.

## Aula 01 - Criando projeto Django

### Comandos
- 1- `python -m venv <nome do ambiente virtual>`: para criar um ambiente virtual, que serve também para que o código rode em outras máquinas;
- 2- ` . <nome do ambiente virtual>/Scripts/activate`: caminho para ativar o ambiente virtual no Windows 11, para Python 3;
- 3- `deactivate`: para desativar o ambiente virtual;
- 4- `pip install Django`: para instalar o Django, após ativar o ambiente virtual do comando **2**;
- 5- `django-admin --version`: para ver a versão do Django;
- 6- `django-admin startproject <nome do projeto> .`: para criar um novo projeto (recomenda-se criar onde está a máquina virtual)