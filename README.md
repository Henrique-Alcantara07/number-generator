<h1 align="center">🎲 Sorteador de Números</h1>

<p align="center">
  Uma aplicação web simples e estilizada para sortear números aleatórios e únicos dentro de um intervalo definido pelo usuário.
</p>

<hr>

<h2>📌 Sobre o projeto</h2>

<p>
  Este projeto foi desenvolvido durante um curso da <strong>Alura</strong>. O HTML e o CSS fornecidos como base do curso,
  enquanto a lógica em <strong>JavaScript</strong> foi implementada por mim.
</p>

<h2>🖥️ Demonstração da interface</h2>

<p>
  A aplicação permite que o usuário informe:
</p>

<ul>
  <li>A quantidade de números que deseja sortear;</li>
  <li>O valor mínimo do intervalo (De);</li>
  <li>O valor máximo do intervalo (Até);</li>
</ul>

<p>
  Ao clicar em <strong>"Sortear"</strong>, os números são gerados aleatoriamente, sem repetição, e exibidos na tela.
  O botão <strong>"Reiniciar"</strong> limpa os campos e o resultado.
</p>

<h2>⚙️ Funcionalidades</h2>

<ul>
  <li>✅ Sorteio de múltiplos números aleatórios</li>
  <li>✅ Garantia de números não repetidos</li>
  <li>✅ Botão de reinício que limpa os campos e o resultado</li>
  <li>✅ Alternância visual do botão "Reiniciar" (habilitado/desabilitado)</li>
  <li>✅ Layout responsivo para telas menores</li>
</ul>

<h2>🧠 Como funciona o JavaScript</h2>

<h3>1. Função <code>sortear()</code></h3>
<p>
  Captura os valores digitados pelo usuário (quantidade, valor mínimo e valor máximo), gera os números aleatórios
  chamando <code>obterNumeroAleatorio()</code> e garante que não haja repetições usando um laço <code>while</code>.
  Ao final, exibe o resultado na tela e atualiza o estado do botão "Reiniciar".
</p>

<h3>2. Função <code>obterNumeroAleatorio(min, max)</code></h3>
<p>
  Utiliza <code>Math.random()</code> combinado com <code>Math.floor()</code> para gerar um número inteiro
  aleatório dentro do intervalo informado (incluindo os limites mínimo e máximo).
</p>

<h3>3. Função <code>alterarStatusBotao()</code></h3>
<p>
  Alterna as classes CSS do botão "Reiniciar", ativando ou desativando seu estilo visual e funcional
  conforme o estado atual do sorteio.
</p>

<h3>4. Função <code>reiniciar()</code></h3>
<p>
  Limpa os campos de entrada e a área de resultado, retornando a aplicação ao estado inicial.
</p>

<h2>🛠️ Tecnologias utilizadas</h2>

<table>
  <thead>
    <tr>
      <th>Tecnologia</th>
      <th>Uso</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>HTML5</td>
      <td>Estrutura da página</td>
    </tr>
    <tr>
      <td>CSS3</td>
      <td>Estilização e responsividade</td>
    </tr>
    <tr>
      <td>JavaScript</td>
      <td>Lógica de sorteio (implementada por mim)</td>
    </tr>
    <tr>
      <td>Google Fonts</td>
      <td>Fontes Chakra Petch e Inter</td>
    </tr>
  </tbody>
</table>

<h2>📁 Estrutura do projeto</h2>

<pre>
📦 sorteador-de-numeros
 ┣ 📂 img
 ┃ ┣ ia.png
 ┃ ┣ code.png
 ┃ ┗ Ruido.png
 ┣ 📜 index.html
 ┣ 📜 style.css
 ┣ 📜 app.js
 ┗ 📜 README.md
</pre>

<h2>🚀 Como executar</h2>

<ol>
  <li>Clone este repositório;</li>
  <li>Abra o arquivo <code>index.html</code> no navegador;</li>
  <li>Preencha os campos e clique em "Sortear"!</li>
</ol>

<h2>🎓 Créditos</h2>

<p>
  Projeto base desenvolvido durante um curso da <a href="https://www.alura.com.br/" target="_blank">Alura</a>.
  A implementação da lógica em JavaScript foi feita por mim como parte do meu aprendizado.
</p>

<hr>

