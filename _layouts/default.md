<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>{{ page.title }} | {{ site.title }}</title>
  <link rel="stylesheet" href="/assets/css/style.css">
</head>
<body>
  {% include header.html %}

  <main class="container mx-auto px-4 my-3">
    {{ content }} 
  </main>
  
  {% include footer.html %}
</body>
</html>