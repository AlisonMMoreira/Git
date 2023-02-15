# Explicando a função de cada comando

### git clone: 
O comando git commit é uma das funções principais do Git. Antes de usar o comando git add é necessário selecionar as alterações que vão ser preparadas para o próximo commit. Então, git commit é usado para criar um instantâneo das alterações preparadas em um cronograma de um histórico de projetos do Git.

### git status: 
O comando git status exibe as condições do diretório de trabalho e da área de staging. Ele permite que você veja quais alterações foram despreparadas, quais não foram e quais arquivos não estão sendo monitorados pelo Git.

### git add . :
O comando git add adiciona uma alteração no diretório ativo à área de staging. Ele diz ao Git que você quer incluir atualizações a um arquivo específico no próximo commit. No entanto, git add não tem efeito real e significativo no repositório — as alterações não são gravadas mesmo até você executar git commit.

### git commit:
O comando git commit é uma das funções principais do Git. Antes de usar o comando git add é necessário selecionar as alterações que vão ser preparadas para o próximo commit. Então, git commit é usado para criar um instantâneo das alterações preparadas em um cronograma de um histórico de projetos do Git.

### git push:
O comando git push é usado para enviar o conteúdo do repositório local para um repositório remoto. O comando push transfere commits do repositório local a um repositório remoto. É o oposto do comando git fetch , que importa commits para branches locais, enquanto o comando push exporta commits para branches remotos.

### cd:
Comando usado para navegar entre diretórios.

<hr>

<ul>
  <li>criar e abrir uma pasta do computador com o git bash</li>
  <li>criar um repositório e copiar a url do repositório</li>
  <li>após isso vc usa o comando <code>git clone url_do_repositório.git</code></li>
  <li>entre dentro da pasta usando o comando <code>cd <nome da pasta></code></li>
  <li>use o <code>git status</code></li>
  <li>use o comando <code>git add .</code></li>
  <li>use o <code>git status</code> para conferir se os arquivos estão hospedados localmente na sua máquina.</li>
  <li>para fazer um commit use o comando <code>git commit -m "digite o que desejar colocar de commit"</code></li>
  <li>e apos isso você precisara usar o comando <code>git push</code></li>
</ul>
