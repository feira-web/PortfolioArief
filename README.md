# Welcome to My Project! 🎉

## "Welcome, enjoy your time" 
<p id="typing"></p>

<script>
  const text = "Welcome, enjoy your time!";
  let index = 0;
  const speed = 150; // Speed of typing effect

  function typeWriter() {
    if (index < text.length) {
      document.getElementById("typing").innerHTML += text.charAt(index);
      index++;
      setTimeout(typeWriter, speed);
    }
  }

  typeWriter();
</script>

This is a simple project where you can explore the magic of animations and interactive web development. 😊
