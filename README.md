# Atividade 4 - Engenharia de Software

Atividade realizada para a disciplina de Engenharia de Software. O objetivo é fazer um relatório,  utilizando Markdown, que aborde os seguintes tópicos:

1. Definir 2 requisitos funcionais de um sistema qualquer.
2. Descrever o Caso de Uso Expandido para os 2 requisitos.
3. Descrever User Storie para os 2 requisitos.
4. Fazer o protótipo da tela para cada um dos requisitos.

## Requisitos Funcionais

- Tela de login
- Tela de busca

## User Story

**Tela de Login**

    “Como usuário, posso entrar na minha conta com meu email e senha para ter acesso às funcionalidades do aplicativo.”

**Tela de busca**

    “Como usuário, posso pesquisar os produtos pelo nome para encontrar rapidamente o que desejo.”

## Caso de Uso Expandido

**RQ01 - Tela de Login**

**Descrição:**

    Para logar no sistema deve-se identificar email e senha.

**Atores:**

    Usuário - Entra no sistema;

**Pré-condição:**

    O ator deve ser cadastrado no sistema.
        
**Fluxo principal:**

    [IN] O usuário insere email e senha.
    [IN] O usuário seleciona o botão "Sign in”.
    [OUT] O sistema direciona o usuário para a tela inicial da sua conta.

**Fluxos alternativos:**

    FA01 - Link “Forgot password”:
    Ao clicar no link “I forgot my password” na tela de Login, o autor é direcionado para uma tela de recuperação de senha;

    FA02 - Link “Create your account”:
    Ao clicar no link “Create your account”, na tela de Login, o autor é direcionado para uma tela de Cadastro;  

**2. RQ02 - Tela de Busca**
    
**Descrição:**

    Para buscar um produto o usuário deve digitar o nome na barra de pesquisa e clicar na tecla enter.

**Atores:**

    Usuário - busca produtos no sistema;

**Pré-condição:**

    O ator deve estar logado no sistema.

**Fluxo principal:**

    [IN] O usuário informa o nome do produto.
    [IN] O usuário clica no botão enter.
    [OUT] O sistema apresenta as opções de produtos relacionadas ao nome inserido.

**Exceções:**
    
    Nenhum produto encontrado.
    [IN] O usuário informa um novo nome.

**Protótipo**

https://www.figma.com/file/scw1E9c7MGXyttQ24vLgnI/App---Eng.-Software?node-id=1%3A18
