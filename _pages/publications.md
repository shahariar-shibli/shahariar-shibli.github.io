---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<code style="color:black;">Most recent publication updates can be found on my <a style ="color:#800080;" href="https://scholar.google.com/citations?user=GBaSF7MAAAAJ&hl=en"><em>[Google Scholar]</em></a> profile.</code>

## 2023
---------
<!-- Paper 05 -->
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

<!-- Paper 04 -->
📌 [<span style="color:blue">**Bengali Fake Review Detection using Semi-supervised Generative Adversarial Networks**</span>](https://www.researchgate.net/publication/369855297_Bengali_Fake_Review_Detection_using_Semi-supervised_Generative_Adversarial_Networks)<br>
<span style="color:black">
	<font size="3"><strong>Authors</strong>: Md. Tanvir Rouf Shawon, <strong style="color:green">G. M. Shahariar</strong>, Faisal Muhammad Shah, Mohammad Shafiul Alam, and Md. Shahriar Mahbub</font>
</span>
<br>
<span style="color:black">
	<font size="3"><strong>Conference:</strong><em> 5th International Conference on Natural Language Processing</em></font> ([ICNLP 2023](http://www.icnlp.net/index.html))
</span>
<br>
[<a style="color:red;" href="#" onclick="$('#icnlp2023_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://arxiv.org/abs/2304.02739)] [[<span style ="color:red"><font size="3">Presentation</font></span>](https://shahariar-shibli.github.io/files/ICNLP2023/BFRD-Final.pdf)] [<a style="color:red;" href="#" onclick="$('#icnlp2023_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

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

<!-- Paper 03 --> 
📌 [<span style="color:Blue">**Effectiveness of Transformer Models on IoT Security Detection in StackOverflow Discussions**</span>](https://link.springer.com/chapter/10.1007/978-981-19-7528-8_10)<br>
<span style="color:black">
	<font size="3"><strong>Authors</strong>: Nibir Chandra Mandal, <strong style="color:green">G. M. Shahariar</strong>, and Md. Tanvir Rouf Shawon</font>
</span>
<br>
<span style="color:black">
	<font size="3"><strong>Conference:</strong><em> International Conference on Information and Communication Technology for Development</em></font> ([ICICTD 2022](https://link.springer.com/book/10.1007/978-981-19-7528-8))
</span>
<br>
[<a style="color:red;" href="#" onclick="$('#icictd2023_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://arxiv.org/pdf/2207.14542.pdf)] [[<span style ="color:red"><font size="3">Dataset</font></span>](https://github.com/shahariar-shibli/Effectiveness-of-Transformer-Models-on-IoT-Security-Detection-in-StackOverflow-Discussions) ] [[<span style ="color:red"><font size="3">Presentation</font></span>](https://shahariar-shibli.github.io/files/ICICTD2022/PaperID_68.pdf)] [<a style="color:red;" href="#" onclick="$('#icictd2023_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="icictd2023_bib" class="bib" style="display:none;">
	<pre>
		@InProceedings{mandalSecurity,
			author="Mandal, Nibir Chandra
			and Shahariar, G. M.
			and Shawon, Md. Tanvir Rouf",
			title="Effectiveness of Transformer Models on IoT Security Detection in StackOverflow Discussions",
			booktitle="Proceedings of International Conference on Information and Communication Technology for Development",
			year="2023",
			publisher="Springer Nature Singapore",
			address="Singapore",
			pages="125--137"
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


<!-- Paper 02 -->
📌 [<span style="color:Blue">**Assorted, Archetypal and Annotated Two Million (3A2M) Cooking Recipes Dataset based on Active Learning**</span>](https://doi.org/10.1007/978-3-031-34622-4_15)<br>
<span style="color:black">
	<font size="3"><strong>Authors</strong>: Nazmus Sakib, <strong style="color:green">G. M. Shahariar</strong>, Md. Mohsinul Kabir, Md. Kamrul, and Hasan Mahmud</font>
</span>
<br>
<span style="color:black">
	<font size="3"><strong>Conference:</strong><em> International Conference on Machine Intelligence and Emerging Technologies</em></font> ([MIET 2022](https://confmiet.org/))
</span>
<br>
[<a style="color:red;" href="#" onclick="$('#miet2022_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://arxiv.org/abs/2303.16778)] [[<span style ="color:red"><font size="3">Dataset</font></span>](https://www.kaggle.com/datasets/nazmussakibrupol/3a2m-cooking-recipe-dataset)] [[<span style ="color:red"><font size="3">Presentation</font></span>](https://shahariar-shibli.github.io/files/MIET2022/PaperID_462.pdf)] [<a style="color:red;" href="#" onclick="$('#miet2022_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="miet2022_bib" class="bib" style="display:none;">
	<pre>
		@InProceedings{3A2M,
			author="Sakib, Nazmus
			and Shahariar, G. M.
			and Kabir, Md. Mohsinul
			and Hasan, Md. Kamrul
			and Mahmud, Hasan",
			title="Assorted, Archetypal and Annotated Two Million (3A2M) Cooking Recipes Dataset Based on Active Learning",
			booktitle="Machine Intelligence and Emerging Technologies",
			year="2023",
			publisher="Springer Nature Switzerland",
			address="Cham",
			pages="188--203"
		}
	</pre>
</div>

<div id="miet2022_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;"> 
		<font size="3">
			Cooking recipes allow individuals to exchange culinary ideas and provide food preparation instructions. Due to a lack of 
			adequate labeled data, categorizing raw recipes found online to the appropriate food genres is a challenging task in this domain. 
			Utilizing the knowledge of domain experts to categorize recipes could be a solution. In this study, we present a novel dataset 
			of two million culinary recipes labeled in respective categories leveraging the knowledge of food experts and an active learning 
			technique. To construct the dataset, we collect the recipes from the RecipeNLG dataset [1]. Then, we employ three human experts 
			whose trustworthiness score is higher than 86.667% to categorize 300K recipe by their Named Entity Recognition (NER) and assign 
			it to one of the nine categories: bakery, drinks, non-veg, vegetables, fast food, cereals, meals, sides and fusion. Finally, we 
			categorize the remaining 1900K recipes using Active Learning method with a blend of Query-by-Committee and Human In The Loop 
			(HITL) approaches. There are more than two million recipes in our dataset, each of which is categorized and has a confidence 
			score linked with it. For the 9 genres, the Fleiss Kappa score of this massive dataset is roughly 0.56026. We believe that the 
			research community can use this dataset to perform various machine learning tasks such as recipe genre classification, recipe 
			generation of a specific genre, new recipe creation, etc. The dataset can also be used to train and evaluate the performance 
			of various NLP tasks such as named entity recognition, part-of-speech tagging, semantic role labeling, and so on.
		</font>
	</p>
</div>

<!-- Paper 01 -->
📌 [<span style="color:Blue">**Can Transformer Models Effectively Detect Software Aspects in StackOverflow Discussion?**</span>](https://doi.org/10.1007/978-3-031-34622-4_18)<br>
<span style="color:black">
	<font size="3"><strong>Authors</strong>: Nibir Chandra Mandal, Tashreef Muhammad, and <strong style="color:green">G. M. Shahariar</strong></font>
</span>
<br>
<span style="color:black">
	<font size="3"><strong>Conference:</strong><em> International Conference on Machine Intelligence and Emerging Technologies</em></font> ([MIET 2022](https://confmiet.org/))
</span>
<br>
[<a style="color:red;" href="#" onclick="$('#miet2022_2_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://arxiv.org/abs/2209.12065)] [[<span style ="color:red"><font size="3">Dataset</font></span>](https://shahariar-shibli.github.io/files/MIET2022/UddinSOAspect.csv)] [[<span style ="color:red"><font size="3">Presentation</font></span>](https://shahariar-shibli.github.io/files/MIET2022/PaperID_371.pptx)] [<a style="color:red;" href="#" onclick="$('#miet2022_2_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="miet2022_2_bib" class="bib" style="display:none;">
	<pre>
		@InProceedings{mandal2022can,
			author="Mandal, Nibir Chandra
			and Muhammad, Tashreef
			and Shahariar, G. M.",
			title="Can Transformer Models Effectively Detect Software Aspects in StackOverflow Discussion?",
			booktitle="Machine Intelligence and Emerging Technologies",
			year="2023",
			publisher="Springer Nature Switzerland",
			address="Cham",
			pages="226--241"
		}
	</pre>
</div>

<div id="miet2022_2_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;"> 
		<font size="3">
			Dozens of new tools and technologies are being incorporated to help developers, which is becoming a source of consternation 
			as they struggle to choose one over the others. For example, there are at least ten frameworks available to developers for 
			developing web applications, posing a conundrum in selecting the best one that meets their needs. As a result, developers 
			are continuously searching for all of the benefits and drawbacks of each API, framework, tool, and so on. One of the typical 
			approaches is to examine all of the features through official documentation and discussion. This approach is time-consuming, 
			often makes it difficult to determine which aspects are the most important to a particular developer and whether a particular 
			aspect is important to the community at large. In this paper, we have used a benchmark API aspects dataset (Opiner) collected 
			from StackOverflow posts and observed how Transformer models (BERT, RoBERTa, DistilBERT, and XLNet) perform in detecting 
			software aspects in textual developer discussion with respect to the baseline Support Vector Machine (SVM) model. Through 
			extensive experimentation, we have found that transformer models improve the performance of baseline SVM for most of the 
			aspects, i.e., 'Performance', 'Security', 'Usability', 'Documentation', 'Bug', 'Legal', 'OnlySentiment', and 'Others'. However, 
			the models fail to apprehend some of the aspects (e.g., 'Community' and 'Potability') and their performance varies depending 
			on the aspects. Also, larger architectures like XLNet are ineffective in interpreting software aspects compared to smaller 
			architectures like DistilBERT.
		</font>
	</p>
</div>

## 2022
---------
<!-- Paper 02 -->
📌 [<span style="color:Blue">**Automatic back transliteration of Romanized Bengali (Banglish) to Bengali**</span>](https://link.springer.com/article/10.1007/s42044-022-00122-9)<br>
<span style="color:black">
	<font size="3"><strong>Authors</strong>: <strong style="color:green">G. M. Shahariar Shibli</strong>, Md. Tanvir Rouf Shawon, Anik Hassan Nibir, Md. Zabed Miandad, and Nibir Chandra Mandal</font>
</span>
<br>
<span style="color:black">
	<font size="3"><strong>Journal:</strong><em> Iran Journal of Computer Science</em></font> ([Iran J Comput Sci](https://www.springer.com/journal/42044))
</span>
<br>
[<a style="color:red;" href="#" onclick="$('#iran2022_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://shahariar-shibli.github.io/files/IRAN2022/Banglish_to_Bangla.pdf)] [[<span style ="color:red"><font size="3">Code & Dataset</font></span>](https://github.com/shahariar-shibli/Automatic-Back-Transliteration-of-Romanized-Bengali-Banglish-to-Bengali)] [<a style="color:red;" href="#" onclick="$('#iran2022_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="iran2022_bib" class="bib" style="display:none;">
	<pre>
		@article{shibli2022automatic,
		  title={Automatic back transliteration of Romanized Bengali (Banglish) to Bengali},
		  author={Shibli, GM Shahariar and Shawon, Md Tanvir Rouf and Nibir, Anik Hassan and Miandad, Md Zabed and Mandal, Nibir Chandra},
		  journal={Iran Journal of Computer Science},
		  pages={1--12},
		  year={2022},
		  publisher={Springer}
		}
	</pre>
</div>

<div id="iran2022_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;"> 
		<font size="3">
			Back transliteration of Romanized Bengali to Bengali is the process of converting text written in the Latin alphabet back into the 
			Bengali script. This is often done in order to improve the readability of Bengali text for Bengali speakers using a simple rules-based 
			system, or an interactive transliteration tool. There are many ways to back transliterate from Romanized Bengali to Bengali, but most 
			of them are either grapheme or phoneme based. This paper introduces a unique pipeline that uses nine open source back transliteration 
			tools to automatically back transliterate Romanized Bengali to Bengali. The pipeline consists of seven steps: (1) processing the 
			Romanized Bengali input; (2) acquiring human transliteration for performance comparison; (3) employing transliteration tools; (4) 
			generating candidate transliterations; (5) post-processing the candidate transliterations; (6) selecting best candidate transliteration, 
			and (7) evaluating the quality of the transliterations through several performance metrics. Experimental results reveal that our approach 
			produced the highest BLEU-1 score of 81.28, BLEU-2 score of 60.75, BLEU-3 score of 44.45, BLEU-4 score of 30.46, and the lowest average 
			Word Error Rate and Word Information Lost of 29.21 and 43.68, respectively, on 1000 Romanized Bengali texts. In terms of recall, 
			we achieved a Rouge-L score of 0.7190.
		</font>
	</p>
</div>

<!-- Paper 01 -->
📌 [<span style="color:Blue">**Urgent Text Detection in Bengali Language Based on Boosting Techniques**</span>](https://link.springer.com/chapter/10.1007/978-981-19-2445-3_49)<br>
<span style="color:black">
	<font size="3"><strong>Authors</strong>: Rafsan Rahman, Tamanna Nazmin, Noor Nafeur Rahman, Miyad Bhuiyan, <strong style="color:green">G. M. Shahariar</strong>, and Faisal Muhammad Shah</font>
</span>
<br>
<span style="color:black">
	<font size="3"><strong>Conference:</strong><em> International Conference on Fourth Industrial Revolution and Beyond</em></font> ([ICFIRB 2022](https://link.springer.com/book/10.1007/978-981-19-2445-3))
</span>
<br>
[<a style="color:red;" href="#" onclick="$('#icfirb2022_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://www.researchgate.net/publication/364138051_Urgent_Text_Detection_in_Bengali_Language_Based_on_Boosting_Techniques)] [<a style="color:red;" href="#" onclick="$('#icfirb2022_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="icfirb2022_bib" class="bib" style="display:none;">
	<pre>
		@InProceedings{10.1007/978-981-19-2445-3_49,
			author="Rahman, Rafsan
			and Nazmin, Tamanna
			and Rahman, Noor Nafeur
			and Bhuiyan, Miyad
			and Shahariar, G. M.
			and Shah, Faisal Muhammad",
			title="Urgent Text Detection in Bengali Language Based on Boosting Techniques",
			booktitle="Proceedings of International Conference on Fourth Industrial Revolution and Beyond 2021 ",
			year="2022",
			publisher="Springer Nature Singapore",
			address="Singapore",
			pages="697--709",
			isbn="978-981-19-2445-3"
		}
	</pre>
</div>

<div id="icfirb2022_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;"> 
		<font size="3">
			This paper presents a learning approach on a unique dataset formulated by authors that detects urgent texts 
			from the posts on social media platforms in Bengali language. It is difficult to keep track of every information 
			we go through social media. In the collision of numerous posts, it is easy to miss information that is urgent. 
			In this advanced era of machine learning, detecting urgent texts among thousands of posts would be much easier 
			if we can implement a model that can filter the urgent text out of them. Therefore, we propose an approach that 
			can identify any type of urgent texts from public posts by leveraging a manually constructed dataset that is fully 
			human annotated. Apart from traditional machine learning classifiers, we applied boosting algorithms in our 
			proposed method in addition. Experimentally, a significant increase in accuracy has been noticed by boosting 
			weak learners. Support Vector Machine (SVM) achieved 80.9% accuracy where gradient boosting outperformed the 
			traditional approach with 82% accuracy while detecting urgent texts in Bengali language.
		</font>
	</p>
</div>


## 2021
-------
<!-- Paper 01 -->
📌 [<span style="color:Blue">**Ben-Sarc: A Corpus for Sarcasm Detection from Bengali Social Media Comments and Its Baseline Evaluation**</span>](https://www.researchgate.net/publication/357888683_Ben-Sarc_A_Corpus_for_Sarcasm_Detection_from_Bengali_Social_Media_Comments_and_Its_Baseline_Evaluation)<br>
<span style="color:black">
	<font size="3"><strong>Authors</strong>: Sanzana Karim Lora, <strong style="color:green">G. M. Shahariar</strong>, Tamanna Nazmin, Noor Nafeur Rahman, Rafsan Rahman, Miyad Bhuiyan, and Faisal Muhammad shah</font>
</span>
<br>
	<span style="color:black">
		<font size="3"><strong>Journal:</strong> 
				<span style ="color:orchid">
					<em>under review</em>
				</span>
		</font>
	</span>
<br>
[<a style="color:red;" href="#" onclick="$('#inreview_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://engrxiv.org/preprint/view/2102/4194)] [[<span style ="color:red"><font size="3">Dataset</font></span>](https://docs.google.com/spreadsheets/d/1paQG4X28R7kiV3zYN9Lwa3mJgouXZjqL/edit#gid=785602251)] [<a style="color:red;" href="#" onclick="$('#inreview_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="inreview_bib" class="bib" style="display:none;">
	<pre>
		@article{loraben,
		  title={Ben-Sarc: A Corpus for Sarcasm Detection from Bengali Social Media Comments and Its Baseline Evaluation},
		  author={Lora, Sanzana Karim and Shahariar, GM and Nazmin, Tamanna and Rahman, Noor Nafeur and Rahman, Rafsan and Bhuiyan, Miyad and others},
		  publisher={Engineering Archive}
		}
	</pre>
</div>

<div id="inreview_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;"> 
		<font size="3">
			Sarcasm detection research of the Bengali language so far can be considered to be narrow due to the unavailability of resources. 
			In this paper, we introduce a large-scale self annotated Bengali corpus for sarcasm detection research problem in the Bengali 
			language named 'Ben-Sarc' containing 25,636 comments, manually collected from different public Facebook pages and evaluated by external 
			evaluators. Then we present a complete strategy to utilize different models of traditional machine learning, deep learning, and 
			transfer learning to detect sarcasm from text using the Ben-Sarc corpus. Finally, we demonstrate a comparison between the performance 
			of traditional machine learning, deep learning, and transfer learning models on our Ben-Sarc corpus. Transfer learning using 
			Indic-Transformers Bengali BERT as a pre-trained source model has achieved the highest accuracy of 75.05%. The second highest 
			accuracy is obtained by the LSTM model with 72.48% and Multinomial Naive Bayes is acquired the third highest with 72.36% accuracy 
			for deep learning and machine learning, respectively. The Ben-Sarc corpus is made publicly available in the hope of advancing 
			the Bengali Natural Language Processing community.
		</font>
	</p>
</div>

## 2019
-------
<!-- Paper 01 -->
📌 [<span style="color:Blue">**Spam Review Detection Using Deep Learning**</span>](https://ieeexplore.ieee.org/document/8936148)<br>
<span style="color:black">
	<font size="3"><strong>Authors</strong>: <strong style="color:green">G. M. Shahariar</strong>, Swapnil Biswas, Faiza Omar, Faisal Muhammad Shah, and Samiha Binte Hassan</font>
</span>
<br>
<span style="color:black">
	<font size="3"><strong>Conference:</strong><em> 10th Annual Information Technology, Electronics and Mobile Communication Conference</em></font> ([IEMCON 2019](https://ieee-iemcon.org/ieee-iemcon-2019-2/))
</span>
<br>
[<a style="color:red;" href="#" onclick="$('#iemcon2019_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://www.researchgate.net/publication/338071063_Spam_Review_Detection_Using_Deep_Learning)] [[<span style ="color:red"><font size="3">Presentation</font></span>](https://shahariar-shibli.github.io/files/IEMCON2019/Spam-Final.pptx)] [<a style="color:red;" href="#" onclick="$('#iemcon2019_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="iemcon2019_bib" class="bib" style="display:none;">
	<pre>
		@INPROCEEDINGS{8936148,
		  author={Shahariar, G. M. and Biswas, Swapnil and Omar, Faiza and Shah, Faisal Muhammad and Binte Hassan, Samiha},
		  booktitle={2019 IEEE 10th Annual Information Technology, Electronics and Mobile Communication Conference (IEMCON)}, 
		  title={Spam Review Detection Using Deep Learning}, 
		  year={2019},
		  volume={},
		  number={},
		  pages={0027-0033},
		  doi={10.1109/IEMCON.2019.8936148}
		  }
	</pre>
</div>

<div id="iemcon2019_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;"> 
		<font size="3">
			A robust and reliable system of detecting spam reviews is a crying need in todays world in order to purchase products 
			without being cheated from online sites. In many online sites, there are options for posting reviews, and thus creating 
			scopes for fake paid reviews or untruthful reviews. These concocted reviews can mislead the general public and put them 
			in a perplexity whether to believe the review or not. Prominent machine learning techniques have been introduced to solve 
			the problem of spam review detection. The majority of current research has concentrated on supervised learning methods, 
			which require labeled data - an inadequacy when it comes to online review. Our focus in this article is to detect any deceptive 
			text reviews. In order to achieve that we have worked with both labeled and unlabeled data and proposed deep learning methods 
			for spam review detection which includes Multi-Layer Perceptron (MLP), Convolutional Neural Network (CNN) and a variant of 
			Recurrent Neural Network (RNN) that is Long Short-Term Memory (LSTM). We have also applied some traditional machine learning 
			classifiers such as Nave Bayes (NB), K Nearest Neighbor (KNN) and Support Vector Machine (SVM) to detect spam reviews and 
			finally, we have shown the performance comparison for both traditional and deep learning classifiers.
		</font>
	</p>
</div>

