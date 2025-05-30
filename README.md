# provabrun
consultinha pra provinha 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Guia de Consulta - Prova de HTML</title>
  <style>
    body { font-family: Arial, sans-serif; padding: 20px; line-height: 1.6; background: #f9f9f9; }
    h1, h2, h3 { color: #003366; }
    code { background: #eee; padding: 2px 4px; border-radius: 4px; font-family: monospace; }
    pre { background: #eee; padding: 10px; border-radius: 5px; overflow-x: auto; }
  </style>
</head>
<body>
  <h1>Guia Rápido de Consulta para Prova de HTML</h1>

  <h2>📌 Estrutura Básica</h2>
  <pre><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
  &lt;head&gt;
    &lt;title&gt;Título&lt;/title&gt;
  &lt;/head&gt;
  &lt;body&gt;
    Conteúdo visível aqui
  &lt;/body&gt;
&lt;/html&gt;</code></pre>

  <h2>🎨 CSS Inline, Interno e Externo</h2>
  <ul>
    <li>Inline: <code>&lt;p style="color:red"&gt;Texto&lt;/p&gt;</code></li>
    <li>Interno:
<pre><code>&lt;style&gt;
  p { color: red; }
&lt;/style&gt;</code></pre></li>
    <li>Externo: <code>&lt;link rel="stylesheet" href="estilo.css"&gt;</code></li>
  </ul>

  <h2>🧠 Entidades Especiais</h2>
  <pre><code>&amp;lt; &amp;gt; &amp;amp; &amp;quot; &amp;nbsp;</code></pre>

  <h2>🖼️ Imagens</h2>
  <code>&lt;img src="caminho.jpg" alt="Texto alternativo" width="300" height="200"&gt;</code>

  <h2>🔗 Links</h2>
  <code>&lt;a href="https://site.com" target="_blank"&gt;Visitar Site&lt;/a&gt;</code>

  <h2>🧩 Tabelas</h2>
<pre><code>&lt;table border="1"&gt;
  &lt;tr&gt;&lt;th&gt;Nome&lt;/th&gt;&lt;th&gt;Idade&lt;/th&gt;&lt;/tr&gt;
  &lt;tr&gt;&lt;td&gt;João&lt;/td&gt;&lt;td&gt;30&lt;/td&gt;&lt;/tr&gt;
&lt;/table&gt;</code></pre>

  <h2>🎯 Tags Semânticas</h2>
  <code>&lt;header&gt; &lt;nav&gt; &lt;main&gt; &lt;section&gt; &lt;article&gt; &lt;footer&gt; &lt;aside&gt;</code>

  <h2>🧪 Inputs HTML</h2>
  <pre><code>&lt;input type="text"&gt;
&lt;input type="email"&gt;
&lt;input type="password"&gt;
&lt;input type="checkbox"&gt;
&lt;input type="radio" name="opcao"&gt;
&lt;input type="submit" value="Enviar"&gt;</code></pre>

  <h2>📐 Atributos Importantes</h2>
  <ul>
    <li><code>id</code>: identificador único</li>
    <li><code>class</code>: define estilos agrupados</li>
    <li><code>value</code>, <code>placeholder</code>, <code>name</code></li>
  </ul>

  <h2>📏 Tamanho e Estilo com CSS</h2>
<pre><code>h1 {
  font-size: 32px;
  color: blue;
  background-color: lightgray;
  padding: 10px;
  margin: 20px;
}</code></pre>

  <h2>🧠 Extras para Prova</h2>
  <ul>
    <li><code>&lt;br&gt;</code>: quebra de linha</li>
    <li><code>&lt;hr&gt;</code>: linha horizontal</li>
    <li><code>&lt;span&gt;</code>: texto em linha</li>
    <li><code>&lt;div&gt;</code>: bloco genérico</li>
    <li><code>&lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt;</code></li>
  </ul>

  <h2>📂 Estrutura de Pastas (Exemplo)</h2>
  <pre><code>/projeto
├── index.html
├── style.css
├── script.js
└── imagens/
     └── foto.jpg</code></pre>

  <h2>💬 Comentários</h2>
  <code>&lt;!-- Comentário no HTML --&gt;</code>

  <h2>🧠 Importante</h2>
  <ul>
    <li>Feche todas as tags corretamente!</li>
    <li>Use aspas nos atributos: <code>src="imagem.jpg"</code></li>
    <li>Use o <code>DOCTYPE</code> sempre!</li>
  </ul>
</body>
</html>

dimensionamento 
width: 300px;    /* Largura fixa */
height: 150px;   /* Altura fixa */
width: 50%;      /* Largura relativa */
padding: 10px;   /* Espaço interno */
margin: 20px;    /* Espaço externo */
border: 1px solid black; /* Borda */
font-size: 16px; /* Tamanho da fonte */
css
<style>
  body {
    background-color: #f2f2f2;
    font-family: Arial;
  }

  h1 {
    color: blue;
    text-align: center;
  }

  .caixa {
    width: 300px;
    height: 150px;
    background-color: lightgray;
    padding: 10px;
    margin: 20px auto;
    border: 2px solid black;
  }
formulários 
<form action="destino.php" method="post">
  <label for="nome">Nome:</label>
  <input type="text" id="nome" name="nome"><br>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br>

  <label>Senha:</label>
  <input type="password" name="senha"><br>

