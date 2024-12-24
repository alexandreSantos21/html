# Tags Estruturais de HTML

## *Tags e Atributos Comuns*  

- *<b>: Deixa o texto em **negrito*, mas sem peso semântico.  
- *<strong>: Deixa o texto em **negrito*, com significado semântico (destaque importante).  
- *<blockquote>*: Separa um trecho em formato de citação.  
- *<ul>: Cria uma lista **não ordenada*.  
- *<ol>: Cria uma lista **ordenada*.  
- *<li>*: Representa os itens dentro das listas.  
- *<mark>: Destaca o texto como se fosse um **marca-texto*.  
- *<u>: Deixa o texto **sublinhado*.  
- *<font>*: Permite alterações no estilo de texto via atributos. Apesar de estar em desuso, ainda é funcional.  
- *b: Deixa o texto em **negrito*, mas sem peso semântico.  
- *strong: Deixa o texto em **negrito*, com significado semântico (destaque importante).  
- *blockquote*: Separa um trecho em formato de citação.  
- *ul: Cria uma lista **não ordenada*.  
- *ol: Cria uma lista **ordenada*.  
- *li*: Representa os itens dentro das listas.  
- *mark: Destaca o texto como se fosse um **marca-texto*.  
- *u: Deixa o texto **sublinhado*.  
- *font*: Permite alterações no estilo de texto via atributos. Apesar de estar em desuso, ainda é funcional.  
  - *color="red"*: Altera a cor do texto.  
  - *face="Arial"*: Altera a fonte do texto.  

---

## *Estruturas de Formulários*  

- *<form>*: Define o início de um formulário.  
- *<fieldset>*: Cria um contorno (linha) para organizar visualmente grupos de campos no formulário.  
- *<legend>*: Dá um título para o grupo de campos do <fieldset>.  
- *form*: Define o início de um formulário.  
- *fieldset*: Cria um contorno (linha) para organizar visualmente grupos de campos no formulário.  
- *legend*: Dá um título para o grupo de campos do <fieldset>.  

### Exemplo:  
```html
@@ -34,4 +34,4 @@ Formulários e outras estruturas HTML são fundamentais para criar páginas inte
    <label for="name">Nome:</label>
    <input type="text" id="name" name="name" required>
  </fieldset>
</form>
</form>


## `<header>`
- **Descrição**: Usada para representar o cabeçalho da página ou de uma seção.
- **Função**: Contém logotipos, menus de navegação ou títulos principais.
- **Exemplo**:
  ```html
  <header>
      <h1>Bem-vindo ao site</h1>
      <nav>
          <ul>
              <li><a href="#home">Home</a></li>
              <li><a href="#sobre">Sobre</a></li>
          </ul>
      </nav>
  </header>
  ```

## `<main>`
- **Descrição**: Representa o conteúdo principal da página.
- **Função**: Deve conter o foco principal do site, e apenas um `<main>` deve ser usado por página.
- **Exemplo**:
  ```html
  <main>
      <article>
          <h2>Artigo Principal</h2>
          <p>Texto sobre o conteúdo principal.</p>
      </article>
  </main>
  ```

## `<footer>`
- **Descrição**: Usada para criar o rodapé da página.
- **Função**: Inclui informações como direitos autorais, links ou contatos.
- **Exemplo**:
  ```html
  <footer>
      <p>&copy; 2024 Minha Empresa</p>
      <a href="#politica">Política de Privacidade</a>
  </footer>
  ```

## `<section>`
- **Descrição**: Define seções temáticas ou agrupamentos de conteúdo relacionados.
- **Função**: Organiza o conteúdo em blocos lógicos.
- **Exemplo**:
  ```html
  <section>
      <h2>Seção Importante</h2>
      <p>Descrição desta seção.</p>
  </section>
  ```

## `<aside>`
- **Descrição**: Usada para conteúdos relacionados ou complementares, como barras laterais.
- **Função**: Inclui informações adicionais ou relacionadas ao conteúdo principal.
- **Exemplo**:
  ```html
  <aside>
      <h3>Artigos Relacionados</h3>
      <ul>
          <li><a href="#artigo1">Artigo 1</a></li>
          <li><a href="#artigo2">Artigo 2</a></li>
      </ul>
  </aside>
  ```

