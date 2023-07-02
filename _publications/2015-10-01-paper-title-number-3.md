---
title: "FACTIFY-5WQA: 5W Aspect-based Fact Verification
through Question Answering."
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'Anku Rani, <i><b>S.M Towhidul Islam Tonmoy</b></i>, Dwip D. Dalal, Shreya Gautam, Megha Chakraborty, Aman
Chadha, Amit Sheth and Amitava Das.'
date: 2023-07-10
venue: ' ACL Main'
paperurl: 'https://arxiv.org/abs/2305.04329'
demo: 'https://arxiv.org/abs/2305.04329'
#citation: 'Anku Rani, <i>S.M Towhidul Islam Tonmoy</i>, Dwip D. Dalal, Shreya Gautam, Megha Chakraborty, Aman
#Chadha, Amit Sheth and Amitava Das'

---

<html>
<head>
    <style>
        .cover {
            text-align: center;
            margin-bottom: 20px;
        }

        .cover img {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
        }
    </style>
</head>
<body>
    <div class="cover">
        <img src="/images/5wqa_poster.png" alt="Cover Image">
    </div>


</body>
</html>

Anku Rani, <i><b>S.M Towhidul Islam Tonmoy</b></i>, Dwip D. Dalal, Shreya Gautam, Megha Chakraborty, Aman
Chadha, Amit Sheth and Amitava Das.

Abstract: Automatic fact verification has received significant attention recently. Contemporary automatic fact-checking systems focus on estimating truthfulness using numerical scores which are not human-interpretable. A human fact-checker generally follows several logical steps to verify a verisimilitude claim and conclude whether its truthful or a mere masquerade. Popular fact-checking websites follow a common structure for fact categorization such as half true, half false, false, pants on fire, etc. Therefore, it is necessary to have an aspect-based (delineating which part(s) are true and which are false) explainable system that can assist human fact-checkers in asking relevant questions related to a fact, which can then be validated separately to reach a final verdict. In this paper, we propose a 5W framework (who, what, when, where, and why) for question-answer-based fact explainability. To that end, we present a semi-automatically generated dataset called FACTIFY-5WQA, which consists of 391, 041 facts along with relevant 5W QAs - underscoring our major contribution to this paper. A semantic role labeling system has been utilized to locate 5Ws, which generates QA pairs for claims using a masked language model. Finally, we report a baseline QA system to automatically locate those answers from evidence documents, which can serve as a baseline for future research in the field. Lastly, we propose a robust fact verification system that takes paraphrased claims and automatically validates them.

<html>
<head>
    <style>
        .container {
            display: flex;
            justify-content: center;
        }

        .container a {
            padding: 8px 16px;
            margin: 0 8px;
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 4px;
            transition: background-color 0.3s;
        }

        .container a:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <a href="https://arxiv.org/abs/2305.04329">PDF</a>
        <a href="https://github.com/ankuranii/acl-5W-QA/tree/master">Code</a>
        <a href="https://huggingface.co/spaces/Towhidul/5WQA">Web Demo</a>
    </div>
</body>
</html>




