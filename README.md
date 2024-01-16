 <h1 id="dynamic-text"></h1>

<script>
  const textElement = document.getElementById('dynamic-text');
  const name = 'Ikhlas';
  let index = 0;
  let direction = 1;

  function updateText() {
    textElement.textContent = name.substring(0, index);
    index += direction;

    if (index > name.length || index < 0) {
      direction *= -1;
      setTimeout(updateText, 1000); // Delay before reversing
    } else {
      setTimeout(updateText, 100); // Speed of animation
    }
  }

  updateText();
</script>

<h3 align="center">A passionate full stack developer and Machine Learning enthusiast from Kashmir/India</h3>

<h2>Certifications 📜<h2>
<p style="font-size: 10px" >🔹 <a href="https://www.udemy.com/certificate/UC-7e5b3b9f-3015-49e4-b3e1-ea24730d92a1/">Web Development </a>-- Udemy</p>
<p style="font-size: 2px">🔹 <a href="https://www.udemy.com/certificate/UC-8674a207-4368-42f4-aae7-10c9a0ae6faa/">Complete Python </a>-- Udemy</p>
<h2>Education  📚<h2>
<ul dir="auto">
<li><strong>Central University of Kashmir</strong> (Dec 2021 - 2025)
<ul dir="auto">
<li>Bachelor of Technology (B. Tech.) in Computer Science &amp; Engineering</li>
</ul>
</li>
</ul>
<h2>Tech Stack 💻</h2>
<h3>Language</h3>
<a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=c,cpp,python,java,javascript,html" />
</a>
<h3>Frameworks</h3>
<a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=react,flask,nodejs,express,bootstrap" />
</a>
<h3>Database</h3>
<a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=mongodb,mysql" />
</a>
<h3>Machine Learning</h3>
<a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=sklearn" />
</a>
<h3>Version Control</h3>
<a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,github" />
</a>


          




