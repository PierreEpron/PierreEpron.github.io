## About me

My name is Pierre Epron, I am 29-year old. Currently in my final semester of pursuing a **Master's degree in Natural Language Processing (NLP)** at Nancy. I had the privilege of delving into projects such as **medical report analysis**, honing my skills and understanding of linguistic data. Presently, I am engaged in an internship at **LORIA**, where my focus lies in leveraging **Large Language Models (LLMs)** to enhance the classification of irony. Eager to further delve into the depths of NLP research, I am actively seeking opportunities to pursue a **PhD** in the field.

## Contact

- [pierre.epron@gmail.com](pierre.epron@gmail.com), [pierre.epron@loria.fr](pierre.epron@loria.fr)
- [github](https://github.com/PierreEpron)

## NLP Master Projects

#### Irony Categories

##### Context

- A 6-month project carried out as part of the end-of-Master's NLP internship
- At [LORIA](https://www.loria.fr/en/), [Orpailleur](https://www.loria.fr/fr/la-recherche/les-equipes/orpailleur/), [Synalp](https://synalp.gitlabpages.inria.fr/synalp-website/)
- Between 03/2024 - 09/2024
- Supervised by [Gaël Guibon](https://gguibon.github.io/) and [Miguel Couceiro](https://members.loria.fr/mcouceiro/)
- [github](https://github.com/PierreEpron/irony-categories)

##### Brief

Large Language Models (LLMs) are trained on massive amount of data ([Kaplan et al., 2020](https://www.semanticscholar.org/paper/Scaling-Laws-for-Neural-Language-Models-Kaplan-McCandlish/e6c561d02500b2596a230b341a8eb8b921ca5bf2)), however these data are not filtered and integrate User Generated Content (UGC) which is prone to possess ironic statements. This leads LLMs to incorporate some bias due to irony that can stem from positive sentiment words, interjections or topical words ([Maladry et al., 2023a](https://www.semanticscholar.org/paper/A-Fine-Line-Between-Irony-and-Sincerity%3A-Bias-in-Maladry-Lefever/b45e5b84fe14a0fffef7f6254a57b5f0116ab7e7)). Bias hinders the exploit of emergent abilities from LLMs ([Srivastava et al., 2022](https://www.semanticscholar.org/paper/Beyond-the-Imitation-Game%3A-Quantifying-and-the-of-Srivastava-Rastogi/bd1331b233e84bab7eba503abc60b31ac08e7881)), especially for irony detection and explanation, which prevent their usage for UGC disambiguation, humoristic content generation, or more personified conversational agents. Currently, irony detection is mainly considered as a binary classification task ([Van Hee et al., 2018](https://www.semanticscholar.org/paper/SemEval-2018-Task-3%3A-Irony-Detection-in-English-Hee-Lefever/901c011dd14950c1f14dba5b6b4d17673be3a669); [Maladry et al., 2023b](https://www.semanticscholar.org/paper/The-limitations-of-irony-detection-in-Dutch-social-Maladry-Lefever/010c881b264096a1aecb2843847567e0bc657333)) and studying the strategies underlying the irony expression is yet to be made, even though these strategies are important to decode harmful content using irony from real opinion expression, or even simple humoristic content. An alternative from these strategies comes from the irony categories from SemEval2018 Task 3 subtask A ([Van Hee et al., 2018](https://www.semanticscholar.org/paper/SemEval-2018-Task-3%3A-Irony-Detection-in-English-Hee-Lefever/901c011dd14950c1f14dba5b6b4d17673be3a669)), which actually focuses on a multiclass classification task to classify irony created from a verbal polarity clash, other verbal irony, and situationnal irony. In this internship proposal, we want to focus on exploiting these 3 classes along with their explanation to better identify and control the irony detection’s binary classification task. This comes with many challenges as state-of-the-art models, such as LLMs, are challenging to control.


#### Irony Dectection

##### Context

- A 6-month project carried out during the first semester of the second year of the NLP Masters.
- At [Université de Lorraine](https://www.univ-lorraine.fr/), [IDMC](https://idmc.univ-lorraine.fr/)
- Between 09/2023 - 02/2024 (Half time)
- Supervised by [Gaël Guibon](https://gguibon.github.io/) and [Miguel Couceiro](https://members.loria.fr/mcouceiro/)
- [github](https://github.com/PierreEpron/irony-detection)
- [report](pdf/irony_detection_report.pdf)

##### Brief

Irony is a complex linguistic phenomenon with varying interpretations that poses a challenge for both humans and automated systems. Recognizing irony is crucial, especially in the context of harmful behavior on social media ([Reyes et al. 2012](https://www.semanticscholar.org/paper/From-humor-recognition-to-irony-detection%3A-The-of-Reyes-Rosso/0b447bc717789cf79b8de76b485a763d21c9ed21), [Estrella et al., 2023](https://www.semanticscholar.org/paper/SINAI-at-SemEval-2023-Task-10%3A-Leveraging-Emotions%2C-Rodríguez-Arco/8e9373edc0d06a4fcd841496ee20f5eb9fe3b4e7), [Frenda et al., 2023](https://www.semanticscholar.org/paper/EPIC%3A-Multi-Perspective-Annotation-of-a-Corpus-of-Frenda-Pedrani/8b39640f3ae7fa68c0ec280252eb2ea9ef06d874)). Leveraging recent advancements and a rich irony dataset, this project aims to enhance irony detection using state-of-the- art language models, comparing the performances of traditional Language Models against the performances of Large Language Models (LLMs), using two irony datasets, one focused on the different perspectives of the annotators and the other focused on the different types of irony

#### JusTAL

##### Context

- A 1 year project carried out during the first year of the NLP Masters
- At [Université de Lorraine](https://www.univ-lorraine.fr/), [IDMC](https://idmc.univ-lorraine.fr/)
- Between 09/2022 - 07/2023 (Half time)
- Supervised by [Samuel Ferey](https://www.beta-economics.fr/annuaire/37/ferey_samuel/)
- [github](https://github.com/MR8u/jusTAL)
- [report](pdf/justal_report.pdf)

##### Brief

Constitutional judges play a vital role in modern democracies, particularly in the interpretation and implementation of equality ideals. Since the 1970s, the French Constitutional Council has consistently employed the concept of equality in various forms to evaluate the constitutionality of legislation. Present estimations suggest that approximately half of the Council’s judgments incorporate the principle of equality. The Isovote project seeks to investigate the Council’s evolving philosophy by examining a previously underutilized source the reports of the Council’s debates. Through this research, the objective is to gain insights into how the Council has shaped its philosophy over time. This tutored project is a component of the Isovote project, aiming to analyze a specific corpus to gain a better understanding of the decision-making process of the Constitutional Council (CC). The objective is to characterize, explain, and comprehend the opinions of each councilor, thereby shedding light on the contributions of the CC to the evolution of the French social state and its assessment of legislative texts pertaining to the fight against inequalities.

#### Paperjam
    
##### Context

- A 6-month project carried out during the first semester of the first year of the NLP Masters
- At [Université de Lorraine](https://www.univ-lorraine.fr/), [IDMC](https://idmc.univ-lorraine.fr/)
- Between 09/2022 - 02/2022 (Half time)
- Supervised by [Maxime Amblard](https://members.loria.fr/MAmblard/) and [Miguel Couceiro](https://members.loria.fr/mcouceiro/)
- [github](https://github.com/PierreEpron/paperjam-lab)
- [report](pdf/paperjam_report.pdf)

##### Brief

Identifying scientific articles related to a specific feature is crucial for most researchers and students. The field of Natural Language Processing (NLP) has long been interested in this task. Different Information Extraction (IE) pipelines have been developed for this purpose. Most of them adopt a similar approach. They first extract mentions associated with specific entities such as tasks, materials, metrics, and methods. Then, they arrange them into coreference clusters. Lastly, they establish relationships between these clusters. This article aims to show some of the unresolved issues with that approach, by focusing on an already existing pipeline: SciREX. To achieve this, it was first necessary to set up their methodology, to which a few minor modifications were implemented.

## IA Simplon Projects

#### PET reports

##### Context
- A 1-month project carried out during my apprenticeship at NancyClotep.
- At [CHRU Nancy](https://www.google.com/search?client=firefox-b-d&q=chru+nancy)
- Between 09/2020 - 09/2021
- [github](https://github.com/PierreEpron/pet)
- [report](pdf/pet_report.pdf)

##### Brief

As part of our training as an Artificial Intelligence (AI) developer, I had the opportunity to do my professionalisation contract at the Nancy Brabois Regional University Hospital (CHRU) and at NancyClotep, an interest group in direct contact with the CHRU's nuclear medicine department. The objective was to create a database of Positron Emission Tomography (PET) images. The main aim of this database was to structure and associate key information with the images (pathology, anatomy, etc.). This would subsequently enable different sets of images to be composed and used in computer vision research. To do this, Professor Karcher asked us to try and extract as much relevant information as possible from the medical reports associated with each examination and therefore with each image. Our main approach was to finetune the token classification models provided by the spacy library.

## Education

#### Master NLP

- Between 09/2022 - 09/2024
- At [Université de Lorraine](https://www.univ-lorraine.fr/), [IDMC](https://idmc.univ-lorraine.fr/)
- [link](https://idmc.univ-lorraine.fr/idmc-master-traitement-automatique-langues/) 

#### (RNCP title) Developer in Artificial Intelligence

- Between 01/2020 - 09/2021
- At [Simplon Nancy](https://simplon.co/), [CHRU Nancy](https://www.google.com/search?client=firefox-b-d&q=chru+nancy), [NancyClotep](https://nancyclotep.com/)
- [link](https://www.francecompetences.fr/recherche/rncp/34757/)

#### Literary Baccalaureate 
- Between 09/2011 - 09/2012
- At [Lycée Jeanne D'Arc Nancy](https://www.lyceejeannedarcnancy.com/)

## Former jobs

#### Civic Service: Digital Support
- Between 08/2019 - 01/2020: 
- At [Pôle emploi Cristallerie Nancy](https://www.francetravail.fr/annuaire/votre-agence-francetravail/nancy-cristallerie-54000)

#### Technician Assistant
- Between 08/2016 - 05/2017
- At [INRAE Champenoux](https://www.inrae.fr/centres/grand-est-nancy) 

## Interests

#### NLP

- Computational Linguistics
- Neural Networks
- LLMs
- Knowledge Graphs
- NEAT

#### Computer Sciences

- NEAT (NeuroEvolution of Augmenting Topologies)
- Video game development (Unity C#)
- Web (Vue, React, Flask, Django)

#### Others

- Rôle Playing Game (Game master since 10 years)
- Literature (Hamilton, Bordage, Cixin, Tchaikovsky, Hobb ...)
- Trips (Autralia, Japan, Brasil, Congo ...)