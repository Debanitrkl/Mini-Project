# 📽️ Mini-Project
Mini Project for Health and Telemedicine Lab 

# 🚑 SADRAT - Smart Adverse Drug Reaction Assessment Tools

#### 1. History and Motivation
This project was started in Autumn Session 2019 by a research group at [National Institute of Technology Rourkela](https://www.nitrkl.ac.in/)
as part of the course assignment for Health Informatics and Telemedicine Lab, Department of Biomedical Engineering. The motivation behind this research is to improve the performance of the state-of-the-art ML and DL models to detect Adverse Drug Reaction Signals(ADRS) from social media platforms like Twitter using the concept o [**Data Programming**](https://arxiv.org/abs/1605.07723#:~:text=We%20therefore%20propose%20a%20paradigm,are%20noisy%20and%20may%20conflict.) .<br>
**How it might look like:** <br>
**Sample Tweet:** <br>
`Tweet: "Having Headaches since morning! I need to get off of crocin!"` <br>
**Sample Result:**<br>
`ADR Probability: 88%`<br>
`Detected Drug: Crocin`<br>
`Detected ADR: Headache`<br>
This was quite an easy one to guess. But in real scenarios, sentence structures can be very complicated.
One of the major improvements and novelty we want to bring in the pipeline of performing such tasks
is to remove the human involvement in preparing a labelled dataset in order to perform supervised learning,
instead, we want to make the process programming weakly supervised strategies and at the same time reducing the noise generated
during the process to a minimum. The above classification might seem a simple enough task for a 
modern classifier. But, the bigger challenge that we are attempting to solve here are the following:<br>
1. Creating a minimum noise, labelled training set for supervised classification.
2. Removing direct manual involvement in preparing the golden training and testing datasets.
3. Creating a highly scalable programmable alternative to maximize performance and minimize time required to 
generate labelled training sets.<br>
Finally, we would develop a web app around the models to interact with them from the client side.

### 🧑‍💻 Developers
1. 🧑‍🎨 Debabrata Panigrahi
2. 🧔 Rudra Prasad Das
3. 👦 Chiranjit Das
