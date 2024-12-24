# Resumo sobre Tags de Formulário em HTML

As tags de formulário em HTML são essenciais para coletar dados de usuários. Aqui estão as principais tags utilizadas para formular um formulário interativo.

---

### 1. `<form>`
A tag `<form>` é usada para criar o formulário. Dentro dessa tag, outros elementos, como campos de entrada, botões e listas, são inseridos.

```html
<form action="/submit" method="post">
  <!-- Campos do formulário -->
</form>
```

- **action**: Define o URL para onde os dados serão enviados.
- **method**: Especifica o método HTTP para enviar os dados (ex.: `post`, `get`).

---

### 2. `<input>`
A tag `<input>` é uma das mais utilizadas, sendo responsável por criar diversos tipos de campos de entrada, como caixas de texto, senhas, botões, entre outros.

```html
<input type="text" name="username" placeholder="Digite seu nome">
<input type="password" name="password" placeholder="Digite sua senha">
<input type="submit" value="Enviar">
```

- **type**: Define o tipo do campo (ex.: `text`, `password`, `radio`, `checkbox`).
- **name**: Nome do campo para identificar quando enviar o formulário.
- **placeholder**: Texto de exemplo que aparece dentro do campo de entrada.
- **value**: Define o valor do campo.

---

### 3. `<button>`
A tag `<button>` é usada para criar botões em formulários. Pode ser configurada com diferentes tipos de ações.

```html
<button type="submit">Enviar</button>
<button type="reset">Limpar</button>
```

- **type**: Pode ser `submit`, `reset` ou `button`.
  - `submit`: Envia o formulário.
  - `reset`: Limpa os campos do formulário.
  - `button`: Cria um botão sem ação atribuída.

---

### 4. `<label>`
A tag `<label>` serve para associar um texto explicativo a um campo de formulário, tornando o formulário mais acessível.

```html
<label for="username">Nome de Usuário</label>
<input type="text" id="username" name="username">
```

- **for**: Associa o texto da tag ao campo de entrada com o `id` correspondente.

---

### 5. `<select>` e `<option>`
Essas tags são usadas para criar menus suspensos, onde o usuário pode escolher uma opção.

```html
<select name="car" id="car">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="mercedes">Mercedes</option>
</select>
```

- **name**: Nome do campo para envio.
- **option**: Define as opções disponíveis no menu suspenso.

---

### 6. `<textarea>`
A tag `<textarea>` permite criar campos de texto multilinha, ideal para comentários ou descrições.

```html
<textarea name="message" rows="4" cols="50"></textarea>
```

- **rows**: Número de linhas visíveis.
- **cols**: Número de colunas visíveis.

---

### 7. `<fieldset>` e `<legend>`
Essas tags são usadas para agrupar elementos de um formulário e adicionar um título ao grupo.

```html
<fieldset>
  <legend>Informações Pessoais</legend>
  Nome: <input type="text" name="name"><br>
  Idade: <input type="text" name="age"><br>
</fieldset>
```

- **fieldset**: Agrupa os campos.
- **legend**: Adiciona um título ao grupo.

---

### 8. `<input type="checkbox">` e `<input type="radio">`
Esses campos permitem ao usuário fazer escolhas. O `checkbox` permite múltiplas seleções, e o `radio` permite apenas uma escolha.

```html
<label><input type="checkbox" name="subscribe"> Quero receber newsletters</label><br>
<label><input type="radio" name="gender" value="male"> Masculino</label>
<label><input type="radio" name="gender" value="female"> Feminino</label>
```

---

### 9. `<input type="file">`
A tag `<input type="file">` é usada para permitir que o usuário envie arquivos no formulário.

```html
<input type="file" name="fileUpload">
```

---

### 10. `<input type="date">`
A tag `<input type="date">` permite que o usuário selecione uma data a partir de um calendário.

```html
<input type="date" name="birthday">
```

---

Essas são as tags principais para a criação de formulários HTML. Elas permitem a coleta de dados de forma interativa e são fundamentais para qualquer site ou aplicação que envolva interação com usuários.
