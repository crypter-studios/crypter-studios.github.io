# Crypter Studios
We are a video game development studio based on the [Roblox](https://www.roblox.com) platform, comprised of various experts and enthusiasts in creating experiences.

Since 2020, we have been driving different projects, among which the most notable one is [Fuerzas Armadas Italianas](https://crypter-studios.github.io/en/fai/about), led by Sig_Vicirrity and Sticky_Sweat (Crypterdev).

# Projects
Here we showcase the public projects that have been released or are in various stages: In-Dev, Pre-Alpha, Alpha, Pre-Beta, Beta.

- **FAI** (In-Dev):
    - Project started in 2020 based on the Roblox platform. More information at [https://crypter-studios.github.io/en/fai/about](https://crypter-studios.github.io/en/fai/about).

- **Insomnia** (In-Dev, suspended):
    - Project started in 2021 based on the Roblox platform. Currently suspended.

# Team
This section displays the credits to our team within the studio.

- **Halo** (Sig_Vicirrity)
    - Chief Developer, Founder of the "FAI" project.
    - Portfolio: N/A

- **Crypter** (Sticky_Sweat)
    - Chief Developer, Co-Founder of the "FAI" project.
    - Portfolio: N/A

# Join Us
We invite you to be a part of our team!

We are not demanding and believe that every skill, no matter how small, counts.

The only, but important requirement is to have experience in any of the following fields:

1. **Game Development.** Whether it's experience with the Roblox Studio program, development on the Unity 3D platform, Godot, or other game engines. This includes map creation, basic knowledge of 3D modeling, programming, or other related fields.
2. **Programming.** If coding is your thing, you'll fit right into our team. You just need experience in a high-level programming language like Python or Javascript and a basic understanding of object-oriented programming (OOP).
3. **Music Production.** If you have already created music, this won't be challenging for you, especially if you specialize in musical ambiance or sound effects creation. Get ready to produce as many "bang, bang" sounds as you can.
4. **3D Modeling.** Do you have experience with programs like Blender 3D or Cinema 4D? You're in. If you can create 3D models with great efficiency, we're interested in having you on our team.

Even if you don't meet one of these requirements, tell us what you can do. There are many things that were not mentioned specifically, but they are so specific that it's not worth creating their own category.

<!-- CSS Styles -->
<style>
  body {
    transition: background-color 0.3s, color 0.3s;
  }

  /* Toggle button styles */
  .dark-mode-toggle {
    position: fixed;
    top: 10px;
    right: 10px;
    width: 50px;
    height: 30px;
    background-color: #ddd;
    border-radius: 15px;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: background-color 0.3s;
  }

  .dark-mode-toggle:hover {
    background-color: #bbb;
  }

  .dark-mode-toggle:active {
    background-color: #999;
  }

  .dark-mode-toggle-label {
    color: #333;
   

 font-size: 12px;
    font-weight: bold;
    text-transform: uppercase;
  }

  .dark-mode-toggle.dark {
    background-color: #333;
  }

  .dark-mode-toggle.dark .dark-mode-toggle-label {
    color: #fff;
  }

  /* Dark mode styles */
  body.dark-mode {
    background-color: #0d1117;
    color: #fff;
  }
</style>

<!-- HTML Content -->
<div class="dark-mode-toggle" onclick="toggleDarkMode()">
  <span class="dark-mode-toggle-label">Light</span>
</div>

<script>
  function toggleDarkMode() {
    const body = document.body;
    const darkModeToggle = document.querySelector('.dark-mode-toggle');

    body.classList.toggle('dark-mode');
    darkModeToggle.classList.toggle('dark');

    if (body.classList.contains('dark-mode')) {
      darkModeToggle.innerHTML = '<span class="dark-mode-toggle-label">Dark</span>';
    } else {
      darkModeToggle.innerHTML = '<span class="dark-mode-toggle-label">Light</span>';
    }
  }
</script>
