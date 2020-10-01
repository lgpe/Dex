<h1 id="monname"> </h1><br>
<img id="monpic" src="https://www.smogon.com/dex/media/sprites/xy/pikachu.gif">
<br>
<b><button onclick="switchForm('ninetales')" style="background:none;border:none;">Ninetales</button> / <button onclick="switchForm('ninetales-alola')" style="background:none;border:none;">Ninetales-Alola</button></b>

<script>
  import {pokedex} from 'src/data.js';
  var id = "ninetales";
  document.getElementById("monname").innerHTML = "owo";
  document.getElementById('monpic').src='https://www.smogon.com/dex/media/sprites/xy/' + id + '.gif';
  
  
  function switchForm(form) {
    document.getElementById('monpic').src='https://www.smogon.com/dex/media/sprites/xy/' + form + '.gif';
  }
</script>
