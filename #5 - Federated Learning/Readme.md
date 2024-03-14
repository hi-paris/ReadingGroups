## Edition 5 - Federated Learning

➡️ For the 5th edition of the Hi! PARIS Reading groups, we teach you the Federated Learning.

The edition consists on 2 sessions.
This reading group aims to present an introduction and a survey of federated learning methods in the context of heterogeneous agents, from a statistical perspective.

### Session 1/2 – Statistical heterogeneity in Federated Learning
Tuesday 11 April, 2023 – 2.00-3.30pm (Online)


**📣 Speakers**

* Aymeric Dieuleveut, Hi! PARIS Fellow @École polytechnique

* Constantin Philippenko, PhD @École polytechnique


**📚 Program**

We will describe the Federated Learning context and the causes and types of heterogeneity.  Then, we will study the impact of heterogeneity on learning: from distributed learning to FedAvg, and FedAvg to Scaffold. We will also relate to the case of learning with compression: for example why partial client participation and degrades convergence in the presence of heterogeneity. We will implement the basic methods on simple datasets.

The proposed paper presents the algorithm, which is one of the most critical algorithms from the point of view of heterogeneity and FL. Introduced in 2019, it had a great influence since.

**📑 Papers**

– SCAFFOLD: Stochastic Controlled Averaging for Federated Learning, Sai Praneeth Karimireddy, Satyen Kale, Mehryar Mohri, Sashank Reddi, Sebastian Stich, Ananda Theertha Suresh Proceedings of the 37th International Conference on Machine Learning, PMLR 119:5132-5143, 2020.


**🐍 Presentatin/Notebook/simulations**

– see above


### Session 2/2 – Personalized federated learning for unsupervised learning
Tuesday 13 June, 2023 – 2.00-3.30pm (Online) 


**📣 Speakers**

* Constantin Philippenko, PhD @École polytechnique   


**📚 Program**

The EM algorithm is well-known in machine learning for its use in unsupervised learning problems, such as density estimation and clustering. The proposed paper presents an EM personalized algorithm under the flexible assumption that each local data distribution is a mixture of unknown underlying distributions. This paper was presented in 2021 and has since been widely cited, demonstrating its usefulness. We will introduce the setting of heterogeneous FL, explain what the EM algorithm is, then present its adaptation to federated learning by Othmane et al., 2021, finally, we we will implement this algorithm using the Flower library.


**📑 Papers**

– Federated Multi-Task Learning under a Mixture of Distributions, Othmane Marfoq, Giovanni Neglia, Aurélien Bellet, Laetitia Kameni, Richard Vidal, NeurIPS 2021. 


**🐍 Presentatin/Notebook/simulations**

– see above