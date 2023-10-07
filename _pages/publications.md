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

<!-- <html lang="en">
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
    <div class="publication">
        <img src="/images/5wqa_gif.gif" alt="FACTIFY-5WQA: 5W Aspect-based Fact Verification through Question Answering.">
        <div class="publication-info">
            <div class="publication-title">FACTIFY-5WQA: 5W Aspect-based Fact Verification through Question Answering.</div>
            <div class="publication-authors">Anku Rani, <i><b>S.M Towhidul Islam Tonmoy</b></i>, Dwip D. Dalal, Shreya Gautam, Megha Chakraborty, Aman Chadha, Amit Sheth and Amitava Das.</div>
            <div class="publication-buttons">
                <a href="https://aclanthology.org/2023.acl-long.581/" target="_blank">PDF</a>
                <a href="paper1_abstract.html" target="_blank">Abstract</a>
                <a href="paper1.bib" target="_blank">BibTeX</a>
                <a href="https://github.com/ankuranii/acl-5W-QA/tree/master" target="_blank">Code</a>
                <a href="https://huggingface.co/spaces/Towhidul/5WQA" target="_blank">Demo</a>
            </div>
        </div>
    </div>

</body>
</html> -->



<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Publication Page</title>
    <style>
        /* Styles for the modal dialogs */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.7);
            z-index: 1;
            overflow: auto;
        }

        .modal-content {
            background-color: #fff;
            margin: 10% auto;
            padding: 20px;
            border: 1px solid #888;
            width: 80%;
            max-width: 600px;
            position: relative;
        }

        /* Close button for the modals */
        .close {
            position: absolute;
            top: 0;
            right: 0;
            padding: 10px;
            cursor: pointer;
        }

        /* Custom styles for your publication list */
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

        .publication-buttons a, .publication-buttons button {
            margin-right: 10px;
            text-decoration: none;
            background-color: #0074d9;
            color: white;
            padding: 5px 10px;
            border-radius: 5px;
            cursor: pointer;
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
                <button onclick="showModal('paper1_abstract')">Abstract</button>
                <button onclick="showModal('paper1_bibtex')">BibTeX</button>
                <a href="https://aclanthology.org/2023.acl-long.581/" target="_blank">PDF</a>
                <a href="https://github.com/ankuranii/acl-5W-QA/tree/master" target="_blank">Code</a>
                <a href="https://huggingface.co/spaces/Towhidul/5WQA" target="_blank">Demo</a>
            </div>
        </div>
    </div>

    <!-- Add more publications in a similar format -->

    <!-- Abstract Modal -->
    <div id="paper1_abstract" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('paper1_abstract')">&times;</span>
            <h2>Paper 1 Abstract</h2>
            <p>Here goes the abstract for your paper...</p>
        </div>
    </div>

    <!-- BibTeX Modal -->
    <div id="paper1_bibtex" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('paper1_bibtex')">&times;</span>
            <h2>Paper 1 BibTeX</h2>
            <pre>
                @article{your-paper-key,
                    author = {Author 1 and Author 2},
                    title = {Your Paper Title},
                    journal = {Journal Name},
                    year = {2023},
                    ...
                }
            </pre>
        </div>
    </div>

    <!-- JavaScript Functions -->
    <script>
        // Function to show the modal
        function showModal(modalId) {
            var modal = document.getElementById(modalId);
            modal.style.display = "block";
        }

        // Function to close the modal
        function closeModal(modalId) {
            var modal = document.getElementById(modalId);
            modal.style.display = "none";
        }
    </script>
</body>
</html>