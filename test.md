<img id="monpic" onload="constructPage()">
<br>
<b><button onclick="switchForm('ninetales')" style="background:none;border:none;">Ninetales</button> / <button onclick="switchForm('ninetales-alola')" style="background:none;border:none;">Ninetales-Alola</button></b>

<script>
  var id = "ninetales"
  function constructPage() {
    document.getElementById('monpic').src='https://www.smogon.com/dex/media/sprites/xy/' + id + '.gif';
  },
  function switchForm(form) {
    document.getElementById('monpic').src='https://www.smogon.com/dex/media/sprites/xy/' + form + '.gif';
  }
</script>
