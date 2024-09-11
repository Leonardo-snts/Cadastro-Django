# Cadastro de pessoas com Django

Esta aplicação é apenas uma maneira simples de verificar dados e permitir que os mesmo não se repitam em uma base de dados de serviços, verifica-se se o CPF é verdadeiro, se o email é valido e se o cliente ja se encontra cadastrado no banco de dados.

## Requisitos 
- Python
- Django

## Configuração do Ambiente

Siga os passos abaixo para configurar corretamente o ambiente de desenvolvimento:

### 1. Clonar o repositório

Clone este repositório para o seu ambiente local:

```bash
git clone https://github.com/Leonardo-snts/Cadastro-Django.git
cd Cadastro-Django
```
### ### 2. Criar e ativar um ambiente virtual (venv)

Criação de uma venv:

```bash
# No Windows
python -m venv venv

# No Linux
python3 -m venv venv
```

Ativação de uma venv:

```bash
# No Windows
.\venv\Scripts\activate

# No Linux
source venv/bin/activate
```

### 3. Instalar dependências dentro da venv

Digite o seguinte comando no seu terminal com a venv ativa:

```bash
pip install -r requirements.txt
```
### 4. Rodar o projeto

No terminal dê o seguinte comando para migrar dados para o db e dps rode a aplicação:

```bash
# No Windows
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

# No Linux
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
```
Pressione "CTRL + C" no terminal para encerrar

### 7. Desativar o Ambiente Virtual

Quando terminar de trabalhar no projeto, você pode desativar o ambiente virtual com o seguinte comando:

```bash
deactivate
```
