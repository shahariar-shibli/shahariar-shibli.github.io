---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

> You can also find the articles on my [[<span style ="color:#800080">*Google Scholar*</span>](https://scholar.google.com/citations?user=GBaSF7MAAAAJ&hl=en)  \|  [<span style ="color:#800080">*ResearchGate*</span>](https://www.researchgate.net/profile/G-Shahariar)  \|  [<span style ="color:#800080">*ORCID*</span>](https://orcid.org/0000-0001-9757-7663)  \|  [<span style ="color:#800080">*Scopus*</span>](https://www.scopus.com/authid/detail.uri?authorId=57844100100)  \|  [<span style ="color:#800080">*Semantic Scholar*</span>](https://www.semanticscholar.org/author/G.-M.-Shahariar/100649170)] profile.

## 2023
---------
<!-- Paper 03 -->
📌 [<span style="color:blue">**Interpretable Multi Labeled Bengali Toxic Comments Classification using Deep Learning**</span>](https://ieeexplore.ieee.org/document/10101588) (<span style="color:red"><strong>Best Paper Award</strong></span> 🏆)<br>
<span style="color:black">
	<font size="3"><strong>Authors</strong>: Tanveer Ahmed Belal, <strong style="color:green">G. M. Shahariar</strong>, and Md. Hasanul Kabir </font>
</span>
<br>
<span style="color:black">
	<font size="3"><strong>Conference:</strong><em> 3rd International Conference on Electrical, Computer and Communication Engineering</em></font> ([ECCE 2023](https://webs.cuet.ac.bd/ecce/))
</span>
<br>
[<a style="color:red;" href="#" onclick="$('#ecce2023_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://www.researchgate.net/publication/369924719_Interpretable_Multi_Labeled_Bengali_Toxic_Comments_Classification_using_Deep_Learning)] [[<span style ="color:red"><font size="3">Code & Dataset</font></span>](https://github.com/deepu099cse/Multi-Labeled-Bengali-Toxic-Comments-Classification)] [[<span style ="color:red"><font size="3">Presentation</font></span>](https://shahariar-shibli.github.io/files/ECCE2023/ECCE-Toxic-Comments-Presentation.pptx)] [<a style="color:red;" href="#" onclick="$('#ecce2023_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="ecce2023_bib" class="bib" style="display:none;">
	<pre>
	  @INPROCEEDINGS{10101588,
	  author={Belal, Tanveer Ahmed and Shahariar, G. M. and Kabir, Md. Hasanul},
	  booktitle={2023 International Conference on Electrical, Computer and Communication Engineering (ECCE)}, 
	  title={Interpretable Multi Labeled Bengali Toxic Comments Classification using Deep Learning}, 
	  year={2023},
	  volume={},
	  number={},
	  pages={1-6},
	  doi={10.1109/ECCE57851.2023.10101588}}
	</pre>
</div>

<div id="ecce2023_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;"> 
		<font size="3">
			This paper presents a deep learning-based pipeline for categorizing Bengali toxic comments, 
			in which at first a binary classification model is used to determine whether a comment is toxic or not, 
			and then a multi-label classifier is employed to determine which toxicity type the comment belongs to. 
			For this purpose, we have prepaBlue a manually labeled dataset consisting of 16,073 instances among which 8,488 are Toxic 
			and any toxic comment may correspond to one or more of the six toxic categories - vulgar, hate, religious, threat, troll, 
			and insult simulta-neously. Long Short Term Memory (LSTM) with BERT Embedding achieved 89.42% accuracy for the binary classification 
			task while as a multi-label classifier, a combination of Convolutional Neural Network and Bi-directional Long Short Term Memory 
			(CNN-BiLSTM) with attention mechanism achieved 78.92% accuracy and 0.86 as weighted F1-score. To explain the pBlueictions and interpret 
			the word feature importance during classification by the proposed models, we utilized Local Interpretable Model-Agnostic Explanations (LIME) framework.
		</font>
	</p>
</div>

<!-- Paper 02 -->
📌 [<span style="color:blue">**Bengali Fake Review Detection using Semi-supervised Generative Adversarial Networks**</span>](https://www.researchgate.net/publication/369855297_Bengali_Fake_Review_Detection_using_Semi-supervised_Generative_Adversarial_Networks)<br>
<span style="color:black">
	<font size="3"><strong>Authors</strong>: Md. Tanvir Rouf Shawon, <strong style="color:green">G. M. Shahariar</strong>, Faisal Muhammad Shah, Mohammad Shafiul Alam, and Md. Shahriar Mahbub</font>
</span>
<br>
<span style="color:black">
	<font size="3"><strong>Conference:</strong><em> 5th International Conference on Natural Language Processing</em></font> ([ICNLP 2023](http://www.icnlp.net/index.html))
</span>
<br>
[<a style="color:red;" href="#" onclick="$('#icnlp2023_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">arXiv</font></span>](https://arxiv.org/abs/2304.02739)] [[<span style ="color:red"><font size="3">Presentation</font></span>](https://shahariar-shibli.github.io/files/ICNLP2023/BFRD-Final.pdf)] [<a style="color:red;" href="#" onclick="$('#icnlp2023_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="icnlp2023_bib" class="bib" style="display:none;">
	<pre>
		@article{shawon2023bengali,
		  title={Bengali Fake Review Detection using Semi-supervised Generative Adversarial Networks},
		  author={Shawon, Md and Rouf, Tanvir and Shahariar, GM and Shah, Faisal Muhammad and Alam, Mohammad Shafiul and Mahbub, Md and others},
		  journal={arXiv preprint arXiv:2304.02739},
		  year={2023}
		}
	</pre>
</div>

<div id="icnlp2023_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;"> 
		<font size="3">
			This paper investigates the potential of semi-supervised Generative Adversarial Networks (GANs) to fine-tune pretrained language 
			models in order to classify Bengali fake reviews from real reviews with a few annotated data. With the rise of social media and e-commerce, 
			the ability to detect fake or deceptive reviews is becoming increasingly important in order to protect consumers from being misled by false 
			information. Any machine learning model will have trouble identifying a fake review, especially for a low resource language like Bengali. 
			We have demonstrated that the proposed semi-supervised GAN-LM architecture (generative adversarial network on top of a pretrained language 
			model) is a viable solution in classifying Bengali fake reviews as the experimental results suggest that even with only 1024 annotated samples, 
			BanglaBERT with semi-supervised GAN (SSGAN) achieved an accuracy of 83.59% and a f1-score of 84.89% outperforming other pretrained language 
			models - BanglaBERT generator, Bangla BERT Base and Bangla-Electra by almost 3%, 4% and 10% respectively in terms of accuracy. The experiments 
			were conducted on a manually labeled food review dataset consisting of total 6014 real and fake reviews collected from various social media 
			groups. Researchers that are experiencing difficulty recognizing not just fake reviews but other classification issues owing to a lack of 
			labeled data may find a solution in our proposed methodology.
		</font>
	</p>
</div>

<!-- Paper 01 --> 
📌 [<span style="color:Blue">**Effectiveness of Transformer Models on IoT Security Detection in StackOverflow Discussions**</span>](https://link.springer.com/chapter/10.1007/978-981-19-7528-8_10)<br>
<span style="color:black">
	<font size="3"><strong>Authors</strong>: Nibir Chandra Mandal, <strong style="color:green">G. M. Shahariar</strong>, and Md. Tanvir Rouf Shawon</font>
</span>
<br>
<span style="color:black">
	<font size="3"><strong>Conference:</strong><em> International Conference on Information and Communication Technology for Development</em></font> ([ICICTD 2022](https://link.springer.com/book/10.1007/978-981-19-7528-8))
</span>
<br>
[<a style="color:red;" href="#" onclick="$('#icictd2023_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://www.researchgate.net/publication/367439808_Effectiveness_of_Transformer_Models_on_IoT_Security_Detection_in_StackOverflow_Discussions)] [[<span style ="color:red"><font size="3">Dataset</font></span>](https://github.com/shahariar-shibli/Effectiveness-of-Transformer-Models-on-IoT-Security-Detection-in-StackOverflow-Discussions) ] [[<span style ="color:red"><font size="3">Presentation</font></span>](https://shahariar-shibli.github.io/files/ICICTD2022/PaperID_68.pdf)] [<a style="color:red;" href="#" onclick="$('#icictd2023_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="icictd2023_bib" class="bib" style="display:none;">
	<pre>
		@InProceedings{10.1007/978-981-19-7528-8_10,
			author="Mandal, Nibir Chandra
			and Shahariar, G. M.
			and Shawon, Md. Tanvir Rouf",
			editor="Ahmad, Mohiuddin
			and Uddin, Mohammad Shorif
			and Jang, Yeong Min",
			title="Effectiveness of Transformer Models on IoT Security Detection in StackOverflow Discussions",
			booktitle="Proceedings of International Conference on Information and Communication Technology for Development",
			year="2023",
			publisher="Springer Nature Singapore",
			address="Singapore",
			pages="125--137",
			isbn="978-981-19-7528-8"
		}
	</pre>
</div>

<div id="icictd2023_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;"> 
		<font size="3">
			The Internet of Things (IoT) is an emerging concept that directly links to the billions of physical items, or “things” 
			that are connected to the Internet and are all gathering and exchanging information between devices and systems. However, 
			IoT devices were not built with security in mind, which might lead to security vulnerabilities in a multi-device system. 
			Traditionally, we investigated IoT issues by polling IoT developers and specialists. This technique, however, is not scalable 
			since surveying all IoT developers is not feasible. Another way to look into IoT issues is to look at IoT developer discussions 
			on major online development forums like Stack Overflow (SO). However, finding discussions that are relevant to IoT issues is 
			challenging since they are frequently not categorized with IoT-related terms. In this paper, we present the “IoT Security Dataset”, 
			a domain-specific dataset of 7147 samples focused solely on IoT security discussions. As there are no automated tools to label these 
			samples, we manually labeled them. We further employed multiple transformer models to automatically detect security discussions. 
			Through rigorous investigations, we found that IoT security discussions are different and more complex than traditional security 
			discussions. We demonstrated a considerable performance loss (up to 44%) of transformer models on cross-domain datasets when we 
			transferred knowledge from a general-purpose dataset “Opiner”, supporting our claim. Thus, we built a domain-specific IoT security 
			detector with an F1-Score of 0.69. We have made the dataset public in the hope that developers would learn more about the security 
			discussion and vendors would enhance their concerns about product security.
		</font>
	</p>
</div>
    

## 2022
---------
📌 [<span style="color:Blue">**Automatic back transliteration of Romanized Bengali (Banglish) to Bengali**</span>](https://link.springer.com/article/10.1007/s42044-022-00122-9)
<span style="color:black"><font size="3"><strong>Authors</strong>: <strong style="color:green">G. M. Shahariar Shibli</strong>, Md. Tanvir Rouf Shawon, Anik Hassan Nibir, Md. Zabed Miandad, and Nibir Chandra Mandal</font></span><br>
<span style="color:black"><font size="3"><strong>Journal:</strong><em> Iran Journal of Computer Science</em></font> ([Iran J Comput Sci](https://www.springer.com/journal/42044))</span><br>
[[<span style ="color:Blue"><font size="3"><strong>PDF</strong></font></span>](https://shahariar-shibli.github.io/files/IRAN2022/Banglish_to_Bangla.pdf) \|  [<span style ="color:Blue"><font size="3"><strong>Code & Dataset</strong></font></span>](https://github.com/shahariar-shibli/Automatic-Back-Transliteration-of-Romanized-Bengali-Banglish-to-Bengali)  \|  [<span style ="color:Blue"><font size="3"><strong>Citation</strong></font></span>](https://shahariar-shibli.github.io/files/IRAN2022/Banglish_to_Bangla.bib)]

📌 [<span style="color:Blue">**Urgent Text Detection in Bengali Language Based on Boosting Techniques**</span>](https://link.springer.com/chapter/10.1007/978-981-19-2445-3_49)
<span style="color:black"><font size="3"><strong>Authors</strong>: Rafsan Rahman, Tamanna Nazmin, Noor Nafeur Rahman, Miyad Bhuiyan, <strong style="color:green">G. M. Shahariar</strong>, and Faisal Muhammad Shah</font></span><br>
<span style="color:black"><font size="3"><strong>Conference:</strong><em> International Conference on Fourth Industrial Revolution and Beyond</em></font> ([ICFIRB 2022](https://link.springer.com/book/10.1007/978-981-19-2445-3))</span><br>
[[<span style ="color:Blue"><font size="3"><strong>PDF</strong></font></span>](https://www.researchgate.net/publication/364138051_Urgent_Text_Detection_in_Bengali_Language_Based_on_Boosting_Techniques)  \|  [<span style ="color:Blue"><font size="3"><strong>Citation</strong></font></span>](https://shahariar-shibli.github.io/files/ICFIRB2022/Urgent-Text.bib)]

📌 [<span style="color:Blue">**Assorted, Archetypal and Annotated Two Million (3A2M) Cooking Recipes Dataset based on Active Learning**</span>](https://www.researchgate.net/publication/364384652_Assorted_Archetypal_and_Annotated_Two_Million_3A2M_Cooking_Recipes_Dataset_based_on_Active_Learning)
<span style="color:black"><font size="3"><strong>Authors</strong>: Nazmus Sakib, <strong style="color:green">G. M. Shahariar</strong>, Md. Mohsinul Kabir, Md. Kamrul, and Hasan Mahmud</font></span><br>
<span style="color:black"><font size="3"><strong>Conference:</strong><em> International Conference on Machine Intelligence and Emerging Technologies</em></font> ([MIET 2022](https://confmiet.org/))</span><br>
[[<span style ="color:Blue"><font size="3"><strong>arXiv</strong></font></span>](https://arxiv.org/abs/2303.16778)  \|  [<span style ="color:Blue"><font size="3"><strong>Dataset</strong></font></span>](https://www.kaggle.com/datasets/nazmussakibrupol/3a2m-cooking-recipe-dataset)  \|  [<span style ="color:Blue"><font size="3"><strong>Presentation</strong></font></span>](https://shahariar-shibli.github.io/files/MIET2022/PaperID_462.pdf)  \|  [<span style ="color:Blue"><font size="3"><strong>Citation</strong></font></span>](https://shahariar-shibli.github.io/files/MIET2022/3A2M.bib)]
 
📌 [<span style="color:Blue">**Can Transformer Models Effectively Detect Software Aspects in StackOverflow Discussion?**</span>](https://www.researchgate.net/publication/363859059_Can_Transformer_Models_Effectively_Detect_Software_Aspects_in_StackOverflow_Discussion)
<span style="color:black"><font size="3"><strong>Authors</strong>: Nibir Chandra Mandal, Tashreef Muhammad, and <strong style="color:green">G. M. Shahariar</strong></font></span><br>
<span style="color:black"><font size="3"><strong>Conference:</strong><em> International Conference on Machine Intelligence and Emerging Technologies</em></font> ([MIET 2022](https://confmiet.org/))</span><br>
[[<span style ="color:Blue"><font size="3"><strong>arXiv</strong></font></span>](https://arxiv.org/abs/2209.12065)  \|  [<span style ="color:Blue"><font size="3"><strong>Dataset</strong></font></span>](https://shahariar-shibli.github.io/files/MIET2022/UddinSOAspect.csv)  \|  [<span style ="color:Blue"><font size="3"><strong>Presentation</strong></font></span>](https://shahariar-shibli.github.io/files/MIET2022/PaperID_371.pptx)  \|  [<span style ="color:Blue"><font size="3"><strong>Citation</strong></font></span>](https://shahariar-shibli.github.io/files/MIET2022/Nibir-Aspect.bib)]
 
## 2021
-------
📌 [<span style="color:Blue">**Ben-Sarc: A Corpus for Sarcasm Detection from Bengali Social Media Comments and Its Baseline Evaluation**</span>](https://www.researchgate.net/publication/357888683_Ben-Sarc_A_Corpus_for_Sarcasm_Detection_from_Bengali_Social_Media_Comments_and_Its_Baseline_Evaluation)
<span style="color:black"><font size="3"><strong>Authors</strong>: Sanzana Karim Lora, <strong style="color:green">G. M. Shahariar</strong>, Tamanna Nazmin, Noor Nafeur Rahman, Rafsan Rahman, Miyad Bhuiyan, and Faisal Muhammad shah</font></span><br>
<span style="color:black"><font size="3"><strong>Journal:</strong> <span style ="color:orchid"><em>under review</em></span></font></span><br>
[[<span style ="color:Blue"><font size="3"><strong>engrXiv</strong></font></span>](https://engrxiv.org/preprint/view/2102/4194)  \|  [<span style ="color:Blue"><font size="3"><strong>Dataset</strong></font></span>](https://docs.google.com/spreadsheets/d/1paQG4X28R7kiV3zYN9Lwa3mJgouXZjqL/edit#gid=785602251)  \|  [<span style ="color:Blue"><font size="3"><strong>Citation</strong></font></span>](https://shahariar-shibli.github.io/files/IN-REVIEW/Ben-Sarc.bib)]

## 2019
-------
📌 [<span style="color:Blue">**Spam Review Detection Using Deep Learning**</span>](https://ieeexplore.ieee.org/document/8936148)
<span style="color:black"><font size="3"><strong>Authors</strong>: <strong style="color:green">G. M. Shahariar</strong>, Swapnil Biswas, Faiza Omar, Faisal Muhammad Shah, and Samiha Binte Hassan</font></span><br>
<span style="color:black"><font size="3"><strong>Conference:</strong><em> 10th Annual Information Technology, Electronics and Mobile Communication Conference</em></font> ([IEMCON 2019](https://ieee-iemcon.org/ieee-iemcon-2019-2/))</span><br>
[[<span style ="color:Blue"><font size="3"><strong>PDF</strong></font></span>](https://www.researchgate.net/publication/338071063_Spam_Review_Detection_Using_Deep_Learning)  \|  [<span style ="color:Blue"><font size="3"><strong>Presentation</strong></font></span>](https://shahariar-shibli.github.io/files/IEMCON2019/Spam-Final.pptx)  \|  [<span style ="color:Blue"><font size="3"><strong>Citation</strong></font></span>](https://shahariar-shibli.github.io/files/IEMCON2019/Spam-Deep.bib)]
 


