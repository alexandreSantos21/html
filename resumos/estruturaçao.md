# Formulários e Estruturas HTML  

Formulários e outras estruturas HTML são fundamentais para criar páginas interativas e organizadas. Abaixo estão os principais elementos e suas funções.  

---

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
  - *color="red"*: Altera a cor do texto.  
  - *face="Arial"*: Altera a fonte do texto.  

---

## *Estruturas de Formulários*  

- *<form>*: Define o início de um formulário.  
- *<fieldset>*: Cria um contorno (linha) para organizar visualmente grupos de campos no formulário.  
- *<legend>*: Dá um título para o grupo de campos do <fieldset>.  

### Exemplo:  
```html
<form action="/submit" method="POST">
  <fieldset>
    <legend>Dados Pessoais</legend>
    <label for="name">Nome:</label>
    <input type="text" id="name" name="name" required>
  </fieldset>
</form>