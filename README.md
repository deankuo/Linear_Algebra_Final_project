# Linear_Algebra_Final_project
This repo is for 2023 Linear Algebra and Its Application final project, written by Peng-Ting Kuo.

## Abstract
This study examines the impact of electoral reform in Taiwan in 2005, which shifted from a mixed electoral system of Single Non-Transferable Vote (SNTV) and Proportional Representation (PR) to a combination of Single-Member District (SMD) and PR. Utilizing Non-Negative Matrix Factorization (NMF) algorithm proposed by Lee and Seung, as implemented in the Python Gensim package, this research analyzes the election manifestos across ten legislative terms to uncover latent topics and strategies. The selection of optimal parameters for the NMF model was guided by Topic Coherence scores, settling on 48 topics with a learning rate of 0.8.  

Upon classification, OPENAI's GPT-4 API was employed to generate labels for each identified topic, categorizing them into pork-barrel legislation and programmatic policies based on keywords and region-specific terms, following Catalinac's methodology. Contrary to findings in Japan, the analysis reveals an increase in pork-barrel strategies among Taiwanese candidates post-reform, suggesting a heightened focus on local interests over national policy agendas.  

The study's initial findings underscore the limitations of electoral system changes in shifting legislative candidates' focus towards more programmatic policies. It also highlights the challenges in text analysis using NMF and LDA, where interpretability remains a concern. Future research directions include the exploration of transformer-based models like BERT and RoBERTa, which promise improved text classification and understanding, addressing some of the shortcomings identified in this study.  

## About Notebook
I conduct the modeling and training through the Google Colab Platform (GCP), for more detail please take a look at the jupyter notebook file.  
