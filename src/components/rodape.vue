<template>
  <div class="linha" id="rodape">
    <div class="coluna-3">
      Redes sociais:
      <br />
      <br />
      <a target="_blank" href="https://www.facebook.com/ruanfaustinocamellodasilva/">
        <img src="https://static.xx.fbcdn.net/rsrc.php/yD/r/d4ZIVX-5C-b.ico" />
      </a>
      <a target="_blank" href="https://www.instagram.com/lordcamello/">
        <img src="https://www.instagram.com/static/images/ico/favicon.ico/36b3ee2d91ed.ico" />
      </a>
      <a target="_blank" href="https://mobile.twitter.com/ruancamello">
        <img src="https://abs.twimg.com/favicons/twitter.ico" />
      </a>
      <a target="_blank" href="https://www.linkedin.com/in/ruanfaustinocamello">
        <img width="32px" height="32px" src="https://static-exp1.licdn.com/scds/common/u/images/logos/favicons/v1/favicon.ico"/>
      </a>
      <a target="_blank" href="https://github.com/decimo3">
        <img src="https://github.githubassets.com/favicons/favicon.png" />
      </a>
    </div>
    <div class="coluna-3">
      Meus artigos favoritos:
      <br />
      <br />
      <li>Minha esposa é a minha inspiração</li>
      <li>Meus filhos são a minha motivação</li>
      <li>Como a tecnologia mudou a minha vida</li>
    </div>
    <div class="coluna-3">
      Categorias:
      <br />
      <br />
      <li>Tecnologias</li>
      <li>Pessoal</li>
      <li>Minha opinião</li>
    </div>
    <div class="coluna-3">
      Galeria de fotos
      <br />
      <br />
      <li>Fotos favoitas</li>
      <li>Fotos minhas</li>
      <li>Minhas paisagens</li>
      <li>Fotos de trabalhos</li>
    </div>
    <div class="linha" id="copyright">Todos os direitos reservados.</div>
  </div>
</template>
<script>
export default {};
</script>

<style scoped>
.linha {
  padding-left: 13px;
  padding-right: 13px;
}
.coluna-3 {
  height: 160px;
  border-left: solid 1px black;
  border-right: solid 1px black;
}
img {
  padding: 5px;
}
#rodape {
  background-color: #bdbdbd;
  font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
}
#copyright {
  padding: 15px;
  text-align: right;
  color: #ffffff;
}
li a:visited {
  color: #ffffff;
}
</style>
