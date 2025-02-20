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
All up-to-date list can be found on my <a href="https://scholar.google.com/citations?user=3lmZN3gAAAAJ&hl=en" target="_blank" style="color: #0074d9;">Google Scholar</a> page.
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
            max-width: 100%; /* Make the image responsive */
            max-height: 100px; /* Limit the height for consistency */
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
        .publication-venue {
            font-style: italic;
            color: #0074d9; /* Highlight the publication venue with blue color */
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

        /* Media query for phone screens */
        @media (max-width: 768px) {
            .publication {
                flex-direction: column; /* Stack elements vertically */
                align-items: flex-start; /* Align items to the left */
            }
            .publication img {
                max-width: 100%; /* Make the image responsive */
                max-height: none; /* Remove max-height to adapt to content */
                margin-right: 0; /* Remove right margin */
                margin-bottom: 10px; /* Add bottom margin for spacing */
            }
        }
    </style>
</head>
<body>
    <!-- Replace this with your actual publications -->
    <div class="publication">
        <img src="/images/5wqa_gif.gif" alt="FACTIFY-5WQA: 5W Aspect-based Fact Verification through Question Answering.">
        <div class="publication-info">
            <div class="publication-title">FACTIFY-5WQA: 5W Aspect-based Fact Verification through Question Answering.</div>
            <div class="publication-venue"><b>ACL 2023</b></div>
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
      <div class="publication">
        <img src="/images/oog_gif.gif" alt="OOG-Optuna Optimized GAN Sampling Technique for Tabular Imbalanced Malware Data.">
        <div class="publication-info">
            <div class="publication-title">OOG-Optuna Optimized GAN Sampling Technique for Tabular Imbalanced Malware Data.</div>
            <div class="publication-venue"><b>IEEE International Conference on Big Data</b></div>
            <div class="publication-authors"><i><b>S.M Towhidul Islam Tonmoy</b></i>, S.M Mehedi Zaman</div>
            
            <div class="publication-buttons">
                <a href="https://ieeexplore.ieee.org/abstract/document/10020393/" target="_blank">PDF</a>
                <a href="\abstract\oog_abstract.html" target="_blank">Abstract</a>
                <a href="\bibtex\oog_bibtex.html" target="_blank">BibTeX</a>
            </div>
        </div>
    </div>

          <div class="publication">
        <!-- <img src="/images/oog_gif.gif" alt="Counter Turing Test (CT2): AI-Generated Text Detection is Not as Easy as You May Think - Introducing AI Detectability Index (ADI)."> -->
        <div class="publication-info">
            <div class="publication-title">Exploring the Relationship between LLM Hallucinations and Prompt Linguistic Nuances: Readability, Formality, and Concreteness</div>
            <div class="publication-venue"><b>Preprint</b></div>
            <div class="publication-authors">Vipula Rawte, Prachi Priya, <i><b>S.M Towhidul Islam Tonmoy</b></i>, S.M Mehedi Zaman, Amit Sheth, Amitava Das</div>
            
            <div class="publication-buttons">
                <a href="https://arxiv.org/abs/2309.11064" target="_blank">Arxiv</a>
                <!-- <a href="\abstract\oog_abstract.html" target="_blank">Abstract</a> -->
                <a href="\bibtex\hallucination_linguistic.html" target="_blank">BibTeX</a>
            </div>
        </div>
    </div>


          <div class="publication">
        <!-- <img src="/images/oog_gif.gif" alt="Counter Turing Test (CT2): AI-Generated Text Detection is Not as Easy as You May Think - Introducing AI Detectability Index (ADI)."> -->
        <div class="publication-info">
            <div class="publication-title">Counter Turing Test (CT2): AI-Generated Text Detection is Not as Easy as You May Think - Introducing AI Detectability Index (ADI).</div>
            <div class="publication-venue"><b>EMNLP 2023 Main</b></div>
            <div class="publication-authors">Megha Chakraborty, <i><b>S.M Towhidul Islam Tonmoy</b></i>, S M Mehedi Zaman, Shreya Gautam, Tanay
Kumar, Krish Sharma, Niyar R Barman, Chandan Gupta, Vinija Jain, Aman Chadha, Amit P. Sheth,
Amitava Das</div>
            
            <!-- <div class="publication-buttons">
                <a href="https://ieeexplore.ieee.org/abstract/document/10020393/" target="_blank">PDF</a>
                <a href="\abstract\oog_abstract.html" target="_blank">Abstract</a>
                <a href="\bibtex\oog_bibtex.html" target="_blank">BibTeX</a>
            </div> -->
        </div>
    </div>

              <div class="publication">
        <!-- <img src="/images/oog_gif.gif" alt="Counter Turing Test (CT2): AI-Generated Text Detection is Not as Easy as You May Think - Introducing AI Detectability Index (ADI)."> -->
        <div class="publication-info">
            <div class="publication-title">The Troubling Emergence of
Hallucination in Large Language Models - An Extensive Definition, Quantification, and
Prescriptive Remediations</div>
            <div class="publication-venue"><b>EMNLP 2023</b> Main</div>
            <div class="publication-authors">Vipula Rawte, SWAGATA CHAKRABORTY, Agnibh Pathak, ANUBHAV SARKAR, <i><b>S.M Towhidul
Islam Tonmoy</b></i>, Aman Chadha, Amit P. Sheth, Amitava Das</div>
            
            <!-- <div class="publication-buttons">
                <a href="https://ieeexplore.ieee.org/abstract/document/10020393/" target="_blank">PDF</a>
                <a href="\abstract\oog_abstract.html" target="_blank">Abstract</a>
                <a href="\bibtex\oog_bibtex.html" target="_blank">BibTeX</a>
            </div> -->
        </div>
    </div>

              <div class="publication">
        <!-- <img src="/images/oog_gif.gif" alt="Counter Turing Test (CT2): AI-Generated Text Detection is Not as Easy as You May Think - Introducing AI Detectability Index (ADI)."> -->
        <div class="publication-info">
            <div class="publication-title">Students’
Mental Wellbeing Prediction in Relation to Mobile Connectivity: A Comprehensive Study</div>
            <div class="publication-venue">Submitted to <b>Scientific Reports Journal</b></div>
            <div class="publication-authors"><i><b>S.M Towhidul Islam Tonmoy</b></i>, S.M Mehedi Zaman, Mirza Muntasir Nishat, Fahim Faisal</div>
            
            <!-- <div class="publication-buttons">
                <a href="https://ieeexplore.ieee.org/abstract/document/10020393/" target="_blank">PDF</a>
                <a href="\abstract\oog_abstract.html" target="_blank">Abstract</a>
                <a href="\bibtex\oog_bibtex.html" target="_blank">BibTeX</a>
            </div> -->
        </div>
    </div>


              <div class="publication">
        <!-- <img src="/images/oog_gif.gif" alt="Embeddings at BLP-2023 Task 2: Optimizing Fine-Tuned Transformers
with Cost-Sensitive Learning for Multiclass Sentiment Analysis"> -->
        <div class="publication-info">
            <div class="publication-title">Embeddings at BLP-2023 Task 2: Optimizing Fine-Tuned Transformers
with Cost-Sensitive Learning for Multiclass Sentiment Analysis</div>
            <div class="publication-venue"><b>EMNLP 2023 BLP Workshop</b></div>
            <div class="publication-authors"><i><b>S.M Towhidul Islam Tonmoy</b></i></div>
            
            <!-- <div class="publication-buttons">
                <a href="https://ieeexplore.ieee.org/abstract/document/10020393/" target="_blank">PDF</a>
                <a href="\abstract\oog_abstract.html" target="_blank">Abstract</a>
                <a href="\bibtex\oog_bibtex.html" target="_blank">BibTeX</a>
            </div> -->
        </div>
    </div>


    <!-- Add more publications in a similar format -->

</body>
</html>