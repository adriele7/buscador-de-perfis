# 🔍 Buscador de Perfis do GitHub (Tema Neon)

Este é um projeto simples e moderno para buscar e exibir informações essenciais de qualquer usuário do GitHub utilizando a API pública da plataforma. O design utiliza um tema escuro com cores neon vibrantes e efeitos de animação.

## ✨ Funcionalidades

* **Busca Rápida:** Encontre perfis do GitHub digitando o nome de usuário.
* **Exibição de Dados:** Mostra avatar, nome, login, bio e estatísticas principais (Repositórios Públicos, Seguidores, Seguindo).
* **Design Responsivo:** Layout otimizado para celulares e desktops (Mobile-First).
* **Estilo Moderno:** Tema escuro com efeitos Neon/Hacker, animações CSS e transições suaves.
* **Tratamento de Erros:** Exibe um card de erro amigável se o usuário não for encontrado.

## 💻 Tecnologias Utilizadas

O projeto é 100% desenvolvido com tecnologias front-end puras, sem frameworks:

* **HTML5:** Estrutura da página.
* **CSS3:** Estilização responsiva e efeitos visuais (com Variáveis CSS e animações `@keyframes`).
* **JavaScript (ES6+):** Lógica de busca assíncrona (`async/await`) e manipulação do DOM.

## 🚀 Como Rodar o Projeto Localmente

Siga estes passos para ter o projeto funcionando no seu computador:

1.  **Clone o repositório** (se estiver no Git) ou **baixe os arquivos** (se não estiver):

    ```bash
    git clone [https://www.youtube.com/watch?v=X49Wz3icO3E](https://www.youtube.com/watch?v=X49Wz3icO3E)
    ```

2.  **Estrutura de Arquivos:** Certifique-se de que os três arquivos principais estejam na mesma pasta:

    ```
    /seu-projeto
    ├── index.html
    ├── style.css
    └── script.js
    ```

3.  **Abra no Navegador:** Basta clicar duas vezes no arquivo `index.html`. O código JavaScript fará as requisições à API do GitHub automaticamente.

## ⚙️ Estrutura do Código

### `index.html`
Contém o formulário de busca e o container (`#profile-container`) onde o resultado é injetado dinamicamente pelo JavaScript.

### `style.css`
Define as variáveis de cor (Neon Verde, background escuro), as regras responsivas (`@media query` para 600px) e todos os estilos visuais e animações (Ex: `fadeIn` para o card).

### `script.js`
A lógica principal:
1.  Seleciona elementos do DOM.
2.  Define a URL da API do GitHub (`https://api.github.com/users/`).
3.  A função `getUser(username)` faz a requisição `fetch` assíncrona.
4.  As funções `createProfileCard(user)` e `createErrorCard(message)` geram o HTML e o injetam no container.
5.  O `searchForm.addEventListener('submit', ...)` captura a entrada do usuário e inicia a busca.

---

## 👨‍💻 Desenvolvedor

* [adriele7]
