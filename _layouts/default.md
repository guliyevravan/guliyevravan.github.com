<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>{{ page.title }} | {{ site.title }}</title>
  <link rel="stylesheet" href="/assets/css/input.css">
</head>
<body class=>
  {% include header.html %}
  <div class="flex">
    <main class="container mx-auto">
      {{ content }} 
    </main>
  </div>
  
  {% include footer.html %}
</body>
</html>