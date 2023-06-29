# Página de Cadastro e Login com LocalStorage

Este projeto consiste em uma página web com funcionalidades de cadastro e login, utilizando JavaScript para manipular as informações e o `localStorage` para armazená-las localmente no navegador do usuário.

## Funcionalidades

### Página de Cadastro

A página de cadastro apresenta um formulário com campos para nome, e-mail e senha. Ao preencher e enviar o formulário, as informações são coletadas via JavaScript e um novo objeto de usuário é criado. Em seguida, o objeto é adicionado à lista existente de usuários no `localStorage`. O cadastro é considerado bem-sucedido, e uma mensagem de confirmação é exibida.

### Página de Login

A página de login possui um formulário com campos para e-mail e senha. Quando o formulário é enviado, o JavaScript recupera as informações do `localStorage` e verifica se o e-mail e a senha correspondem a algum usuário registrado. Se as informações estiverem corretas, o login é considerado bem-sucedido e uma mensagem de confirmação é exibida. Caso contrário, uma mensagem de erro é exibida.

### Armazenamento com localStorage

O `localStorage` é uma funcionalidade do JavaScript no navegador que permite armazenar dados localmente no dispositivo do usuário. Neste projeto, utilizamos o `localStorage` para armazenar as informações dos usuários cadastrados. Os dados são armazenados como uma lista de objetos JSON, em que cada objeto representa um usuário com propriedades como nome, e-mail e senha.

As informações de cadastro são coletadas pelo JavaScript, adicionadas à lista existente de usuários no `localStorage` e armazenadas através do método `setItem`. Ao realizar o login, as informações são recuperadas do `localStorage` através do método `getItem` para verificação.

## Tecnologias Utilizadas

- HTML: Linguagem de marcação para a estruturação da página web.
- CSS: Linguagem de estilização para a aparência visual da página.
- JavaScript: Linguagem de programação utilizada para a manipulação das informações e interações com o `localStorage`.
- localStorage: Recurso do JavaScript no navegador para armazenar dados localmente no dispositivo do usuário.

## Como executar o projeto

1. Clone ou faça o download deste repositório.
2. Abra o arquivo `index.html` em um navegador web compatível.
3. A página de cadastro e login será exibida. Você pode interagir com os formulários para testar as funcionalidades.

Este projeto é uma demonstração básica do uso do `localStorage` para armazenar informações de cadastro e realizar o login em uma página web. Lembre-se de que o `localStorage` possui algumas limitações, como a persistência dos dados apenas no dispositivo do usuário e a capacidade limitada de armazenamento. Para cenários mais complexos ou com requisitos adicionais de segurança e escalabilidade, é recomendável considerar o uso de um servidor e um sistema de gerenciamento de banco de dados adequado.
