# HTML Semântico

Link do deployment: <https://joaoroccella.github.io/html-semantico-t2/>

## Atividade 1: Explorando as Tags Semânticas e Documentação do HTML

### Enunciado:
Vocês foram contratados como uma equipe de desenvolvedores front-end para criar um site informativo sobre os benefícios do uso das tags semânticas do HTML. Vocês devem utilizar as tags semânticas mencionadas, além de outras que julguem relevantes, e criar um site com várias seções informativas. O site deve incluir um menu de navegação que permita aos usuários acessarem facilmente cada seção do site. Vocês devem utilizar a documentação oficial do HTML nos sites W3Schools e MDN Web Docs para consultar informações sobre as tags e seus atributos.

#### Parte 1: Header e Menu de Navegação
No cabeçalho do site, criem um menu de navegação utilizando as tags `<nav>`, `<ul>` e `<li>`. O menu deve conter links para cada seção do site.

Exemplo de código:
```html
<header>
    <h1>Explorando as Tags Semânticas do HTML</h1>
    <nav>
        <ul>
            <li><a href="#introducao">Introdução</a></li>
            <li><a href="#secao1">Seção 1</a></li>
            <!-- Adicione os links para as outras seções aqui -->
        </ul>
    </nav>
</header>
```

#### Parte 2: Seção Introdução
Nesta seção, expliquem brevemente o que são tags semânticas e por que são importantes. Utilizem a tag `<article>` para apresentar o conteúdo principal.

Exemplo de código:
```html
<section id="introducao">
    <article>
        <h2>O que são Tags Semânticas?</h2>
        <p>As tags semânticas do HTML são elementos que conferem significado ao conteúdo, permitindo uma melhor compreensão tanto para os desenvolvedores quanto para os mecanismos de busca.</p>
        <p>Elas ajudam a estruturar o conteúdo de forma mais clara e organizada, contribuindo para a acessibilidade e usabilidade do site.</p>
    </article>
</section>
```

#### Parte 3: Outras Seções
Crie uma seção principal utilizando a tag semântica `<main>`. Dentro dela, criem pelo menos mais três seções utilizando a tag `<section>`. Em cada seção, explorem o uso de diferentes tags semânticas, como `<article>`, `<aside>`, `<footer>`, `<blockquote>`, `<cite>`, `<details>`, `<figure>`, entre outras. Incluam exemplos relevantes e expliquem seu propósito.

Lembrem-se de consultar a documentação do W3Schools e MDN Web Docs para obter informações detalhadas sobre as tags e seus atributos.

#### COMPLEMENTAR
Utilize as tags `<strong>`, `<em>`, `<del>` e `<ins>`, `<sup>` e `<sub>` para marcar trechos do seu código com ênfase.


### Observações:
1. Crie e utilize um repositório chamado **html-semantico** no GitHub.
2. Utilize uma máquina virtual do **GitHub Codespaces** para escrever e editar seu código.
3. Não se esqueça de versionar o código sempre que preciso, utilize as práticas já vistas em aula para isso.
4. Não se preocupe em estilizar a página com CSS, **foque na estrutura do HTML**.
5. **EXPLORE**, NÃO TENHA MEDO DE ERRAR. 

> Quem não erra, não aprende.
