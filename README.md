# Projeto Django - Desafio Técnico

Este projeto foi desenvolvido como parte de um desafio técnico para demonstrar conhecimentos em Django, desvios condicionais e laços simples.

## Descrição

O projeto consiste em uma aplicação Django que permite criar questões (`Question`) e respostas (`Choice`), com funcionalidades para calcular o total de votos e verificar se uma questão possui votos.

## Funcionalidades Implementadas

1. **Método `total_votes`**:
   - Retorna o total de votos de todas as respostas associadas a uma questão.

2. **Método `has_votes`**:
   - Retorna `True` se a questão tiver pelo menos uma resposta com votos, caso contrário, retorna `False`.

## Como Executar o Projeto

### Pré-requisitos

- Python 3.x instalado.
- Pip (gerenciador de pacotes do Python).

### Passos para Configuração

1. **Clone o repositório**:
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
Instale as dependências:


pip install -r requirements.txt
Execute as migrações:


python manage.py migrate
Crie um superusuário:


python manage.py createsuperuser
Inicie o servidor de desenvolvimento:


python manage.py runserver
Acesse o projeto:

Abra o navegador e acesse:


http://127.0.0.1:8000/
Como Usar
Acesse o Django Admin:

Acesse http://127.0.0.1:8000/admin e faça login com o superusuário criado.

Crie questões (Questions) e respostas (Choices) no painel de administração.

Verifique os resultados:

Acesse a página de resultados de uma questão (ex: http://127.0.0.1:8000/polls/1/results/).

Confira o total de votos e se a questão possui votos.

## Screenshots

1. **Painel de Administração**:
   ![Tela Admin](screenshots/Tela%20admin.jpg)

2. **Página de Resultados**:
   ![Resultado](screenshots/Resultado.jpg)
