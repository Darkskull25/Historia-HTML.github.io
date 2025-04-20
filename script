<script>
        function cambiarTema() {
            document.body.classList.toggle("tema-claro");
            document.body.classList.toggle("tema-oscuro");
        }

  document.addEventListener("DOMContentLoaded" , function () {
       const musica = document.getElementById("musicaFondo");
       const boton = document.getElementById("muteBtn");

      function iniciarAudio() {
      musica.play().catch(() => {}); 
      document.removeEventListener("mousemove", iniciarAudio);
        }

      document.addEventListener("mousemove", iniciarAudio);

      boton.addEventListener("click", funcion () {
          if (musica.paused) {
              musica.play(); 
              boton.classList.remove("muted"); 
          } else {

              musica.pause(); 
              boton.classList.add("muted");
          }
        });
      });
    </script>
