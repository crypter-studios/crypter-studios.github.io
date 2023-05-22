<!-- Enable Dark Mode Toggle -->
<input type="checkbox" id="dark-mode-toggle">
<label for="dark-mode-toggle" id="dark-mode-label"></label>

<!-- Your HTML content goes here -->
# Crypter Studios
Somos un estudio de desarrollo de videojuegos basados en la plataforma de [Roblox](https://www.roblox.com) conformado por varios expertos y entusiastas de la creación de experiencias.

Desde 2020 empezamos a impulsar diferentes proyectos, entre los más destacados se encuentra las [Fuerzas Armadas Italianas](https://crypter-studios.github.io/es/fai/about), liderado por Sig_Vicirrity y Sticky_Sweat (Crypterdev).

# Proyectos
Aquí se mostrarán los proyectos públicos que ya fueron lanzados o están en su versión In-Dev, Pre-Alpha, Alpha, Pre-Beta, Beta.

- <b>FAI</b> (In-Dev):
    - Proyecto empezado desde 2020 basado en la plataforma Roblox. Más información en https://crypter-studios.github.io/es/fai/about.

- <b>Insomnia</b> (In-Dev, suspendido):
    - Proyecto empezado desde 2021 basado en la plataforma de Roblox. Actualmente suspendido.

# Equipo
En este apartado se muestran los créditos a nuestro equipo dentro del estudio.

- <b>Halo</b> (Sig_Vicirrity)
    - Desarrollador en jefe, Fundador del proyecto "FAI".
    - Portafolio: N/A

- <b>Crypter</b> (Sticky_Sweat)
    - Desarrollador en jefe, Co-Fundador del proyecto "FAI".
    - Portafolio: N/A

# Forma parte de nosotros
¡Te invitamos a formar parte de nuestro equipo!

No somos exigentes y creemos que cada habilidad, por más pequeña que sea, cuenta.

El único pero importante requisito es tener experiencia en alguno de los siguientes campos:

1. <b>Creación de videojuegos.</b> Ya sea tener experiencia con el programa de Roblox Studio, haber desarrollado en la plataforma de Unity 3D, Godot u otros motores de videojuegos. Esto incluye la creación de mapas, conocimiento básico de modelado 3D, programación u otro campo relacionado.
2. <b>Programación.</b> Si lo tuyo es el código, encajarás excelente dentro de nuestro equipo. Basta con tener experiencia en algún lenguaje de programación de alto nivel, como Python o Javascript y tener una noción básica de la programación orientada a objetos (OOP).
3. <b>Producción musical.</b> Si ya has creado música antes, esto no será desafiante para ti, en especial si te especializas en ambientación musical o creación de efectos de sonido. Prepárate para producir tantos "bang, bang" como puedas.
4. <b>Modelado 3D.</b> ¿Tienes experiencia en programas como Blender 3D o Cinema 4D? Estás dentro. Si eres capaz de crear modelos 3D con gran eficacia, estamos interesados en tenerte en nuestro equipo.

Aún si no cuentas con uno de estos requisitos, cuéntanos qué sabes hacer. Hay muchas cosas que faltaron por poner, pero son tan específicas que no vale la pena hacerles su propia categoría.
<!-- CSS Styles for Dark Mode Toggle Button -->
<style>
  body {
    transition: background-color 0.3s, color 0.3s;
  }

  /* Dark Mode Toggle Button Styles */
  #dark-mode-label {
    position: fixed;
    top: 10px;
    right: 10px;
    width: 30px;
    height: 30px;
    background-color: #ddd;
    border-radius: 50%;
    cursor: pointer;
    transition: background-color 0.3s;
  }

  #dark-mode-label:hover {
    background-color: #bbb;
  }

  #dark-mode-toggle {
    display: none;
  }

  #dark-mode-toggle:checked + #dark-mode-label {
    background-color: #333;
  }

  #dark-mode-toggle:checked + #dark-mode-label:before {
    content: "";
    display: block;
    width: 12px;
    height: 12px;
    background-color: #fff;
    border-radius: 50%;
    margin: 8px;
    transition: transform 0.3s;
  }

  #dark-mode-toggle:checked + #dark-mode-label:hover:before {
    transform: scale(1.2);
  }
</style>

<!-- JavaScript to handle Dark Mode toggle -->
<script>
  const darkModeToggle = document.getElementById('dark-mode-toggle');

  darkModeToggle.addEventListener('change', () => {
    if (darkModeToggle.checked) {
      document.body.classList.add('dark-mode');
    } else {
      document.body.classList.remove('dark-mode');
    }
  });
</script>
