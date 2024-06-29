# ChatSite

Bem-vindo ao ChatSite! Este é um projeto de chat online desenvolvido em Python e HTML. O objetivo deste projeto é fornecer um exemplo prático de como criar um aplicativo de chat simples, utilizando Flask, Socket.IO e outras tecnologias.

## Funcionalidades

- Chat em tempo real
- Conexão de múltiplos usuários
- Interface simples e intuitiva

## Tecnologias Utilizadas

- Python
- Flask
- Socket.IO
- HTML
- JavaScript (jQuery)
- CSS

## Instalação

### Pré-requisitos

Certifique-se de ter as seguintes ferramentas e bibliotecas instaladas:

- [Python](https://www.python.org/downloads/)
- [Git](https://git-scm.com/downloads)
- pip install flask flask-socketio python-socketio

Altere dois scripts no código homepage.html, que são do socketio e do jquery:

- Para obter esses scripts você pode acessar o site https://cdnjs.com/ e 
procurar por socketio e jquery (pode clicar nos nomes para ser
redirecionado e poder copiar os scripts).
- Com os scripts copiados, basta colar os dois no lugar dos antigos, que 
estão logo abaixo do título (<title>Document</title>)

### Passo a Passo

### 1. **Clone o repositório**

   git clone https://github.com/patimaltez/ChatSite.git
   cd ChatSite
   troque o nome ChatSite para projeto

### 2. **Crie e ative um ambiente virtual**

    python -m venv .venv
    # Ative o ambiente virtual:
    # No Windows
    .venv\Scripts\activate
    # No macOS/Linux
    source .venv/bin/activate


### 3. **Instale as dependências**

pip install -r requirements.txt

### 4. **Execute o aplicativo**

python app.py

### 5. **Acesse o aplicativo**

Abra o navegador e vá para http://localhost:5000.

## Estrutura do Projeto

- app.py: Arquivo principal da aplicação Flask.
- templates/index.html: Interface do chat em HTML.
- static/: Diretório para arquivos estáticos (CSS, JavaScript).

## Contribuição

Se você deseja contribuir para este projeto, sinta-se à vontade para abrir um pull request ou relatar problemas na seção de issues.

## Licença

Este projeto está licenciado sob a MIT License.

## Contato
Para dúvidas ou sugestões, entre em contato através do LinkedIn.

Aproveite e divirta-se explorando e aprendendo com o ChatSite!