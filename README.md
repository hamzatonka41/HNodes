<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Başlık</title>
<style>
  body { font-family: 'Arial', sans-serif; line-height: 1.6; color: #333; }
  .container { width: 80%; margin: auto; overflow: hidden; }
  header { background: #50b3a2; color: white; padding-top: 30px; min-height: 70px; border-bottom: #e8491d 3px solid; }
  header a { color: #ffffff; text-decoration: none; text-transform: uppercase; font-size: 16px; }
  header ul { padding: 0; list-style: none; }
  header li { float: left; display: inline; padding: 0 20px 0 20px; }
  header #branding { float: left; }
  header #branding h1 { margin: 0; }
  header nav { float: right; margin-top: 10px; }
  header .highlight, header .current a { color: #e8491d; font-weight: bold; }
  header a:hover { color: #ffffff; font-weight: bold; }
</style>
</head>
<body>
  <header>
    <div class="container">
      <div id="branding">
        <h1><span class="highlight">Web</span> Siteniz</h1>
      </div>
      <nav>
        <ul>
          <li class="current"><a href="index.html">Ana Sayfa</a></li>
          <li><a href="hakkimizda.html">Hakkımızda</a></li>
          <li><a href="servisler.html">Servisler</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="showcase">
    <div class="container">
      <h1>Profesyonel Web Tasarımı</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus mi augue, viverra sit amet ultricies at, vulputate id lorem. Nulla facilisi.</p>
    </div>
  </section>

  <footer>
    <p>Telif Hakkı © 2024 Web Siteniz</p>
  </footer>
</body>
</html>
