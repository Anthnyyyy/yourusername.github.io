# yourusername.github.io
For my LOML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Palagi 💖</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://fonts.googleapis.com/css?family=Dancing+Script" rel="stylesheet">
</head>
<body>
  <div class="hearts"></div>
  <div class="envelope" onclick="openEnv()">
    <div class="flap"></div>
    <div class="letter" id="letter">
      <div class="message">
        <!-- Your message here -->
        It’s finally the big day! Congrats, My Engineer! 👷‍♀️ … Go, My Engineer! 👷‍♀️
      </div>
      <iframe src="https://open.spotify.com/embed/track/0sqnYgWOw9DMc6jRgkcB2m"
              width="300" height="80" frameborder="0"
              allow="autoplay; clipboard-write; encrypted-media" loading="lazy"></iframe>
    </div>
  </div>
<script>
function openEnv() {
  document.querySelector('.flap').classList.add('opened');
  document.getElementById('letter').classList.add('visible');
  document.querySelector('.hearts').classList.add('floats');
}
</script>
</body>
</html>
