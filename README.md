# Projeto mercadinho mc - portfólio de produtos

> É um site que cadastra e apresenta produtos e suas informações básicas, como nome, status, quantide e descrição dos produtos.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/mauricioDosantos/mercadinho_mc/blob/master/static/images/1.png" sizes=0.5>
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/mauricioDosantos/mercadinho_mc/blob/master/static/images/1.png" sizes=0.5>
</picture>

## Configurações
A seguir as configurações de cada parte do projeto

### Configurações de ambiente
Instalar python no [linux](https://python.org.br/instalacao-linux/), [windows](https://python.org.br/instalacao-windows/), [mac](https://python.org.br/instalacao-mac/), [documentação python](https://www.python.org/) 
```
git clone git@github.com:mauricioDosantos/mercadinho_mc.git
```
### Instalar postgres
```
git clone git@github.com:mauricioDosantos/mercadinho_mc.git
```
### Instalar git
```
git clone git@github.com:mauricioDosantos/mercadinho_mc.git
```
### Clonar projeto e configurar
Clonar o projeto para sua máquina
```
git clone git@github.com:mauricioDosantos/mercadinho_mc.git
```
Criar ambiente virtual para isolar as dependências do projeto
```
virtualenv -p 3.10 venv
```
Instalar os requisitos do projeto
```
pip install -r requirements.txt
```
### Configuração do banco de dados
Rodar as migrações no banco de dados
```
manage.py makemigrations
manage.py makemigrate
```
Executar o projeto
```
manage.py webserver
```

Página online [mercadinho mc](https://127.0.0.1)

### Lista de tarefas
- [ ] Criar base do projeto, pastas, e configurações inciais :tada:  
- [ ] Criar modelo de produto :sparkles: 
- [ ] Criar modelo de status do produto :sparkles:
- [ ] Criar modelo do gostei :sparkles:
- [ ] Adicionar campo em modelo de usuário padrão :sparkles:
- [ ] Criar rota de produto :sparkles:
- [ ] Criar visão de produto :sparkles:
- [ ] Personalizar admin :sparkles:
- [ ] Criar página principal com lista de produtos :sparkles:
- [ ] Criar destaque de produtos em promoção. :sparkles:
- [ ] Criar destaque de produtos que são novidades. :sparkles:
- [ ] Criar lista de todos produtos. :sparkles:
- [ ] Criar caixinha de pesquisa de produto. :sparkles:
- [ ] Criar função de pesquisa de produto. :sparkles:
