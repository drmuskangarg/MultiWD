# MultiWD
Introducing the MultiWD dataset, a meticulously curated collection of 3281 instances, purposefully created and annotated to enable the identification of multiple wellness dimensions within Reddit posts.

Refer to our research paper for more details on development of the datasets: [MULTIWD: Multiple Wellness Dimensions in Social Media Posts](https://www.techrxiv.org/articles/preprint/MULTIWD_Multiple_Wellness_Dimensions_in_Social_Media_Posts/22816586)

The concept of wellness, as proposed by Halbert L. Dunn, recognizes the importance of multiple dimensions, such as social and mental well-being, in maintaining overall health. Neglecting these dimensions can have long-term negative consequences on an individual's mental well-being. In the context of traditional in-person therapy sessions, efforts are made to manually identify underlying factors that contribute to mental disturbances, as these factors, if triggered, can potentially lead to severe mental health disorders. Our research focuses on introducing a meticulous task aimed at identifying indicators of wellness dimensions and detecting their presence in self-narrated human writings on the Reddit social media platform.

## Dataset schema
**Input**: Text <String> <br/>
**Output**: 6 binary labels for SpA, PA, IA, SA, VA, EA <br/>
  
## Source Code
We provide our source code for BERT baseline model.
