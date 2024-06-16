---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<span style="color:black; font-family:Georgia;">Most recent publication updates can be found on my <a style ="color:#800080;" href="https://scholar.google.com/citations?hl=en&user=GBaSF7MAAAAJ&view_op=list_works&sortby=pubdate"><em>[Google Scholar]</em></a> profile.</span><br>
<span style="color:black; font-family:Georgia;">[*] denotes equal contribution</span>

## 2024
---------

<!-- Paper 04 -->
📌 [<span style="color:Blue;font-family:Trebuchet MS;">**Bengali Fake Reviews: A Benchmark Dataset and Detection System**</span>](https://www.sciencedirect.com/science/article/abs/pii/S0925231224005034) (<span style="color:red"><strong>Q1</strong></span>)<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Authors</strong>: <strong style="color:green">G. M. Shahariar*</strong>, Md. Tanvir Rouf Shawon*, Faisal Muhammad Shah, Mohammad Shafiul Alam, Md. Shahriar Mahbub</font>
</span>
<br>
	<span style="color:black;font-family:Georgia">
		<font size="3"><strong>Journal: </strong><em>Neurocomputing</em></font> ([Neurocomputing](https://www.sciencedirect.com/journal/neurocomputing))
	</span>
<br>
[<a style="color:red;" href="#" onclick="$('#neucom_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://arxiv.org/pdf/2308.01987)] [[<span style ="color:red"><font size="3">Code & Dataset</font></span>](https://github.com/shahariar-shibli/Bengali-Fake-Reviews-A-Benchmark-Dataset-and-Detection-System)] [<a style="color:red;" href="#" onclick="$('#neucom_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="neucom_bib" class="bib" style="display:none;">
	<pre>
		@article{SHAHARIAR2024127732,
			title = {Bengali fake reviews: A benchmark dataset and detection system},
			journal = {Neurocomputing},
			volume = {592},
			pages = {127732},
			year = {2024},
			issn = {0925-2312},
			doi = {https://doi.org/10.1016/j.neucom.2024.127732},
			url = {https://www.sciencedirect.com/science/article/pii/S0925231224005034},
			author = {G M Shahariar and Md. Tanvir Rouf Shawon and Faisal Muhammad Shah and Mohammad Shafiul Alam and Md. Shahriar Mahbub},
			keywords = {Bengali fake reviews detection, Ensemble learning, Transformers, Deep learning, Augmentation, Transliteration}
		}
	</pre>
</div>

<div id="neucom_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;font-family:Monaco;"> 
		<font size="3">
			The proliferation of fake reviews on various online platforms has created a major concern for both consumers and businesses. 
			Such reviews can deceive customers and cause damage to the reputation of products or services, making it crucial to identify them. 
			Although the detection of fake reviews has been extensively studied in English language, detecting fake reviews in non-English 
			languages such as Bengali is still a relatively unexplored research area. The novelty of this study unfolds on three fronts: (i) a 
			new publicly available dataset called Bengali Fake Review Detection (BFRD) dataset is introduced, (ii) a unique pipeline has been 
			proposed that translates English words to their corresponding Bengali meaning and also back transliterates Romanized Bengali to 
			Bengali, (iii) a weighted ensemble model that combines four pre-trained transformers model is proposed. The developed dataset 
			consists of 7710 non-fake and 1339 fake food-related reviews collected from social media posts. Rigorous experiments have been 
			conducted to compare multiple deep learning and pre-trained transformer language models and our proposed model to identify the 
			best-performing model. According to the experimental results, the proposed ensemble model attained a weighted F1-score of 0.9843 
			on a dataset of 13,390 reviews, comprising 1339 actual fake reviews, 5,356 augmented fake reviews, and 6695 reviews randomly 
			selected from the 7710 non-fake instances.
		</font>
	</p>
</div>


<!-- Paper 03 -->
📌 [<span style="color:Blue;font-family:Trebuchet MS;">**A Comparative Analysis of Noise Reduction Methods in Sentiment Analysis on Noisy Bangla Texts**</span>](https://aclanthology.org/2024.wnut-1.5/) (<span style="color:red"><strong>Core A</strong></span>)<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Authors</strong>: Kazi Toufique Elahi, Tasnuva Binte Rahman, Shakil Shahriar, Samir Sarker, Md. Tanvir Rouf Shawon, <strong style="color:green">G. M. Shahariar</strong></font>
</span>
<br>
	<span style="color:black;font-family:Georgia">
		<font size="3"><strong>Workshop: </strong><em>Proceedings of the Ninth Workshop on Noisy and User-generated Text collocated with EACL 2024</em></font> ([(W-NUT 2024)](https://noisy-text.github.io/2024/))
	</span>
<br>
[<a style="color:red;" href="#" onclick="$('#wnut_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://aclanthology.org/2024.wnut-1.5.pdf)] [[<span style ="color:red"><font size="3">Code & Dataset</font></span>](https://github.com/shahariar-shibli/A-Comparative-Analysis-of-Noise-Reduction-Methods-in-Sentiment-Analysis-on-Noisy-Bangla-Texts)] [[<span style ="color:red"><font size="3">Presentation</font></span>](https://shahariar-shibli.github.io/files/WNUT2024/NC-SentNoB.pptx)] [<a style="color:red;" href="#" onclick="$('#wnut_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="wnut_bib" class="bib" style="display:none;">
	<pre>
		@inproceedings{elahi-etal-2024-comparative,
			title = "A Comparative Analysis of Noise Reduction Methods in Sentiment Analysis on Noisy {B}angla Texts",
			author = "Elahi, Kazi  and
			  Rahman, Tasnuva  and
			  Shahriar, Shakil  and
			  Sarker, Samir  and
			  Shawon, Md.  and
			  Shibli, G. M.",
			booktitle = "Proceedings of the Ninth Workshop on Noisy and User-generated Text (W-NUT 2024)",
			month = mar,
			year = "2024",
			address = "San {\.G}iljan, Malta",
			publisher = "Association for Computational Linguistics",
			url = "https://aclanthology.org/2024.wnut-1.5",
			pages = "44--57"
		}
	</pre>
</div>

<div id="wnut_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;font-family:Monaco;"> 
		<font size="3">
			While Bangla is considered a language with limited resources, sentiment analysis has been a subject of extensive research in the 
			literature. Nevertheless, there is a scarcity of exploration into sentiment analysis specifically in the realm of noisy Bangla texts. 
			In this paper, we introduce a dataset (NC-SentNoB) that we annotated manually to identify ten different types of noise found in a 
			pre-existing sentiment analysis dataset comprising of around 15K noisy Bangla texts. At first, given an input noisy text, we identify 
			the noise type, addressing this as a multi-label classification task. Then, we introduce baseline noise reduction methods to 
			alleviate noise prior to conducting sentiment analysis. Finally, we assess the performance of fine-tuned sentiment analysis models 
			with both noisy and noise-reduced texts to make comparisons. The experimental findings indicate that the noise reduction methods 
			utilized are not satisfactory, highlighting the need for more suitable noise reduction methods in future research endeavors.
		</font>
	</p>
</div>


<!-- Paper 02 -->
📌 [<span style="color:Blue;font-family:Trebuchet MS;">**Ben-Sarc: A Self-Annotated Corpus for Sarcasm Detection from Bengali Social Media Comments and Its Baseline Evaluation**</span>](https://www.cambridge.org/core/journals/natural-language-processing/article/bensarc-a-selfannotated-corpus-for-sarcasm-detection-from-bengali-social-media-comments-and-its-baseline-evaluation/CE2E2FE7EC596AB6E0C528E995214095) (<span style="color:red"><strong>Q1</strong></span>)<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Authors</strong>: Sanzana Karim Lora, <strong style="color:green">G. M. Shahariar</strong>, Tamanna Nazmin, Noor Nafeur Rahman, Rafsan Rahman, Miyad Bhuiyan, and Faisal Muhammad Shah</font>
</span>
<br>
	<span style="color:black;font-family:Georgia">
		<font size="3"><strong>Journal: </strong><em>Natural Language Processing</em></font> ([Natural Language Processing](https://www.cambridge.org/core/journals/natural-language-engineering))
	</span>
<br>
[<a style="color:red;" href="#" onclick="$('#nlp_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/CE2E2FE7EC596AB6E0C528E995214095/S2977042424000116a.pdf/ben-sarc-a-self-annotated-corpus-for-sarcasm-detection-from-bengali-social-media-comments-and-its-baseline-evaluation.pdf)] [[<span style ="color:red"><font size="3">Dataset</font></span>](https://github.com/sanzanalora/Ben-Sarc)] [<a style="color:red;" href="#" onclick="$('#nlp_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="nlp_bib" class="bib" style="display:none;">
	<pre>
		@article{Lora_Shahariar_Nazmin_Rahman_Rahman_Bhuiyan_Shah_2024, 
			title={Ben-Sarc: A self-annotated corpus for sarcasm detection from Bengali social media comments and its baseline evaluation}, 
			DOI={10.1017/nlp.2024.11}, 
			journal={Natural Language Processing}, 
			author={Lora, Sanzana Karim and Shahariar, G. M. and Nazmin, Tamanna and Rahman, Noor Nafeur and Rahman, Rafsan and Bhuiyan, Miyad and Shah, Faisal Muhammad}, 
			year={2024}, 
			pages={1–26}
		}
	</pre>
</div>

<div id="nlp_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;font-family:Monaco;"> 
		<font size="3">
			Sarcasm detection research in the Bengali language so far can be considered to be narrow due to the unavailability of resources. 
			In this paper, we introduce a large-scale self-annotated Bengali corpus for sarcasm detection research problem in the Bengali 
			language named ‘Ben-Sarc’ containing 25,636 comments, manually collected from different public Facebook pages and evaluated by 
			external evaluators. Then we present a complete strategy to utilize different models of traditional machine learning, deep learning, 
			and transfer learning to detect sarcasm from text using the Ben-Sarc corpus. Finally, we demonstrate a comparison between the 
			performance of traditional machine learning, deep learning, and transfer learning models on our Ben-Sarc corpus. Transfer learning 
			using Indic-Transformers Bengali Bidirectional Encoder Representations from Transformers as a pre-trained source model has achieved 
			the highest accuracy of 75.05%. The second-highest accuracy is obtained by the long short-term memory model with 72.48% and Multinomial 
			Naive Bayes is acquired the third highest with 72.36% accuracy for deep learning and machine learning, respectively. The Ben-Sarc corpus 
			is made publicly available in the hope of advancing the Bengali Natural Language Processing Community.
		</font>
	</p>
</div>

<!-- Paper 01 -->
📌 [<span style="color:Blue;font-family:Trebuchet MS;">**Explainable Contrastive and Cost-Sensitive Learning for Cervical Cancer Classification**</span>](https://ieeexplore.ieee.org/document/10441352)<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Authors</strong>: Ashfiqun Mustari, Rushmia Ahmed, Afsara Tasnim, Jakia Sultana Juthi, <strong style="color:green">G M Shahariar</strong></font>
</span>
<br>
	<span style="color:black;font-family:Georgia">
		<font size="3"><strong>Conference: </strong><em>26th International Conference on Computer and Information Technology</em></font> ([ICCIT 2023](https://iccit.org.bd/2023/))
	</span>
<br>
[<a style="color:red;" href="#" onclick="$('#iccit_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://arxiv.org/pdf/2402.15905)] [[<span style ="color:red"><font size="3">Code & Dataset</font></span>](https://github.com/isha-67/CervicalCancerStudy)] [<a style="color:red;" href="#" onclick="$('#iccit_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="iccit_bib" class="bib" style="display:none;">
	<pre>
		@INPROCEEDINGS{10441352,
			  author={Mustari, Ashfiqun and Ahmed, Rushmia and Tasnim, Afsara and Juthi, Jakia Sultana and Shahariar, G. M.},
			  booktitle={2023 26th International Conference on Computer and Information Technology (ICCIT)}, 
			  title={Explainable Contrastive and Cost-Sensitive Learning for Cervical Cancer Classification}, 
			  year={2023},
			  volume={},
			  number={},
			  pages={1-6},
			  keywords={Visualization;Costs;Sensitivity;System performance;Self-supervised learning;Cervical cancer;Testing;Cervical Cancer;Cost-Sensitive Learning;Contrastive Learning;SIPaKMeD;XAI;LIME;GradCAM},
			  doi={10.1109/ICCIT60459.2023.10441352}
		  }
	</pre>
</div>

<div id="iccit_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;font-family:Monaco;"> 
		<font size="3">
			This paper proposes an efficient system for classifying cervical cancer cells using pre-trained convolutional neural 
			networks (CNNs). We first fine-tune five pre-trained CNNs and minimize the overall cost of mis-classification by prioritizing 
			accuracy for certain classes that have higher associated costs or importance. To further enhance the performance of the models, 
			supervised contrastive learning is included to make the models more adept at capturing important features and patterns. 
			Extensive experimentation are conducted to evaluate the proposed system on the SIPaKMeD dataset. The experimental results demonstrate 
			the effectiveness of the developed system, achieving an accuracy of 97.29%. To make our system more trustworthy, we have employed 
			several explainable AI techniques to interpret how the models reached a specific decision.
		</font>
	</p>
</div>


## 2023
---------


<!-- Paper 09 -->
📌 [<span style="color:blue;font-family:Trebuchet MS;">**Contrastive Learning for API Aspect Analysis**</span>](https://ieeexplore.ieee.org/document/10298556) (<span style="color:red"><strong>Core A*</strong></span>)<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Authors</strong>: <strong style="color:green">G. M. Shahariar</strong>, Tahmid Hasan, Anindya Iqbal and Gias Uddin</font>
</span>
<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Conference:</strong><em> 38th IEEE/ACM International Conference on Automated Software Engineering</em></font> ([ASE 2023](https://conf.researchr.org/home/ase-2023))
</span>
<br>
[<a style="color:red;" href="#" onclick="$('#ase2023_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://www.researchgate.net/publication/372784896_Contrastive_Learning_for_API_Aspect_Analysis)] [[<span style ="color:red"><font size="3">Code & Dataset</font></span>](https://github.com/shahariar-shibli/Contrastive-Learning-for-API-Aspect-Analysis)] [[<span style ="color:red"><font size="3">Presentation</font></span>](https://www.youtube.com/watch?v=ZB9CMhRz7Pc)] [<a style="color:red;" href="#" onclick="$('#ase2023_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="ase2023_bib" class="bib" style="display:none;">
	<pre>
	  @article{shahariar2023contrastive,
		  title={Contrastive Learning for API Aspect Analysis},
		  author={Shahariar, GM and Hasan, Tahmid and Iqbal, Anindya and Uddin, Gias},
		  journal={arXiv preprint arXiv:2307.16878},
		  year={2023}
		}
	</pre>
</div>

<div id="ase2023_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;font-family:Monaco;"> 
		<font size="3">
			We present a novel approach - CLAA - for API aspect detection in API reviews that utilizes transformer models 
			trained with a supervised contrastive loss objective function. We evaluate CLAA using performance and impact analysis. 
			For performance analysis, we utilized a benchmark dataset on developer discussions collected from Stack Overflow and 
			compare the results to those obtained using state-of-the-art transformer models. Our experiments show that contrastive 
			learning can significantly improve the performance of transformer models in detecting aspects such as Performance, 
			Security, Usability, and Documentation. For impact analysis, we performed empirical and developer study. On a randomly 
			selected and manually labeled 200 online reviews, CLAA achieved 92% accuracy while the SOTA baseline achieved 81.5%. 
			According to our developer study involving 10 participants, the use of 'Stack Overflow + CLAA' resulted in increased 
			accuracy and confidence during API selection.
		</font>
	</p>
</div>

<!-- Paper 08 -->
📌 [<span style="color:blue;font-family:Trebuchet MS;">**Rank Your Summaries: Enhancing Bengali Text Summarization via Ranking-based Approach**</span>](https://arxiv.org/pdf/2307.07392.pdf) <br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Authors</strong>: <strong style="color:green">G. M. Shahariar*</strong>, Tonmoy Talukder*, Rafin Alam Khan Sotez and Md. Tanvir Rouf Shawon </font>
</span>
<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Conference:</strong><em> 2nd International Conference on Big Data, IoT and Machine Learning</em></font> ([BIM 2023](https://confbim.com/))
</span>
<br>
[<a style="color:red;" href="#" onclick="$('#rank2023_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://www.researchgate.net/publication/372404336_Rank_Your_Summaries_Enhancing_Bengali_Text_Summarization_via_Ranking-based_Approach)] [[<span style ="color:red"><font size="3">Code & Dataset</font></span>](https://github.com/TonmoyTalukder/Rank-Your-Summaries-Enhancing-Bengali-Text-Summarization-via-Ranking-based-Approach)] [[<span style ="color:red"><font size="3">Presentation</font></span>](https://shahariar-shibli.github.io/files/BIM2023/Paper-312.pdf)] [<a style="color:red;" href="#" onclick="$('#rank2023_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="rank2023_bib" class="bib" style="display:none;">
	<pre>
		@article{shahariar2023rank,
		  title={Rank Your Summaries: Enhancing Bengali Text Summarization via Ranking-based Approach},
		  author={Shahariar, GM and Talukder, Tonmoy and Sotez, Rafin Alam Khan and Shawon, Md Tanvir Rouf},
		  journal={arXiv preprint arXiv:2307.07392},
		  year={2023}
		}
	</pre>
</div>

<div id="rank2023_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;font-family:Monaco;"> 
		<font size="3">
			With the increasing need for text summarization techniques that are both efficient and accurate, it becomes 
			crucial to explore avenues that enhance the quality and precision of pre-trained models specifically tailored 
			for summarizing Bengali texts. When it comes to text summarization tasks, there are numerous pre-trained transformer 
			models at one's disposal. Consequently, it becomes quite a challenge to discern the most informative and relevant 
			summary for a given text among the various options generated by these pre-trained summarization models. This paper 
			aims to identify the most accurate and informative summary for a given text by utilizing a simple but effective 
			ranking-based approach that compares the output of four different pre-trained Bengali text summarization models. 
			The process begins by carrying out preprocessing of the input text that involves eliminating unnecessary elements 
			such as special characters and punctuation marks. Next, we utilize four pre-trained summarization models to generate 
			summaries, followed by applying a text ranking algorithm to identify the most suitable summary. Ultimately, the summary 
			with the highest ranking score is chosen as the final one. To evaluate the effectiveness of this approach, the generated 
			summaries are compared against human-annotated summaries using standard NLG metrics such as BLEU, ROUGE, BERTScore, WIL, 
			WER, and METEOR. Experimental results suggest that by leveraging the strengths of each pre-trained transformer model and 
			combining them using a ranking-based approach, our methodology significantly improves the accuracy and effectiveness of 
			the Bengali text summarization.
		</font>
	</p>
</div>

<!-- Paper 07 -->
📌 [<span style="color:blue;font-family:Trebuchet MS;">**Gastrointestinal Disease Classification through Explainable and Cost-Sensitive Deep Neural Networks with Supervised Contrastive Learning**</span>](https://arxiv.org/pdf/2307.07603.pdf)<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Authors</strong>: Dibya Nath and <strong style="color:green">G. M. Shahariar</strong></font>
</span>
<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Conference:</strong><em> 2nd International Conference on Big Data, IoT and Machine Learning</em></font> ([BIM 2023](https://confbim.com/))
</span>
<br>
[<a style="color:red;" href="#" onclick="$('#gas2023_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://www.researchgate.net/publication/372417019_Gastrointestinal_Disease_Classification_through_Explainable_and_Cost-Sensitive_Deep_Neural_Networks_with_Supervised_Contrastive_Learning)] [[<span style ="color:red"><font size="3">Code & Dataset</font></span>](https://github.com/dibya404/Gastrointestinal-Disease-Classification-through-Explainable-and-Cost-Sensitive-DNN-with-SCL)] [[<span style ="color:red"><font size="3">Presentation</font></span>](https://shahariar-shibli.github.io/files/BIM2023/Paper-307.pptx)] [<a style="color:red;" href="#" onclick="$('#gas2023_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="gas2023_bib" class="bib" style="display:none;">
	<pre>
		@article{nath2023gastrointestinal,
		  title={Gastrointestinal Disease Classification through Explainable and Cost-Sensitive Deep Neural Networks with Supervised Contrastive Learning},
		  author={Nath, Dibya and Shahariar, GM},
		  journal={arXiv preprint arXiv:2307.07603},
		  year={2023}
		}
	</pre>
</div>

<div id="gas2023_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;font-family:Monaco;"> 
		<font size="3">
			Gastrointestinal diseases pose significant healthcare chall-enges as they manifest in diverse ways and can lead 
			to potential complications. Ensuring precise and timely classification of these diseases is pivotal in guiding 
			treatment choices and enhancing patient outcomes. This paper introduces a novel approach on classifying gastrointestinal 
			diseases by leveraging cost-sensitive pre-trained deep convolutional neural network (CNN) architectures with supervised 
			contrastive learning. Our approach enables the network to learn representations that capture vital disease-related features, 
			while also considering the relationships of similarity between samples. To tackle the challenges posed by imbalanced 
			datasets and the cost-sensitive nature of misclassification errors in healthcare, we incorporate cost-sensitive learning. 
			By assigning distinct costs to misclassifications based on the disease class, we prioritize accurate classification of 
			critical conditions. Furthermore, we enhance the interpretability of our model by integrating gradient-based techniques 
			from explainable artificial intelligence (AI). This inclusion provides valuable insights into the decision-making process 
			of the network, aiding in understanding the features that contribute to disease classification. To assess the effectiveness 
			of our proposed approach, we perform extensive experiments on a comprehensive gastrointestinal disease dataset, such as 
			the Hyper-Kvasir dataset. Through thorough comparisons with existing works, we demonstrate the strong classification accuracy, 
			robustness and interpretability of our model.
		</font>
	</p>
</div>

<!-- Paper 06 -->
📌 [<span style="color:blue;font-family:Trebuchet MS;">**Evaluating the Reliability of CNN Models on Classifying Traffic and Road Signs using LIME**</span>](https://arxiv.org/pdf/2309.05747.pdf)<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Authors</strong>: Md. Atiqur Rahman, Ahmed Saad Tanim, Sanjid Islam, Fahim Pranto, <strong style="color:green">G. M. Shahariar</strong>, and Md. Tanvir Rouf Shawon</font>
</span>
<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Conference:</strong><em> 2nd International Conference on Big Data, IoT and Machine Learning</em></font> ([BIM 2023](https://confbim.com/))
</span>
<br>
[<a style="color:red;" href="#" onclick="$('#traffic2023_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://www.researchgate.net/publication/374236414_Evaluating_the_Reliability_of_CNN_Models_on_Classifying_Traffic_and_Road_Signs_using_LIME)] [[<span style ="color:red"><font size="3">Presentation</font></span>](https://shahariar-shibli.github.io/files/BIM2023/Paper-289.pptx)] [<a style="color:red;" href="#" onclick="$('#traffic2023_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="traffic2023_bib" class="bib" style="display:none;">
	<pre>
		@article{rahman2023evaluating,
		  title={Evaluating the Reliability of CNN Models on Classifying Traffic and Road Signs using LIME},
		  author={Rahman, Md Atiqur and Tanim, Ahmed Saad and Islam, Sanjid and Pranto, Fahim and Shahariar, GM and Shawon, Md Tanvir Rouf},
		  journal={arXiv preprint arXiv:2309.05747},
		  year={2023}
		}
	</pre>
</div>

<div id="traffic2023_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;font-family:Monaco;"> 
		<font size="3">
			The objective of this investigation is to evaluate and contrast the effectiveness of four state-of-the-art pre-trained 
			models, ResNet-34, VGG-19, DenseNet-121, and Inception V3, in classifying traffic and road signs with the utilization 
			of the GTSRB public dataset. The study fo-cuses on evaluating the accuracy of these models' predictions as well as their 
			ability to employ appropriate features for image categorization. To gain insights into the strengths and limitations 
			of the model's predictions , the study employs the local interpretable model-agnostic explanations (LIME) framework. 
			The findings of this experiment indicate that LIME is a crucial tool for improving the interpretability and dependability 
			of machine learning models for image identification, regardless of the models achieving an f1 score of 0.99 on classifying 
			traffic and road signs. The conclusion of this study has important ramifications for how these models are used in practice, 
			as it is crucial to ensure that model predictions are founded on the pertinent image features.
		</font>
	</p>
</div>

<!-- Paper 05 -->
📌 [<span style="color:blue;font-family:Trebuchet MS;">**Interpretable Multi Labeled Bengali Toxic Comments Classification using Deep Learning**</span>](https://ieeexplore.ieee.org/document/10101588) (<span style="color:red"><strong>Best Paper Award</strong></span> 🏆)<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Authors</strong>: Tanveer Ahmed Belal, <strong style="color:green">G. M. Shahariar</strong>, and Md. Hasanul Kabir </font>
</span>
<br>
<span style="color:black;font-family:Georgia">
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
	<p style="text-align:justify; color:black;font-family:Monaco;"> 
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
📌 [<span style="color:blue;font-family:Trebuchet MS;">**Bengali Fake Review Detection using Semi-supervised Generative Adversarial Networks**</span>](https://ieeexplore.ieee.org/document/10236810)<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Authors</strong>: Md. Tanvir Rouf Shawon*, <strong style="color:green">G. M. Shahariar*</strong>, Faisal Muhammad Shah, Mohammad Shafiul Alam, and Md. Shahriar Mahbub</font>
</span>
<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Conference:</strong><em> 5th International Conference on Natural Language Processing</em></font> ([ICNLP 2023](http://www.icnlp.net/index.html))
</span>
<br>
[<a style="color:red;" href="#" onclick="$('#icnlp2023_abstract').toggle();return false;"><font size="3">Abstract</font></a>] [[<span style ="color:red"><font size="3">PDF</font></span>](https://arxiv.org/abs/2304.02739)] [[<span style ="color:red"><font size="3">Presentation</font></span>](https://shahariar-shibli.github.io/files/ICNLP2023/BFRD-Final.pdf)] [<a style="color:red;" href="#" onclick="$('#icnlp2023_bib').toggle();return false;"><font size="3">Citation bib</font></a>] 

<div id="icnlp2023_bib" class="bib" style="display:none;">
	<pre>
		@INPROCEEDINGS{10236810,
		  author={Shawon, Md. Tanvir Rouf and Shahariar, G. M. and Shah, Faisal Muhammad and Alam, Mohammad Shafiul and Mahbub, Md. Shahriar},
		  booktitle={2023 5th International Conference on Natural Language Processing (ICNLP)}, 
		  title={Bengali Fake Review Detection using Semi-supervised Generative Adversarial Networks}, 
		  year={2023},
		  volume={},
		  number={},
		  pages={12-16},
		  doi={10.1109/ICNLP58431.2023.00011}}
	</pre>
</div>

<div id="icnlp2023_abstract" class="abstract" style="display:none;">
	<p style="text-align:justify; color:black;font-family:Monaco;"> 
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
📌 [<span style="color:Blue;font-family:Trebuchet MS;">**Effectiveness of Transformer Models on IoT Security Detection in StackOverflow Discussions**</span>](https://link.springer.com/chapter/10.1007/978-981-19-7528-8_10)<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Authors</strong>: Nibir Chandra Mandal, <strong style="color:green">G. M. Shahariar</strong>, and Md. Tanvir Rouf Shawon</font>
</span>
<br>
<span style="color:black;font-family:Georgia">
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
	<p style="text-align:justify; color:black;font-family:Monaco;"> 
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
📌 [<span style="color:Blue;font-family:Trebuchet MS;">**Assorted, Archetypal and Annotated Two Million (3A2M) Cooking Recipes Dataset based on Active Learning**</span>](https://doi.org/10.1007/978-3-031-34622-4_15)<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Authors</strong>: Nazmus Sakib, <strong style="color:green">G. M. Shahariar</strong>, Md. Mohsinul Kabir, Md. Kamrul, and Hasan Mahmud</font>
</span>
<br>
<span style="color:black;font-family:Georgia">
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
	<p style="text-align:justify; color:black;font-family:Monaco;"> 
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
📌 [<span style="color:Blue;font-family:Trebuchet MS;">**Can Transformer Models Effectively Detect Software Aspects in StackOverflow Discussion?**</span>](https://doi.org/10.1007/978-3-031-34622-4_18)<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Authors</strong>: Nibir Chandra Mandal, Tashreef Muhammad, and <strong style="color:green">G. M. Shahariar</strong></font>
</span>
<br>
<span style="color:black;font-family:Georgia">
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
	<p style="text-align:justify; color:black;font-family:Monaco;"> 
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
📌 [<span style="color:Blue;font-family:Trebuchet MS;">**Automatic back transliteration of Romanized Bengali (Banglish) to Bengali**</span>](https://link.springer.com/article/10.1007/s42044-022-00122-9)<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Authors</strong>: <strong style="color:green">G. M. Shahariar Shibli</strong>, Md. Tanvir Rouf Shawon, Anik Hassan Nibir, Md. Zabed Miandad, and Nibir Chandra Mandal</font>
</span>
<br>
<span style="color:black;font-family:Georgia">
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
	<p style="text-align:justify; color:black;font-family:Monaco;"> 
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
📌 [<span style="color:Blue;font-family:Trebuchet MS;">**Urgent Text Detection in Bengali Language Based on Boosting Techniques**</span>](https://link.springer.com/chapter/10.1007/978-981-19-2445-3_49)<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Authors</strong>: Rafsan Rahman, Tamanna Nazmin, Noor Nafeur Rahman, Miyad Bhuiyan, <strong style="color:green">G. M. Shahariar</strong>, and Faisal Muhammad Shah</font>
</span>
<br>
<span style="color:black;font-family:Georgia">
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
	<p style="text-align:justify; color:black;font-family:Monaco;"> 
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

## 2019
-------
<!-- Paper 01 -->
📌 [<span style="color:Blue;font-family:Trebuchet MS;">**Spam Review Detection Using Deep Learning**</span>](https://ieeexplore.ieee.org/document/8936148)<br>
<span style="color:black;font-family:Georgia">
	<font size="3"><strong>Authors</strong>: <strong style="color:green">G. M. Shahariar</strong>, Swapnil Biswas, Faiza Omar, Faisal Muhammad Shah, and Samiha Binte Hassan</font>
</span>
<br>
<span style="color:black;font-family:Georgia">
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
	<p style="text-align:justify; color:black;font-family:Monaco;"> 
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

