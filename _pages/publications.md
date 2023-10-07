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
        <img src="/images/5wqa_gif.gif" alt="FACTIFY-5WQA: 5W Aspect-based Fact Verification through Question Answering.">
        <div class="publication-info">
            <div class="publication-title">FACTIFY-5WQA: 5W Aspect-based Fact Verification through Question Answering.</div>
            <div class="publication-authors">Anku Rani, <i><b>S.M Towhidul Islam Tonmoy</b></i>, Dwip D. Dalal, Shreya Gautam, Megha Chakraborty, Aman Chadha, Amit Sheth and Amitava Das.</div>
            <div class="publication-buttons">
                <a href="https://aclanthology.org/2023.acl-long.581/" target="_blank">PDF</a>
                <a href="\abstract\5wqa_abstract.html" target="_blank">Abstract</a>
                <a href="\bibtex\5wqa_bibtex.html" target="_blank">BibTeX</a>
                <a href="https://github.com/ankuranii/acl-5W-QA/tree/master" target="_blank">Code</a>
                <a href="https://huggingface.co/spaces/Towhidul/5WQA" target="_blank">Demo</a>
            </div>
        </div>
    </div>

    <!-- Add more publications in a similar format -->

</body>
</html>


