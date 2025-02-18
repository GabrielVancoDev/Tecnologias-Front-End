# Tecnologia Front-End

O **CSS** (_Cascading Style Sheets_) foi desenvolvido como uma linguagem de estilo para a web, sendo utilizado em conjunto com outras linguagens, como HTML e JavaScript.

## Formas de Utilização do CSS

Podemos utilizar o CSS de três formas:

1. **CSS Externo**: Utilizando um arquivo `.css` separado e importando no HTML com a tag `<link>`.
   ```html
   <link rel="stylesheet" href="styles.css" />
   ```
2. **_CSS Interno_**: Declarando regras dentro da tag <style> no próprio HTML.

```html
<style>
  body {
  }
</style>
```

3. **_CSS Inline_**: Aplicando estilos diretamente na tag HTML.

```html
<h1 style="color: blue;">
  <p style="color: blue; font-size: 18px;">Este é um exemplo de CSS inline.</p>
</h1>
```

<tr>

## Conhecendo Seletores

O HTML tem Seletores que são utilizado no CSS que são:<br>

1. **_ID_**
1. **_Classe_**

**Exemplos:**

```HTML
    <div class="cor-branca" id="texto1">Este texto pertence ao id texto e pertence a classe cor-branca</div>

```

<tr>

## Unidades de Medida no CSS

O CSS possui diferentes unidades para definir tamanhos, larguras, alturas, espaçamentos, etc. Aqui estão algumas das mais comuns:<br>

**Absolutas:**

_`px (Pixels)`_ – Unidade fixa, usada para definir tamanhos exatos.
_`pt (Pontos)`_ – Comum em impressão, mas pouco usado na web.

**Relativas:**

_`%`_ – Proporcional ao elemento pai.<br>
_`em`_ – Relativo ao tamanho da fonte do elemento pai.<br>
_`rem`_ – Relativo ao tamanho da fonte do elemento raiz (html).<br>
_`vh`_ / vw – Porcentagem da altura ou largura da tela<br>

```HTML
.container {
  width: 80%;
  height: 50vh;
  font-size: 1.2em;
}
```

<tr>

## Cores e transparencia
