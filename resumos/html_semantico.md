# Resumo: HTML Semântico

O HTML semântico utiliza *tags com significados claros, facilitando a leitura e a organização do código. Ele melhora a **acessibilidade, o **SEO* e a manutenção de projetos.

---

## Estruturas Principais
### <header>
- Contém o cabeçalho da página ou seção.
- Geralmente inclui:
  - Logo
  - Menus de navegação
  - Títulos

### <main>
- Representa o conteúdo principal da página.
- *Regras*:
  - Deve haver *apenas um* <main> por documento.
  - Não deve conter cabeçalhos, rodapés ou barras laterais.

### <footer>
- Define o rodapé da página ou seção.
- Exemplos de conteúdo:
  - Informações de contato
  - Copyright
  - Links adicionais

---

## Seções e Navegação
### <section>
- Agrupa conteúdo relacionado em uma página.
- Útil para dividir a página em blocos lógicos, como:
  - Introdução
  - Serviços
  - Contato

### <aside>
- Usado para *conteúdo complementar*:
  - Barras laterais
  - Informações extras
  - Anúncios

### <nav>
- Contém *links de navegação*.
- Exemplo de estrutura:
  ```html
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">Sobre</a></li>
      <li><a href="#contact">Contato</a></li>
    </ul>
  </nav>