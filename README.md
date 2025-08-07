# Bio Link Page

Este é um projeto de uma página de "link na bio" pessoal, desenvolvida com um tema cyberpunk/tecnológico. A página serve como um hub central para links de projetos e redes sociais, apresentados com uma estética moderna e animações interativas.

-----
### ✨ Funcionalidades Principais

  - 🎨 **Design Cyberpunk:** Tema escuro com gradientes animados no fundo e detalhes em neon, criando uma atmosfera futurista.
  - ✨ **Efeito de Decodificação:** A bio ("Data Driver | Full Stack Developer") possui uma animação de texto "scramble" em JavaScript, que simula uma decodificação em um terminal.
  - 📱 **Totalmente Responsivo:** O layout se adapta perfeitamente a telas de desktops, tablets e celulares.
  - 🔗 **Seções de Links:** Links personalizáveis para projetos principais e ícones de redes sociais no rodapé.
-----
### 💻 Tecnologias Utilizadas

  - **HTML5:** Para a estrutura semântica da página.
  - **CSS3:** Para a estilização completa, utilizando:
      - Variáveis CSS para fácil customização do tema.
      - Flexbox para o alinhamento dos elementos.
      - Animações com `@keyframes` para os efeitos de fundo.
  - **JavaScript (Vanilla JS):** Para o efeito interativo de decodificação do texto da bio.
  - **Font Awesome:** Para os ícones de redes sociais.

-----
### 🚀 Como Usar e Customizar

Para utilizar ou modificar esta página, siga os passos abaixo.

#### 1\. Pré-requisitos

Não há pré-requisitos\! Apenas um navegador web.

#### 2\. Instalação

Basta clonar ou baixar este repositório e abrir o arquivo `index.html` no seu navegador.

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

#### 3\. Customização

O código está em dois arquivos `index.html` e `style.css` para facilitar a edição.

  - **Alterar Informações do Perfil:**

      - **Foto:** Substitua o link em `<img src="..." class="profile-photo" />`.
      - **Nome:** Altere o texto dentro de `<h1 class="profile-name">...</h1>`.
      - **Bio (Texto do Efeito):** Vá até o final do arquivo, na seção `<script>`, e altere a constante `text`:
        ```javascript
        const text = "Seu Novo Cargo | Sua Nova Especialidade";
        ```

  - **Alterar Links:**

      - **Botões Principais:** Edite os links `href` e os textos dentro das tags `<a href="..." class="link-button">`.
      - **Redes Sociais:** Edite os links `href` nas tags `<a>` dentro do `<footer class="social-links">`.

  - **Alterar Cores e Estilos:**

      - As cores principais do tema (neon, fundo, painéis) podem ser facilmente alteradas no início do CSS, na seção `:root`:
        ```css
        :root {
          --bg-color: #0a0a14;
          --primary-neon: #00aaff;
          --secondary-neon: #aa00ff;
          /* ...e outras variáveis */
        }
        ```

-----

### 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
