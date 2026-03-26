Topic Analysis of Synthetic Vietnamese Student Feedback   

📌 Introduction


This project focuses on automating the classification and analysis of prominent topics from student feedback datasets. By leveraging Natural Language Processing (NLP) techniques, the system identifies key issues concerning students, such as teaching quality, curriculum, and campus facilities.

Author: Nguyen Huy Hung

Major: Data Science

Institution: HUTECH University

Advisor: Le Nhat Tung


🛠 Methodology & Technologies

The research implements and compares two primary approaches to topic modeling:

LDA (Latent Dirichlet Allocation): An unsupervised machine learning model used to extract latent topics based on word frequency distributions.

PhoBERT: A state-of-the-art deep learning model pre-trained specifically for the Vietnamese language, providing deeper contextual and semantic understanding.

Key Tools:

Programming Language: Python 

Libraries: Gensim (for LDA), Transformers (for PhoBERT), Scikit-learn, Matplotlib, and WordCloud.


📊 Dataset Overview

Source: Synthetic Vietnamese Student Feedback dataset generated via ChatGPT API to ensure data quality and representation.

Scale: Over 10,000 feedback sentences.

Attributes: Includes sentiment labels (positive, negative, neutral) and topic categories (lecturers, curriculum, facilities).


🚀 Workflow

Preprocessing: Tokenization and text normalization using Vietnamese-specific NLP toolkits.

Vectorization: Utilizing Bag-of-Words (BoW) for the LDA model and word embeddings for PhoBERT.

Model Building: Training the LDA model to discover hidden themes and applying PhoBERT for advanced semantic clustering.

Visualization: Generating Word Clouds and frequency charts to display the most significant keywords for each topic.


📈 Key Findings

The models successfully identified 4 main topic groups: Lecturers, Curriculum, Facilities, and Service Quality.

LDA Performance: Provided a good baseline for grouping by frequency but occasionally struggled with overlapping content or ambiguous topics.

PhoBERT Performance: Demonstrated a superior ability to capture context, especially in long or complex sentences.

⚠️ Limitations & Future WorkLimitations: PhoBERT requires significant computational power and processing time. Initial data cleaning for abbreviations and typos still impacts accuracy.

Future Directions: Integrating the system into real-time online survey platforms. Experimenting with hybrid models or advanced clustering techniques like BERTopic.
