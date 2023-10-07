---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Publication Page</title>
    <style>
        /* Add your custom CSS styles here */
        .publication {
            display: flex;
            margin-bottom: 20px;
            align-items: center;
        }
        .publication img {
            max-width: 150px;
            max-height: 100px;
            margin-right: 20px;
        }
        .publication-info {
            flex-grow: 1;
        }
        .publication-title {
            font-size: 1.2em;
            font-weight: bold;
        }
        .publication-authors {
            font-style: italic;
        }
        .publication-buttons {
            margin-top: 10px;
        }
        .publication-buttons a {
            margin-right: 10px;
            text-decoration: none;
            background-color: #0074d9;
            color: white;
            padding: 5px 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <!-- Replace this with your actual publications -->
    <div class="publication">
        <img src="paper1.gif" alt="Paper 1">
        <div class="publication-info">
            <div class="publication-title">Paper 1 Title</div>
            <div class="publication-authors">Author 1, Author 2</div>
            <div class="publication-buttons">
                <a href="paper1.pdf" target="_blank">PDF</a>
                <a href="paper1_abstract.html" target="_blank">Abstract</a>
                <a href="paper1.bib" target="_blank">BibTeX</a>
                <a href="paper1_code.html" target="_blank">Code</a>
                <a href="paper1_demo.html" target="_blank">Demo</a>
            </div>
        </div>
    </div>

    <!-- Add more publications in a similar format -->

</body>
</html>
